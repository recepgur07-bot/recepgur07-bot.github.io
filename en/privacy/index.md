---
source: apple-release-kit/config/APP_PRIVACY.tsv
layout: default
lang: en
title: Our privacy principles
alt_url: /tr/gizlilik/
description: How Forali apps and this site approach personal data, with links to each app's privacy policy.
---
# Our privacy principles

Not collecting your personal data is our default. We do not ask for any data an app does not need to work.
{: .lead}

## App Store privacy labels

As of October 2026, every one of our apps on the App Store declares "Data Not Collected" in its App Store privacy label. You can see this label on each app's App Store page.

## Where your data stays

- The content and settings you create in our apps are stored on your device.
- In apps that sync between devices, your data is kept in your own iCloud account; it does not reach Forali's servers.

## Purchases

In-app purchases and subscriptions are processed by Apple. We never see your payment details.

## When you write to us

If you email us, we use your address and message only to reply and to solve the problem; we do not share them with third parties.

## This site

This site uses no cookies, analytics, tracking, external fonts or external scripts.

## App privacy policies

Each app's own privacy policy is the definitive and binding source.

<ul>
{%- for app in site.data.apps %}
  <li><a href="{{ app.privacy }}">{{ site.data.ui.en.privacy }}: {{ app.en.name }}</a></li>
{%- endfor %}
</ul>
