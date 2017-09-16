# FusionFall Türkçe Wiki Ana Kılavuz


## Bu bilgilerle ne yapacağız?

Gördüğünüz üzere, 16 Eylül 2017'de nihayet FusionFall Wiki'nin bütün bilgilerinin bulunduğu yaklaşık 20MB'lık XML dosya çıkıntısı belli araçların yardımıyla ayıklanarak (dosyanın en altındaki düzenli ifadeler dizinleri sağolsun), en çok tekrarlanan terimler çevirildi, ilerideki çevirilerimizde başımızı ağrıtacak hep tekrar tekrar çevirmek zorunda kalabileceğimiz şeyler, kod editörlerinin bul ve değiştir teknikleriyle basit bölümler nihayet tamamlandı.

Bununla birlikte FusionFall Türkçe Wiki'de neler yapacağımızın ilk resmi, temeli atıldı sayılır. Farkettiyseniz oyunun İngilizce olmasına rağmen karakterlerden tutun, orijinal yer isimleri bile (özel isimlerin haricinde) Türkçe'ye çevirildi. İlk baktığınızda belki bu duruma 'yabancı' kalıyor olabilirsiniz ama buradaki maksat bu wikinin kesinlikle ama kesinlikle Türkçe olması. Bundan ödün verseydik kesinlikle bu wikinin olması için anlam kalmazdı diye düşünüyorum. Bundan dolayı olabildiğince bütün bu çevirilen kavramları altta listeledim.

Eğer siz, çevirmenler, yöneticiler, bürokratlar, yardımcılar, ya da katkıda bulunmak misafirler, eksik kalan bilgiler veya çevirmek istediğiniz bir sayfa olduğunda lütfen ama lütfen bu alttaki terimlerin çevirilerine bağlı kalarak hareket edin. Bu wiki için en önemli önceliklerinden birisidir.

Bunlara uyacağınıza güvenerekten sizlere bu listeyi bırakıyorum. Gözünüzde korkutucu gelebilir belki ama işi sizin için kolaylaştırmak için kavramları 5-6 kategoriye ayırarak kelime/kelime gruplarını A'dan Z'ye sıraladık. Sadece ihtiyacınız olan kelimenin çevirisini buraya güvenerek işinizi görebilirsiniz.

Wikide sayfa çevireceğiniz zaman sizin işinizi kolaylaştıracak WYSIWYG (Ne görürsen odur) terminolojisine uygun, Wikia'nın kendi özel sitesinde görsel editörlerde sayfa çevirmeniz mümkün. 

Ya da bunun yerine ileri derecede çeviri yapmayı tercih ederseniz, [Sublime Text](http://www.sublimetext.com), [Atom](https://atom.io), [Notepad++](https://notepad-plus-plus.org) gibi orta-yüksek derecede iyi kod editörlerini size kesinlikle tavsiye ederim. Bununla beraber eğer bir wikinin nasıl çalıştığı hakkında bilgi sahibi değilseniz, bu noktadan itibaren alttaki bütün paragrafları okumanızı da şiddetle tavsiye ediyorum.

Bunları zaten biliyor ve wikideki temel bilgileri geçmek istiyorsanız Sonsöz başlığına gidin.

## Wikide Kesinlikle Öğrenmeniz Gereken Temel Bilgiler

### Başlıklar, Vurgulamalar vb.

Wikide sayfanın tasarımını düzenlerken nasıl başlık eklenir, nasıl bağlantı verilebilir, nasıl çalıştığını göstermek istiyorum:

Yazının etrafında ne kadar '=' karakteri eklenirse o dereceye temsilen, başlık oluşur:
```
=Birincil Başlık=
==İkincil Başlık==
===Üçüncül Başlık===
(5'e kadar uzayabilir)
```
Başlıkların önceliğine göre (= işaretleri azaldıkça) metin büyüklüğü büyür. (Ama lütfen ne yazdığınız paragrafa dikkat ederek, hangi kategori içerisinde olup olmadığına dikkat ederek başlık ekleyin)

```
''İtalik''
'''Kalın'''
```

### Wiki içerisinde bağlantı eklemek

Wikilerda sayfa oluşturacağınız zaman kendi wikinizin içerisinde geçen bir kelimenin kaynağın sayfası bulunuyorsa bağlantı eklemeniz gerekebilir. (Ki kullanıcı anlamadığı kavramların ne demek olduğunu kolayca anlayabilsin.) Bağlantılar formata göre şöyle eklenir:

```
[[Sayfa Adı]]
```

Bunun çıktısında, okuyucu bunu sadece 'Sayfa Adı' yazısı olarak okuyacaktır. Eğer bu yazıldığında makalede bağlantı mavi ise, bu adda bir sayfamız var ya da bu adda bir yönlendirme sayfamız var demektir. Fakat kırmızıysa, belli ki öyle bir sayfa yoktur. Peki bu bağlantının ismi illa gözükmesi gerekir mi? Değil.

```
Ne mutlu [[Sayfa Adı|Türküm]] diyene! 
```

Şeklinde yazarsanız, okuyucu bunu okuduğunda 'Ne mutlu Türküm diyene!' diye görecek ve Türküm kelimesine tıkladığında 'Sayfa Adı' sayfasına gidecektir. Tabi bu bağlantılar yalnızca sayfa adlarıyla da sınırlı değil, sonraki başlığı okuduktan sonra daha iyi anlayacaksınız... 

###Wikideki URL bağlantıları/Sayfa Türleri

Tabi bağlantılardan söz etmişken Wiki'deki adreslerin de nasıl çalıştığını bilmenizde de fayda var:

```
http://(ülkekısaltması).alanadı.wikia.com/wiki/Sayfanın_Adı
```

Biz Wikia'nın kolları altında Wiki sayfaları ekleyebiliyoruz. Bundan dolayı wikia.com alan adına sahibiz.
alanadı, şu durumda fusionfall oluyor.
Tabi bu fusionfall wikisinin diğer dillerden ayırılması lazım. Şu durumda Türkiye'den tr. kısaltmasına sahibiz. Bunun dışında İspanyolların es. Brezilyalılarınsa br. kısaltması kullanıyor. Hepimiz fusionfall.wikia.com sayfasına bağlıyız.
Wikia.com'dan sonraki gördüğünüz /wiki dizini var. Bu dizini nereye ulaşırsanız ulaşın, her zaman websitenin adresinde görürsünüz. Bu sizin bir 'Wiki' sayfasında olduğunuzu vurguluyor.
/wiki dizisinin içerisinde de bizim ilgilendiğimiz, çevirdiğimiz sayfalar yer alıyor. Mesela ana sayfamızı baz alalım. Biz ana sayfamızı 'FusionFall Wiki' sayfasına bağladık. Bu durumda bizim ana sayfamız:

```
http://tr.fusionfall.wikia.com/wiki/FusionFall_Wiki
```

Fakat sayfanın boşluğunun olduğu yerde bir _ sembolünün olduğunu farkedeceksiniz. Bu neredeyse bütün Wiki'lerin sayfalarında dahilinde olan bir şeydir. Bağlantı ekleme örneğinde de gördüğünüz üzere [[Sayfa Adı]] demiştik ya? Bu da demektir ki aynısını [[Sayfa_Adı]] şeklinde de yazabiliriz anlamına geliyor. 

Eh sayfa sayfa sayfa. Ama neyin sayfası?
Sıra geldi sayfaların ad alanına.

```
https://tr.fusionfall.wikia.com/wiki/MediaWiki:
                                     Special:
                                     Template: 
                                     Category:
									 File:
```

MediaWiki, internetteki bütün wikilerin kullandığı bir çeşit bir formatın adıdır. Bu ==başlık== vb. formatları kullanmamızı sağlayan ana tabandır. Bu ad alanına sahip sayfalarsa, wikimizin genel stilini, çalışma şeklini, hemen hemen wikimizin bütün kökenleriyle alakalı sayfalara sahiptir. Bu sayfaların misafirler tarafından düzenlenmesine izin verilemez, ancak kaynaklarını görebilirsiniz. Bu dosyalardan yalnızca moderatörler, yöneticiler sorumludur.

Template, yani Şablon wikide gördüğünüz görsel kutucuklar, resimler, tablolar ve benzeri verileri kolayca sizlere sunmanın bir yoludur. Normalde bir nanonun bilgilerini yazdığınız zaman onun adı, seviyesi, yetenekleri, hangi görevle alındığını belirtmeniz gerekir. Ve bunu düz bir şekilde listeyle eklerseniz, okuyucu neye baktığına şaşırabilir. Daha düz ifadeyle, sayfa karman çorman olur. Bunun yardımına şablonlar yetişiyor. Önceden Template:Nano şeklinde bir şablon eklerseniz bunun tablosunu, tasarımını tek bir yerden düzenleyebilir daha sonra yalnızca bütün bu kod yığınını {{Nano|Ad=Buttercup|Svye=16}} şeklinde yazarak düzenli bir tablo oluşturabilirsiniz. Eğer siz de bir tane yapmak istiyorsanız bunun tabi önceden format kodlarını vb. şeylerini bilmeniz gerekiyor. Ya kendiniz araştırın ya da bizim kendi şablonlarımızı örnek alarak bir şeyler yapmayı deneyin. Wikinin kodlama dili oldukça kolaydır. 

Category, yani Kategori ad alanı, adı üstünde, sayfaların kategorisini belirler. Bu sayfanın varolması için normal bir sayfa olarak ekleyip böyle bir ad alanı eklemenize gerek yok. Ad alanına sahip olmayan, normal bir sayfanın sonuna 
{{Category:Nanolar}} diye ekleyip, paylaştığınız anda (ya da görsel editörden kendi elinizle kategori yazıp eklerseniz) otomatikman boş Category:Nanolar sayfası eklenmiş oluyor. Bu sayfaya giderseniz, o kategoriye sahip ne makaleler, sayfalar varsa onların bir listesini görebilirsiniz.

File, yani Dosya ad alanı, resim, video, müzik, çerçeve vb. medya dosyalarını barındıran bir ad alanıdır. Belli bir resim/video eklemek isterseniz, ilk önce siteye/wikiye yüklemeniz gerekiyor. Yükledikten sonra o dosyanın kendi ismini kullanarak veya kendi düzenlediğiniz isme göre o dosyanın da kendine göre bir sayfası olmuş oluyor. Bu sayfa da bir nevi otomatikman hazırlanır; içeriğinde o resmin geçmiş revizyonları, detaylı bilgileri bir minik bir tabloda yazılıdır. Atıyorum ki ffturkiye.png diye bir resmi yüklemek istedik diyelim, aynen bunu yüklediğiniz de artık wikinin resim veritabanlarından birine yer alır ve ``tr.fusionfall.wikia.com/wiki/File:ffturkiye.png`` adresinde yuvası olur. Peki bu resmi nasıl bir sayfada göstereceğiz? Eğer düz mantığınız iyi çalışıyorsa bunun cevabını çoktan biliyor olmanız gerek. [[File:ffturkiye.png]] ile tabii ki.

Şimdilik bilmenizi isteyeceğinizi düşündüğüm ad alanları bunlar. Bunun dışında diğer ad alanlarını merak ediyorsanız, yine bir ad alanı kullanarak, bir wikinin bütün sayfalarını gösterebilecek bir adres de girebilirsiniz.

```
http://tr.fusionfall.wikia.com/wiki/Special:AllPages
                                    Özel:TümSayfalar
```

Şimdilik biz de sayfa türleri kısıtlı ama mesela orijinal wikinin Talk:, Forum:, Discussion: gibi zengin özellikli diğer ad alanları da var. Yapmanız gereken şeyi biliyorsunuz: yalnızca ülke kısaltmasını silin, İngilizce siteye gitsin.

```
http://fusionfall.wikia.com/wiki/Special:AllPages
```


##Sonsöz
Şimdiden bu kılavuzdan yararlananlar kişilere büyük bir içtenlikle teşekkürlerimi iletiyorum, bu bilgilere verdiğiniz değeri yansıtıyor kesinlikle. Umarım faydalı bilgiler edinmişsinizdir.

Kılavuzda herhangi bir soruna rastlarsanız beni Discord [sunucumuzdan](http://discord.gg/nPTEy9Y) bulup mesaj atabilirsiniz, en geç 1 gün içerisinde cevap verebilirim.

----

##Lejant
Alttaki kavramlarda parantez içerisine alınanlar ek/çoğul eki/kelime/kelime grupları opsiyoneldir ya da o terimin türünü açıklıyordur.

##Yerler
**Önemli Not:** Bu başlığın altındaki parantezler, tür göstermez, verinin kendisidir.

```
The Future............................: Gelecek
Tech Square (The Future)..............: Tekno Meydanı (Gelecek)
Sector V (The Future).................: Sektör V (Gelecek)
Pokey Oaks North (The Future).........: Kuzey Pokey Oaks (Gelecek)
Pokey Oaks South (The Future).........: Güney Pokey Oaks (Gelecek)
Peach Creek Commons (The Future)......: Şeftali Deresi Avamı (Gelecek)
Peach Creek Estates (The Future)......: Şeftali Deresi Arazileri (Gelecek)
Genius Grove (The Future).............: Yetenek Bahçesi (Gelecek)
Candy Cove (The Future)...............: Şeker Koyu (Gelecek)
Goat's Junk Yard (The Future).........: Goat'ın Çöplüğü (Gelecek)

The Suburbs...........................: Mahalleler
Sector V..............................: Sektör V
Pokey Oaks North......................: Kuzey Pokey Oaks
Pokey Oaks South......................: Güney Pokey Oaks
Peach Creek Commons...................: Şeftali Deresi Avamı
Peach Creek Estates...................: Şeftali Deresi Arazileri
Genius Grove..........................: Yetenek Bahçesi
Candy Cove............................: Şeker Koyu
Goat's Junk Yard......................: Goat'ın Çöplüğü
Eternal Vistas........................: Ölümsüz Manzaralar
Eternal Meadows.......................: Ölümsüz Çayırlar
Endsville.............................: Endsville
Foster's Home.........................: Foster'ın Evi
Nuclear Plant.........................: Nükleer Santral
Habitat Homes.........................: Habitat Evleri

Downtown..............................: Şehir Merkezi
City Point............................: Şehir Noktası
City Station..........................: Şehir İstasyonu
Marquee Row...........................: Tente Sokakları
(Marquee kelimesi konser, tiyatro salonlarının tavanı için kullanılır. Buna ben 'tente' diyebildim Türkçe'si bilene de bilmeyene de biraz saçma gelebilir, marquee aynı zamanda manav/otel/restoran girişlerinin tepelerine takılan bir şeydir, daha alakalı bir kelime bulabilirseniz değişime açık. ????? Sokakları'na uydurmamız da lazım.)
(Row kelimesi ise birbirine benzeyen sıralı evlerin bulunduğu bir sokağa verilen genel bir isimdir ancak Türkçe'de bunun tam karşılığı olmadığı için direkt 'Sokak' dedim, çoğul kullandım çünkü koca bölgede tek bir sokak yok.)
Townsville Center.....................: Townsville Merkezi
City Hall.............................: Belediye Binası
Townsville Park.......................: Townsville Parkı
Orchid Bay............................: Orkide Şehri
(Alakalı çizgi dizide Türkçe'si varsa dublajına bakılmasını öneririm)
Bravo Beach...........................: Bravo Sahili
Morbucks Towers.......................: Morbucks Kuleleri
Mojo's Volcano........................: Mojo'nun Volkanı
Galaxy Gardens........................: Galaksi Bahçeleri
Tech Square...........................: Tekno Meydanı
Steam Alley...........................: Buharlı Yol
Offworld Plaza........................: Offworld Plaza

The Wilds.............................: Vahşi Doğa
Prickly Pines.........................: Dikenli Çamlar
(Kamp Lazlo'da tam Türkçe'si varsa kullanılmasını öneririm)
Camp Kidney...........................: Barbunya Kampı
Mt./Mount Blackhead...................: Karabaş Dağı
Leakey Lake...........................: Delikli Göl
(Not: İsim İskoçya'daki ünlü bir göl Loch Ness'ten geliyor. Yalnızca mess(kirli,pis anlamına gelen) kelimesiyle benzetilerek konulmuş. Biz de aynı mantıkla Loch Ness'teki Loch'u Leş'e benzetebiliz diye düşündüm.)
Acorn Flats...........................: Meşe Düzlükleri
Pimpleback Mountains..................: Sivilcesurat Dağları
Haunted Ridge.........................: Lanetli Sırt
Twisted Forest........................: Bükülmüş Orman
The Ruins.............................: Yıkıntılar
Devil's Bluff.........................: Şeytanın Uçurumu
Devil's Canyon........................: Şeytanın Kanyonu
Nowhere...............................: Hiçbir Yer
Area 51.5.............................: 51.5. Bölge
Really Twisted Forest.................: İyice Bükülmüş Orman
Lower Catacombs.......................: Aşağı Katakomplar
Forgotten Falls.......................: Unutulmuş Şelale
Upper Catacombs.......................: Yukarı Katakomplar
Monkey Foothills......................: Maymun Bayırları
Monkey Mountain.......................: Maymun Dağı

The Darklands.........................: Karanlık Diyarlar
Forsaken Valley.......................: Terkedilmiş Vadi
Dinosaur Pass.........................: Dinozor Geçidi
Fireswamps............................: Ateşbataklıkları
Firepits..............................: Ateşçukurları
Huntor's Crest........................: Huntor'un Tepesi
Dark Glade............................: Karanlık Kayran
Hero's Hollow.........................: Kahramanın Çukuru
The Precipice.........................: Sarp Kayalıklar
Green Maw.............................: Yeşil Ağız
Fuse's Lair...........................: Fuse'un Sığınağı

The Academy...........................: Akademi
Null Void.............................: Hiçlik Boyutu
Providence HQ.........................: Providence Karargâhı
Mt. Neverest..........................: Neverest Dağı
(Bu yer Dexter'ın Laboratuvarı'nda söz edilmiş olunabilir, orijinal Türkçe dublajını bulmak gerek)
```

###Karantina Bölgeleri

```
KND Training Area.....................: Afacanlar Eğitim Alanı
Pokey Oaks Junior High................: Pokey Oaks Ortaokulu
Delightful Developments...............: Keyfine Düşkün Sitesi
Mandark's House.......................: Mandark'ın Evi
Sweet Revenge.........................: Tatlı İntikam
Megas' Last Stand.....................: Megas'ın Son Direnişi
The Boneyard..........................: Mezarlık
Reactor Works.........................: Reaktör Tesisi
Charles Darwin Middle School..........: Charles Darwin Ortaokulu

Dizzy World...........................: Dizzy Dünyası
Sunny Bridges Auditorium..............: Sunny Bridges Konser Salonu
The Fissure...........................: Çatlak
Cutts and Bruises Skate Park..........: Cutts ve Bruises Kaykay Parkı
Sand Castle...........................: Kumdan Kale
Construction Site.....................: İnşaat Alanı
Tyrannical Gardens....................: Acımasız Bahçeler
Skypad Space Port.....................: Skypad Uzay Üssü

Jungle Training Area..................: Orman Eğitim Alanı
Loch Mess.............................: Leş Ness
Crystalline Caverns...................: Kristal Mağaralar
Hani-Baba Temple......................: Hani-Baba Tapınağı
(Hani-Baba değiştirilmeyecek çünkü ordaki isim özellikle öyle yapılmış, Hanna-Barbera'nın ismine yakıştırma olarak kullanılmıştır.)
Nowhere Triangle......................: Hiçbir Yer Üçgeni
The Canopy............................: Gölgelik
Monkey Summit.........................: Maymun Zirvesi

Dinosaur Graveyard....................: Dinozor Mezarlığı
Inferno Fields........................: Cehennem Alanları
Dark Tree Clearing....................: Koyu Ağaç Açıklığı
Green Gullet..........................: Yeşil Boğaz
```

###Görevlerde sıkça adı geçen, spesifik yerler
```
Chowder's Mouth.......................: Chowder'ın Ağzı
City Tower/City Station Tower.........: Şehir Kulesi/Şehir İstasyonu Kulesi 
Cul-de-Sac............................: Çıkmaz Sokak
Hero Square...........................: Kahraman Meydanı
KND Jungle Outpost....................: ?Afacanların Orman Mevkisi
Mandark Industries Carrier............: Mandark Endüstrisi Taşıyıcısı
Mandy's House.........................: Mandy'nin Evi
Providence Townsville Park Outpost....: Providence Townsville Parkı Karakolu 
Sunken Mall...........................: Çökük Çarşı
Townsville Mall.......................: Townsville AVM
Trailer Park..........................: Karavan Parkı 
Ship's Interior.......................: Gemi'nin İçi
```

###Potansiyel FF Legacy Yerleri

```
Area 51.1.............................: 51.1. Bölge
Wilson Way............................: Wilson Yolu
Hookslice Hills.......................: Hookslice Tepeleri
Mt. Whitehead.........................: Akbaş Dağı
Skull Rock............................: Kafatası Kayalıkları
Townsville Aquarium...................: Townsville Akvaryumu
Townsville Zoo........................: Townsville Hayvanat Bahçesi
```

##Karakterler, Karakter Grupları ve Nanolar

```
A. Kwest's Gravestone.................: A. Kwest'in Mezartaşı
Agent Avery...........................: Ajan Avery
Agent Boyd............................: Ajan Boyd
Agent Cahill..........................: Ajan Cahill
Agent Cutts...........................: Ajan Cutts
Agent Greenberg.......................: Ajan Greenberg
Agent Grace...........................: Ajan Grace
Agent K9..............................: Ajan K9
Agent Six.............................: Ajan Altı
Agent Taylor..........................: Ajan Taylor
Alien X...............................: Uzaylı X
AmpFibian.............................: AmpFibiyan
Bobby Baboon..........................: Bobby Babun
Buttercup(Future).....................: Buttercup (Gelecek)
Candy Pirate(s).......................: Şeker Korsan(lar)ı
Candy Wife............................: Şeker Karı
Cheese................................: Peynir
Computress............................: Bilgisayar
Courage...............................: Cesur
Demon(s)..............................: Şeytan(lar)
DexLabs Scientist.....................: DexLabs Bilim İnsanı
Doc Saturday..........................: Doc Cumartesi
Drew Saturday.........................: Drew Cumartesi
Dukey.................................: Dük
Eggplant(s)...........................: Patlıcan(lar)
Father................................: Baba
Fourarms/Four Arms/FourArms...........: Dört Kol
Fusion AmpFibian......................: Fusion AmpFibiyan
Fusion Cheese.........................: Fusion Peynir
Fusion Numbuh Five....................: Fusion Numara Beş
Fusion Numbuh Four....................: Fusion Numara Dört
Fusion Numbuh One.....................: Fusion Numara Bir
Fusion Numbuh Three...................: Fusion Numara Üç
Fusion Numbuh Two.....................: Fusion Numara İki
Fusion Professor Utonium..............: Fusion Profesör Utonium
Fusion Samurai Jack...................: Fusion Samuray Jack
Fusion Stickybeard....................: Fusion Şekersakal
Fusion Toiletnator....................: Fusion Tuvaletör
Grandpa Max...........................: Büyükbaba Max
Humungausaur..........................: İnsanozor
Ice King..............................: Buz Kralı
Jellybean Jane........................: Jelibon Jane
Kumari Admiral(s) (and) Serpent(s)....: Kumari Amiral(ler)i (ve) Yılan(lar)ı
Lady Rainicorn........................: Gökkuşağı Atı
Magic(al) Toadstool(s)................: Sihirli Kurbağa(lar)
Mayor.................................: Başkan
Mr. Herriman..........................: Bay Herriman
Mutant Eggplant(s)....................: Mutant Patlıcan(lar)
Numbuh Five...........................: Numara Beş
Numbuh Four...........................: Numara Four
Numbuh One............................: Numara Bir
Numbuh Three..........................: Numara Üç
Numbuh Two............................: Numara İki
Numbuh................................: Numara 
Numbuh................................: Numara 
Numbuh................................: Numara 
Numbuh................................: Numara 
Numbuh................................: Numara 
Numbuh................................: Numara 
Numbuh................................: Numara 
Numbuh................................: Numara 
Numbuh................................: Numara 
Numbuh................................: Numara 
Numbuh................................: Numara 
Princess Bubblegum....................: Prenses Ciklet
Professor Utonium.....................: Profesör Utonium
Providence Agent......................: Providence Ajanı
Providence Recon Agent................: Providence Keşif Ajanı
Ranger Charles........................: Koruyucu Charles
Ranger Joey...........................: Koruyucu Joey
Ranger Melissa........................: Koruyucu Melissa
Ranger Ralphie........................: Koruyucu Ralphie
SACT Agent(s).........................: SACT Ajanları
Samurai Jack..........................: Samuray Jack
Secret Agent William..................: Gizli Ajan William
Shopkeeper(s).........................: Dükkâncı(lar)
Space Chicken.........................: Uzaylı Tavuk
Spencer Spidermonkey..................: Spencer Örümcekmaymun (Jake Örümcekmaymun'un kuzeni)
Stickybeard...........................: Şekersakal
The Scotsman..........................: İskoçyalı
Toiletnator...........................: Tuvaletör
Unstable Nano.........................: Kararsız Nano
Whoosh(, the Alpha Whale).............: Alfa Balina Whoosh
Worlds Collide (Manganın İsmi)........: Dünyalar Çarpışıyor
```

###Potansiyel FF Legacy Karakterleri
```
Eustace...............................: Huysuz
Muriel................................: Merdane
```

###Nano Güçleri
**Not:** Nano isimleri Türkçelendirilmiştir.
```
Passive Powers........................: Pasif Güçler
Antidote..............................: Antidot
		Blossom............|Liberty Belle.................: Özgürlük Çanı
		Mandark............|Bio Dome......................: Biyolojik Kubbe
		Samuray Jack.......|Sacred Guardian...............: Lanetli Gardiyan
Bonus.................................: Bonus
		Numara İki.........|Lunch Money...................: Öğle Harçlığı
		Numara Bir.........|Big Bucks.....................: Büyük Para
		Aku................|Ancient Treasure..............:
		Mordecai...........|Working for the Weekend.......: Haftasonu İçin Çalışmak
		Prenses Ciklet.....|Penny Candy...................:
Freedom...............................: Özgürlük
		Blossom............|Everything Nice...............: Güzel Olan Herşey
		Mojo Jojo..........|Jojo Juggernaut...............: Jojo Ezicisi
		Coco...............|Bird Brain Unbound............: Özgür Kuş Beyni 
		Billy..............|Unstoppable Stupid............: Durdurulamayan Aptal
		O (Him)............|Demonic Possession............:
		İnsanozor..........|Giant Unleashed...............: Devasa Kurtuluş
		Chowder............|I'm Not your Boyfriend!.......: Ben Erkek Arkadaşın Değilim!
		Rath...............|Can't Stop Me.................: Beni Durduramazsın!
Guard.................................: Koruyucu
		Eddy...............|Energy Saver..................: Enerji Tasarrufu
		Mojo Jojo..........|Brain Power...................: Beyin Gücü
		Coco...............|Power Shell...................: Güç Kabuğu
		AmpFibiyan.........|Surge Protector...............: Gerilim Koruyucusu
Jump..................................: Zıplama
		Profesör Utonium...|Rocket Pack...................: Roket Paketi
		Samuray Jack.......|Rise Of The Spirit............: Ruhun Yükselişi
		Gumball............|The Bunny Hop.................: Tavşan Zıplaması
		Jake...............|Leg Stretch...................: Ayak
		Wilt...............|Crazy Air.....................: Çılgın Hava 
		Bubbles............|Bunny Hop.....................: Tavşan Zıplaması
		Juniper Lee........|Mystical Boost................: Mistik Güçlenme 
		Finn...............|Turbo Action Backpack.........: Turbo Macera Çantası
Radar.................................: Radar
		Eduardo............|Who's There?..................: Kim O?
		Vilgax.............|Secure Perimeter..............: Güvenlik Çemberi
		Ed.................|Monster Tracker...............: Canavar Takipçisi
		Titan..............|Sensor Array..................: Sensör Dizisi
		Zak Cumartesi......|Monster Hunter................: Canavar Avcısı
Run...................................: Koşma
		Eddy...............|Speedy Gedaway................: Çabuk Kaçış
		Grim...............|Bat Out Of Heck...............:
		Mandy..............|Seismic Slap..................: Sismik Çarpma
		Darwin.............|Dodge or Dare.................: Ya Savaş Ya Kaç
		Flapjack...........|The Foot Burn.................: Ayak Yanığı
		Numara İki.........|Fast Feet.....................: Hızlı Ayaklar
		Vilgax.............|Light Speed...................: Işık Hızı
		Hex................|Summon Wind...................: Rüzgar Çağırışı
		Rex................|Boogie Pack...................:
		Cheese.............|Good Horsie!..................:  
		Johnny Bravo.......|Momma's Calling...............: Annem Çağırdı
Scavenge..............................: Çöpcü
		Buttercup..........|Buttercup Burst...............: Buttercup Yarması
		Dört Kol...........|Four Hand Grab................: Dört elle yakalamak 
		Cesur..............|Cower Power...................:
		Chowder............|Spit Take.....................: ?Tükürük
		Cheese.............|I Like Candy..................: Şeker Severim
Sneak.................................: Gizlenme
		Numara Beş.........|Secret Agent..................: Gizli Ajan
		Dexter.............|Inviso-Ray....................: Görünmez-Işın
		Numara Üç..........|Sanban Sneak..................: Sanban Saklan
		Darwin.............|Hide..........................: Saklan
		Megas..............|Stealth Mode..................: ?Hayalet/Görünmezlik Modu
		Çamurateş..........|Creeping Vine.................: Sürünen Asma
		Mac................|Hide And Sneak................: Saklambaç
Treasure Finder.......................: Hazine Arayıcısı
		Edd................|Meddal Detector...............: Meddal Detektörü
		Burada Edd'in ismiyle Metal ismi birleştirilip kelime oyunu yapılmıştır, çeviride ve orijinalinde kasten metal yerine meddal yazılmıştır.
		Bloo...............|Finders Keepers...............: Kim Bulduysa Onundur
		Mandy..............|More For Me...................: Benim İçin Daha Fazla
		Buz Kralı..........|Penguin Sense.................: Penguen Hissi

Triggered Powers......................: Tetiklenebilen Güçler
Damage................................: Hasar
		Dee Dee............|Ponypuff Pirouette............: Midilli Pirueti
		Demongo............|Demon's Fire..................: Şeytanın Ateşi
		İnsanozor..........|Ground Quake..................: Yeraltı 
		Rigby..............|Death Punch...................: Ölüm Yumruğu
		Rath...............|Rath's Wrath..................: Rath'in Gazabı
		Billy..............|Snot Rocket...................: Sümük Roketi
		Numara Bir.........|Spitwad Volley................:
		Aku................|Wizard Storm..................: Büyücü Fırtınası
		Rex................|Big Freaking Sword............: Aşırı Büyük Kılıç
		Johnny Test........|Power Poots...................:
		Titan..............|Symbionic Sword...............: Simbionik Kılıç
		Dee Dee............|Diva Dynamite.................:
		Samuray Jack.......|Samurai Slash.................: Samuray Vuruşu
		Finn...............|Smite Evil....................:
		Gumball............|Tae Kwon Dork.................:
		Mordecai...........|Punchies......................:
		Zak Cumartesi......|Cryptid Assault...............: Criptit Saldırısı
Drain.................................: Yaralama
		Eduardo............|Monster Roar..................: Canavar Kükreyişi
		O (Him)............|Evil Laugh....................: Şeytani Kahkaha
		Numara Dört........|Sabotage Strike...............: Sabotaj Vurgunu
		AmpFibiyan.........|Circuit Breaker...............: Döngü Kırıcı
		Profesör Utonium...|Prof. Protection..............: Profesör Protection
		Mojo Jojo..........|Freeze Ray....................: Dondurucu Işın
		Cesur..............|Horrific Howl.................: Korkunç Uluma
		Flapjack...........|Love Gnat.....................: Sevgi Tatarcığı
Health................................: Sağlık
		Buttercup..........|Rallying Cry..................: Toplanma Çağrısı
		Grim...............|Heebie Jeebie Holt............:
		Numara Üç..........|Share The Love................: Sevgiyi Paylaş
		Darwin.............|Trauma Therapy................: Travma Terapisi
		Peynir.............|Heal!.........................: İyileş!
		Eddy...............|Jawbreaker Break..............: Çenekıran Molası
		Numara Bir.........|First Aid.....................: İlk Yardım
		Cesur..............|Softshoe Shimmy...............:
		Rigby..............|Java Jolt.....................: Kahve Etkisi
		Eduardo............|Papas Fritas..................: Papas Fritas/Patates Kızartması
		Papas Fritas denilmesinin sebebi en başta patates kızartmasını Eduardo kendi ana diliyle söylemesi olabilir. Ya tercümesiyle yazılmalı ya da orijinal bırakılmalı
		O (Him)............|Mwa-Ha-Ha.....................: Hıha-Ha-Ha
		Numara Dört........|Battle Monster................:
		Uzaylı X...........|Celestial Light...............: İlahi Işık
Leech.................................: Sülük
		Numara Beş.........|Drop Kick.....................: Uçan Tekme
		Dört Kol...........|Overpower.....................: Aşırı Güç
		Juniper Lee........|Te-Xuan-Zap...................: Ti-Şuan-Zap
Recall................................: Geri Çağırma
		Numara İki.........|Nonstop Flight................: İnişsiz Uçuş
		Vilgax.............|Null Void Passage.............: Hiçlik Boyutu Yolcusu
		Hex................|Vanishing Act.................: Kaybolma Numarası
		Rigby..............|Magical Keyboard..............: Sihirli Klavye
		Edd................|Narrow Escape.................: Kısa Kaçış
		Dexter.............|Teleporter....................: Işınlayıcı
		Mandy..............|Dimensional Rift..............: Boyutsal Çatlak
		Uzaylı X...........|Reality Fade..................: Gerçeklik Soluşu
Rocket................................: Roket
		Profesör Utonium...|Utonium Zoom..................: Utonium Yükselişi
		Dexter.............|Glide.........................: Planör
		Mac................|Fizzy Rocket..................: Gazlı Roket
		Gumball............|Swan Dive of Eternal Beauty...: Ebedi Güzelliğin Kuğu Dalışı
		Titan..............|Booster Rockets...............: İtici Roketler
		Buz Kralı..........|Beard Pilot...................: Sakal Pilotu
		Jake...............|Ear Glide.....................: Kulaktan Planör
Sleep.................................: Uyutucu
		Megas..............|Garden State Slam.............:
		Çamurateş..........|Heat Stroke...................: Sıcak Çarpması
		Hex................|Sleep Charm...................: Uyku Cazibesi
		Prenses Ciklet.....|Sweet Dreams..................: Tatlı Rüyalar
		Megas..............|Eightball Fireball............: ?Sekiztop Ateştop
		Çamurateş..........|Swamp Gas.....................: Çamur Gazı
		Mac................|After School Special..........:
		AmpFibiyan.........|Blackout......................: Elektrik Kesintisi
		Billy..............|Inner Frat Boy................:
		Dört Kol...........|Seeing Red....................: ?Kırmızı Görmek
		Ed.................|Paging Dr. Ed.................:
		Chowder............|Blormed Milk..................: ?Çürük Süt
		Flapjack...........|Adventurer's Lullaby..........: Maceraperestin Ninnisi
		Jake...............|Viola Lullaby.................: Viyola Ninnisi
Snare.................................: Tuzak
		Wilt...............|Nothing But Net...............: Deliksiz Basket
		Bloo...............|Bloo Glue.....................: Bloo Yapıştırıcısı
		İnsanozor..........|Saurian Snare.................: Saurian Tuzağı
		Edd................|Sugar Rush....................: Şeker Yağması
		Demongo............|Hero's Strength...............: Kahramanın Dayanıklılığı
		Ed.................|Group Hug.....................: Grup Sarılması
		Wilt...............|Zone Defense..................: Bölge Defansı
		Bubbles............|Tornado Trap..................: Hortum Tuzağı
		Juniper Lee........|Monster Ambush................: Canavar Pususu
		Uzaylı X...........|Black Hole....................: Kara Delik
Stun..................................: Bayıltıcı
		Blossom............|Ice Breath....................: Buz Nefesi
		Mandark............|Mandarkness...................: Mandark'lık
		Coco...............|Egg Bomb......................: Yumurta Bombası
		Buttercup..........|Miss Fire.....................: Iskaladın!
		Bloo...............|Juicebox Belch................: Meyve Suyu Geğiriği
		Aku................|Evil Eye......................: Şeytani Göz
		Rex................|Smackhands....................: Bayıltıcı Yumruk
		Johnny Test........|Hurricane Hands...............: Kasırga Eller

Other Powers..........................: Diğer Güçler
Revive................................: Diriltme
		Dee Dee............|Way Of The Dee Dee............: Dee Dee'nin Yolu
		Kalıplaşmış olan ölmenin yolu/şekli (The way of the death) cümlesine kelime oyunu yapılmıştır ancak düz çeviri gerek.
		Grim...............|Scythe Of Relief..............: Kurtuluşun Tırpanı
		Numara Dört........|Don't Give Up!................: Pes Etme!
		Numara Beş.........|Medic!........................: Doktor!
		Demongo............|Warrior's Resolve.............: Savaşçının Azmi
		Numara Üç..........|Rainbow Revival...............: Gökkuşağı Dirilişi
		Finn...............|Righteous Recovery............:
		Mordecai...........|Death Block...................: Ölüm Bloğu
		Prenses Ciklet.....|De-Corpsenaitor Serum.........: Canlandırıcı Serum
		Johnny Bravo.......|Too Pretty to Die.............: Ölmek İçin Çok Güzelim
		...................|..............................:
		...................|..............................:

Self..................................: Kendi
Group.................................: Grup
Area..................................: Çevre
Target Area...........................: Hedef Alanı
Point.................................: Nokta
Cone..................................: Koni
```

##Kayda değer görevler/görev grupları
```
Snail Quest...........................: Salyangoz Arayışı
Chowder's IncrEDIBLE Journey..........: Chowder'ın Yenilebilir Macerası
Ice King's Invasion...................: Buz Kralı'nın İstilası
Alien Abduction.......................: Uzaylı Kaçırma
```


##Genel Kavramlar
```
Accessories...........................: Takılar
Affiliation...........................: Bağlantılar
Area..................................: Yer
Armor.................................: Zırhlar
Attack................................: Atak
Backpack..............................: Arkalık
Blowfish..............................: Balonbalık
Body..................................: Üstlük
Border................................: Kenarlık
Buy...................................: Al
CRATE.................................: CRATE
C.R.A.T.E.|...........................: C.R.A.T.E.
Croc Pot Catering Company.............: Croc Pot Gıda Şirketi
Char..................................: Krktr
CharText..............................: KrktrMetin
Cost..................................: Ücret
Description...........................: Tanım
Def(ense).............................: Koruma
Difficuly/D...........................: Zorluk/Zrlk
Documentation.........................: Belgeleme
E.G.G.(E.R.)..........................: Y.U.M.U.R.T.(A./L.A.Y.I.C.I.)
Epic Lair.............................: Efsanevi Sığınak
Featured (Nano/etc)...................: Öne Çıkan (Nano/vb.)
Fusion Matter/FM......................: Fusion Maddesi/FM
Fusion................................: Fusion
FusionFall Wiki.......................: FusionFall Wiki
Glasses...............................: Gözlük
Group Att(ack)........................: Çoklu Atak
Guide Mission.........................: Rehber Görevi
Gumball...............................: Sakız
Hats..................................: Şapkalar
Height................................: Yükseklik
Infected Zone/IZ......................: Karantina Bölgesi/KB
Level/LVL/LV..........................: Seviye/Svye
Lair..................................: Sığınak
Legs..................................: Altlık
Location..............................: Konum/Yer
Main Area (Future, Darklands etc.)....: Bölge
Mechomorph E.G.G.|....................: ?Mekamorf(ik) Y.U.M.U.R.T.A.
Melee.................................: Yakın Dövüş
Mission Details.......................: Görev Detayları
Mission Stub/MisnStub.................: Görev Taslak Maddesi/GrvTslkMdde
Mission/Misn..........................: Görev/Grv
Momma Blowfish........................: Balonbalık Anne
NChar.................................: NKrktr
Name..................................: Ad
Nano Mission..........................: Nano Görevi
Nano..................................: Nano
No Retro/Not in Retro.................: Retro Yok/Retroda Yok
Not avaible in Retro..................: Retro'da mevcut olmayan(lar)
Object/Obj............................: Amaç
Pistol................................: Tabancalar
Power Item(s).........................: Güç Eşya(lar)sı
Primary Nano Mission..................: Birincil Nano Görevi
Quote.................................: Alıntı
Range.................................: Menzil
Rarity................................: Enderlik
Relative..............................: Yakını
Relatives.............................: Yakınları
Reward(s).............................: Ödül(ler)
Rifle.................................: Tüfek
Rockets...............................: Roketler
Secondary Nano Mission................: İkincil Nano Görevi
Secret Lair...........................: Gizli Sığınak
SectionDesign.........................: BölümTasarım
Sell..................................: Sat
Shattergun............................: Parçalayıcı
Shoes.................................: Ayakkabılar
Size..................................: Boyut
Solo Att(ack).........................: Tekli Atak
Species...............................: Irk
Speed.................................: Sürat
Step..................................: Adım
Subject/Subj..........................: Konu
Taro..................................: Taro
Template..............................: Şablon
Text..................................: Metin
Thrown................................: Fırlatmalık
Trade((-)ability).....................: Takas
Transport.............................: Ulaşım
Transport Hubs........................: Ulaşım Merkezleri
Type..................................: Tür
Vehicle...............................: Taşıtlar
Width.................................: En
World Mission.........................: Dünya Görevi
current...............................: Bulunan
inst..................................: Yap
```

###Çevrilmesi Planlananlar
```
Eruption Attacks
Corruption Attacks
Mechomorph
```

##Çizgi Diziler
```
Courage the Coward Dog................: Cesur Korkak Köpek
Adventure Time with Finn and Jake.....: Adventure Time
Codename: Kids Next Door..............: Kod Adı Afacanlar
The Life and Times of Juniper Lee.....: Juniper Lee'nin Maceraları
Foster's Home for Imaginary Friends...: Foster'ın Hayali Dostlar Mekanı
The Misadventures of Flapjack.........: Flapjack'in Müthiş Talihsizlikleri
```

##Wikipedia Başlıkları
```
Community Portal......................: Topluluk Portali
Policies..............................: Poliçeler
Blocking Policy.......................: Engellenme Poliçesi
Blogs and Forums......................: Bloglar ve Forumlar
Protected Page Policy.................: Korunan Sayfa Poliçesi
Image Policy..........................: Resim Poliçesi
Manual of Style.......................: Tasarım Kılavuzu
User guidelines.......................: Kullanıcı Yönergeleri
Administrators........................: Adminler
Assuming good faith...................: İyi niyet varsayımı
FAQ...................................: SSS
Mission Format........................: Görev Formatı
Monster Format........................: Canavar Formatı
Area and Infected Zone Format.........: Yer ve Karantina Bölgesi Formatı
Requests for adminship................: Adminlik için istekler
Simplified Ruleset....................: Basitleştirilmiş Kural Düzeni
......................................: 
```

###Çevrilmesi Planlananlar
```
Eruption Attacks
Corruption Attacks
Mechomorph
```

##XML dökümünü çevirmede yardımcı olabilecek düzenli ifadeler/regexler
(Yalnızca Vim kod editörüyle çalışır, farklı kod editörleri için isterseniz, kılavuza ekleyebilirim)

```
---Çevirilecek terimin çevresindeki genel sözdizimleri---
Category: 
[[Category: ]]
|Image: Haritası.png
|Resim= Haritası.png
|YerGeçmiş
|YerGelecek
|Ad= 
{: }
<title> </title>
{{Template: 
{{{ }}}

---Yer, Yerin sayfası, NPC bilgilendirmedeki yer, Harita linkindeki yer ismi, Yerin sayfa ismi---
Not: Bu alttaki düzenli ifade yalnızca yerler, karatina bölgelerin çevirimi için yaratılmıştır, bu türlerin dışındaki sayfa isimlerinde (nanolar, karakterler vb.) için kullanılırsa da işe yarayabilir fakat 100% eksik kalacak noktalar olabilir. Bundan dolayı bu bölümü yalnızca yer çevirilerinde kullanmanızı tavsiye ederim.

\m\(<title>\|&lt;br\/&gt;\|Ad=\|Yer=\|Category\:\|YerGeçmiş=\|YerGelecek=\|YerAkademi=\|Resim=\|\*\|\*\s\|\nImage\:\|File\:\|Makale=\|\[\[\||\)\zsStickybeard\ze\(\}\}\|\]\]\|\n\|\s\n\|<\/title>\n\(\s\{4}.*\n\s\{6}<text xml\:space="preserve">\c\#REDIRECT\)\@!\| Canavarları\| Haritası.png\| (Gelecek) Haritası.png\| (Gelecek)\| - \|- \||\)

---Kategori, FusionFall Wiki, Şablon, Proje, yönlendirmeler haricindeki bütün sayfa başlıkları---
<title>\(Category:\|FusionFall\sWiki:\|Template:\|Project:\|User:\|Forum:\)\@!\zs.*\ze\((Bölüm \d\/\d)\)\@<!<\/title>\n\(\s\{4}.*\n\s\{6}<text xml\:space="preserve">\c#REDIRECT\)\@!


---Tüm yönlendirmeler/All redirections---
<title>\zs.*\ze<\/title>\n\s\{4}.*\n\s\{6}<text xml\:space="preserve">\c#REDIRECT

<!-- Dikkat: Yukarıda çevirilecek sayfaların orijinal adlarının korunmasını sağlamak, aradıklarını bulmalarını sağlamak ve kullanıcıların dilleri değiştirirken zorluk yaşamaması için alttaki <page> kodunu kullanın. <title> İçerisindeki başlık, orijinal başlığı ima eder. #REDIRECT'den sonra gelen başlıksa yönlendirilecek, Türkçe başlıktır. -->
\<title\>\zs.*\ze\<\/title/>
```
```xml
---Bir yönlendirme sayfa örneği (XML)---
  <page>
    <title>English</title>
    <revision>
      <text xml:space="preserve">#REDIRECT [[Türkçe]]</text>
    </revision>
  </page>
```
```

---Deneysel Alan (Büyük bir ihtimalle çalışmayabilir)---
\m\(\(|Yer=\||YerGeçmiş=\|<title>\||Category\:\)\(\[\[\)\=\zs.\(+\)\=\ze\(\]\]\)\=\( (Bölüm\)\@!\( \| -\|- \| - \|-\)\=\(\[\[\)\=\(Monsters\|Canavarları\|Training\|The Future\|Future\|Gelecek\|Mahalleler\|Suburbs\|The Suburbs\|Downtown\|The Downtown\|Şehir Merkezi\|Darklands\|The Darklands\|Karanlık Diyarlar\|The Wilds\|The Wild\|Wilds\|Vahşi Doğa\)\=\(\]\]\)\=
```
