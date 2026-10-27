# Notes on this fork

- Upstream: https://github.com/freqtrade/freqtrade
- Fork: https://github.com/bisource05/freqtrade
- Source that led me here: https://x.com/carm1nee/article/2113257064352915664 ("The 10 Most Dangerous GitHub Repos in Trading", Carm1ne, Oct 22, 2026)
- Role in that stack: Execution desk - crypto bot

## What it is

A free crypto trading bot with backtesting, plotting, money management, parameter tuning, adaptive machine learning, dry-run mode and control from Telegram or a web UI, for spot and futures on several exchanges.

## Caution

Compare the backtest on the period you tuned on with a backtest on a period it never saw, and run the lookahead check. Stay in dry-run until the numbers survive fees.

## Status

Forked Oct 27, 2026. Nothing here has been run, configured, or connected to any account, API key, or real money. Paper / dry-run first, and only after a walk-forward backtest with fees, a look-ahead check, and 30 days on paper.
