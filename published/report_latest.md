# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-24

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

- **EUROPE:** 78.5/100
- **OTHER:** 83.0/100
- **US:** 80.3/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.93 |             80.94 |         75.77 |         80.45 |          83.18 |        81.42 |           96.65 |             77.9  |             62.81 |         3.74 |             73.14 | medium             |               -3.25 |                  0.95 |                 0.97 |
|      2 | MPC       | MPC       | US       |               95.27 |             80.75 |         74.09 |         82.85 |          83.31 |        78.65 |           84.52 |             90.45 |             63.3  |         4.37 |             73.14 | medium             |               -6.4  |                nan    |               nan    |
|      3 | MU        | MU        | US       |             1057.46 |             79.24 |         77.43 |         70.13 |          82.7  |        81.04 |           95.11 |             83.06 |             64.68 |         8.25 |             73.14 | medium             |               -1.53 |                  2.06 |                 1.61 |
|      4 | HPE       | HPE       | US       |               72.28 |             78.92 |         87.48 |         80.61 |          77.22 |        67.56 |           73.24 |             82.31 |             43.44 |         7    |             72.34 | short              |               -2.44 |                 -0.18 |               nan    |
|      5 | DELL      | DELL      | US       |              305.37 |             78.1  |         81.05 |         79.18 |          77.01 |        64.31 |           72.17 |             87.55 |             29.57 |         7.84 |             72.23 | short              |               -5.52 |                 -0.83 |                -0.77 |
|      6 | FRO       | FRO       | US       |                9.25 |             77.84 |         78.69 |         76.98 |          79.57 |        76.34 |           91.33 |             81.69 |             50.92 |         5.6  |             73.14 | medium             |               -7.08 |                 -0.31 |                -0.15 |
|      7 | VLO       | VLO       | US       |               94.53 |             77.79 |         73.09 |         80.08 |          80.58 |        75.49 |           85.68 |             82.28 |             53.73 |         3.68 |             69.68 | medium             |               -7.96 |                  0.1  |                 0.25 |
|      8 | REP.MC    | REP.MC    | EUROPE   |               33.59 |             76.95 |         81.08 |         79.87 |          74.03 |        69.46 |           62.11 |             80.93 |             68.11 |         3.81 |             73.14 | short              |                2.3  |                  1.55 |                 1.24 |
|      9 | PSX       | PSX       | US       |               89.83 |             76.95 |         75.57 |         80.09 |          78.33 |        72.81 |           79.45 |             86.74 |             51.87 |         3.87 |             73.14 | swing              |               -6.91 |                  0.38 |                 0.62 |
|     10 | SHELL.AS  | SHELL.AS  | EUROPE   |              240.89 |             76.84 |         81.59 |         74.79 |          73.7  |        78.89 |           94.18 |             83.26 |             64.2  |         2.47 |             73.14 | short              |                2.69 |                  2.56 |                 2.44 |
|     11 | AMC       | AMC       | US       |                2.24 |             76.19 |         76.96 |         80.5  |          75.42 |        73.76 |           82.99 |             78.6  |            nan    |         9.51 |             65.07 | swing              |               -0    |                  3.46 |                 3.37 |
|     12 | KIN.BR    | KIN.BR    | EUROPE   |                1.35 |             75.39 |         78.41 |         77.75 |          73.02 |        64.45 |           90.97 |             64.46 |             19.03 |         3.81 |             73.14 | short              |               -2.36 |                 -0.66 |                -0.5  |
|     13 | HSHP      | HSHP      | US       |                0.75 |             74.81 |         81.07 |         75.72 |          73.91 |        64.37 |           85.89 |            nan    |             22.59 |         4.84 |             62.84 | short              |               -7.99 |                nan    |               nan    |
|     14 | DHT       | DHT       | US       |                3    |             74.77 |         73.94 |         72.21 |          75.81 |        75.61 |           87.76 |             84.34 |             54.87 |         4.78 |             73.14 | medium             |               -7.29 |                 -0.32 |                -0.36 |
|     15 | OMV.VI    | OMV.VI    | EUROPE   |               23.48 |             74.74 |         76.18 |         77.75 |          73.31 |        69.79 |           65.49 |             85.57 |             65.74 |         1.79 |             72.34 | swing              |                3.53 |                  0.84 |                 0.4  |
|     16 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.38 |             74.68 |         60.25 |         70.71 |          78.65 |        81.42 |           73.65 |            nan    |             98.56 |         4.31 |             62.84 | long               |               -0.5  |                nan    |               nan    |
|     17 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.92 |             74.46 |         75.66 |         71.7  |          73.62 |        75.31 |           97    |             67.12 |             55.14 |         2.19 |             73.14 | short              |               -1.27 |                  1.55 |                 1.35 |
|     18 | PBR-A     | PBR-A     | US       |              114.95 |             74.11 |         81.65 |         72.83 |          69.36 |        75.4  |           73.34 |             70.57 |             84.34 |         4.55 |             69.89 | short              |               -0.41 |                  0.12 |                -0.1  |
|     19 | ABN.AS    | ABN.AS    | EUROPE   |               35.21 |             73.76 |         73.65 |         74.37 |          73.86 |        69.08 |           80.7  |             69.46 |             49.73 |         2.88 |             73.14 | swing              |               -2.3  |                  0.94 |                 1.03 |
|     20 | MT.AS     | MT.AS     | EUROPE   |               47.76 |             73.63 |         60.46 |         73.55 |          76.81 |        73.72 |           72.91 |             83.14 |             68.9  |         5.07 |             73.14 | medium             |                1.04 |                  3.03 |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              240.89 |                  61.41 |                    73.21 |                 76.99 |              68.52 |                88.78 |                   11.22 |           94.18 |             83.26 |         nan |         nan |       nan |         nan |         9.62 |         10.71 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP       | US       |              100.09 |                  60.5  |                    71.23 |                 74.78 |              67.35 |                82.91 |                   17.09 |           87.28 |             88.66 |         nan |         nan |       nan |         nan |         9.06 |         20.6  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |              114.95 |                  69.88 |                    70.54 |                 70.89 |              70    |                70.16 |                   29.84 |           73.34 |             70.57 |         nan |         nan |       nan |         nan |         4.78 |          4.78 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL     | US       |              237.78 |                  65.68 |                    70.28 |                 71.61 |              69.17 |                76.66 |                   23.34 |           73.72 |             80.84 |         nan |         nan |       nan |         nan |         9.21 |         10.48 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR  | EUROPE   |                4.93 |                  55.36 |                    69.06 |                 73.63 |              63.1  |                85.8  |                   14.2  |           96.65 |             77.9  |         nan |         nan |       nan |         nan |         9.39 |          6.59 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM       | US       |                7.13 |                  61.78 |                    68.78 |                 71.42 |              65.79 |                72.76 |                   27.24 |           81.56 |             82.13 |         nan |         nan |       nan |         nan |         4.3  |          6.01 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              178.25 |                  64.94 |                    68.43 |                 69.35 |              67.9  |                73.93 |                   26.07 |           69.14 |             78.32 |         nan |         nan |       nan |         nan |         9.11 |         11.59 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               18.92 |                  55.95 |                    68.28 |                 72.33 |              62.39 |                85.56 |                   14.44 |           97    |             67.12 |         nan |         nan |       nan |         nan |        10.93 |         14.86 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO      | US       |                9.25 |                  55.95 |                    68.15 |                 72.36 |              62.97 |                80.65 |                   19.35 |           91.33 |             81.69 |         nan |         nan |       nan |         nan |        10.39 |          7.18 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR   | EUROPE   |               15.36 |                  63.44 |                    68.12 |                 69.67 |              64.66 |                77.47 |                   22.53 |           87.76 |             50.4  |         nan |         nan |       nan |         nan |         8.57 |          7.57 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT      | US       |                3    |                  55.77 |                    67.87 |                 71.89 |              63.24 |                81.36 |                   18.64 |           87.76 |             84.34 |         nan |         nan |       nan |         nan |         9.92 |          7.29 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS    | EUROPE   |               20.47 |                  62.56 |                    66.29 |                 67.25 |              64.78 |                74.57 |                   25.43 |           73.8  |             63.13 |         nan |         nan |       nan |         nan |         8.85 |         11.61 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS | EUROPE   |               14.54 |                  57.71 |                    65.96 |                 68.43 |              62.39 |                79.89 |                   20.11 |           83.14 |             64.6  |         nan |         nan |       nan |         nan |        11.11 |         14.04 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY      | US       |              109.11 |                  62.48 |                    65.61 |                 66.66 |              63.48 |                71.21 |                   28.79 |           77.37 |             56.8  |         nan |         nan |       nan |         nan |         9.31 |         13.71 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               24.24 |                  55.08 |                    65.57 |                 69.14 |              59.53 |                80.73 |                   19.27 |           96.94 |             53.42 |         nan |         nan |       nan |         nan |        11.67 |         11.93 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR      | US       |              119    |                  69.02 |                    65.25 |                 64.45 |              64.47 |                59.76 |                   40.24 |           73.6  |             40.2  |         nan |         nan |       nan |         nan |         5.3  |          5.25 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ALL      | ALL      | US       |               49.84 |                  58.96 |                    65.05 |                 67.14 |              61.93 |                72.87 |                   27.13 |           80.52 |             63.63 |         nan |         nan |       nan |         nan |         8.13 |          4.6  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAGP     | PAGP     | US       |                5.43 |                  50.44 |                    65    |                 69.36 |              60.45 |                85.78 |                   14.22 |           83.04 |             86.91 |         nan |         nan |       nan |         nan |        12.94 |         76.26 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX      | CVX      | US       |              352.14 |                  60.14 |                    64.98 |                 66.37 |              63.96 |                71.56 |                   28.44 |           67.58 |             77.83 |         nan |         nan |       nan |         nan |        15.14 |         19.91 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC      | US       |               95.27 |                  50.19 |                    64.95 |                 69.66 |              60.03 |                82.5  |                   17.5  |           84.52 |             90.45 |         nan |         nan |       nan |         nan |         8.24 |         13.51 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              240.89 |                  61.41 |                    73.21 |                 76.99 |              68.52 |                88.78 |                   11.22 |           94.18 |             83.26 |         nan |         nan |       nan |         nan |         9.62 |         10.71 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP       | US       |              100.09 |                  60.5  |                    71.23 |                 74.78 |              67.35 |                82.91 |                   17.09 |           87.28 |             88.66 |         nan |         nan |       nan |         nan |         9.06 |         20.6  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR  | EUROPE   |                4.93 |                  55.36 |                    69.06 |                 73.63 |              63.1  |                85.8  |                   14.2  |           96.65 |             77.9  |         nan |         nan |       nan |         nan |         9.39 |          6.59 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO      | US       |                9.25 |                  55.95 |                    68.15 |                 72.36 |              62.97 |                80.65 |                   19.35 |           91.33 |             81.69 |         nan |         nan |       nan |         nan |        10.39 |          7.18 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               18.92 |                  55.95 |                    68.28 |                 72.33 |              62.39 |                85.56 |                   14.44 |           97    |             67.12 |         nan |         nan |       nan |         nan |        10.93 |         14.86 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT      | US       |                3    |                  55.77 |                    67.87 |                 71.89 |              63.24 |                81.36 |                   18.64 |           87.76 |             84.34 |         nan |         nan |       nan |         nan |         9.92 |          7.29 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL     | US       |              237.78 |                  65.68 |                    70.28 |                 71.61 |              69.17 |                76.66 |                   23.34 |           73.72 |             80.84 |         nan |         nan |       nan |         nan |         9.21 |         10.48 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM       | US       |                7.13 |                  61.78 |                    68.78 |                 71.42 |              65.79 |                72.76 |                   27.24 |           81.56 |             82.13 |         nan |         nan |       nan |         nan |         4.3  |          6.01 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |              114.95 |                  69.88 |                    70.54 |                 70.89 |              70    |                70.16 |                   29.84 |           73.34 |             70.57 |         nan |         nan |       nan |         nan |         4.78 |          4.78 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU       | US       |             1057.46 |                  49.3  |                    64.58 |                 70.08 |              57.79 |                77.73 |                   22.27 |           95.11 |             83.06 |         nan |         nan |       nan |         nan |         6.74 |         24.75 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR   | EUROPE   |               15.36 |                  63.44 |                    68.12 |                 69.67 |              64.66 |                77.47 |                   22.53 |           87.76 |             50.4  |         nan |         nan |       nan |         nan |         8.57 |          7.57 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC      | US       |               95.27 |                  50.19 |                    64.95 |                 69.66 |              60.03 |                82.5  |                   17.5  |           84.52 |             90.45 |         nan |         nan |       nan |         nan |         8.24 |         13.51 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAGP     | PAGP     | US       |                5.43 |                  50.44 |                    65    |                 69.36 |              60.45 |                85.78 |                   14.22 |           83.04 |             86.91 |         nan |         nan |       nan |         nan |        12.94 |         76.26 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              178.25 |                  64.94 |                    68.43 |                 69.35 |              67.9  |                73.93 |                   26.07 |           69.14 |             78.32 |         nan |         nan |       nan |         nan |         9.11 |         11.59 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               24.24 |                  55.08 |                    65.57 |                 69.14 |              59.53 |                80.73 |                   19.27 |           96.94 |             53.42 |         nan |         nan |       nan |         nan |        11.67 |         11.93 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO      | US       |               94.53 |                  50.06 |                    64.09 |                 68.56 |              59    |                81.84 |                   18.16 |           85.68 |             82.28 |         nan |         nan |       nan |         nan |         9.88 |         15.73 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS | EUROPE   |               14.54 |                  57.71 |                    65.96 |                 68.43 |              62.39 |                79.89 |                   20.11 |           83.14 |             64.6  |         nan |         nan |       nan |         nan |        11.11 |         14.04 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PSX      | PSX      | US       |               89.83 |                  51.54 |                    64.11 |                 68.03 |              60.14 |                79.77 |                   20.23 |           79.45 |             86.74 |         nan |         nan |       nan |         nan |        10.3  |         14.66 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR   | EUROPE   |                1.65 |                  51.81 |                    63.89 |                 68.01 |              57.19 |                80.78 |                   19.22 |           98.26 |             53.44 |         nan |         nan |       nan |         nan |        10.32 |         10.66 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN      | US       |               14.52 |                  54.19 |                    64.4  |                 67.68 |              60.29 |                78    |                   22    |           82.98 |             72.31 |         nan |         nan |       nan |         nan |        10.29 |         22.56 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.93 |                     0.06 |    -0.06 |      0.09 |                  85.67 |                        84.09 |         75.77 |         80.45 |          83.18 |        81.42 |           96.65 |             77.9  |         3.74 |
|               2 | MPC       | MPC       | US       |               95.27 |                     0.09 |    -0.06 |      0.09 |                  69.68 |                        82.35 |         74.09 |         82.85 |          83.31 |        78.65 |           84.52 |             90.45 |         4.37 |
|               3 | FRO       | FRO       | US       |                9.25 |                     0.08 |    -0.05 |      0.17 |                  74.2  |                        81    |         78.69 |         76.98 |          79.57 |        76.34 |           91.33 |             81.69 |         5.6  |
|               4 | PSX       | PSX       | US       |               89.83 |                     0.06 |    -0.03 |      0.08 |                  73.84 |                        80.02 |         75.57 |         80.09 |          78.33 |        72.81 |           79.45 |             86.74 |         3.87 |
|               5 | VLO       | VLO       | US       |               94.53 |                     0.09 |    -0.07 |      0.1  |                  68.65 |                        79.82 |         73.09 |         80.08 |          80.58 |        75.49 |           85.68 |             82.28 |         3.68 |
|               6 | DELL      | DELL      | US       |              305.37 |                     0.07 |    -0.02 |      0.22 |                  71.27 |                        78.78 |         81.05 |         79.18 |          77.01 |        64.31 |           72.17 |             87.55 |         7.84 |
|               7 | BP        | BP        | US       |              100.09 |                     0.05 |    -0.02 |      0.04 |                  75.07 |                        78.34 |         72.65 |         68.35 |          68.93 |        74.04 |           87.28 |             88.66 |         4.57 |
|               8 | DHT       | DHT       | US       |                3    |                     0.09 |    -0.08 |      0.11 |                  74.22 |                        78.31 |         73.94 |         72.21 |          75.81 |        75.61 |           87.76 |             84.34 |         4.78 |
|               9 | NAT       | NAT       | US       |                1.41 |                     0.08 |    -0.05 |      0.15 |                  71.11 |                        76.91 |         76.62 |         71.84 |          73.53 |        68.62 |           87.35 |             69.76 |         4.97 |
|              10 | SMTC      | SMTC      | US       |               13.8  |                     0.08 |     0.01 |      0.33 |                  49.35 |                        76.35 |         82.39 |         69.23 |          71.45 |        59.07 |           74.56 |             85.62 |         8.48 |
|              11 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.22 |                     0.03 |    -0.03 |      0.39 |                  67.72 |                        75.71 |         80.53 |         75.04 |          66.82 |        67.02 |           84.21 |             56.29 |         5.4  |
|              12 | MT.AS     | MT.AS     | EUROPE   |               47.76 |                     0.06 |    -0.03 |     -0.01 |                  76.65 |                        75.32 |         60.46 |         73.55 |          76.81 |        73.72 |           72.91 |             83.14 |         5.07 |
|              13 | PAGP      | PAGP      | US       |                5.43 |                     0.06 |    -0.04 |     -0.02 |                  76.61 |                        74.92 |         58.07 |         67.57 |          71.66 |        70.56 |           83.04 |             86.91 |         1.77 |
|              14 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.92 |                     0.02 |    -0.01 |      0.07 |                  50.67 |                        74.9  |         75.66 |         71.7  |          73.62 |        75.31 |           97    |             67.12 |         2.19 |
|              15 | EQNR      | EQNR      | US       |               88.83 |                     0.06 |    -0.03 |      0.04 |                  74.9  |                        74.77 |         67.62 |         71.58 |          70.41 |        69.57 |           74.79 |             85.25 |         5.72 |
|              16 | C5H.IR    | C5H.IR    | EUROPE   |                1.65 |                     0.06 |    -0.02 |      0.05 |                  73.04 |                        73.78 |         70.3  |         64.32 |          69.91 |        73.87 |           98.26 |             53.44 |         2.71 |
|              17 | FORTUM.HE | FORTUM.HE | EUROPE   |               21.32 |                     0.04 |    -0.03 |      0.17 |                  70.05 |                        73.08 |         77.8  |         64.5  |          57.58 |        52.16 |           69.52 |             65.12 |         4.66 |
|              18 | DAR       | DAR       | US       |                8.46 |                     0.09 |    -0.06 |     -0.02 |                  65.59 |                        73.03 |         52.26 |         64.04 |          73.79 |        78.46 |           90.31 |             87.39 |         4.77 |
|              19 | SHEL      | SHEL      | US       |              237.78 |                     0.04 |    -0    |      0.03 |                  59.82 |                        72.56 |         73.44 |         69.15 |          66.79 |        70.51 |           73.72 |             80.84 |         3.04 |
|              20 | PBR-A     | PBR-A     | US       |              114.95 |                     0.02 |     0.02 |      0.2  |                  42.76 |                        72.49 |         81.65 |         72.83 |          69.36 |        75.4  |           73.34 |             70.57 |         4.55 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     29 | AMS.SW   | AMS.SW | EUROPE   |                2.26 |             71.39 |         81.9  |         74.33 |          68.44 |        51.92 |           55.24 |             90.16 |             11.82 |         8.69 |             73.14 | short              |                0.32 |                  4.35 |               nan    |
|    124 | GVR.IR   | GVR.IR | EUROPE   |                1.19 |             62.91 |         60.2  |         53.59 |          65.63 |        71.8  |           93.63 |             62.36 |             59.52 |         2.72 |             73.14 | long               |              nan    |                  4.06 |               nan    |
|    371 | ITRG     | ITRG   | US       |                0.49 |             51.94 |         51.9  |         51.86 |          51.98 |        60.06 |           58.09 |             61.4  |             77.16 |         8.22 |             68.32 | long               |               -3.86 |                  3.68 |                 4.22 |
|     11 | AMC      | AMC    | US       |                2.24 |             76.19 |         76.96 |         80.5  |          75.42 |        73.76 |           82.99 |             78.6  |            nan    |         9.51 |             65.07 | swing              |               -0    |                  3.46 |                 3.37 |
|    240 | VZLA     | VZLA   | OTHER    |                1.25 |             57.13 |         65.4  |         59.64 |          54.63 |        52.01 |           76.14 |            nan    |             21.88 |         8.37 |             61.82 | short              |               -0.38 |                  3.3  |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    487 | TEVA     | TEVA    | US       |               39.74 |             47.03 |         62.33 |         50.92 |          43.14 |        35.64 |           17.92 |             24.74 |             42.79 |         4.82 |             72.34 | short              |               -7.98 |                 -4.54 |                -4.39 |
|    690 | PAH3.DE  | PAH3.DE | EUROPE   |                7.82 |             29.8  |         26.13 |         25.56 |          33.47 |        57.27 |          nan    |             23.29 |             94.37 |         5.25 |             70.3  | long               |              -15.55 |                 -4.34 |                -3.56 |
|    485 | CNC      | CNC     | US       |               26.79 |             47.04 |         40.38 |         51.66 |          55.34 |        42.42 |           11.97 |             70.74 |             55.37 |         5.98 |             71.66 | medium             |              -12.18 |                 -4.06 |                -3.43 |
|    437 | CMPS     | CMPS    | US       |                1.66 |             49.21 |         43.94 |         54.49 |          55.68 |        39.83 |           43.47 |             49.31 |              5.19 |         7.91 |             69.27 | medium             |              -16.45 |                 -3.72 |                -3.77 |
|    319 | UMC      | UMC     | US       |               54.07 |             53.74 |         71.39 |         50.53 |          56.96 |        48.25 |           62.48 |             35.76 |             18.56 |         7.85 |             72.68 | short              |               -5.31 |                 -3.66 |                -3.72 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `sector_score`: r=1.00
- `relative_63d_rank` vs `sector_score`: r=1.00
- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.87

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
- Excluded by hard/data filters: **287**
- Event watch (otherwise eligible): **0**
- Final eligible: **713**
- Eligible change vs previous stored run: **+4**

Top exclusion categories:
- liquidity: 237
- price: 183
- market_cap: 161
- price_history: 15
- data_confidence: 11
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| CMBT.BR | 1 |  | 1 |  | 2 | main,pullback |
| MPC | 2 |  | 2 |  | 2 | main,pullback |
| DELL | 5 |  | 6 |  | 2 | main,pullback |
| FRO | 6 |  | 3 |  | 2 | main,pullback |
| VLO | 7 |  | 5 |  | 2 | main,pullback |
| PSX | 9 |  | 4 |  | 2 | main,pullback |
| MSFT | 160 | 1 |  | 1 | 1 | value,quality_value |
| SU.PA | 349 | 3 |  | 3 | 1 | value,quality_value |
| NESN.SW | 556 | 2 | 202 | 2 | 1 | value,quality_value |
| MU | 3 |  |  |  | 1 | main |
| HPE | 4 |  |  |  | 1 | main |
| REP.MC | 8 |  |  |  | 1 | main |
| SHELL.AS | 10 |  |  |  | 1 | main |
| DHT | 14 |  | 8 |  | 1 | pullback |
| NAT | 22 |  | 9 |  | 1 | pullback |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **4** (MU, HPE, REP.MC, SHELL.AS)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (SMTC)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | CMBT.BR | pullback | 60.86 | 55.36 | 85.67 | 96.65 | 77.90 | 85.80 | 80.94 |
| 2 | PAGP | pullback | 57.45 | 50.44 | 76.61 | 83.04 | 86.91 | 85.78 | 69.07 |
| 3 | BP | pullback | 57.31 | 60.50 | 75.07 | 87.28 | 88.66 | 82.91 | 70.79 |
| 4 | FRO | pullback | 56.55 | 55.95 | 74.20 | 91.33 | 81.69 | 80.65 | 77.84 |
| 5 | DHT | pullback | 56.43 | 55.77 | 74.22 | 87.76 | 84.34 | 81.36 | 74.77 |
| 6 | MPC | pullback | 55.64 | 50.19 | 69.68 | 84.52 | 90.45 | 82.50 | 80.75 |
| 7 | DAR | pullback | 55.41 | 52.70 | 65.59 | 90.31 | 87.39 | 83.62 | 68.92 |
| 8 | PSX | pullback | 55.00 | 51.54 | 73.84 | 79.45 | 86.74 | 79.77 | 76.95 |
| 9 | ARGX.BR | pullback | 54.72 | 35.23 | 63.93 | 95.07 | 81.97 | 81.39 | 62.19 |
| 10 | VLO | pullback | 54.61 | 50.06 | 68.65 | 85.68 | 82.28 | 81.84 | 77.79 |
| 11 | C5H.IR | pullback | 54.50 | 51.81 | 73.04 | 98.26 | 53.44 | 80.78 | 70.11 |
| 12 | V | pullback | 53.72 | 41.56 | 76.19 | 93.76 | 50.35 | 77.89 | 56.29 |
| 13 | GVR.IR | pullback | 53.49 | 52.11 | 67.79 | 93.63 | 62.36 | 81.30 | 62.91 |
| 14 | RDDT | pullback | 53.30 | 43.30 | 75.63 | 86.29 | 75.27 | 69.62 | 49.66 |
| 15 | AMV0.DE | pullback | 53.28 | 59.22 | 77.48 | 93.31 | 55.47 | 71.82 | 61.90 |
| 16 | EQNR | pullback | 53.12 | 55.87 | 74.90 | 74.79 | 85.25 | 73.28 | 69.99 |
| 17 | NAT | pullback | 53.07 | 49.67 | 71.11 | 87.35 | 69.76 | 76.09 | 72.68 |
| 18 | MT.AS | pullback | 53.00 | 51.00 | 76.65 | 72.91 | 83.14 | 72.96 | 73.63 |
| 19 | AGS.BR | pullback | 52.82 | 63.44 | 76.49 | 87.76 | 50.40 | 77.47 | 62.83 |
| 20 | ASRNL.AS | pullback | 52.67 | 57.71 | 71.05 | 83.14 | 64.60 | 79.89 | 67.82 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 73.1 | 6 / 4 |
| Top 25 | 25/25 | 23/25 | 24/25 | 22/25 | 0/25 | 73.1 | 14 / 11 |
| Top 50 | 49/50 | 48/50 | 49/50 | 46/50 | 0/50 | 72.5 | 26 / 24 |

Top-10 market-cap mix: small_1_5b=1, mid_5_20b=1, large_20_100b=5, mega_100b_plus=3
