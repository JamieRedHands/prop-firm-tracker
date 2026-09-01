# Prop Firm Edge

Position sizing, rule checking and a trade journal for prop-firm evaluations,
with live BTC/ETH prices from OKX perpetual futures.

**Live:** https://jamieredhands.github.io/prop-firm-tracker/

Currently covers **Breakout Prop** — Classic, Pro and Turbo, plus a no-cost paper
account for rehearsing a strategy under the same fees and drawdown rules.

- **Dashboard** — eval simulator, which challenge to buy, live position tracking
- **Pre-Trade Check** — exact position size with commissions and financing priced in,
  checked against the daily loss limit and the static max drawdown
- **Journal** — log trades per account, settle them at the real fill, track your true edge

Your journal is stored in your own browser and never leaves it. Nothing is sent
anywhere — the page has no backend. Use Journal → Export JSON to keep a backup.
