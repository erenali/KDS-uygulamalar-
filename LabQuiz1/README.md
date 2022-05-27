# LabQuiz1
Bir firma SSM’den aldığı büyük bir ihaleyi alt yüklenicilere devredecektir. İhaleyi 6 alt projeye bölmüş ve altı ayrı firmadan aldığı tekliflerin bedellerini milyon TL cinsinden aşağdaki tabloda sunmuştur. Risk enküçüklemek için firma, altı projenin her birini bir alt yüklenici firmaya verecektir. Projeler firmalar arasında bölünemez. Projelerin firmalara atanmasında toplam bedelin enküçük olması arzu edilmektedir.

Bu problemin 1. excel dosyasında solver ile çözümü sağlanmıs. 2. dosyada ise makro kaydedici kullanılarak makro ile çözümü sağlanmıştır.


Makro aşağıdaki gibidir. Excel alanların isimlendirilmelerinin koddaki şekilde yapılması önemlidir.

Sub EnKBedel()
'EnKBedel Makro
SolverReset
SolverOk SetCell:="EnKHedef", MaxMinVal:=2, ValueOf:=0, ByChange:="Karar", _
    Engine:=2, EngineDesc:="Simplex LP"
SolverAdd CellRef:="SolT", Relation:=2, FormulaText:="SagT"
SolverAdd CellRef:="AltT", Relation:=2, FormulaText:="UstT"
SolverAdd CellRef:="Karar", Relation:=5, FormulaText:="ikili düzen"
SolverSolve
End Sub
