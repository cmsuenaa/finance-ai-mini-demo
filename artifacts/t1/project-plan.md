# T1 Project Plan

## Project Goal

Develop a clear and reproducible research workflow for comparing three familiar asset classes using the illustrative ETFs in this repository:

- `SPY` — US equities
- `TLT` — long-term US Treasury bonds
- `GLD` — gold

The plan will later support a bounded analysis task and a verifiable agent workflow in subsequent tutorials.

## Available Data

The repository provides one small, fixed dataset, `data/etf_snapshot.csv`, containing one row per illustrative ETF with the following fields (see `data/data_dictionary.md`):

- `ticker` — short identifier for the ETF
- `asset_class` — broad type of asset represented
- `expected_return_pct` — illustrative annual return assumption
- `volatility_pct` — illustrative annual variability assumption
- `max_drawdown_pct` — illustrative largest peak-to-trough loss
- `expense_ratio_pct` — illustrative annual fund fee

The dataset is synthetic teaching data, not live or historical market observations. It is deliberately small and fixed so no download or data-cleaning step is required.

## Expected Final Deliverable

A concise written research plan (this document, `artifacts/t1/project-plan.md`) that documents the project goal, the available data, milestones, and known limitations. Later tutorials are planned to extend the repository with a bounded analysis task and an organized, verifiable agent workflow that compares the three asset classes.

## Three Project Milestones

1. **Project setup (T1)**: Document the project plan, confirm the data dictionary matches the dataset, and agree on the research goal and scope.
2. **Bounded analysis**: Design and run a clearly scoped comparison of SPY, TLT, and GLD using the illustrative assumptions (planned work, not yet completed).
3. **Verifiable workflow**: Organize the analysis as a reproducible, agent-assisted workflow with clear verification steps and a documented final result (planned work, not yet completed).

## One Data Limitation

All numeric values in `etf_snapshot.csv` are synthetic teaching assumptions. They are not current quotations, verified historical estimates, or forecasts, and the dataset omits correlations, taxes, transaction costs, liquidity, currency exposure, and investor-specific constraints. Therefore any later analysis is illustrative only and must not be used as investment advice or as the basis for a real investment decision.

## Next Action

Have the student review this plan and save it with Git (commit and push are intentionally left to the student; the agent must not run Git commands that change the repository during T1). After review, the next tutorial can build on this plan to design the bounded analysis milestone.
