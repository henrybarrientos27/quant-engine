# Quant Engine — High-Level Overview
This project evaluates trading strategies under uncertainty using **Monte Carlo** stress tests and **Geometric Brownian Motion** path models.  
**Note:** Core strategy generation and evaluation internals are intentionally redacted.

## What this does (conceptually)
- Simulates price paths (GBM) to test robustness.
- Evaluates strategies across sessions (e.g., 08:30–09:30 CT) and regimes.
- Summarizes risk metrics (win rate, drawdown, expectancy) at a high level.

## What’s intentionally NOT here
- Strategy formulas / genetic evolution code
- Private data feeds or API keys
- Any production execution logic
