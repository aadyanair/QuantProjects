# Quant Learning Projects

Simple Python projects for learning quantitative finance.

## 1. Simple Backtester
- Moving average crossover strategy
- Compares strategy vs buy-and-hold
- Basic performance analysis

## 2. Pair Trading
### CORE CONCEPT:

Statistical arbitage through mean reversion - identifying temporarily diverged stock pairs and betting on their reconciliation.

### WHAT WAS BUILT:

A market-neutral strategy that:
- Finds highly correlated stocks (KO & PEP:93.5% correlation)
- Trades the spread between them when it deviates statistically
- Goes long the underperfomer + short the outperformer
- Profits when the relationship normalizes

### Key Learning:
Pairs trading isn't about predicting direction, but about exploiting statistical relationships - a fundamental quant approach that reduces market risk.

### Technical Stack:
- Correlation analysis & Z-score signals
- Hedged positions (long/short simultaneously)
- Risk-adjusted performance metrics
