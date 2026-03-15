# Value Investing Research

A collection of interactive investment research pages — thesis deep dives, educational infographics, and analytical tools — built on Buffett-style value investing principles.

**Live site:** [dubiwork.github.io/value-investing](https://dubiwork.github.io/value-investing/)

## What's Inside

| Category | Description |
|----------|-------------|
| **Investment Thesis** | Stock-specific deep dives with bull vs bear debates, cash flow analysis, and valuation assessments |
| **Education & Concepts** | Visual guides to value investing fundamentals — ROIC, WACC, Incremental ROIC, and more |

## Current Pages

- **[ZETA Global 2025: The Cash Truth Test](https://dubiwork.github.io/value-investing/thesis/zeta-thesis-2026.html)** — Bull vs Bear debate analyzing ZETA's cash flow, dilution, balance sheet quality, and growth sources
- **[The Value Investor's Compass: Incremental ROIC](https://dubiwork.github.io/value-investing/education/inc-roic.html)** — WACC, ROIC, and Incremental ROIC explained with real-world analogies and a ZETA case study
- **[ZETA Global: Forensic Investigation Report](https://dubiwork.github.io/value-investing/thesis/zeta-forensic-2026.html)** — Deep bear case covering consent farms, revenue round-tripping, FCF illusion, M&A smoke screen, and insider selling
- **[Reverse DCF: The Value Investor's Secret Weapon](https://dubiwork.github.io/value-investing/education/reverse-dcf.html)** — Reverse DCF framework explained with a real AMD case study
- **[AMD Investment Thesis 2026](https://dubiwork.github.io/value-investing/thesis/amd-thesis-2026.html)** — Buffett-lens analysis: business moat, true FCF, Reverse DCF valuation, capital allocation. HOLD at $160, buy zone $85–$113
- **[AMD Strategic Research: Pre-Q1 2026](https://dubiwork.github.io/value-investing/thesis/amd-forensic-2026.html)** — Comprehensive forensic deep-dive: market share, AI deals, gross margins, dilution, geopolitical risks. Interactive tabs + charts
- **[Capital Allocation: Why M&A Deals Fail](https://dubiwork.github.io/value-investing/education/ma-capital-allocation.html)** — Interactive guide to M&A failures with risk simulator and AMD case study (Xilinx, ZT Systems). Based on Saturday Stock School

## How It Works

Pages are organized into folders by category (`thesis/`, `education/`, etc.). A `pages.json` manifest stores metadata (title, description, tags, date) for each page. The landing page dynamically reads this manifest and renders an organized, filterable view — no manual index editing needed.

```
value-investing/
├── index.html          ← Dynamic landing page
├── pages.json          ← Page metadata manifest
├── thesis/             ← Stock-specific analysis
│   └── zeta-thesis-2026.html
└── education/          ← Concepts & frameworks
    └── inc-roic.html
```

## Author

**Dubi Greenfeld** — Value investing researcher applying Buffett & Munger principles to public markets.

## Changelog

| Date | Change |
|------|--------|
| 2026-03-15 | Added Capital Allocation: Why M&A Deals Fail — interactive educational guide with risk simulator and AMD case study |
| 2026-03-15 | Added AMD Strategic Research — comprehensive forensic deep-dive merging two reports with interactive tabs and charts |
| 2026-03-15 | Added AMD Investment Thesis 2026 — "Industrial Financial Noir" design with Buffett-lens analysis |
| 2026-03-14 | Added Reverse DCF educational guide with AMD case study |
| 2026-03-14 | Added ZETA Global forensic investigation report (bear case / short thesis) |
| 2026-03-13 | Added Firebase Analytics (edgar-value-miner project) to all pages for unified usage tracking |
| 2026-03-12 | Added custom diamond favicon to index page |
| 2026-03-12 | Updated Inc. ROIC guide — added money vs percentage clarification, Buffett's 10% hurdle rate badge |
| 2026-03-12 | Reorganized repo into `thesis/` and `education/` folders with dynamic index and `pages.json` manifest |
| 2026-03-12 | Initial publish — ZETA Global 2025 thesis and Incremental ROIC educational guide |
