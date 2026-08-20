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

- **EUROPE:** 89.2/100
- **OTHER:** 74.8/100
- **US:** 87.0/100

## Main multi-horizon ranking

|   rank | symbol    | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HALO      | HALO                | US       |               10.55 |             78.84 |         84.89 |         82.73 |          74.95 |        72.94 |           86.33 |             68.36 |             52.47 |         5.49 |             66.48 | short              |               -0.95 |                  0.71 |                  nan |
|      2 | BAX       | BAX                 | US       |               11.89 |             77.4  |         80.31 |         82.63 |          74.48 |        71.76 |           76.05 |             99.01 |             55.49 |         5.85 |             66.02 | swing              |                1.02 |                  0.84 |                  nan |
|      3 | MU        | MU                  | US       |              914    |             76.19 |         54    |         69.74 |          82.64 |        83.2  |           95.29 |             58.71 |             72.38 |         8.05 |             67.5  | long               |               -2.48 |                 -0.45 |                  nan |
|      4 | NAT       | NAT                 | US       |                1.28 |             76.12 |         75.85 |         78.99 |          76.39 |        68.17 |           76.92 |             73.3  |             38.01 |         4.51 |             66.7  | swing              |               -0.91 |                nan    |                  nan |
|      5 | PBF       | PBF                 | US       |                7.57 |             76.09 |         79.08 |         78.93 |          73.25 |        68.57 |           50.52 |             56.28 |             84.43 |         7.01 |             64.98 | short              |               -2.8  |                 -3.32 |                  nan |
|      6 | AMC       | AMC                 | US       |                1.94 |             76.06 |         64.89 |         80.94 |          76.37 |        75.75 |           82.21 |             79.85 |            nan    |         9.6  |             61.25 | swing              |               -0.8  |                nan    |                  nan |
|      7 | TNK       | Teekay Tankers Ltd. | OTHER    |                2.72 |             75.55 |         81.19 |         76.12 |          74.99 |        73.82 |           75.11 |             75.31 |             63.1  |         4.94 |             84.89 | short              |                3.11 |                  1.39 |                  nan |
|      8 | FRO       | FRO                 | US       |                8.55 |             75.48 |         77.25 |         75.15 |          75.81 |        74.11 |           83.17 |             62.05 |             58.51 |         5.16 |             67.5  | short              |               -2.35 |                  0.26 |                  nan |
|      9 | CCC       | CCC                 | US       |                3.78 |             75.33 |         82.58 |         79.17 |          71.5  |        69.87 |           86.96 |             80.47 |             51.74 |         7.91 |             66.02 | short              |               -1.36 |                  1.44 |                  nan |
|     10 | U         | U                   | US       |               17.9  |             75.3  |         84.45 |         85.81 |          66.15 |        48.97 |           44.19 |             97.9  |             19.13 |         8.32 |             67.5  | swing              |               -1.31 |                  0.09 |                  nan |
|     11 | PSX       | PSX                 | US       |               83.49 |             75.23 |         76.41 |         76.25 |          74.21 |        71.48 |           79.66 |             53.77 |             58.13 |         3.36 |             67.5  | short              |               -2.28 |                 -1.37 |                  nan |
|     12 | BCRX      | BCRX                | US       |                2.22 |             75.21 |         61.96 |         73.08 |          78.16 |        77.33 |           84.87 |             95.06 |             66.44 |         5.76 |             66.59 | medium             |                0.62 |                  2.8  |                  nan |
|     13 | NOEJ.DE   | NOEJ.DE             | EUROPE   |                0.59 |             74.94 |         79.52 |         75.41 |          74.47 |        68.96 |           94.98 |             90.23 |             27.64 |         4.13 |             65.68 | short              |               -0.73 |                nan    |                  nan |
|     14 | HPE       | HPE                 | US       |               60.76 |             74.87 |         60.46 |         78.91 |          78.92 |        70.83 |           71.56 |             73.18 |             53.68 |         6.79 |             65.68 | medium             |               -4.34 |                 -2.25 |                  nan |
|     15 | AMCX      | AMCX                | US       |                0.43 |             74.61 |         81.08 |         79.74 |          69.48 |        62.97 |           22.2  |             89.86 |             95.28 |         6.69 |             67.05 | short              |                6.21 |                  1.03 |                  nan |
|     16 | AUTL      | AUTL                | US       |                0.58 |             74.39 |         87.67 |         78.78 |          67.03 |        70    |           57.63 |             55.62 |             96.88 |         7.81 |             63.64 | short              |                2.88 |                 -1.99 |                  nan |
|     17 | FLYW      | FLYW                | US       |                1.98 |             74.17 |         78.35 |         75.29 |          73.04 |        67.83 |           74.16 |             75.53 |             51.19 |         5.81 |             66.7  | short              |              nan    |                  0.44 |                  nan |
|     18 | W         | W                   | US       |               12.29 |             74.12 |         86.81 |         80.47 |          67.77 |        53.09 |          nan    |             97.65 |             17.01 |         8.69 |             63.75 | short              |               -0.48 |                  1.97 |                  nan |
|     19 | SSABBH.HE | SSABBH.HE           | EUROPE   |                9.46 |             74.09 |         67.79 |         69.16 |          79.03 |        82.05 |           75.39 |            nan    |             98.39 |         3.31 |             62.84 | long               |               -2.13 |                 -1.88 |                  nan |
|     20 | PGEN      | PGEN                | US       |                2.2  |             74.08 |         88.09 |         81.15 |          67    |        51.16 |           66.36 |            nan    |              1.66 |         7.6  |             62.84 | short              |                1.56 |                  1.83 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                        | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:----------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                    | EUROPE   |              220.39 |                  68.08 |                    72.09 |                 73.66 |              68.38 |                78.43 |                   21.57 |           93.58 |             52.41 |     nan     |         nan |       nan |      nan    |         9.98 |         10.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | BHF      | Brighthouse Financial, Inc. | US       |                2.65 |                  79.15 |                    69.75 |                 67.1  |              74.1  |                67.5  |                   32.5  |           55.68 |             49.6  |       6.488 |         nan |       nan |      nan    |         2.65 |          4.25 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|          nan | PBR-A    | PBR-A                       | US       |               98.5  |                  68.59 |                    69.73 |                 70.16 |              69.14 |                71.34 |                   28.66 |           72.3  |            nan    |     nan     |         nan |       nan |      nan    |         6.77 |          4.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAH3.DE  | PAH3.DE                     | EUROPE   |                8.49 |                  63.78 |                    69.27 |                 71    |              68.64 |                79.39 |                   20.61 |          nan    |             84.3  |     nan     |         nan |       nan |      nan    |         1.88 |         89.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | RCI      | Rogers Communications Inc.  | OTHER    |               17.04 |                  68.95 |                    68.27 |                 67.7  |              65.82 |                61.95 |                   38.05 |           79.35 |             50.29 |       0.277 |         nan |       nan |        7.32 |        10.43 |          4.37 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|          nan | VOW.DE   | VOW.DE                      | EUROPE   |               38.02 |                  68.32 |                    66.94 |                 66.52 |              67.09 |                64.22 |                   35.78 |          nan    |             63.41 |     nan     |         nan |       nan |      nan    |         2.79 |          7.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                     | EUROPE   |               37.52 |                  69.16 |                    66.56 |                 65.8  |              66.84 |                61.09 |                   38.91 |          nan    |             60.44 |     nan     |         nan |       nan |      nan    |         3.18 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                     | EUROPE   |               17.53 |                  59.95 |                    66.27 |                 68.63 |              60.89 |                76.77 |                   23.23 |           97.11 |             39.06 |     nan     |         nan |       nan |      nan    |        10.17 |         13.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | TNK      | Teekay Tankers Ltd.         | OTHER    |                2.72 |                  61.38 |                    65.94 |                 68.66 |              64.88 |                73.08 |                   26.92 |           75.11 |             75.31 |       0.071 |         nan |       nan |        3.87 |         8.33 |          5.35 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY      | BMY                         | US       |              119.27 |                  63.47 |                    65.92 |                 66.76 |              63.92 |                70.87 |                   29.13 |           77.47 |             54.64 |     nan     |         nan |       nan |      nan    |        10.31 |         14.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | IHS      | IHS Holding Limited         | OTHER    |                2.43 |                  69.79 |                    65.82 |                 66    |              69.36 |                59.14 |                   40.86 |           52.12 |             84.63 |      -0.115 |         nan |       nan |        7.47 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BEN      | BEN                         | US       |               14.91 |                  56.59 |                    64.75 |                 67.44 |              60.78 |                76.21 |                   23.79 |           84.28 |             63.16 |     nan     |         nan |       nan |      nan    |        10.76 |         23.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                        | US       |              221.04 |                  67.12 |                    64.58 |                 63.91 |              63.71 |                63.71 |                   36.29 |           73.1  |             39.18 |     nan     |         nan |       nan |      nan    |        10.52 |         10.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | ALL-PH   | The Allstate Corporation    | US       |               24.57 |                  66.16 |                    64.56 |                 64.54 |              63.47 |                59.4  |                   40.6  |           72.63 |             51.36 |       0.533 |         nan |       nan |        0.5  |       nan    |          3.41 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BSBR     | BSBR                        | US       |               36.02 |                  67.9  |                    64.51 |                 63.45 |              66    |                59.35 |                   40.65 |           57.4  |             64.28 |     nan     |         nan |       nan |      nan    |         6.44 |         16.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EVK.DE   | EVK.DE                      | EUROPE   |                8.64 |                  56.58 |                    63.75 |                 65.84 |              62.97 |                78.61 |                   21.39 |          nan    |             80.84 |     nan     |         nan |       nan |      nan    |        12.37 |         71.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                         | US       |               15.45 |                  66.97 |                    63.74 |                 63.18 |              60.51 |                63.39 |                   36.61 |           88.86 |              8.78 |     nan     |         nan |       nan |      nan    |         7.63 |          5.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBLK     | SBLK                        | US       |                2.91 |                  60.01 |                    63.59 |                 64.83 |              61.49 |                68.6  |                   31.4  |           74.52 |             59.33 |     nan     |         nan |       nan |      nan    |         8.48 |         11.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS                      | EUROPE   |               11.87 |                  61.17 |                    63.56 |                 64.2  |              61.96 |                70.06 |                   29.94 |           72.85 |             53.03 |     nan     |         nan |       nan |      nan    |         8.83 |         13.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                       | EUROPE   |               20.05 |                  62.96 |                    63.54 |                 63.63 |              62.1  |                68.62 |                   31.38 |           73.53 |             44.13 |     nan     |         nan |       nan |      nan    |         8.85 |         11.37 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                        | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:----------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                    | EUROPE   |              220.39 |                  68.08 |                    72.09 |                 73.66 |              68.38 |                78.43 |                   21.57 |           93.58 |             52.41 |     nan     |         nan |       nan |      nan    |         9.98 |         10.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAH3.DE  | PAH3.DE                     | EUROPE   |                8.49 |                  63.78 |                    69.27 |                 71    |              68.64 |                79.39 |                   20.61 |          nan    |             84.3  |     nan     |         nan |       nan |      nan    |         1.88 |         89.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A                       | US       |               98.5  |                  68.59 |                    69.73 |                 70.16 |              69.14 |                71.34 |                   28.66 |           72.3  |            nan    |     nan     |         nan |       nan |      nan    |         6.77 |          4.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | TNK      | Teekay Tankers Ltd.         | OTHER    |                2.72 |                  61.38 |                    65.94 |                 68.66 |              64.88 |                73.08 |                   26.92 |           75.11 |             75.31 |       0.071 |         nan |       nan |        3.87 |         8.33 |          5.35 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                     | EUROPE   |               17.53 |                  59.95 |                    66.27 |                 68.63 |              60.89 |                76.77 |                   23.23 |           97.11 |             39.06 |     nan     |         nan |       nan |      nan    |        10.17 |         13.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | RCI      | Rogers Communications Inc.  | OTHER    |               17.04 |                  68.95 |                    68.27 |                 67.7  |              65.82 |                61.95 |                   38.05 |           79.35 |             50.29 |       0.277 |         nan |       nan |        7.32 |        10.43 |          4.37 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN      | BEN                         | US       |               14.91 |                  56.59 |                    64.75 |                 67.44 |              60.78 |                76.21 |                   23.79 |           84.28 |             63.16 |     nan     |         nan |       nan |      nan    |        10.76 |         23.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | BHF      | Brighthouse Financial, Inc. | US       |                2.65 |                  79.15 |                    69.75 |                 67.1  |              74.1  |                67.5  |                   32.5  |           55.68 |             49.6  |       6.488 |         nan |       nan |      nan    |         2.65 |          4.25 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|          nan | BMY      | BMY                         | US       |              119.27 |                  63.47 |                    65.92 |                 66.76 |              63.92 |                70.87 |                   29.13 |           77.47 |             54.64 |     nan     |         nan |       nan |      nan    |        10.31 |         14.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE                      | EUROPE   |               38.02 |                  68.32 |                    66.94 |                 66.52 |              67.09 |                64.22 |                   35.78 |          nan    |             63.41 |     nan     |         nan |       nan |      nan    |         2.79 |          7.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                          | US       |              914    |                  51.44 |                    62.12 |                 66.34 |              55.58 |                70.38 |                   29.62 |           95.29 |             58.71 |     nan     |         nan |       nan |      nan    |         6.05 |         21.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                         | US       |                8.55 |                  56.34 |                    63.51 |                 66.12 |              59.58 |                71.13 |                   28.87 |           83.17 |             62.05 |     nan     |         nan |       nan |      nan    |        10.94 |         10.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | IHS      | IHS Holding Limited         | OTHER    |                2.43 |                  69.79 |                    65.82 |                 66    |              69.36 |                59.14 |                   40.86 |           52.12 |             84.63 |      -0.115 |         nan |       nan |        7.47 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | EVK.DE   | EVK.DE                      | EUROPE   |                8.64 |                  56.58 |                    63.75 |                 65.84 |              62.97 |                78.61 |                   21.39 |          nan    |             80.84 |     nan     |         nan |       nan |      nan    |        12.37 |         71.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                     | EUROPE   |               37.52 |                  69.16 |                    66.56 |                 65.8  |              66.84 |                61.09 |                   38.91 |          nan    |             60.44 |     nan     |         nan |       nan |      nan    |         3.18 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | GL9.IR   | GL9.IR                      | EUROPE   |                5.38 |                  42.78 |                    60.13 |                 65.77 |              52.23 |                84.33 |                   15.67 |           97.95 |             62.55 |     nan     |         nan |       nan |      nan    |        15.27 |         26.5  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBLK     | SBLK                        | US       |                2.91 |                  60.01 |                    63.59 |                 64.83 |              61.49 |                68.6  |                   31.4  |           74.52 |             59.33 |     nan     |         nan |       nan |      nan    |         8.48 |         11.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                         | US       |                2.78 |                  60.32 |                    63.38 |                 64.81 |              59.44 |                67.39 |                   32.61 |           86.96 |             38.81 |     nan     |         nan |       nan |      nan    |        10.63 |          6.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DRH      | DRH                         | US       |                2.26 |                  47.81 |                    60.52 |                 64.68 |              55.13 |                84.42 |                   15.58 |           83.2  |            nan    |     nan     |         nan |       nan |      nan    |        21.56 |         17.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | ALL-PH   | The Allstate Corporation    | US       |               24.57 |                  66.16 |                    64.56 |                 64.54 |              63.47 |                59.4  |                   40.6  |           72.63 |             51.36 |       0.533 |         nan |       nan |        0.5  |       nan    |          3.41 |      nan    |                 nan |              nan |                   8 |                  0.42 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.89 |                     0.06 |    -0.01 |      0.23 |                  70.9  |                        82.01 |         80.31 |         82.63 |          74.48 |        71.76 |           76.05 |             99.01 |         5.85 |
|               2 | BCRX     | BCRX     | US       |                2.22 |                     0.05 |    -0.05 |      0.06 |                  81.5  |                        80    |         61.96 |         73.08 |          78.16 |        77.33 |           84.87 |             95.06 |         5.76 |
|               3 | NTAP     | NTAP     | US       |               32.91 |                     0.06 |    -0.04 |      0.17 |                  78.14 |                        75.13 |         67.17 |         76.02 |          73.21 |        65.79 |           86.29 |             54.26 |         6.24 |
|               4 | P        | P        | US       |               32.15 |                     0.05 |     0.01 |      0.5  |                  67.49 |                        74.86 |         80.5  |         77.69 |          65.96 |        54.12 |           66.17 |             75.03 |         7.83 |
|               5 | GENI     | GENI     | US       |                1.86 |                     0.07 |     0.02 |      0.22 |                  55.24 |                        74.84 |         77.81 |         76.55 |          68.71 |        69.15 |           63.97 |             99.01 |         9.11 |
|               6 | SMWB     | SMWB     | US       |                0.64 |                     0.07 |    -0.05 |      0.33 |                  74.13 |                        74.38 |         74.62 |         82.56 |          63.02 |        43.38 |           35.66 |             99.01 |         9.38 |
|               7 | HPE      | HPE      | US       |               60.76 |                     0.11 |    -0.1  |      0.1  |                  63.73 |                        74.3  |         60.46 |         78.91 |          78.92 |        70.83 |           71.56 |             73.18 |         6.79 |
|               8 | SNOW     | SNOW     | US       |               97.28 |                     0.04 |    -0.02 |      0.21 |                  65.85 |                        74.26 |         73.01 |         82.8  |          67.41 |        46.88 |           43.14 |             95.67 |         8.78 |
|               9 | AMC      | AMC      | US       |                1.94 |                     0.12 |    -0    |      0.12 |                  34.35 |                        74.04 |         64.89 |         80.94 |          76.37 |        75.75 |           82.21 |             79.85 |         9.6  |
|              10 | SYENS.BR | SYENS.BR | EUROPE   |                8.22 |                     0.02 |    -0    |      0.16 |                  51.4  |                        73.27 |         75.21 |         69.35 |          62.12 |        58.34 |           71.63 |             90.85 |         5.04 |
|              11 | BFLY     | BFLY     | US       |                2.11 |                     0.05 |    -0.03 |      0.39 |                  79.25 |                        72    |         73.74 |         79.34 |          68.7  |        50.25 |           46.97 |             73.67 |         8.37 |
|              12 | ZETA     | ZETA     | US       |                6.24 |                     0.03 |     0.01 |      0.43 |                  51.68 |                        72    |         83.6  |         81.69 |          66.31 |        51.62 |           48.4  |             85.11 |         7.48 |
|              13 | WKC      | WKC      | US       |                1.61 |                     0.09 |    -0.01 |      0.01 |                  50.6  |                        71.51 |         58.58 |         76.33 |          75.44 |        65.39 |           54.54 |             99.01 |         3.11 |
|              14 | QNST     | QNST     | US       |                1.04 |                     0.04 |     0.01 |      0.35 |                  59.99 |                        71.49 |         81.41 |         74.22 |          66.91 |        67.74 |           83.81 |             33.5  |         7.75 |
|              15 | KRMN     | KRMN     | US       |                6.66 |                     0.06 |    -0.06 |      0.22 |                  82.92 |                        71.31 |         62.73 |         45.05 |          50.15 |        54.51 |           87.74 |             66.38 |         8.76 |
|              16 | NWL      | NWL      | US       |                2.27 |                     0.03 |     0    |      0.14 |                  56.25 |                        71.28 |         74.41 |         82.23 |          69.2  |        62.71 |           36.31 |             96.42 |         8.05 |
|              17 | JHX      | JHX      | US       |               15.14 |                     0.03 |    -0.02 |      0.22 |                  60.55 |                        71.01 |         76.45 |         76.95 |          63.63 |        57.45 |           57.73 |             79.36 |         6.71 |
|              18 | TGB      | TGB      | US       |                2.68 |                     0.04 |    -0.03 |      0.12 |                  70.04 |                        70.93 |         73.43 |         71.98 |          68.63 |        66.64 |           55.41 |             84.18 |         7.48 |
|              19 | KRX.IR   | KRX.IR   | EUROPE   |               18.34 |                     0.02 |    -0.02 |      0.33 |                  53.46 |                        70.35 |         74.91 |         66.2  |          60.99 |        60.75 |           97.95 |             35.23 |         5.14 |
|              20 | OKTA     | OKTA     | US       |               21.38 |                     0.09 |    -0.04 |      0.03 |                  62.05 |                        70.1  |         52.2  |         73.37 |          70.27 |        58.18 |           67.33 |             70.95 |         7.46 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | PD       | PagerDuty, Inc.                                      | US       |                0.81 |             70.11 |         77.43 |         75.12 |          65.09 |        61.48 |           81.25 |             57.63 |             39.67 |         8.08 |             86.86 | short              |                7.47 |                 -0.1  |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |             51.07 |         43.08 |         45.9  |          56.25 |        65.84 |           83.69 |             46.59 |             60    |         3.81 |             75.81 | long               |                2.61 |                  0.26 |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.                              | US       |                3.42 |             48.21 |         47.06 |         47.34 |          49.09 |        57.49 |           70.87 |             53.46 |             54.24 |         7.28 |             87.87 | long               |              nan    |                  0.44 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.77 |             46.92 |         53.82 |         36.29 |          42.91 |        50.93 |           54.61 |             69.82 |             55.6  |         6.85 |             77.1  | short              |                5.21 |                  2.26 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.93 |             44.05 |         43.99 |         30.37 |          44.11 |        57.64 |           84.42 |             23.88 |             46.89 |         8.9  |             78.45 | long               |               11.41 |                  2    |                  nan |
|    nan | DQ       | Daqo New Energy Corp.                                | OTHER    |                0.82 |             32.16 |         51.32 |         25.99 |          27.42 |        36.89 |           31.88 |             34.23 |             60    |         8.5  |             76.14 | short              |                1.42 |                  1.16 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    376 | TEM      | TEM    | US       |                9.54 |             54.35 |         76.48 |         62.75 |          45.94 |        35    |           32.64 |             81.09 |              5.65 |         9    |             63.64 | short              |               12.25 |                  3.41 |                  nan |
|    295 | HIMS     | HIMS   | US       |                6.26 |             57.37 |         55.96 |         67.87 |          58.78 |        41.41 |           36.88 |             96.54 |             14.23 |         9.41 |             67.5  | swing              |                5.53 |                  3.01 |                  nan |
|    335 | BBIO     | BBIO   | US       |               14.17 |             56.01 |         55.63 |         58.83 |          56.38 |        49.48 |           68.15 |             48.08 |              1.26 |         4.7  |             65.57 | swing              |                1.01 |                  2.84 |                  nan |
|     12 | BCRX     | BCRX   | US       |                2.22 |             75.21 |         61.96 |         73.08 |          78.16 |        77.33 |           84.87 |             95.06 |             66.44 |         5.76 |             66.59 | medium             |                0.62 |                  2.8  |                  nan |
|    599 | ABR      | ABR    | US       |                0.91 |             43.98 |         58.73 |         40.91 |          40.26 |        47.05 |           23.33 |             70.46 |             80.1  |         6.74 |             67.5  | short              |               14.7  |                  2.64 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    548 | RBI.VI   | RBI.VI | EUROPE   |               19.72 |             46.9  |         48.27 |         51.26 |          45.52 |        39.51 |           12.27 |             10.26 |             68.92 |         3.75 |             66.14 | swing              |               -3.57 |                 -7.09 |                  nan |
|    659 | GLE.PA   | GLE.PA | EUROPE   |               56.46 |             38.42 |         30.96 |         38.74 |          38.63 |        38.21 |            7.54 |             24.23 |             73.83 |         3.72 |             67.5  | swing              |               -1.51 |                 -6.75 |                  nan |
|    575 | NBIS     | NBIS   | US       |               49.09 |             45.27 |         46.59 |         43.96 |          50.21 |        43.54 |           54.9  |              2.35 |             19.88 |         8.84 |             64.66 | medium             |               -8.87 |                 -6.55 |                  nan |
|    558 | BNP.PA   | BNP.PA | EUROPE   |              117.03 |             46.34 |         38.76 |         47.51 |          46.41 |        46.27 |           28.04 |             19.28 |             73.53 |         2.61 |             67.5  | swing              |               -1.02 |                 -6.19 |                  nan |
|    359 | ABCL     | ABCL   | US       |                3.36 |             55.01 |         73.89 |         65.06 |          44.95 |        32    |            9.57 |             12.61 |             37.23 |         8.98 |             63.64 | short              |               -0.36 |                 -6.17 |                  nan |

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
- Excluded by hard/data filters: **286**
- Event watch (otherwise eligible): **6**
- Final eligible: **708**
- Eligible change vs previous stored run: **+7**

Top exclusion categories:
- liquidity: 234
- price: 169
- market_cap: 158
- price_history: 17
- data_confidence: 16
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| TNK | 7 | 3 |  | 1 | 2 | main,value,quality_value |
| BAX | 2 |  | 1 |  | 2 | main,pullback |
| AMC | 6 |  | 9 |  | 2 | main,pullback |
| PARR | 29 | 7 | 40 | 7 | 1 | value,quality_value |
| EVT | 112 | 9 |  | 6 | 1 | value,quality_value |
| KYN | 182 | 10 |  | 8 | 1 | value,quality_value |
| RCI | 261 | 2 |  | 2 | 1 | value,quality_value |
| IHS | 278 | 4 |  | 4 | 1 | value,quality_value |
| ALL-PH | 542 | 5 | 237 | 5 | 1 | value,quality_value |
| XNET | 590 | 8 |  | 9 | 1 | value,quality_value |
| BHF | 624 | 1 |  | 3 | 1 | value,quality_value |
| HALO | 1 |  |  |  | 1 | main |
| MU | 3 |  |  |  | 1 | main |
| NAT | 4 |  |  |  | 1 | main |
| PBF | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (HALO, NAT, PBF, AMC, FRO, CCC, U)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (AMC, SYENS.BR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | ALL-PH | value+pullback | 61.71 | 66.16 | 55.82 | 72.63 | 51.36 | 59.40 | 47.03 |
| 2 | TV | value+pullback | 60.70 | 62.92 | 77.79 | 50.00 | 37.45 | 55.64 | 38.20 |
| 3 | HRTG | value+pullback | 60.04 | 56.84 | 66.56 | 58.41 | 66.71 | 54.59 | 67.48 |
| 4 | BCRX | pullback | 58.89 | 52.80 | 81.50 | 84.87 | 95.06 | 81.41 | 75.21 |
| 5 | PARR | value+pullback | 57.53 | 63.57 | 43.28 | 69.06 | 69.67 | 51.56 | 72.37 |
| 6 | GL9.IR | pullback | 56.13 | 42.78 | 73.26 | 97.95 | 62.55 | 84.33 | 62.94 |
| 7 | OUT1V.HE | pullback | 56.09 | 52.37 | 78.81 | 71.61 | 99.01 | 78.70 | 62.83 |
| 8 | BAX | pullback | 54.65 | 46.63 | 70.90 | 76.05 | 99.01 | 78.07 | 77.40 |
| 9 | KRMN | pullback | 54.06 | 35.83 | 82.92 | 87.74 | 66.38 | 67.67 | 52.33 |
| 10 | AALB.AS | pullback | 52.66 | 44.96 | 83.20 | 73.66 | 64.77 | 71.66 | 60.85 |
| 11 | ESI | pullback | 52.29 | 42.38 | 74.19 | 83.53 | 68.60 | 71.75 | 54.86 |
| 12 | TNK | value | 51.83 | 61.38 | 30.95 | 75.11 | 75.31 | 73.08 | 75.55 |
| 13 | CRF | pullback | 51.71 | 51.92 | 76.79 | 76.30 |  | 80.35 | 52.97 |
| 14 | NTAP | pullback | 51.51 | 40.19 | 78.14 | 86.29 | 54.26 | 68.04 | 70.19 |
| 15 | GALD.SW | pullback | 51.29 | 31.21 | 76.85 | 78.71 | 57.85 | 72.43 | 50.24 |
| 16 | PDI | pullback | 51.12 | 57.03 | 77.59 |  |  | 96.11 | 32.39 |
| 17 | ROCK-B.CO | pullback | 50.90 | 46.83 | 66.02 | 74.78 | 85.11 | 73.35 | 56.80 |
| 18 | KRZ.IR | pullback | 50.70 | 45.53 | 66.17 | 95.44 | 46.48 | 75.95 | 56.22 |
| 19 | PAH3.DE | pullback | 50.56 | 63.78 | 75.03 |  | 84.30 | 79.39 | 47.38 |
| 20 | BHF | value | 50.56 | 79.15 | 35.00 | 55.68 | 49.60 | 67.50 | 42.06 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 66.6 | 3 / 7 |
| Top 25 | 24/25 | 23/25 | 24/25 | 21/25 | 0/25 | 66.5 | 10 / 15 |
| Top 50 | 49/50 | 46/50 | 49/50 | 44/50 | 0/50 | 66.6 | 25 / 25 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=5, mega_100b_plus=1
