# Custom-SP500-Index-Build
Coded in Python

This is my attempt at creating a passive index that should potentially outperform the SP500. I tried several ways to do this, starting off by picking the top 50 historically top performing stocks and then creating an index. That gave me a highly volatile index with a negative Sharpe ratio. Moreover, the index performed poorly with respect to SP500.

From here I redirected to volatility reduction so I decided to pick 50 stocks off SP500 that have historically had the lowest annualized volatility. I The resulting index has a superior Sharpe ratio and is able to outperform the SP500.

In order to diversify, I pick 5 least volatile stocks from each sector of the SP500. This not only gives representation to each sector but also allows the index to be hedged against sector concentration risk.


