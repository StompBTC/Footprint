# Footprint

A free, single-file browser app that turns live public trade data from Coinbase, Kraken and Bitstamp into an order-flow footprint chart. It covers BTC, ETH, SOL, XRP, LTC and DOGE, and runs on desktop and Android.

## What it does (and doesn't do)

- Reads **public** trade data only. No account, login, API key or wallet connection.
- Never asks for passwords, seed phrases or personal information.
- Runs inside your browser's sandbox. It can't install anything or read files on your computer.
- Saves chart history only in your own browser (and, if you choose, in one folder you pick).
- The only sites it talks to are the Coinbase, Kraken and Bitstamp public market-data endpoints.

All of the code is in one readable file. Desktop and phone run the same code; the layout adapts to the screen.

## Use it

- **Desktop:** download `desktop/footprint.html` and open it in Chrome or Edge. It runs straight from your computer.
- **Phone (Android):** open the hosted link in Chrome (link to be added), then menu > Add to Home screen > Install.

## What's in here

| Location | What it is |
| --- | --- |
| `desktop/footprint.html` | Desktop version: one file you download and open |
| `index.html`, `manifest.webmanifest`, `sw.js`, icons | Phone / web version, served by GitHub Pages so it installs like an app |
| `versions/` | Every version, 0.01 through 0.08 |
| `Footprint-White-Paper.pdf` | How it works and what changed in each version, in plain language and technical detail |

What changed in each version is in [CHANGELOG.md](CHANGELOG.md). The current version is 0.08.

## Disclaimer

For information and education only. Not financial advice. Data comes from the exchanges as-is and may contain gaps or errors.
