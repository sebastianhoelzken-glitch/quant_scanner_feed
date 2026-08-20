# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-20

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

- **EUROPE:** 88.4/100
- **OTHER:** 77.5/100
- **US:** 86.5/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HQL       | HQL       | US       |                0.6  |             79.37 |         79.97 |         83.42 |          78.78 |        73.74 |          nan    |            nan    |             67.96 |         1.94 |             55.57 | swing              |               12.16 |                  3.57 |                  nan |
|      2 | HALO      | HALO      | US       |               10.55 |             78.46 |         84.69 |         82.3  |          74.62 |        72.61 |           87.52 |             67.49 |             50.23 |         5.55 |             66.48 | short              |               -1.33 |                  0.63 |                  nan |
|      3 | TNK       | TNK       | US       |                2.72 |             77.79 |         80.33 |         75.79 |          76.77 |        78.8  |           82.28 |             72.96 |             74.39 |         5.85 |             76.09 | short              |                5.34 |                  1.84 |                  nan |
|      4 | BAX       | BAX       | US       |               11.89 |             77.16 |         80.19 |         82.35 |          74.12 |        70.82 |           76.88 |             99.01 |             51.17 |         5.92 |             66.02 | swing              |                0.78 |                  0.79 |                  nan |
|      5 | RMAX      | RMAX      | US       |                0.69 |             76.25 |         84.56 |         84.95 |          67.95 |        56.17 |           23.02 |             91.56 |             72.36 |         7.23 |             67.05 | swing              |              nan    |                 -2.07 |                  nan |
|      6 | TWST      | TWST      | US       |                7.71 |             75.8  |         86.43 |         82.59 |          69.01 |        49.55 |           48.03 |             76.43 |              6.73 |         6.99 |             64.66 | short              |              nan    |                 -1.03 |                  nan |
|      7 | U         | U         | US       |               17.9  |             75.67 |         84.66 |         86.11 |          66.68 |        49.57 |           46.23 |             99.01 |             18.2  |         8.32 |             67.5  | swing              |               -0.94 |                  0.16 |                  nan |
|      8 | PBF       | PBF       | US       |                7.57 |             75.59 |         79.03 |         78.48 |          72.71 |        67.76 |           51.41 |             55.21 |             81.1  |         7.04 |             67.05 | short              |               -3.29 |                 -3.42 |                  nan |
|      9 | BCRX      | BCRX      | US       |                2.22 |             75.47 |         61.26 |         73.51 |          78.55 |        77.43 |           86.54 |             94.91 |             63.92 |         5.84 |             66.59 | medium             |                0.88 |                  2.85 |                  nan |
|     10 | PSX       | PSX       | US       |               83.89 |             75    |         76.49 |         76    |          74    |        71.02 |           81.4  |             52.85 |             54.39 |         3.4  |             67.5  | short              |               -2.51 |                 -1.41 |                  nan |
|     11 | CRGY      | CRGY      | US       |                4.56 |             74.72 |         80.41 |         68.58 |          73.32 |        76.13 |           71.32 |             83    |             86.07 |         6.11 |             67.05 | short              |              nan    |                nan    |                  nan |
|     12 | HPE       | HPE       | US       |               60.76 |             74.66 |         60.8  |         78.67 |          78.86 |        70.65 |           74.45 |             72.46 |             49.59 |         6.81 |             65.68 | medium             |               -4.55 |                 -2.29 |                  nan |
|     13 | CCC       | CCC       | US       |                3.78 |             74.64 |         81.93 |         78.57 |          70.72 |        68.61 |           87.07 |             79.4  |             47.72 |         7.9  |             66.02 | short              |               -2.05 |                  1.3  |                  nan |
|     14 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.46 |             74.25 |         68.3  |         69.65 |          78.85 |        81.67 |           74.47 |            nan    |             98.39 |         3.34 |             62.84 | long               |               -1.97 |                 -1.85 |                  nan |
|     15 | AMCX      | AMCX      | US       |                0.43 |             74.13 |         80.82 |         79.24 |          69.01 |        62.24 |           22.78 |             88.71 |             92.5  |         6.73 |             67.05 | short              |                5.73 |                  0.93 |                  nan |
|     16 | GH        | GH        | US       |               18.93 |             73.98 |         65.75 |         77.26 |          76.18 |        71.79 |           64.01 |             67.62 |            nan    |         6.8  |             62.73 | swing              |              nan    |                 -2.04 |                  nan |
|     17 | PGEN      | PGEN      | US       |                2.21 |             73.98 |         87.84 |         80.99 |          66.97 |        51.26 |           66.99 |            nan    |              1.5  |         7.61 |             62.84 | short              |                1.47 |                  1.81 |                  nan |
|     18 | ZETA      | ZETA      | US       |                6.2  |             73.86 |         83.49 |         81.45 |          66.27 |        51.75 |           49.84 |             84.43 |             21.35 |         7.49 |             67.05 | short              |               -0.36 |                 -1.31 |                  nan |
|     19 | FLYW      | FLYW      | US       |                1.98 |             73.77 |         75.11 |         74.67 |          72.86 |        66.8  |           73.63 |             74.57 |             47.43 |         5.9  |             67.05 | short              |              nan    |                  0.36 |                  nan |
|     20 | AUTL      | AUTL      | US       |                0.58 |             73.11 |         87.24 |         78.04 |          65.94 |        68.19 |           57.36 |             54.34 |             91.68 |         7.84 |             63.64 | short              |                1.61 |                 -2.24 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                              | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:----------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                          | EUROPE   |              220.39 |                  68.06 |                    72.07 |                 73.65 |              68.23 |                78.43 |                   21.57 |           94.38 |             51.12 |      nan    |         nan |       nan |      nan    |         9.98 |         10.24 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|            1 | PBR-A    | PBR-A                             | US       |               98.5  |                  66.99 |                    69.44 |                 70.36 |              68.21 |                73.08 |                   26.92 |           74.81 |            nan    |      nan    |         nan |       nan |      nan    |         6.77 |          4.12 |         4.1 |                 nan |              nan |                   6 |                  0.32 |
|          nan | PAH3.DE  | PAH3.DE                           | EUROPE   |                8.49 |                  63.35 |                    68.76 |                 70.47 |              68.14 |                78.78 |                   21.22 |          nan    |             83.5  |      nan    |         nan |       nan |      nan    |         1.88 |         89.42 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE                            | EUROPE   |               38.02 |                  68.29 |                    66.51 |                 65.96 |              66.7  |                63.02 |                   36.98 |          nan    |             61.91 |      nan    |         nan |       nan |      nan    |         2.79 |          7.27 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|            2 | HRTG     | Heritage Insurance Holdings, Inc. | US       |                0.86 |                  74.72 |                    66.44 |                 65.31 |              69.26 |                52.65 |                   47.35 |           59.22 |             59.9  |        0.26 |         nan |       nan |        1.52 |         6.43 |          4.75 |       nan   |                 nan |              nan |                   9 |                  0.47 |
|          nan | JD       | JD                                | US       |               34.23 |                  61.18 |                    66.4  |                 68.17 |              65.77 |                74.8  |                   25.2  |          nan    |             82.51 |      nan    |         nan |       nan |      nan    |         6.96 |         19.31 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                           | EUROPE   |               17.53 |                  60.21 |                    66.4  |                 68.72 |              61.03 |                76.71 |                   23.29 |           97.26 |             38.71 |      nan    |         nan |       nan |      nan    |        10.17 |         13.77 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                           | EUROPE   |               37.52 |                  69.24 |                    66.28 |                 65.41 |              66.6  |                60.15 |                   39.85 |          nan    |             59.18 |      nan    |         nan |       nan |      nan    |         3.18 |          7.18 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                               | US       |              119.27 |                  63.55 |                    66.22 |                 67.17 |              63.94 |                71.38 |                   28.62 |           79.43 |             53.35 |      nan    |         nan |       nan |      nan    |        10.31 |         14.57 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                               | US       |               14.91 |                  57.41 |                    65.47 |                 68.18 |              61.31 |                76.71 |                   23.29 |           86.35 |             61.66 |      nan    |         nan |       nan |      nan    |        10.76 |         23.12 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                              | US       |              221.04 |                  67.26 |                    65.16 |                 64.67 |              63.96 |                64.73 |                   35.27 |           75.47 |             38.83 |      nan    |         nan |       nan |      nan    |        10.52 |         10.17 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|            3 | TNK      | TNK                               | US       |                2.72 |                  57.06 |                    64.37 |                 68.12 |              61.49 |                72.83 |                   27.17 |           82.28 |             72.96 |      nan    |         nan |       nan |      nan    |         8.33 |          5.35 |       nan   |                 nan |              nan |                   6 |                  0.32 |
|          nan | BSBR     | BSBR                              | US       |               36.02 |                  66.95 |                    64.26 |                 63.45 |              65.29 |                60.01 |                   39.99 |           59.56 |             62.9  |      nan    |         nan |       nan |      nan    |         6.44 |         16.38 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                               | US       |               15.45 |                  66.81 |                    63.95 |                 63.52 |              60.55 |                64.02 |                   35.98 |           89.91 |              9.18 |      nan    |         nan |       nan |      nan    |         7.63 |          5.65 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR                               | US       |              103.18 |                  69.71 |                    63.48 |                 61.96 |              62.59 |                56.5  |                   43.5  |           75.07 |             22.35 |      nan    |         nan |       nan |      nan    |         4.65 |          4.61 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                             | EUROPE   |               20.05 |                  62.84 |                    63.43 |                 63.54 |              61.84 |                68.55 |                   31.45 |           74.4  |             42.56 |      nan    |         nan |       nan |      nan    |         8.85 |         11.37 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS                            | EUROPE   |               11.87 |                  60.98 |                    63.41 |                 64.08 |              61.67 |                69.98 |                   30.02 |           73.55 |             51.74 |      nan    |         nan |       nan |      nan    |         8.83 |         13.38 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                                | US       |               62.98 |                  58.7  |                    63.37 |                 65    |              59.19 |                73.23 |                   26.77 |           87.91 |             37.47 |      nan    |         nan |       nan |      nan    |        12.1  |         14.51 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY                              | US       |                4.56 |                  55.5  |                    63.19 |                 65.76 |              60.87 |                70.06 |                   29.94 |           71.32 |             83    |      nan    |         nan |       nan |      nan    |         6.26 |        167.88 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBLK     | SBLK                              | US       |                2.91 |                  58.51 |                    63.07 |                 64.67 |              60.39 |                69.28 |                   30.72 |           77.02 |             57.94 |      nan    |         nan |       nan |      nan    |         8.48 |         11.83 |       nan   |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                              | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:----------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                          | EUROPE   |              220.39 |                  68.06 |                    72.07 |                 73.65 |              68.23 |                78.43 |                   21.57 |           94.38 |             51.12 |      nan    |         nan |       nan |      nan    |         9.98 |         10.24 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAH3.DE  | PAH3.DE                           | EUROPE   |                8.49 |                  63.35 |                    68.76 |                 70.47 |              68.14 |                78.78 |                   21.22 |          nan    |             83.5  |      nan    |         nan |       nan |      nan    |         1.88 |         89.42 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|            1 | PBR-A    | PBR-A                             | US       |               98.5  |                  66.99 |                    69.44 |                 70.36 |              68.21 |                73.08 |                   26.92 |           74.81 |            nan    |      nan    |         nan |       nan |      nan    |         6.77 |          4.12 |         4.1 |                 nan |              nan |                   6 |                  0.32 |
|          nan | BIRG.IR  | BIRG.IR                           | EUROPE   |               17.53 |                  60.21 |                    66.4  |                 68.72 |              61.03 |                76.71 |                   23.29 |           97.26 |             38.71 |      nan    |         nan |       nan |      nan    |        10.17 |         13.77 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                               | US       |               14.91 |                  57.41 |                    65.47 |                 68.18 |              61.31 |                76.71 |                   23.29 |           86.35 |             61.66 |      nan    |         nan |       nan |      nan    |        10.76 |         23.12 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | JD       | JD                                | US       |               34.23 |                  61.18 |                    66.4  |                 68.17 |              65.77 |                74.8  |                   25.2  |          nan    |             82.51 |      nan    |         nan |       nan |      nan    |         6.96 |         19.31 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|            3 | TNK      | TNK                               | US       |                2.72 |                  57.06 |                    64.37 |                 68.12 |              61.49 |                72.83 |                   27.17 |           82.28 |             72.96 |      nan    |         nan |       nan |      nan    |         8.33 |          5.35 |       nan   |                 nan |              nan |                   6 |                  0.32 |
|          nan | BMY      | BMY                               | US       |              119.27 |                  63.55 |                    66.22 |                 67.17 |              63.94 |                71.38 |                   28.62 |           79.43 |             53.35 |      nan    |         nan |       nan |      nan    |        10.31 |         14.57 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE                            | EUROPE   |               38.02 |                  68.29 |                    66.51 |                 65.96 |              66.7  |                63.02 |                   36.98 |          nan    |             61.91 |      nan    |         nan |       nan |      nan    |         2.79 |          7.27 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY                              | US       |                4.56 |                  55.5  |                    63.19 |                 65.76 |              60.87 |                70.06 |                   29.94 |           71.32 |             83    |      nan    |         nan |       nan |      nan    |         6.26 |        167.88 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | GL9.IR   | GL9.IR                            | EUROPE   |                5.38 |                  42.97 |                    60.04 |                 65.6  |              52.14 |                83.89 |                   16.11 |           98.12 |             61.04 |      nan    |         nan |       nan |      nan    |        15.27 |         26.5  |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                           | EUROPE   |               37.52 |                  69.24 |                    66.28 |                 65.41 |              66.6  |                60.15 |                   39.85 |          nan    |             59.18 |      nan    |         nan |       nan |      nan    |         3.18 |          7.18 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|            2 | HRTG     | Heritage Insurance Holdings, Inc. | US       |                0.86 |                  74.72 |                    66.44 |                 65.31 |              69.26 |                52.65 |                   47.35 |           59.22 |             59.9  |        0.26 |         nan |       nan |        1.52 |         6.43 |          4.75 |       nan   |                 nan |              nan |                   9 |                  0.47 |
|          nan | ET       | ET                                | US       |               62.98 |                  58.7  |                    63.37 |                 65    |              59.19 |                73.23 |                   26.77 |           87.91 |             37.47 |      nan    |         nan |       nan |      nan    |        12.1  |         14.51 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBLK     | SBLK                              | US       |                2.91 |                  58.51 |                    63.07 |                 64.67 |              60.39 |                69.28 |                   30.72 |           77.02 |             57.94 |      nan    |         nan |       nan |      nan    |         8.48 |         11.83 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                              | US       |              221.04 |                  67.26 |                    65.16 |                 64.67 |              63.96 |                64.73 |                   35.27 |           75.47 |             38.83 |      nan    |         nan |       nan |      nan    |        10.52 |         10.17 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                               | US       |                2.78 |                  58.54 |                    62.66 |                 64.45 |              58.23 |                67.99 |                   32.01 |           88.56 |             38.46 |      nan    |         nan |       nan |      nan    |        10.63 |          6.58 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS                            | EUROPE   |               11.87 |                  60.98 |                    63.41 |                 64.08 |              61.67 |                69.98 |                   30.02 |           73.55 |             51.74 |      nan    |         nan |       nan |      nan    |         8.83 |         13.38 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                | US       |                7.42 |                  62.28 |                    62.9  |                 63.8  |              59.84 |                60.38 |                   39.62 |           82.09 |             41.32 |      nan    |         nan |       nan |      nan    |         4.85 |          6.3  |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                             | EUROPE   |               20.05 |                  62.84 |                    63.43 |                 63.54 |              61.84 |                68.55 |                   31.45 |           74.4  |             42.56 |      nan    |         nan |       nan |      nan    |         8.85 |         11.37 |       nan   |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.89 |                     0.06 |    -0.01 |      0.22 |                  70.9  |                        82.04 |         80.19 |         82.35 |          74.12 |        70.82 |           76.88 |             99.01 |         5.92 |
|               2 | BCRX     | BCRX     | US       |                2.22 |                     0.05 |    -0.05 |      0.04 |                  81.5  |                        80.52 |         61.26 |         73.51 |          78.55 |        77.43 |           86.54 |             94.91 |         5.84 |
|               3 | GENI     | GENI     | US       |                1.86 |                     0.07 |     0.02 |      0.21 |                  55.24 |                        74.98 |         77.64 |         76.32 |          68.55 |        68.57 |           65.12 |             99.01 |         9.11 |
|               4 | NTAP     | NTAP     | US       |               32.96 |                     0.06 |    -0.04 |      0.16 |                  78.14 |                        74.95 |         66.91 |         75.52 |          73    |        65.78 |           87.64 |             52.98 |         6.26 |
|               5 | HPE      | HPE      | US       |               60.76 |                     0.11 |    -0.1  |      0.1  |                  63.73 |                        74.65 |         60.8  |         78.67 |          78.86 |        70.65 |           74.45 |             72.46 |         6.81 |
|               6 | SNOW     | SNOW     | US       |               97.28 |                     0.04 |    -0.02 |      0.21 |                  65.85 |                        74.49 |         72.98 |         82.79 |          67.61 |        47.3  |           44.33 |             95.66 |         8.81 |
|               7 | SMWB     | SMWB     | US       |                0.64 |                     0.07 |    -0.05 |      0.33 |                  74.13 |                        73.9  |         74.19 |         82.16 |          62.46 |        42.59 |           34.24 |             99.01 |         9.39 |
|               8 | SYENS.BR | SYENS.BR | EUROPE   |                8.22 |                     0.02 |    -0    |      0.16 |                  51.4  |                        72.99 |         75.1  |         69.37 |          61.72 |        57.98 |           71.27 |             89.83 |         5.06 |
|               9 | ZETA     | ZETA     | US       |                6.2  |                     0.03 |     0.01 |      0.43 |                  51.68 |                        72.13 |         83.49 |         81.45 |          66.27 |        51.75 |           49.84 |             84.43 |         7.49 |
|              10 | BFLY     | BFLY     | US       |                2.11 |                     0.05 |    -0.03 |      0.39 |                  79.25 |                        71.9  |         73.34 |         78.97 |          68.45 |        50    |           48.01 |             72.83 |         8.39 |
|              11 | WKC      | WKC      | US       |                1.61 |                     0.09 |    -0.01 |      0.01 |                  50.6  |                        71.67 |         58.94 |         76.35 |          75.19 |        64.54 |           55.26 |             99.01 |         3.15 |
|              12 | QNST     | QNST     | US       |                1.04 |                     0.04 |     0.01 |      0.35 |                  59.99 |                        71.65 |         81.32 |         73.85 |          66.58 |        67.33 |           85.67 |             32.38 |         7.81 |
|              13 | NWL      | NWL      | US       |                2.27 |                     0.03 |     0    |      0.14 |                  56.25 |                        71.55 |         74.56 |         82.17 |          68.99 |        61.98 |           37.63 |             96.65 |         8.04 |
|              14 | KRMN     | KRMN     | US       |                6.66 |                     0.06 |    -0.06 |      0.23 |                  82.92 |                        71.35 |         62.62 |         44.85 |          50.13 |        54.78 |           88.87 |             65.51 |         8.77 |
|              15 | JHX      | JHX      | US       |               15.14 |                     0.03 |    -0.02 |      0.22 |                  60.55 |                        70.97 |         76.31 |         76.68 |          63.37 |        57.02 |           58.93 |             78.41 |         6.77 |
|              16 | TGB      | TGB      | US       |                2.68 |                     0.04 |    -0.03 |      0.12 |                  70.04 |                        70.93 |         73.55 |         71.73 |          68.06 |        65.67 |           55.81 |             83.25 |         7.5  |
|              17 | GH       | GH       | US       |               18.93 |                     0.03 |    -0.01 |      0.07 |                  58.8  |                        70.4  |         65.75 |         77.26 |          76.18 |        71.79 |           64.01 |             67.62 |         6.8  |
|              18 | OKTA     | OKTA     | US       |               21.2  |                     0.09 |    -0.04 |      0.03 |                  62.05 |                        70.18 |         52.37 |         73.2  |          70.21 |        58.12 |           68.58 |             70.35 |         7.49 |
|              19 | KRX.IR   | KRX.IR   | EUROPE   |               18.34 |                     0.02 |    -0.02 |      0.33 |                  53.46 |                        70.12 |         74.64 |         66.06 |          60.87 |        60.74 |           98.12 |             34.37 |         5.18 |
|              20 | PANW     | PANW     | US       |              253.21 |                     0.09 |    -0.07 |      0.07 |                  68.77 |                        69.88 |         58.41 |         74.46 |          68.75 |        51.28 |           56.97 |             72.95 |         6.58 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |             44.02 |         39.01 |         40.72 |          47.32 |        53.16 |           58.77 |             43.28 |             56.28 |         4.17 |             75.81 | long               |               -4.45 |                 -1.15 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    453 | STLA     | STLA   | US       |               17.67 |             50.52 |         45.77 |         42.68 |          55.28 |        69.46 |           63.7  |             86.23 |             95.53 |         7.22 |             66.48 | long               |               21.29 |                  4.66 |                  nan |
|    615 | LI       | LI     | US       |               10.76 |             43.28 |         52.01 |         42.47 |          42.43 |        44.09 |           19.53 |             95.78 |             62.22 |         6.73 |             67.5  | short              |              nan    |                  4.07 |                  nan |
|    501 | TLRY     | TLRY   | US       |                0.57 |             48.52 |         71.1  |         46.38 |          45.6  |        50.66 |           38.39 |             89.95 |             62.43 |         8.08 |             67.5  | short              |               18.43 |                  3.85 |                  nan |
|      1 | HQL      | HQL    | US       |                0.6  |             79.37 |         79.97 |         83.42 |          78.78 |        73.74 |          nan    |            nan    |             67.96 |         1.94 |             55.57 | swing              |               12.16 |                  3.57 |                  nan |
|    366 | TEM      | TEM    | US       |                9.54 |             54.27 |         76.18 |         62.52 |          46.02 |        35.42 |           34.69 |             79.78 |              4.96 |         9.04 |             63.64 | short              |               12.18 |                  3.4  |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    540 | RBI.VI   | RBI.VI | EUROPE   |               19.72 |             47.09 |         48.73 |         51.42 |          45.44 |        39.31 |           11.88 |             10.67 |             68.56 |         3.81 |             66.14 | swing              |               -3.37 |                 -7.05 |                  nan |
|    672 | GLE.PA   | GLE.PA | EUROPE   |               56.46 |             38.12 |         31    |         38.78 |          38.37 |        37.88 |            7.31 |             23.08 |             73.38 |         3.76 |             67.5  | swing              |               -1.81 |                 -6.81 |                  nan |
|    572 | NBIS     | NBIS   | US       |               52.57 |             45.52 |         46.83 |         44.21 |          50.06 |        42.94 |           55.15 |              2.23 |             17.17 |         8.86 |             64.66 | medium             |               -8.63 |                 -6.5  |                  nan |
|    358 | ABCL     | ABCL   | US       |                3.36 |             54.48 |         73.77 |         64.67 |          44.29 |        30.52 |            9.48 |             12.66 |             32.21 |         9.01 |             63.64 | short              |               -0.89 |                 -6.27 |                  nan |
|    559 | BNP.PA   | BNP.PA | EUROPE   |              117.03 |             46.07 |         38.97 |         47.66 |          46.21 |        45.94 |           27.41 |             18.61 |             73.52 |         2.63 |             67.5  | swing              |               -1.28 |                 -6.25 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.89

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
- Excluded by hard/data filters: **279**
- Event watch (otherwise eligible): **1**
- Final eligible: **720**
- Eligible change vs previous stored run: **+19**

Top exclusion categories:
- liquidity: 230
- price: 171
- market_cap: 154
- price_history: 17
- data_confidence: 16
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| TNK | 3 | 3 |  | 2 | 2 | main,value,quality_value |
| BAX | 4 |  | 1 |  | 2 | main,pullback |
| BCRX | 9 |  | 2 |  | 2 | main,pullback |
| SLDE | 42 | 6 |  | 6 | 1 | value,quality_value |
| PARR | 66 | 7 | 80 | 9 | 1 | value,quality_value |
| HRTG | 76 | 2 | 28 | 3 | 1 | value,quality_value |
| EVT | 78 | 9 |  | 8 | 1 | value,quality_value |
| PEO | 103 | 4 |  | 4 | 1 | value,quality_value |
| PBR-A | 156 | 1 |  | 1 | 1 | value,quality_value |
| AVGO | 448 | 5 |  | 5 | 1 | value,quality_value |
| AD | 512 | 8 | 179 | 7 | 1 | value,quality_value |
| HQL | 1 |  |  |  | 1 | main |
| HALO | 2 |  |  |  | 1 | main |
| RMAX | 5 |  |  |  | 1 | main |
| TWST | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **5** (HALO, RMAX, U, PBF, PSX)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (SYENS.BR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | HRTG | value+pullback | 64.46 | 74.72 | 66.56 | 59.22 | 59.90 | 52.65 | 67.70 |
| 2 | BCRX | pullback | 59.25 | 52.36 | 81.50 | 86.54 | 94.91 | 82.03 | 75.47 |
| 3 | OUT1V.HE | pullback | 56.04 | 52.74 | 78.81 | 71.54 | 99.01 | 78.53 | 62.93 |
| 4 | GL9.IR | pullback | 55.91 | 42.97 | 73.26 | 98.12 | 61.04 | 83.89 | 62.97 |
| 5 | BAX | pullback | 54.83 | 47.07 | 70.90 | 76.88 | 99.01 | 78.37 | 77.16 |
| 6 | KRMN | pullback | 54.20 | 36.32 | 82.92 | 88.87 | 65.51 | 67.94 | 52.45 |
| 7 | AALB.AS | pullback | 52.70 | 45.73 | 83.20 | 74.51 | 63.90 | 71.68 | 61.15 |
| 8 | NTAP | pullback | 51.63 | 38.66 | 78.14 | 87.64 | 52.98 | 68.28 | 69.96 |
| 9 | PARR | value+pullback | 51.62 | 60.66 | 34.36 | 57.20 | 66.12 | 48.20 | 68.72 |
| 10 | TNK | value | 51.32 | 57.06 | 30.95 | 82.28 | 72.96 | 72.83 | 77.79 |
| 11 | PDI | pullback | 51.07 | 56.72 | 77.59 |  |  | 95.87 | 32.25 |
| 12 | PBR-A | value | 50.93 | 66.99 | 48.64 | 74.81 |  | 73.08 | 62.54 |
| 13 | GALD.SW | pullback | 50.89 | 31.75 | 76.85 | 77.88 | 56.70 | 71.60 | 49.92 |
| 14 | KRZ.IR | pullback | 50.62 | 45.54 | 66.17 | 96.00 | 45.16 | 75.79 | 56.28 |
| 15 | BEN | pullback | 50.56 | 57.41 | 64.38 | 86.35 | 61.66 | 76.71 | 67.87 |
| 16 | PAH3.DE | pullback | 50.36 | 63.35 | 75.03 |  | 83.50 | 78.78 | 47.28 |
| 17 | METSO.HE | pullback | 50.28 | 40.35 | 82.57 | 83.15 | 40.69 | 65.47 | 50.39 |
| 18 | FITB | pullback | 49.92 | 55.84 | 85.17 | 69.78 | 51.61 | 65.00 | 57.00 |
| 19 | BIRG.IR | pullback | 49.71 | 60.21 | 63.65 | 97.26 | 38.71 | 76.71 | 59.92 |
| 20 | BN | pullback | 49.63 | 49.35 | 80.84 | 68.46 |  | 70.76 | 47.54 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 9/10 | 10/10 | 9/10 | 1/10 | 66.8 | 5 / 5 |
| Top 25 | 24/25 | 22/25 | 24/25 | 21/25 | 1/25 | 66.6 | 12 / 13 |
| Top 50 | 48/50 | 45/50 | 48/50 | 42/50 | 1/50 | 66.6 | 25 / 25 |

Top-10 market-cap mix: micro_250m_1b=2, small_1_5b=2, mid_5_20b=5, large_20_100b=1
Top-10 sparse-data names: HQL (missing quality,revisions; conf=55.6)
