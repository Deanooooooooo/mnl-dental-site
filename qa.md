# QA — Дентални клиники MNL

## Gate 1 — source/fact audit
- PASS: Name/category/address/phone from sheet + Google Maps + Oink/Titul.
- PASS: Address used: `бл. 418, Младост 4, вх. 1 - партер, 1715 София` from Google/Oink/Titul.
- PASS: Phone used: `089 728 8776` from Google/Titul and sheet.
- PASS: Hours used from Titul: Mon–Fri 09:00–20:00, Sat closed, Sun 10:00–16:00.
- PASS: mnl.business.site checked and returned 404, so not used as CTA.

## Gate 2 — image audit
- PASS: Dental clinic is not a visual-result beauty business. Real clinic/equipment/location/team images sourced from Oink and Facebook.
- PASS: Image decisions and rejected assets recorded in `image-map.md`.
- PASS: No stock/fake images used.

## Gate 3 — testimonial audit
- PASS: Google Maps manually inspected in browser.
- PASS: Used 3 real written Google reviews with real public names and original Bulgarian/English display text.
- PASS: Did not use rating-only cards or review-count copy.
- Note: Titul has additional reviews and one negative scheduling complaint; final testimonials use stronger Google reviews and do not hide aggregate profile link.

## Gate 4 — copy audit
- PASS: Customer-facing text inspected; no invented prices, awards, guarantees, credentials, or review counts.
- PASS: No dynamic “open now” copy.

## Gate 5 — link/schema audit
- PASS: `tel:` link present.
- PASS: Google Maps link uses exact place query/place_id.
- PASS: Facebook and Oink profile links present.
- PASS: Dentist schema includes NAP, geo, opening hours, canonical and sameAs links.

## Gate 6 — image/layout audit
- PASS: image paths exist and optimized WebP assets generated; desktop/mobile screenshots inspected.
- PASS: No duplicate image files in visible layout.
- PASS: Hero image not repeated in gallery.
- PASS: No captions with inferred descriptions.

## Gate 7 — map/local SEO audit
- PASS: bottom Google Maps/local SEO block exists directly above footer.
- PASS: Map/contact block has exactly one visible Google Maps navigation CTA.
- PASS: iframe uses `ll=lat,lng&q=business&output=embed`, explicit width/height, and was verified after scrolling into view on desktop/mobile screenshots.

## Gate 8 — responsive visual QA
- PASS: Desktop and mobile screenshots inspected. Fixed mobile hero order, reduced overlarge headline, shortened long testimonials, and verified footer icons/tap targets.

## Gate 9 — final live QA
- Pending after deploy.
