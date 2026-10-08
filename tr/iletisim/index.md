---
kaynaksiz: Uygulama başına destek bağlantıları derleme anında _data/apps.yml verisinden üretilir; genel adres _config.yml'deki contact_email'dir.
layout: default
lang: tr
title: Destek ve iletişim
alt_url: /en/contact/
description: Forali uygulamaları için destek, gizlilik ve iletişim bağlantıları.
---
# Destek ve iletişim

Bir uygulamayla ilgili sorun, soru veya öneriniz varsa önce [Sık sorulan sorular](/tr/sss/) sayfasına ve o uygulamanın destek sayfasına bakın. Erişilebilirlik sorunlarını bildirmeniz bizim için özellikle değerlidir: hangi cihazı, hangi sistem sürümünü ve hangi yardımcı teknolojiyi (örneğin VoiceOver) kullandığınızı yazarsanız sorunu daha hızlı bulabiliriz.

{% if site.contact_email != "" -%}
## E-posta

- Uygulama desteği ve sorun bildirimi: [{{ site.support_email }}](mailto:{{ site.support_email }})
- Genel iletişim, iş birliği ve basın: [{{ site.contact_email }}](mailto:{{ site.contact_email }})
{% endif %}
## Uygulamalara göre destek

{% include support-list.html %}
