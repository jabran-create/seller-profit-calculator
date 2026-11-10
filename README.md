# Seller Profit Calculator

A free, simple, offline tool for Amazon and Etsy sellers. Enter your selling
price, product cost, shipping and marketplace fees — and see your real profit
per order, profit margin, and break-even price before you list a product.

## Why this exists

New sellers often look only at the selling price and forget the marketplace
fee, shipping, packaging and ads. A product that "sells for $25" can easily
lose money after all the costs. This calculator makes the real number visible
in seconds, so a bad product is spotted before money is spent on stock.

## Features

- Amazon and Etsy fee presets (editable — fees change, so always verify)
- Custom marketplace mode with your own fee %
- Profit per order, profit margin %, and break-even price
- USD, GBP and PKR currencies
- One single HTML file — no install, no server, no tracking, works offline

## How to use

1. Open `index.html` in any browser (double-click it, or drag it into a browser window).
2. Pick the marketplace (Amazon / Etsy / Other).
3. Fill in selling price, product cost, shipping and any other costs.
4. Click **Calculate profit**.
5. If profit is red / negative, raise the price or find a cheaper supplier.

## Fee notes (estimates — check the live fee before you rely on it)

- **Amazon:** referral fee is usually around 15% of the selling price (varies by category).
- **Etsy:** 6.5% transaction fee + about 3% payment processing + $0.20 listing fee per listing.
- The calculator ships with 15% for Amazon and 9.5% + $0.20 for Etsy as
  starting defaults. Change them to match your real category and country.

## Tech

Plain HTML, CSS and JavaScript in a single file. No build step, no
dependencies, no data leaves your browser.

## License

MIT — see `LICENSE`. Free to use, copy and change.
