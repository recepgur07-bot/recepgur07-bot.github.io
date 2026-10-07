---
kaynaksiz: Per-app support links are generated at build time from _data/apps.yml; the general address is contact_email in _config.yml.
layout: default
lang: en
title: Support and contact
alt_url: /tr/iletisim/
description: Support, privacy and contact links for Forali apps.
---
# Support and contact

If you have a problem, question or suggestion about an app, start with that app's support page. Accessibility reports are especially welcome: mentioning your device, system version and assistive technology (for example VoiceOver) helps me find the problem faster.

{% if site.contact_email != "" -%}
## General contact

Email: [{{ site.contact_email }}](mailto:{{ site.contact_email }})
{% endif %}
## Support by app

{% include support-list.html %}
