# SOL/USDC :: PRICE TERMINAL

```
 ██████╗  ██████╗ ██╗         ██████╗ ██████╗ ██╗ ██████╗███████╗    ████████╗███████╗██████╗ ███╗   ███╗
██╔════╝ ██╔═══██╗██║         ██╔══██╗██╔══██╗██║██╔════╝██╔════╝    ╚══██╔══╝██╔════╝██╔══██╗████╗ ████║
███████╗ ██║   ██║██║         ██████╔╝██████╔╝██║██║     █████╗         ██║   █████╗  ██████╔╝██╔████╔██║
╚════██║ ██║   ██║██║         ██╔═══╝ ██╔══██╗██║██║     ██╔══╝         ██║   ██╔══╝  ██╔══██╗██║╚██╔╝██║
 ██████╔╝╚██████╔╝███████╗    ██║     ██║  ██║██║╚██████╗███████╗       ██║   ███████╗██║  ██║██║ ╚═╝ ██║
 ╚═════╝  ╚═════╝ ╚══════╝    ╚═╝     ╚═╝  ╚═╝╚═╝ ╚═════╝╚══════╝       ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝
```

> **EYE CANDY ONLY. NOT FINANCIAL ADVICE. NOT TRADING ADVICE. NOT ANYTHING ADVICE.**  
> This is a pretty terminal that goes bleep bloop. That's it.

**[▶ LIVE DEMO](https://eric-lautanen.github.io/SOLPriceTerm/)**

---

## What is this

A single-file, zero-dependency hacker-aesthetic price terminal for **SOL/USDC** — live data streamed directly from 10 exchanges in your browser via WebSocket. Green phosphor glow. Matrix rain. VT323 font. The works.

No server. No backend. No npm install. Open the file. Vibe.

## Features

- **10 live price feeds** — Coinbase, OKX, Bybit, Kraken, Bitstamp, Gate.io, Bitfinex, Gemini, Crypto.com, Pyth
- **6 live orderbook feeds** — aggregated into a single depth view with bid/ask pressure bars
- **Consensus price** — median across all connected feeds
- **Per-exchange imbalance** — top 5 levels, visualized
- **Live spread matrix** — best buy / best sell / Δ delta at a glance
- **Tick log** — auto-pruned every 2 minutes
- **Matrix rain** — because of course
- **Zero dependencies** — one `.html` file, runs offline after first load (fonts cached)

## Usage

```bash
# Option 1: just open it
open solhack.html

# Option 2: serve locally if your browser blocks local WS
npx serve .
```

No build step. No node_modules. No env vars. Drop it in an S3 bucket, GitHub Pages, or your desktop. Works anywhere.

## Exchanges

| Feed | Type | Pair |
|------|------|------|
| Coinbase | WebSocket | SOL-USD |
| OKX | WebSocket | SOL-USDT |
| Bybit | WebSocket | SOLUSDT |
| Kraken | WebSocket | SOL/USD |
| Bitstamp | WebSocket | SOLUSD |
| Gate.io | WebSocket | SOL_USDT |
| Bitfinex | WebSocket | tSOLUSD |
| Gemini | WebSocket | SOLUSD |
| Crypto.com | WebSocket | SOL_USD |
| Pyth | HTTP Poll | SOL/USD |

## ⚠️ Disclaimer

This tool is **purely cosmetic / educational**. It does not:
- Execute trades
- Store your data
- Connect to any wallet
- Constitute financial advice of any kind

Numbers go up. Numbers go down. Phosphor glows. That's the whole pitch.

---

*Built with WebSockets, vibes, and an unhealthy appreciation for CRT aesthetics.*
