# Stock Trader

Mobile-first stock analysis prototype by AFI LLC.

## Current version

**v0.9**

Features include:

- Twelve Data market-data connection (API key stored locally in the browser, never committed)
- Current stock price and historical daily chart data
- Company/instrument name and market details
- Persistent local watchlist
- 20/50/200-day moving averages
- RSI(14)
- MACD and signal line
- Relative-volume analysis
- Graham Formula valuation
- Graham Number valuation
- Combined 100-point opportunity score
- BUY / WATCH / HOLD / SELL labels
- Free/Pro product preview

## Run locally

Open `index.html` in a modern browser. For live market data, expand **Twelve Data connection** and enter your own Twelve Data API key. The key is saved only in that browser's local storage.

## Deploy on Vercel

This repository is ready for a static Vercel deployment.

1. In Vercel, choose **Add New → Project**.
2. Import the GitHub repository `Ridge3d/Stock-trader-`.
3. Framework preset: **Other** (or let Vercel auto-detect the static site).
4. Build command: leave empty.
5. Output directory: leave empty / project root.
6. Deploy.

After Git integration is connected, future pushes to `main` can automatically trigger new Vercel production deployments.

## Important

This project is an experimental prototype. Its scoring rules have not been validated to produce profits and should not be treated as investment advice.

© 2026 AFI LLC. All rights reserved.
