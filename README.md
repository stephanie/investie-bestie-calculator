# Investie Bestie Calculator

A single-page calculator that shows what a lump sum plus monthly contributions could grow to in index funds that have historically beaten most active fund managers, with a rent-vs-buy section underneath.

Open `index.html` in a browser. No build step, no dependencies beyond Google Fonts.

## What's in it

- Six index funds (S&P 500, Total US Market, MSCI World, All-World, Nasdaq-100, Emerging Markets) with long-run average annual returns and the matching SPIVA stat on how many professionals lose to each.
- A growth chart against a 2% savings account.
- A side-by-side table of all funds for the same inputs.
- "Buy a home or invest?": enter a home price, deposit, mortgage, costs and rent, and compare home equity against renting and investing the deposit in the chosen fund over the same horizon, with a breakeven price-growth figure.

## Return assumptions

Long-run nominal averages, dividends reinvested, compounded monthly, before fees, tax and inflation. Edit the `FUNDS` array in `index.html` to change them.

| Fund | Rate used |
|---|---|
| S&P 500 | 10.5% |
| Total US Market | 10.0% |
| MSCI World | 9.0% |
| All-World | 8.5% |
| Nasdaq-100 | 16.0% |
| Emerging Markets | 7.0% |

## Sources

- [SPIVA U.S. Year-End 2025](https://www.spglobal.com/spdji/en/spiva/article/spiva-us-year-end-2025/)
- [SPIVA Persistence Scorecard Year-End 2025](https://www.spglobal.com/spdji/en/spiva/article/us-persistence-scorecard/)
- [Nasdaq-100 vs S&P 500, Q4 2025](https://www.nasdaq.com/articles/when-performance-matters-nasdaq-100-vs-s-and-p-500-q4-2025)
- [S&P 500 trailing returns (SPY)](https://chartrow.com/quote/spy/trailing-returns)
- [MSCI World trailing returns (URTH)](https://chartrow.com/msci-world/trailing-returns)

## Disclaimer

General education only. Not financial advice, not a recommendation, not a forecast. Past returns don't guarantee future ones.
