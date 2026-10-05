---
source:
  - pazarlama/uygulamalar/video-recorder/TANITIM-METNI.md
  - video recorder/Sources/VideoRecorderApp/Localizable.xcstrings
layout: default
lang: tr
title: FrameMate kullanım kılavuzu
permalink: /tr/framemate/kilavuz/
alt_url: /en/framemate/guide/
description: FrameMate'te her kayıt modunu, duyacağınız anonsları, kısayolları ve düzen geçişlerini somut örneklerle anlatan kılavuz. VoiceOver kullanıcıları için yazılmıştır.
---
<!-- Kaynak: pazarlama/uygulamalar/video-recorder/TANITIM-METNI.md. Metin orada değişirse burası da güncellenir. -->

# FrameMate kullanım kılavuzu

FrameMate, Mac'inizde dört farklı kayıt yapar ve her birinde ne olacağını size sesli söyler.

**Kamera videosu:** Yalnızca kendinizi çekersiniz; videoyu yatay (YouTube, sunum) ya da dikey (Reels, Shorts, TikTok) alabilirsiniz. Sesi siz seçersiniz: yalnız mikrofonunuz, isterseniz Mac'te çalan sistem sesi de. Kadraj Koçu yüzünüzün çerçevede olup olmadığını, sağa mı sola mı geçmeniz gerektiğini, çok yakın ya da uzak olup olmadığınızı sesli söyler.

**Ekran kaydı:** Tüm ekranı ya da yalnız seçtiğiniz bir pencereyi kaydedersiniz. İsterseniz kendinizi de ekranın üstünde küçük bir kutuda gösterirsiniz; kutuyu dokuz konumdan birine koyar, üç boyuttan birini seçersiniz. Mikrofonunuz ve sistem sesi yine isteğe bağlıdır. Kayıt sürerken kısayolla yalnız kendinize ya da yalnız ekrana geçebilirsiniz.

**Telefon kaydı:** Kabloyla bağladığınız iPhone ya da iPad'in ekranını kaydedersiniz. Video telefonun kendi oranında, dikey, yatay ya da telefon bir yanda siz diğer yanda olacak şekilde yan yana alınabilir. Telefonun sesini videoya ekleyebilir, kulaklığınızla canlı dinleyebilir, kendinizi ekranda gösterebilir ve yine kısayollarla düzeni değiştirebilirsiniz.

**Ses kaydı:** Görüntü olmadan yalnız ses alırsınız: mikrofon, Mac'in sistem sesi ve telefonun sesi birlikte ya da ayrı ayrı.

Uygulamadaki her düğme, ayar ve durum VoiceOver ile seslendirilir; hangi mikrofonun, hangi sesin, hangi düzenin açık olduğunu görmeden her an öğrenirsiniz.
{: .lead}

Bu kılavuz, FrameMate'i görmeden rahatça kullanabilmeniz için hazırlandı. Kılavuzda her kayıt modunu, tuşlara bastığınızda ne duyacağınızı ve kaydettiğiniz videonun nasıl görüneceğini bulabilirsiniz. Uygulama içindeki düğme ve ayar adları burada da birebir aynı kullanılmıştır. Bölümler arasında VoiceOver başlık rotoruyla dolaşabilir ya da aşağıdaki listeden istediğiniz konuya atlayabilirsiniz.

<nav class="toc" aria-labelledby="toc-baslik" markdown="1">
<h2 id="toc-baslik">Bu sayfada</h2>

1. [Başlamadan önce: izinler](#izinler)
2. [Uygulamayı tanıyın: modlar ve durum anonsları](#tanima)
3. [Kamera kaydı ve Kadraj Koçu](#kamera)
4. [Ekran ve pencere kaydı](#ekran)
5. [Düzen geçişleri: "tam ekran video", "tam ekran ekran", "tam ekran telefon"](#duzen)
6. [Telefon ekranı kaydı](#telefon)
7. [Yalnız ses kaydı](#ses)
8. [Kayıt sırasında: kısayollar ve ne duyarsınız](#kayit-sirasi)
9. [Kayıt bitince](#bitis)
10. [Ayarlar](#ayarlar)
11. [Sorun giderme](#sorun)
</nav>

<h2 id="izinler">1. Başlamadan önce: izinler</h2>

Bu bölümde FrameMate'in Mac'inizde çalışabilmesi için hangi izinlere ihtiyaç duyduğunu ve bu izinleri adım adım nasıl vereceğinizi öğreneceksiniz.

macOS, gizliliğinizi korumak için kamera, mikrofon ve ekran kaydı gibi özelliklerde sizden onay ister. FrameMate yalnızca yapacağınız kayıt için gereken izinleri ister:

- **Kamera izni:** Kamera kaydı yaparken, ekran kaydına kendi görüntünüzü eklerken ve telefon ekranı kaydederken gerekir. Mac sistemi bağlı telefonu bir kamera gibi algılar; bu yüzden telefon kaydı için de kamera izni istenir.
- **Mikrofon izni:** Mikrofonunuzla ses kaydettiğiniz her durumda gerekir.
- **Ekran Kaydı izni:** Ekranı, tek bir pencereyi ve **Mac'te çalan sistem sesini** kaydetmek için gerekir. Yalnızca kameranızı veya yalnızca mikrofonunuzu kaydederken bu izin gerekmez.
- **Erişilebilirlik izni:** Bu izin isteğe bağlıdır. Cmd+I ayar duyurusunun, klavye kısayollarının her uygulamadan sorunsuz çalışmasının ve ekran kaydında basılan kısayol tuşlarının videoda görünmesinin yolunu açar. Temel kayıtlar için zorunlu değildir.

FrameMate'i ilk açtığınızda karşınıza dört adımlı bir karşılama ekranı gelir: "Adım 1 / 4: FrameMate'e Hoş Geldin", "Adım 2 / 4: Kayıt Modları", "Adım 3 / 4: Birkaç İzne İhtiyacımız Var" ve "Adım 4 / 4: Nasıl Çalışır?". Üçüncü adımda her izin için ayrı bir düğme yer alır: **Kamera iznini ver**, **Mikrofon iznini ver** ve **Ekran kaydı iznini iste**. Düğmeye bastığınızda macOS kendi standart onay penceresini açar. VoiceOver bu pencereyi okur, siz de "İzin Ver" seçeneğine basarsınız. İzin penceresi bazen FrameMate penceresinin arkasında kalabilir. Sesini duymazsanız pencereler arasında geçiş yapmak için Cmd+Tab tuşlarını kullanabilirsiniz.

Dikkat edilmesi gereken iki önemli nokta:

- **Ekran Kaydı izni verdikten sonra FrameMate'i tamamen kapatıp yeniden açmanız şarttır.** İzni verdiğinizde uygulama "Ekran kaydı izni verildi, değişikliğin geçerli olması için uygulamayı yeniden başlat" anonsunu yapar. Uygulamayı yeniden başlatmazsanız ekran görüntüsü ve sistem sesi kaydedilemez.
- İzni yanlışlıkla reddettiyseniz veya FrameMate listede görünmüyorsa: Mac'inizde **Sistem Ayarları > Gizlilik ve Güvenlik > Ekran Kaydı** bölümüne gidin. FrameMate listede yoksa ekle (artı) düğmesine basın, Uygulamalar klasöründen FrameMate'i seçip ekleyin ve yanındaki anahtarı açık konuma getirin.

Hazır olup olmadığınızı dilediğiniz zaman öğrenebilirsiniz. Uygulama durum satırında örneğin "Hazır durumu: Mikrofon tamam. Ekran kaydı şu anda gerekmiyor. Kamera tamam." şeklinde bilgi verir. İlk 7 gün boyunca tüm kayıt özellikleri sınırsızdır ve hiçbir hesap açmanız gerekmez. 7 günün ardından kayda devam etmek için FrameMate Pro üyeliği gerekir.

[Başa dön](#icerik){: .top}

<h2 id="tanima">2. Uygulamayı tanıyın: modlar ve durum anonsları</h2>

Bu bölümde FrameMate'teki dört kayıt modunu ve kaydın o anki durumunu tek bir tuşla nasıl öğreneceğinizi göreceksiniz.

Kayıt Modu listesinde dört seçenek vardır. Listeyi Boşluk tuşuyla açıp ok tuşlarıyla seçebilir ya da doğrudan kısayolları kullanabilirsiniz:

- **Kamera** (Cmd+1): Yalnız kameranızı kaydeder. Videoyu yatay ya da dikey alırsınız; mikrofonu seçersiniz; isterseniz Mac'te çalan sistem sesi de videoya girer. Kadraj Koçu burada çalışır.
- **Ekran** (Cmd+2): Tüm ekranı ya da seçtiğiniz tek pencereyi kaydeder. Mikrofon ve sistem sesi isteğe bağlıdır. İsterseniz kendinizi ekranın üstünde küçük bir kutuda gösterirsiniz; kutunun yerini dokuz konumdan, boyutunu üç boyuttan seçersiniz.
- **Ses** (Cmd+3): Görüntü kaydetmez. Mikrofon, sistem sesi ve telefonun sesini ayrı ayrı ya da birlikte kaydeder.
- **Telefon Ekranı** (Cmd+4): Kabloyla bağlı iPhone ya da iPad'in ekranını kaydeder. Beş video düzeni, telefon sesi ve kendi görüntünüzü ekleme seçenekleri vardır.

Bir modu seçtiğinizde VoiceOver o modun adını duyurur (örneğin "Mod seçildi: …"). Uygulama, en son seçtiğiniz modu hatırlar ve bir sonraki açılışta aynı modla başlar.

**Kaydın durumunu tek bir kısayolla dinleyin:**
FrameMate öndeyken Cmd+I kısayoluna, başka bir uygulamadayken de Cmd+Option+B kısayoluna basarak durum özeti alabilirsiniz:

- **Kayıt başlamadan önce basarsanız:** Bir sonraki kaydın hazır ayarlarını okur. Örneğin Kamera modundaysanız: "Yatay video, Kamera MacBook Kamerası, mikrofon MacBook Mikrofonu, sistem sesi kapalı, kadraj koçu açık." Ekran modundaysanız: "Kaynak tam ekran, ekran …, mikrofon …, sistem sesi açık, imleç vurgusu açık, kamera kutusu açık." Telefon modundaysanız telefonun bağlı olup olmadığını, seçilen düzeni ve ses ayarlarını söyler. Eksik bir izin varsa cümlenin sonuna "Eksik izinler: …" uyarısını ekler.
- **Kayıt sürerken basarsanız:** O anki kaydın durumunu bildirir: "Kayıt sürüyor. Telefon ekranı, 1 dakika 5 saniye. Düzen Yan yana. Telefon sesi açık. Mikrofon açık." Kaydı duraklattıysanız cümle "Kayıt duraklatıldı." diye başlar. Canlı ekrana bakamadığınız için bu anons çok işinize yarar; hangi seslerin ve hangi düzenin devrede olduğunu kaydı durdurmadan teyit edersiniz.

Kaydı başlatmak için penceredeki **Kaydı Başlat** düğmesine basabilir ya da her uygulamadan çalışan **Cmd+Option+R** kısayolunu kullanabilirsiniz. Geri sayım açıksa "Kayıt 3 saniye sonra başlıyor…" diye geriye doğru sayar; ardından "Kayıt başladı" anonsu duyulur. İsterseniz Ayarlar bölümünden kayıt başlangıç, bitiş ve duraklatma ses efektlerini açabilirsiniz.

[Başa dön](#icerik){: .top}

<h2 id="kamera">3. Kamera kaydı ve Kadraj Koçu</h2>

Bu bölümde kameranızla yatay veya dikey video çekmeyi, mikrofon seçimini ve görmeden kadrajın ortasında kalmanızı sağlayan Kadraj Koçu'nu öğreneceksiniz.

Kamera modunu seçtiğinizde (Cmd+1) karşınıza şu ayarlar çıkar:

- **Video yönü:** İki seçenek vardır. Yatay 1920×1080 (Cmd+Shift+Y) bilgisayar ekranları, sunumlar ve YouTube videoları içindir. Dikey 1080×1920 (Cmd+Shift+D) ise Reels, Shorts ve TikTok gibi telefon odaklı içerikler içindir. Seçtiğinizde "Yatay video seçildi. 1920 çarpı 1080." ya da "Dikey video seçildi. 1080 çarpı 1920." anonsu gelir.
- **Kamera:** Mac'inizin kendi kamerasını, harici bir web kamerasını ya da Süreklilik Kamerası özelliğiyle iPhone'unuzun arka kamerasını seçebilirsiniz. Kamera bulunamazsa uygulama "Kamera bulunamadı. Bir kamera takın." der.
- **Mikrofon:** MacBook mikrofonu, harici mikrofon veya kulaklık mikrofonu arasından seçim yapabilirsiniz. **Mikrofon kanalı** ayarında Otomatik, Mono veya Stereo seçenekleri bulunur. Konuşma ve anlatım kayıtlarında Mono seçeneği genellikle daha temiz ve net bir ses verir.
- **Sistem sesini dahil et:** Mac'inizde o sırada çalan müzikleri, videoları veya uygulamaların seslerini kayda ekler. Yalnızca kendi sesinizi kaydetmek istiyorsanız bu ayarı kapalı tutun. Açmak için Ekran Kaydı izni gerekir.

### Kadraj Koçu: Çerçevenin ortasında kalın

Kameranın karşısına oturduğunuzda yüzünüzün tam ortada olup olmadığını ekrana bakmadan bilemezsiniz. Kadraj Koçu, kameradaki görüntünüzü takip eder ve duruşunuzu düzeltmeniz için size sesli yönlendirmeler verir.

Kadraj Koçu'nu **Cmd+D** kısayoluyla (veya başka uygulamadayken **Cmd+Option+O** ile) açıp kapatabilirsiniz. Açıldığında "Kadraj koçu açık" duyulur.

Kadraj Koçu kamerayı izler ve yapmanız gereken en önemli düzeltmeyi söyler. Duyabileceğiniz anonslardan bazıları:

- "Yüz algılanamıyor, kameraya bak": Kamera yüzünüzü göremiyor.
- "Kadraja tam girmiyorsun, biraz sağa gel" ya da "…biraz sola gel": Yüzünüz ekranın kenarına çok yaklaşmış.
- "Çok yakınsın, biraz uzaklaş. Omuzların ve göğsün de görünsün." ya da "Kadraj çok uzak, biraz yaklaş."
- "Kamerayı biraz yukarı al", "kamerayı biraz aşağı indir", "biraz sağa geç": Kameranın açısını veya oturuşunuzu ayarlama önerileri.
- "Işık düşük, lambayı aç veya ekran parlaklığını artır."
- "Kadraj uygun": Her şey yolunda, kayda hazırsınız.

Kameranın karşısında birden fazla kişi varsa önce kişi sayısını bildirir: "Bir kişi görünüyor", "İki kişi görünüyor" veya "Üç kişi görünüyor". Üçten fazla kişi varsa "Üçten fazla kişi görünüyor, en öne çıkan üç kişiye göre yönlendiriliyor" der. Yönlendirmeler de kişiyi belirtir: "Soldaki kişi kadraja tam girmiyor, biraz sağa gelsin", "Sağdaki kişi kameraya daha yakın, biraz geri gelsin" veya "Aranız çok açık, birbirinize biraz yaklaşın". Tek veya iki kişilik çekim kuralları otomatik devreye girer; fazladan bir ayar yapmanız gerekmez.

**Önemli kural:** Kadraj Koçu kayıt başladıktan sonra susar. Çünkü konuşmaya devam ederse kendi sesi videonun içine girer. Bu yüzden kadrajınızı kayıt başlamadan önce, hazırlık aşamasında ayarlarsınız. Kayıt bittiğinde Kadraj Koçu yeniden konuşmaya başlar.

Kadraj Koçu'nun davranışını Ayarlar penceresinden değiştirebilirsiniz:

- **Geri bildirim sıklığı:** Minimal (yalnızca belirgin kaymalarda konuşur), Dengeli veya Sık (birkaç saniyede bir durum bildirir).
- **Aynı uyarıyı tekrarla:** Bir uyarının kaç saniye arayla yineleneceğini belirler.
- **Yönlendirmenin nasıl iletileceği:** Otomatik (VoiceOver açıksa VoiceOver anonsu, kapalıysa uygulamanın kendi sesi konuşur), VoiceOver, Uygulama sesi ya da Sessiz.
- **Yönlendirme sesi:** Kapalı, Sadece yön sesi ya da Yön sesi ve konuşma. "Yön sesi" açıkken kulaklık takarsanız, hareket etmeniz gereken yönü sesin geldiği kulaktan anlarsınız: Ses sağ kulağınızdan geliyorsa sağa, sol kulağınızdan geliyorsa sola kaymanız gerekir.
- **Merkez onayı çal:** Yüzünüz tam merkeze oturduğunda kısa bir onay sesi çalar; doğru yeri bulduğunuzu hemen anlarsınız.
- **Ekranda yönlendirme metnini göster:** Sesli uyarıların metnini ekrana da yazar.

### Otomatik yeniden kadrajlama

Bu özelliği **Cmd+Shift+A** kısayoluyla açıp kapatabilirsiniz. Açıldığında "Otomatik yeniden kadrajlama açık" duyulur. Tek başınıza video çekerken koltuğunuzda sağa sola hareket etseniz bile, yazılım görüntüyü dengeler ve yüzünüzü çerçevenin ortasında tutar. Bu düzeltme bitmiş videoya uygulanır.

[Başa dön](#icerik){: .top}

<h2 id="ekran">4. Ekran ve pencere kaydı</h2>

Bu bölümde Mac ekranınızı veya belirli bir pencereyi nasıl kaydedeceğinizi, ses seçeneklerini ve ekranın köşesine kendi kameranızı nasıl ekleyeceğinizi öğreneceksiniz.

Ekran moduna geçtiğinizde (Cmd+2) önce görüntünün kaynağını seçersiniz:

- **Tam ekran:** Mac'inizin tüm ekranını kaydeder. Birden fazla monitör kullanıyorsanız Ekran seçimi listesinden istediğiniz ekranı belirlersiniz.
- **Pencere:** Yalnızca tek bir uygulamanın penceresini kaydeder. Pencere seçimi listesinden istediğiniz pencereyi seçebilirsiniz. Pencerenin ekranda açık ve önde durması gerekir; simge durumuna küçültülmüş pencereler siyah bir görüntü olarak kaydedilir (ayrıntılar için bkz. [Sorun giderme](#sorun)).

Ardından ses kaynaklarını belirlersiniz:

- **Mikrofon:** Kendi sesinizi ve anlatımınızı kaydetmek için kullanılır.
- **Sistem sesini dahil et:** Mac'inizde çalan tüm sesleri (videolar, müzikler, internet aramaları veya uygulama bildirimleri) videoya ekler. Örneğin bir programı tanıtırken onun sesini de duyurmak istiyorsanız bu seçeneği açın. Yalnızca kendi sesiniz yeterliyse kapalı bırakabilirsiniz. Sistem sesi seviyesi ile mikrofon seviyesini ayrı ayrı ayarlayabilirsiniz; böylece kendi sesiniz arka plan seslerinin altında ezilmez.
- Bilgisayarın hoparlöründen çıkan ses mikrofona geri dönebilir. Hem mikrofonu hem de sistem sesini aynı anda kaydediyorsanız kulaklık takmanız yankıyı önler.

Görsel anlatım yardımcıları:

- **İmleci vurgula** (Cmd+Shift+C): Fare imlecinin etrafına belirgin bir halka ekler ve tıkladığınız yerleri vurgular. Videoyu izleyenler nereye tıkladığınızı rahatça takip eder. Açıldığında "İmleç vurgusu açık" duyulur.
- **Klavye kısayollarını göster:** Kayıt sırasında bastığınız kısayol tuşlarını (Cmd, Control, Option gibi) videonun üzerinde kısa süreyle gösterir. Bu özellik için Erişilebilirlik izni gerekir.

### Kamera kutusu: Ekranın istediğiniz yerinde kendi görüntünüz

Ekran kaydı yaparken **Kamera Kutusu** ayarını açarsanız, kendi kameranız ekran görüntüsünün üzerine küçük bir kutu olarak yerleşir. Tıpkı televizyondaki haber bültenlerinde ya da oyun yayınlarında sunucunun köşede görünmesi gibidir.

Kamera kutusunda şu ayarları yapabilirsiniz:

- **Kamera kutusu için kamera:** Mac kamerası, harici kamera veya iPhone kamerası.
- **Kamera konumu:** Dokuz farklı konum seçebilirsiniz: Üst Sol, Üst Orta, Üst Sağ, Orta Sol, Merkez, Orta Sağ, Alt Sol, Alt Orta, Alt Sağ. Köşeleri, kenarların ortasını ya da tam merkezi seçebilirsiniz. Ekrandaki önemli yerleri kapatmayan bir konum iyi olur; çoğu kişi Alt Sağ ya da Alt Sol kullanır.
- **Kamera boyutu:** Küçük, Orta ya da Büyük.

Kamera kutusu açıkken videonuzda ekranınız ve siz birlikte görünürsünüz. Kayıt sürerken kısayolla yalnız kendinize ya da yalnız ekrana da geçebilirsiniz; bunu bir sonraki bölümde anlatıyoruz.

Bir konum veya boyut seçtiğinizde VoiceOver çıktıyı örneğin "Çıktı önizlemesi. Kamera kutusu Alt Sağ konumunda ve Orta boyutta." şeklinde okur; böylece kutunun nereye yerleştiğini hemen anlarsınız. Kamera kutusu devredeyken Kadraj Koçu da bu kutudaki duruşunuz için çalışır. Kamera kutusunu kayıt başladıktan sonra kapatıp açamazsınız; ancak kayıt sürerken kendinizi tam ekrana büyütüp küçültebilirsiniz. Bunu bir sonraki bölümde inceleyelim.

[Başa dön](#icerik){: .top}

<h2 id="duzen">5. Düzen geçişleri: "tam ekran video", "tam ekran ekran", "tam ekran telefon"</h2>

Bu bölümde, ekran veya telefon kaydı yaparken görüntünün biçimini kısayollarla nasıl değiştireceğinizi öğreneceksiniz.

Kamera kutusu açıkken bir ekran veya telefon kaydı yapıyorsanız, kayıt sürerken tek bir kısayolla görüntünün biçimini (düzenini) değiştirebilirsiniz. Bu terimlerin izleyici için ne anlama geldiğini günlük hayattan örneklerle açıklayalım:

- **Varsayılan düzen** (Cmd+Option+G):
  - **Nasıl görünür?** Televizyondaki eğitim videolarını veya oyun yayınlarını düşünün: Bilgisayar ekranınız bütün kareyi kaplar, sizin görüntünüz ise seçtiğiniz köşede küçük bir kutu içinde yer alır.
  - **Ne zaman kullanılır?** Başlangıçtaki normal görünümünüze geri dönmek istediğinizde bu kısayola basarsınız. (Telefon kaydında yan yana bir düzen seçtiyseniz, bu tuş yine o yan yana düzene geri döndürür ve anonsu "Yan yana" olur.)
- **Tam ekran video** (Cmd+Option+V):
  - **Nasıl görünür?** Televizyon haberlerinde spikerin ekrana tek başına gelip doğrudan seyirciyle konuştuğu anlar gibidir. Bilgisayar ekranınız veya telefonunuz tamamen gizlenir; izleyenler yalnızca sizin kameranızı, yani bütün karede sadece sizi görür.
  - **Ne zaman kullanılır?** Ekrana bir şey yansıtmadan doğrudan izleyiciye hitap edeceğiniz anlar için idealdir: Giriş konuşması yaparken, konuyu özetlerken veya videoyu kapatırken.
- **Tam ekran ekran** (Cmd+Option+E):
  - **Nasıl görünür?** Sunum yaparken slaytı tek başına ekrana vermek gibidir. Köşedeki kamera kutunuz gizlenir; izleyenler sizi görmez, videoda yalnızca Mac'inizin ekranı görünür.
  - **Ne zaman kullanılır?** Ekrandaki küçük bir yazıyı, tablonun köşesini veya kameranın kapatabileceği önemli bir ayrıntıyı gösterirken kullanılır.
  - **Telefon kaydındaki karşılığı:** Telefon kaydı yaparken bu seçeneğin adı **Tam ekran telefon** olur. Kamera kutunuz gizlenir ve videoda yalnızca telefonunuzun ekranı görünür.
- **Yan yana** (Telefon kaydındaki yan yana düzenler için):
  - **Nasıl görünür?** Televizyon tartışma programlarında ekranın ikiye bölünmesi gibidir. Sol yarıda telefon ekranı, sağ yarıda ise siz büyük boy yer alırsınız (ya da tam tersi).

Kısayol tuşuna bastığınızda seçtiğiniz düzenin adı anons edilir: "Tam ekran video", "Tam ekran ekran", "Tam ekran telefon", "Varsayılan düzen" ya da "Yan yana". Anonsun ardından kısa bir onay sesi çalar; bu onay sesi videonun içine girmez. Aynı tuşa tekrar basarsanız o düzenden çıkmazsınız, sadece nerede olduğunuzu yeniden duyarsınız. Başka bir düzene geçmek için ilgili kısayola basmanız, başlangıçtaki görünümünüze dönmek içinse **Cmd+Option+G** tuşlarına basmanız yeterlidir.

Aklınızda bulunması gereken üç önemli kural:

- **Değişim o anda ekrandaki canlı önizlemede görünmez; doğrudan bitmiş videoda ortaya çıkar.** Kayıt sırasında hiçbir görüntü kesintiye uğramaz; geçişler videoda çeyrek saniyelik yumuşak bir akışla gerçekleşir.
- Kayıtta kamera kutusu kapalıysa bu tuşlar çalışmaz. Bastığınızda uygulama "Bu kayıtta kamera kutusu yok. Kayıt başlamadan önce kamera kutusunu açın." der. Kamera kutusunu açma kapama kısayolu (**Cmd+Option+K**) yalnızca kayıt başlamadan önce kullanılabilir.
- Bu kısayolları kayıt başlamadan önce de kullanabilirsiniz. Böylece kaydın doğrudan hangi görünümle **başlayacağını** önceden seçmiş olursunuz. Örneğin kayda girmeden önce Cmd+Option+V'ye basarsanız video sizin tam ekran görüntünüzle açılır. Hangi düzende olduğunuzu unutursanız **Cmd+Option+B** kısayolu durumu hemen söyler.

**Örnek bir ders kaydı senaryosu:** Kamera kutusunu Alt Sağ konuma ve Orta boyuta ayarlayın. Kayda başlamadan önce Cmd+Option+V'ye basın ("Tam ekran video" duyulur). Kaydı başlatıp izleyicilere kendinizi tanıtın ve dersi özetleyin. Ardından Cmd+Option+G'ye basarak varsayılan düzene geçin ("Varsayılan düzen" duyulur); Mac ekranınız tam boy gelir, siz de köşede görünürsünüz. Ekrandaki bir detayı gösterirken Cmd+Option+E ile kendinizi gizleyin ("Tam ekran ekran"). Dersi bitirirken tekrar Cmd+Option+V ile tam ekran kendinize geçip veda edin.

[Başa dön](#icerik){: .top}

<h2 id="telefon">6. Telefon ekranı kaydı</h2>

Bu bölümde iPhone veya iPad ekranınızı kabloyla Mac'e bağlayıp nasıl kaydedeceğinizi, düzen seçeneklerini ve ses ayarlarını öğreneceksiniz.

Bu mod, iPhone veya iPad ekranınızı bir kablo aracılığıyla Mac'e aktarıp yüksek kalitede kaydeder. Kablosuz olarak çalışmaz; cihazın Mac'e kabloyla bağlı olması şarttır.

**Kayda hazırlık adımları:**

1. Telefonunuzu kabloyla Mac'e bağlayın.
2. Telefonunuzun ekran kilidini açın. Ekran kilitliyken Mac'e görüntü aktarılmaz.
3. Telefonda "Bu bilgisayara güvenilsin mi?" uyarısı çıkarsa "Güven" seçeneğine dokunun ve şifrenizi girin.
4. FrameMate'te Kayıt Modu olarak Telefon Ekranı'nı seçin (Cmd+4). Durum satırında önce "… bulundu, bağlanıyor." duyulur, ardından "… hazır." anonsu gelir. Cihaz henüz hazır değilse "Telefon bağlı değil. Kabloyu takın ve telefonun kilidini açın." ya da "Telefon henüz hazır değil. Görüntü gelene kadar bekleyin." uyarısı verilir.
5. Mac'e birden fazla cihaz bağlıysa **Telefon seçimi** listesinden kaydedeceğiniz cihazı belirleyin.

**Video düzeni seçenekleri:**
Uygulamada beş farklı düzen seçeneği vardır. Yaptığınız seçim bir sonraki açılışta hatırlanır:

1. **Telefon oranını koru:** Kenarlık veya siyah şerit eklemez; videoyu telefonun kendi doğal ekran ölçülerinde kaydeder. Instagram hikâyesi ya da uygulama tanıtımı gibi yalnız telefonu gösterdiğiniz videolar için en uygun seçenektir.
2. **1080 çarpı 1920 dikey:** Reels, YouTube Shorts ve TikTok için standart dikey video ölçüsüdür. Telefon ekranı dikey karenin tam ortasına yerleştirilir.
3. **1920 çarpı 1080 yatay:** YouTube veya bilgisayar sunumları için standart yatay video ölçüsüdür. Dikey telefon ekranı ortada durur, iki yanında boşluk kalır.
4. **Yan yana yatay, kamera sağda:** Yatay bir videoda ekran ikiye bölünür; telefon ekranı solda tam boy, sizin görüntünüz sağda büyük boy yer alır.
5. **Yan yana yatay, kamera solda:** Telefon ekranı sağda, sizin görüntünüz solda büyük boy yer alır.

Yan yana düzenleri kullanabilmek için **Kamera Kutusu'nun açık olması şarttır**. Kapalıysa uygulama sizi uyarır ve video otomatik olarak ortalanmış yatay düzene geçer.

**Ses ayarları ve önemli kurallar:**

- **Telefon sesini kaydet:** Telefonda çalan müzik, video ve uygulama seslerini kaydın içine ekler. Kapalı tutarsanız video sessiz kaydedilir (mikrofonunuz hariç).
- **Telefonda VoiceOver kullanıyorsanız:** VoiceOver'ın konuşması da telefon sesi sayılır ve kaydın içine girer. Bu bilinçli bir tercih olmalıdır: Bir VoiceOver kullanım eğitimi hazırlıyorsanız bu sesi açık bırakırsınız; ancak VoiceOver konuşmasının videoda çıkmasını istemiyorsanız **Telefon sesini kaydet** seçeneğini kapatmanız gerekir.
- **Telefon sesini hoparlörden duy** (Cmd+Shift+H): Telefon Mac'e kabloyla bağlandığında sesi Mac'e aktarılır ve kendi hoparlöründen çıkmaz. Telefonu kullanırken ne yaptığınızı duymak için bu ayarı açık tutmalısınız; aksi halde telefondan hiçbir ses alamazsınız. Bu ayar yalnızca sizin duymanızı sağlar, kayda nelerin gireceğini değiştirmez.
- **Kulaklıkla dinleme:** Mac'inize kulaklık taktıysanız ve Telefon sesini hoparlörden duy açıksa, telefondan gelen her şey, telefonda VoiceOver konuşuyorsa onun sesi de, kulaklığınızdan gelir. Kaydın içinde ne olacağını ise ayrıca Telefon sesini kaydet belirler. Yani üç şey birbirinden bağımsızdır: telefon sesi kayda girsin mi, siz telefonu dinleyin mi, mikrofonunuz kayda girsin mi. İsterseniz telefonu kulaklıktan dinleyip videoya yalnız kendi sesinizi, ya da yalnız telefon sesini koyabilirsiniz.
- **Yankıyı önlemek için mutlaka kulaklık takın.** Telefonun sesi Mac hoparlöründen çıkarken mikrofonunuz da açıksa, telefon sesi mikrofona girip yankı oluşturur. FrameMate bu durumu "Telefon sesi hoparlörden çalarken mikrofon da kaydediyor. Yankıyı önlemek için kulaklık kullanın." diye haber verir. Mac'in sistem sesi de açıksa telefon sesi videoya iki kez girebilir; bu durumda sistem sesini kapatın.

**Kayıt sırasında düzen değiştirme:**
Telefon kaydında da düzen kısayolları aynı şekilde çalışır. Yan yana bir düzen seçtiyseniz: **Cmd+Option+V** sizi tam ekran yapar, **Cmd+Option+E** telefonu tek başına tam ekrana yayar ("Tam ekran telefon"), **Cmd+Option+G** ise yeniden yan yana düzene döndürür ("Yan yana"). Ayrıntılı mantık için [Düzen geçişleri](#duzen) bölümüne bakabilirsiniz.

**Karşılaşılabilecek durumlar:**

- **Telefon ekranı tamamen siyah görünüyorsa:** Telefonda VoiceOver ekran perdesi açık kalmış olabilir. Üç parmağınızla ekrana üç kez art arda dokunarak ekran perdesini kapatın. Telefon uyku moduna geçtiyse ekranı uyandırın. FrameMate siyah görüntüyü kayıt sırasında "Telefon ekranı siyah görünüyor" diyerek haber verir.
- **Telefonu yatay veya dikey çevirdiğinizde:** Uygulama "Telefon yatay çevrildi. Görüntü kayıt tuvaline sığdırılıyor." şeklinde bilgi verir ve görüntüyü seçtiğiniz video kalıbına uygun şekilde yeniden hizalar.
- **Kablo yerinden çıkarsa:** Kayıt güvenle sonlandırılır ve önceki bölüm korunur: "Telefon bağlantısı kesildi. Kayıt durduruluyor."
- Görüntü hiçbir şekilde gelmiyorsa telefon kilidini açın, bilgisayara güven onayını verin ve kabloyu çıkarıp tekrar takın.

[Başa dön](#icerik){: .top}

<h2 id="ses">7. Yalnız ses kaydı</h2>

Bu bölümde görüntü olmadan yalnızca ses kaydı almayı (podcast, toplantı veya sesli notlar gibi) öğreneceksiniz.

Görüntüye ihtiyaç duymadığınız podcast, ders anlatımı veya sesli not kayıtları için Ses modunu (Cmd+3) kullanabilirsiniz:

- **Mikrofon** seçiminizi yapın; isterseniz Mac'te çalan sesleri ya da toplantıdaki karşı tarafın sesini eklemek için **Sistem sesi** seçeneğini de açın. Kayda başlayabilmek için bu ikisinden en az birinin açık olması gerekir; aksi halde uygulama "Ses kaydı için bir mikrofon seçin ya da sistem sesini dahil edin." uyarısını verir.
- **Mikrofon kanalı:** Otomatik, Mono veya Stereo arasından seçim yapabilirsiniz.
- Kaydı başlatmak için **Ses Kaydını Başlat** düğmesine basabilir veya **Cmd+Option+5** kısayolunu kullanabilirsiniz. Kaydı bitirmek için aynı tuşa tekrar basmanız yeterlidir.
- Kayıt bittiğinde dosyanız bir **M4A** ses dosyası olarak kaydedilir.

Telefonun sesini de kaydetmek istiyorsanız kabloyla bağlı telefonu seçip **Telefon sesi** seçeneğini açabilirsiniz; Mac'inizin sesi, telefonun sesi ve mikrofon aynı kayda birlikte girebilir.

Kayıt sırasında **Cmd+Option+B** kısayoluna basarak durumu dilediğiniz an öğrenebilirsiniz: "Mikrofon …, sistem sesi açık." İhtiyaç duyduğunuzda kaydı **Cmd+Option+P** ile duraklatabilir ve aynı tuşla sürdürebilirsiniz.

[Başa dön](#icerik){: .top}

<h2 id="kayit-sirasi">8. Kayıt sırasında: kısayollar ve ne duyarsınız</h2>

Bu bölümde kayıt sürerken başka bir uygulamadayken bile kullanabileceğiniz genel kısayolları ve bu tuşlara bastığınızda alacağınız sesli geri bildirimleri öğreneceksiniz.

FrameMate'in genel kısayolları, uygulama arka plandayken veya başka bir programda çalışırken de geçerlidir. Bir kısayola bastığınızda uygulama neyi değiştirdiğini sesli olarak bildirir:

- **Cmd+Option+R:** Kaydı başlatır veya durdurur. Kayıt başlarken "Kayıt başladı", durdurulduğunda ise sırasıyla "Kayıt durdu. Dosya hazırlanıyor" ve "Kayıt tamamlandı, dosya hazır" anonsları duyulur.
- **Cmd+Option+5:** Ses kaydını başlatır ya da durdurur.
- **Cmd+Option+P:** Kaydı duraklatır ("Kayıt duraklatıldı.") ya da devam ettirir. Duraklatılan bölümler videoda yer almaz, kayıt kaldığı yerden temiz şekilde devam eder.
- **Cmd+Option+V, E, G:** Görüntü düzenini değiştirir (ayrıntılar için bkz. [Düzen geçişleri](#duzen)).
- **Cmd+Option+K:** Kayıt başlamadan önce kamera kutusunu açar ya da kapatır ("Kamera kutusu açık", "Kamera kutusu kapalı").
- **Cmd+Option+S:** Sistem sesini açar ya da kapatır. Duyulan anons: "Sistem sesi açık." veya "Sistem sesi kapalı."
- **Cmd+Option+F:** Telefon sesini açar ya da kapatır.
- **Cmd+Option+M:** Mikrofonu açar ya da sessize alır. Konuşurken öksürmeniz gerektiğinde ya da yanınızdaki biriyle kısa bir şey konuşurken kaydı durdurmadan mikrofonu kapatıp ardından tekrar açabilirsiniz.
- **Cmd+Option+B:** O anki kayıt durumunu özetler.
- **Cmd+Option+O:** Kadraj Koçu'nu açar ya da kapatır (Kadraj Koçu kayıt sırasında zaten sessiz kalır).

FrameMate penceresi öndeyken kullanabileceğiniz pratik kısayollar: Mod seçimi için Cmd+1 ile Cmd+4 arası; video yönü için Cmd+Shift+Y ve Cmd+Shift+D; imleç vurgusu için Cmd+Shift+C; otomatik kadraj için Cmd+Shift+A; telefon sesini hoparlörden duyma için Cmd+Shift+H; son kaydı açmak için Cmd+Shift+O; Finder'da göstermek için Cmd+Shift+F; Kadraj Koçu için Cmd+D; ayar özetini dinlemek için Cmd+I.

**Önemli kural:** Kayıt sırasında bir kısayol tuşu yalnızca o kayıtta önceden seçilmiş olan özellikleri değiştirebilir. Örneğin kayda başlarken telefon sesini açmadıysanız, kayıt sürerken Cmd+Option+F tuşuna bastığınızda uygulama "Bu kayıtta telefon sesi yok. Kayıt başlamadan önce telefon sesini açın." der. Çünkü başlamış bir videoya sonradan sıfırdan yeni bir ses kanalı eklenemez; aynı kural mikrofon, sistem sesi ve kamera kutusu için de geçerlidir. O kayıtta karşılığı olmayan bir tuşa bastığınızda (örneğin yalnızca ses kaydederken görüntü düzeni tuşuna basarsanız) FrameMate arka plandayken sessiz kalır, pencere öndeyken ise neden çalışmadığını açıklar.

**Güvenlik önlemleri:**
- Kaydı duraklatırsanız unutmayın; **Cmd+Option+B** kısayolu "Kayıt duraklatıldı." diye hatırlatır.
- Mikrofonun kablosu çıkarsa kayıt kendiliğinden duraklatılır ve "Mikrofon bağlantısı kesildi. Kayıt duraklatıldı. Mikrofonu yeniden takıp Devam Et'e basabilirsin." uyarısı gelir.
- Disk alanı azalırsa "Disk alanı azalıyor." uyarısı alırsınız; kritik seviyeye inerse dosyanın bozulmaması için kayıt güvenle durdurulup kaydedilir.
- Mac'iniz uyku moduna geçmek üzereyse kayıt yine güvenle tamamlanıp saklanır.

[Başa dön](#icerik){: .top}

<h2 id="bitis">9. Kayıt bitince</h2>

Bu bölümde kayıt durduktan sonra dosyanıza nasıl erişeceğinizi, dosyayı nasıl kontrol edip yeniden adlandıracağınızı öğreneceksiniz.

Kaydı durdurduğunuzda video dosyanız işlenir. Bu sırada pencere açık kalır ve işlem tamamlandığında "Kayıt tamamlandı, dosya hazır" anonsu duyulur. Pencerede şu seçenekler yer alır:

- **Son Kaydı Aç** (Cmd+Shift+O): Kaydettiğiniz dosyayı Mac'inizin saptanmış oynatıcısında hemen açar. Böylece kaydı vakit kaybetmeden dinleyip izleyebilirsiniz.
- **Klasörde Göster** (Cmd+Shift+F): Finder uygulamasını açarak kaydın bulunduğu klasörü ve dosyayı seçili olarak gösterir.
- **Yeniden Adlandır:** Dosyaya yeni bir isim vermenizi sağlar; dosya uzantısını yazmanıza gerek yoktur, otomatik olarak eklenir. İşlem tamamlanınca "Yeniden adlandırıldı: …" anonsu gelir.
- **Farklı Kaydet:** Kayıt dosyasını dilediğiniz başka bir klasöre kopyalar.

Ekran, kamera ve telefon kayıtları 1080p kalitesinde standart **MP4** formatında; ses kayıtları ise **M4A** formatında kaydedilir. Kayıtların bilgisayarınızda hangi klasörde toplanacağını **Varsayılan kayıt klasörü** ayarından belirleyebilirsiniz.

[Başa dön](#icerik){: .top}

<h2 id="ayarlar">10. Ayarlar</h2>

Bu bölümde FrameMate'in kayıt süreleri, ses efektleri ve çalışma tercihlerini kendi kullanım alışkanlıklarınıza göre nasıl özelleştireceğinizi öğreneceksiniz.

Ayarlar penceresinde kayıt deneyiminizi kolaylaştıran şu seçenekler bulunur:

- **Geri sayım süresi:** Kaydı Başlat dedikten kaç saniye sonra kaydın başlayacağını belirler (örneğin 3 saniye).
- **Maksimum kayıt süresi:** Sınırsız kayıt yapabilir ya da hazır süreler arasından seçim yapabilirsiniz. İsterseniz 5 saniye ile 60 dakika arasında Özel bir süre sınırı da belirleyebilirsiniz. Süre dolduğunda kayıt kendiliğinden güvenle durur.
- **Kayıt sonu uyarısı:** Belirlediğiniz süre dolmadan önceki son 3, 5 veya 10 saniyede geri sayım sesi ve sesli uyarı verir. Kaydı yarıda kesmez.
- **Kayıt süresini düzenli olarak hatırlat** ve **Hatırlatma şekli:** Kayıt sürerken geçen süreyi periyodik olarak bildirir. Sesli okuma seçilirse VoiceOver geçen süreyi söyler; Ses efekti seçilirse yalnızca kısa bir tık sesi çalar. Dahili mikrofonla kayıt yapıyorsanız bu uyarıların mikrofona girmemesi için kulaklık takmanız ya da hatırlatmayı kapatmanız önerilir.
- **Ses efekti:** Kayıt başladı, durdu, duraklatıldı durumlarında ve kısayol tuşlarına basıldığında çalan kısa onay sesleridir. Bu efektler videonun içine girmez.
- **Canlı düzen:** Kayıt sırasında düzen değiştiğinde yapılacak bildirimleri yönetir: "Canlı düzen değişimini duyur" ve "Canlı düzen sesini çal".
- **Kayıt başlarken pencereyi gizle** ve **Kayıt bitince pencereyi geri aç:** Ekran kaydederken FrameMate'in kendi penceresinin videoda görünmesini engeller.
- **Dock'ta göster** ya da **Yalnızca menü çubuğunda çalıştır;** uygulamanın nerede duracağını belirler. Ayrıca **Girişte otomatik başlat** seçeneği de bulunur.
- **Varsayılan kayıt klasörü:** Tüm video ve ses kayıtlarınızın otomatik olarak kaydedileceği klasörü seçmenizi sağlar.
- **Hızlı Yardım:** Uygulama içindeki kısa kullanım rehberine buradan ulaşabilirsiniz. **Yardım ve Destek**, **Gizlilik Politikası** ve **Kullanım Koşulları** sayfalarının bağlantıları da bu ekrandadır.

[Başa dön](#icerik){: .top}

<h2 id="sorun">11. Sorun giderme</h2>

Bu bölümde karşılaşabileceğiniz olası aksaklıkları ve bunların pratik çözümlerini bulabilirsiniz.

- **Kamera, mikrofon ya da ekran kaydı çalışmıyorsa:** Mac'inizde **Sistem Ayarları > Gizlilik ve Güvenlik** yolunu izleyerek ilgili izinlerin açık olup olmadığını kontrol edin.
- **FrameMate Ekran Kaydı listesinde görünmüyorsa:** Ekran Kaydı ayarlarındaki ekle (artı) düğmesine basın, Uygulamalar klasöründen FrameMate'i seçin, anahtarı açın ve uygulamayı yeniden başlatın. İzin penceresi bazen başka pencerelerin arkasında kalabilir.
- **Sistem sesi videoya girmiyorsa:** Ekran Kaydı iznini kontrol edin ve izin verdikten sonra FrameMate'i tamamen kapatıp yeniden açtığınızdan emin olun.
- **Telefondan görüntü gelmiyorsa:** Telefonun ekran kilidini açın, ekrandaki "Güven" sorusunu onaylayın, kabloyu çıkarıp yeniden takın.
- **Telefon sesi telefonun kendi hoparlöründen çıkmaya başladıysa:** Kabloyu çıkarıp yeniden takın.
- **Kaydedilen pencere ya da ekran simsiyah görünüyorsa:** Pencerenin ekranda açık ve önde olduğundan, küçültülmüş ya da şeffaf olmadığından emin olun. Ekranın uyku modunda olup olmadığını kontrol edin. FrameMate kayıt sürerken böyle bir durum olursa "Ekran görüntüsü tamamen siyah görünüyor…" uyarısını verir. (Gerçekten siyah temalı bir pencere kaydediyor olabileceğiniz için bu uyarı kaydı durdurmaz.)
- **Videoda bir ses ya da kamera eksik çıktıysa:** Kayda başlamadan önce ilgili anahtarın altındaki bilgilere dikkat edin; hazır olmayan aygıtlar adıyla belirtilir. Ayrıca çalışmayan bir kısayola bastığınızda uygulama neden çalışmadığını söyler.
- **Duyurular ve kısayollar güvenilir şekilde çalışmıyorsa:** Sistem Ayarları > Gizlilik ve Güvenlik > Erişilebilirlik bölümünden FrameMate'e izin verin.

Başka bir konuda yardıma ihtiyaç duyarsanız uygulama içindeki Yardım ve Destek bağlantısını ya da sitemizdeki Destek sayfasını kullanabilirsiniz.

[Başa dön](#icerik){: .top}
