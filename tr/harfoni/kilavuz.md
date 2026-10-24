---
source:
  - harfoni/app/Views/HowToPlayView.swift
  - harfoni/app/Services/AccessPolicy.swift
  - harfoni/app/Models/AnagramGame.swift
layout: default
lang: tr
title: Harfoni kullanım kılavuzu
permalink: /tr/harfoni/kilavuz/
alt_url: /en/harfoni/guide/
description: Harfoni'nin oyun türleri, puan, rütbe ve ipucu kuralları ile Dokunmatik Alan hareketleri. VoiceOver kullanıcıları için yazılmıştır.
---
<!-- Kaynak: uygulamadaki Nasıl Oynanır ekranı (HowToPlayView.swift) ve ücretsiz sınırlar (AccessPolicy.swift, AnagramGame.swift). Uygulamada değişirse burası da güncellenir. -->

# Harfoni kullanım kılavuzu

Bu kılavuz, Harfoni'deki Nasıl Oynanır ekranının anlattıklarını tek sayfada toplar. Başlıklar arasında VoiceOver başlık rotoruyla geçebilir ya da aşağıdaki listeden doğrudan bir bölüme gidebilirsiniz.
{: .lead}

<nav class="toc" aria-labelledby="toc-baslik" markdown="1">
<h2 id="toc-baslik">Bu sayfada</h2>

1. [Oyunun kuralı](#kural)
2. [Bölümler](#bolumler)
3. [Puan ve rütbeler](#puan)
4. [Kontroller](#kontroller)
5. [İpuçları ve ipucu hakları](#ipucu)
6. [Günün Bulmacası](#gunun-bulmacasi)
7. [Zamana Karşı](#zamana-karsi)
8. [Anagram](#anagram)
9. [Dokunmatik Alan](#dokunmatik-alan)
10. [Ücretsiz sürüm ve Tam Sürüm](#ucret)
</nav>

<h2 id="kural">1. Oyunun kuralı</h2>

Size bir kelimenin harfleri karışık verilir. Bu harflerle anlamlı Türkçe kelimeler kurarsınız. Her harfi bir kelimede en fazla verildiği kadar kullanabilirsiniz; harflerin hepsini kullanmak zorunda değilsiniz.

- **Hedef kelime:** bölümde bulmanız gereken kelimeler. Hepsi bulununca bölüm biter.
- **Bonus kelime:** hedefte olmayan ama geçerli kelime. 1 puan verir.

Yaygın Türkçe kelimeler ve sık kullanılan çekimleri geçer. Özel adlar, kısaltmalar ve çok nadir kelimeler sayılmaz.

Kabul edilen en kısa kelime harf sayısına göre değişir; bölümün başında ve durum özetinde söylenir. Bölümde başka bir aralık yazmıyorsa genel kural şöyledir: 4 harfte 3–4, 5 harfte 3–5, 6 harfte 4–6, 7 harfte 5–7, 8 harfte 6–8 harfli kelimeler.

[Başa dön](#icerik){: .top}

<h2 id="bolumler">2. Bölümler</h2>

Bölümler tek sırayla ilerler. Ana ekrandaki **Devam et** düğmesi sizi her zaman sıradaki bölüme götürür. Biten bölümler sırası gelmeden tekrar oynanmaz.

Bölüme ara verirseniz bulduğunuz kelimeler kaydedilir; döndüğünüzde kaldığınız yerden sürersiniz. İlerledikçe harf sayısı ve kelime uzunluğu artar; arada kolay bölümler de gelir.

Bölüm sonunda isterseniz oyuna dönüp kalan bonus kelimeleri aramaya devam edebilir ya da bulamadıklarınızı görebilirsiniz. Gösterdikten sonra o bölümde yeni kelime sayılmaz.

[Başa dön](#icerik){: .top}

<h2 id="puan">3. Puan ve rütbeler</h2>

- Hedef kelime: harf sayısı kadar puan (3 harfli 3, 6 harfli 6 puan).
- Bonus kelime: 1 puan.
- İpucuyla açılan kelime: 1 puan.

Günün Bulmacası ve Anagram puanı da toplama eklenir; Zamana Karşı puanı eklenmez. Toplam puanınız arttıkça rütbeniz yükselir ve her yeni rütbede 3 ipucu hakkı kazanırsınız.

<details markdown="1">
<summary>Rütbeler ve gereken puan</summary>

- Acemi: başlangıç
- Çırak: 750 puan
- Kalfa: 2.250 puan
- Usta: 5.500 puan
- Bilge: 10.500 puan
- Üstat: 17.500 puan
- Laf Cambazı: 26.500 puan
- Söz Ehli: 37.500 puan
- Hezarfen: 50.000 puan
- Allame: 65.000 puan

Allame'den sonra her 20.000 puanda Allame 2, Allame 3 diye sürer. İstatistikler ekranı rütbenizi ve sonraki rütbeye kalan puanı söyler.
</details>

[Başa dön](#icerik){: .top}

<h2 id="kontroller">4. Kontroller</h2>

Harflere dokunarak kelimenizi oluşturursunuz; seçtiğiniz harfler üstteki alana eklenir.

- Bir harfe dokunmak o harfi seçer; seçili harfe tekrar dokunmak seçimi geri alır.
- **Sil** en son seçilen harfi kaldırır.
- **Sıfırla** tüm seçimi temizler.
- **Karıştır** harflerin sırasını değiştirir.

Klavyeyi de kullanabilirsiniz: alttaki metin alanına yazıp gönder tuşuna basmanız yeterli. VoiceOver ile ekran üstten alta sade ilerler: önce durum, sonra harfler, sonra yazı alanı ve düğmeler.

[Başa dön](#icerik){: .top}

<h2 id="ipucu">5. İpuçları ve ipucu hakları</h2>

Takılınca üç ipucundan birini seçebilirsiniz. Bedeller her oyunda aynıdır:

- **Anlamdan Bul** (2 hak): kelimenin kısa anlamını gösterir.
- **İlk Harf ve Uzunluk** (3 hak): ilk harfi ve kaç harfli olduğunu gösterir.
- **Kelimeyi Göster** (5 hak): kelimeyi doğrudan açar.

Kalan kelimeler ve Karıştır ücretsizdir. Oyuna 10 ipucu hakkıyla başlarsınız. İpucu hakkı satın alınmaz, yalnız oynayarak kazanılır:

- Bölümü ipucu kullanmadan bitirmek: +1
- Bölümde hedeflerin ve bonusların tümünü bulmak: +1
- Günün Bulmacası'nı çözmek: +1; bonuslarla birlikte tümünü bulmak: toplam +3
- Her 5 anagram: +1
- Yeni rütbe: +3
- Zamana Karşı'da bir turda 30, 60, 100, 125 ve 150 puanın her biri: +1

Kalanları gösterirseniz tümünü bulma ödülü verilmez.

[Başa dön](#icerik){: .top}

<h2 id="gunun-bulmacasi">6. Günün Bulmacası</h2>

Her gün herkese aynı bulmaca gelir; harfler 6 ya da 7 tanedir. Kurallar bölümlerle aynıdır. Bulmacayı çözdükten sonra gün içinde yeniden açıp kalan bonus kelimeleri aramaya devam edebilirsiniz. Gün değişince yeni bulmaca açılır; kaçırdığınız gün geri gelmez. Çözdükten sonra sonucunuzu paylaşabilirsiniz.

[Başa dön](#icerik){: .top}

<h2 id="zamana-karsi">7. Zamana Karşı</h2>

Size 7 harfli bir kaynak kelime verilir. 90 saniyede bu harflerden en az 3 harfli olabildiğince çok kelime bulursunuz. Bu modda ipucu kullanılmaz.

- 3 harf: 4 puan
- 4 harf: 7 puan
- 5 harf: 11 puan
- 6 harf: 16 puan
- 7 ve daha fazla harf: 22 puan

Süre bittiğinde en az 30 puandaysanız 15 saniyelik ek süre teklifi gelir; 3 ipucu hakkı harcayarak alabilirsiniz.

[Başa dön](#icerik){: .top}

<h2 id="anagram">8. Anagram</h2>

Harfler karışık verilir. Harflerin hepsini birer kez kullanarak anlamlı kelimeyi bulursunuz; alt kelime türetilmez. Bazı harflerden birden fazla kelime çıkar; o zaman ekranın üstünde kaç kelime olduğu yazar ve hepsi bulununca bölüm biter. Puan ve ipucu bedelleri ana oyunla aynıdır.

[Başa dön](#icerik){: .top}

<h2 id="dokunmatik-alan">9. Dokunmatik Alan</h2>

Oyun ekranındaki **Dokunmatik alan** düğmesine çift dokununca bütün ekran tek bir dokunma alanı olur. Oyunda iki parmakla çift dokunarak da alanı açıp kapatabilirsiniz. Ayarlar'daki "Oyunlara dokunmatik modla başla" açıksa oyunlar bu alanla başlar. Bu komutların hepsi VoiceOver eylemler listesinde de vardır.

<details markdown="1">
<summary>Dokunmatik Alan hareketleri</summary>

Harfler:

- Tek parmakla sağa fiske: sonraki harf
- Tek parmakla sola fiske: önceki harf (sonda başa, başta sona sarar)
- Tek dokunuş: bulunduğunuz harfi okur
- Çift dokunuş: harfi seçer
- Tek parmakla basılı tutmak: tüm harfleri okur

Yazılan kelime:

- İki parmakla sola: son harfi siler
- İki parmakla sağa: gönderir
- İki parmakla aşağı: yazılanı okur

Bilgi:

- Üç parmakla yukarı: durum (süre ya da bölüm, puan, bulunan, kalan, bonus, ipucu hakkı, rütbe)
- Üç parmakla aşağı: bulunan kelimeler
- Üç parmakla sağa: ipucu
- Üç parmakla sola: kaç harf olduğu ve harfler

Çıkış ve klavye:

- İki parmakla yukarı: alandan çıkar, yazı kutusuna geçer; klavye açılır
- İki parmakla çift dokunuş ya da iki parmakla basılı tutmak: alandan çıkar
</details>

Braille ile yazmak için iPhone'un Braille ekran girişini kullanın. Oyunda önce iki parmakla yukarı kaydırıp yazı kutusuna geçin, sonra Braille ekran girişini açın. Braille'de satır sonu kelimeyi gönderir.

[Başa dön](#icerik){: .top}

<h2 id="ucret">10. Ücretsiz sürüm ve Tam Sürüm</h2>

- İlk 25 bölüm ve ilk 25 anagram ücretsizdir.
- Günün Bulmacası her gün ücretsiz açıktır.
- Zamana Karşı'da her gün 3 ücretsiz tur vardır; hak her gün yenilenir.

Tek seferlik Tam Sürüm tüm bölümleri, tüm anagramları ve sınırsız Zamana Karşı turunu açar. Abonelik ve reklam yoktur.

[Başa dön](#icerik){: .top}
