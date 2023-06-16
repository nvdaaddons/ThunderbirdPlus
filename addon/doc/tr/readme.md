# Thunderbird+ #

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
