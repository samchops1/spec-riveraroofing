# Rivera Roofing Inc — spec-site preview

- **Suggested slug:** `riveraroofing`
- **Target host (not live, do not claim it is):** riveraroofing.capitalreconsulting.com
- **Current public site:** https://riveraroofinginc.wixsite.com/rivera-roofing-inc
- **Site path:** `/workspace/previews/riveraroofing/index.html`
- **One-line note (Outreach):** Replaced the default Wix brochure — leftover “Residential Roofing Services” template copy and a Facebook photo carousel — with an Englewood storm-dispatch shop for Rivera Roofing Inc: license 243785, 24-hour emergency line, click-to-call (303) 437 5915.

This folder is a static preview only. Do not deploy. Do not treat the target host as live.

## What changed vs their current site

Stripped the Wix “This website was built on Wix” chrome, the leftover About stub that names a different company (“Residential Roofing Services is a full service residential building contractor”), the generic Our Staff line, the BBB badge, and the template contact form. Rebuilt a mobile-first four-page shop as a storm-dispatch / copper-flashing yard: tar `#12100e`, copper `#c56a2c`, vest orange `#e85d04`, logo red `#c61f1a`, Teko + IBM Plex Sans, offset shingle courses, a stamped license plate, a sticky call/email dock on phones, and one compressed job photo.

## Facts used (with sources)

| Fact | Source |
| --- | --- |
| Brand **RIVERA ROOFING INC** / **RIVERA ROOFING** | Homepage H1 / header / every live page |
| **Residential Commercial** | Header strip on Home, About, Contact |
| Phone **(303) 437 5915** / `tel:+13034375915` | Homepage, Contact (“Telephone”), 24-hour block |
| **License number 243785** | Homepage |
| **24 HOURS EMERGENCY TELEPHONE** | Homepage and shared footer block |
| **CALL FOR A FREE ESTIMATE (303) 437 5915** | Homepage / every live page footer |
| Email **riveraroofing5@gmail.com** (printed as “Email:” on Home; “iEmail:” on Contact) | Home, Contact |
| Address **2900 S Zuni St / Englewood, CO 80110** | Home, Contact |
| **GET A FREE ESTIMATE** | About Us form heading |
| One job photo (vest prints **303-437-5915**) | Homepage carousel, Wix media `000762_0a178cf1e04e4490bfc2f08d54373bf2` |

## Facts deliberately omitted

- **Owner name** — not printed on the live Wix pages. No founder in copy or JSON-LD. No invented Rivera first name.
- **About stub** — “Residential Roofing Services is a full service residential building contractor.” Leftover Wix / template language that renames the company. Not used on customer pages.
- **Our Staff** — “Our team is skilled and experienced and will take extra care to ensure your satisfaction upon completion of your roofing project.” Generic template. No crew invented.
- **Logo graphic tagline** — “Professional Roofers Serving Denver for over 20 years!” on the uploaded mark. Not copied into copy (no invented years; no extra city list). Fresh SVG mark instead.
- **BBB Accredited Business** badge — stock trust graphic, not treated as a verified claim.
- **YouTube social icon** — `UCRYbeBxtDRJpRYKZphREYBQ` is a generic Wix social bar. Destination not used.
- **Wix builder banner** and template form chrome (“iEmail”, “Success! Message received.”).
- **Hours, prices, insurance, reviews, extra trades, extra cities** — not printed as facts on the live pages.
- **Any claim this preview is live** at riveraroofing.capitalreconsulting.com.

## Pages

- `index.html` — storm-dispatch hero, residential / commercial, 24-hour line, click-to-call
- `services.html` — the two published words only
- `about.html` — shop, license, Englewood address, emergency telephone
- `contact.html` — tel, mailto, 2900 S Zuni St, estimate form (mailto draft)

Forms open a mail draft to riveraroofing5@gmail.com. They do not post to Wix.

## Images

One photo: `assets/job.jpg` (114KB JPEG, from `000762_0a178cf1e04e4490bfc2f08d54373bf2~mv2.jpg` on the live site). Vest on the left prints 303-437-5915. Same file is small enough for web and email. No fat original kept. No 1MB+ files. Logo is a fresh SVG roof mark in copper / tar / red, plus an SVG favicon.

## JSON-LD

`RoofingContractor` + `LocalBusiness` on the homepage only, verified fields: name, telephone, email, live Wix URL, 2900 S Zuni St, Englewood CO 80110, description, the one image. No founder, no aggregateRating, no invented geo, no openingHours (24-hour emergency is copy, not a shop-hours table).

## Blockers

- No owner name on the live Wix page.
- No hours table, prices, or insurance on the live Wix pages.
- About page still ships leftover template copy that names another company.
