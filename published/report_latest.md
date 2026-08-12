# Daily Multi-Horizon Stock Scanner — 2026-08-12

**Model:** 1.5.0-nokey-shared

## Interpretation

There is deliberately no single fixed investment horizon:

- **Short:** approximately 1–20 trading days
- **Swing:** approximately 1–3 months
- **Medium:** approximately 3–12 months
- **Long:** approximately 12–36 months

`consensus_score` is only a descriptive median of those horizon scores, not a universal buy signal.

## Market regime

- unavailable

Market regime is kept separate from company quality; it is intended for later exposure/position-sizing research, not to rewrite a company's quality score.

## Top eligible names

_No rows._

## Event watch

Upcoming earnings close enough to overwhelm the normal factor model are shown separately.

_No rows._

## Fastest improving (5 stored runs)

_No rows._

## Fastest deteriorating (5 stored runs)

_No rows._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- No pair above configured warning threshold (or insufficient history/universe size).

High correlation does not automatically mean a factor is wrong. It warns that the model may be counting the same underlying information more than once.

## Hard filters

- Market cap >= €1,000,000,000
- Price >= €5.0
- Median 20-day turnover >= €10,000,000
- Price history >= 230 observations
- Data confidence >= 55/100
- Maximum weekday-only stale-price lag: 3 business days

## Important remaining limitations

This live-forward scanner stores what it knew on each run. A historical backtest still needs genuine point-in-time historical constituents, delisted names, and information-availability timestamps. Re-downloading today's revised fundamentals for 2018 is not a valid point-in-time backtest.

`financials-lite` and `reit-lite` are deliberately conservative sector adaptations. A production bank model should use banking-specific capital/credit metrics; a production REIT model should use FFO/AFFO and NAV-style valuation.

Going-concern/accounting-restatement/legal-risk detection is not hard-coded from free text yet. Those require filing/news parsing with reliable timestamps.

The weekday stale-price check avoids weekend mistakes but is not yet exchange-holiday-aware.
