# Preço Claro

A simple product price comparison helper for Portugal. Search a product to open KuantoKusta's official live results page, which lists current offers from multiple shops. The optional local tracker lets you enter and compare prices yourself; those entries are stored in the browser on the current device.

## Run locally

Open `index.html` in a browser, or serve this directory with any static file server, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Retailers

Worten, FNAC, Rádio Popular, PCDIGA, MediaMarkt, Amazon.es, Continente and KuantoKusta.

The app does not scrape retailer pages or copy prices out of KuantoKusta. Live results are provided by KuantoKusta's own search page. Each retailer card also opens Google results scoped to that shop, so the user can confirm the matching model, availability, seller and delivery cost before recording a price.

