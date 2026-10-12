# Changelog

Every version listed here is in the `versions/` folder.

## 0.09 — Cleaner phone layout, day/night backgrounds, more indicators
- Phone: slimmer top bar; floating pause button, with a Live button that appears when you scroll back; one-line status (tap for details)
- Price axis sizes itself to each coin's prices so they're never cut off; the delta profile narrows (then drops its labels) on small screens
- Backgrounds: Auto (follows the time of day, 30-minute blends), Midnight, Morning, Slate, Dusk, Night, or Custom colors; phones default to Auto, desktop stays on Midnight
- Night is a lifted, low-glare slate with brighter labels for dark rooms
- New order-flow tools: stacked imbalances, value area (VAH / VAL / POC), delta divergence
- New indicators: anchored VWAP (pick any bar), Supertrend, Keltner and Donchian channels, pivot points (daily or weekly), prior-week high / low
- New panels: OBV, ATR, ADX / DMI
- Indicators menu: grouped by category, with search and favorites

## 0.08 — Phone fixes
- Phones keep the screen on by default (re-requested on the next tap if Android drops it)
- Auto Fib is off by default on phones, where it clutters a small screen; still available under Indicators
- Status line shows ☀ while the screen is being kept on, or a note if the page isn't on https

## 0.07 — Six coins, phone version, installable app
- Coin selector (BTC, ETH, SOL, XRP, LTC, DOGE) next to the "Footprint" title
- Tracking: collect only the viewed coin, or a selection of coins in the background
- Phone layout and touch controls (pinch, swipe, hold for crosshair, tap for details, double-tap for live)
- Price-axis drag to scale price (desktop and phone)
- Device role: Viewer (keeps nothing) or Collector (saves history)
- Keep screen on, battery saver, installable web app
- Storage upgraded to per-coin records; BTC history from 0.06 migrates automatically

## 0.06 — Storage, gap recovery and history on first start
- Auto-save to browser storage (and optional folder), with a RAM limit
- Backfills trades missed while closed, asleep or disconnected; gap markers on the chart
- Only one tab collects at a time; sleep detection; clock check; export by date range
- Loads about 250 bars of history for the selected timeframe on first start; marks where older history is Kraken-only

## 0.05 — Developer timeframes
- 5, 10, 15 and 30-second charts covering the last 2 hours

## 0.04 — Default profile
- One-click default: Auto Fib (yellow resistance / purple support), SMA 200 (white), custom-styled RSI, Volume
- Save and load your own profile

## 0.03 — Full indicator suite, settings, pause and speed
- SMAs, Bollinger Bands, Ichimoku
- Bottom panels: Volume, RSI, CVD, MACD, Stoch RSI, resizable
- Settings for every indicator and panel; Auto Fib anchor options; auto support/resistance colors
- Pause the chart while data keeps collecting; profile-row hover highlights matching bars
- Performance work for older hardware

## 0.02 — Restyle, candles and first indicators
- Cleaner, more polished look; larger bar-delta summary; more space before the profile
- Faint candles behind the cells, shown clearly on hover
- VWAP with bands, EMAs, key levels; stronger delta-profile contrast
- Every indicator can be switched on or off; Auto Fib with levels that flip between support and resistance

## 0.01 — First browser build
- Live BTC footprint from Coinbase, Kraken and Bitstamp
- Cell modes: Delta, Sell × Buy, Volume; USD or BTC units
- Visible-range profile, bar delta strip, large-print bubbles
- JSON/CSV export and JSON import
