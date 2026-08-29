# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-29

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

- **EUROPE:** 88.6/100
- **OTHER:** 71.9/100
- **US:** 84.8/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO      | FRO                        | US       |                8.49 |             81.25 |         78.52 |         82    |          81.23 |        81.28 |           83.83 |             80.69 |             69.78 |         5.19 |             69.68 | swing              |                4.43 |                  1.5  |                  nan |
|      2 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.61 |             80.81 |         79.14 |         79.89 |          82.69 |        81.73 |           96.3  |             79.91 |             60.74 |         3.75 |             69.68 | medium             |                9.81 |                  4.92 |                  nan |
|      3 | NAT      | NAT                        | US       |                1.24 |             79.67 |         64.45 |         80.66 |          82.27 |        78.68 |           88.38 |             86.5  |             49.58 |         4.59 |             69.68 | medium             |                7.09 |                nan    |                  nan |
|      4 | OKTA     | OKTA                       | US       |               25.08 |             79.66 |         85.7  |         82.63 |          76.68 |        63.66 |           77.25 |             79.83 |             16.67 |         7.55 |             67.86 | short              |                4.28 |                  3.25 |                  nan |
|      5 | PARR     | Par Pacific Holdings, Inc. | US       |                3.41 |             77.81 |         61.28 |         76.22 |          80.99 |        79.4  |           83.48 |             61.08 |             72.8  |         6.87 |             85.72 | medium             |               13.81 |                  0.53 |                  nan |
|      6 | DK       | DK                         | US       |                3.82 |             77.19 |         78.75 |         84.76 |          75.63 |        61.34 |           54.49 |             84.15 |             35.11 |         6.8  |             69.68 | swing              |              nan    |                  0.4  |                  nan |
|      7 | AVAH     | AVAH                       | US       |                2.51 |             77.06 |         85.87 |         80.67 |          73.44 |        70.93 |           92.66 |             50.48 |             40.69 |         7.36 |             68.66 | short              |                3.21 |                 -0.3  |                  nan |
|      8 | PAGP     | PAGP                       | US       |                5.62 |             76.11 |         77.42 |         75.93 |          76.29 |        74.11 |           83.03 |             76.34 |             54.72 |         1.74 |             66.7  | short              |                4.43 |                nan    |                  nan |
|      9 | NIQ      | NIQ                        | US       |                4.89 |             75.8  |         85.48 |         85.74 |          66.11 |        56.54 |           46.41 |             91.81 |             44.5  |         9.03 |             67.86 | swing              |                5.38 |                  0.32 |                  nan |
|     10 | CAKE     | CAKE                       | US       |                4.81 |             75.78 |         74.17 |         81.29 |          77.38 |        67.94 |           86.76 |             65.78 |             23.06 |         5.71 |             67.18 | swing              |                3.58 |                  0.11 |                  nan |
|     11 | RNG      | RNG                        | US       |                5    |             75.16 |         80.93 |         83.58 |          69.38 |        55.21 |           22.23 |             82.68 |             61.63 |         7.14 |             67.75 | swing              |                3.64 |                  0.94 |                  nan |
|     12 | BMAG.VI  | Bajaj Mobility AG          | EUROPE   |                1.09 |             75.08 |         82.9  |         80.44 |          69.72 |        56.1  |           49.15 |             79.67 |             31.14 |         6.6  |             66.3  | short              |                9.05 |                  1.73 |                  nan |
|     13 | AMC      | AMC                        | US       |                2    |             74.7  |         52.27 |         74.71 |          74.69 |        75.05 |           83.82 |             61.46 |            nan    |         9.63 |             63.43 | long               |                4.4  |                nan    |                  nan |
|     14 | DOCM.SW  | DOCM.SW                    | EUROPE   |                0.6  |             74.4  |         79.11 |         79.25 |          69.69 |        57.53 |           52.06 |             75.75 |             42.07 |         7.13 |             66.84 | swing              |                0.28 |                nan    |                  nan |
|     15 | BION.SW  | BB Biotech AG              | EUROPE   |                3.3  |             74.36 |         70.12 |         73.14 |          75.57 |        79.9  |           86.35 |             58.81 |             84.12 |         2.24 |             79.55 | long               |               16.24 |                  0.1  |                  nan |
|     16 | HPE      | HPE                        | US       |               59.78 |             74.31 |         58.92 |         76.6  |          80.06 |        72.01 |           69.45 |             80.91 |             57.69 |         6.64 |             67.86 | medium             |                4.17 |                 -0.01 |                  nan |
|     17 | GTE      | GTE                        | US       |                0.3  |             74.29 |         81.3  |         76.59 |          71.99 |        68.26 |           52.48 |             64.17 |             77.38 |         8.03 |             69.68 | short              |                4.69 |                nan    |                  nan |
|     18 | SRAIL.SW | SRAIL.SW                   | EUROPE   |                3.23 |             74.23 |         84.68 |         77.38 |          71.07 |        63.46 |           80.12 |             76.58 |             28.53 |         5.4  |             69.68 | short              |                0.53 |                  3.06 |                  nan |
|     19 | SSRM     | SSRM                       | US       |                6.68 |             73.97 |         79.18 |         73.36 |          71.02 |        74.58 |           65.03 |             73.67 |             83.41 |         7.03 |             68.32 | short              |                4.83 |                 -0.17 |                  nan |
|     20 | WDAY     | WDAY                       | US       |               43.63 |             73.85 |         82.3  |         79.37 |          68.34 |        62.6  |           73.33 |             80.08 |             40.54 |         8.39 |             68.2  | short              |                5.01 |                  1.51 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.3  |                  78.57 |                    77.44 |                 78.88 |              78.18 |                87.39 |                   12.61 |           86.35 |             58.81 |       0.8   |         nan |       nan |      nan    |       -85.14 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            2 | BBWI     | Bath & Body Works, Inc.          | US       |                3.34 |                  79.66 |                    73.25 |                 71.59 |              71.82 |                61.03 |                   38.97 |           85.51 |             34.75 |       0.197 |         nan |       nan |        5.86 |         6.85 |          5.04 |        0.68 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              215.49 |                  64.6  |                    72.76 |                 75.48 |              68.61 |                84.08 |                   15.92 |           93.42 |             69.64 |     nan     |         nan |       nan |      nan    |         9.85 |         10.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | STNE     | StoneCo Ltd.                     | OTHER    |                1.93 |                  75.23 |                    72.62 |                 72.66 |              71.75 |                71.75 |                   28.25 |           84.18 |             46.67 |       0.609 |         nan |       nan |        1.62 |         4.15 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.41 |                  72.81 |                    71.57 |                 72.91 |              70.67 |                67.45 |                   32.55 |           83.48 |             61.08 |       0.021 |         nan |       nan |        3.78 |         6.67 |          4.63 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | GSL      | Global Ship Lease, Inc.          | OTHER    |                1.38 |                  79.95 |                    71.52 |                 70.22 |              73.42 |                68.82 |                   31.18 |           74.89 |             34.67 |       0.081 |         nan |       nan |        3.87 |         5.02 |          4.34 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.59 |                  67.73 |                    70.28 |                 72.61 |              69.22 |                77.73 |                   22.27 |           83.1  |             64.65 |       0.179 |         nan |       nan |        4.28 |         2.75 |          5.23 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.55 |                  61.63 |                    69.08 |                 72.32 |              65.17 |                82.01 |                   17.99 |           92.93 |             60.35 |       0.154 |         nan |       nan |        0.76 |         5.24 |          5.07 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR  | CMBT.BR                          | EUROPE   |                4.61 |                  54.81 |                    68.97 |                 73.66 |              62.98 |                86.24 |                   13.76 |           96.3  |             79.91 |     nan     |         nan |       nan |      nan    |         8.87 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | IHS      | IHS Holding Limited              | OTHER    |                2.44 |                  73.64 |                    68.14 |                 67.98 |              72.16 |                60.45 |                   39.55 |           53.5  |             82.64 |      -0.115 |         nan |       nan |        7.47 |        15.2  |          5.13 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | NAT      | NAT                              | US       |                1.24 |                  54.71 |                    67.8  |                 72.1  |              62.94 |                82.73 |                   17.27 |           88.38 |             86.5  |     nan     |         nan |       nan |      nan    |        14.88 |         26.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                              | US       |               14.99 |                  67.83 |                    67.75 |                 68.04 |              64.59 |                70.68 |                   29.32 |           89.47 |             30.3  |     nan     |         nan |       nan |      nan    |         7.41 |          5.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | DAC      | Danaos Corporation               | OTHER    |                2.37 |                  64.59 |                    67.43 |                 69.57 |              66.4  |                79.21 |                   20.79 |           80.65 |             56.39 |       0.002 |         nan |       nan |        4.05 |         6.15 |          5.1  |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                              | US       |                8.49 |                  57.65 |                    67.33 |                 70.61 |              63.51 |                77.38 |                   22.62 |           83.83 |             80.69 |     nan     |         nan |       nan |      nan    |        10.14 |         10.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                               | US       |               93.68 |                  56.42 |                    67.01 |                 70.5  |              62.73 |                79.94 |                   20.06 |           86.15 |             77.21 |     nan     |         nan |       nan |      nan    |         9.51 |         20.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                           | EUROPE   |               15.64 |                  61.7  |                    66.82 |                 68.5  |              63.13 |                76.96 |                   23.04 |           87.68 |             48.47 |     nan     |         nan |       nan |      nan    |         8.73 |          7.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS                         | EUROPE   |               14.59 |                  57.01 |                    66.6  |                 69.46 |              62.85 |                82.14 |                   17.86 |           83.86 |             70.12 |     nan     |         nan |       nan |      nan    |        11.25 |         14.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | UNIT     | Uniti Group Inc.                 | US       |                2.1  |                  80.26 |                    66.48 |                 63.35 |              68.69 |                44.44 |                   55.56 |           64.86 |             28.98 |      -0.106 |         nan |       nan |        9.13 |       -14.11 |          2.61 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           11 | WB       | Weibo Corporation                | OTHER    |                1.48 |                  77.93 |                    66.39 |                 62.38 |              68.54 |                57.61 |                   42.39 |           62.28 |             20.67 |     nan     |         nan |       nan |        1.96 |         5.45 |          5.78 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BIRG.IR  | BIRG.IR                          | EUROPE   |               17.7  |                  58.07 |                    65.95 |                 68.76 |              60.32 |                78.33 |                   21.67 |           97.01 |             44.16 |     nan     |         nan |       nan |      nan    |        10.27 |         13.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.3  |                  78.57 |                    77.44 |                 78.88 |              78.18 |                87.39 |                   12.61 |           86.35 |             58.81 |       0.8   |         nan |       nan |      nan    |       -85.14 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              215.49 |                  64.6  |                    72.76 |                 75.48 |              68.61 |                84.08 |                   15.92 |           93.42 |             69.64 |     nan     |         nan |       nan |      nan    |         9.85 |         10.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                          | EUROPE   |                4.61 |                  54.81 |                    68.97 |                 73.66 |              62.98 |                86.24 |                   13.76 |           96.3  |             79.91 |     nan     |         nan |       nan |      nan    |         8.87 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.41 |                  72.81 |                    71.57 |                 72.91 |              70.67 |                67.45 |                   32.55 |           83.48 |             61.08 |       0.021 |         nan |       nan |        3.78 |         6.67 |          4.63 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | STNE     | StoneCo Ltd.                     | OTHER    |                1.93 |                  75.23 |                    72.62 |                 72.66 |              71.75 |                71.75 |                   28.25 |           84.18 |             46.67 |       0.609 |         nan |       nan |        1.62 |         4.15 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.59 |                  67.73 |                    70.28 |                 72.61 |              69.22 |                77.73 |                   22.27 |           83.1  |             64.65 |       0.179 |         nan |       nan |        4.28 |         2.75 |          5.23 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.55 |                  61.63 |                    69.08 |                 72.32 |              65.17 |                82.01 |                   17.99 |           92.93 |             60.35 |       0.154 |         nan |       nan |        0.76 |         5.24 |          5.07 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | NAT      | NAT                              | US       |                1.24 |                  54.71 |                    67.8  |                 72.1  |              62.94 |                82.73 |                   17.27 |           88.38 |             86.5  |     nan     |         nan |       nan |      nan    |        14.88 |         26.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | BBWI     | Bath & Body Works, Inc.          | US       |                3.34 |                  79.66 |                    73.25 |                 71.59 |              71.82 |                61.03 |                   38.97 |           85.51 |             34.75 |       0.197 |         nan |       nan |        5.86 |         6.85 |          5.04 |        0.68 |                 nan |              nan |                  11 |                  0.58 |
|          nan | FRO      | FRO                              | US       |                8.49 |                  57.65 |                    67.33 |                 70.61 |              63.51 |                77.38 |                   22.62 |           83.83 |             80.69 |     nan     |         nan |       nan |      nan    |        10.14 |         10.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                               | US       |               93.68 |                  56.42 |                    67.01 |                 70.5  |              62.73 |                79.94 |                   20.06 |           86.15 |             77.21 |     nan     |         nan |       nan |      nan    |         9.51 |         20.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | GSL      | Global Ship Lease, Inc.          | OTHER    |                1.38 |                  79.95 |                    71.52 |                 70.22 |              73.42 |                68.82 |                   31.18 |           74.89 |             34.67 |       0.081 |         nan |       nan |        3.87 |         5.02 |          4.34 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            9 | DAC      | Danaos Corporation               | OTHER    |                2.37 |                  64.59 |                    67.43 |                 69.57 |              66.4  |                79.21 |                   20.79 |           80.65 |             56.39 |       0.002 |         nan |       nan |        4.05 |         6.15 |          5.1  |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|          nan | ASRNL.AS | ASRNL.AS                         | EUROPE   |               14.59 |                  57.01 |                    66.6  |                 69.46 |              62.85 |                82.14 |                   17.86 |           83.86 |             70.12 |     nan     |         nan |       nan |      nan    |        11.25 |         14.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                          | EUROPE   |               17.7  |                  58.07 |                    65.95 |                 68.76 |              60.32 |                78.33 |                   21.67 |           97.01 |             44.16 |     nan     |         nan |       nan |      nan    |        10.27 |         13.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                           | EUROPE   |               15.64 |                  61.7  |                    66.82 |                 68.5  |              63.13 |                76.96 |                   23.04 |           87.68 |             48.47 |     nan     |         nan |       nan |      nan    |         8.73 |          7.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           15 | HMC      | Honda Motor Co., Ltd.            | OTHER    |               35.68 |                  58.96 |                    65.18 |                 68.47 |              64.23 |                74.48 |                   25.52 |           72.83 |             83.74 |       0.04  |         nan |       nan |        7.16 |         6.42 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|          nan | NLY      | NLY                              | US       |               14.99 |                  67.83 |                    67.75 |                 68.04 |              64.59 |                70.68 |                   29.32 |           89.47 |             30.3  |     nan     |         nan |       nan |      nan    |         7.41 |          5.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | IHS      | IHS Holding Limited              | OTHER    |                2.44 |                  73.64 |                    68.14 |                 67.98 |              72.16 |                60.45 |                   39.55 |           53.5  |             82.64 |      -0.115 |         nan |       nan |        7.47 |        15.2  |          5.13 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | GL9.IR   | GL9.IR                           | EUROPE   |                5.36 |                  42.5  |                    61.58 |                 67.67 |              53.68 |                87.84 |                   12.16 |           97.86 |             72.66 |     nan     |         nan |       nan |      nan    |        15.32 |         26.72 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                       | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | NAT      | NAT                        | US       |                1.24 |                     0.04 |    -0.03 |      0.04 |                  67.2  |                        81.06 |         64.45 |         80.66 |          82.27 |        78.68 |           88.38 |             86.5  |         4.59 |
|               2 | CAKE     | CAKE                       | US       |                4.81 |                     0.04 |    -0.01 |      0.11 |                  67.58 |                        78    |         74.17 |         81.29 |          77.38 |        67.94 |           86.76 |             65.78 |         5.71 |
|               3 | AVAH     | AVAH                       | US       |                2.51 |                     0.04 |     0.01 |      0.42 |                  55.64 |                        77.39 |         85.87 |         80.67 |          73.44 |        70.93 |           92.66 |             50.48 |         7.36 |
|               4 | SSRM     | SSRM                       | US       |                6.68 |                     0.05 |    -0.01 |      0.46 |                  70.81 |                        74.27 |         79.18 |         73.36 |          71.02 |        74.58 |           65.03 |             73.67 |         7.03 |
|               5 | PARR     | Par Pacific Holdings, Inc. | US       |                3.41 |                     0.05 |    -0    |     -0.08 |                  68.4  |                        74.23 |         61.28 |         76.22 |          80.99 |        79.4  |           83.48 |             61.08 |         6.87 |
|               6 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.65 |                     0.04 |    -0.03 |      0.12 |                  66.49 |                        74.11 |         74.61 |         74.8  |          72.44 |        69.57 |           76.34 |             76.46 |         5.09 |
|               7 | PR       | PR                         | US       |               16.41 |                     0.05 |    -0.04 |      0.07 |                  80.02 |                        74.07 |         66.14 |         72.42 |          75.08 |        76.33 |           76.22 |             70.76 |         4.02 |
|               8 | KRX.IR   | KRX.IR                     | EUROPE   |               18.37 |                     0.02 |     0.01 |      0.27 |                  43.75 |                        72.35 |         79.96 |         68.16 |          64.02 |        62.68 |           96.76 |             43.05 |         5.08 |
|               9 | CVE      | CVE                        | US       |               50.26 |                     0.04 |    -0.04 |      0.05 |                  74.12 |                        72.1  |         62.91 |         71.25 |          75.26 |        73    |           75.69 |             68.11 |         4.67 |
|              10 | HMC      | Honda Motor Co., Ltd.      | OTHER    |               35.68 |                     0.05 |    -0.05 |      0.06 |                  78    |                        71.89 |         58.25 |         66.12 |          64.68 |        69.69 |           72.83 |             83.74 |         3.69 |
|              11 | IAG      | IAG                        | US       |               10.15 |                     0.07 |    -0.03 |      0.45 |                  68.35 |                        71.88 |         75.75 |         61.51 |          64.73 |        75.02 |           74.34 |             59.24 |         7.62 |
|              12 | MP       | MP                         | US       |                8.63 |                     0.07 |    -0.07 |      0.36 |                  82.36 |                        71.71 |         69.23 |         50.61 |          48.78 |        46.28 |           58    |             87.56 |         8.76 |
|              13 | BAX      | BAX                        | US       |               11.66 |                     0.08 |    -0.01 |     -0    |                  58.73 |                        71.7  |         57.67 |         74.35 |          71.67 |        70.17 |           75.85 |             70.33 |         5.92 |
|              14 | VWS.CO   | VWS.CO                     | EUROPE   |               27.72 |                     0.02 |     0.02 |      0.21 |                  47.16 |                        71.45 |         78.54 |         64.37 |          64.05 |        60.58 |           88.49 |             49.41 |         5.49 |
|              15 | FSM      | FSM                        | US       |                3.13 |                     0.04 |     0.02 |      0.45 |                  58.77 |                        71.14 |         80.58 |         63.42 |          61.49 |        74.76 |           76.84 |             44.44 |         7.05 |
|              16 | TOST     | TOST                       | US       |               17.53 |                     0.05 |    -0.04 |      0.09 |                  79.12 |                        70.98 |         61.8  |         70.85 |          61.12 |        54.51 |           65.13 |             71.06 |         6.76 |
|              17 | REP.MC   | REP.MC                     | EUROPE   |               28.9  |                     0.05 |    -0.05 |      0.01 |                  84.82 |                        70.95 |         51.35 |         69.18 |          73.48 |        70.1  |           62.66 |             74    |         3.68 |
|              18 | CRGY     | CRGY                       | US       |                3.86 |                     0.04 |    -0.04 |      0.19 |                  70.47 |                        70.86 |         73.37 |         71.88 |          70.95 |        77.53 |           70.37 |             63.51 |         5.94 |
|              19 | AG       | AG                         | US       |                8.83 |                     0.05 |    -0.02 |      0.38 |                  69.26 |                        70.66 |         70.44 |         47.43 |          57.36 |        66.04 |           88.48 |             49.04 |         8.36 |
|              20 | APA      | APA                        | US       |               12.86 |                     0.04 |    -0.02 |      0.14 |                  68.3  |                        70.5  |         72.79 |         72.23 |          74.17 |        74.41 |           73.92 |             60.5  |         5.47 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1514.17 |             49.75 |         38.88 |         41.78 |          57.72 |        60.58 |           90.54 |             57.78 |             26.48 |         6.04 |             89.18 | long               |               -0.23 |                 -0.03 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             46.64 |         40.73 |         42.57 |          50.72 |        63.25 |           61.05 |             54.06 |             89.63 |         4.17 |             82.14 | long               |                1.28 |                  0.21 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |             45.92 |         39.01 |         39.23 |          52.61 |        64.19 |           85.51 |             43.43 |             54.51 |         3.7  |             75.81 | long               |               10.05 |                 -0.47 |                  nan |
|    nan | ORCL     | Oracle Corporation                                   | US       |              374.99 |             43.33 |         59.92 |         38.81 |          42.01 |        44.64 |           60.11 |             61.26 |             30.03 |         7.93 |             89.54 | short              |               -2.75 |                  0.17 |                  nan |
|    nan | MTRX     | Matrix Service Company                               | US       |                0.26 |             39.57 |         34.6  |         36.26 |          42.88 |        48.76 |           39.89 |             63.15 |             73.11 |         5.87 |             80.44 | long               |                2.3  |                nan    |                  nan |
|    nan | SHOE     | Shoe Station Group Inc.                              | US       |                0.32 |             31.12 |         23.72 |         26.22 |          36.03 |        46.42 |           50.36 |             40.79 |             58.3  |         6.7  |             84.21 | long               |                3.49 |                nan    |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      2 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.61 |             80.81 |         79.14 |         79.89 |          82.69 |        81.73 |           96.3  |             79.91 |             60.74 |         3.75 |             69.68 | medium             |                9.81 |                  4.92 |                  nan |
|     49 | CRWD     | CRWD     | US       |              192.99 |             70.54 |         77.19 |         75.21 |          65.87 |        44.11 |           36.53 |             87.98 |              1.64 |         7.34 |             69.68 | short              |               -3.01 |                  4.25 |                  nan |
|      4 | OKTA     | OKTA     | US       |               25.08 |             79.66 |         85.7  |         82.63 |          76.68 |        63.66 |           77.25 |             79.83 |             16.67 |         7.55 |             67.86 | short              |                4.28 |                  3.25 |                  nan |
|     18 | SRAIL.SW | SRAIL.SW | EUROPE   |                3.23 |             74.23 |         84.68 |         77.38 |          71.07 |        63.46 |           80.12 |             76.58 |             28.53 |         5.4  |             69.68 | short              |                0.53 |                  3.06 |                  nan |
|    301 | BHVN     | BHVN     | US       |                2.01 |             58.62 |         72.65 |         65.12 |          52.13 |        40.7  |           51.2  |             53.53 |              1.9  |         8.88 |             66.84 | short              |                4.35 |                  2.57 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    707 | DNUT     | DNUT   | US       |                0.52 |             34.48 |         55.67 |         36.82 |          32.14 |        30.41 |           21.77 |             39.93 |             25.47 |         6.85 |             69.68 | short              |                4.57 |                 -3.49 |                  nan |
|    582 | ENI.MI   | ENI.MI | EUROPE   |               65.67 |             47.44 |         33.89 |         41.32 |          53.57 |        56.88 |           59.5  |             30.93 |             59.92 |         3.32 |             67.86 | long               |                1.72 |                 -3.48 |                  nan |
|    466 | SDF.DE   | SDF.DE | EUROPE   |                2.92 |             53.75 |         69.25 |         54.07 |          53.42 |        51.7  |          nan    |             53.69 |             42.93 |         4.09 |             62.41 | short              |                1.06 |                 -3.03 |                  nan |
|    701 | LDO.MI   | LDO.MI | EUROPE   |               30.5  |             34.96 |         30.05 |         35.26 |          37.87 |        34.65 |          nan    |             44.94 |             19.28 |         4.41 |             66.84 | medium             |              nan    |                 -2.99 |                  nan |
|    449 | AZTA     | AZTA   | US       |                1.25 |             54.08 |         61.15 |         62.37 |          47    |        38.1  |           28.8  |             47.01 |             26.9  |         7.84 |             67.64 | swing              |              nan    |                 -2.96 |                  nan |

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
- Excluded by hard/data filters: **271**
- Event watch (otherwise eligible): **6**
- Final eligible: **723**
- Eligible change vs previous stored run: **-6**

Top exclusion categories:
- liquidity: 219
- price: 162
- market_cap: 159
- price_history: 12
- data_confidence: 8
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 5 | 4 | 5 | 2 | 3 | main,value,pullback,quality_value |
| NAT | 3 |  | 1 |  | 2 | main,pullback |
| AVAH | 7 |  | 3 |  | 2 | main,pullback |
| CAKE | 10 |  | 2 |  | 2 | main,pullback |
| BION.SW | 15 | 1 | 27 | 1 | 1 | value,quality_value |
| DAC | 38 | 9 |  | 8 | 1 | value,quality_value |
| DDI | 39 | 7 |  | 5 | 1 | value,quality_value |
| IRWD | 94 | 6 | 54 | 4 | 1 | value,quality_value |
| HMC | 127 | 15 | 10 | 9 | 1 | pullback,quality_value |
| GSL | 130 | 5 | 165 | 7 | 1 | value,quality_value |
| IHS | 333 | 8 |  | 10 | 1 | value,quality_value |
| BBWI | 586 | 2 | 266 | 6 | 1 | value,quality_value |
| STNE | 632 | 3 |  | 3 | 1 | value,quality_value |
| FRO | 1 |  |  |  | 1 | main |
| CMBT.BR | 2 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **6** (FRO, CMBT.BR, OKTA, DK, PAGP, NIQ)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (KRX.IR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | IRWD | value+pullback | 73.58 | 67.73 | 75.14 | 83.10 | 64.65 | 77.73 | 66.89 |
| 2 | BION.SW | value+pullback | 71.53 | 78.57 | 46.59 | 86.35 | 58.81 | 87.39 | 74.36 |
| 3 | HMC | value+pullback | 71.38 | 58.96 | 78.00 | 72.83 | 83.74 | 74.48 | 65.40 |
| 4 | PARR | value+pullback | 71.06 | 72.81 | 68.40 | 83.48 | 61.08 | 67.45 | 77.81 |
| 5 | BBWI | value+pullback | 67.42 | 79.66 | 60.06 | 85.51 | 34.75 | 61.03 | 47.03 |
| 6 | XNET | value+pullback | 64.60 | 59.23 | 67.50 | 57.83 | 79.67 | 66.54 | 42.42 |
| 7 | GSL | value+pullback | 63.16 | 79.95 | 42.85 | 74.89 | 34.67 | 68.82 | 65.16 |
| 8 | MFA | value+pullback | 62.53 | 59.50 | 66.23 | 79.64 | 34.54 | 63.60 | 42.92 |
| 9 | WKC | value+pullback | 62.03 | 61.83 | 51.15 | 64.35 | 75.09 | 67.67 | 70.21 |
| 10 | AIR.PA | value+pullback | 61.31 | 60.67 | 70.10 | 66.09 | 56.19 | 50.29 | 58.24 |
| 11 | INVA | value+pullback | 60.64 | 57.70 | 52.87 | 75.26 | 36.09 | 76.05 | 46.48 |
| 12 | ALL-PH | value+pullback | 59.33 | 60.19 | 58.76 | 70.38 | 41.88 | 59.19 | 45.41 |
| 13 | UNIT | value+pullback | 59.07 | 80.26 | 53.90 | 64.86 | 28.98 | 44.44 | 48.57 |
| 14 | TV | value+pullback | 57.76 | 65.08 | 68.77 | 44.82 | 28.82 | 57.20 | 39.40 |
| 15 | BP | pullback | 56.85 | 56.42 | 80.88 | 86.15 | 77.21 | 79.94 | 64.23 |
| 16 | MAU.PA | value+pullback | 56.65 | 65.30 | 72.62 | 60.87 | 9.84 | 43.94 | 42.47 |
| 17 | GL9.IR | pullback | 55.69 | 42.50 | 64.71 | 97.86 | 72.66 | 87.84 | 63.45 |
| 18 | DEC | value+pullback | 55.40 | 62.75 | 48.14 | 65.65 | 54.76 | 46.06 | 58.18 |
| 19 | ONIT | value+pullback | 55.28 | 70.68 | 46.30 | 63.94 | 43.48 | 42.82 | 43.43 |
| 20 | NAT | pullback | 55.25 | 54.71 | 67.20 | 88.38 | 86.50 | 82.73 | 79.67 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.2 | 4 / 6 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 68.3 | 12 / 13 |
| Top 50 | 48/50 | 50/50 | 49/50 | 47/50 | 0/50 | 68.7 | 22 / 28 |

Top-10 market-cap mix: small_1_5b=7, mid_5_20b=2, large_20_100b=1
