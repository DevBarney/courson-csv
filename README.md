# Courson CSV

Free Udemy coupon snapshots from [courson.xyz](https://courson.xyz).

## How to get the CSV

1. **In Grok chat** — say `refresh courson csv` and download the file it returns.
2. This repo will hold snapshots when updated.

## Columns
id, title, headline, coupon_code, discount_percent, uses_remaining, max_uses, duration, level, language, rating, subscribers, reviews, lectures, category, subcategory, instructors, has_certificate, badges, udemy_url, coupon_url, image, created_date, last_updated

## Why not fully automatic?
Courson.xyz sits behind Cloudflare, so a public live API proxy gets blocked (HTTP 403). Snapshots generated from a clean request still work.
