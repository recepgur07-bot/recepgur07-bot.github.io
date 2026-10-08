---
source: forali/docs/AMAC-VE-YOL.md
layout: default
lang: en
title: Press and media
alt_url: /tr/basin/
description: A short description, key facts, app list and press contact for anyone writing about Forali.
---
# Press and media

If you are writing about Forali or our apps, you are welcome to use the information and text on this page.
{: .lead}

## Short description

Forali is an independent software brand developing apps and games for iPhone, iPad, and Mac. It considers accessibility from the start of design, aiming to reduce barriers for blind and low-vision users while creating simple, clear experiences for everyone. Its apps declare "Data Not Collected" in their App Store privacy labels.

## Key facts

- **Name:** Forali (one word, capital F)
- **Tagline:** Accessible by design. Useful for everyone.
- **Focus:** Apps and games for iPhone, iPad, and Mac
- **Apps on the App Store:** {{ site.data.apps.size }}
- **Web:** forali.app
- **App Store:** The apps are published under an individual developer account, so the seller name shown there is the account holder’s name rather than Forali.

## Apps

<ul>
{%- for app in site.data.apps %}
  <li><a href="{{ app.appstore }}">{{ app.en.name }}</a>: {{ app.en.subtitle }}</li>
{%- endfor %}
</ul>

Screenshots for each app are on its App Store page.

## Images and interview requests

For high-resolution images, review access or interview requests, write to [hello@forali.app](mailto:hello@forali.app).
