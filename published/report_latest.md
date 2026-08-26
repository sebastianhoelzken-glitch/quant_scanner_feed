# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-26

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

- **EUROPE:** 88.3/100
- **OTHER:** 68.7/100
- **US:** 83.7/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | AVAH     | AVAH                       | US       |                2.54 |             78.24 |         84.86 |         81.77 |          74.71 |        71.59 |           93.75 |             55    |             40.79 |         7.36 |             68.66 | short              |               -0.92 |                  1.92 |                  nan |
|      2 | HALO     | HALO                       | US       |               10.63 |             77.22 |         82.58 |         80.91 |          73.52 |        72.45 |           86.23 |             57.35 |             55.31 |         5.58 |             68.66 | short              |              nan    |                nan    |                  nan |
|      3 | KIN.BR   | KIN.BR                     | EUROPE   |                1.24 |             77.14 |         79.88 |         82.14 |          74.39 |        66.26 |           90.38 |             67.71 |             22.5  |         4.19 |             69.68 | swing              |                0.75 |                  1.95 |                  nan |
|      4 | GH       | GH                         | US       |               18.97 |             77.13 |         74.09 |         80.91 |          80.18 |        73.75 |           62.62 |             82.45 |            nan    |         6.54 |             64.91 | swing              |              nan    |                  0.08 |                  nan |
|      5 | HPE      | HPE                        | US       |               60.65 |             76.88 |         64.48 |         80.86 |          81.27 |        72.91 |           71.25 |             83.16 |             57.1  |         6.82 |             67.86 | medium             |                0.43 |                  0.16 |                  nan |
|      6 | SSRM     | SSRM                       | US       |                6.85 |             76.2  |         85.56 |         78.11 |          73.02 |        74.29 |           66.87 |             76.4  |             79.2  |         7.01 |             68.32 | short              |                1.74 |                  0.78 |                  nan |
|      7 | PR       | PR                         | US       |               16.72 |             76.14 |         79.47 |         75.68 |          76.03 |        76.25 |           78.94 |             74.69 |             70.41 |         4.09 |             68.32 | short              |               -0.06 |                  0.81 |                  nan |
|      8 | SM       | SM                         | US       |                7.27 |             76.07 |         76    |         73.29 |          76.14 |        80.68 |           81.33 |             69.26 |             94.72 |         7.04 |             68.66 | long               |               -2.88 |                  0.3  |                  nan |
|      9 | WT       | WT                         | US       |                3.13 |             75.9  |         82    |         78.64 |          73.17 |        65.01 |           73.34 |             77.71 |             33.19 |         5.38 |             69.68 | short              |              nan    |                  0.88 |                  nan |
|     10 | ERO      | ERO                        | US       |                3.61 |             75.89 |         88.02 |         74.04 |          71.57 |        77.74 |           84.24 |             47.93 |             76.22 |         7.55 |             69.68 | short              |               -1.44 |                  0.15 |                  nan |
|     11 | PARR     | Par Pacific Holdings, Inc. | US       |                3.17 |             75.14 |         50.89 |         71.97 |          79.55 |        78.31 |           81.79 |             62.1  |             73    |         6.84 |             85.72 | medium             |                0.46 |                  1.1  |                  nan |
|     12 | IMAX     | IMAX                       | US       |                2.53 |             74.94 |         81.14 |         78.34 |          71.54 |        59.16 |           65.17 |             82.26 |             19.21 |         5.39 |             67.3  | short              |              nan    |                nan    |                  nan |
|     13 | TGB      | TGB                        | OTHER    |                2.98 |             74.76 |         89.4  |         78.35 |          71.17 |        67.15 |           57.14 |             88.02 |             54.55 |         7.65 |             69.23 | short              |                1.01 |                  0.2  |                  nan |
|     14 | CART     | CART                       | US       |               10.22 |             74.07 |         79.18 |         77.29 |          70.86 |        68.13 |           69.15 |             79.16 |             62.42 |         5.7  |             67.64 | short              |               -1.13 |                  0.28 |                  nan |
|     15 | CAKE     | CAKE                       | US       |                4.84 |             73.96 |         83.09 |         76.79 |          71.14 |        63.79 |           87.1  |             45.82 |             21.22 |         5.76 |             67.18 | short              |               -1.29 |                  0.42 |                  nan |
|     16 | DK       | DK                         | US       |                3.55 |             73.81 |         71.29 |         81.81 |          76.33 |        62.71 |           55.2  |             87.18 |             39.95 |         6.82 |             69.68 | swing              |                3.4  |                  1.33 |                  nan |
|     17 | BEN      | BEN                        | US       |               15.25 |             73.64 |         68.7  |         70.99 |          76.29 |        77.44 |           86.5  |             75.24 |             68.41 |         3.2  |             67.86 | long               |               -0.43 |                  0.63 |                  nan |
|     18 | NIQ      | NIQ                        | US       |                4.86 |             73.49 |         82.98 |         85.46 |          64    |        51.86 |           36.02 |             93.59 |             45.39 |         9.05 |             68.2  | swing              |              nan    |                 -0.58 |                  nan |
|     19 | SBLK     | SBLK                       | US       |                2.98 |             73.41 |         78.49 |         71.19 |          71.6  |        75.22 |           74.44 |             54.02 |             83.36 |         3.92 |             69.34 | short              |               -1.89 |                 -0.33 |                  nan |
|     20 | APA      | APA                        | US       |               12.42 |             73.33 |         71.87 |         69.68 |          74.79 |        74.91 |           74.96 |             69.56 |             74.62 |         5.53 |             68.66 | long               |                4.57 |                  0.68 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | STNE     | StoneCo Ltd.                     | OTHER    |                1.93 |                  75.8  |                    72.92 |                 72.99 |              71.99 |                70.89 |                   29.11 |           85.05 |             46.53 |       0.609 |         nan |       nan |        1.62 |         4.18 |          3.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | YALA     | Yalla Group Limited              | OTHER    |                0.73 |                  70.64 |                    70.7  |                 72.41 |              69.62 |                78.88 |                   21.12 |           87.83 |             45.55 |     nan     |         nan |       nan |        0.18 |         5.85 |          7.3  |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|            3 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.17 |                  71.09 |                    70.1  |                 71.51 |              69.1  |                65.02 |                   34.98 |           81.79 |             62.1  |       0.022 |         nan |       nan |        3.66 |         6.25 |          4.36 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | QFIN     | Qfin Holdings, Inc.              | OTHER    |                1.2  |                  83.55 |                    69.46 |                 65.81 |              73.88 |                59.36 |                   40.64 |           59.02 |             30.36 |       1.047 |         nan |       nan |       -0.31 |         2.58 |          1.92 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|            5 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  61.63 |                    69.31 |                 72.65 |              65.37 |                82.33 |                   17.67 |           93.21 |             61.79 |       0.153 |         nan |       nan |        0.77 |         5.25 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | PRU      | PRU                              | US       |               35.52 |                  67.06 |                    68.37 |                 68.65 |              68.16 |                71.38 |                   28.62 |           68.88 |             70.3  |     nan     |         nan |       nan |      nan    |         8.11 |         11.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                               | US       |               94.6  |                  57.33 |                    68.33 |                 71.94 |              64.05 |                81.33 |                   18.67 |           86.97 |             81.34 |     nan     |         nan |       nan |      nan    |         9.63 |         20.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | IHS      | IHS Holding Limited              | OTHER    |                2.42 |                  70.07 |                    68.12 |                 68.93 |              70.89 |                66.91 |                   33.09 |           59.07 |             83.95 |      -0.115 |         nan |       nan |        7.47 |        15.16 |          5.12 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              218.13 |                  67.02 |                    68.08 |                 68.85 |              64.24 |                71.36 |                   28.64 |           93.12 |             31.42 |     nan     |         nan |       nan |      nan    |         9.97 |         10.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                               | US       |                7.27 |                  62.94 |                    67.44 |                 69.37 |              64.63 |                68.81 |                   31.19 |           81.33 |             69.26 |     nan     |         nan |       nan |      nan    |         4.76 |          6.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | ACCO     | Acco Brands Corporation          | US       |                0.33 |                  84.51 |                    67.29 |                 62.45 |              75.03 |                48.4  |                   51.6  |           35.83 |             54.71 |       0.106 |         nan |       nan |        8    |         4.37 |          6.79 |        0.81 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BEN      | BEN                              | US       |               15.25 |                  56.69 |                    67.18 |                 70.56 |              62.91 |                80.92 |                   19.08 |           86.5  |             75.24 |     nan     |         nan |       nan |      nan    |        11.07 |         23.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ADAM     | ADAM                             | US       |                0.76 |                  59.55 |                    66.46 |                 68.89 |              62.1  |                76.27 |                   23.73 |           89.64 |             54.98 |     nan     |         nan |       nan |      nan    |         7.88 |          5.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | UNIT     | Uniti Group Inc.                 | US       |                2.1  |                  76.5  |                    66.42 |                 64.01 |              67.72 |                54.38 |                   45.62 |           68.61 |             28.52 |      -0.105 |         nan |       nan |        9.12 |       -14.23 |          2.56 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|            9 | PBR-A    | PBR-A                            | US       |               94.23 |                  68.38 |                    66.33 |                 65.92 |              65.46 |                64.07 |                   35.93 |           74    |             46.95 |     nan     |         nan |       nan |      nan    |         6.53 |          4.24 |        4.2  |                 nan |              nan |                   6 |                  0.32 |
|          nan | ET       | ET                               | US       |               62.03 |                  60.57 |                    65.83 |                 67.61 |              61.7  |                76.13 |                   23.87 |           89.46 |             43.82 |     nan     |         nan |       nan |      nan    |        12.01 |         14.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR                              | US       |               98.58 |                  69.25 |                    65.76 |                 64.97 |              64.95 |                61.59 |                   38.41 |           74.31 |             39.98 |     nan     |         nan |       nan |      nan    |         4.48 |          4.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | RCI      | RCI                              | US       |               16.94 |                  60.5  |                    65.56 |                 67.49 |              61.63 |                72.42 |                   27.58 |           87.42 |             50.33 |     nan     |         nan |       nan |      nan    |        10.39 |          4.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                              | US       |              118.9  |                  62.32 |                    65.48 |                 66.61 |              62.94 |                71.18 |                   28.82 |           79.99 |             52.58 |     nan     |         nan |       nan |      nan    |        10.36 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                             | US       |              217.67 |                  66.9  |                    65.48 |                 65.13 |              64.53 |                65.69 |                   34.31 |           73.43 |             45.43 |     nan     |         nan |       nan |      nan    |        10.46 |         10.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | STNE     | StoneCo Ltd.                     | OTHER    |                1.93 |                  75.8  |                    72.92 |                 72.99 |              71.99 |                70.89 |                   29.11 |           85.05 |             46.53 |       0.609 |         nan |       nan |        1.62 |         4.18 |          3.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  61.63 |                    69.31 |                 72.65 |              65.37 |                82.33 |                   17.67 |           93.21 |             61.79 |       0.153 |         nan |       nan |        0.77 |         5.25 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | YALA     | Yalla Group Limited              | OTHER    |                0.73 |                  70.64 |                    70.7  |                 72.41 |              69.62 |                78.88 |                   21.12 |           87.83 |             45.55 |     nan     |         nan |       nan |        0.18 |         5.85 |          7.3  |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BP       | BP                               | US       |               94.6  |                  57.33 |                    68.33 |                 71.94 |              64.05 |                81.33 |                   18.67 |           86.97 |             81.34 |     nan     |         nan |       nan |      nan    |         9.63 |         20.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.17 |                  71.09 |                    70.1  |                 71.51 |              69.1  |                65.02 |                   34.98 |           81.79 |             62.1  |       0.022 |         nan |       nan |        3.66 |         6.25 |          4.36 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BEN      | BEN                              | US       |               15.25 |                  56.69 |                    67.18 |                 70.56 |              62.91 |                80.92 |                   19.08 |           86.5  |             75.24 |     nan     |         nan |       nan |      nan    |        11.07 |         23.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                               | US       |                7.27 |                  62.94 |                    67.44 |                 69.37 |              64.63 |                68.81 |                   31.19 |           81.33 |             69.26 |     nan     |         nan |       nan |      nan    |         4.76 |          6.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | IHS      | IHS Holding Limited              | OTHER    |                2.42 |                  70.07 |                    68.12 |                 68.93 |              70.89 |                66.91 |                   33.09 |           59.07 |             83.95 |      -0.115 |         nan |       nan |        7.47 |        15.16 |          5.12 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ADAM     | ADAM                             | US       |                0.76 |                  59.55 |                    66.46 |                 68.89 |              62.1  |                76.27 |                   23.73 |           89.64 |             54.98 |     nan     |         nan |       nan |      nan    |         7.88 |          5.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              218.13 |                  67.02 |                    68.08 |                 68.85 |              64.24 |                71.36 |                   28.64 |           93.12 |             31.42 |     nan     |         nan |       nan |      nan    |         9.97 |         10.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PRU      | PRU                              | US       |               35.52 |                  67.06 |                    68.37 |                 68.65 |              68.16 |                71.38 |                   28.62 |           68.88 |             70.3  |     nan     |         nan |       nan |      nan    |         8.11 |         11.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                          | EUROPE   |               18.06 |                  57.06 |                    65.05 |                 67.86 |              59.52 |                77.61 |                   22.39 |           95.37 |             44.66 |     nan     |         nan |       nan |      nan    |        10.48 |         14.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                               | US       |               62.03 |                  60.57 |                    65.83 |                 67.61 |              61.7  |                76.13 |                   23.87 |           89.46 |             43.82 |     nan     |         nan |       nan |      nan    |        12.01 |         14.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | RCI      | RCI                              | US       |               16.94 |                  60.5  |                    65.56 |                 67.49 |              61.63 |                72.42 |                   27.58 |           87.42 |             50.33 |     nan     |         nan |       nan |      nan    |        10.39 |          4.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                              | US       |                2.65 |                  60.31 |                    65.24 |                 67.24 |              60.97 |                71.17 |                   28.83 |           89.26 |             47.37 |     nan     |         nan |       nan |      nan    |        10.19 |          6.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PR       | PR                               | US       |               16.72 |                  55.53 |                    64.35 |                 67.21 |              60.99 |                75.2  |                   24.8  |           78.94 |             74.69 |     nan     |         nan |       nan |      nan    |        10.68 |         15.33 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI                           | EUROPE   |               22.15 |                  58.66 |                    65.2  |                 66.99 |              63.63 |                75.83 |                   24.17 |           70.37 |             77.48 |     nan     |         nan |       nan |      nan    |         8.98 |         14.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                              | US       |              118.9  |                  62.32 |                    65.48 |                 66.61 |              62.94 |                71.18 |                   28.82 |           79.99 |             52.58 |     nan     |         nan |       nan |      nan    |        10.36 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | COP      | COP                              | US       |              135.74 |                  61.32 |                    65.16 |                 66.28 |              64.36 |                70.07 |                   29.93 |           67.13 |             75.95 |     nan     |         nan |       nan |      nan    |        13.84 |         17.63 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CTSH     | CTSH                             | US       |               24.34 |                  57.33 |                    63.62 |                 66.27 |              59.39 |                66.84 |                   33.16 |           85.29 |             60.85 |     nan     |         nan |       nan |      nan    |         9.99 |         13.36 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name    | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:--------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | NTAP     | NTAP    | US       |               31.52 |                     0.09 |    -0.08 |      0.07 |                  70.76 |                        76.49 |         58.34 |         75.52 |          77.19 |        69.27 |           88.49 |             69.47 |         6.17 |
|               2 | DK       | DK      | US       |                3.55 |                     0.05 |    -0.01 |      0.08 |                  73.09 |                        75.98 |         71.29 |         81.81 |          76.33 |        62.71 |           55.2  |             87.18 |         6.82 |
|               3 | SM       | SM      | US       |                7.27 |                     0.05 |     0.01 |      0.2  |                  67.46 |                        74.77 |         76    |         73.29 |          76.14 |        80.68 |           81.33 |             69.26 |         7.04 |
|               4 | HPE      | HPE     | US       |               60.65 |                     0.11 |    -0.04 |      0.17 |                  50.64 |                        74.75 |         64.48 |         80.86 |          81.27 |        72.91 |           71.25 |             83.16 |         6.82 |
|               5 | DELL     | DELL    | US       |              250.02 |                     0.09 |    -0.04 |      0.15 |                  61.71 |                        73.05 |         63.02 |         77.69 |          76.58 |        64.75 |           70.54 |             72.26 |         7.73 |
|               6 | PLTR     | PLTR    | US       |              355.73 |                     0.04 |     0.01 |      0.4  |                  59.57 |                        72.97 |         77.05 |         64.68 |          57.54 |        54.37 |           90.41 |             49.48 |         8.45 |
|               7 | WBI      | WBI     | US       |                3.36 |                     0.07 |    -0    |     -0.01 |                  62.29 |                        72.87 |         47.68 |         61.65 |          72.5  |        70.49 |           94.89 |             91.46 |         6.26 |
|               8 | NTNX     | NTNX    | US       |               15.39 |                     0.02 |     0.01 |      0.13 |                  47.84 |                        72.3  |         68.99 |         76.5  |          67.31 |        56.49 |           77.1  |             76.38 |         6.96 |
|               9 | REP.MC   | REP.MC  | EUROPE   |               29.27 |                     0.04 |    -0.02 |      0.06 |                  70.22 |                        72.28 |         62.44 |         75.49 |          75.97 |        71.09 |           62.84 |             76.26 |         3.85 |
|              10 | APA      | APA     | US       |               12.42 |                     0.07 |    -0.02 |      0.18 |                  69.51 |                        71.79 |         71.87 |         69.68 |          74.79 |        74.91 |           74.96 |             69.56 |         5.53 |
|              11 | VET      | VET     | US       |                1.6  |                     0.05 |    -0    |      0.18 |                  68.36 |                        71.63 |         71.56 |         63.78 |          67.12 |        65.39 |           59.94 |             90.73 |         6.67 |
|              12 | SNOW     | SNOW    | US       |               94.17 |                     0.06 |    -0.03 |      0.17 |                  74.97 |                        71.44 |         66.49 |         78.35 |          64.39 |        44.55 |           41.92 |             84.26 |         8.9  |
|              13 | BP       | BP      | US       |               94.6  |                     0.05 |    -0.01 |      0.04 |                  71.75 |                        71.04 |         59.84 |         61.37 |          70.18 |        75.61 |           86.97 |             81.34 |         4.1  |
|              14 | CVE      | CVE     | US       |               48.62 |                     0.07 |    -0.05 |      0.11 |                  79.87 |                        71.02 |         63.65 |         66.37 |          73.27 |        72.38 |           76.93 |             69.79 |         4.8  |
|              15 | BAX      | BAX     | US       |               11.65 |                     0.07 |     0.01 |      0.08 |                  55.96 |                        70.92 |         68.69 |         73.47 |          69.28 |        68.95 |           76.43 |             70.04 |         6.04 |
|              16 | BILL     | BILL    | US       |                4.07 |                     0.07 |    -0.03 |      0.03 |                  70.11 |                        70.76 |         59.16 |         70.93 |          65.84 |        65.88 |           54.19 |             92.93 |         7.04 |
|              17 | AALB.AS  | AALB.AS | EUROPE   |                4.58 |                     0.05 |     0.01 |      0.01 |                  64.52 |                        70.37 |         58.58 |         67.14 |          72.05 |        65.51 |           74.5  |             81.46 |         3.15 |
|              18 | OMV.VI   | OMV.VI  | EUROPE   |               22.15 |                     0.02 |     0    |      0.1  |                  48.47 |                        70.25 |         69.27 |         74.57 |          73.56 |        70.84 |           70.37 |             77.48 |         2.07 |
|              19 | ADAM     | ADAM    | US       |                0.76 |                     0.04 |    -0.02 |      0.13 |                  67.33 |                        70    |         67.46 |         66.96 |          74.36 |        81.76 |           89.64 |             54.98 |         3.06 |
|              20 | ANGX     | ANGX    | US       |                0.73 |                     0.06 |    -0.06 |      0.12 |                  86.66 |                        69.79 |         69.46 |         73.28 |          62.69 |        57.62 |           58.61 |             56.24 |         9.48 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4422.47 |             58.07 |         55.58 |         53.03 |          60.57 |        65.76 |           93.04 |             66.5  |             36.89 |         8.5  |             89.49 | long               |                2.2  |                 -0.21 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.72 |             52.98 |         35.85 |         50.95 |          55.01 |        60.1  |           56.28 |             52.49 |             71.1  |         8.5  |             85.47 | long               |               -1.74 |                  0.11 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.1  |             52.39 |         51.25 |         44.1  |          53.53 |        64.46 |           83.46 |             43.63 |             56.68 |         3.89 |             75.81 | long               |                0.54 |                  0.7  |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             47.12 |         43.55 |         42.48 |          50.68 |        64.67 |           67.72 |             53.81 |             87.9  |         4.38 |             82.14 | long               |                1.82 |                  0.52 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1454.55 |             46.8  |         30.74 |         39.15 |          54.44 |        58.98 |           79.84 |             57.96 |             37.21 |         6.2  |             89.83 | long               |               -1.48 |                 -0.64 |                  nan |
|    nan | BBWI     | BBWI                                                 | US       |                3.04 |             39.08 |         29.49 |         36.94 |          41.22 |        52.58 |           31.25 |             49.89 |             95.67 |         8.5  |             64.5  | long               |               -6.87 |                nan    |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.88 |             37.84 |         30.91 |         33.04 |          42.64 |        55.82 |           60.06 |             43.93 |             73.21 |         8.5  |             78.58 | long               |                0.26 |                 -0.1  |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.7  |             36.28 |         35.91 |         31.04 |          36.65 |        41.96 |           42.43 |             68.12 |             44.52 |         8.5  |             77.1  | long               |               -3.96 |                 -0.51 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.83 |             31.2  |         29.13 |         20.33 |          33.27 |        44.76 |           61.41 |             18.07 |             41.11 |         8.98 |             78.45 | long               |               -1.1  |                 -0.6  |                  nan |
|    nan | LI       | Li Auto Inc.                                         | OTHER    |               10.3  |             25.35 |         30.16 |         22.06 |          23.57 |        27.13 |           21.33 |             37.68 |             39.12 |         8.5  |             76.54 | short              |              nan    |                nan    |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol    | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    610 | CYH       | Community Health Systems, Inc. | US       |                0.36 |             43.76 |         45.88 |         37.65 |          41.64 |        54.06 |           50.36 |             25.47 |             78.68 |         7.8  |             81.72 | long               |               -2.51 |                  3.96 |                  nan |
|    605 | LKFT      | Lakefront Biotherapeutics NV   | OTHER    |                1.67 |             44    |         60.81 |         42.69 |          40.43 |        45.31 |           42.22 |             46.21 |             50.3  |         5.19 |             76.99 | short              |                4.01 |                  3.84 |                  nan |
|     97 | KURA      | KURA                           | US       |                1.04 |             66.59 |         85.07 |         74.7  |          58.47 |        43.9  |           48.64 |             68.51 |              3.49 |         7.21 |             66.84 | short              |                5.71 |                  3.63 |                  nan |
|     54 | TKA.DE    | TKA.DE                         | EUROPE   |                8.53 |             68.97 |         76.1  |         69.09 |          68.86 |        66.79 |          nan    |             61.86 |             57.91 |         6.69 |             66.84 | short              |                0.46 |                  3.47 |                  nan |
|    458 | NOVO-B.CO | Novo Nordisk A/S               | EUROPE   |              182.04 |             52.52 |         52.13 |         46.44 |          52.91 |        60.86 |           74.57 |             47.47 |             61.22 |         5.33 |             88.49 | long               |                5.38 |                  3.05 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    346 | DAR      | DAR     | US       |                8.46 |             56.74 |         53.65 |         52.34 |          59.84 |        63.9  |           63.92 |             39.01 |             67.68 |         3.99 |             68.89 | long               |              -11.61 |                 -3.92 |                  nan |
|    244 | BION.SW  | BION.SW | EUROPE   |                3.34 |             60.02 |         69.85 |         62.56 |          57.47 |        56.61 |           52.2  |             26.09 |             60.91 |         2.09 |             66.84 | short              |               -6.27 |                 -3.45 |                  nan |
|    576 | ZIP      | ZIP     | US       |                0.31 |             46.08 |         46.24 |         59.77 |          45.91 |        30.07 |           19.74 |             53.19 |             13.7  |         9.5  |             67.75 | swing              |               -5.68 |                 -2.97 |                  nan |
|    697 | HFG.DE   | HFG.DE  | EUROPE   |                0.41 |             31.53 |         24.36 |         26.97 |          36.09 |        56.51 |          nan    |             46.88 |             80.58 |         7.07 |             66.84 | long               |                0.61 |                 -2.94 |                  nan |
|    216 | W        | W       | US       |               12.27 |             61.03 |         69.17 |         65.11 |          56.96 |        47.92 |           54.95 |             52.14 |             17.79 |         8.75 |             66.39 | short              |              nan    |                 -2.87 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.86

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
- Excluded by hard/data filters: **288**
- Event watch (otherwise eligible): **10**
- Final eligible: **702**
- Eligible change vs previous stored run: **-2**

Top exclusion categories:
- liquidity: 232
- price: 166
- market_cap: 162
- price_history: 19
- data_confidence: 16
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| HPE | 5 |  | 4 |  | 2 | main,pullback |
| SM | 8 |  | 3 |  | 2 | main,pullback |
| PARR | 11 | 3 |  | 4 | 1 | value,quality_value |
| DDI | 41 | 5 |  | 2 | 1 | value,quality_value |
| PBR-A | 298 | 9 | 148 | 6 | 1 | value,quality_value |
| IHS | 305 | 6 |  | 5 | 1 | value,quality_value |
| YALA | 496 | 2 |  | 3 | 1 | value,quality_value |
| UNIT | 574 | 8 | 296 | 9 | 1 | value,quality_value |
| STNE | 600 | 1 |  | 1 | 1 | value,quality_value |
| XNET | 615 | 10 |  | 10 | 1 | value,quality_value |
| QFIN | 679 | 4 |  | 7 | 1 | value,quality_value |
| AVAH | 1 |  |  |  | 1 | main |
| HALO | 2 |  |  |  | 1 | main |
| KIN.BR | 3 |  |  |  | 1 | main |
| GH | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (AVAH, HALO, KIN.BR, SSRM, PR, WT, ERO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | ATNI | value+pullback | 63.86 | 71.29 | 70.37 | 49.46 | 55.91 | 59.36 | 56.65 |
| 2 | PBR-A | value+pullback | 63.08 | 68.38 | 55.83 | 74.00 | 46.95 | 64.07 | 58.64 |
| 3 | MFA | value+pullback | 62.03 | 58.10 | 68.13 | 78.23 | 33.50 | 62.44 | 39.49 |
| 4 | MC.PA | value+pullback | 61.79 | 56.31 | 57.28 | 73.61 | 59.48 | 67.93 | 40.70 |
| 5 | AVK | value+pullback | 59.50 | 55.04 | 62.34 | 63.30 |  | 64.55 | 49.70 |
| 6 | KYN | value+pullback | 59.49 | 59.83 | 57.00 | 56.41 | 56.50 | 65.89 | 52.75 |
| 7 | ACCO | value+pullback | 59.32 | 84.51 | 53.78 | 35.83 | 54.71 | 48.40 | 52.51 |
| 8 | UNIT | value+pullback | 58.80 | 76.50 | 47.31 | 68.61 | 28.52 | 54.38 | 46.13 |
| 9 | ALL-PH | value+pullback | 57.63 | 60.13 | 50.55 | 68.77 | 43.24 | 61.59 | 45.60 |
| 10 | AAPL | value+pullback | 56.51 | 60.17 | 53.71 | 62.11 | 49.60 | 53.77 | 50.26 |
| 11 | LNC | value+pullback | 56.08 | 57.07 | 63.04 | 46.32 | 64.99 | 48.75 | 56.83 |
| 12 | WBI | pullback | 55.81 | 41.62 | 62.29 | 94.89 | 91.46 | 84.27 | 66.07 |
| 13 | BP | pullback | 55.38 | 57.33 | 71.75 | 86.97 | 81.34 | 81.33 | 65.78 |
| 14 | DDI | value | 55.11 | 61.63 | 42.08 | 93.21 | 61.79 | 82.33 | 70.61 |
| 15 | GNW | value+pullback | 55.09 | 68.32 | 61.43 | 26.65 | 66.93 | 42.75 | 48.85 |
| 16 | ORCL | value+pullback | 54.98 | 69.90 | 55.44 | 45.19 | 59.97 | 36.90 | 41.51 |
| 17 | YALA | value | 54.70 | 70.64 | 35.83 | 87.83 | 45.55 | 78.88 | 50.74 |
| 18 | STNE | value | 54.33 | 75.80 | 9.68 | 85.05 | 46.53 | 70.89 | 44.38 |
| 19 | PARR | value | 52.81 | 71.09 | 41.26 | 81.79 | 62.10 | 65.02 | 75.14 |
| 20 | NTAP | pullback | 52.75 | 39.24 | 70.76 | 88.49 | 69.47 | 74.18 | 72.39 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 68.7 | 3 / 7 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 68.7 | 9 / 16 |
| Top 50 | 49/50 | 48/50 | 49/50 | 47/50 | 1/50 | 68.9 | 22 / 28 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=5, large_20_100b=1
