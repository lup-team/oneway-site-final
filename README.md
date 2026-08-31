# One Way Travel & Tours

Static bilingual landing page for One Way Travel & Tours in Nizwa, Oman.

## Website type

- Static informational landing page
- Arabic RTL and English LTR
- No database
- No server-side programming
- No online booking system

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Swiper
- AOS
- Local Tajawal and Inter fonts

## Main files

- `index.html` — Main website page
- `404.html` — Custom Not Found page
- `robots.txt` — Search-engine crawling instructions
- `sitemap.xml.template` — Sitemap template for the publishing company
- `css/style.css` — Main website styles
- `css/destinations-slider.css` — Destination slider styles
- `css/404.css` — 404 page styles
- `js/main.js` — Website interactions

## Project structure

```text
site/
├── index.html
├── 404.html
├── robots.txt
├── sitemap.xml.template
├── css/
├── fonts/
├── images/
├── js/
└── vendor/

## Production domain checklist

This package currently uses the reserved temporary domain `https://onewaytravel.example`.
Before connecting the real custom domain, replace every occurrence of `https://onewaytravel.example` in:

- `index.html` (canonical, Open Graph, Twitter, structured data)
- `robots.txt`
- `sitemap.xml`

Then add the GA4 Measurement ID and verify the final domain in Google Search Console.
