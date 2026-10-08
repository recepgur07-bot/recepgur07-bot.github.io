---
source: forali/docs/AMAC-VE-YOL.md
layout: default
lang: tr
title: Basın ve medya
alt_url: /en/press/
description: Forali hakkında yazacaklar için kısa tanıtım metni, temel bilgiler, uygulama listesi ve basın iletişimi.
---
# Basın ve medya

Forali veya uygulamalarımız hakkında yazıyorsanız bu sayfadaki bilgileri ve metinleri serbestçe kullanabilirsiniz.
{: .lead}

## Kısa tanıtım

Forali, iPhone, iPad ve Mac için uygulamalar ve oyunlar geliştiren bağımsız bir yazılım markasıdır. Erişilebilirliği tasarımın başlangıcından itibaren ele alır; görme engelli ve az gören kullanıcıların karşılaştığı engelleri azaltırken herkes için sade ve anlaşılır deneyimler geliştirmeyi hedefler. Uygulamalarının App Store gizlilik etiketlerinde "Veri Toplanmaz" beyan edilmiştir.

## Temel bilgiler

- **Ad:** Forali (tek kelime, ilk harf büyük)
- **Slogan:** Accessible by design. Useful for everyone.
- **Alan:** iPhone, iPad ve Mac için uygulamalar ve oyunlar
- **Yayındaki uygulama sayısı:** {{ site.data.apps.size }}
- **Web:** forali.app
- **App Store:** Uygulamalar bireysel geliştirici hesabıyla yayımlanır; mağazadaki satıcı adı Forali değil, hesap sahibinin adıdır.

## Uygulamalar

<ul>
{%- for app in site.data.apps %}
  <li><a href="{{ app.appstore }}">{{ app.tr.name }}</a>: {{ app.tr.subtitle }}</li>
{%- endfor %}
</ul>

Her uygulamanın ekran görüntüleri App Store sayfasında yer alır.

## Görsel ve röportaj talepleri

Yüksek çözünürlüklü görseller, inceleme için uygulama erişimi veya röportaj talepleriniz için [hello@forali.app](mailto:hello@forali.app) adresine yazın.
