# Thunderbird+ #

<<<<<<< HEAD
* Yazar: Pierre-Louis Renaud (Thunderbird 78 - 102) & Cyrille Bougot (TB 102), Daniel Poiraud (TB 68 - 91), Yannick (TB 45 - 60);
* URL: [Kullanım kılavuzu][4] ;
  [RPTools.org'daki değişikliklerin geçmişi][5] ;
  [İletişim Fransızca ve İngilizce][6];
* [Kararlı sürümü indirin][1]
* [RPTools.org'daki en son sürümü][3]
* NVDA uyumluluğu: 2019.3 ve üzeri;
* Thunderbird uyumluluğu: 102.x sürümleri;
* [RPTools.org'daki değişikliklerin geçmişi][3]
* [gitHub'daki kaynak kodu][2]

Not 1: Bu Eklenti, Mozilla Apps Enhancements Eklentisiyle uyumlu değildir. İkincisi kuruluysa, ThunderbirdPlus'ı kurmadan önce onu devre dışı bırakmalı veya kaldırmalısınız;

Not 2: Bu belge Fransızcadan Türkçeye Google Translate tarafından çevrilmiştir. İnsan tarafından tercüme edilmiş bir versiyon yakında gelecek.

## Tanım

Bu eklenti, Mozilla Thunderbird posta istemcisini NVDA ile kullanmanın kolaylığını ve verimliliğini büyük ölçüde artırır.

İyileştirmeler aşağıdaki yönlerle ilgilidir:

### İşitme konforu

* "Falanca istendi alındı" uyarıları bir seçenek aracılığıyla devre dışı bırakılabilir;
* "Bu bir taslaktır" ve "Thunderbird bu mesajın sahte olduğunu düşünüyor" uyarıları dikkate alınmaz;
* Seçenekler, posta listelerinin adlarının duyurulmasını devre dışı bırakmayı, "RE" ifadelerini kaldırmayı veya gruplandırmayı ve sayıları ve diğer garip özel karakterleri kaldırarak muhabirlerin adlarını saflaştırmayı mümkün kılar;

### Ana pencerede gezinme

* Bir sonraki panele geçiş TAB tuşu kullanılarak yapılırken, escape tuşu bir önceki panele dönmenizi sağlar. Bu, F6 ve Shift+F6'dan daha rahattır.
* Control+Tab ve Control+a sayısı ile sekme seçme bu örnekteki gibi seslendirilir: Sekme 1/4, Gelen posta;
* Bir klavye kısayolu, kolayca etkinleştirmek için bir menüdeki sekmeleri listelemenizi sağlar;
* Sekme çubuğunun bağlamsal menüsünü görüntülemek için bir klavye kısayolu kullanılır;

### Klasör ağacı

* alt+aşağı ok ve Alt+yukarı ok, okunmamış mesajların bulunduğu klasörler arasında gezinir;
* Bir harf veya rakam yazıldığında, adı yazılan karakterle başlayan bir sonraki klasör seçilir. Shift tuşu ile hareket aşağıdan yukarıya doğrudur. Ayrıca klasörün ait olduğu hesabın adı duyurulur;
* Okunmamış mesajların bulunduğu bir klasördeki Space tuşu, mesaj listesindeki ilk okunmamış mesajı seçer;
* İki hesap iletişim kutusu ve ilişkili klasörleri, bunların anahtar kelimeye göre filtrelenmesine veya yalnızca okunmamış mesajların bulunduğu klasörlerin görüntülenmesine izin verir;

### Mesaj listesi

* Sütunların seçimi ve mesaj listesindeki düzenlemeleri basit bir iletişim kutusu aracılığıyla erişilebilir hale getirilir;
* Mesaj listesinin sütunlarına danışma: kısayollar, alfasayısal klavyede bir sayıya basarak gönderenin adını, konuyu veya mesajın tarihini tekrar dinlemenize, hecelemenize veya kolayca kopyalamanıza olanak tanır: örneğin, 1 veya & göndereni duyurur, 2 basış adı heceler ve 3 basış panoya kopyalar;
* F8 ile görüntülenen başlıklar bölmesinin başlıklarına danışma: Alt+bir sayı ile, 1 basış gönderici veya alıcıların adreslerini içeren bir başlığı söyler, 2 basış kopyalanmalarını sağlayan bir iletişim kutusu açar, 3 basış bağlamsal açar başlıkla ilişkilendirilmiş yerel Thunderbird menüsü;
* Boşluk, Alt+aşağı ok veya F4 ile mesaj metninin temiz hızlı önizlemesi: mesaj alıntılarındaki büyük blok başlıkları "Gönderenin adı yazdı" ifadesiyle değiştirilir. NVDA, uzun bağlantı adresi yerine "tıklanabilir bağlantı"yı da duyurur.
* Alıntıların kronolojik sırayla, aşağıdan yukarıya, Shift+Boşluk, Alt+yukarı ok veya Shift+F4 ile hızlı görünümü;
* Alt+sonraki sayfa kısayolunu veya alfanümerik klavyede 1 sayısını kullanarak eklere kolay erişim;

### Hızlı filtre çubuğu ve öncelikli etiket yönetimi

* Dikey okları kullanarak Filtre seçenekleri arasında gezinmek mümkündür. Enter tuşu, bir seçeneği işaretlemenizi veya işaretini kaldırmanızı sağlar;
* etiket ekleme veya kaldırma, alfanümerik klavyede Shift+a sayı tuşlarına basılarak yapılır. Örneğin, bir mesaja "Yapılacaklar" etiketini eklemek için 4'e basın. Ardından, artık erişilebilen hızlı filtre çubuğu aracılığıyla mesajların listesini etiketlere göre filtreleyebilirsiniz;


### Mesaj oluştur penceresi

Alt+1, Göndereni, Alt+2 alıcıyı, Alt+3 ekleri vb. duyurur. İki basış, odağı bu alanlardan birine yerleştirir;

### Yazım denetimi iletişim kutusu:

* yanlış yazılan kelime, önerilen kelimeden önce heceli veya hecesiz olarak duyurulur. NVDA+Tab veya Alt+yukarı ok kısayolları, yanlış yazılan ve değiştirilen sözcükleri duyurur: 1 tıklama sözcükleri normal hızda heceler, 2 dokunma sözcükleri hızlı heceler, 3 dokunma yanlış yazılmış sözcüğü başka bir düzenleme alanında analiz edilmek üzere panoya kopyalar;
* enter tuşunun çeşitli kombinasyonları Değiştir, Tümünü değiştir, Yoksay, Tümünü yoksay veya Sözcüğü sözlüğe ekle düğmelerini etkinleştirir, bu iletişim kutusunun daha rahat olması için eklenmiştir;

### Otomatik güncelleme

ThunderbirdPlus, devre dışı bırakma/yeniden etkinleştirme ve erteleme seçenekleriyle bağımsız bir otomatik güncelleme sistemine sahiptir;

### Chichi ile ikili operasyon

ThunderbirdPlus, doğrudan Thunderbird'e yüklenen bir eklenti olan Chichi ile sorunsuz çalışacak şekilde tasarlanmıştır.

Bu [Chichi'nin sayfası][7] hakkında bilgi edinin;


[1]: https://www.nvaccess.org/addonStore/legacy?file=thunderbirdPlus

[2]: https://github.com/RPTools-org/ThunderbirdPlus/

[3]: https://www.rptools.org/?p=8610

[4]: https://www.rptools.org/NVDA-Thunderbird/get.php?pg=manual&lang=tr

[5]: https://www.rptools.org/NVDA-Thunderbird/get.php?pg=changes&lang=tr

[6]: https://www.rptools.org/NVDA-Thunderbird/toContact.html

[7]: https://www.rptools.org/NVDA-Thunderbird/get.php?pg=chichi&lang=tr
=======
* Yazarlar: Pierre-Louis Renaud (Thunderbird v. 78 - 102), Daniel Poiraud
  (TB v. 68 - 91), Abdelkrim Bensaïd for TB 78, Yannick (TB v. 38 - 60)
* [Kullanım kılavuzu
  Bağlantısı:](https://www.rptools.org/Outils-DV/NVDA-ThunderbirdPlus-en.html)
  , [Fransızca veya İngilizce iletişim
  için](https://www.rptools.org/Outils-DV/contact.html)
* [Kararlı sürümü indirin][1]
* [En son sürümü RPTools.org'dan indirin][2]
* NVDA Uyumluluğu: 2019.3 ve sonrası
* Thunderbird uyumluluğu: 102.x sürümleri;
* [GitHub'daki kaynak kodu][3]

Not: Bu eklenti, Mozilla Apps Enhancements eklentisi ile uyumlu
değildir. Mozilla Apps Enhancements eklentiniz yüklüyse, bunu kullanmadan
önce onu devre dışı bırakmalı veya kaldırmalısınız;

Bu eklenti, Mozilla Thunderbird posta istemcisini NVDA ile kullanmanın
erişilebilirliğini, verimliliğini ve rahatlığını büyük ölçüde artırır.

## İşitme konforu

* "Şu veya bu şekilde istenen onay" uyarıları bir seçenek aracılığıyla devre
  dışı bırakılabilir;
* "Bu bir taslaktır" ve "Thunderbird bu iletinin sahte olduğunu düşünüyor"
  uyarıları basitçe göz ardı edilir;
* Seçenekler, posta listelerinin adlarının duyurulmasını devre dışı
  bırakmayı, "RE" ifadelerini kaldırmayı veya gruplandırmayı, sayıları ve
  diğer garip özel karakterleri kaldırarak karşılık gelenlerin adlarını
  saflaştırmayı mümkün kılar;

## Geliştirilmiş gezinme

* Bir sonraki panele geçiş TAB tuşu kullanılarak yapılırken, escape tuşu bir
  önceki panele dönmenizi sağlar. Bu, F6 ve Shift+F6'dan daha rahattır.
* İki hesap iletişim kutusu ve ilişkili klasörleri, bunların anahtar
  kelimeye göre filtrelenmesine veya yalnızca okunmamış iletilerin bulunduğu
  klasörlerin görüntülenmesine izin verir;
* Klasör ağacında alt+aşağı ok ve Alt+yukarı ok, okunmamış mesajların
  bulunduğu klasörler arasında gezinmenizi sağlar;
* Yine klasör ağacında, bir harf veya sayı girildiğinde, adı yazılan
  karakterle başlayan bir sonraki klasör seçilir. Shift tuşu ile hareket
  aşağıdan yukarıya doğrudur. Ayrıca klasörün ait olduğu hesabın adı
  duyurulur;
* Okunmamış mesajların bulunduğu bir klasörde, Boşluk tuşu listedeki ilk
  okunmamış mesajı seçer;

## İleti listesinde

* Sütun seçimi ve ileti listesindeki düzenlemesi basit bir iletişim
  kutusuyla erişilebilir hale getirilir;
* İleti listesinin sütunlarına danışma: alfanümerik klavyede bir sayıya
  basarak bir iletiyi tekrar dinlemenizi, gönderenin adını, konuyu, tarihi
  hecelemenizi veya kolayca kopyalamanızı sağlar: örneğin, 1 veya &
  göndereni duyurur, 2'ye basıldığında ad hecelenir ve 3'e basıldığında
  panoya kopyalanır;
* F8 ile görüntülenen başlıklar bölmesinin başlıklarına danışma:
  Alt+herhangi bir sayısal rakama, 1 basışta gönderenin veya alıcıların
  adreslerini içeren bir başlık konuşur, 2 basışta bunların kopyalanmasını
  sağlayan bir iletişim kutusu açılır, 3 basışta başlıkla ilişkili yerel
  Thunderbird bağlam menüsü açılır;
* İleti metninin boşluk, Alt+aşağı ok veya F4 ile hızlı önizlemesini
  temizleyin: ileti tırnak işaretlerindeki büyük blok üstbilgileri
  "Gönderenin adı yazdı" ifadesiyle değiştirilir. NVDA ayrıca uzun bağlantı
  adresi yerine "tıklanabilir bağlantı" duyuracaktır.
* Alıntıların kronolojik sırayla, aşağıdan yukarıya, Shift+Boşluk,
  Alt+yukarı ok veya Shift+F4 ile hızlı görünümü;
* Alt+sayfa aşağı kısayolunu veya alfanümerik klavyede 1 sayısını kullanarak
  eklere kolay erişim;
* Hızlı filtre çubuğu erişilebilir hale getirildi ve öncelikli etiket
  yönetimi basitleştirildi:

	* Yukarı/aşağı ok tuşlarını kullanarak Filtre seçenekleri arasında gezinmek
	  mümkündür. Enter tuşu, bir seçeneği işaretlemenizi veya işaretini
	  kaldırmanızı sağlar;
	* Öncelik etiketlerinin eklenmesi veya kaldırılması, alfanümerik klavyede
	  Shift+bir sayıya basılarak yapılır. Örneğin, bir mesaja "Yapılacaklar"
	  etiketini eklemek için 4'e basın. Daha sonra, artık erişilebilir olan
	  hızlı filtre çubuğu aracılığıyla ileti listesini etiketlere göre
	  filtreleyebilirsiniz;
	
	## İleti oluştur penceresi

* Alt+1, Göndereni, Alt+2 alıcıyı, Alt+3 ekleri vb. duyurur. İki kez basmak,
  odağı bu alanlardan birine ayarlar;
* Yazım denetimi iletişim kutusunda:

	* yanlış yazılan sözcük, önerilen sözcükten önce duyurulur. NVDA+Sekme veya
	  Alt+yukarı ok kısayolları yanlış yazılmış ve değiştirilen sözcükleri
	  duyurur: 1 dokunuşla sözcükler normal hızda yazılır, 2 dokunuş sözcükleri
	  hızlı heceler, 3 dokunuşla yanlış yazılan sözcüğü başka bir düzenleme
	  alanında analiz edilmek üzere panoya kopyalar;
	* enter tuşunun çeşitli kombinasyonları Değiştir, Tümünü değiştir, Yoksay,
	  Tümünü yoksay veya Kelimeyi sözlüğe ekle düğmelerini etkinleştirir, bu
	  iletişim kutusunun daha rahat olması için eklenmiştir;

* Otomatik eklenti güncellemesi;
* Ve [kullanım kılavuzunu][4] okuyarak keşfedeceğiniz diğer birçok şey;

[[!tag dev stable]]

[1]: https://www.nvaccess.org/addonStore/legacy?file=thunderbirdPlus

[2]: https://www.rptools.org/?p=8610

[3]: https://github.com/RPTools-org/ThunderbirdPlus/

[4]: https://www.rptools.org/Outils-DV/NVDA-ThunderbirdPlus-en.html
>>>>>>> nvdaaddons/stable
