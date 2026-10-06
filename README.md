# EASY OFFERS 🏷️ — Affiliate Offers Hub

*Part of the EASY CODE collection — Apps Made Easy ✨*

**Live page:** https://mido9980.github.io/easy-offers/

An Arabic RTL deals page that acts as a broker ("سمسار عروض") for offers from all sources. Every offer lives in a database record (Base44 entity `Offer`) — add or update offers without touching the code, and each offer links to your affiliate tracking URL from any network (Admitad, CPAlead, Adsterra, or a direct brand deal).

## Features
- Offer cards with discount badges, old/new prices, categories, and a big CTA.
- Category chips with instant filtering.
- Click tracking: every CTA click is counted per offer.
- Offer images with emoji fallback per category.
- Gateway-agnostic: affiliate URLs come from data, not code — works with any CPA network.
- Built-in honesty: offers without a URL yet show "قريب جداً" instead of fake buttons.

## How to add/edit offers
Offers are records in the `Offer` entity (name, description, category, image_url, old_price, new_price, discount_text, url, provider, active, sort_order). The page reads them live and sorts by sort_order.

## Edit on your phone with SPCK
1. SPCK Editor → clone: `https://github.com/Mido9980/easy-offers.git`
2. Credentials: GitHub username + Personal Access Token as password.

---
© EASY CODE — Apps Made Easy
