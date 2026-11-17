# SAT Score Calculator

A free, no-signup Digital SAT score calculator. Enter the number of correct answers for each module and get an estimated **400–1600** score, section breakdowns, and the percentile your score falls into.

**Live site: [satcalcpro.dpdns.org](https://satcalcpro.dpdns.org/)**

---

## What it does

- **Score estimation** — converts raw correct-answer counts from the Reading & Writing and Math modules into a scaled 400–1600 score, using the College Board's practice-test conversion tables as a reference.
- **Section breakdown** — shows the Reading & Writing and Math section scores (200–800 each) alongside the total.
- **Percentile lookup** — tells you roughly what percentage of test takers scored below you.
- **No accounts, no data collection** — every calculation runs in the browser. Nothing is uploaded or stored.

## Pages

| Page | What's on it |
|---|---|
| [Home / calculator](https://satcalcpro.dpdns.org/) | The calculator itself, plus how scoring works |
| [SAT Score Calculator 2026](https://satcalcpro.dpdns.org/sat-score-calculator-2026/) | 2026-specific scoring notes and estimator |
| [College Board score tables](https://satcalcpro.dpdns.org/college-board/) | How the official conversion tables are built |
| [What is a good SAT score?](https://satcalcpro.dpdns.org/good-sat-score/) | Benchmarks by college selectivity |
| [SAT percentiles](https://satcalcpro.dpdns.org/sat-percentiles/) | Full 400–1600 percentile chart |
| [Average SAT score](https://satcalcpro.dpdns.org/average-sat-score/) | National averages and recent trends |

## Why we built it

Most "SAT score calculators" online either ask you to sign up, hide the result behind a paywall, or return a number with no explanation. This one is a single static page: no login, no upload, and it shows the arithmetic so you can sanity-check the estimate.

## Technical notes

- Plain static HTML/CSS/JS — no framework, no build step, no server-side code.
- Hosted on GitHub Pages behind a custom domain, served over HTTPS.
- Score conversion tables are approximations derived from publicly released College Board practice-test scales. Official scores are produced only by the College Board; this tool is an independent estimator and is not affiliated with or endorsed by the College Board.

## Disclaimer

This is an independent study aid. It is not affiliated with, endorsed by, or sponsored by the College Board. "SAT" is a trademark of the College Board.
