# recepgur07-bot.github.io

Recep Gür'ün uygulamaları için tanıtım ve kullanım kılavuzu sitesi.
GitHub Pages "deploy from branch" (main, kök) ile Jekyll yerleşik olarak derlenir; ek iş akışı yoktur.

## Yapı

| Yol | İçerik |
|---|---|
| `index.html` | Dil seçimi (Türkçe / English) |
| `tr/`, `en/` | Dil başına ana sayfa ve uygulama sayfaları |
| `tr/<uygulama>/index.md` | Uygulama tanıtımı |
| `tr/<uygulama>/kilavuz.md` | Kullanım kılavuzu (`permalink` ile `/tr/<uygulama>/kilavuz/`) |
| `_data/apps.yml` | Uygulama kataloğu: ad, alt başlık, cihazlar, App Store, gizlilik, destek |
| `_data/ui.yml` | Her sayfada tekrar eden arayüz metinleri (dil başına) |
| `_layouts/default.html` | Ortak iskelet: `lang`, "İçeriğe atla", site gezinmesi, dil bağlantısı |
| `_includes/` | Uygulama bilgi kutusu ve uygulama listesi |

## Kurallar

Ayrıntılı ve bağlayıcı kurallar [AGENTS.md](AGENTS.md) dosyasındadır. Kısaca:

- **Mevcut adresler bozulmaz.** Gizlilik ve destek sayfaları eski depolarda durur
  (`memora`, `folio-privacy`, `oneday-support`, `kelimelerim-legal`, ...) ve App Store'a
  bu adreslerle girilmiştir. Bu sitede kök düzeyde bu adlarla klasör açılmaz;
  aynı adlı proje sayfası her zaman önceliklidir. Bu yüzden içerik `tr/` ve `en/` altındadır.
- Yalnız App Store'da yayında olan uygulamalar listelenir. Ad ve alt başlık
  `fastlane/metadata`'dan alınır; uydurma bilgi yazılmaz.
- Çerez, analitik, izleme, dış yazı tipi ve betik yoktur.
- Erişilebilirlik: her sayfa tek `h1`, sıralı başlıklar, doğru `lang`, "İçeriğe atla",
  içindekiler ve "Başa dön" bağlantıları; açılır alan için yalnız yerel `<details>`.
  Temel bilgi kapalı alana saklanmaz.
- Kılavuz metinlerinin kaynağı `pazarlama/uygulamalar/<uygulama>/` altındadır; orada
  değişen metin burada da güncellenir.

## Yeni uygulama eklemek

1. `_data/apps.yml` içine kayıt ekle (`page: false` ile yalnız listede görünür).
2. Kendi sayfası olacaksa `page: true` yap; `tr/<slug>/index.md` ve `en/<slug>/index.md`
   oluştur, ön bilgide `alt_url` ile birbirine bağla ve `source:` alanına kaynak metnin
   yolunu yaz (`projelerim/`e göre). `bin/kaynak-kontrol` kaynak sayfadan yeniyse uyarır.

`tr/hakkinda/` ve `en/about/` bilinçli olarak boş ve `noindex`'tir; içeriği kullanıcı karar verince yazılır.

## Önizleme ve denetim

```bash
bin/kur        # bir kez: Jekyll'i vendor/gems içine kurar
bin/onizle     # http://127.0.0.1:4000
bin/denetle    # göndermeden önce: öz test, derleme, yapı ve kaynak denetimi
bin/adres-kontrol  # push sonrası: App Store'a girili canlı adresler (ağ ister)
```
