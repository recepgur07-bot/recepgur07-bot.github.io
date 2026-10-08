---
source: apple-release-kit/config/APP_PRIVACY.tsv
layout: default
lang: tr
title: Gizlilik ilkelerimiz
alt_url: /en/privacy/
description: Forali uygulamalarında ve bu sitede kişisel verilere yaklaşımımız; her uygulamanın gizlilik politikasına bağlantılar.
---
# Gizlilik ilkelerimiz

Kişisel verilerinizi toplamamayı varsayılan kabul ediyoruz. Bir uygulamanın çalışması için gerekmeyen hiçbir veriyi istemeyiz.
{: .lead}

## App Store gizlilik etiketleri

Yayındaki uygulamalarımızın tamamı için App Store gizlilik etiketinde "Veri Toplanmaz" beyan edilmiştir. Her uygulamanın App Store sayfasında bu etiketi görebilirsiniz.

## Verileriniz nerede durur

- Uygulamalarda oluşturduğunuz içerik ve ayarlar cihazınızda saklanır.
- Cihazlar arası eşitleme sunan uygulamalarda veriler sizin iCloud hesabınızda tutulur; Forali'nin sunucularına gelmez.

## Satın almalar

Uygulama içi satın almalar ve abonelikler Apple tarafından işlenir. Ödeme bilgilerinizi görmeyiz.

## Bize yazdığınızda

Bize e-posta gönderirseniz adresinizi ve mesajınızı yalnız size yanıt vermek ve sorunu çözmek için kullanırız; üçüncü taraflarla paylaşmayız.

## Bu site

Bu sitede çerez, analitik, izleme, dış yazı tipi veya dış betik yoktur.

## Uygulamaların gizlilik politikaları

Kesin ve bağlayıcı bilgi her uygulamanın kendi gizlilik politikasındadır.

<ul>
{%- for app in site.data.apps %}
  <li><a href="{{ app.privacy }}">{{ site.data.ui.tr.privacy }}: {{ app.tr.name }}</a></li>
{%- endfor %}
</ul>
