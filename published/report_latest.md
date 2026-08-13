# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-13

**Model:** 1.6.1-nokey-broad-value-corrguard

## Coverage architecture

- Discovery target: approximately **2,000** liquid US/European equities.
- Deep fundamental/analyst enrichment cap: **1,000** candidates per run.
- The deep shortlist is deliberately seeded by value, pullback, momentum and the manual watchlist; it is not simply the largest companies by market cap.
- Market cap hard floor after EUR normalization: **€250,000,000**.

## Interpretation

There is deliberately no single fixed investment horizon:

- **Short:** approximately 1–20 trading days
- **Swing:** approximately 1–3 months
- **Medium:** approximately 3–12 months
- **Long:** approximately 12–36 months

`consensus_score` is only a descriptive median. `undervaluation_score` is a separate value signal and never rewrites the four horizon alpha scores.

## Market regime

- **EUROPE:** unavailable
- **OTHER:** unavailable
- **US:** unavailable

## Main multi-horizon ranking

|   rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | ASML.AS  | ASML Holding N.V.                                      | EUROPE   |              618.55 |             67.21 |         64.09 |         65.69 |          74.08 |        68.73 |           86.3  |             75.61 |             25.85 |         6.1  |             86.42 | medium             |                3.27 |                   nan |                  nan |
|      2 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              174.49 |             66.64 |         77.34 |         69.13 |          64.16 |        63.22 |           68.84 |             66.87 |             49.15 |         4.69 |             86.48 | short              |               -0.97 |                   nan |                  nan |
|      3 | SAP.DE   | SAP SE                                                 | EUROPE   |              203.97 |             63.72 |         76.77 |         61.93 |          56.21 |        65.51 |           73.48 |             50.61 |             72.95 |         6.5  |             85.97 | short              |                5.57 |                   nan |                  nan |
|      4 | AIR.PA   | Airbus SE                                              | EUROPE   |              169.46 |             61.14 |         67.98 |         64.51 |          57.36 |        57.78 |           62.69 |             53.08 |             49.14 |         4.66 |             85.18 | short              |               -0.53 |                   nan |                  nan |
|      5 | SIE.DE   | SIEMENS AG                    N                        | EUROPE   |              217.31 |             56.62 |         61.35 |         54.7  |          56.06 |        57.18 |           51.81 |             59.54 |             60.36 |         4.49 |             83.32 | short              |                2.67 |                   nan |                  nan |
|      6 | NOKIA.HE | Nokia Oyj                                              | EUROPE   |               52.54 |             54.1  |         55.5  |         42.78 |          56.5  |        52.7  |           40.33 |             44.96 |             56.3  |         7.18 |             85.45 | medium             |                7.24 |                   nan |                  nan |
|      7 | ALV.DE   | Allianz SE                    v                        | EUROPE   |              166.81 |             53.99 |         57.06 |         59.71 |          50.92 |        39.37 |           30.94 |             65.3  |             25.83 |         2.33 |             76.08 | swing              |               -4.08 |                   nan |                  nan |
|      8 | MAU.PA   | Etablissements Maurel & Prom S.A.                      | EUROPE   |                1.6  |             51.36 |         47.54 |         37.37 |          55.17 |        61.1  |           58.7  |             52.5  |             72.01 |         5.34 |             76.31 | long               |               -4.93 |                   nan |                  nan |
|      9 | AF.PA    | Air France-KLM SA                                      | EUROPE   |                3.22 |             50.44 |         37.83 |         50.71 |          50.18 |        53.65 |           39.08 |             56.92 |             72.15 |         6.98 |             81.92 | long               |               -2.34 |                   nan |                  nan |
|     10 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |             50.13 |         53.51 |         40.26 |          46.74 |        56.5  |           70.78 |             56.84 |             53.1  |         4.61 |             73.84 | long               |                0.13 |                   nan |                  nan |
|     11 | MC.PA    | LVMH Moët Hennessy - Louis Vuitton, Société Européenne | EUROPE   |              228.64 |             42.09 |         32.19 |         36.74 |          47.44 |        52.42 |           71.8  |             57.51 |             34.38 |         4.62 |             85.79 | long               |               -1.4  |                   nan |                  nan |
|     12 | LKFT.AS  | LAKEFRONT BIOTHERAPEUTICS                              | EUROPE   |                1.6  |             40.63 |         41.87 |         32.82 |          39.38 |        49.57 |           33.9  |             45.14 |             88.89 |         3.97 |             68.34 | long               |              nan    |                   nan |                  nan |
|     13 | LEG.DE   | LEG Immobilien SE                                      | EUROPE   |                4.03 |             37.79 |         38.26 |         31.3  |          37.32 |        44.82 |           56.75 |             41.98 |             42.41 |         5.01 |             74.58 | long               |               -0.25 |                   nan |                  nan |
|     14 | IF.MI    | Banca IFIS S.p.A.                                      | EUROPE   |                0.94 |             35.02 |         41.64 |         26.47 |          31.27 |        38.76 |           26.8  |             41.03 |             63.29 |         7.08 |             74.26 | short              |               -3.61 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | SAP.DE   | SAP SE                                                 | EUROPE   |              203.97 |                  73.38 |                    70.8  |                 69.15 |              70.09 |                67.77 |                   32.23 |           73.48 |             50.61 |       0.045 |         nan |       nan |       17.17 |        21.12 |         26.42 |        1.76 |                 nan |              nan |                  12 |                  0.63 |
|            2 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  60.73 |                    62.28 |                 64.11 |              62.09 |                70.43 |                   29.57 |           70.78 |             56.84 |       0.965 |         nan |       nan |        5.3  |      -121.93 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            3 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              174.49 |                  48.42 |                    58.91 |                 59.89 |              54.58 |                72.36 |                   27.64 |           68.84 |             66.87 |       0.031 |         nan |       nan |       22.47 |        25.72 |         36.56 |        1.88 |                 nan |              nan |                  12 |                  0.63 |
|            4 | AF.PA    | Air France-KLM SA                                      | EUROPE   |                3.22 |                  67.4  |                    57.35 |                 54.53 |              61.29 |                39.26 |                   60.74 |           39.08 |             56.92 |      -0.199 |         nan |       nan |        3.95 |         2.77 |          3.2  |        0.14 |                 nan |              nan |                  10 |                  0.53 |
|            5 | NOKIA.HE | Nokia Oyj                                              | EUROPE   |               52.54 |                  61.17 |                    56.65 |                 52.83 |              58.71 |                56.52 |                   43.48 |           40.33 |             44.96 |       0.023 |         nan |       nan |       18.72 |        23.28 |         78.43 |        1.01 |                 nan |              nan |                  12 |                  0.63 |
|            6 | SIE.DE   | SIEMENS AG                    N                        | EUROPE   |              217.31 |                  52.39 |                    56.13 |                 55.45 |              55.67 |                66.63 |                   33.37 |           51.81 |             59.54 |       0.03  |         nan |       nan |       21.1  |        22.04 |         28.46 |        5.35 |                 nan |              nan |                  11 |                  0.58 |
|            7 | MAU.PA   | Etablissements Maurel & Prom S.A.                      | EUROPE   |                1.6  |                  56.46 |                    55.06 |                 55.54 |              55    |                50.56 |                   49.44 |           58.7  |             52.5  |     nan     |         nan |       nan |        4.52 |         7.91 |          3.81 |        0.82 |                 nan |              nan |                  11 |                  0.58 |
|            8 | LKFT.AS  | LAKEFRONT BIOTHERAPEUTICS                              | EUROPE   |                1.6  |                  65.57 |                    54.31 |                 51.27 |              59.54 |                43.43 |                   56.57 |           33.9  |             45.14 |     nan     |         nan |       nan |       -2.08 |        -6.23 |          2.7  |      nan    |                 nan |              nan |                   6 |                  0.32 |
|            9 | ASML.AS  | ASML Holding N.V.                                      | EUROPE   |              618.55 |                  33.69 |                    54.18 |                 58.84 |              44.73 |                71.71 |                   28.29 |           86.3  |             75.61 |       0.014 |         nan |       nan |       44.21 |        31.32 |         63.18 |        2.11 |                 nan |              nan |                  12 |                  0.63 |
|           10 | MC.PA    | LVMH Moët Hennessy - Louis Vuitton, Société Européenne | EUROPE   |              228.64 |                  41.94 |                    53.26 |                 55    |              47.41 |                63.65 |                   36.35 |           71.8  |             57.51 |       0.05  |         nan |       nan |       12.76 |        18.15 |         21.15 |        1.81 |                 nan |              nan |                  12 |                  0.63 |
|           11 | AIR.PA   | Airbus SE                                              | EUROPE   |              169.46 |                  46.95 |                    51.09 |                 51.45 |              47.14 |                44.61 |                   55.39 |           62.69 |             53.08 |       0.018 |         nan |       nan |       18.92 |        24.6  |         28.47 |        1.85 |                 nan |              nan |                  12 |                  0.63 |
|           12 | ALV.DE   | Allianz SE                    v                        | EUROPE   |              166.81 |                  50.29 |                    48.24 |                 46.59 |              50.45 |                42.86 |                   57.14 |           30.94 |             65.3  |       0.056 |         nan |       nan |        3.13 |        13.14 |         14.42 |        3.27 |                 nan |              nan |                  11 |                  0.58 |
|           13 | IF.MI    | Banca IFIS S.p.A.                                      | EUROPE   |                0.94 |                  58.26 |                    47.75 |                 43.93 |              51.88 |                32.38 |                   67.62 |           26.8  |             41.03 |     nan     |         nan |       nan |      nan    |         7.45 |          3.65 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           14 | LEG.DE   | LEG Immobilien SE                                      | EUROPE   |                4.03 |                  39.03 |                    45.16 |                 46.55 |              42.51 |                56.73 |                   43.27 |           56.75 |             41.98 |       0.082 |         nan |       nan |       21.04 |         8.94 |          3.49 |      nan    |                 nan |              nan |                  11 |                  0.58 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | SAP.DE   | SAP SE                                                 | EUROPE   |              203.97 |                  73.38 |                    70.8  |                 69.15 |              70.09 |                67.77 |                   32.23 |           73.48 |             50.61 |       0.045 |         nan |       nan |       17.17 |        21.12 |         26.42 |        1.76 |                 nan |              nan |                  12 |                  0.63 |
|            2 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  60.73 |                    62.28 |                 64.11 |              62.09 |                70.43 |                   29.57 |           70.78 |             56.84 |       0.965 |         nan |       nan |        5.3  |      -121.93 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            3 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              174.49 |                  48.42 |                    58.91 |                 59.89 |              54.58 |                72.36 |                   27.64 |           68.84 |             66.87 |       0.031 |         nan |       nan |       22.47 |        25.72 |         36.56 |        1.88 |                 nan |              nan |                  12 |                  0.63 |
|            9 | ASML.AS  | ASML Holding N.V.                                      | EUROPE   |              618.55 |                  33.69 |                    54.18 |                 58.84 |              44.73 |                71.71 |                   28.29 |           86.3  |             75.61 |       0.014 |         nan |       nan |       44.21 |        31.32 |         63.18 |        2.11 |                 nan |              nan |                  12 |                  0.63 |
|            7 | MAU.PA   | Etablissements Maurel & Prom S.A.                      | EUROPE   |                1.6  |                  56.46 |                    55.06 |                 55.54 |              55    |                50.56 |                   49.44 |           58.7  |             52.5  |     nan     |         nan |       nan |        4.52 |         7.91 |          3.81 |        0.82 |                 nan |              nan |                  11 |                  0.58 |
|            6 | SIE.DE   | SIEMENS AG                    N                        | EUROPE   |              217.31 |                  52.39 |                    56.13 |                 55.45 |              55.67 |                66.63 |                   33.37 |           51.81 |             59.54 |       0.03  |         nan |       nan |       21.1  |        22.04 |         28.46 |        5.35 |                 nan |              nan |                  11 |                  0.58 |
|           10 | MC.PA    | LVMH Moët Hennessy - Louis Vuitton, Société Européenne | EUROPE   |              228.64 |                  41.94 |                    53.26 |                 55    |              47.41 |                63.65 |                   36.35 |           71.8  |             57.51 |       0.05  |         nan |       nan |       12.76 |        18.15 |         21.15 |        1.81 |                 nan |              nan |                  12 |                  0.63 |
|            4 | AF.PA    | Air France-KLM SA                                      | EUROPE   |                3.22 |                  67.4  |                    57.35 |                 54.53 |              61.29 |                39.26 |                   60.74 |           39.08 |             56.92 |      -0.199 |         nan |       nan |        3.95 |         2.77 |          3.2  |        0.14 |                 nan |              nan |                  10 |                  0.53 |
|            5 | NOKIA.HE | Nokia Oyj                                              | EUROPE   |               52.54 |                  61.17 |                    56.65 |                 52.83 |              58.71 |                56.52 |                   43.48 |           40.33 |             44.96 |       0.023 |         nan |       nan |       18.72 |        23.28 |         78.43 |        1.01 |                 nan |              nan |                  12 |                  0.63 |
|           11 | AIR.PA   | Airbus SE                                              | EUROPE   |              169.46 |                  46.95 |                    51.09 |                 51.45 |              47.14 |                44.61 |                   55.39 |           62.69 |             53.08 |       0.018 |         nan |       nan |       18.92 |        24.6  |         28.47 |        1.85 |                 nan |              nan |                  12 |                  0.63 |
|            8 | LKFT.AS  | LAKEFRONT BIOTHERAPEUTICS                              | EUROPE   |                1.6  |                  65.57 |                    54.31 |                 51.27 |              59.54 |                43.43 |                   56.57 |           33.9  |             45.14 |     nan     |         nan |       nan |       -2.08 |        -6.23 |          2.7  |      nan    |                 nan |              nan |                   6 |                  0.32 |
|           12 | ALV.DE   | Allianz SE                    v                        | EUROPE   |              166.81 |                  50.29 |                    48.24 |                 46.59 |              50.45 |                42.86 |                   57.14 |           30.94 |             65.3  |       0.056 |         nan |       nan |        3.13 |        13.14 |         14.42 |        3.27 |                 nan |              nan |                  11 |                  0.58 |
|           14 | LEG.DE   | LEG Immobilien SE                                      | EUROPE   |                4.03 |                  39.03 |                    45.16 |                 46.55 |              42.51 |                56.73 |                   43.27 |           56.75 |             41.98 |       0.082 |         nan |       nan |       21.04 |         8.94 |          3.49 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|           13 | IF.MI    | Banca IFIS S.p.A.                                      | EUROPE   |                0.94 |                  58.26 |                    47.75 |                 43.93 |              51.88 |                32.38 |                   67.62 |           26.8  |             41.03 |     nan     |         nan |       nan |      nan    |         7.45 |          3.65 |      nan    |                 nan |              nan |                   8 |                  0.42 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AF.PA    | Air France-KLM SA                                      | EUROPE   |                3.22 |                     0.06 |    -0.05 |     -0.04 |                  80.7  |                        53.81 |         37.83 |         50.71 |          50.18 |        53.65 |           39.08 |             56.92 |         6.98 |
|               2 | MC.PA    | LVMH Moët Hennessy - Louis Vuitton, Société Européenne | EUROPE   |              228.64 |                     0.06 |    -0.04 |     -0.08 |                  76.31 |                        52.8  |         32.19 |         36.74 |          47.44 |        52.42 |           71.8  |             57.51 |         4.62 |
|               3 | MAU.PA   | Etablissements Maurel & Prom S.A.                      | EUROPE   |                1.6  |                     0.07 |     0.01 |      0.02 |                  59.75 |                        52.35 |         47.54 |         37.37 |          55.17 |        61.1  |           58.7  |             52.5  |         5.34 |
|               4 | LEG.DE   | LEG Immobilien SE                                      | EUROPE   |                4.03 |                     0.02 |     0.01 |      0    |                  46.7  |                        43.78 |         38.26 |         31.3  |          37.32 |        44.82 |           56.75 |             41.98 |         5.01 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.94
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.94
- `risk_adj_mom_126d_rank` vs `dist_sma_200_rank`: r=0.89

High correlation does not automatically mean a factor is wrong. It warns that the model may be counting the same underlying information more than once.

## Hard filters

- Market cap >= €250,000,000
- Price >= €2.0
- Median 20-day turnover >= €1,000,000
- Price history >= 230 observations
- Data confidence >= 55/100
- Maximum weekday-only stale-price lag: 3 business days
- Global recent-pullback gate: **OFF** in v1.6; pullbacks have their own ranking.

## Value variables currently used when available

Forward/trailing P/E, earnings yields, EV/EBITDA, EV/EBIT, EBIT yield, EV/revenue, P/S, P/B, price/tangible-book, FCF yield, FCF/EV, CFO yield, PEG, forward-P/E-to-growth, shareholder/net-payout yield, dividend yield and net-cash yield. Value-trap protection separately uses ROIC/profitability/FCF quality, cash conversion, accruals, earnings stability, leverage, interest coverage, current/quick ratio, Altman-style Z score, revisions, dilution/SBC and risk.

## Important limitations

The discovery layer can consider ~2,000 names, but free public endpoints make full deep enrichment of every one of them unreliable/slow; the expensive factor model therefore runs on a diversified shortlist. A name outside that shortlist can be reconsidered on a later run as its price/value screen changes.

Historical self-valuation percentiles and a genuinely point-in-time historical DCF are **not** fabricated from today's revised fundamentals. Financials/insurers/REITs remain `lite` until sector-specific CET1/NIM/credit, solvency/combined-ratio, or FFO/AFFO/NAV metrics are available.


## Eligibility diagnostics

- Deep analyzed: **1000**
- Excluded by hard/data filters: **986**
- Event watch (otherwise eligible): **0**
- Final eligible: **14**
- Eligible change vs previous stored run: **-90**

Top exclusion categories:
- market_cap: 980
- liquidity: 325
- price: 279
- data_confidence: 59
- price_history: 23
- asset_type: 1
- delisted: 1
- duplicate_listing: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MAU.PA | 8 | 7 | 3 | 5 | 3 | main,value,pullback,quality_value |
| AF.PA | 9 | 4 | 1 | 8 | 3 | main,value,pullback,quality_value |
| ASML.AS | 1 | 9 |  | 4 | 2 | main,value,quality_value |
| SU.PA | 2 | 3 |  | 3 | 2 | main,value,quality_value |
| SAP.DE | 3 | 1 |  | 1 | 2 | main,value,quality_value |
| SIE.DE | 5 | 6 |  | 6 | 2 | main,value,quality_value |
| NOKIA.HE | 6 | 5 |  | 9 | 2 | main,value,quality_value |
| NWL.MI | 10 | 2 |  | 2 | 2 | main,value,quality_value |
| MC.PA | 11 | 10 | 2 | 7 | 2 | value,pullback,quality_value |
| AIR.PA | 4 | 11 |  | 10 | 1 | main,quality_value |
| ALV.DE | 7 | 12 |  | 12 | 1 | main |
| LKFT.AS | 12 | 8 |  | 11 | 1 | value |
| LEG.DE | 13 | 14 | 4 | 13 | 1 | pullback |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **0** (none)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | AF.PA | value+pullback | 59.80 | 67.40 | 80.70 | 39.08 | 56.92 | 39.26 | 50.44 |
| 2 | MAU.PA | value+pullback | 56.04 | 56.46 | 59.75 | 58.70 | 52.50 | 50.56 | 51.36 |
| 3 | SAP.DE | value | 51.65 | 73.38 | 43.42 | 73.48 | 50.61 | 67.77 | 63.72 |
| 4 | NWL.MI | value | 48.61 | 60.73 | 30.95 | 70.78 | 56.84 | 70.43 | 50.13 |
| 5 | MC.PA | pullback | 48.33 | 41.94 | 76.31 | 71.80 | 57.51 | 63.65 | 42.09 |
| 6 | NOKIA.HE | value | 40.20 | 61.17 | 30.95 | 40.33 | 44.96 | 56.52 | 54.10 |
| 7 | LKFT.AS | value | 37.96 | 65.57 | 60.00 | 33.90 | 45.14 | 43.43 | 40.63 |
| 8 | LEG.DE | pullback | 35.73 | 39.03 | 46.70 | 56.75 | 41.98 | 56.73 | 37.79 |
| 9 | IF.MI | value | 32.08 | 58.26 | 30.95 | 26.80 | 41.03 | 32.38 | 35.02 |
