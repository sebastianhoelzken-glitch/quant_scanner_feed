# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-31

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

- **EUROPE:** 88.9/100
- **OTHER:** 71.7/100
- **US:** 83.9/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO      | FRO                        | US       |                8.44 |             80.4  |         77.88 |         80.15 |          80.66 |        82.91 |           91.98 |             69.93 |             69.52 |         5.25 |             69.68 | long               |               -0.01 |                  2.62 |                  nan |
|      2 | OKTA     | OKTA                       | US       |               24.93 |             79.85 |         85.9  |         82.8  |          76.9  |        63.95 |           77.85 |             80.19 |             16.72 |         7.57 |             67.86 | short              |                0.93 |                  3.89 |                  nan |
|      3 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.61 |             79.55 |         78.94 |         78.1  |          80.16 |        80.59 |           96.26 |             63.07 |             60.41 |         3.8  |             69.68 | long               |               -1.97 |                  4.78 |                  nan |
|      4 | SM       | SM                         | US       |                7.47 |             77.98 |         75.7  |         77.68 |          78.28 |        82.22 |           80.55 |             66.25 |             96.72 |         7    |             68.66 | long               |               -0.36 |                  0.38 |                  nan |
|      5 | PARR     | Par Pacific Holdings, Inc. | US       |                3.39 |             77.98 |         61.45 |         76.45 |          81.13 |        79.5  |           83.48 |             61.89 |             72.8  |         6.86 |             85.07 | medium             |                3.01 |                  0.57 |                  nan |
|      6 | AVAH     | AVAH                       | US       |                2.49 |             77.76 |         86.18 |         81.35 |          74.17 |        71.69 |           92.99 |             53.09 |             41.72 |         7.38 |             68.66 | short              |               -0.44 |                 -0.1  |                  nan |
|      7 | DK       | DK                         | US       |                3.8  |             77.38 |         79.01 |         84.99 |          75.75 |        61.36 |           55.14 |             84.56 |             34.08 |         6.83 |             69.68 | swing              |               -0.29 |                  0.71 |                  nan |
|      8 | BION.SW  | BB Biotech AG              | EUROPE   |                3.3  |             76.47 |         71.96 |         75.31 |          77.63 |        82.63 |           88.1  |             58.9  |             87.73 |         2.22 |             78.9  | long               |                7.82 |                  3.29 |                  nan |
|      9 | NAT      | NAT                        | US       |                1.23 |             76.45 |         62.86 |         77.1  |          78.38 |        75.81 |           86.48 |             72.55 |             49.12 |         4.65 |             69.68 | medium             |               -3.78 |                nan    |                  nan |
|     10 | DOCM.SW  | DOCM.SW                    | EUROPE   |                0.6  |             76.14 |         81.17 |         81.57 |          71.11 |        58.56 |           51.95 |             75.72 |             40.99 |         7.17 |             66.84 | swing              |                0.88 |                  1.89 |                  nan |
|     11 | PAGP     | PAGP                       | US       |                5.59 |             76.03 |         77.62 |         75.87 |          76.2  |        73.91 |           82.86 |             76.73 |             54.39 |         1.76 |             66.7  | short              |               -0.48 |                nan    |                  nan |
|     12 | SRAIL.SW | SRAIL.SW                   | EUROPE   |                3.23 |             76.01 |         86.29 |         79.68 |          72.34 |        64.66 |           80.21 |             75.29 |             28.45 |         5.45 |             69.68 | short              |                1.07 |                nan    |                  nan |
|     13 | RNG      | RNG                        | US       |                4.97 |             75.31 |         81.09 |         83.73 |          69.54 |        55.52 |           22.97 |             82.72 |             61.71 |         7.15 |             67.75 | swing              |               -0.34 |                  0.71 |                  nan |
|     14 | AMC      | AMC                        | US       |                1.98 |             74.72 |         52.24 |         74.73 |          74.71 |        75.21 |           84.31 |             61.29 |            nan    |         9.66 |             63.43 | long               |               -0.56 |                nan    |                  nan |
|     15 | DEZ.DE   | DEZ.DE                     | EUROPE   |                1.98 |             74.44 |         87.02 |         78.29 |          68.3  |        70.6  |          nan    |             82.24 |             62.47 |         6.12 |             66.84 | short              |                1.88 |                nan    |                  nan |
|     16 | ABN.AS   | ABN.AS                     | EUROPE   |               33.97 |             74.43 |         73.99 |         75.39 |          74.86 |        70.42 |           80.25 |             62.02 |             50.13 |         2.79 |             69.68 | swing              |                1.49 |                  1.93 |                  nan |
|     17 | HPE      | HPE                        | US       |               59.43 |             74.21 |         59.07 |         76.55 |          79.93 |        71.86 |           69.21 |             81.01 |             57.68 |         6.67 |             67.86 | medium             |               -0.6  |                 -0.53 |                  nan |
|     18 | PR       | PR                         | US       |               16.31 |             73.99 |         66.54 |         72.62 |          75.37 |        76.64 |           76.89 |             71.58 |             74.01 |         4.09 |             68.32 | long               |               -0.46 |                 -0.43 |                  nan |
|     19 | GH       | GH                         | US       |               18.59 |             73.95 |         50.96 |         75.35 |          79.06 |        72.55 |           61.01 |             79.92 |            nan    |         6.47 |             64.91 | medium             |               -0.47 |                 -0.64 |                  nan |
|     20 | WDAY     | WDAY                       | US       |               42.33 |             73.92 |         82.33 |         79.42 |          68.42 |        62.7  |           73.54 |             80.57 |             40.49 |         8.41 |             68.2  | short              |               -0.38 |                  2.12 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                    | EUROPE   |                3.3  |                  78.27 |                    77.63 |                 79.27 |              78.07 |                87.92 |                   12.08 |           88.1  |             58.9  |       0.8   |         nan |       nan |      nan    |       -85.14 |          2.25 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHELL.AS  | SHELL.AS                         | EUROPE   |              215.49 |                  64.98 |                    72.99 |                 75.68 |              68.93 |                84.05 |                   15.95 |           93.21 |             70.15 |     nan     |         nan |       nan |      nan    |         9.85 |         10.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | VOLV-B.ST | AB Volvo (publ)                  | EUROPE   |               63.89 |                  84.11 |                    72.7  |                 68.84 |              76.99 |                56.97 |                   43.03 |           52.72 |             61.77 |       0.034 |         nan |       nan |       16.41 |        13.99 |         19.87 |        1.45 |                 nan |              nan |                  12 |                  0.63 |
|            3 | PARR      | Par Pacific Holdings, Inc.       | US       |                3.39 |                  72.81 |                    71.67 |                 73.06 |              70.78 |                67.6  |                   32.4  |           83.48 |             61.89 |       0.021 |         nan |       nan |        3.85 |         6.67 |          4.63 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | GSL       | Global Ship Lease, Inc.          | OTHER    |                1.38 |                  79.95 |                    71.54 |                 70.25 |              73.44 |                68.84 |                   31.16 |           74.89 |             34.81 |       0.081 |         nan |       nan |        3.83 |         5.02 |          4.34 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            5 | STNE      | StoneCo Ltd.                     | OTHER    |                1.92 |                  75.23 |                    71.21 |                 70.57 |              70.18 |                69.55 |                   30.45 |           84.18 |             34.92 |       0.613 |         nan |       nan |        1.62 |         4.16 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA      | NVIDIA Corporation               | US       |             4506.7  |                  61.64 |                    70.87 |                 72.75 |              65.56 |                77.06 |                   22.94 |           89.96 |             73.07 |       0.008 |         nan |       nan |       25.93 |        14.21 |         27.47 |        0.63 |                 nan |              nan |                  12 |                  0.63 |
|            7 | BBWI      | Bath & Body Works, Inc.          | US       |                3.32 |                  77.39 |                    69.97 |                 67.29 |              69.37 |                56.9  |                   43.1  |           75.28 |             34.09 |       0.197 |         nan |       nan |        5.95 |         6.85 |          5.04 |        0.72 |                 nan |              nan |                  11 |                  0.58 |
|            8 | DDI       | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  63.12 |                    69.68 |                 72.65 |              66.21 |                81.71 |                   18.29 |           91.64 |             60.53 |       0.154 |         nan |       nan |        0.77 |         5.24 |          5.07 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | IRWD      | Ironwood Pharmaceuticals, Inc.   | US       |                0.59 |                  65.93 |                    69.62 |                 72.45 |              67.78 |                76.64 |                   23.36 |           86.05 |             65.13 |       0.179 |         nan |       nan |        4.2  |         2.75 |          5.23 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | IHS       | IHS Holding Limited              | OTHER    |                2.43 |                  73.2  |                    68.55 |                 68.59 |              72.38 |                63.08 |                   36.92 |           54.84 |             83.2  |      -0.115 |         nan |       nan |        7.48 |        15.2  |          5.13 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO       | FRO                              | US       |                8.44 |                  58.66 |                    68.14 |                 71.57 |              63.25 |                77.88 |                   22.12 |           91.98 |             69.93 |     nan     |         nan |       nan |      nan    |        10.14 |          6.63 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR    | AGS.BR                           | EUROPE   |               15.64 |                  61.89 |                    67.82 |                 69.71 |              64.18 |                78.79 |                   21.21 |           87.57 |             54.35 |     nan     |         nan |       nan |      nan    |         8.66 |          7.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY       | NLY                              | US       |               14.9  |                  67.69 |                    67.56 |                 67.83 |              64.44 |                70.43 |                   29.57 |           89.07 |             30.22 |     nan     |         nan |       nan |      nan    |         7.41 |          5.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | DAC       | Danaos Corporation               | OTHER    |                2.35 |                  64.59 |                    67.4  |                 69.53 |              66.37 |                79.18 |                   20.82 |           80.65 |             56.12 |       0.002 |         nan |       nan |        4.03 |         6.15 |          5.1  |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP        | BP                               | US       |               93.13 |                  56.75 |                    67.18 |                 70.61 |              62.95 |                79.77 |                   20.23 |           86.07 |             77.27 |     nan     |         nan |       nan |      nan    |         9.51 |         20.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | WB        | Weibo Corporation                | OTHER    |                1.47 |                  79.34 |                    67.13 |                 62.87 |              69.69 |                58.28 |                   41.72 |           61.28 |             20.71 |     nan     |         nan |       nan |        1.96 |         5.45 |          5.78 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|           13 | PKX       | POSCO Holdings Inc.              | OTHER    |               15.63 |                  65.95 |                    67.02 |                 69.99 |              65.15 |                59.7  |                   40.3  |           83.91 |             69.22 |      -0.138 |         nan |       nan |        3.9  |        10.45 |         29.53 |        0.89 |                 nan |              nan |                  12 |                  0.63 |
|          nan | ASRNL.AS  | ASRNL.AS                         | EUROPE   |               14.59 |                  57.19 |                    66.71 |                 69.52 |              63.14 |                82.14 |                   17.86 |           82.8  |             71.77 |     nan     |         nan |       nan |      nan    |        11.25 |         14.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | UNIT      | Uniti Group Inc.                 | US       |                2.09 |                  80.26 |                    66.67 |                 63.64 |              68.73 |                44.76 |                   55.24 |           65.89 |             28.88 |      -0.106 |         nan |       nan |        9.11 |       -14.11 |          2.61 |        0.17 |                 nan |              nan |                   9 |                  0.47 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                    | EUROPE   |                3.3  |                  78.27 |                    77.63 |                 79.27 |              78.07 |                87.92 |                   12.08 |           88.1  |             58.9  |       0.8   |         nan |       nan |      nan    |       -85.14 |          2.25 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHELL.AS  | SHELL.AS                         | EUROPE   |              215.49 |                  64.98 |                    72.99 |                 75.68 |              68.93 |                84.05 |                   15.95 |           93.21 |             70.15 |     nan     |         nan |       nan |      nan    |         9.85 |         10.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PARR      | Par Pacific Holdings, Inc.       | US       |                3.39 |                  72.81 |                    71.67 |                 73.06 |              70.78 |                67.6  |                   32.4  |           83.48 |             61.89 |       0.021 |         nan |       nan |        3.85 |         6.67 |          4.63 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA      | NVIDIA Corporation               | US       |             4506.7  |                  61.64 |                    70.87 |                 72.75 |              65.56 |                77.06 |                   22.94 |           89.96 |             73.07 |       0.008 |         nan |       nan |       25.93 |        14.21 |         27.47 |        0.63 |                 nan |              nan |                  12 |                  0.63 |
|            8 | DDI       | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  63.12 |                    69.68 |                 72.65 |              66.21 |                81.71 |                   18.29 |           91.64 |             60.53 |       0.154 |         nan |       nan |        0.77 |         5.24 |          5.07 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | IRWD      | Ironwood Pharmaceuticals, Inc.   | US       |                0.59 |                  65.93 |                    69.62 |                 72.45 |              67.78 |                76.64 |                   23.36 |           86.05 |             65.13 |       0.179 |         nan |       nan |        4.2  |         2.75 |          5.23 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO       | FRO                              | US       |                8.44 |                  58.66 |                    68.14 |                 71.57 |              63.25 |                77.88 |                   22.12 |           91.98 |             69.93 |     nan     |         nan |       nan |      nan    |        10.14 |          6.63 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                               | US       |               93.13 |                  56.75 |                    67.18 |                 70.61 |              62.95 |                79.77 |                   20.23 |           86.07 |             77.27 |     nan     |         nan |       nan |      nan    |         9.51 |         20.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | STNE      | StoneCo Ltd.                     | OTHER    |                1.92 |                  75.23 |                    71.21 |                 70.57 |              70.18 |                69.55 |                   30.45 |           84.18 |             34.92 |       0.613 |         nan |       nan |        1.62 |         4.16 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR   | CMBT.BR                          | EUROPE   |                4.61 |                  55.1  |                    66.48 |                 70.42 |              60.5  |                80.69 |                   19.31 |           96.26 |             63.07 |     nan     |         nan |       nan |      nan    |         8.86 |          6.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | GSL       | Global Ship Lease, Inc.          | OTHER    |                1.38 |                  79.95 |                    71.54 |                 70.25 |              73.44 |                68.84 |                   31.16 |           74.89 |             34.81 |       0.081 |         nan |       nan |        3.83 |         5.02 |          4.34 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|           13 | PKX       | POSCO Holdings Inc.              | OTHER    |               15.63 |                  65.95 |                    67.02 |                 69.99 |              65.15 |                59.7  |                   40.3  |           83.91 |             69.22 |      -0.138 |         nan |       nan |        3.9  |        10.45 |         29.53 |        0.89 |                 nan |              nan |                  12 |                  0.63 |
|          nan | AGS.BR    | AGS.BR                           | EUROPE   |               15.64 |                  61.89 |                    67.82 |                 69.71 |              64.18 |                78.79 |                   21.21 |           87.57 |             54.35 |     nan     |         nan |       nan |      nan    |         8.66 |          7.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | DAC       | Danaos Corporation               | OTHER    |                2.35 |                  64.59 |                    67.4  |                 69.53 |              66.37 |                79.18 |                   20.82 |           80.65 |             56.12 |       0.002 |         nan |       nan |        4.03 |         6.15 |          5.1  |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|          nan | ASRNL.AS  | ASRNL.AS                         | EUROPE   |               14.59 |                  57.19 |                    66.71 |                 69.52 |              63.14 |                82.14 |                   17.86 |           82.8  |             71.77 |     nan     |         nan |       nan |      nan    |        11.25 |         14.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NAT       | NAT                              | US       |                1.23 |                  56.52 |                    66.2  |                 69.51 |              61.84 |                77.18 |                   22.82 |           86.48 |             72.55 |     nan     |         nan |       nan |      nan    |        14.88 |         11.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           16 | HMC       | Honda Motor Co., Ltd.            | OTHER    |               35.46 |                  59.96 |                    65.79 |                 69    |              65    |                74.53 |                   25.47 |           72.83 |             84.2  |       0.041 |         nan |       nan |        7.16 |         6.42 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|            2 | VOLV-B.ST | AB Volvo (publ)                  | EUROPE   |               63.89 |                  84.11 |                    72.7  |                 68.84 |              76.99 |                56.97 |                   43.03 |           52.72 |             61.77 |       0.034 |         nan |       nan |       16.41 |        13.99 |         19.87 |        1.45 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR   | BIRG.IR                          | EUROPE   |               17.7  |                  58.65 |                    66.14 |                 68.83 |              60.66 |                78.01 |                   21.99 |           96.57 |             43.93 |     nan     |         nan |       nan |      nan    |        10.27 |         13.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | IHS       | IHS Holding Limited              | OTHER    |                2.43 |                  73.2  |                    68.55 |                 68.59 |              72.38 |                63.08 |                   36.92 |           54.84 |             83.2  |      -0.115 |         nan |       nan |        7.48 |        15.2  |          5.13 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                       | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AVAH     | AVAH                       | US       |                2.49 |                     0.04 |     0.01 |      0.42 |                  55.64 |                        77.99 |         86.18 |         81.35 |          74.17 |        71.69 |           92.99 |             53.09 |         7.38 |
|               2 | NAT      | NAT                        | US       |                1.23 |                     0.04 |    -0.03 |      0.04 |                  67.2  |                        76.81 |         62.86 |         77.1  |          78.38 |        75.81 |           86.48 |             72.55 |         4.65 |
|               3 | GH       | GH                         | US       |               18.59 |                     0.06 |    -0.05 |     -0    |                  86.47 |                        74.83 |         50.96 |         75.35 |          79.06 |        72.55 |           61.01 |             79.92 |         6.47 |
|               4 | PARR     | Par Pacific Holdings, Inc. | US       |                3.39 |                     0.05 |    -0    |     -0.08 |                  68.4  |                        74.47 |         61.45 |         76.45 |          81.13 |        79.5  |           83.48 |             61.89 |         6.86 |
|               5 | PR       | PR                         | US       |               16.31 |                     0.05 |    -0.04 |      0.07 |                  80.02 |                        74.43 |         66.54 |         72.62 |          75.37 |        76.64 |           76.89 |             71.58 |         4.09 |
|               6 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.64 |                     0.04 |    -0.03 |      0.12 |                  66.49 |                        74.27 |         74.75 |         74.9  |          72.54 |        69.66 |           76.34 |             77.2  |         5.14 |
|               7 | SM       | SM                         | US       |                7.47 |                     0.03 |    -0.02 |      0.13 |                  58.11 |                        73.61 |         75.7  |         77.68 |          78.28 |        82.22 |           80.55 |             66.25 |         7    |
|               8 | SSRM     | SSRM                       | US       |                6.64 |                     0.05 |    -0.01 |      0.46 |                  70.81 |                        73.2  |         78.54 |         71.91 |          69.72 |        73.85 |           65.1  |             68.61 |         7.04 |
|               9 | KRX.IR   | KRX.IR                     | EUROPE   |               18.37 |                     0.02 |     0.01 |      0.27 |                  43.75 |                        73.02 |         81.6  |         70.15 |          65.19 |        63.57 |           96.68 |             42.17 |         5.13 |
|              10 | VWS.CO   | VWS.CO                     | EUROPE   |               27.72 |                     0.02 |     0.02 |      0.21 |                  47.16 |                        72.53 |         80.46 |         66.74 |          65.59 |        61.76 |           88.87 |             49.69 |         5.54 |
|              11 | CVE      | CVE                        | US       |               49.97 |                     0.04 |    -0.04 |      0.05 |                  74.12 |                        72.19 |         63.11 |         71.32 |          75.22 |        72.96 |           75.85 |             68.3  |         4.74 |
|              12 | NVDA     | NVIDIA Corporation         | US       |             4506.7  |                     0.05 |     0.01 |      0.08 |                  61.26 |                        72.11 |         67.94 |         62.33 |          66.83 |        66.98 |           89.96 |             73.07 |         5.75 |
|              13 | HMC      | Honda Motor Co., Ltd.      | OTHER    |               35.46 |                     0.05 |    -0.05 |      0.06 |                  78    |                        72.03 |         58.66 |         66.28 |          64.67 |        69.71 |           72.83 |             84.2  |         3.72 |
|              14 | REP.MC   | REP.MC                     | EUROPE   |               28.9  |                     0.05 |    -0.05 |      0.01 |                  84.82 |                        71.97 |         53.23 |         71.51 |          74.66 |        70.68 |           61.54 |             74.58 |         3.76 |
|              15 | MP       | MP                         | US       |                8.58 |                     0.07 |    -0.07 |      0.36 |                  82.36 |                        71.88 |         69.38 |         50.57 |          48.8  |        46.42 |           58.55 |             87.53 |         8.78 |
|              16 | BAX      | BAX                        | US       |               11.59 |                     0.08 |    -0.01 |     -0    |                  58.84 |                        71.55 |         57.77 |         74.27 |          71.41 |        69.93 |           75.46 |             69.99 |         5.97 |
|              17 | TOST     | TOST                       | US       |               17.43 |                     0.05 |    -0.04 |      0.09 |                  79.12 |                        71.21 |         62.24 |         70.96 |          61.18 |        54.67 |           65.94 |             71.14 |         6.81 |
|              18 | FSM      | FSM                        | US       |                3.11 |                     0.04 |     0.02 |      0.45 |                  58.77 |                        71.1  |         80.44 |         63.29 |          61.41 |        74.76 |           77.01 |             44.43 |         7.09 |
|              19 | BION.SW  | BB Biotech AG              | EUROPE   |                3.3  |                     0.02 |     0    |      0.09 |                  46.59 |                        71.1  |         71.96 |         75.31 |          77.63 |        82.63 |           88.1  |             58.9  |         2.22 |
|              20 | CRGY     | CRGY                       | US       |                3.84 |                     0.04 |    -0.04 |      0.19 |                  70.47 |                        70.9  |         73.47 |         71.74 |          70.87 |        77.54 |           70.55 |             63.22 |         5.99 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1505.23 |             51.75 |         39.93 |         44.37 |          59.13 |        60.93 |           82.27 |             66.36 |             32.32 |         8.5  |             89.18 | long               |                1.57 |                  0.99 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             46.83 |         40.83 |         42.65 |          51.02 |        63.87 |           62.02 |             54.62 |             90.51 |         4.21 |             82.14 | long               |                1.5  |                 -0.06 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.06 |             45.72 |         38.99 |         39.07 |          52.37 |        63.92 |           84.91 |             43.6  |             54.6  |         3.74 |             75.81 | long               |                0.2  |                 -1.33 |                  nan |
|    nan | ORCL     | Oracle Corporation                                   | US       |              372.77 |             43.28 |         60.73 |         40.37 |          41.93 |        44.63 |           48.63 |             61.34 |             42.08 |         7.94 |             89.54 | short              |               -0.19 |                  0.35 |                  nan |
|    nan | MTRX     | Matrix Service Company                               | US       |                0.26 |             39.25 |         34.18 |         35.54 |          42.96 |        49.5  |           43.73 |             62.71 |             72.53 |         8.5  |             80.44 | long               |               -0.02 |                nan    |                  nan |
|    nan | SHOE     | Shoe Station Group Inc.                              | US       |                0.32 |             31.15 |         23.76 |         26.62 |          35.68 |        46.27 |           43.94 |             40.77 |             65.57 |         6.69 |             84.21 | long               |                1.52 |                nan    |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name          | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     53 | CRWD     | CRWD          | US       |              191.85 |             70.63 |         77.38 |         75.32 |          65.95 |        44.14 |           36.59 |             88.68 |              1.59 |         7.36 |             69.68 | short              |               -0.32 |                  5.09 |                  nan |
|      3 | CMBT.BR  | CMBT.BR       | EUROPE   |                4.61 |             79.55 |         78.94 |         78.1  |          80.16 |        80.59 |           96.26 |             63.07 |             60.41 |         3.8  |             69.68 | long               |               -1.97 |                  4.78 |                  nan |
|      2 | OKTA     | OKTA          | US       |               24.93 |             79.85 |         85.9  |         82.8  |          76.9  |        63.95 |           77.85 |             80.19 |             16.72 |         7.57 |             67.86 | short              |                0.93 |                  3.89 |                  nan |
|      8 | BION.SW  | BB Biotech AG | EUROPE   |                3.3  |             76.47 |         71.96 |         75.31 |          77.63 |        82.63 |           88.1  |             58.9  |             87.73 |         2.22 |             78.9  | long               |                7.82 |                  3.29 |                  nan |
|     22 | ANF      | ANF           | US       |                5.66 |             73.68 |         85.95 |         76.49 |          68.02 |        70.87 |           87.64 |             32.24 |             58.19 |         8.38 |             65.45 | short              |                0.44 |                  3.18 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    721 | TLRY     | Tilray Brands, Inc.          | OTHER    |                0.54 |             29.19 |         35.12 |         25.08 |          26.6  |        31.78 |           30.84 |             44.78 |             36.88 |         8.7  |             79.03 | short              |                0.22 |                 -3.09 |                  nan |
|    714 | LBTYA    | Liberty Global Ltd.          | OTHER    |                3.12 |             31.44 |         43.21 |         29.72 |          30.69 |        32.19 |           21.41 |             44.49 |             38.12 |         5.18 |             79.2  | short              |                0.74 |                 -2.86 |                  nan |
|    504 | SLDB     | SLDB                         | US       |                0.9  |             51.71 |         63.26 |         57.44 |          45.98 |        35.48 |            4.5  |             22.67 |             51.73 |         7.53 |             64.8  | short              |                0.17 |                 -2.7  |                  nan |
|    725 | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.61 |             23.6  |         19.76 |         18.57 |          27.44 |        36.41 |           36.87 |             34.51 |             52.06 |         6.76 |             77.68 | long               |                0.07 |                 -2.54 |                  nan |
|    718 | LBTYK    | Liberty Global Ltd.          | OTHER    |                3.05 |             30.59 |         46.59 |         29.55 |          29.63 |        31.54 |           21.41 |             39.9  |             39.02 |         4.53 |             72.93 | short              |                0.42 |                 -2.46 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
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
- Excluded by hard/data filters: **269**
- Event watch (otherwise eligible): **6**
- Final eligible: **725**
- Eligible change vs previous stored run: **+1**

Top exclusion categories:
- liquidity: 218
- price: 161
- market_cap: 155
- price_history: 14
- data_confidence: 10
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 5 | 3 | 4 | 2 | 3 | main,value,pullback,quality_value |
| BION.SW | 8 | 1 | 19 | 1 | 2 | main,value,quality_value |
| SM | 4 |  | 7 |  | 2 | main,pullback |
| AVAH | 6 |  | 1 |  | 2 | main,pullback |
| NAT | 9 |  | 2 |  | 2 | main,pullback |
| DDI | 42 | 8 |  | 4 | 1 | value,quality_value |
| IRWD | 98 | 9 | 47 | 5 | 1 | value,quality_value |
| NVDA | 101 | 6 | 12 | 3 | 1 | value,quality_value |
| GSL | 137 | 4 | 165 | 7 | 1 | value,quality_value |
| STNE | 658 | 5 |  | 6 | 1 | value,quality_value |
| FRO | 1 |  |  |  | 1 | main |
| OKTA | 2 |  |  |  | 1 | main |
| CMBT.BR | 3 |  |  |  | 1 | main |
| DK | 7 |  |  |  | 1 | main |
| DOCM.SW | 10 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **5** (FRO, OKTA, CMBT.BR, DK, DOCM.SW)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (KRX.IR, VWS.CO)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | IRWD | value+pullback | 73.32 | 65.93 | 75.14 | 86.05 | 65.13 | 76.64 | 67.26 |
| 2 | BION.SW | value+pullback | 71.82 | 78.27 | 46.59 | 88.10 | 58.90 | 87.92 | 76.47 |
| 3 | HMC | value+pullback | 71.74 | 59.96 | 78.00 | 72.83 | 84.20 | 74.53 | 65.47 |
| 4 | PARR | value+pullback | 71.17 | 72.81 | 68.40 | 83.48 | 61.89 | 67.60 | 77.98 |
| 5 | NVDA | value+pullback | 70.02 | 61.64 | 61.26 | 89.96 | 73.07 | 77.06 | 66.90 |
| 6 | VOLV-B.ST | value+pullback | 66.12 | 84.11 | 61.62 | 52.72 | 61.77 | 56.97 | 56.74 |
| 7 | XNET | value+pullback | 64.89 | 59.23 | 67.50 | 57.83 | 81.75 | 66.97 | 43.21 |
| 8 | BBWI | value+pullback | 64.31 | 77.39 | 60.06 | 75.28 | 34.09 | 56.90 | 45.60 |
| 9 | GSL | value+pullback | 63.18 | 79.95 | 42.85 | 74.89 | 34.81 | 68.84 | 65.08 |
| 10 | MFA | value+pullback | 62.55 | 59.27 | 66.23 | 79.81 | 34.82 | 63.79 | 43.34 |
| 11 | WKC | value+pullback | 62.19 | 61.83 | 51.15 | 64.35 | 76.24 | 67.86 | 70.38 |
| 12 | INVA | value+pullback | 61.41 | 58.54 | 52.87 | 79.49 | 36.26 | 75.39 | 46.97 |
| 13 | ALL-PH | value+pullback | 59.43 | 60.39 | 58.76 | 69.60 | 43.48 | 59.19 | 45.52 |
| 14 | UNIT | value+pullback | 59.28 | 80.26 | 53.90 | 65.89 | 28.88 | 44.76 | 49.00 |
| 15 | TV | value+pullback | 58.27 | 65.87 | 68.77 | 44.91 | 28.39 | 58.72 | 39.30 |
| 16 | BP | pullback | 56.81 | 56.75 | 80.88 | 86.07 | 77.27 | 79.77 | 64.17 |
| 17 | GL9.IR | pullback | 55.98 | 43.14 | 64.71 | 97.82 | 74.63 | 88.35 | 65.58 |
| 18 | ONIT | value+pullback | 55.33 | 71.40 | 46.30 | 63.78 | 43.53 | 42.09 | 43.21 |
| 19 | CLW | value+pullback | 55.17 | 56.29 | 51.22 | 47.39 | 66.71 | 58.48 | 56.00 |
| 20 | DDI | value | 55.08 | 63.12 | 46.34 | 91.64 | 60.53 | 81.71 | 71.25 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.7 | 5 / 5 |
| Top 25 | 23/25 | 25/25 | 23/25 | 21/25 | 0/25 | 68.7 | 11 / 14 |
| Top 50 | 48/50 | 50/50 | 48/50 | 46/50 | 0/50 | 69.3 | 21 / 29 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=6, mid_5_20b=2, large_20_100b=1
