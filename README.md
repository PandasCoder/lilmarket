# MarketScout

> Real-time market scanner for online games — find the best items to trade, transport and craft.

MarketScout pulls live market data and turns it into actionable opportunities: which items to buy cheap in one city and sell for profit in another, which items are worth crafting right now, and how prices have moved over time.

No spreadsheets. No manual price checking. Just open the dashboard and see what's worth doing.

---

## Supported Games

| Game | Status | Demo |
|---|---|---|
| [Albion Online](games/albion/README.md) | ✅ Live | [albion.codea.plus](https://albion.codea.plus) |

More games coming. If you want to see your game here, open an issue.

---

## How it works

MarketScout connects to each game's public market data API, stores price and trade history, and runs a scoring algorithm that balances profit margin, market volume, and data freshness. The result is a ranked list of opportunities you can act on immediately.

Each game integration is independent — different economies, different mechanics, same idea.

---

## Status

This is an early proof of concept. The Albion Online integration is fully functional and running live. Feedback and suggestions are welcome via [Issues](https://github.com/PandasCoder/market-scanner/issues).
