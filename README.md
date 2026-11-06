# Leisure Depot — Price Book

Internal rep tool: search Lloyd Flanders, Casual Comfort, Telescope and Frankford, build a quote with up to 20% discount, and send it.

- **Prices** come from the published Google Sheet (see `CONFIG` in `index.html`). Update the sheet, not this repo.
- **Send** posts the quote to GoHighLevel through the shared lead endpoint on the Spa Studio site (`https://leisuredepot-spa-studio.netlify.app/api/lead`), tagged `ld-tool-price-book`, and opens the customer email.
- Deploys from `main` on Netlify (project `leisuredepot-pricebook`), no build step.
