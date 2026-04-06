# DekantPM — Mathematical Analysis

An interactive, offline-first document providing comprehensive mathematical analysis of **continuous prediction markets** and their implementation through discretized L²-Norm Automated Market Makers (AMMs).

## Overview

DekantPM explores the theory and mathematics behind continuous prediction markets, where participants trade contracts whose payoffs depend on the probability distribution of continuous future outcomes. Rather than traditional binary prediction markets ("Will X happen?"), this system handles continuous quantities like prices, temperatures, and other real-world measurements.

## Key Topics

- **L²-Norm AMM**: Core mechanism architecture for continuous markets
- **Distribution Trading**: Methods for trading probability distributions
- **Liquidity Provision**: LP mathematics and incentive structures
- **Market Initialization**: Setting up and parameterizing the market
- **Discretization**: Bin-based discretization strategies for practical implementation
- **Fee Structure**: Economic incentives and protocol fees
- **Solvency Proof**: Mathematical guarantees for market integrity

## Features

### Mathematical Document
- 📐 **Full Mathematical Treatment** — Rigorous proofs, formulas, and theoretical foundations
- 📊 **Visualizations** — Chart.js-powered graphs and interactive demonstrations
- 🌓 **Dark/Light Theme** — Adaptive UI with both themes
- 🌍 **Multilingual** — English and Persian (Farsi) support
- 💻 **Offline-First** — All resources included locally; works without internet
- ⚡ **Built for Solana/Anchor** — Designed with blockchain implementation in mind

### Market Playground
- 🧮 **Interactive Demos** — Market Playground, Distortion Explorer, Gaussian Discretization demo, LP Calculator
- 🏪 **Multi-Market Support** — Create and manage multiple markets simultaneously with a market selector dropdown
- 👥 **Global Traders** — Traders are shared across all markets with a single wallet; per-market holdings and P&L are tracked separately
- 🔁 **Discrete & Distribution Trading** — Buy/sell individual bins or trade Gaussian-weighted distributions across bins
- 📈 **Interactive Trade Previews** — Real-time buy/sell preview with estimated tokens, peak payout, max profit, and new probability before executing a trade; toggle between buy and sell preview modes
- 💰 **Per-Market Fee Configuration** — Configure trade fee (bps), LP fee share (%), and redemption fee (bps) independently for each market via a dedicated fee modal
- 📋 **Portfolio Tab** — Detailed portfolio view with trader summary cards (wallet, invested, received, expected payout, peak payout, net P&L), holdings table by bin, and per-trader trade history
- 📊 **Market Overview** — Dashboard showing market invariant (k), bins, range, accumulated LP fees, LP shares, collateral flow, and top bins ranked by probability
- 📜 **Trade History** — Per-market trade history recording with type badges (buy/sell/LP), detail, amount, result, and timestamp
- 🔄 **Resolve & Re-Resolve** — Resolve markets at any outcome value, and re-resolve to explore different scenarios; resolve state persists across save/load
- 💾 **State Persistence** — Autosave (configurable interval) and manual save/load via localStorage; preserves all markets, traders, trade history, settings, and resolve state
- ⚙️ **Settings Modal** — Configurable font size (XS–XL), number format (short `1.2M` / long `1,200,000`), decimal precision (0–6), theme, language, and autosave toggle
- 📝 **Action Log** — Scrollable bottom panel logging all market actions (trades, LP operations, resolves) with timestamps and details
- 🔔 **Toast Notifications** — Non-intrusive feedback for save/load/trade operations
- 💳 **Wallet Top-Up** — Add funds to any trader's wallet at any time

## Demo

Explore the interactive document live at: **https://pa-ya.github.io/dekantpm**

## Structure

```
dekantpm/
├── index.html           # Document markup with embedded styles
├── math_doc_script.js   # All interactive logic (market engine, UI, persistence)
├── fonts/
│   ├── fonts.css        # Font-face definitions
│   └── *.ttf            # Local font files for offline use
└── lib/
    ├── chart.umd.min.js # Chart.js visualization library
    └── tex-svg.js       # MathJax for mathematical rendering
```

## Getting Started

Simply open `index.html` in your browser. No build process, no dependencies installation required.

## Technologies

- **MathJax** — Mathematical equation rendering (LaTeX/TeX)
- **Chart.js** — Data visualization and interactive charts
- **Pure HTML/CSS/JavaScript** — No framework dependencies
- **Progressive Enhancement** — Works on all modern browsers
