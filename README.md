# Commercial Property Rotherham

A rebuilt website for Commercial Property Rotherham, chartered surveyors and commercial property agents in Rotherham and South Yorkshire.

It's a single static page (`index.html`) with no build step. Open it in a browser, or serve the folder with any static host (GitHub Pages, Netlify, Cloudflare Pages).

## Pages

The site uses hash routes:

- `#home`: hero search, sectors, latest listings, ways to get in touch and services
- `#properties`: listings with filters (sale/let, type, size, area, keyword), sorting, grid or list view and a shortlist
- `#p-<ref>`: property detail with key facts, accommodation table, EPC chart, transport, small print and an enquiry form
- `#services`, `#about`, `#contact`

## Editing listings

Listings live in the `PROPS` array near the top of the script in `index.html`. Each entry holds the reference, tenure (`sale` or `let`), price or monthly rent, size, rateable value, EPC, features, accommodation rows and transport links.

## Still to do

- Add the remaining listings (only the five featured on the old home page are in so far)
- Replace the placeholder drawings with real property photos
- Connect the enquiry and contact forms to an inbox or form service
