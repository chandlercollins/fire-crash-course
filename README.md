# FIRE Crash Course

An interactive, visual crash course in **financial independence** — how saving, debt, taxes,
employer matches, and time compound into the freedom to stop working. Built as a single
HTML file with [D3.js](https://d3js.org/) (CDN), no build step.

🔗 **Live:** https://chandlercollins.github.io/fire-crash-course/

It follows one example two-income household ("Sam & Jordan") through four scroll views:

1. **The Future Vision** — a Monte Carlo projection with a dynamic FIRE target (the 4% rule),
   plus toggles for how much you invest, retirement spend, withdrawal rate, pay growth, and
   today's-dollars vs future-dollars.
2. **The Flow of Money** — an animated waterfall: every dollar of income gets a job, with a
   "prioritise brokerage ↔ debt-free" dial.
3. **The Reality** — the everyday budget that's left, and how housing quietly decides everything.
4. **The Setup** — the automation blueprint that makes the plan run itself.

> The numbers are an **illustrative example**, not financial advice. A "plug in your own
> numbers" mode is on the roadmap — see the parent [portfolio roadmap](https://github.com/chandlercollins/chandlercollins.github.io/blob/main/ROADMAP.md).

## Running locally

```bash
node .claude/serve.cjs    # → http://localhost:4323
```
…or just open `index.html` in a browser.

## Make it your own

All assumptions live in the `DATA` object near the top of the `<script>` in
[`index.html`](index.html). Change the numbers there to model a different household.

## Credit

A public, sanitized derivative of a personal planning tool, by
[Chandler Collins](https://chandlercollins.github.io/).
