# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-26

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

- **EUROPE:** 77.8/100
- **OTHER:** 81.5/100
- **US:** 82.0/100

## Main multi-horizon ranking

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.88 |             80.68 |         73.27 |         79.86 |          83.14 |        81.51 |           96.42 |             77.73 |             63.59 |         3.66 |             73.14 | medium             |               -3.5  |                  0.9  |                 0.93 |
|      2 | HPE      | HPE      | US       |               73.45 |             80.16 |         86.39 |         82.54 |          77.77 |        67.72 |           71.95 |             82.84 |             44.48 |         6.91 |             72.34 | short              |               -1.2  |                  0.07 |               nan    |
|      3 | DELL     | DELL     | US       |              314.64 |             79.82 |         83.07 |         82.06 |          77.58 |        64.55 |           71.54 |             87.64 |             30.24 |         7.82 |             72.23 | short              |               -3.8  |                 -0.48 |                -0.52 |
|      4 | MU       | MU       | US       |             1074.59 |             78.77 |         77.24 |         68.7  |          82.08 |        80.29 |           94.75 |             82.85 |             63.45 |         8.1  |             73.14 | medium             |               -2    |                  1.97 |                 1.53 |
|      5 | VLO      | VLO      | US       |               98.01 |             78.41 |         76.41 |         81.37 |          80.41 |        75.03 |           85.07 |             82.58 |             52.84 |         3.57 |             69.68 | swing              |               -7.34 |                  0.22 |                 0.34 |
|      6 | AMC      | AMC      | US       |                2.31 |             77.22 |         78.45 |         81.28 |          76    |        74.35 |           83.29 |             78.94 |            nan    |         9.48 |             65.07 | swing              |                1.03 |                  3.67 |                 3.53 |
|      7 | FRO      | FRO      | US       |                9.34 |             77.18 |         76.66 |         77.69 |          78.23 |        75.18 |           90.68 |             68.43 |             52.85 |         5.03 |             73.14 | medium             |               -7.74 |                 -0.44 |                -0.25 |
|      8 | REP.MC   | REP.MC   | EUROPE   |               32.76 |             76.44 |         82.15 |         78.94 |          73.95 |        70.22 |           61.31 |             84.05 |             70.73 |         3.81 |             73.14 | short              |                1.79 |                  1.45 |                 1.17 |
|      9 | SMTC     | SMTC     | US       |               14.96 |             76.03 |         81.91 |         78.38 |          73.68 |        59.51 |           73.38 |             85.72 |             12.24 |         8.45 |             73.14 | short              |                5.19 |                  0.17 |               nan    |
|     10 | SHELL.AS | SHELL.AS | EUROPE   |              239.93 |             75.82 |         79.72 |         73.33 |          72.25 |        78.31 |           93.65 |             80.92 |             64.68 |         2.45 |             73.14 | short              |                1.67 |                  2.35 |                 2.29 |
|     11 | KIN.BR   | KIN.BR   | EUROPE   |                1.35 |             75.57 |         78.2  |         78.12 |          73.02 |        64.16 |           89.87 |             65.11 |             19.12 |         3.69 |             73.14 | short              |               -2.18 |                 -0.62 |                -0.47 |
|     12 | PSX      | PSX      | US       |               90.15 |             75.54 |         72.16 |         80.11 |          78.18 |        72.9  |           78.36 |             87.38 |             53.79 |         3.81 |             73.14 | swing              |               -8.32 |                  0.1  |                 0.41 |
|     13 | NAT      | NAT      | US       |                1.44 |             75.38 |         76.9  |         75.89 |          74.87 |        68.87 |           86.86 |             69.19 |             34.7  |         4.61 |             73.14 | short              |               -5.18 |                 -0.54 |                -0.34 |
|     14 | BIRG.IR  | BIRG.IR  | EUROPE   |               18.96 |             74.93 |         76.63 |         72.71 |          73.97 |        75.9  |           97.14 |             67.84 |             57.15 |         2.18 |             73.14 | short              |               -0.8  |                  1.64 |                 1.42 |
|     15 | AMD      | AMD      | US       |              905.06 |             74.59 |         82.16 |         76.76 |          72.42 |        58.8  |           77.75 |             73.28 |              9.02 |         7.15 |             69.09 | short              |                2.47 |                  1.45 |                 0.44 |
|     16 | DHT      | DHT      | US       |                3.09 |             74.56 |         74.46 |         74.67 |          74.99 |        74.29 |           87.53 |             70.12 |             55.57 |         4.44 |             73.14 | medium             |               -7.5  |                 -0.37 |                -0.39 |
|     17 | ERO      | ERO      | US       |                3.47 |             74.44 |         68.37 |         73.76 |          76.24 |        75.12 |           82.26 |             70    |             66.12 |         7.74 |             73.14 | medium             |              nan    |                nan    |               nan    |
|     18 | OMV.VI   | OMV.VI   | EUROPE   |               23.35 |             73.32 |         74.3  |         76.32 |          72.35 |        69.67 |           64.56 |             85.73 |             66.73 |         1.95 |             72.34 | swing              |                2.11 |                  0.55 |                 0.19 |
|     19 | P        | P        | US       |               36.91 |             72.9  |         88.82 |         80.08 |          65.73 |        52.82 |           67.24 |             76.28 |             10.61 |         8.16 |             72.68 | short              |               -4.46 |                  1.66 |                 1.17 |
|     20 | OKTA     | OKTA     | US       |               30    |             72.85 |         82.38 |         76.64 |          69.06 |        54.44 |           65.3  |             70.03 |             12.21 |         7.85 |             72.11 | short              |               -5.68 |                 -0.18 |                 0.09 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              239.93 |                  60.45 |                    72.17 |                 75.93 |              67.42 |                87.82 |                   12.18 |           93.65 |             80.92 |         nan |         nan |       nan |         nan |         9.59 |         10.65 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |              111.47 |                  69.92 |                    70.63 |                 70.98 |              70.17 |                70.29 |                   29.71 |           72.84 |             71.74 |         nan |         nan |       nan |         nan |         4.61 |          4.68 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL     | US       |              240.17 |                  66.16 |                    70.31 |                 71.47 |              69.45 |                76.24 |                   23.76 |           72.51 |             80.92 |         nan |         nan |       nan |         nan |         9.25 |         10.58 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              176.64 |                  65.17 |                    69.78 |                 71    |              69.3  |                76.43 |                   23.57 |           69.13 |             86.21 |         nan |         nan |       nan |         nan |         8.7  |         11.46 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR  | EUROPE   |                4.88 |                  55.41 |                    69.03 |                 73.57 |              63.11 |                85.77 |                   14.23 |           96.42 |             77.73 |         nan |         nan |       nan |         nan |         9.23 |          6.47 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM       | US       |                7.09 |                  62.31 |                    69.02 |                 71.57 |              66.15 |                72.64 |                   27.36 |           81.3  |             82.09 |         nan |         nan |       nan |         nan |         4.25 |          6.01 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               18.96 |                  56    |                    68.46 |                 72.55 |              62.56 |                85.89 |                   14.11 |           97.14 |             67.84 |         nan |         nan |       nan |         nan |        10.96 |         14.9  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP       | US       |               99.96 |                  55.01 |                    67.85 |                 72.01 |              63.37 |                82.59 |                   17.41 |           86.08 |             89    |         nan |         nan |       nan |         nan |         8.98 |         21.12 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR   | EUROPE   |               15.57 |                  63.4  |                    67.84 |                 69.27 |              64.62 |                76.93 |                   23.07 |           86.05 |             51.26 |         nan |         nan |       nan |         nan |         8.67 |          7.66 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA      | US       |               15.15 |                  54.42 |                    66.56 |                 70.3  |              62.11 |                83.9  |                   16.1  |           85.94 |             78.3  |         nan |         nan |       nan |         nan |        12.8  |         20.87 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO      | US       |                9.34 |                  56.43 |                    66.38 |                 69.91 |              61.37 |                77.21 |                   22.79 |           90.68 |             68.43 |         nan |         nan |       nan |         nan |        10.43 |          7.16 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS    | EUROPE   |               20.79 |                  62.86 |                    66.23 |                 67.06 |              64.95 |                74.05 |                   25.95 |           72.52 |             63.59 |         nan |         nan |       nan |         nan |         9    |         11.79 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               24.5  |                  55.85 |                    66.13 |                 69.64 |              60.24 |                80.99 |                   19.01 |           96.71 |             54.5  |         nan |         nan |       nan |         nan |        11.79 |         12.06 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX      | CVX      | US       |              352.58 |                  60.61 |                    66.02 |                 67.5  |              65.4  |                73.2  |                   26.8  |           65.5  |             85.83 |         nan |         nan |       nan |         nan |        14.46 |         19.64 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT      | US       |                3.09 |                  56.08 |                    65.88 |                 69.24 |              61.31 |                77.33 |                   22.67 |           87.53 |             70.12 |         nan |         nan |       nan |         nan |        10.15 |          7.41 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | XOM      | XOM      | US       |              580.52 |                  58.8  |                    65.62 |                 67.61 |              64.12 |                74.61 |                   25.39 |           69.68 |             83.57 |         nan |         nan |       nan |         nan |        14.5  |         20.67 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR      | US       |              115.41 |                  69.3  |                    65.46 |                 64.64 |              64.8  |                59.85 |                   40.15 |           73.11 |             41.31 |         nan |         nan |       nan |         nan |         5.11 |          5.14 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY      | US       |              112.89 |                  62.28 |                    65.43 |                 66.46 |              63.38 |                71.21 |                   28.79 |           76.71 |             57.18 |         nan |         nan |       nan |         nan |         9.58 |         13.85 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN      | US       |               14.75 |                  54.76 |                    65.36 |                 68.72 |              61.4  |                79.4  |                   20.6  |           82.55 |             76.86 |         nan |         nan |       nan |         nan |        10.35 |         22.46 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS | EUROPE   |               14.81 |                  56.97 |                    65.33 |                 67.82 |              61.84 |                79.48 |                   20.52 |           81.99 |             65.12 |         nan |         nan |       nan |         nan |        11.31 |         14.3  |         nan |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              239.93 |                  60.45 |                    72.17 |                 75.93 |              67.42 |                87.82 |                   12.18 |           93.65 |             80.92 |         nan |         nan |       nan |         nan |         9.59 |         10.65 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR  | EUROPE   |                4.88 |                  55.41 |                    69.03 |                 73.57 |              63.11 |                85.77 |                   14.23 |           96.42 |             77.73 |         nan |         nan |       nan |         nan |         9.23 |          6.47 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               18.96 |                  56    |                    68.46 |                 72.55 |              62.56 |                85.89 |                   14.11 |           97.14 |             67.84 |         nan |         nan |       nan |         nan |        10.96 |         14.9  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP       | US       |               99.96 |                  55.01 |                    67.85 |                 72.01 |              63.37 |                82.59 |                   17.41 |           86.08 |             89    |         nan |         nan |       nan |         nan |         8.98 |         21.12 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM       | US       |                7.09 |                  62.31 |                    69.02 |                 71.57 |              66.15 |                72.64 |                   27.36 |           81.3  |             82.09 |         nan |         nan |       nan |         nan |         4.25 |          6.01 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL     | US       |              240.17 |                  66.16 |                    70.31 |                 71.47 |              69.45 |                76.24 |                   23.76 |           72.51 |             80.92 |         nan |         nan |       nan |         nan |         9.25 |         10.58 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              176.64 |                  65.17 |                    69.78 |                 71    |              69.3  |                76.43 |                   23.57 |           69.13 |             86.21 |         nan |         nan |       nan |         nan |         8.7  |         11.46 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |              111.47 |                  69.92 |                    70.63 |                 70.98 |              70.17 |                70.29 |                   29.71 |           72.84 |             71.74 |         nan |         nan |       nan |         nan |         4.61 |          4.68 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA      | US       |               15.15 |                  54.42 |                    66.56 |                 70.3  |              62.11 |                83.9  |                   16.1  |           85.94 |             78.3  |         nan |         nan |       nan |         nan |        12.8  |         20.87 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO      | US       |                9.34 |                  56.43 |                    66.38 |                 69.91 |              61.37 |                77.21 |                   22.79 |           90.68 |             68.43 |         nan |         nan |       nan |         nan |        10.43 |          7.16 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU       | US       |             1074.59 |                  48.85 |                    64.25 |                 69.76 |              57.46 |                77.77 |                   22.23 |           94.75 |             82.85 |         nan |         nan |       nan |         nan |         6.79 |         24.49 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               24.5  |                  55.85 |                    66.13 |                 69.64 |              60.24 |                80.99 |                   19.01 |           96.71 |             54.5  |         nan |         nan |       nan |         nan |        11.79 |         12.06 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR   | EUROPE   |               15.57 |                  63.4  |                    67.84 |                 69.27 |              64.62 |                76.93 |                   23.07 |           86.05 |             51.26 |         nan |         nan |       nan |         nan |         8.67 |          7.66 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT      | US       |                3.09 |                  56.08 |                    65.88 |                 69.24 |              61.31 |                77.33 |                   22.67 |           87.53 |             70.12 |         nan |         nan |       nan |         nan |        10.15 |          7.41 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN      | US       |               14.75 |                  54.76 |                    65.36 |                 68.72 |              61.4  |                79.4  |                   20.6  |           82.55 |             76.86 |         nan |         nan |       nan |         nan |        10.35 |         22.46 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR   | EUROPE   |                1.65 |                  51.47 |                    63.87 |                 68.08 |              57.12 |                81.18 |                   18.82 |           98.26 |             54.49 |         nan |         nan |       nan |         nan |        10.34 |         10.68 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO      | US       |               98.01 |                  48.81 |                    63.31 |                 67.9  |              58.13 |                81.84 |                   18.16 |           85.07 |             82.58 |         nan |         nan |       nan |         nan |        10.18 |         16.15 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS | EUROPE   |               14.81 |                  56.97 |                    65.33 |                 67.82 |              61.84 |                79.48 |                   20.52 |           81.99 |             65.12 |         nan |         nan |       nan |         nan |        11.31 |         14.3  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | XOM      | XOM      | US       |              580.52 |                  58.8  |                    65.62 |                 67.61 |              64.12 |                74.61 |                   25.39 |           69.68 |             83.57 |         nan |         nan |       nan |         nan |        14.5  |         20.67 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PSX      | PSX      | US       |               90.15 |                  51.05 |                    63.69 |                 67.6  |              59.81 |                79.55 |                   20.45 |           78.36 |             87.38 |         nan |         nan |       nan |         nan |        10.27 |         14.59 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO       | US       |               98.01 |                     0.06 |    -0.06 |      0.12 |                  84.21 |                        82.72 |         76.41 |         81.37 |          80.41 |        75.03 |           85.07 |             82.58 |         3.57 |
|               2 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.88 |                     0.07 |    -0.05 |      0.06 |                  75.94 |                        82.26 |         73.27 |         79.86 |          83.14 |        81.51 |           96.42 |             77.73 |         3.66 |
|               3 | PSX       | PSX       | US       |               90.15 |                     0.07 |    -0.06 |      0.07 |                  81.77 |                        81.1  |         72.16 |         80.11 |          78.18 |        72.9  |           78.36 |             87.38 |         3.81 |
|               4 | FRO       | FRO       | US       |                9.34 |                     0.07 |    -0.07 |      0.16 |                  81.39 |                        79.46 |         76.66 |         77.69 |          78.23 |        75.18 |           90.68 |             68.43 |         5.03 |
|               5 | DELL      | DELL      | US       |              314.64 |                     0.04 |    -0.01 |      0.19 |                  66.28 |                        78.93 |         83.07 |         82.06 |          77.58 |        64.55 |           71.54 |             87.64 |         7.82 |
|               6 | NAT       | NAT       | US       |                1.44 |                     0.06 |    -0.06 |      0.19 |                  83.85 |                        78.78 |         76.9  |         75.89 |          74.87 |        68.87 |           86.86 |             69.19 |         4.61 |
|               7 | DHT       | DHT       | US       |                3.09 |                     0.06 |    -0.06 |      0.13 |                  83.92 |                        77.95 |         74.46 |         74.67 |          74.99 |        74.29 |           87.53 |             70.12 |         4.44 |
|               8 | BP        | BP        | US       |               99.96 |                     0.06 |    -0.01 |      0.04 |                  70.65 |                        76.74 |         71.15 |         68.35 |          68.03 |        73.21 |           86.08 |             89    |         4.48 |
|               9 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.2  |                     0.04 |    -0.02 |      0.37 |                  68.63 |                        75.74 |         80.39 |         75.25 |          67.07 |        67.14 |           83.35 |             57.22 |         5.32 |
|              10 | C5H.IR    | C5H.IR    | EUROPE   |                1.65 |                     0.06 |     0.01 |      0.05 |                  66.53 |                        74.24 |         72.87 |         65.4  |          70.3  |        74.32 |           98.26 |             54.49 |         2.67 |
|              11 | NESTE.HE  | NESTE.HE  | EUROPE   |               26.13 |                     0.05 |    -0.02 |      0.09 |                  74.77 |                        74.21 |         74.49 |         70.92 |          67.77 |        60.73 |           62.78 |             87.97 |         4.95 |
|              12 | FORTUM.HE | FORTUM.HE | EUROPE   |               21.01 |                     0.05 |    -0.05 |      0.13 |                  83.13 |                        73.34 |         74.48 |         63    |          57.13 |        52.09 |           69.05 |             65.44 |         4.63 |
|              13 | PBR-A     | PBR-A     | US       |              111.47 |                     0.05 |    -0.02 |      0.12 |                  74.65 |                        73.14 |         73.22 |         70.05 |          68.54 |        75.54 |           72.84 |             71.74 |         4.55 |
|              14 | EQNR      | EQNR      | US       |               87.93 |                     0.08 |    -0.04 |      0.02 |                  69.28 |                        73.1  |         60.98 |         70.05 |          69.85 |        69.98 |           74.05 |             85.84 |         5.63 |
|              15 | ARGX.BR   | ARGX.BR   | EUROPE   |               52.56 |                     0.07 |    -0.03 |     -0.06 |                  68.06 |                        72.81 |         53.61 |         63.11 |          67.36 |        60.42 |           93.34 |             82.55 |         6.14 |
|              16 | DAR       | DAR       | US       |                8.5  |                     0.09 |    -0.06 |     -0    |                  64.43 |                        72.69 |         54.19 |         64.44 |          73.21 |        78.3  |           89.58 |             85.89 |         4.73 |
|              17 | PAA       | PAA       | US       |               15.15 |                     0.06 |    -0.04 |     -0.04 |                  75.96 |                        72.26 |         52.65 |         63.86 |          69.86 |        71.58 |           85.94 |             78.3  |         2.05 |
|              18 | SHEL      | SHEL      | US       |              240.17 |                     0.03 |     0.01 |      0.06 |                  52.79 |                        72.13 |         75.14 |         70.58 |          66.41 |        70.02 |           72.51 |             80.92 |         2.96 |
|              19 | OMV.VI    | OMV.VI    | EUROPE   |               23.35 |                     0.02 |    -0.01 |      0.07 |                  52.96 |                        71.87 |         74.3  |         76.32 |          72.35 |        69.67 |           64.56 |             85.73 |         1.95 |
|              20 | GTLB      | GTLB      | US       |                6.86 |                     0.07 |    -0.05 |      0.05 |                  76.83 |                        71.35 |         66.65 |         74.78 |          60.52 |        45.82 |           57.43 |             72.99 |         8.38 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    137 | GVR.IR   | GVR.IR | EUROPE   |                1.19 |             62.48 |         59.51 |         53.53 |          65.45 |        71.69 |           92.9  |             63.27 |             60.68 |         2.67 |             73.14 | long               |              nan    |                  3.97 |               nan    |
|    333 | ITRG     | ITRG   | US       |                0.49 |             53.35 |         45.48 |         53.14 |          53.55 |        59.85 |           55.78 |             62.03 |             77.71 |         8.18 |             68.32 | long               |               -2.45 |                  3.96 |                 4.43 |
|    327 | HUT      | HUT    | US       |               10.49 |             53.51 |         63.55 |         50.15 |          56.86 |        41.9  |           36.72 |             78.33 |             13.33 |         8.57 |             66.84 | short              |              nan    |                  3.96 |               nan    |
|      6 | AMC      | AMC    | US       |                2.31 |             77.22 |         78.45 |         81.28 |          76    |        74.35 |           83.29 |             78.94 |            nan    |         9.48 |             65.07 | swing              |                1.03 |                  3.67 |                 3.53 |
|    556 | ZH       | ZH     | US       |                0.28 |             42.15 |         69.67 |         50.9  |          33.41 |        24.36 |           17.34 |             25.79 |             24.62 |         7.29 |             73.14 | short              |                3.11 |                  3.66 |                 2.73 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    469 | TEVA     | TEVA    | US       |               40.18 |             47.87 |         62.75 |         52.54 |          43.21 |        35.85 |           17.56 |             25.06 |             43.09 |         4.8  |             72.34 | short              |               -7.14 |                 -4.37 |                -4.27 |
|    491 | CNC      | CNC     | US       |               26.85 |             46.51 |         39.09 |         50.28 |          55.14 |        42.74 |           11.87 |             71.78 |             57.26 |         5.92 |             71.66 | medium             |              -12.71 |                 -4.16 |                -3.51 |
|    673 | PAH3.DE  | PAH3.DE | EUROPE   |                7.89 |             30.78 |         26.54 |         27.1  |          34.45 |        58.32 |          nan    |             23.38 |             96.29 |         5.16 |             70.3  | long               |              -14.57 |                 -4.14 |                -3.41 |
|    228 | HAFN     | HAFN    | US       |                4.2  |             57.57 |         63.65 |         56.91 |          55.08 |        58.22 |           71.18 |             13.42 |             52.49 |         5.63 |             69.68 | short              |               -8.4  |                 -3.84 |                -4.43 |
|    651 | 0JHU.IL  | 0JHU.IL | OTHER    |                8.25 |             34.07 |         21.22 |         28.43 |          39.72 |        71.09 |          nan    |            nan    |            100    |         5.18 |             60    | long               |               -3.53 |                 -3.73 |                -3.7  |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `sector_score`: r=1.00
- `relative_63d_rank` vs `sector_score`: r=0.99
- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.85

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
- Excluded by hard/data filters: **295**
- Event watch (otherwise eligible): **0**
- Final eligible: **705**
- Eligible change vs previous stored run: **-4**

Top exclusion categories:
- liquidity: 236
- price: 188
- market_cap: 165
- price_history: 20
- data_confidence: 14
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| CMBT.BR | 1 |  | 2 |  | 2 | main,pullback |
| DELL | 3 |  | 5 |  | 2 | main,pullback |
| VLO | 5 |  | 1 |  | 2 | main,pullback |
| FRO | 7 |  | 4 |  | 2 | main,pullback |
| MSFT | 121 | 1 |  | 1 | 1 | value,quality_value |
| NOVO-B.CO | 643 | 2 |  | 2 | 1 | value,quality_value |
| HPE | 2 |  |  |  | 1 | main |
| MU | 4 |  |  |  | 1 | main |
| AMC | 6 |  |  |  | 1 | main |
| REP.MC | 8 |  |  |  | 1 | main |
| SMTC | 9 |  |  |  | 1 | main |
| SHELL.AS | 10 |  |  |  | 1 | main |
| PSX | 12 |  | 3 |  | 1 | pullback |
| NAT | 13 |  | 6 |  | 1 | pullback |
| DHT | 16 |  | 7 |  | 1 | pullback |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **5** (MU, AMC, REP.MC, SMTC, SHELL.AS)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | VLO | pullback | 58.44 | 48.81 | 84.21 | 85.07 | 82.58 | 81.84 | 78.41 |
| 2 | CMBT.BR | pullback | 58.37 | 55.41 | 75.94 | 96.42 | 77.73 | 85.77 | 80.68 |
| 3 | PSX | pullback | 56.84 | 51.05 | 81.77 | 78.36 | 87.38 | 79.55 | 75.54 |
| 4 | DHT | pullback | 56.59 | 56.08 | 83.92 | 87.53 | 70.12 | 77.33 | 74.56 |
| 5 | PAA | pullback | 56.49 | 54.42 | 75.96 | 85.94 | 78.30 | 83.90 | 66.86 |
| 6 | FRO | pullback | 56.23 | 56.43 | 81.39 | 90.68 | 68.43 | 77.21 | 77.18 |
| 7 | NAT | pullback | 56.18 | 49.86 | 83.85 | 86.86 | 69.19 | 76.37 | 75.38 |
| 8 | BP | pullback | 55.99 | 55.01 | 70.65 | 86.08 | 89.00 | 82.59 | 69.75 |
| 9 | ARGX.BR | pullback | 55.44 | 35.63 | 68.06 | 93.34 | 82.55 | 80.85 | 61.76 |
| 10 | DAR | pullback | 54.71 | 52.95 | 64.43 | 89.58 | 85.89 | 82.87 | 68.83 |
| 11 | NETC.CO | pullback | 54.03 | 41.47 | 76.30 | 83.59 | 74.09 | 75.03 | 54.07 |
| 12 | C5H.IR | pullback | 53.06 | 51.47 | 66.53 | 98.26 | 54.49 | 81.18 | 71.58 |
| 13 | BEN | pullback | 52.74 | 54.76 | 67.18 | 82.55 | 76.86 | 79.40 | 66.44 |
| 14 | XOM | pullback | 52.22 | 58.80 | 73.96 | 69.68 | 83.57 | 74.61 | 63.54 |
| 15 | BIT | pullback | 51.82 | 47.91 | 78.57 |  |  | 98.37 | 32.00 |
| 16 | EQNR | pullback | 51.67 | 55.32 | 69.28 | 74.05 | 85.84 | 73.28 | 69.92 |
| 17 | CVX | pullback | 51.56 | 60.61 | 74.06 | 65.50 | 85.83 | 73.20 | 63.66 |
| 18 | ARIS | pullback | 51.39 | 53.88 | 63.15 | 87.36 | 78.50 | 73.22 | 69.41 |
| 19 | EQNR.OL | pullback | 51.13 | 53.45 | 74.64 | 74.14 | 72.23 | 70.63 | 68.45 |
| 20 | PDT | pullback | 51.01 | 49.67 | 74.88 |  |  | 98.95 | 37.73 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 5 / 5 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 73.1 | 15 / 10 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 73.0 | 27 / 23 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=2, large_20_100b=3, mega_100b_plus=3
