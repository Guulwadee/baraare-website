# Baraare Agri-Livestock Initiative — website

Official website of **Baraare Agri-Livestock Initiative**, an independent, non-governmental Somali non-profit in Mogadishu. *Baraare* is the Somali word for prosperity/abundance.

> Baraare helps Somali farmers and herders earn more from their land and animals by teaching them to track their costs and profits, know fair market prices, access water, and work together in cooperatives.

## Stack

Deliberately minimal for low-bandwidth users:

- Static HTML — no framework, no build step, no CMS, no external CDNs
- One shared stylesheet (`css/style.css`), system fonts only
- Inline SVG illustration only, no raster images (~37 KB max per page)
- `js/nav.js` — mobile navigation toggle only; the site works without JS

## Structure

| File | Page |
|---|---|
| `index.html` | Home |
| `about.html` | About — story, values, governance, founder |
| `programs.html` | Programs — the six-step ladder |
| `water.html` | Water (Phase 2) |
| `partner.html` | Partner with us |
| `contact.html` | Contact |

## Deploying

All links are relative — serve the folder as-is (GitHub Pages, Netlify, any static host). Before going live, search the repo for `[` and replace the remaining bracketed placeholders: `[DOMAIN]` (head tags, `sitemap.xml`, `robots.txt`), `[BOARD MEMBER NAMES AND SHORT BIOS]`, `[MOIFAR CERTIFICATE NUMBER]`, and the `[FIELD PHOTO — …]` blocks.

A Somali edition (`/so/`) is planned; nav and footer contain commented hooks for it.
