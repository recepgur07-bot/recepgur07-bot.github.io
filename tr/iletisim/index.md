---
kaynaksiz: Uygulama başına destek bağlantıları derleme anında _data/apps.yml verisinden üretilir; genel adres _config.yml'deki contact_email'dir.
layout: default
lang: tr
title: Destek ve iletişim
alt_url: /en/contact/
description: Forali uygulamaları için destek, gizlilik ve iletişim bağlantıları.
---
# Destek ve iletişim

Bir uygulamayla ilgili sorun, soru veya öneriniz varsa önce o uygulamanın destek sayfasına bakın. Erişilebilirlik sorunlarını bildirmeniz özellikle değerlidir: hangi cihazı, hangi sistem sürümünü ve hangi yardımcı teknolojiyi (örneğin VoiceOver) kullandığınızı yazarsanız sorunu daha hızlı bulabilirim.

{% if site.contact_email != "" -%}
## Genel iletişim

E-posta: [{{ site.contact_email }}](mailto:{{ site.contact_email }})
{% endif %}
## Uygulamalara göre destek

{% include support-list.html %}
