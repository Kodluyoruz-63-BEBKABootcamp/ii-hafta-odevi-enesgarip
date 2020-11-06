#### Github Lisansları

Githubda paylaşılan bir repository'nin gerçekten açık kaynaklı olması için lisanslanması gerekir. Bu sayede diğer kullanıcılara repository'nin kullanımı, değişimi veya dağıtımı konusunda kolaylık sağlar. Çünkü bu lisanslar yazılımın kullanım sınırlarını ve koşullarını belirleyen bir belge niteliği taşır. Birçok lisans tipi vardır fakat en yaygın olarak kullanılan 3 tanesi şunlardır.

* MIT
* Apache
* GNU General Public Licence

**MIT Lisansı** MIT tarafından yayınlanmış bir lisans türüdür. Bu lisansla yazılımı ticari olarak kullanabilir, değiştirebilir, dağıtabilir aynı zamanda hususi olarak kullanabilirsiniz. Bunlara ek olarak lisanslayabilirsiniz fakat yazarı hiç bir şekilde sorumlu tutamazsınız. Telif ve lisansı bulundurmanız zorunludur.



**Apache** neredeyse MIT gibi yazılımı değiştirip kullanabilirsiniz. Fakat yazarı sorumlu tutamazsınız maddesine ek olarak yazarın isimlerini de kullanamazsınız. Aynı zamanda ek olarak yaptığınız değişiklikleri bildirip belirtmeniz gerekmektedir.



**GNU** lisansında ise eğer bu lisansı kullandıysanız yazılımın her yeni versiyonunda bu lisansı sağlamak zorundasınız.



[Bu](https://choosealicense.com/) site lisanslar ve lisanslama konusunda insanlara yardım amaçlı oluşturulan bir sitedir. Bu sayede lisanslama ile ilgili bir problem yaşamadan lisanslama işlemi yapılabilir.

#### Merge-Squash-Rebase

* Merge durumunda bütün commitler yeni bir commit yardımıyla main branch'e eklenir.

![](https://docs.github.com/assets/images/help/pull_requests/standard-merge-commit-diagram.png) 

* Squash and Merge durumunda bütün commitler tek bir commite sıkıştırılır ve default branch'e eklenir.![](https://docs.github.com/assets/images/help/pull_requests/commit-squashing-diagram.png)
* Rebase and Merge durumunda ise tüm commitler ana branch'e merge edilmeden tek tek eklenir. 

#### Agile-Scrum-Kanban

**Agile** bir organizasyonun yeni koşullara uyum sağlama ve yeni iş fırsatları yaratmak için değişime ayak uydurma yeteneğidir. Yazılım geliştirmede kullanılan proje yönetimine özel bir yaklaşımdır. Yazılım geliştirme süreçlerinin öngörülemezliğine cevap verme konusunda yardımcı olur. 

<u>Agile Metodunun Genel Prensipleri</u>

* Müşteriyi memnun etmek ve sürekli yazılım geliştirmek önemlidir. 
* Müşterinin rekabet avantajı için değişen gereksinimler benimsenmelidir. 
* Sık sık çalışan yazılımlar sunmaya odaklanılmalıdır. Teslimat, mümkün olan en kısa sürede yapılmalıdır.
* Geliştiriciler ve iş adamları tüm proje boyunca birlikte çalışmalıdır.
* Projeler motive olmuş insanlarla devam etmelidir. Onlara uygun ortam ve ihtiyaç duydukları destek sağlanmalıdır. İşlerini yapmak için güvende olmalıdırlar. 
* Yüz yüze iletişim, bir takıma bilgi aktarmanın en iyi yoludur. 
* Çalışan yazılım, ilerlemenin birincil ölçümüdür. 
* Çevik süreçler sürdürülebilir kalkınmayı teşvik ederler. Sponsorlar, geliştiriciler ve kullanıcılar belirsiz ve sürekli bir tempoyu koruyabilmelidir.
* Teknik mükemmellik ve iyi tasarıma sürekli dikkat etmek çevikliği artıracaktır. 
* Sadelik, yapılmayan işi en üst düzeye çıkarma sanatı olarak kabul edilir ve esastır.
* Kendi kendine organize ekipler genellikle en iyi tasarımları oluşturur.
* Düzenli aralıklarla, takımın nasıl daha etkili olacağına dair düşünülmeli ve davranışlar buna göre düzenlemelidir.

<u>Agile Metodunun Avantajları</u>

* Kısa planlanmış iterasyonlar ile ani değişimlere ve gereksinimler için organizasyona esneklik tanır.
* Müşteriler ile sürekli iletişim halinde bulunmayı sağlar.
* Ekip katılımı önemli olduğu için sorunlar daha hızlı çözülür.

<u>Agile Metodunun Dezavantajları</u>

* Ürün gereksinimi sürekli değiştiğinden maliyet tahmin edilemez.
* Müşterilerin iletişimde kalacak yeterli zamanı olamayabilir.
* Müşterilerin geri bildirim verirken akıllarına gelebilecek yeni istekler proje süresini ve maliyetini arttırabilir.
* Müşterileri ile iletişimi zor olan kurumsal yapılarda uygulanması daha zordur.



**Scrum** en popüler Agile metodlarından biridir. Kompleks yazılım süreçlerinin yönetilmesi için kullanılır. Bütünü parçalayıp, tekrara dayalı bir yöntem izler. Düzenli geri bildirim ve planlamalarla hedefe ulaşmayı sağlar. Müşteri geri bildirimine göre ilerlendiği için esnek bir yapısı vardır. 3 temel prensibi vardır.

* Şeffaflık; Projenin ilerleyişi, sorunlar ve gelişmeler herkese açık olmalıdır.
* Denetleme; Projenin gelişimi sürekli ve düzenli olarak takip edilir.
* Uyarlama; Proje, yapılabilecek değişikliklere uyum sağlama konusunda sıkıntı çekmemelidir.

<u>Scrum'a Ait Kavramlar</u>

*Product Backlog*, Proje için gerekli olan gereksinimlerin listesidir. Product Owner tarafından müşteriden gereksinimler alınır ve öncelik sırasına göre sıralanır. Product Owner, değişen ihtiyaca göre bu listeye ekleme veya çıkarma yapabilir. Böylece değişime ayak uydurulmuş olunur.

*Product Backlog Item*, Product Backlog içindeki her bir gereksinime denir.

*Sprint*, Proje sprint denilen küçük parçalara ayrılır. Tüm aktiviteler sprint içerisinde gerçekleştirilir. Ortalama 1-2 haftalık süreçlerdir.

*Sprint Backlog*, Sprintlerde bulunan product backlog'daki gereksinimlere denir.

*Scrum Board*, Sprint içerisinde yapılacak olan maddeler burada yönetilir. Yapılacak işler "TO DO" bölümündedir. Bir iş seçildiğinde bu iş "IN PROGRESS" bölümüne aktarılır. Test aşamasına gelindiğinde bu bölümden "TO VERIFY" bölümüne aktarılır. İş kontrol edildikten sonra "DONE" bölümüne getirilerek sonuca varılmış olunur.

*Burndown Chart*, Sprint'in günlerini ve kalan işleri gösteren grafiktir. Şeffaflığı sağlar.

*Product Owner*, Geliştici takımı ile müşteri arasındaki iletişimi sağlar. Product Backlog'u oluşturan kişidir. Bir Sprint'i iptal etme yetkisine sahiptir.

*Scrum Master*, Scrum kurallarını, teorilerini ve pratiklerini iyi bilen ve önceden bu konuda tecrübesi olan kişidir. Takımı rahatsız eden ve çalışmasına engel olan nedenleri ortadan kaldırır.

*Geliştirme Takımı*, Bir Sprint'e alınan bütün işleri tamamalayacak özelliklere sahip kişilerden oluşur. Her bir kişinin tek görevi yoktur. İnteraktif bir şekilde çalışırlar. Projenin geliştirilmesi ile ilgili sorumluluk geliştirme takımına aittir. Genelde 5-7 kişilik gruplardır.

*Sprint Planning*, Belirlenen gereksinimler, bu toplantı ile geliştirme takımı tarafından küçük parçalara ayrılır. Bu toplantıya Product Owner, Scrum Master ve geliştirme takımı katılır. Sprintler bu toplantıda oluşturulur.

*Daily Scrum*, Her gün aynı yerde, aynı saatte yapılan ayak üstü toplantılardır. Bu toplantı ile gelecek 24 saat belirlenir.

*Sprint Review*, Her sprint sonunda sprint'i değerlendirmek için yapılan toplantılardır. Ortaya çıkan ürün gözden geçirilir. Gereksinimlerin sağlanıp sağlanmadığına dikkat edilir.

*Sprint Retrospective*, Sprint boyunca yapılan tüm işlerin kalitesinin, doğruların ve yanlışların değerlendirildiği toplantıdır. Bu toplantı Scrum takımının kendini geliştirmesi için büyük bir fırsat sunar.



**Kanban**, Agile metotlarından biridir. Scrum board gibi Kanban board vardır. "TO-DO", "IN-PROGRESS", "TEST", "DONE" kısımlarına ayrılmıştır. Yapacağımız işi görselleştirip düzenli hale getirmeye yarayan bir tekniktir.



#### Github Flow Avantajları ve Alternatifleri

**Github Flow** hafif bir workflow'dur. Github tarafından 2011 yılında oluşturulmuştur.

<u>Avantajları</u>

* Sürekli entegrasyon avantajı
* Git Flow'a alternatif
* Tek bir versiyonu yönetmek için ideal

<u>Dezavantajları</u>

* Proje çabucak kompleks hale gelebilir
* Çok sayıda versiyon yönetimi için önerilmez



**Git Flow** en popüler ve en bilinen workflow'dur. Vincent Driessen tarafından 2010 yılında oluşturulmuştur. 2 ana branch üzerine kurulmuştur.(master ve develop)

<u>Avantajları</u>

* Projenin yaşam döngüsünde branchlerin daha temiz bir durumda olmasını sağlar.
* Branch isimlendirmeleri proje yönetimini kolaylaştırır.
* Git eklentileri desteği vardır.
* Çok sayıda versiyon yönetimi yapılabilir. 

<u>Dezavantajları</u>

* Git geçmişi çok düzgün okunamaz.
* 2 branche bölünmeden dolayı sürekli üretimi ve entegrasyonu daha zorlu hale gelir
* Tek versiyon için önerilmez.



**GitLab Flow** GitLab tarafından 2014 yılında geliştirilmiştir. Github Flow'dan farklı olarak farklı branchleri vardır. 

<u>Avantajları</u>

* Git geçmişi daha okunaklı ve temizdir.
* Tek versiyon için avantajlıdır.

<u>Dezavantajları</u>

* Github Flow'dan daha kompleksdir.
* Çok fazla versiyonlamada Git Flow kadar karmaşık bir yapıya bürünebilir.



**One Flow** 2015 yılında Git Flow'a alternatif olarak Adam Ruka tarafından üretilmiştir. Git Flow ile arasındaki fark One Flow'da develop branch'inin olmamasıdır.

<u>Avantajları</u>

* Takımın kararlarına göre değişkenlik gösterebilir.
* Tek versiyon için uygundur.
* Git geçmişi daha temizdir.

<u>Dezavantajları</u>

* Sürekli teslim projeler için uygun değildir.
* Feature branch'i sürekli entegrasyonu daha zor hale getirir.
* Çok fazla versiyonlama kısmında iyi değildir.

#### Gang of Four(GOF)

Yaklaşık 25 yıl önce Gang of Four olarak bilinen Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides,**Design Patterns — Elements of Reusable Object-Oriented Software**  adında bir kitap çıkardı. Bu kitapta Design Patterns konusundan bahsedildi. Bu konu yazılım alanında tasarım kalıpları olarak ilk kez ortaya atıldı. Tasarım kalıpları, yazılım tasarımında sürekli karşılaşılan sorunlara çözümler getiren kalıplardır. Nesne yönelimli programlamada nesne ve sınıflar arasındaki ilişkinin en iyi şekilde nasıl olmaları gerektiğini anlatan yöntemlerdir. 3 başlık altında incelenirler. 

![](https://miro.medium.com/max/551/1*m08_ovO1qVVb4pPtlz9CrA.png)

*Creational Design Patterns*, Nesnelerin oluşturulması ve yönetilmesi ile ilgili kalıplardır.

*Structural Design Patterns*, Nesnelerin birbirleri ile olan ilişkilerini düzenleyen kalıpların bulunduğu kategoridir.

*Behavioral Design Patterns*, Birden fazla sınıfın bir işi yaparken birlikte nasıl davranacağını düzenleyen kalıplardır.

#### Interface ve Abstract Sınıflar Arasındaki Farklar 

| Abstract Sınıf                                           | Interface                          |
| :------------------------------------------------------- | ---------------------------------- |
| abstract ve abstract olmayan methodlar                   | sadece abstract methodlar          |
| çoklu inheritance yok                                    | çoklu inheritance var              |
| final, final olmayan, static, static olmayan değişkenler | sadece static ve final değişkenler |
| constructor içerebilir                                   | constructor yok                    |
| is-a ilişkisi                                            | can-do ilişkisi                    |



#### Kaynakça

https://medium.com/@mehmet.baran/yaz%C4%B1l%C4%B1m-lisans-tipleri-mit-apache-gnu-1397af4d1fbb

https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/licensing-a-repository

https://toptalent.co/agile-nedir-agile-metodu-nasil-uygulanir

https://www.acmagile.com/scrum-nedir/

https://www.pem360.com/blog/Agile/Agile-Yontemlerin-Avantajlari-ve-Dezavantajlari/183

https://medium.com/@secilcor/scrum-nedi%CC%87r-6a4326951dd8

https://medium.com/@patrickporto/4-branching-workflows-for-git-30d0aaee7bf

https://deryacakmak.medium.com/tasar%C4%B1m-kal%C4%B1plar%C4%B1-nelerdir-cd216ba47921

https://medium.com/software-development-turkey/abstract-class-ve-interface-aras%C4%B1ndaki-farklar-nelerdir-3c0a4f956eba