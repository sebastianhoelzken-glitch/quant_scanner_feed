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

- **EUROPE:** 88.5/100
- **OTHER:** 72.0/100
- **US:** 83.7/100

## Main multi-horizon ranking

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | AVAH     | AVAH   | US       |                2.54 |             78.63 |         85.24 |         82.22 |          75.05 |        72.39 |           93.77 |             52.91 |             42.87 |         7.36 |             68.66 | short              |               -0.52 |                  2    |                  nan |
|      2 | HALO     | HALO   | US       |               10.63 |             78.02 |         83.17 |         81.8  |          74.24 |        73.4  |           85.81 |             57.29 |             57.56 |         5.58 |             68.66 | short              |              nan    |                nan    |                  nan |
|      3 | KIN.BR   | KIN.BR | EUROPE   |                1.24 |             77.83 |         80.81 |         83.3  |          74.84 |        66.65 |           88.81 |             65.86 |             23.33 |         4.19 |             69.68 | swing              |                1.44 |                  2.09 |                  nan |
|      4 | HPE      | HPE    | US       |               60.65 |             77.56 |         64.84 |         81.34 |          81.64 |        73.78 |           70.63 |             81.48 |             60.32 |         6.82 |             67.86 | medium             |                1.11 |                  0.3  |                  nan |
|      5 | GH       | GH     | US       |               18.97 |             77.32 |         74.44 |         81.25 |          80.21 |        73.85 |           62.2  |             80.66 |            nan    |         6.54 |             64.91 | swing              |              nan    |                  0.12 |                  nan |
|      6 | SSRM     | SSRM   | US       |                6.85 |             77.25 |         85.96 |         78.64 |          73.74 |        75.86 |           67.71 |             74.47 |             83.06 |         7.01 |             68.32 | short              |                2.79 |                  0.99 |                  nan |
|      7 | ERO      | ERO    | US       |                3.61 |             77.11 |         88.62 |         74.97 |          72.52 |        79.24 |           84.4  |             47.7  |             79.83 |         7.55 |             69.68 | short              |               -0.22 |                  0.39 |                  nan |
|      8 | PR       | PR     | US       |               16.72 |             76.82 |         79.7  |         76    |          76.38 |        77.27 |           78.58 |             72.82 |             74.22 |         4.09 |             68.32 | short              |                0.62 |                  0.95 |                  nan |
|      9 | WT       | WT     | US       |                3.13 |             76.29 |         82.34 |         79.02 |          73.55 |        65.9  |           73.83 |             75.77 |             35.15 |         5.38 |             69.68 | short              |              nan    |                  0.95 |                  nan |
|     10 | SM       | SM     | US       |                7.27 |             76.27 |         76.2  |         73.51 |          76.35 |        81.43 |           81.15 |             67.26 |             97.39 |         7.04 |             68.66 | long               |               -2.68 |                  0.34 |                  nan |
|     11 | IMAX     | IMAX   | US       |                2.53 |             75.27 |         81.52 |         78.76 |          71.77 |        59.67 |           65.05 |             80.47 |             20.35 |         5.39 |             67.3  | short              |              nan    |                nan    |                  nan |
|     12 | TGB      | TGB    | US       |                2.98 |             74.94 |         89.49 |         78.51 |          71.36 |        68.35 |           56.83 |             86.09 |             59.49 |         7.65 |             69.23 | short              |                1.18 |                  0.23 |                  nan |
|     13 | REP.MC   | REP.MC | EUROPE   |               29.27 |             74.69 |         63.15 |         76.7  |          76.67 |        72.7  |           58.81 |             74.38 |             78.69 |         3.85 |             69.68 | swing              |                5.93 |                  0.88 |                  nan |
|     14 | CAKE     | CAKE   | US       |                4.84 |             74.61 |         83.66 |         77.59 |          71.62 |        64.28 |           86.35 |             45.65 |             22.27 |         5.76 |             67.18 | short              |               -0.64 |                  0.55 |                  nan |
|     15 | CART     | CART   | US       |               10.22 |             74.52 |         79.53 |         77.73 |          71.31 |        69.17 |           69.17 |             77.34 |             65.48 |         5.7  |             67.64 | short              |               -0.68 |                  0.37 |                  nan |
|     16 | SBLK     | SBLK   | US       |                2.98 |             74.48 |         78.87 |         71.85 |          72.37 |        76.58 |           74.4  |             53.82 |             87.36 |         3.92 |             69.34 | short              |               -0.83 |                 -0.12 |                  nan |
|     17 | DK       | DK     | US       |                3.55 |             74.3  |         71.76 |         82.44 |          76.83 |        63.55 |           55.14 |             85.94 |             41.9  |         6.82 |             69.68 | swing              |                3.89 |                  1.43 |                  nan |
|     18 | BEN      | BEN    | US       |               15.25 |             74.2  |         69.07 |         71.4  |          77    |        79.08 |           87.79 |             73.17 |             72.25 |         3.2  |             67.86 | long               |                0.13 |                  0.75 |                  nan |
|     19 | CRGY     | CRGY   | US       |                4.53 |             74.01 |         79.32 |         69.31 |          70.9  |        77.12 |           72.46 |             63.53 |             96.94 |         6.1  |             69.23 | short              |               -3.33 |                nan    |                  nan |
|     20 | NIQ      | NIQ    | US       |                4.86 |             73.93 |         83.39 |         85.95 |          64.47 |        52.92 |           36.39 |             91.46 |             47.9  |         9.05 |             68.2  | swing              |              nan    |                 -0.49 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                    | EUROPE   |                3.34 |                  78.19 |                    76.17 |                 77.1  |              77.54 |                85.78 |                   14.22 |           81.41 |             58.01 |       0.79  |         nan |       nan |      nan    |       -86.2  |          2.31 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            2 | STNE      | StoneCo Ltd.                     | OTHER    |                1.93 |                  75.8  |                    72.89 |                 72.94 |              71.95 |                70.87 |                   29.13 |           85.05 |             46.21 |       0.609 |         nan |       nan |        1.62 |         4.18 |          3.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | 0QXR.IL   | Stellantis N.V.                  | OTHER    |               25.94 |                  73.55 |                    72.32 |                 72.16 |              72.43 |                67.93 |                   32.07 |           72.17 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|            4 | VOW3.DE   | Volkswagen AG                    | EUROPE   |               36.74 |                  80.65 |                    71.77 |                 68.92 |              74.56 |                65.68 |                   34.32 |           63.11 |             46.67 |       0.384 |         nan |       nan |       13.77 |         3.12 |          7.03 |        0.69 |                 nan |              nan |                  12 |                  0.63 |
|          nan | ADAM      | ADAM                             | US       |                0.76 |                  68.58 |                    71.4  |                 72.59 |              68.28 |                75.67 |                   24.33 |           89.8  |             52.87 |     nan     |         nan |       nan |      nan    |         7.88 |          5.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | SAP.DE    | SAP SE                           | EUROPE   |              214.06 |                  70.01 |                    71.36 |                 71.14 |              68.61 |                72.08 |                   27.92 |           83.91 |             52.32 |       0.042 |         nan |       nan |       18.1  |        22.16 |         27.76 |        1.88 |                 nan |              nan |                  12 |                  0.63 |
|            6 | 0Q2N.IL   | K+S Aktiengesellschaft           | OTHER    |                3.17 |                  72.06 |                    71    |                 70.13 |              72.34 |                73.45 |                   26.55 |           64.67 |            nan    |       0.234 |         nan |       nan |        1.54 |       nan    |          2.95 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | PARR      | Par Pacific Holdings, Inc.       | US       |                3.17 |                  71.87 |                    70.9  |                 72.07 |              70.36 |                69.15 |                   30.85 |           80.43 |             61.67 |       0.022 |         nan |       nan |        3.66 |         6.25 |          4.36 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | YALA      | Yalla Group Limited              | OTHER    |                0.73 |                  70.64 |                    70.74 |                 72.47 |              69.66 |                78.95 |                   21.05 |           87.83 |             45.88 |     nan     |         nan |       nan |        0.18 |         5.85 |          7.3  |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|            9 | 0P6O.IL   | Volkswagen AG                    | OTHER    |               40.59 |                  65.68 |                    70.51 |                 72.44 |              67.88 |                76.68 |                   23.32 |           82.07 |            nan    |       0.426 |         nan |       nan |        7.45 |       nan    |          2.64 |        0.68 |                 nan |              nan |                   9 |                  0.47 |
|           10 | IRWD      | Ironwood Pharmaceuticals, Inc.   | US       |                0.62 |                  64.69 |                    70.36 |                 73.8  |              68.38 |                79.46 |                   20.54 |           86.05 |             75.06 |       0.168 |         nan |       nan |        4.38 |         2.98 |          5.23 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | DDI       | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  61.63 |                    69.02 |                 72.24 |              65.1  |                81.85 |                   18.15 |           92.93 |             60.01 |       0.153 |         nan |       nan |        0.77 |         5.25 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | PRU       | PRU                              | US       |               35.52 |                  68.14 |                    68.8  |                 68.9  |              68.67 |                70.99 |                   29.01 |           69.38 |             68.31 |     nan     |         nan |       nan |      nan    |         8.11 |         11.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | NWL.MI    | NewPrinces S.p.A.                | EUROPE   |                0.65 |                  70.18 |                    68.77 |                 70.1  |              69.63 |                74.81 |                   25.19 |           75.34 |             56.42 |       1.026 |         nan |       nan |        5.16 |      -114.69 |          2.02 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BP        | BP                               | US       |               94.6  |                  58.1  |                    68.42 |                 71.83 |              64.3  |                80.59 |                   19.41 |           86.64 |             79.56 |     nan     |         nan |       nan |      nan    |         9.63 |         20.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | IHS       | IHS Holding Limited              | OTHER    |                2.42 |                  72.79 |                    68.37 |                 68.69 |              71.69 |                60.98 |                   39.02 |           57.31 |             83.06 |      -0.115 |         nan |       nan |        7.47 |        15.16 |          5.12 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           14 | VOLV-B.ST | AB Volvo (publ)                  | EUROPE   |               64.43 |                  71.22 |                    68.15 |                 66.76 |              68.61 |                62.07 |                   37.93 |           64.63 |             61.59 |       0.034 |         nan |       nan |       16.5  |        14.09 |         19.9  |        1.43 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS  | SHELL.AS                         | EUROPE   |              218.13 |                  67.02 |                    68.08 |                 68.84 |              64.4  |                71.36 |                   28.64 |           92.11 |             33    |     nan     |         nan |       nan |      nan    |         9.97 |         10.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN       | BEN                              | US       |               15.25 |                  57.26 |                    67.49 |                 70.83 |              63.11 |                80.9  |                   19.1  |           87.79 |             73.17 |     nan     |         nan |       nan |      nan    |        11.07 |         23.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM        | SM                               | US       |                7.27 |                  63.51 |                    67.41 |                 69.16 |              64.7  |                68.07 |                   31.93 |           81.15 |             67.26 |     nan     |         nan |       nan |      nan    |         4.76 |          6.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.34 |                  78.19 |                    76.17 |                 77.1  |              77.54 |                85.78 |                   14.22 |           81.41 |             58.01 |       0.79  |         nan |       nan |      nan    |       -86.2  |          2.31 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           10 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.62 |                  64.69 |                    70.36 |                 73.8  |              68.38 |                79.46 |                   20.54 |           86.05 |             75.06 |       0.168 |         nan |       nan |        4.38 |         2.98 |          5.23 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | STNE     | StoneCo Ltd.                     | OTHER    |                1.93 |                  75.8  |                    72.89 |                 72.94 |              71.95 |                70.87 |                   29.13 |           85.05 |             46.21 |       0.609 |         nan |       nan |        1.62 |         4.18 |          3.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ADAM     | ADAM                             | US       |                0.76 |                  68.58 |                    71.4  |                 72.59 |              68.28 |                75.67 |                   24.33 |           89.8  |             52.87 |     nan     |         nan |       nan |      nan    |         7.88 |          5.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | YALA     | Yalla Group Limited              | OTHER    |                0.73 |                  70.64 |                    70.74 |                 72.47 |              69.66 |                78.95 |                   21.05 |           87.83 |             45.88 |     nan     |         nan |       nan |        0.18 |         5.85 |          7.3  |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|            9 | 0P6O.IL  | Volkswagen AG                    | OTHER    |               40.59 |                  65.68 |                    70.51 |                 72.44 |              67.88 |                76.68 |                   23.32 |           82.07 |            nan    |       0.426 |         nan |       nan |        7.45 |       nan    |          2.64 |        0.68 |                 nan |              nan |                   9 |                  0.47 |
|           11 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  61.63 |                    69.02 |                 72.24 |              65.1  |                81.85 |                   18.15 |           92.93 |             60.01 |       0.153 |         nan |       nan |        0.77 |         5.25 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | 0QXR.IL  | Stellantis N.V.                  | OTHER    |               25.94 |                  73.55 |                    72.32 |                 72.16 |              72.43 |                67.93 |                   32.07 |           72.17 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|            7 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.17 |                  71.87 |                    70.9  |                 72.07 |              70.36 |                69.15 |                   30.85 |           80.43 |             61.67 |       0.022 |         nan |       nan |        3.66 |         6.25 |          4.36 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                               | US       |               94.6  |                  58.1  |                    68.42 |                 71.83 |              64.3  |                80.59 |                   19.41 |           86.64 |             79.56 |     nan     |         nan |       nan |      nan    |         9.63 |         20.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | SAP.DE   | SAP SE                           | EUROPE   |              214.06 |                  70.01 |                    71.36 |                 71.14 |              68.61 |                72.08 |                   27.92 |           83.91 |             52.32 |       0.042 |         nan |       nan |       18.1  |        22.16 |         27.76 |        1.88 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BEN      | BEN                              | US       |               15.25 |                  57.26 |                    67.49 |                 70.83 |              63.11 |                80.9  |                   19.1  |           87.79 |             73.17 |     nan     |         nan |       nan |      nan    |        11.07 |         23.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | 0Q2N.IL  | K+S Aktiengesellschaft           | OTHER    |                3.17 |                  72.06 |                    71    |                 70.13 |              72.34 |                73.45 |                   26.55 |           64.67 |            nan    |       0.234 |         nan |       nan |        1.54 |       nan    |          2.95 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | NWL.MI   | NewPrinces S.p.A.                | EUROPE   |                0.65 |                  70.18 |                    68.77 |                 70.1  |              69.63 |                74.81 |                   25.19 |           75.34 |             56.42 |       1.026 |         nan |       nan |        5.16 |      -114.69 |          2.02 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SM       | SM                               | US       |                7.27 |                  63.51 |                    67.41 |                 69.16 |              64.7  |                68.07 |                   31.93 |           81.15 |             67.26 |     nan     |         nan |       nan |      nan    |         4.76 |          6.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           15 | SDF.DE   | K+S Aktiengesellschaft           | EUROPE   |                2.88 |                  64.27 |                    67    |                 69.1  |              64.97 |                72.18 |                   27.82 |           83.18 |             57.05 |       0.118 |         nan |       nan |        2.03 |        16.3  |          2.72 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|            4 | VOW3.DE  | Volkswagen AG                    | EUROPE   |               36.74 |                  80.65 |                    71.77 |                 68.92 |              74.56 |                65.68 |                   34.32 |           63.11 |             46.67 |       0.384 |         nan |       nan |       13.77 |         3.12 |          7.03 |        0.69 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PRU      | PRU                              | US       |               35.52 |                  68.14 |                    68.8  |                 68.9  |              68.67 |                70.99 |                   29.01 |           69.38 |             68.31 |     nan     |         nan |       nan |      nan    |         8.11 |         11.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              218.13 |                  67.02 |                    68.08 |                 68.84 |              64.4  |                71.36 |                   28.64 |           92.11 |             33    |     nan     |         nan |       nan |      nan    |         9.97 |         10.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | IHS      | IHS Holding Limited              | OTHER    |                2.42 |                  72.79 |                    68.37 |                 68.69 |              71.69 |                60.98 |                   39.02 |           57.31 |             83.06 |      -0.115 |         nan |       nan |        7.47 |        15.16 |          5.12 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:--------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | NTAP     | NTAP                | US       |               31.52 |                     0.09 |    -0.08 |      0.07 |                  70.76 |                        76.38 |         58.72 |         75.92 |          77.43 |        69.84 |           88.33 |             67.6  |         6.17 |
|               2 | DK       | DK                  | US       |                3.55 |                     0.05 |    -0.01 |      0.08 |                  73.09 |                        76.1  |         71.76 |         82.44 |          76.83 |        63.55 |           55.14 |             85.94 |         6.82 |
|               3 | HPE      | HPE                 | US       |               60.65 |                     0.11 |    -0.04 |      0.17 |                  50.64 |                        74.61 |         64.84 |         81.34 |          81.64 |        73.78 |           70.63 |             81.48 |         6.82 |
|               4 | SM       | SM                  | US       |                7.27 |                     0.05 |     0.01 |      0.2  |                  67.46 |                        74.54 |         76.2  |         73.51 |          76.35 |        81.43 |           81.15 |             67.26 |         7.04 |
|               5 | TNK      | Teekay Tankers Ltd. | OTHER    |                2.68 |                     0.02 |     0.01 |      0.18 |                  47.06 |                        73.49 |         77.29 |         72.13 |          71.87 |        68.6  |           81.59 |             76.46 |         5.03 |
|               6 | PLTR     | PLTR                | US       |              355.73 |                     0.04 |     0.01 |      0.4  |                  59.57 |                        73.24 |         77.59 |         65.42 |          58.08 |        54.9  |           90.49 |             49.41 |         8.45 |
|               7 | DELL     | DELL                | US       |              250.02 |                     0.09 |    -0.04 |      0.15 |                  61.71 |                        73.01 |         63.41 |         78.14 |          76.9  |        65.44 |           70.65 |             70.34 |         7.73 |
|               8 | WBI      | WBI                 | US       |                3.36 |                     0.07 |    -0    |     -0.01 |                  62.29 |                        72.96 |         48.04 |         62.18 |          72.95 |        71.27 |           94.76 |             90.53 |         6.26 |
|               9 | NTNX     | NTNX                | US       |               15.39 |                     0.02 |     0.01 |      0.13 |                  47.84 |                        72.27 |         69.39 |         76.92 |          67.58 |        57.03 |           77.38 |             74.41 |         6.96 |
|              10 | APA      | APA                 | US       |               12.42 |                     0.07 |    -0.02 |      0.18 |                  69.51 |                        71.94 |         72.22 |         70.16 |          75.54 |        76.54 |           76.2  |             67.74 |         5.53 |
|              11 | REP.MC   | REP.MC              | EUROPE   |               29.27 |                     0.04 |    -0.02 |      0.06 |                  70.22 |                        71.8  |         63.15 |         76.7  |          76.67 |        72.7  |           58.81 |             74.38 |         3.85 |
|              12 | VET      | VET                 | US       |                1.6  |                     0.05 |    -0    |      0.18 |                  68.36 |                        71.65 |         71.91 |         64.35 |          67.7  |        66.49 |           59.86 |             89.81 |         6.67 |
|              13 | BAX      | BAX                 | US       |               11.65 |                     0.07 |     0.01 |      0.08 |                  55.96 |                        71.51 |         69.32 |         74.42 |          70.33 |        70.61 |           77.18 |             69.76 |         6.04 |
|              14 | SNOW     | SNOW                | US       |               94.17 |                     0.06 |    -0.03 |      0.17 |                  74.97 |                        71.25 |         66.88 |         78.68 |          64.44 |        44.71 |           41.74 |             82.13 |         8.9  |
|              15 | BILL     | BILL                | US       |                4.07 |                     0.07 |    -0.03 |      0.03 |                  70.11 |                        71.15 |         59.72 |         71.69 |          66.78 |        67.61 |           55.17 |             91.7  |         7.04 |
|              16 | CVE      | CVE                 | US       |               48.62 |                     0.07 |    -0.05 |      0.11 |                  79.87 |                        70.97 |         63.91 |         66.71 |          73.69 |        73.47 |           77.21 |             67.94 |         4.8  |
|              17 | BP       | BP                  | US       |               94.6  |                     0.05 |    -0.01 |      0.04 |                  71.75 |                        70.88 |         60.09 |         61.71 |          70.46 |        76.38 |           86.64 |             79.56 |         4.1  |
|              18 | ANGX     | ANGX                | US       |                0.73 |                     0.06 |    -0.06 |      0.12 |                  86.66 |                        70.21 |         70.08 |         74.15 |          63.32 |        58.31 |           58.59 |             56.14 |         9.48 |
|              19 | ADAM     | ADAM                | US       |                0.76 |                     0.04 |    -0.02 |      0.13 |                  67.33 |                        69.84 |         67.69 |         67.25 |          74.71 |        82.8  |           89.8  |             52.87 |         3.06 |
|              20 | QNST     | QNST                | US       |                0.99 |                     0.09 |    -0.03 |      0.26 |                  60.18 |                        69.8  |         74.93 |         75.07 |          70.21 |        71.86 |           84.07 |             42.84 |         7.95 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4422.47 |             58.44 |         56.11 |         53.51 |          60.76 |        65.53 |           94.07 |             66.14 |             33.41 |         8.5  |             89.49 | long               |                2.57 |                 -0.14 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.72 |             53.46 |         36.25 |         51.6  |          55.31 |        60.56 |           54.32 |             52.09 |             74.03 |         8.5  |             85.47 | long               |               -1.27 |                  0.21 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.1  |             51.75 |         50.88 |         43.44 |          52.62 |        63.11 |           82.39 |             42.97 |             54.27 |         3.85 |             75.81 | long               |               -0.1  |                  0.57 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1454.55 |             47.32 |         31.36 |         39.79 |          54.86 |        58.93 |           81.17 |             58.59 |             33.73 |         6.17 |             89.83 | long               |               -0.95 |                 -0.53 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             46.09 |         42.92 |         41.66 |          49.27 |        62.82 |           62.68 |             53.66 |             89.63 |         4.32 |             82.14 | long               |                0.79 |                  0.31 |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.                              | US       |                3.04 |             42.91 |         30.56 |         37.76 |          48.06 |        63.65 |           69.38 |             50.07 |             85.43 |         8.5  |             87.88 | long               |               -3.04 |                nan    |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.88 |             36.45 |         30.19 |         32.36 |          40.54 |        52.84 |           49.02 |             44.4  |             78.34 |         8.5  |             78.58 | long               |               -1.13 |                 -0.38 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.7  |             35.74 |         35.42 |         30.24 |          36.06 |        41.41 |           42.43 |             68.13 |             44.52 |         8.5  |             77.1  | long               |               -4.5  |                 -0.62 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.83 |             30.53 |         28.5  |         19.36 |          32.55 |        44.13 |           61.41 |             17.83 |             41.11 |         8.98 |             78.45 | long               |               -1.77 |                 -0.74 |                  nan |
|    nan | LI       | Li Auto Inc.                                         | OTHER    |               10.3  |             26.76 |         31.4  |         23.32 |          25.26 |        28.26 |           30.65 |             37.86 |             27.29 |         8.5  |             76.54 | short              |              nan    |                nan    |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     43 | TKA.DE   | TKA.DE                         | EUROPE   |                8.53 |             71.09 |         77.17 |         70.74 |          70.9  |        71.27 |          nan    |             60.29 |             65.16 |         6.69 |             66.84 | short              |                2.57 |                  3.89 |                  nan |
|    102 | KURA     | KURA                           | US       |                1.04 |             66.92 |         85.48 |         75.1  |          58.73 |        44.4  |           49.08 |             66.55 |              3.86 |         7.21 |             66.84 | short              |                6.04 |                  3.7  |                  nan |
|    642 | CYH      | Community Health Systems, Inc. | US       |                0.36 |             41.11 |         44.32 |         35.49 |          37.9  |        48.56 |           39.82 |             24.4  |             76.37 |         7.74 |             81.72 | long               |               -5.15 |                  3.43 |                  nan |
|    648 | LKFT     | Lakefront Biotherapeutics NV   | OTHER    |                1.67 |             40.32 |         59.2  |         40.06 |          37.29 |        40.58 |           39.03 |             46.04 |             42.41 |         5.09 |             76.99 | short              |                0.32 |                  3.1  |                  nan |
|    196 | HOOD     | HOOD                           | US       |               86.37 |             62.69 |         74    |         68.28 |          57.09 |        48.18 |           64.11 |             57    |             11.65 |         8.74 |             68.2  | short              |                0.52 |                  3.1  |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    340 | DAR      | DAR                                  | US       |                8.46 |             57.58 |         54.26 |         53.45 |          60.9  |        65.3  |           63.34 |             40.48 |             71.57 |         3.99 |             68.89 | long               |              -10.78 |                 -3.75 |                  nan |
|    700 | STLAP.PA | Stellantis N.V.                      | EUROPE   |               16.91 |             28.12 |         28.67 |         18.25 |          27.57 |        35.37 |           46.49 |             37.12 |             36.84 |         6.21 |             84.82 | long               |               -8.73 |                 -2.86 |                  nan |
|    572 | ZIP      | ZIP                                  | US       |                0.31 |             46.73 |         46.87 |         60.6  |          46.59 |        30.85 |           20.03 |             53.05 |             14.43 |         9.5  |             67.75 | swing              |               -5.03 |                 -2.84 |                  nan |
|    376 | ASA      | ASA Gold and Precious Metals Limited | US       |                1.04 |             56.28 |         71.89 |         46.57 |          51.36 |        61.19 |           63.16 |            nan    |             57.41 |         5.72 |             61.6  | short              |               -4.16 |                 -2.81 |                  nan |
|    476 | CERT     | CERT                                 | US       |                1.06 |             52.08 |         56.22 |         62.94 |          47.94 |        39.97 |           20.35 |             67.61 |             44.58 |         8.62 |             69.68 | swing              |                1.36 |                 -2.72 |                  nan |

## Duplicate-security checks

- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)

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
- Excluded by hard/data filters: **289**
- Event watch (otherwise eligible): **10**
- Final eligible: **701**
- Eligible change vs previous stored run: **-3**

Top exclusion categories:
- liquidity: 232
- price: 166
- market_cap: 163
- price_history: 19
- data_confidence: 13
- duplicate_listing: 3
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| HPE | 4 |  | 3 |  | 2 | main,pullback |
| SM | 10 |  | 4 |  | 2 | main,pullback |
| BION.SW | 23 | 1 |  | 1 | 1 | value,quality_value |
| PARR | 24 | 7 |  | 8 | 1 | value,quality_value |
| IRWD | 37 | 10 |  | 2 | 1 | value,quality_value |
| 0Q2N.IL | 167 | 6 |  | 10 | 1 | value,quality_value |
| SAP.DE | 201 | 5 |  | 9 | 1 | value,quality_value |
| 0QXR.IL | 487 | 3 |  | 7 | 1 | value,quality_value |
| YALA | 511 | 8 |  | 4 | 1 | value,quality_value |
| STNE | 614 | 2 |  | 3 | 1 | value,quality_value |
| 0P6O.IL | 630 | 9 |  | 5 | 1 | value,quality_value |
| AVAH | 1 |  |  |  | 1 | main |
| HALO | 2 |  |  |  | 1 | main |
| KIN.BR | 3 |  |  |  | 1 | main |
| GH | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (AVAH, HALO, KIN.BR, SSRM, ERO, PR, WT)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 72.09 | 70.18 | 76.55 | 75.34 | 56.42 | 74.81 | 43.46 |
| 2 | 0P6O.IL | value+pullback | 68.40 | 65.68 | 64.21 | 82.07 |  | 76.68 | 42.74 |
| 3 | VOW3.DE | value+pullback | 67.61 | 80.65 | 64.57 | 63.11 | 46.67 | 65.68 | 40.31 |
| 4 | MFA | value+pullback | 61.91 | 57.72 | 68.13 | 77.94 | 33.79 | 62.47 | 40.01 |
| 5 | PBR-A | value+pullback | 61.25 | 74.06 | 55.83 | 54.53 | 69.90 | 49.51 | 58.69 |
| 6 | 1VOW3.MI | value+pullback | 60.98 | 68.04 | 58.23 | 63.11 | 36.64 | 64.39 | 38.76 |
| 7 | INVA | value+pullback | 60.94 | 58.54 | 51.33 | 79.49 | 35.88 | 75.18 | 44.88 |
| 8 | VOW.DE | value+pullback | 59.63 | 66.09 | 57.41 | 63.11 | 33.31 | 63.27 | 37.35 |
| 9 | PBR | value+pullback | 58.80 | 61.62 | 66.43 | 54.53 | 59.94 | 47.65 | 56.35 |
| 10 | NOKIA.HE | value+pullback | 58.69 | 63.45 | 60.06 | 54.78 | 40.48 | 61.85 | 52.67 |
| 11 | BION.SW | value | 58.62 | 78.19 | 30.95 | 81.41 | 58.01 | 85.78 | 73.16 |
| 12 | ACCO | value+pullback | 57.99 | 72.48 | 53.78 | 44.00 | 54.61 | 53.69 | 53.05 |
| 13 | UNIT | value+pullback | 57.92 | 80.26 | 47.31 | 67.37 | 28.83 | 45.14 | 46.25 |
| 14 | ALL-PH | value+pullback | 57.62 | 60.86 | 50.55 | 69.58 | 42.43 | 60.25 | 46.41 |
| 15 | AAPL | value+pullback | 56.83 | 60.17 | 53.71 | 63.89 | 49.34 | 54.18 | 50.54 |
| 16 | KYN | value+pullback | 56.82 | 56.87 | 57.00 | 55.06 | 55.41 | 58.54 | 53.46 |
| 17 | TV | value+pullback | 56.63 | 65.08 | 63.47 | 44.82 | 30.54 | 57.30 | 38.00 |
| 18 | IRWD | value | 55.71 | 64.69 | 35.57 | 86.05 | 75.06 | 79.46 | 71.78 |
| 19 | WBI | pullback | 55.62 | 42.02 | 62.29 | 94.76 | 90.53 | 83.91 | 66.73 |
| 20 | ORCL | value+pullback | 55.39 | 69.90 | 55.44 | 47.06 | 60.00 | 37.51 | 41.56 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 68.7 | 3 / 7 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 68.7 | 9 / 16 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 69.1 | 23 / 27 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=5, large_20_100b=1
