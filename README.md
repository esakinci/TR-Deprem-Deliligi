# TR Deprem Deliligi
![](/William_Blake_-_Nebuchadnezzar.jpg)
 Depremden korun(a)mayan bir ülkenin vatandaşı olarak; her gün bunun derdiyle yaşarken ve taşınacak ev ararken belki biraz daha az delirmemize sebep olabilecek, bir bilgi bankası projesidir.
## Projenin İçeriği
Sağlam ev nasıl anlaşılır? Eviniz doğru materyallerden yapılmış mı nasıl anlarız? gibi bilgilere burada yer verilmemiştir. Bu konuda her bina değişkendir ve belirli testlerin bilir kişiler tarafından yapılırsa ancak anlaşılabilecek bir şeyi burada barındırmak ve tartışmaya yol açmak yersizdir. 

Onun yerine zemin bilgisi ve hangi şartlarda binalar daha tehlikededir, depremden zarar görmeye açıktır hususunda araştırmaları kapsar. Bu bile aslında belirsizlik barındırır. %100 emin olmak için saha çalışmaları ve bu konuda çeşitli datalar elde etmek zorundasınız!
#### **DİKKAT!!**
>**Bu sebeple buradan edindiğiniz bilgiler ile seçtiğiniz evin lokasyonu hakkında herhangi bir sağlamlık iddiası bulunmamaktadır! [Bkz lisans](/LICENSE). Bu sebeple buradan elde edilmiş bilgilerle yapılan seçimleriniz yalnızca sizi bağlar.**

Google Earth yer imleri kullanılarak: Türkiye üzerinde bulunan jeoloji yapısına ait resimler, eski haritalar, çeşitli simulasyonlara ait risk haritalarına ait imajların yerleştirilerek, gözlemler ve karşılaştırmalar yapabilme olanağını elde edebiliyoruz. 
Bu bağlamda Google Earth'e yerleştirilen bu imajların elle yerleştirilmiş olduğu ve 1 pixellik bir sapmanın 100'lerce metre kayabileceği göz önünde bulundurulmalıdır! Bu konuda benim yaptığım işi GE'ye entegre edene kadar [bu çalışmadan](https://mapelse.github.io/istanbulJeoloji/) faydalanılabilir. Ayrıca jeoloji haritalarının kaynağı olan [MTA'nın bu web haritası](http://yerbilimleri.mta.gov.tr/anasayfa.aspx) benim kendi elimle yerleştirdiğim imajlardan daha isabetli ve konforlu bir deneyim sunacaktır.  

Projeye İBB'nin risk tespit haritaları da eklenmiştir. GE çıktısı içerisinde isimlendirmeleri ile ne olduğu anlaşılmaktadır. Ayrıca başka bir Github kullanıcısının yine İBB'nin hasar riski tabloları üzerinden faydalanarak yayınladığı güzel bir harita projesine rastladım. [Buradan paylaşıyorum.](https://github.com/alicangnll/ibb-istanbul-depremi-tahmini-2021)

Kadıköy belediyesinin bir [haritasına](https://webgis.kadikoy.bel.tr/keos/?p=ABIS6_ITRF96) rastladım. Bu bölgede eve çıkmak istenirse faydalanılabilir.

#### Google Earth versiyonunda neler var?
+ [Prof. Cenk Yaltırak](https://www.researchgate.net/profile/Cenk-Yaltirak)'a ait bir çalışma olan yeni nesil sismik simulasyon'un imajları.
+ Eski İstanbul haritaları. 
+ İBB zemin etüd ve risk analiz haritaları.
+ Jeoloji haritası.

#### Bu bilgiler ne işimize yarayacak?
+ Simulasyonlardan: evim ne kadar fazla sallanır, ne kadar tehlikedeyim? Bir fikir elde ederiz. Mütheait'e ve ustalara ne kadar güvenmemiz gerektiğine dair kafamızda bir ölçek oluşur.
+ Eski haritalardan: yerleşim yerleri eskiden nerelere konudurulmaya uygun görülmüş, eski akarsular nerelerdedir? (Ayrıca eğlenceli :+1: *Eskiden buralar hep dutluktu..*)
+ Jeoloji haritası: Zemin'in karakteri, çeşitliliği, şekli hakkında bilgilenebiliriz.

### Google Earth Yer İmleri Çıktısı
Google Earth bilgisayarınızda kurulu değilse [önce kurunuz](https://support.google.com/earth/answer/21955?hl=tr). Çıktı repo içerisinde "output" klasörü içinde TR-DD-BB.kmz uzantısı olarak konumlanmıştır.

### Overlay Yer İmleri Hakkında Önemli Notlar
+ İmajların bulundukları yere, **el yordamı ile göz kararı yerleştirildiklerinin farkında olun!** :frowning_man:
+ Eğer overlay imajı, odaklandığınız bölgeye tam olarak oturmadığını fark ediyorsanız, imajın pozisyonu, scale ve rotasyonunu kendiniz ayarlayabilirsiniz. Sağ click yapıp özellikler sekmesini açınca harita üzerinde düzenleme moduna giriyor.

## Kaynakları Anlamlandırabilmek İçin Bazı Notlar
+ Ev sulak arazide olmayacak. Eski bir dereyatağına yakın olmayacak. Zeminin kendisi jeolojik olarak sağlam kabul edilen türden olacak. Faydan ne kadar uzak o kadar iyi. 
+ İBB Zemin'in paylaştığı, [PDF dosyası](/sources/iSTANBUL-iL-ALANI-JEOLOJiSi-YoNETiCi-oZETi_2013.pdf) içerisinde İstanbul'a ait zemin tiplerine dair tanımlamalar ve açıklamalar vardır. 81. sayfada V.1.2 başlığı ile beraber İstanbul üzerinde bulunan zeminler hakkında önemli bir yorumlama bulunuyor. Koca PDF yi gözden geçirmeden evvel, direkt olarak bir bilinç kazanmak adına bakılabilir. 
+ Bu [resim](/sources/İstanbul-toprak-zemin-harita.JPG), bu [PDF içinden](/sources/İstanbul-Zemin-ve-Ev-fiyatları-ilişkisi.pdf) alınmıştır. Bkz "4.2. İstanbul ve İlçelerindeki Zemin Formasyonları".
+ Jeoloji haritaları incelenirken her bir harita parçası içindeki simgeler ve renkler farklılık gösterebilir. Bunu dikkate alarak kontrol edin.
+ Prof. Cenk Yaltırak'ın simulasyonunu ve faylar hakkındaki çalışmasının detaylı anlatımı [bu videoda](https://youtu.be/_2cvfFWN56E) bulunabilir. Video biraz uzun! Ancak kendisi Marmara hakkında uzman bir bilimci ve yaptığı çalışmanın ciddiyetini, detay seviyesini ve konuya dair tahminlerindeki tutarlılığı hakkında net açıklamaları var. Hocamız, simulasyonlarında yıkım 0.2g den başlıyor demektedir. Yaptığı çalışmada yüksek çözünürlüklü bina ivme datası toplanırsa, hangi binaların gerçekten yenilenmesi gerektiğinin tespitini yapabileceğini anlatıyor.
+ İstanbulda kırılmaya müsait 3 farklı fay olduğunun farkında olunması gerekir. Prof. Cenk Yaltırak'ın simulasyon görsellerinin farklı MW değerli görselleri var. Bunlar farklı fayların, farklı şiddetler üretme potansiyeli ile üreteceği ivmenin simulasyonları. Öngörülen şiddet değerleri belirli bir tarihte (2023) üretildiği için, fayların kırılmadığı her geçen zamanda MW değeri değişebilir diye tahmin ediyorum.
+ Söylenene göre İstanbul depremine hazırlık; Cenk Yaltırak simulasyonlarındaki Fatih-Bağcılar'ın altına denk düşen fay'ın 7.4mw hareketine hazırlandığı iddiası var. 

## Kaynaklar
+ https://mapelse.github.io/istanbulJeoloji/
+ https://www.mta.gov.tr/
+ https://depremzemin.ibb.istanbul/
+ https://youtu.be/_2cvfFWN56E
+ https://github.com/alicangnll/ibb-istanbul-depremi-tahmini-2021