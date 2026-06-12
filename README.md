# R Calc — Position Size Calculator

A free, self-contained position sizing calculator for swing traders. One HTML file, zero dependencies, works offline.

**Live:** https://vinthomas1.github.io/rcalc/

## What it does

- Set your account size and what 1R means to you (% of account)
- Enter your entry and stop — get exact shares and dollar position size instantly
- Auto-detects long vs short from stop placement
- Shows 2R / 3R price targets
- Flags risk issues: stops inside ADR noise, position concentration, total portfolio heat
- One-tap "copy summary" for your trade journal
- Dark mode, mobile-friendly, WCAG AA accessible

## How to use

Open the live link above, or download `index.html` and open it in any browser. No install, no signup, no tracking — the page makes zero network requests.

## The math

```
Shares = Risk per trade ÷ |Entry − Stop|
```

Position size adapts to stop distance automatically: wider stops → smaller positions, tighter stops → larger positions. Risk stays constant.

---

Created by [Vin Thomas](https://x.com/VinRips)
