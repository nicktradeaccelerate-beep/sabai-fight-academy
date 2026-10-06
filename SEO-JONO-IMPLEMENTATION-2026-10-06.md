# Sabai SEO — Jono Framework Implementation

Date: 2026-10-06

## Method
Applied from Jono's Claude Code SEO masterclass already stored in the Caldr/Joyful Noether training data:
1. Find winning keywords rather than guessing lists.
2. Create service pages for money / buyer-intent searches.
3. Create useful guide content for topical authority.
4. Use the primary query early and add 3–5 relevant internal links.
5. Keep technical SEO clean: performance, crawlability, robots, sitemap, metadata.
6. Connect Search Console, submit sitemap and use live query/page data to decide what gets expanded next.

## Current opportunity clusters
### Tier 1 — money pages
- muay thai hua hin -> /muay-thai-hua-hin/
- private muay thai hua hin -> /private-muay-thai-hua-hin/
- sauna hua hin / finnish sauna hua hin -> /sauna-ice-bath-hua-hin/
- cold plunge hua hin / ice bath hua hin -> /sauna-ice-bath-hua-hin/
- kids muay thai hua hin / junior muay thai hua hin -> /kids-muay-thai-hua-hin/
- muay thai retreat hua hin -> /muay-thai-retreat-hua-hin/
- fitness retreat hua hin / private group wellness hua hin -> /events-retreats-hua-hin/

### Tier 2 — authority / guide content
- muay thai prices hua hin -> /guides/muay-thai-prices-hua-hin/
- beginner muay thai hua hin -> /guides/beginner-muay-thai-hua-hin/
- muay thai recovery hua hin -> /guides/muay-thai-recovery-hua-hin/
- plan muay thai retreat hua hin -> /guides/planning-muay-thai-retreat-hua-hin/

## SERP observations — 2026-10-06
- Hua Hin Muay Thai results reward dedicated location pages with schedules, prices, trainer/proof content and FAQs.
- The local category is competitive: current directories show roughly 30+ Hua Hin gyms.
- Sauna/cold-plunge search has a clear established Hua Hin competitor, so Sabai must differentiate around the combined Train + Recover proposition rather than imitate a generic spa.
- Retreat search surfaces marketplace/package pages, supporting a dedicated retreat-intent landing page.

## Next data-driven loop
Once Search Console is verified:
- submit /sitemap.xml
- inspect/index the Tier 1 money pages first
- after data settles, prioritize queries/pages with meaningful impressions and positions roughly 4–20
- strengthen those pages with genuine photos, proof, FAQs and internal links rather than spinning up thin pages
- record confirmed bookings and revenue by landing page / source

## Live technical QA after implementation
Lighthouse mobile, 2026-10-06:
- Performance: 95/100 (was 65 before optimisation pass)
- Accessibility: 100/100
- Best Practices: 100/100
- SEO: 100/100
- LCP: 1.6s
- CLS: 0
- Total Blocking Time: 230ms

All 13 sitemap URLs return HTTP 200. No duplicate page titles were found in the indexable page set. Every indexable page has a title, meta description, canonical and H1.

## Search Console status
A Google Search Console property attempt was made for https://retreat.raifinder.com/ and the verification file is live at the required root URL. The Safari Google session currently active on the Mac mini is signed in as charlene@backfromblack.co.uk, and Google reports that account does not have access to the Sabai property. Do not switch identities or alter Google ownership from the wrong account. Finish Search Console verification/submission when the owner Google identity is active, then submit https://retreat.raifinder.com/sitemap.xml and inspect Tier-1 money pages first.
