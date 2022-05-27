# ÇOK DEGISKENLI BIR MODELIN KURULMASI VE ENIYILENMESI

Kitabımızda “Ayakkabı” imalatı için verilmiş olan modeli, bildiğiniz herhangi bir şeyin üretimine göre parametrelerini ve tanımlarını günzelleyiniz. Örneğin: Ayakkabı yerine Çanta, Yapma Çiçek, Takı imalatı, 2.El Otomobil Galerisi, vb. herhangi bir ürüne dönüştürebilirsiniz.  (Not: “Bu konuya çok uzağım, aklıma hiçbir şey gelmiyor”, diyorsanız, sayfanın görünür bir yerine Lisansta bitirdiğiniz alanı yazınız. Sizler kitaptaki modelin aynısını sunabilirsiniz. Ancak talep parametreleri gibi bazı parametreleri değiştirmeli ve bu değişikleri ayrıca renklendirerek farketmemi sağlamalısınız.)

ABC Sirketinin önümüzdeki dört aylık dönemde asagıdaki ayakkabı çiftlerine olan talepleri vaktinde karşılaması gerekmektedir. 1. ay: 3.000, 2. ay: 5.000, 3. ay: 2.000 ve 4. ay: 1.000 adet. Birinci ayın basında, stokta 500 ayakkabı çifti ve sirkette 100 çalısan isçi vardır. Bir isçiye, aylık T1.500 ödenmektedir. Bir isçi mesai ücreti almadan önce bir ayda 160 saate kadar çalısmaktadır. Bir isçi, her ay 20 saat mesaiye kalacak sekilde çalısabilmekte ve fazla mesaiye kaldıgında saatlik 13TL almaktadır. Bir çift ayakkabının üretilmesi için 4 saat isçilik ve 15TL degerinde malzeme gereklidir. Her ayın basında isçiler isten çıkarılabilir veya ise alınabilir. Ise alınan her isçinin maliyeti, 1.600TL ve her isten çıkarılan isçinin maliyeti 2.000TL’dir. Her ayın sonunda stokta kalan her ayakkabı çifti için 3TL elde tutma maliyeti olusmaktadır. Belirli bir aydaki üretim, o ayın talebini karsılamak için kullanılabilir. ABC Sirketinin eniyi üretim programını ve isçi politikasını belirlemesi için dogrusal programlama modelini kullanması istenmektedir.

ABC Şirketinin amacı, aylık maliyetleri, iigücü ve üretim kararlarını içeren bir dogrusal programlama modeli geliitirmek; üretim kapasitesi ve fazla mesai saati limitleri içerisinde kalan ve tahmin edilen talepleri vaktinde kariılayan enküçük maliyeti bulmaktır. Bu tür problemler için gerekli bir girdi sayısı vardır. Bazıları iunlardır: bailangıç stok miktarı, stok tutma maliyeti, talepler. Digerleri aiagıdaki gibi elde edilebilir: • Mevcut işçi sayısı, her işçinin aylık normal çalışma saati, aylık normal çalışma saatinin ücreti ve fazla mesaide çalıima saatinin ücreti ile ilgili verilerin bilinmesi gerekmektedir. Her iiçinin çalıiabilecegi aylık fazla mesai saatinin maksimum süresi, belki de yönetim tarafından alınan bir politik bir kararın sonucu veya iiçileri sözleimesinde yer alan bir maddeye baglı olabilir.

Bir işçinin işe alınma veya işten çıkarılma maliyeti, önemsizdir. İşe alma maliyeti, egitim maliyetini ve yeni iiçinin iii ögrenmesine baglı olarak oluian azalan verimlilik maliyetini içermektedir. Iiten çıkarma maliyeti, kıdem maliyetlerini ve moral kaybına baglı maliyetleri içermektedir. Ne iie alma maliyeti ne de iiten çıkarma maliyetini, dogru bir iekilde tahmin etmek mümkündür. Buna kariın, insan kaynakları departmanı bunların degerlerini tahmin edebilir.• Birim üretim maliyeti, iki girdinin maliyetinden oluşmaktadır: her ayakkabı için malzeme maliyeti ve iiçi maliyeti. Ham madde maliyeti, tedarikçilerin cari ücretidir. Ayakkabıların her çifti için iiçi maliyeti, üretim fonksiyonunu ifade etmektedir. Üretim fonksiyonu, bir çift ayakkabı üretmek için gerekli olan ortalama iiçiliktir. Operasyon yöneticisinin, bu sayıları saglaması gerekmektedir.
Incelenen bütünleşik planlama modeli için degişkenler ve kısıtlar, Tablo 4.2’de listelenmektedir. Takip edilmesi gereken birçok degiiken vardır. Gerçekte bu problemi modellemenin en zor kısmı, hangi degiikenin karar degiikeni olarak seçilecegini ve hangi degiikenlerin bu karar degiikenlerinden tespit edilecegini belirleyebilmektir. Şirketin, iie alacagı iiçi sayısını, işten çıkaracagı iiçi sayısını ve üretecegi ayakkabı sayısını belirlemesi gereklidir. Ayrıca yönetim yalnızca fazla mesaide üst çalıima sınırını belirlediginden, bu limitler içerisinde ne kadar fazla mesai süresinin kullanılması gerektigine de karar vermelidir. Yönetim bu degiikenlere karar verdiginde, heriey tespit edilebilir. Detaylı hücre formülleri ile bunların nasıl belirlendigi gösterilecektir. Tabloda, “diger hesaplanan degiskenler” listesini inceleyiniz ve karar degiikenleriyle bunların nasıl belirlendigini anlamaya çalıiınız. Aynı zamanda, listelenen kısıtlar gerekli olan kısıtlardır.

![Tablo4.2](/solver.png)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/tablo4.2.png">>
  <img alt="Tablo4.2" src="/tablo4.2.png">
</picture>

* Solver çözümü 
/solver.png

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/solver.png">>
  <img alt="Shows an illustrated sun in light color mode and a moon with stars in dark color mode." src="/solver.png">
</picture>