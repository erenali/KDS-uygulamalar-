# Topsis Örneği

Yeşil tedarikçi seçim problemi için TOPSIS yöntemiyle en uygun tedarikçinin seçilmesi amaçlanmıştır. Aday tedarikçiler için tabloda 5 ana kriter belirlenmiştir. Seçeneklerin önem sırasını ve karar vericinin hangi seçeneği benimsemesi gerektiğini belirleyen bir işlemtablosu yönelimli karar destek sistemi geliştiriniz. Geliştireceğiniz çok-ölçütlü karar destek sistemi, tedarikçi bilgileri ve ağırlıklar değiştiğinde yeni seçeneği göstermelidir. Excel dosyanızın adı Topsis(Adriana-Gigi-Bella).xlsm şeklinde olmalıdır (Bir kişi için ad ve soyad, 2 ve 3 kişi için sadece adlarınızı kullanınız.


* Topsis yönetimde elimizde bulunan verilerin sutun karelerinin toplamın kareköküne oranı ilgili alanın Standart Karar Matrisi değerini verecektir.
* Bulunan bu değerlerin ağırlık katsayıları ile çarpılması sonucu Ağırlıklaştırılmış Karar Matrisinin oluşturulması sağlanır.
* Bu matristeki max ve min değerleri ile ölçütün maksimal/minimal yaklaşımına göre Pozitif ideal/ Negatif ideal değerleri belirlenir.
* İlgili ölçütün tüm değerlerin pozitif ideal değerinden farkının karelerinin karekökü ve negatif ideal değerinden farkının karelerinin karekökü ayrı ayrı hesaplanır ve S+ / S- değerleri bulunur.
* Son olarak S+/(S+ + S-) çözümü ile nihai sonuçlar bulunur ki. Bu değere göre en iyi en kötü seçimler belirlenebilir.