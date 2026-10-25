# Preço Claro

A simple, static product price comparison helper for Portugal. Search a product across popular Portugal-facing retailers, open a live search for each shop, and enter the prices you confirm. Prices are stored in the browser on the current device.

## Run locally

Open `index.html` in a browser, or serve this directory with any static file server, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Retailers

Worten, FNAC, Rádio Popular, PCDIGA, MediaMarkt, Amazon.es, Continente and KuantoKusta.

The app does not scrape retailer pages or automatically fetch prices. Each shop search opens Google results scoped to that retailer, so the user can confirm the matching model, availability, seller and delivery cost before recording a price.

