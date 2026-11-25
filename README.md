# Ruang

Editorial studio-booking concept by Atmaja Desna Adinata.

A vanilla HTML/CSS/JavaScript frontend with category/capacity filters, studio details, date/time selection, live totals, overlapping-booking rejection, browser persistence, cancellation and JSON export.

## Run

`python -m http.server 8011`

Open http://localhost:8011. Run tests with Node and Playwright: `node test.cjs` (set PLAYWRIGHT_MODULE to your installed Playwright module path).

## Limits

All venues, capacities, prices and availability are fictional demo data. No payment or reservation is made. Records are browser/origin-local, not synchronized or authoritative. Clearing site data removes bookings. External photos/fonts require network access.

Illustrative interior images: Unsplash https://unsplash.com/license — image IDs are retained in index.html. No affiliation with pictured venues.

Source files: index.html holds markup, styles, studio data and interactions; test.cjs exercises filters, booking totals, persistence, overlap rejection and cancellation at phone/desktop widths.
