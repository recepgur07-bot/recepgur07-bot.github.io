# Uygulama sitesi — tüm AI araçları için çalışma sözleşmesi

Bu dosya Claude Code, Codex, Cursor, Antigravity ve buraya girecek her araç için geçerlidir.
`CLAUDE.md` bu dosyaya işaret eder; kural tektir.

## Bu depo nedir

Recep Gür'ün App Store uygulamalarının tanıtım ve kullanım kılavuzu sitesi.
Yayın adresi: https://recepgur07-bot.github.io/ (GitHub Pages, `main` dalı, kök klasör).
`main`'e gönderilen her commit bir iki dakikada **herkese açık** yayına girer.

## Bilgi zinciri

```
uygulama kodu + fastlane/metadata      (gerçek)
  → pazarlama/uygulamalar/<slug>/TANITIM-METNI.md   (Türkçe kaynak metin)
    → bu site: tr/<slug>/…              (Türkçe sayfa)
      → bu site: en/<slug>/…            (İngilizce çeviri)
```

- İçerik **önce kaynağında** düzeltilir, sonra buraya taşınır. Sitede kaynağa ters düşen metin yazılmaz.
- Her sayfanın ön bilgisinde `source:` vardır (yol `projelerim/` klasörüne görelidir).
  `bin/kaynak-kontrol` kaynağı sayfadan yeni olanları `ESKİ` diye bildirir.
- Yayındaki uygulamaların listesi ve kimlikleri için kanonik kaynak
  `/Users/recepgur/Desktop/projelerim/apple-release-kit` (`config/PROJECTS.tsv`,
  `QUICK-REFERENCE.md` → App Privacy özeti).
- Arayüz adları (düğme, ayar, VoiceOver metni) uygulamanın kendi yerelleştirme
  dosyasından birebir alınır; İngilizce sayfada `en` değerleri kullanılır.

## Zorunlu kurallar

1. **Göndermeden önce `bin/denetle`** koşulur ve geçer (öz test → derleme → yapı → kaynak).
   Dış bağlantılar ayrıca `pazarlama/bin/link-kontrol` ya da `curl` ile doğrulanır.
2. **Push = yayın.** Kullanıcının açık onayı olmadan `git push` yapılmaz.
3. **Mevcut adresler bozulmaz.** App Store'a girilmiş gizlilik/destek sayfaları eski
   depolarda durur (`memora`, `folio-privacy`, `oneday-support`, `oneday-privacy`,
   `kelimelerim-legal`, …). Bu sitede kök düzeyde bu adlarla klasör açılmaz; içerik
   yalnız `tr/` ve `en/` altındadır.
4. **Yalnız yayındaki uygulamalar** listelenir. Yeni uygulama yayına girince
   `_data/apps.yml`'e eklenir; bilgi uydurulmaz, doğrulanamayan alan boş bırakılır.
5. **Erişilebilirlik:** tek `h1`, sıralı başlıklar, doğru `lang`, "İçeriğe atla",
   uzun sayfada içindekiler ve "Başa dön", açılır alan için yalnız yerel `<details>`;
   temel bilgi kapalı alana saklanmaz. Bağlantı metni tek başına anlaşılır olur.
6. **Kesin olmayan iddia yazılmaz.** Kodla ya da cihaz turuyla doğrulanmamış
   "her şey erişilebilir" türü mutlak cümle kurulmaz.
7. **İzleme yok:** çerez, analitik, dış yazı tipi veya dış betik eklenmez.
8. **Kişisel bilgi** (geliştiricinin sağlığı, kimliği vb.) kullanıcının açık onayı olmadan yazılmaz.
   `tr/hakkinda/` ve `en/about/` bu yüzden boş ve `noindex`'tir.
9. **Sır yok.** Token, anahtar, parola bu depoya girmez.

## Yapı

| Yol | İçerik |
|---|---|
| `_data/apps.yml` | Uygulama kataloğu (ad, alt başlık, cihaz, sistem, App Store, gizlilik, destek) |
| `_data/ui.yml` | Her sayfada tekrar eden arayüz metinleri, dil başına |
| `_layouts/default.html` | Ortak iskelet |
| `_includes/` | Uygulama bilgi kutusu, uygulama listesi |
| `tr/<slug>/index.md`, `en/<slug>/index.md` | Genel bakış |
| `tr/<slug>/kilavuz.md`, `en/<slug>/guide.md` | Kullanım kılavuzu |
| `bin/` | `kur`, `onizle`, `denetle`, `yapi-kontrol`, `kaynak-kontrol`, `oz-test` |

## Uygulama sayfası şablonu (Memora örneği)

1. Kaynak metin pazarlamada hazır ve kodla doğrulanmış olmalı (`TANITIM-METNI.md`).
2. `apps.yml` kaydında `page: true`.
3. `tr/<slug>/index.md`: kısa tanıtım, bilgi kutusu (`app-links.html`), "Neler yapabilirsiniz".
4. `tr/<slug>/kilavuz.md`: içindekiler, numaralı `h2` bölümler, uzun listeler `<details>` içinde.
5. İngilizce karşılıklar, `alt_url` ile birbirine bağlı; her sayfada `source:`.
6. `bin/denetle` → kullanıcı onayı → push → canlı adresleri kontrol.

## Rutin bakım

- Bir uygulamanın yeni sürümü yayımlanınca: özellik değiştiyse önce `TANITIM-METNI.md`,
  sonra buradaki sayfalar; `bin/kaynak-kontrol` temiz çıkana kadar.
- Yeni uygulama yayına girince: `apps.yml` kaydı (apple-release-kit'ten).
- Bir uygulama kaldırılırsa: kaydı silmeden önce kullanıcıya sorulur.
