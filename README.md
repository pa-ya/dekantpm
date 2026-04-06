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

- 📐 **Full Mathematical Treatment** — Rigorous proofs, formulas, and theoretical foundations
- 🧮 **Interactive Demos** — Market Playground, Distortion Explorer, Gaussian distributions, LP Calculator
- 📊 **Visualizations** — Chart.js-powered graphs and interactive demonstrations
- 🌓 **Dark/Light Theme** — Adaptive UI with both themes
- 🌍 **Multilingual** — English and Persian (Farsi) support
- 💻 **Offline-First** — All resources included locally; works without internet
- ⚡ **Built for Solana/Anchor** — Designed with blockchain implementation in mind

## Demo

Explore the interactive document live at: **https://pa-ya.github.io/dekantpm**

## Structure

```
dekantpm/
├── index.html           # Complete document with embedded styles and logic
├── assets/
│   ├── css/
│   │   └── fonts_local.css
│   ├── fonts/           # Local font files for offline use
│   └── js/
│       ├── chart.js     # Chart visualization library
│       └── tex-svg.js   # MathJax for mathematical rendering
```

## Getting Started

Simply open `index.html` in your browser. No build process, no dependencies installation required.

## Technologies

- **MathJax** — Mathematical equation rendering (LaTeX/TeX)
- **Chart.js** — Data visualization and interactive charts
- **Pure HTML/CSS/JavaScript** — No framework dependencies
- **Progressive Enhancement** — Works on all modern browsers
