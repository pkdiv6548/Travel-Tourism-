# Wanderly — Travel & Tourism Frontend

A multi-page, responsive static website built from the Travel & Tourism Industry research section. Built only with **HTML, CSS and vanilla JavaScript**. No framework, build step, backend, database, authentication or booking API is used.

## Pages
- `index.html` — home, destination discovery, experience themes and newsletter demo.
- `destinations.html` — searchable/filterable destination directory.
- `experiences.html` — adventure, culture, culinary, wellness, wildlife and pilgrimage categories.
- `stays.html` — accommodation types and selection checklist.
- `transport.html` — air, rail, road and transfer comparison.
- `plan.html` — browser-only trip sketch with a downloadable text summary.
- `industry-categories.html` — searchable, filterable map of 30 travel & tourism business-function categories.
- `industry-detail.html` — bookmarkable detail route; use `?category=<slug>` to open one of the 30 tailored category guides (roles, workflows, systems, integrations, KPIs, buying checks and risks).
- `travel-tools.html` — research-based starter directory of real travel-industry software and official provider links.
- `css/style.css` — shared responsive visual system.
- `js/app.js` — mobile navigation, destination search, category filters, industry-map search/filter, card-detail routing, year, newsletter demo and trip planner.
- `js/industry-details.js` — category-specific operating guides for all 30 industry-map categories.

## Preview
Open `index.html` directly in a browser or enable GitHub Pages from the repository settings using the `main` branch and root folder.

## Industry category detail pages

Each category card on the Industry Map has an **Open category detail** control. It opens a dedicated URL such as `industry-detail.html?category=lodging`. The page is populated client-side from the category slug and covers business purpose, roles, workflows, system types, integrations, governance, KPIs, software selection and operational risks. The content is a working guide, not a claim that one product provides every capability.

All main pages currently contain at least seven content sections. Source-level checks have been run for section counts, local links, duplicate IDs and JavaScript syntax. Real browser, mobile visual and live GitHub Pages deployment checks are still pending.

## Important boundaries
- Frontend-only demo. No live reservations, payments, user accounts, inventory, real-time prices or API connections.
- The trip planner creates a local summary and can download a text file; form data is not sent to a server.
- Newsletter form is a UI demo and does not collect or transmit email addresses.
- Destination photography is loaded from Unsplash URLs and therefore requires internet access.
- Software directory entries are a curated starting list based on the Travel & Tourism Industry research. Verify vendor features, contracts, pricing, integrations and regional availability using official sources.
- The 30 industry categories are a working taxonomy, not a claimed official universal classification.

## Technology
Semantic HTML5, CSS3, vanilla JavaScript, responsive CSS and native browser APIs.
