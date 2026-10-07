# Uygulama sitesi — tüm AI araçları için çalışma sözleşmesi

Bu dosya Claude Code, Codex, Cursor, Antigravity ve buraya girecek her araç için geçerlidir.
`CLAUDE.md` bu dosyaya işaret eder; kural tektir.

## Bu depo nedir

Recep Gür'ün App Store uygulamalarının tanıtım ve kullanım kılavuzu sitesi.
Yayın adresi: https://forali.app/ (GitHub Pages, `main` dalı, kök klasör; `CNAME` dosyası). Eski `recepgur07-bot.github.io` adresleri ve aynı hesaptaki proje siteleri (`/memora/`, `/folio-privacy/` …) bu alan adına yönlenir.
`main`'e gönderilen her commit bir iki dakikada **herkese açık** yayına girer.

## Bilgi zinciri

```
uygulama kodu + fastlane/metadata      (gerçek)
  → pazarlama/uygulamalar/<slug>/TANITIM-METNI.md   (Türkçe kaynak metin)
    → bu site: tr/<slug>/…              (Türkçe sayfa)
      → bu site: en/<slug>/…            (İngilizce çeviri)
```

- İçerik **önce kaynağında** düzeltilir, sonra buraya taşınır. Sitede kaynağa ters düşen metin yazılmaz.
- Her sayfanın ön bilgisinde `source:` vardır (tek yol ya da liste; `projelerim/`e göre).
  Kaynağı olmayan sayfa bunu `kaynaksiz: <gerekçe>` ile açıkça yazar; ikisi de yoksa denetim düşer.
- **Tanıtım sayfası** (`index.md`) kaynağı: varsa `TANITIM-METNI.md`, yoksa uygulamanın
  `fastlane/metadata/<dil>/description.txt` dosyası.
- **Kılavuz** (`kilavuz.md` / `guide.md`) kaynağı her zaman ikidir: kodla doğrulanmış
  `pazarlama/uygulamalar/<slug>/TANITIM-METNI.md` **ve** uygulamanın `Localizable.xcstrings`
  dosyası. Mağaza açıklaması kılavuza kaynak olmaz. Kılavuzu olan uygulama `apps.yml`'de `guide: true` taşır.
- `bin/kaynak-kontrol` kaynağı sayfadan yeni olanları `ESKİ` diye bildirir. Bu bir
  **inceleme tetikleyicisidir, doğruluk kanıtı değildir:** `GÜNCEL`, sayfanın doğru olduğunu değil,
  kaynağın sayfadan sonra değişmediğini söyler. `ESKİ` görünce kaynaktaki farkı okuyup sayfayı
  güncelle; yalnız dokunup zaman damgasını yenileme.
- Yayındaki uygulamaların listesi ve kimlikleri için kanonik kaynak
  `/Users/recepgur/Desktop/projelerim/apple-release-kit` (`config/PROJECTS.tsv`,
  `QUICK-REFERENCE.md` → App Privacy özeti).
- Arayüz adları (düğme, ayar, VoiceOver metni) uygulamanın kendi yerelleştirme
  dosyasından birebir alınır; İngilizce sayfada `en` değerleri kullanılır.

## Zorunlu kurallar

1. **Göndermeden önce `bin/denetle`** koşulur ve geçer (öz test → derleme → yapı → kaynak).
   Push'tan sonra `bin/adres-kontrol` App Store'a girili gizlilik/destek adreslerini ve
   App Store bağlantılarını canlıda sınar. Sayfa içindeki diğer dış bağlantılar
   `pazarlama/bin/link-kontrol` ile doğrulanır.
2. **Push = yayın.** Kullanıcının açık onayı olmadan `git push` yapılmaz.
3. **Mevcut adresler bozulmaz.** `bin/yapi-kontrol` derlenmiş sitenin kökünde yalnız
   `tr/`, `en/`, `assets/` ve birkaç standart dosyaya izin verir; başka ad hata verir. App Store'a girilmiş gizlilik/destek sayfaları eski
   depolarda durur (`memora`, `folio-privacy`, `oneday-support`, `oneday-privacy`,
   `kelimelerim-legal`, …). Bu sitede kök düzeyde bu adlarla klasör açılmaz; içerik
   yalnız `tr/` ve `en/` altındadır.
4. **Yalnız yayındaki uygulamalar** listelenir. Yeni uygulama yayına girince
   `_data/apps.yml`'e eklenir; bilgi uydurulmaz, doğrulanamayan alan boş bırakılır.
   `bin/katalog-kontrol` apple-release-kit `PROJECTS.tsv`'deki uygulamaları Apple'ın herkese
   açık arama servisine sorar ve site listesiyle karşılaştırır (EKSİK / FAZLA). Ağ ister;
   her push'tan sonra ve her uygulama yayınından sonra koşulur. FAZLA çıkan kayıt
   kullanıcıya sorulmadan silinmez.
5. **Erişilebilirlik:** tek `h1`, sıralı başlıklar, doğru `lang`, "İçeriğe atla",
   uzun sayfada içindekiler ve "Başa dön", açılır alan için yalnız yerel `<details>`;
   temel bilgi kapalı alana saklanmaz. Bağlantı metni tek başına anlaşılır olur.
   Denetçiler yalnız iskeleti sınar; "erişilebilirlik doğrulandı" demek için VoiceOver ile
   gerçek bir okuma turu gerekir ve yapılmadıysa yapılmadı denir.
6. **Kesin olmayan iddia yazılmaz.** Kodla ya da cihaz turuyla doğrulanmamış
   "her şey erişilebilir" türü mutlak cümle kurulmaz.
7. **İzleme yok:** çerez, analitik, dış yazı tipi veya dış betik eklenmez.
8. **Kişisel bilgi** (geliştiricinin sağlığı, kimliği vb.) kullanıcının açık onayı olmadan yazılmaz.
   `tr/hakkinda/` ve `en/about/` yalnız Forali markasını anlatır; kişisel bilgi içermez.
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
| `bin/` | `kur`, `onizle`, `denetle`, `yapi-kontrol`, `kaynak-kontrol`, `oz-test`, `adres-kontrol`, `katalog-kontrol` |

## Uygulama sayfası şablonu (Memora örneği)

1. Kaynak metin pazarlamada hazır ve kodla doğrulanmış olmalı (`TANITIM-METNI.md`).
2. `apps.yml` kaydında `page: true`.
3. `tr/<slug>/index.md`: kısa tanıtım, bilgi kutusu (`app-links.html`), "Neler yapabilirsiniz".
4. `tr/<slug>/kilavuz.md` (`guide: true`): içindekiler, numaralı `h2` bölümler, uzun listeler `<details>` içinde.
5. İngilizce karşılıklar, `alt_url` ile birbirine bağlı; her sayfada `source:`.
6. `bin/denetle` → kullanıcı onayı → push → `bin/adres-kontrol` ve `bin/katalog-kontrol`.

## Rutin bakım

- Bir uygulamanın yeni sürümü yayımlanınca: özellik değiştiyse önce `TANITIM-METNI.md`,
  sonra buradaki sayfalar; `bin/kaynak-kontrol` temiz çıkana kadar.
- Yeni uygulama yayına girince: `bin/katalog-kontrol` EKSİK der; `apps.yml` kaydı apple-release-kit'ten doldurulur.
- Bir uygulama kaldırılırsa: kaydı silmeden önce kullanıcıya sorulur.
