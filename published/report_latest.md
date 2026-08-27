# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-27

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

- **EUROPE:** 89.0/100
- **OTHER:** 72.0/100
- **US:** 84.2/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | GH       | GH                         | US       |               19.65 |             80.73 |         80.75 |         83.96 |          80.7  |        73.84 |           61.76 |             80.24 |            nan    |         6.45 |             64.91 | swing              |                3.59 |                nan    |                  nan |
|      2 | CAKE     | CAKE                       | US       |                4.92 |             80.2  |         84.54 |         83.01 |          77.39 |        67.75 |           87.57 |             64.26 |             21    |         5.61 |             67.18 | short              |                6.24 |                  1.19 |                  nan |
|      3 | DK       | DK                         | US       |                3.72 |             79.23 |         81.7  |         85.23 |          76.76 |        62.47 |           55.6  |             84.9  |             36.52 |         6.85 |             69.68 | swing              |                5.42 |                  0.22 |                  nan |
|      4 | HPE      | HPE                        | US       |               62.64 |             79.2  |         76.82 |         83.94 |          81.58 |        72.54 |           69.9  |             81.62 |             54.96 |         6.78 |             67.86 | swing              |                2.32 |                  0.55 |                  nan |
|      5 | AVAH     | AVAH                       | US       |                2.55 |             79.19 |         85.66 |         83.14 |          75.23 |        72.2  |           94.13 |             53.36 |             40.28 |         7.32 |             68.66 | short              |                0.95 |                  2.13 |                  nan |
|      6 | HALO     | HALO                       | US       |               10.41 |             77.65 |         81.75 |         80.9  |          74.41 |        73.65 |           85.84 |             56.84 |             57.84 |         5.53 |             68.66 | short              |                0.44 |                nan    |                  nan |
|      7 | WT       | WT                         | US       |                3.21 |             77.43 |         84.79 |         81.28 |          73.59 |        65.64 |           74.73 |             74.89 |             31.7  |         5.31 |             69.68 | short              |                1.53 |                  0.74 |                  nan |
|      8 | KIN.BR   | KIN.BR                     | EUROPE   |                1.22 |             77.34 |         79.66 |         80.73 |          75.02 |        67.12 |           91.69 |             65.93 |             23.4  |         4.01 |             69.68 | swing              |                0.21 |                  1.25 |                  nan |
|      9 | SSRM     | SSRM                       | US       |                6.65 |             77.28 |         86.52 |         78.14 |          73.92 |        76.43 |           69.49 |             73.91 |             82    |         6.97 |             68.32 | short              |                1.08 |                  0.7  |                  nan |
|     10 | ERO      | ERO                        | US       |                3.51 |             76.73 |         88.59 |         73.94 |          72.36 |        79.51 |           84.51 |             49.14 |             78.87 |         7.54 |             69.68 | short              |                0.84 |                 -0.41 |                  nan |
|     11 | TALO     | TALO                       | US       |                2.39 |             76.68 |         75.5  |         77.85 |          78.97 |        74.97 |           69.19 |             93.92 |             69.32 |         5.4  |             69.68 | medium             |              nan    |                  0.19 |                  nan |
|     12 | DELL     | DELL                       | US       |              256.7  |             76.45 |         76.19 |         80.02 |          76.7  |        64.88 |           71.33 |             68.41 |             30.07 |         7.7  |             68.77 | swing              |                5.78 |                  0.48 |                  nan |
|     13 | PAGP     | PAGP                       | US       |                5.61 |             76.37 |         77.95 |         75.81 |          76.93 |        74.24 |           83.82 |             76.54 |             54.09 |         1.76 |             66.7  | short              |              nan    |                nan    |                  nan |
|     14 | SM       | SM                         | US       |                7.2  |             76.07 |         70.68 |         74.09 |          78.05 |        82.05 |           81.42 |             66.52 |             96.49 |         6.96 |             68.66 | long               |                0    |                  0.18 |                  nan |
|     15 | GTE      | GTE                        | US       |                0.31 |             75.03 |         87.24 |         77.86 |          72.19 |        68.52 |           54.26 |             63.87 |             76.01 |         8.07 |             69.68 | short              |              nan    |                nan    |                  nan |
|     16 | NIQ      | NIQ                        | US       |                4.73 |             74.57 |         84.28 |         84.86 |          64.85 |        53.38 |           37.91 |             91.52 |             45.48 |         9.02 |             68.2  | swing              |                1.08 |                nan    |                  nan |
|     17 | TGB      | TGB                        | US       |                2.89 |             74.43 |         88.03 |         77.34 |          71.51 |        68.16 |           56.91 |             86.25 |             57.87 |         7.62 |             69.23 | short              |               -0.34 |                 -0.21 |                  nan |
|     18 | BEN      | BEN                        | US       |               15.24 |             74.4  |         71.75 |         71.82 |          76.98 |        78.57 |           87.61 |             72.87 |             69.84 |         3.08 |             67.86 | long               |                0.76 |                  0.5  |                  nan |
|     19 | CRGY     | CRGY                       | US       |                4.51 |             74.34 |         75.49 |         71.29 |          73.18 |        78.35 |           72.92 |             63.21 |             96.3  |         5.95 |             69.23 | long               |                1.48 |                 -0.74 |                  nan |
|     20 | PARR     | Par Pacific Holdings, Inc. | US       |                3.25 |             74.2  |         53.89 |         72.8  |          78.79 |        75.61 |           80.43 |             60.78 |             65.67 |         6.86 |             85.72 | medium             |               -0.93 |                 -0.84 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                    | EUROPE   |                3.3  |                  78.04 |                    76.54 |                 77.73 |              77.54 |                86.53 |                   13.47 |           83.85 |             57.77 |       0.797 |         nan |       nan |      nan    |       -85.44 |          2.29 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            2 | STNE      | StoneCo Ltd.                     | OTHER    |                1.92 |                  76.86 |                    72.59 |                 72.09 |              72.41 |                69.62 |                   30.38 |           80.98 |             45.43 |       0.614 |         nan |       nan |        1.62 |         4.15 |          3.68 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ADAM      | ADAM                             | US       |                0.75 |                  67.86 |                    71.13 |                 72.46 |              67.91 |                76.13 |                   23.87 |           89.93 |             53.43 |     nan     |         nan |       nan |      nan    |         7.83 |          5.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | VOLV-B.ST | AB Volvo (publ)                  | EUROPE   |               64.48 |                  79.76 |                    71.02 |                 67.88 |              74.09 |                58.95 |                   41.05 |           56.25 |             60.58 |       0.034 |         nan |       nan |       16.52 |        14.11 |         19.94 |        1.46 |                 nan |              nan |                  12 |                  0.63 |
|            4 | 0Q2N.IL   | K+S Aktiengesellschaft           | OTHER    |                3.19 |                  72.93 |                    70.5  |                 69.1  |              72.55 |                71.02 |                   28.98 |           61.05 |            nan    |       0.232 |         nan |       nan |        1.54 |       nan    |          2.97 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | IRWD      | Ironwood Pharmaceuticals, Inc.   | US       |                0.61 |                  61.96 |                    69.47 |                 73.27 |              66.98 |                82.72 |                   17.28 |           87.02 |             74.85 |       0.172 |         nan |       nan |        4.31 |         2.86 |          5.43 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | DDI       | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  62.1  |                    69.23 |                 72.37 |              65.43 |                81.86 |                   18.14 |           92.69 |             59.8  |       0.154 |         nan |       nan |        0.76 |         5.24 |          5.07 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | ACCO      | Acco Brands Corporation          | US       |                0.33 |                  74.12 |                    69.19 |                 68.9  |              70.35 |                64.19 |                   35.81 |           71.09 |             54.28 |       0.106 |         nan |       nan |        7.98 |         4.35 |          6.76 |        0.81 |                 nan |              nan |                  12 |                  0.63 |
|            8 | DXC       | DXC Technology Company           | US       |                1.44 |                  84.78 |                    68.95 |                 63.88 |              73.65 |                51.59 |                   48.41 |           52.01 |             33.28 |       0.52  |         nan |       nan |        3.05 |         3.57 |         14.65 |        0.49 |                 nan |              nan |                  10 |                  0.53 |
|            9 | PARR      | Par Pacific Holdings, Inc.       | US       |                3.25 |                  68.27 |                    68.8  |                 70.29 |              67.64 |                68.95 |                   31.05 |           80.43 |             60.78 |       0.022 |         nan |       nan |        3.73 |         6.41 |          4.33 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                         | EUROPE   |              217.07 |                  67.14 |                    68.61 |                 69.53 |              64.53 |                72.48 |                   27.52 |           94.88 |             31.48 |     nan     |         nan |       nan |      nan    |         9.93 |         10.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | NWL.MI    | NewPrinces S.p.A.                | EUROPE   |                0.65 |                  67.98 |                    68.26 |                 70.27 |              68.05 |                74.71 |                   25.29 |           79.95 |             56.56 |       1.023 |         nan |       nan |        5.17 |      -115.05 |          2.02 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | NLY       | NLY                              | US       |               14.76 |                  68.22 |                    68.17 |                 68.5  |              64.92 |                71    |                   29    |           90.46 |             30.23 |     nan     |         nan |       nan |      nan    |         7.35 |          5.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | IHS       | IHS Holding Limited              | OTHER    |                2.42 |                  71.93 |                    67.77 |                 68.02 |              71.17 |                61.72 |                   38.28 |           55.97 |             82.71 |      -0.115 |         nan |       nan |        7.48 |        15.2  |          5.13 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP        | BP                               | US       |               93.75 |                  56.71 |                    67.27 |                 70.75 |              62.92 |                80.05 |                   19.95 |           86.83 |             76.78 |     nan     |         nan |       nan |      nan    |         9.58 |         20.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | UNIT      | Uniti Group Inc.                 | US       |                2.11 |                  80.26 |                    66.87 |                 63.93 |              68.76 |                45.07 |                   54.93 |           67.04 |             28.62 |      -0.105 |         nan |       nan |        9.13 |       -14.31 |          2.64 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BEN       | BEN                              | US       |               15.24 |                  56.06 |                    66.74 |                 70.2  |              62.22 |                80.95 |                   19.05 |           87.61 |             72.87 |     nan     |         nan |       nan |      nan    |        11.06 |         23.82 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM        | SM                               | US       |                7.2  |                  62.26 |                    66.66 |                 68.57 |              63.74 |                68.12 |                   31.88 |           81.42 |             66.52 |     nan     |         nan |       nan |      nan    |         4.72 |          6.33 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | NVDA      | NVIDIA Corporation               | US       |             4349.71 |                  55.07 |                    66.48 |                 69.14 |              59.92 |                76.44 |                   23.56 |           92.54 |             65.09 |       0.009 |         nan |       nan |       30.41 |        15.97 |         32.56 |        0.59 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT       | DHT                              | US       |                2.53 |                  62.26 |                    66.4  |                 68.17 |              62.4  |                71.27 |                   28.73 |           89.35 |             47.49 |     nan     |         nan |       nan |      nan    |         9.74 |          6.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                    | EUROPE   |                3.3  |                  78.04 |                    76.54 |                 77.73 |              77.54 |                86.53 |                   13.47 |           83.85 |             57.77 |       0.797 |         nan |       nan |      nan    |       -85.44 |          2.29 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | IRWD      | Ironwood Pharmaceuticals, Inc.   | US       |                0.61 |                  61.96 |                    69.47 |                 73.27 |              66.98 |                82.72 |                   17.28 |           87.02 |             74.85 |       0.172 |         nan |       nan |        4.31 |         2.86 |          5.43 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ADAM      | ADAM                             | US       |                0.75 |                  67.86 |                    71.13 |                 72.46 |              67.91 |                76.13 |                   23.87 |           89.93 |             53.43 |     nan     |         nan |       nan |      nan    |         7.83 |          5.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | DDI       | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  62.1  |                    69.23 |                 72.37 |              65.43 |                81.86 |                   18.14 |           92.69 |             59.8  |       0.154 |         nan |       nan |        0.76 |         5.24 |          5.07 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | STNE      | StoneCo Ltd.                     | OTHER    |                1.92 |                  76.86 |                    72.59 |                 72.09 |              72.41 |                69.62 |                   30.38 |           80.98 |             45.43 |       0.614 |         nan |       nan |        1.62 |         4.15 |          3.68 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP        | BP                               | US       |               93.75 |                  56.71 |                    67.27 |                 70.75 |              62.92 |                80.05 |                   19.95 |           86.83 |             76.78 |     nan     |         nan |       nan |      nan    |         9.58 |         20.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | PARR      | Par Pacific Holdings, Inc.       | US       |                3.25 |                  68.27 |                    68.8  |                 70.29 |              67.64 |                68.95 |                   31.05 |           80.43 |             60.78 |       0.022 |         nan |       nan |        3.73 |         6.41 |          4.33 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | NWL.MI    | NewPrinces S.p.A.                | EUROPE   |                0.65 |                  67.98 |                    68.26 |                 70.27 |              68.05 |                74.71 |                   25.29 |           79.95 |             56.56 |       1.023 |         nan |       nan |        5.17 |      -115.05 |          2.02 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BEN       | BEN                              | US       |               15.24 |                  56.06 |                    66.74 |                 70.2  |              62.22 |                80.95 |                   19.05 |           87.61 |             72.87 |     nan     |         nan |       nan |      nan    |        11.06 |         23.82 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                         | EUROPE   |              217.07 |                  67.14 |                    68.61 |                 69.53 |              64.53 |                72.48 |                   27.52 |           94.88 |             31.48 |     nan     |         nan |       nan |      nan    |         9.93 |         10.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | NVDA      | NVIDIA Corporation               | US       |             4349.71 |                  55.07 |                    66.48 |                 69.14 |              59.92 |                76.44 |                   23.56 |           92.54 |             65.09 |       0.009 |         nan |       nan |       30.41 |        15.97 |         32.56 |        0.59 |                 nan |              nan |                  12 |                  0.63 |
|            4 | 0Q2N.IL   | K+S Aktiengesellschaft           | OTHER    |                3.19 |                  72.93 |                    70.5  |                 69.1  |              72.55 |                71.02 |                   28.98 |           61.05 |            nan    |       0.232 |         nan |       nan |        1.54 |       nan    |          2.97 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | ACCO      | Acco Brands Corporation          | US       |                0.33 |                  74.12 |                    69.19 |                 68.9  |              70.35 |                64.19 |                   35.81 |           71.09 |             54.28 |       0.106 |         nan |       nan |        7.98 |         4.35 |          6.76 |        0.81 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM        | SM                               | US       |                7.2  |                  62.26 |                    66.66 |                 68.57 |              63.74 |                68.12 |                   31.88 |           81.42 |             66.52 |     nan     |         nan |       nan |      nan    |         4.72 |          6.33 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY       | NLY                              | US       |               14.76 |                  68.22 |                    68.17 |                 68.5  |              64.92 |                71    |                   29    |           90.46 |             30.23 |     nan     |         nan |       nan |      nan    |         7.35 |          5.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                              | US       |                2.53 |                  62.26 |                    66.4  |                 68.17 |              62.4  |                71.27 |                   28.73 |           89.35 |             47.49 |     nan     |         nan |       nan |      nan    |         9.74 |          6.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAGP      | PAGP                             | US       |                5.61 |                  51.66 |                    64.28 |                 68.11 |              59.76 |                82.85 |                   17.15 |           83.82 |             76.54 |     nan     |         nan |       nan |      nan    |        13.08 |         78.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | IHS       | IHS Holding Limited              | OTHER    |                2.42 |                  71.93 |                    67.77 |                 68.02 |              71.17 |                61.72 |                   38.28 |           55.97 |             82.71 |      -0.115 |         nan |       nan |        7.48 |        15.2  |          5.13 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR   | BIRG.IR                          | EUROPE   |               17.94 |                  56.37 |                    64.97 |                 67.99 |              59.09 |                78.36 |                   21.64 |           97.04 |             44.03 |     nan     |         nan |       nan |      nan    |        10.41 |         14.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | VOLV-B.ST | AB Volvo (publ)                  | EUROPE   |               64.48 |                  79.76 |                    71.02 |                 67.88 |              74.09 |                58.95 |                   41.05 |           56.25 |             60.58 |       0.034 |         nan |       nan |       16.52 |        14.11 |         19.94 |        1.46 |                 nan |              nan |                  12 |                  0.63 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:--------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | TALO     | TALO                | US       |                2.39 |                     0.06 |    -0.03 |      0.17 |                  76.6  |                        78.34 |         75.5  |         77.85 |          78.97 |        74.97 |           69.19 |             93.92 |         5.4  |
|               2 | NTNX     | NTNX                | US       |               15.14 |                     0.04 |    -0    |      0.1  |                  60.24 |                        76.82 |         68.15 |         79.35 |          71.03 |        60.55 |           77.55 |             83.99 |         6.93 |
|               3 | SYENS.BR | SYENS.BR            | EUROPE   |                8.16 |                     0.03 |    -0.01 |      0.12 |                  57.35 |                        74.95 |         73.3  |         77.2  |          68.46 |        60.21 |           71.67 |             89.44 |         5.15 |
|               4 | FIGR     | FIGR                | US       |                7.13 |                     0.1  |     0.01 |      0.48 |                  41.97 |                        74.82 |         83.63 |         58.55 |          56.52 |        59.7  |           91.28 |             56.35 |         9.2  |
|               5 | SM       | SM                  | US       |                7.2  |                     0.06 |    -0.02 |      0.11 |                  73.68 |                        74.36 |         70.68 |         74.09 |          78.05 |        82.05 |           81.42 |             66.52 |         6.96 |
|               6 | HALO     | HALO                | US       |               10.41 |                     0.02 |    -0.01 |      0.29 |                  51.1  |                        74.23 |         81.75 |         80.9  |          74.41 |        73.65 |           85.84 |             56.84 |         5.53 |
|               7 | BAX      | BAX                 | US       |               11.74 |                     0.07 |    -0.01 |      0.07 |                  66.02 |                        73.82 |         68.09 |         75.67 |          71.19 |        70.27 |           77.79 |             70.14 |         5.96 |
|               8 | WBI      | WBI                 | US       |                3.34 |                     0.08 |    -0    |     -0.03 |                  58.86 |                        72.84 |         45.35 |         63.59 |          73.61 |        70.72 |           93.53 |             90.08 |         6.17 |
|               9 | CCC      | CCC                 | US       |                3.68 |                     0.03 |    -0.02 |      0.21 |                  58.78 |                        72.22 |         73.37 |         72.01 |          64.59 |        69.12 |           87.27 |             61.73 |         7.95 |
|              10 | CRGY     | CRGY                | US       |                4.51 |                     0.05 |    -0    |      0.22 |                  68.47 |                        72.08 |         75.49 |         71.29 |          73.18 |        78.35 |           72.92 |             63.21 |         5.95 |
|              11 | JHX      | JHX                 | US       |               14.99 |                     0.03 |    -0    |      0.15 |                  55.79 |                        71.79 |         74.11 |         77.36 |          69.38 |        62.58 |           59.57 |             85.51 |         5.82 |
|              12 | VWS.CO   | VWS.CO              | EUROPE   |               27.26 |                     0.02 |    -0.01 |      0.26 |                  52.57 |                        71.57 |         77.91 |         65.53 |          63.36 |        61.49 |           90.83 |             43.74 |         5.47 |
|              13 | REP.MC   | REP.MC              | EUROPE   |               29.24 |                     0.04 |    -0.02 |      0.02 |                  69.49 |                        71.49 |         57.91 |         74.33 |          76.39 |        72.39 |           64.11 |             73.82 |         3.73 |
|              14 | U        | U                   | US       |               16.73 |                     0.06 |    -0.06 |      0.39 |                  85.91 |                        71.31 |         75.85 |         78.04 |          60.95 |        46.46 |           44.49 |             70.08 |         8.37 |
|              15 | VET      | VET                 | US       |                1.6  |                     0.05 |    -0.02 |      0.13 |                  71.72 |                        70.95 |         69.6  |         66.57 |          69.08 |        66.38 |           60.11 |             89.12 |         6.55 |
|              16 | SNOW     | SNOW                | US       |               93.63 |                     0.07 |    -0.03 |      0.11 |                  73.15 |                        70.93 |         63.66 |         78.45 |          65.25 |        45.17 |           41.02 |             83.5  |         8.88 |
|              17 | BP       | BP                  | US       |               93.75 |                     0.06 |    -0.03 |     -0.01 |                  76.88 |                        70.66 |         52.86 |         60.49 |          70.97 |        76.34 |           86.83 |             76.78 |         3.97 |
|              18 | WDAY     | WDAY                | US       |               40.35 |                     0.08 |    -0.04 |      0.14 |                  69.08 |                        70.59 |         67.93 |         72.31 |          63.7  |        61.48 |           76.13 |             58.98 |         8.43 |
|              19 | TNK      | Teekay Tankers Ltd. | OTHER    |                2.47 |                     0.1  |    -0.08 |      0.07 |                  70.08 |                        70.58 |         61.85 |         64.63 |          69.79 |        68.75 |           81.59 |             76.22 |         5.12 |
|              20 | BILL     | BILL                | US       |                4.1  |                     0.06 |     0.01 |      0.01 |                  63.83 |                        70.55 |         62.89 |         72.34 |          67.64 |        67.95 |           56.83 |             89.59 |         7.01 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | GOLD     | Gold.com, Inc.                                       | US       |                1.13 |             56.91 |         69.02 |         55.43 |          57.91 |        55.91 |           53.22 |             83.61 |             32.36 |         5.92 |             77.94 | short              |              nan    |                  0.02 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.09 |             51.1  |         48.28 |         42.33 |          53.91 |        64.88 |           85.4  |             43.3  |             54.47 |         3.79 |             75.81 | long               |               -1.29 |                  0.14 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1449.07 |             46.81 |         33.73 |         39.62 |          54.01 |        57.69 |           81.46 |             56.84 |             29.17 |         6.08 |             89.83 | long               |                0.01 |                 -1.15 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             45.1  |         42.02 |         40.59 |          48.19 |        60.6  |           57.83 |             53.4  |             88.08 |         4.22 |             82.14 | long               |               -2.01 |                 -0.44 |                  nan |
|    nan | MTRX     | Matrix Service Company                               | US       |                0.26 |             44.1  |         35.28 |         39.81 |          48.39 |        57.31 |           59.13 |             63.01 |             70.53 |         5.92 |             80.44 | long               |              nan    |                nan    |                  nan |
|    nan | ORCL     | Oracle Corporation                                   | US       |              367.3  |             41.9  |         61.67 |         39.22 |          40.47 |        43.32 |           49.6  |             59.82 |             38.02 |         8.06 |             89.54 | short              |                0.39 |                 -1.02 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.85 |             37.31 |         27.54 |         32.21 |          42.41 |        57.12 |           50.53 |             43.88 |             90.12 |         8.5  |             78.58 | long               |               -0.53 |                 -0.31 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.81 |             28    |         23.49 |         19.19 |          32.5  |        42.36 |           59.73 |             17.87 |             34.67 |         8.99 |             78.45 | long               |               -3.2  |                 -1.76 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    100 | VIG.VI   | VIG.VI    | EUROPE   |                9.08 |             67.23 |         68.02 |         62.03 |          66.44 |        70.09 |          nan    |             66.12 |             66.51 |         2.45 |             66.84 | long               |              nan    |                  3.39 |                  nan |
|    342 | AIR.PA   | Airbus SE | EUROPE   |              162.93 |             57.64 |         50.92 |         57.32 |          57.97 |        59.49 |           66.67 |             54.65 |             52.27 |         4.45 |             88.41 | long               |                1.97 |                  3.08 |                  nan |
|    160 | KURA     | KURA      | US       |                1    |             64.09 |         83.88 |         71.1  |          57.08 |        44.08 |           49.81 |             59.97 |              4.81 |         7.2  |             66.84 | short              |               -2.49 |                  3.03 |                  nan |
|    175 | ERAS     | ERAS      | US       |                5.74 |             63.53 |         64.8  |         67.3  |          62.26 |        48.42 |           49.04 |             54.51 |              9.38 |         8.65 |             65.82 | swing              |               18.15 |                  3.02 |                  nan |
|    223 | BHVN     | BHVN      | US       |                2.19 |             61.85 |         78.82 |         70.49 |          53.22 |        41.05 |           51.02 |             53.32 |              1.72 |         8.86 |             66.84 | short              |              nan    |                  2.97 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    690 | VOW3.DE  | VOW3.DE  | EUROPE   |               36.3  |             35.03 |         29.12 |         30.38 |          39.68 |        62.91 |          nan    |             36.7  |             92.37 |         4.42 |             66.84 | long               |               -3.23 |                 -3.45 |                  nan |
|    710 | 1VOW3.MI | 1VOW3.MI | EUROPE   |               36.3  |             31.08 |         28.51 |         26.92 |          33.66 |        46.87 |           18.31 |            nan    |             93.82 |         4.26 |             61.82 | long               |               -4.74 |                 -3.35 |                  nan |
|    706 | 0P6O.IL  | 0P6O.IL  | OTHER    |               40.18 |             31.58 |         26.94 |         24.26 |          36.23 |        63.68 |          nan    |            nan    |             85.71 |         4.33 |             60    | long               |               -7.67 |                 -3.21 |                  nan |
|    691 | RKT      | RKT      | US       |               33.71 |             34.89 |         36.32 |         29.96 |          33.46 |        42.96 |           46.31 |             17.3  |             50.89 |         7.68 |             67.41 | long               |              nan    |                 -3.15 |                  nan |
|    703 | HFG.DE   | HFG.DE   | EUROPE   |                0.41 |             32.29 |         25.31 |         27.53 |          37.05 |        57.78 |          nan    |             47.19 |             82.1  |         7.09 |             66.84 | long               |                0.76 |                 -3.13 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
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
- Excluded by hard/data filters: **278**
- Event watch (otherwise eligible): **8**
- Final eligible: **714**
- Eligible change vs previous stored run: **+12**

Top exclusion categories:
- liquidity: 216
- price: 168
- market_cap: 160
- price_history: 17
- data_confidence: 12
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| HALO | 6 |  | 6 |  | 2 | main,pullback |
| PARR | 20 | 9 | 42 | 5 | 1 | value,quality_value |
| BION.SW | 42 | 1 |  | 1 | 1 | value,quality_value |
| DDI | 45 | 6 |  | 3 | 1 | value,quality_value |
| IRWD | 51 | 5 | 23 | 2 | 1 | value,quality_value |
| 0Q2N.IL | 162 | 4 |  | 8 | 1 | value,quality_value |
| ACCO | 385 | 7 | 185 | 9 | 1 | value,quality_value |
| NWL.MI | 604 | 10 | 212 | 6 | 1 | value,quality_value |
| STNE | 636 | 2 |  | 4 | 1 | value,quality_value |
| GH | 1 |  |  |  | 1 | main |
| CAKE | 2 |  |  |  | 1 | main |
| DK | 3 |  |  |  | 1 | main |
| HPE | 4 |  |  |  | 1 | main |
| AVAH | 5 |  |  |  | 1 | main |
| WT | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (GH, CAKE, DK, HPE, AVAH, WT, KIN.BR, SSRM, ERO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (SYENS.BR, FIGR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 71.85 | 67.98 | 75.45 | 79.95 | 56.56 | 74.71 | 45.16 |
| 2 | IRWD | value+pullback | 70.59 | 61.96 | 59.68 | 87.02 | 74.85 | 82.72 | 70.62 |
| 3 | NVDA | value+pullback | 70.32 | 55.07 | 72.50 | 92.54 | 65.09 | 76.44 | 58.28 |
| 4 | HMC | value+pullback | 69.32 | 56.96 | 73.09 | 69.35 | 83.79 | 75.89 | 64.11 |
| 5 | ACCO | value+pullback | 66.01 | 74.12 | 59.38 | 71.09 | 54.28 | 64.19 | 56.43 |
| 6 | DXC | value+pullback | 65.62 | 84.78 | 74.94 | 52.01 | 33.28 | 51.59 | 44.76 |
| 7 | MFA | value+pullback | 64.17 | 57.65 | 75.24 | 79.81 | 33.86 | 63.52 | 40.53 |
| 8 | DAC | value+pullback | 63.34 | 57.10 | 55.90 | 77.17 | 56.11 | 75.25 | 69.22 |
| 9 | PBR-A | value+pullback | 63.08 | 73.63 | 63.18 | 54.53 | 70.63 | 49.79 | 57.62 |
| 10 | MC.PA | value+pullback | 62.08 | 58.19 | 64.33 | 68.66 | 58.71 | 61.83 | 40.16 |
| 11 | AAPL | value+pullback | 61.83 | 60.17 | 71.40 | 66.60 | 49.27 | 55.05 | 50.97 |
| 12 | PARR | value+pullback | 61.46 | 68.27 | 36.20 | 80.43 | 60.78 | 68.95 | 74.20 |
| 13 | ALL-PH | value+pullback | 60.16 | 61.76 | 60.13 | 70.02 | 41.24 | 59.87 | 44.73 |
| 14 | PBR | value+pullback | 60.10 | 60.53 | 73.25 | 54.53 | 59.19 | 47.64 | 54.11 |
| 15 | WKC | value+pullback | 59.42 | 57.82 | 48.93 | 58.15 | 74.98 | 68.11 | 67.69 |
| 16 | BION.SW | value | 59.07 | 78.04 | 40.18 | 83.85 | 57.77 | 86.53 | 71.49 |
| 17 | UNIT | value+pullback | 58.95 | 80.26 | 51.77 | 67.04 | 28.62 | 45.07 | 45.47 |
| 18 | BYD | value+pullback | 58.79 | 57.03 | 66.46 | 69.99 | 36.87 | 54.41 | 42.56 |
| 19 | ORC | value+pullback | 57.11 | 59.31 | 51.56 | 73.20 | 36.15 | 59.16 | 45.62 |
| 20 | NOVO-B.CO | value+pullback | 56.91 | 61.52 | 58.24 | 61.80 | 47.57 | 49.34 | 48.94 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 68.7 | 1 / 9 |
| Top 25 | 22/25 | 25/25 | 24/25 | 21/25 | 0/25 | 68.7 | 7 / 18 |
| Top 50 | 45/50 | 49/50 | 49/50 | 43/50 | 0/50 | 68.9 | 16 / 34 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=3, large_20_100b=1
