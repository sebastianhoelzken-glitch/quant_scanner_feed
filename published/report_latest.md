# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-01

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
- **OTHER:** 71.8/100
- **US:** 83.7/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | VLO      | VLO                        | US       |               89.17 |             80.63 |         81.47 |         82.86 |          79.79 |        76.08 |           84.61 |             62    |             57.77 |         3.16 |             67.5  | swing              |              nan    |                nan    |               nan    |
|      2 | DK       | DK                         | US       |                3.93 |             79.92 |         85.92 |         85.03 |          74.8  |        59.82 |           54.11 |             85.22 |             29.67 |         6.91 |             69.68 | short              |                2.54 |                  0.14 |                 0.72 |
|      3 | MPC      | MPC                        | US       |               90.46 |             79.37 |         83.21 |         81.4  |          77.34 |        73.95 |           83.9  |             53.49 |             56.31 |         3.79 |             69.68 | short              |              nan    |                nan    |               nan    |
|      4 | SM       | SM                         | US       |                7.63 |             79.12 |         81.61 |         76    |          76.86 |        81.38 |           80.46 |             64.98 |             95.81 |         6.98 |             68.66 | short              |                1.14 |                  0.61 |                 0.09 |
|      5 | FRO      | FRO                        | US       |                8.41 |             78.64 |         74.08 |         78    |          79.28 |        82.39 |           92.13 |             69.33 |             67.84 |         5.27 |             69.68 | long               |               -1.76 |                  2.79 |               nan    |
|      6 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.56 |             77.88 |         77.26 |         74.42 |          78.5  |        79.63 |           96.03 |             61.72 |             61.05 |         3.84 |             69.68 | long               |               -1.67 |                  4.43 |               nan    |
|      7 | PARR     | Par Pacific Holdings, Inc. | US       |                3.45 |             77.82 |         68.67 |         76.9  |          80.29 |        78.74 |           79.57 |             62.98 |             75.3  |         6.89 |             85.07 | medium             |               -0.15 |                  0.72 |                 0.56 |
|      8 | AVAH     | AVAH                       | US       |                2.53 |             77.75 |         82.42 |         81.42 |          74.08 |        71.19 |           92.99 |             52.88 |             39.67 |         7.32 |             68.66 | short              |               -0.01 |                 -0.29 |                -0.98 |
|      9 | OKTA     | OKTA                       | US       |               26.1  |             77.47 |         88.07 |         81.83 |          73.12 |        58.44 |           65.5  |             81.1  |             15.48 |         7.44 |             68.66 | short              |               -2.38 |                  2.95 |                 3.42 |
|     10 | BMAG.VI  | BMAG.VI                    | EUROPE   |                1.08 |             77.11 |         88.12 |         82    |          72.21 |        47.21 |          nan    |            nan    |             21.84 |         6.83 |             60    | short              |                8.34 |                  1.63 |               nan    |
|     11 | NAT      | NAT                        | US       |                1.25 |             76.35 |         67.4  |         77.29 |          77.45 |        75.41 |           86.57 |             72.41 |             47.65 |         4.69 |             69.68 | medium             |               -0.11 |                nan    |               nan    |
|     12 | PAGP     | PAGP                       | US       |                5.67 |             76.3  |         79.3  |         76.73 |          75.87 |        73.45 |           82.24 |             78.32 |             52.87 |         1.72 |             66.7  | short              |                0.27 |                 -0.02 |                -0.48 |
|     13 | WT       | WT                         | US       |                3.15 |             75.52 |         77.14 |         78.62 |          73.9  |        64.9  |           72.07 |             79.8  |             30.1  |         5.35 |             69.68 | swing              |              nan    |                 -0.38 |               nan    |
|     14 | PR       | PR                         | US       |               16.83 |             75.13 |         74.2  |         75.1  |          75.17 |        75.99 |           76.53 |             71.22 |             71.92 |         4.12 |             68.32 | long               |                1.14 |                  1.07 |               nan    |
|     15 | RNG      | RNG                        | US       |                5.02 |             74.64 |         79.89 |         82.76 |          69.38 |        54.94 |           22.82 |             83.8  |             59.75 |         7.04 |             67.75 | swing              |               -0.68 |                  0.4  |                 1.22 |
|     16 | DAR      | DAR                        | US       |                9.02 |             74.38 |         76.74 |         65.01 |          72.03 |        76.73 |           90.24 |             52.94 |             64.88 |         4.09 |             67.86 | short              |                6.19 |                  2.47 |               nan    |
|     17 | SSRM     | SSRM                       | US       |                6.62 |             74.33 |         77.82 |         75.21 |          70.58 |        73.45 |           64.66 |             68.66 |             80.63 |         7.01 |             68.32 | short              |                1.45 |                 -0.59 |               nan    |
|     18 | SRAIL.SW | SRAIL.SW                   | EUROPE   |                3.18 |             74.23 |         85.49 |         77.17 |          71.29 |        64.04 |           79.91 |             76.03 |             28.37 |         5.15 |             69.68 | short              |               -1.78 |                  0.07 |                -0.63 |
|     19 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.68 |             74.05 |         75.53 |         75.65 |          72.56 |        69.68 |           74.06 |             78.46 |             45.5  |         5.14 |             84.92 | swing              |                0.4  |                  1.47 |                 1.38 |
|     20 | 0P6O.IL  | 0P6O.IL                    | OTHER    |               42.98 |             73.94 |         74.81 |         87.55 |          72.8  |        73.06 |          nan    |            nan    |             73.91 |         7.8  |             60    | swing              |               29.75 |                  8.47 |                 6.64 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              216.45 |                  65.93 |                    73.94 |                 76.59 |              70.08 |                84.97 |                   15.03 |           92.83 |             73.15 |     nan     |         nan |       nan |      nan    |         9.83 |         10.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.54 |                  69.69 |                    73.58 |                 75.94 |              71.24 |                82.93 |                   17.07 |           91.77 |             61.32 |       0.154 |         nan |       nan |        0.75 |         5.22 |          5.05 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.61 |                  70.04 |                    72.11 |                 74.41 |              71.29 |                79.19 |                   20.81 |           84.41 |             66.07 |       0.173 |         nan |       nan |        4.28 |         2.83 |          5.38 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.39 |                  81.02 |                    71.8  |                 69.84 |              74.86 |                72.22 |                   27.78 |           69.02 |             35.3  |       0.081 |         nan |       nan |        3.83 |         5.03 |          4.34 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|            4 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.45 |                  73.74 |                    71.56 |                 72.52 |              71.39 |                66.67 |                   33.33 |           79.57 |             62.98 |       0.021 |         nan |       nan |        3.89 |         6.76 |          4.63 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | STNE     | StoneCo Ltd.                         | OTHER    |                1.93 |                  75.56 |                    71.43 |                 70.78 |              70.46 |                69.61 |                   30.39 |           84.18 |             35.27 |       0.611 |         nan |       nan |        1.62 |         4.16 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA     | NVIDIA Corporation                   | US       |             4600.22 |                  61.64 |                    70.68 |                 72.45 |              65.58 |                76.84 |                   23.16 |           88.51 |             73.71 |       0.008 |         nan |       nan |       26.32 |        14.33 |         27.88 |        0.63 |                 nan |              nan |                  12 |                  0.63 |
|            7 | BBWI     | Bath & Body Works, Inc.              | US       |                3.35 |                  78.03 |                    70.06 |                 67.08 |              70    |                57.43 |                   42.57 |           72.54 |             34.8  |       0.197 |         nan |       nan |        5.95 |         6.86 |          5.05 |        0.72 |                 nan |              nan |                  11 |                  0.58 |
|            8 | IHS      | IHS Holding Limited                  | OTHER    |                2.46 |                  71.77 |                    68.19 |                 68.49 |              71.73 |                64.59 |                   35.41 |           55.43 |             84.31 |      -0.114 |         nan |       nan |        7.51 |        15.29 |          5.13 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO      | FRO                                  | US       |                8.41 |                  58.81 |                    68.17 |                 71.56 |              63.27 |                77.74 |                   22.26 |           92.13 |             69.33 |     nan     |         nan |       nan |      nan    |        10.16 |          6.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.64 |                  62.72 |                    67.97 |                 69.65 |              64.56 |                78.11 |                   21.89 |           86.76 |             53.43 |     nan     |         nan |       nan |      nan    |         8.76 |          7.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              102.8  |                  79.06 |                    67.66 |                 65.29 |              73.12 |                49.96 |                   50.04 |           45.65 |             72.04 |       0.153 |         nan |       nan |        1.75 |         7.07 |          4.39 |        4.14 |                 nan |              nan |                  12 |                  0.63 |
|          nan | NLY      | NLY                                  | US       |               14.91 |                  68.07 |                    67.57 |                 67.73 |              64.57 |                70    |                   30    |           88.6  |             29.63 |     nan     |         nan |       nan |      nan    |         7.37 |          5.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |               95.27 |                  57.08 |                    67.21 |                 70.55 |              63.14 |                79.5  |                   20.5  |           85.35 |             77.32 |     nan     |         nan |       nan |      nan    |         9.67 |         20.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS                             | EUROPE   |               14.62 |                  57.93 |                    66.99 |                 69.66 |              63.58 |                81.82 |                   18.18 |           82.43 |             71.36 |     nan     |         nan |       nan |      nan    |        11.26 |         14.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | UNIT     | Uniti Group Inc.                     | US       |                2.08 |                  80.26 |                    66.89 |                 63.96 |              68.89 |                45.1  |                   54.9  |           66.38 |             29.85 |      -0.107 |         nan |       nan |        9.09 |       -13.97 |          2.61 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           11 | KSS      | Kohl's Corporation                   | US       |                1.74 |                  76.95 |                    66.64 |                 63.39 |              69.49 |                43.7  |                   56.3  |           51.52 |             62.23 |       0.466 |         nan |       nan |        5.89 |        11.38 |          7.52 |        1.99 |                 nan |              nan |                  11 |                  0.58 |
|          nan | NAT      | NAT                                  | US       |                1.25 |                  57.12 |                    66.53 |                 69.77 |              62.24 |                77.1  |                   22.9  |           86.57 |             72.41 |     nan     |         nan |       nan |      nan    |        15.01 |         11.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               17.9  |                  59.16 |                    66.42 |                 69.02 |              61.02 |                78.05 |                   21.95 |           96.47 |             43.81 |     nan     |         nan |       nan |      nan    |        10.39 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.63 |                  62.25 |                    66.18 |                 67.94 |              63.4  |                67.11 |                   32.89 |           80.46 |             64.98 |     nan     |         nan |       nan |      nan    |         4.96 |          6.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              216.45 |                  65.93 |                    73.94 |                 76.59 |              70.08 |                84.97 |                   15.03 |           92.83 |             73.15 |     nan     |         nan |       nan |      nan    |         9.83 |         10.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  69.69 |                    73.58 |                 75.94 |              71.24 |                82.93 |                   17.07 |           91.77 |             61.32 |       0.154 |         nan |       nan |        0.75 |         5.22 |          5.05 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.61 |                  70.04 |                    72.11 |                 74.41 |              71.29 |                79.19 |                   20.81 |           84.41 |             66.07 |       0.173 |         nan |       nan |        4.28 |         2.83 |          5.38 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.45 |                  73.74 |                    71.56 |                 72.52 |              71.39 |                66.67 |                   33.33 |           79.57 |             62.98 |       0.021 |         nan |       nan |        3.89 |         6.76 |          4.63 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA     | NVIDIA Corporation               | US       |             4600.22 |                  61.64 |                    70.68 |                 72.45 |              65.58 |                76.84 |                   23.16 |           88.51 |             73.71 |       0.008 |         nan |       nan |       26.32 |        14.33 |         27.88 |        0.63 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                              | US       |                8.41 |                  58.81 |                    68.17 |                 71.56 |              63.27 |                77.74 |                   22.26 |           92.13 |             69.33 |     nan     |         nan |       nan |      nan    |        10.16 |          6.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | STNE     | StoneCo Ltd.                     | OTHER    |                1.93 |                  75.56 |                    71.43 |                 70.78 |              70.46 |                69.61 |                   30.39 |           84.18 |             35.27 |       0.611 |         nan |       nan |        1.62 |         4.16 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                               | US       |               95.27 |                  57.08 |                    67.21 |                 70.55 |              63.14 |                79.5  |                   20.5  |           85.35 |             77.32 |     nan     |         nan |       nan |      nan    |         9.67 |         20.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                          | EUROPE   |                4.56 |                  54.78 |                    66.02 |                 69.93 |              60.03 |                80.08 |                   19.92 |           96.03 |             61.72 |     nan     |         nan |       nan |      nan    |         8.71 |          6.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | GSL      | Global Ship Lease, Inc.          | OTHER    |                1.39 |                  81.02 |                    71.8  |                 69.84 |              74.86 |                72.22 |                   27.78 |           69.02 |             35.3  |       0.081 |         nan |       nan |        3.83 |         5.03 |          4.34 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|          nan | NAT      | NAT                              | US       |                1.25 |                  57.12 |                    66.53 |                 69.77 |              62.24 |                77.1  |                   22.9  |           86.57 |             72.41 |     nan     |         nan |       nan |      nan    |        15.01 |         11.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS                         | EUROPE   |               14.62 |                  57.93 |                    66.99 |                 69.66 |              63.58 |                81.82 |                   18.18 |           82.43 |             71.36 |     nan     |         nan |       nan |      nan    |        11.26 |         14.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                           | EUROPE   |               15.64 |                  62.72 |                    67.97 |                 69.65 |              64.56 |                78.11 |                   21.89 |           86.76 |             53.43 |     nan     |         nan |       nan |      nan    |         8.76 |          7.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | GL9.IR   | GL9.IR                           | EUROPE   |                5.35 |                  43.87 |                    63.03 |                 69.12 |              55.33 |                89.21 |                   10.79 |           97.87 |             76.87 |     nan     |         nan |       nan |      nan    |        15.2  |         26.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                          | EUROPE   |               17.9  |                  59.16 |                    66.42 |                 69.02 |              61.02 |                78.05 |                   21.95 |           96.47 |             43.81 |     nan     |         nan |       nan |      nan    |        10.39 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | IHS      | IHS Holding Limited              | OTHER    |                2.46 |                  71.77 |                    68.19 |                 68.49 |              71.73 |                64.59 |                   35.41 |           55.43 |             84.31 |      -0.114 |         nan |       nan |        7.51 |        15.29 |          5.13 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           15 | HMC      | Honda Motor Co., Ltd.            | OTHER    |               35.79 |                  57.21 |                    64.82 |                 68.38 |              63.59 |                77.24 |                   22.76 |           73.26 |             84.9  |       0.04  |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   8 |                  0.42 |
|           12 | TNK      | Teekay Tankers Ltd.              | OTHER    |                2.68 |                  57.66 |                    65.41 |                 68.27 |              63.8  |                80.25 |                   19.75 |           74.06 |             78.46 |       0.073 |         nan |       nan |        3.79 |         8.23 |          5.23 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM       | SM                               | US       |                7.63 |                  62.25 |                    66.18 |                 67.94 |              63.4  |                67.11 |                   32.89 |           80.46 |             64.98 |     nan     |         nan |       nan |      nan    |         4.96 |          6.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                              | US       |               14.91 |                  68.07 |                    67.57 |                 67.73 |              64.57 |                70    |                   30    |           88.6  |             29.63 |     nan     |         nan |       nan |      nan    |         7.37 |          5.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                  | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:----------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | CAKE     | CAKE                  | US       |                4.7  |                     0.07 |    -0.04 |      0.05 |                  76.74 |                        79.02 |         66.37 |         79.85 |          77.66 |        67.68 |           87.54 |             67.19 |         5.77 |
|               2 | AVAH     | AVAH                  | US       |                2.53 |                     0.03 |    -0.02 |      0.4  |                  60.66 |                        76.84 |         82.42 |         81.42 |          74.08 |        71.19 |           92.99 |             52.88 |         7.32 |
|               3 | ARGX.BR  | ARGX.BR               | EUROPE   |               54.45 |                     0.04 |     0.01 |      0.21 |                  54.63 |                        76.4  |         78.62 |         73.3  |          67.76 |        61.33 |           93.62 |             67.85 |         5.92 |
|               4 | FIGR     | FIGR                  | US       |                7.1  |                     0.11 |    -0.05 |      0.36 |                  52.64 |                        76.38 |         79.12 |         65.26 |          63.66 |        61.31 |           90.35 |             72.34 |         9.23 |
|               5 | NAT      | NAT                   | US       |                1.25 |                     0.03 |    -0.02 |      0.06 |                  60.62 |                        75.91 |         67.4  |         77.29 |          77.45 |        75.41 |           86.57 |             72.41 |         4.69 |
|               6 | FRO      | FRO                   | US       |                8.41 |                     0.02 |    -0.01 |      0.1  |                  47.9  |                        75.01 |         74.08 |         78    |          79.28 |        82.39 |           92.13 |             69.33 |         5.27 |
|               7 | WDAY     | WDAY                  | US       |               41.06 |                     0.04 |    -0.01 |      0.2  |                  66.26 |                        74.98 |         75.91 |         76.32 |          67.44 |        62.37 |           73.01 |             81.9  |         8.41 |
|               8 | WT       | WT                    | US       |                3.15 |                     0.04 |     0.01 |      0.15 |                  58.32 |                        74.44 |         77.14 |         78.62 |          73.9  |        64.9  |           72.07 |             79.8  |         5.35 |
|               9 | TNK      | Teekay Tankers Ltd.   | OTHER    |                2.68 |                     0.03 |    -0.03 |      0.12 |                  60.24 |                        73.44 |         75.53 |         75.65 |          72.56 |        69.68 |           74.06 |             78.46 |         5.14 |
|              10 | HMC      | Honda Motor Co., Ltd. | OTHER    |               35.79 |                     0.04 |    -0.02 |      0.08 |                  68.58 |                        72.63 |         63.19 |         69.9  |          66.94 |        72.08 |           73.26 |             84.9  |         3.65 |
|              11 | SSRM     | SSRM                  | US       |                6.62 |                     0.04 |    -0.03 |      0.39 |                  69.6  |                        72.58 |         77.82 |         75.21 |          70.58 |        73.45 |           64.66 |             68.66 |         7.01 |
|              12 | PR       | PR                    | US       |               16.83 |                     0.02 |    -0.02 |      0.11 |                  56.75 |                        72.05 |         74.2  |         75.1  |          75.17 |        75.99 |           76.53 |             71.22 |         4.12 |
|              13 | BAX      | BAX                   | US       |               11.6  |                     0.08 |    -0.02 |     -0.07 |                  59.07 |                        71.29 |         51.61 |         73.68 |          72.18 |        69.83 |           75.49 |             69.94 |         5.99 |
|              14 | SYENS.BR | SYENS.BR              | EUROPE   |                8.28 |                     0.02 |    -0    |      0.04 |                  46.35 |                        71.19 |         67.87 |         75.63 |          68.92 |        57.58 |           68.63 |             84.65 |         5.13 |
|              15 | CCC      | CCC                   | US       |                3.79 |                     0.02 |    -0.01 |      0.18 |                  49.74 |                        71.16 |         73.68 |         74.22 |          67.05 |        68.03 |           86.49 |             61.97 |         7.93 |
|              16 | FSM      | FSM                   | US       |                3.08 |                     0.06 |    -0.01 |      0.39 |                  72.24 |                        71.16 |         77.01 |         63.36 |          61.21 |        74.19 |           75.61 |             44.64 |         7.16 |
|              17 | AG       | AG                    | US       |                8.76 |                     0.05 |    -0.01 |      0.31 |                  72.89 |                        71.02 |         70.03 |         47.31 |          57.27 |        65.36 |           88.7  |             48.9  |         8.41 |
|              18 | GL9.IR   | GL9.IR                | EUROPE   |                5.35 |                     0.07 |    -0.02 |     -0.01 |                  65.73 |                        70.73 |         45.81 |         59.53 |          74.15 |        70.37 |           97.87 |             76.87 |         2.15 |
|              19 | AMC      | AMC                   | US       |                2.03 |                     0.02 |    -0.01 |     -0.07 |                  53.82 |                        70.7  |         51.47 |         72.61 |          74.2  |        75.27 |           85.46 |             61.52 |         9.57 |
|              20 | SBSW     | SBSW                  | US       |                7.4  |                     0.06 |    -0.05 |      0.33 |                  83.46 |                        70.65 |         70.41 |         54.68 |          57.65 |        65.81 |           50.76 |             85.14 |         8.5  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1520.35 |             52.11 |         43.91 |         44.64 |          59.58 |        61.4  |           79.84 |             66.63 |             37.21 |         8.5  |             89.18 | long               |                0.36 |                  1.06 |                 1.47 |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.09 |             50.41 |         47.75 |         41.66 |          53.07 |        63.75 |           82.67 |             43.89 |             55.36 |         3.78 |             75.81 | long               |                4.69 |                 -0.14 |                -0.13 |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.71 |             43.7  |         34.22 |         39.1  |          48.3  |        61.34 |           57.3  |             55.53 |             92    |         8.5  |             82.14 | long               |               -3.13 |                 -0.28 |                -0.09 |
|    nan | ORCL     | Oracle Corporation                                   | US       |              370.64 |             43.41 |         54.98 |         39.15 |          41.74 |        45.07 |           45.19 |             61.49 |             47.57 |         7.87 |             89.54 | short              |                0.13 |                  0.3  |                 0.25 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     20 | 0P6O.IL  | 0P6O.IL | OTHER    |               42.98 |             73.94 |         74.81 |         87.55 |          72.8  |        73.06 |          nan    |            nan    |             73.91 |         7.8  |             60    | swing              |               29.75 |                  8.47 |                 6.64 |
|      6 | CMBT.BR  | CMBT.BR | EUROPE   |                4.56 |             77.88 |         77.26 |         74.42 |          78.5  |        79.63 |           96.03 |             61.72 |             61.05 |         3.84 |             69.68 | long               |               -1.67 |                  4.43 |               nan    |
|     74 | 0MHU.IL  | 0MHU.IL | OTHER    |               21.58 |             68.73 |         74.07 |         80.19 |          63.4  |        47.08 |           50    |            nan    |             17.39 |         6.1  |             62.5  | swing              |               19.42 |                  4.08 |                 3.53 |
|     45 | CRWD     | CRWD    | US       |              204.1  |             71.51 |         81.67 |         77.19 |          65.84 |        43.91 |           35.93 |             87.79 |              1.54 |         7.39 |             69.68 | short              |                0.88 |                  3.42 |                 4.46 |
|      9 | OKTA     | OKTA    | US       |               26.1  |             77.47 |         88.07 |         81.83 |          73.12 |        58.44 |           65.5  |             81.1  |             15.48 |         7.44 |             68.66 | short              |               -2.38 |                  2.95 |                 3.42 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    519 | MRVL     | MRVL    | US       |              164.14 |             50.41 |         46.16 |         54.65 |          61.55 |        44.27 |           35.94 |             75.67 |             12.49 |         8.79 |             69.23 | medium             |               -3.94 |                 -3.24 |                -1.78 |
|    678 | 0QXR.IL  | 0QXR.IL | OTHER    |               14.77 |             38.58 |         22.65 |         27.46 |          49.71 |        70.72 |           83.33 |            nan    |             82.61 |         9.23 |             61.02 | long               |              -16.91 |                 -3.13 |                -2.68 |
|    256 | TGB      | TGB     | US       |                2.86 |             60.28 |         70.96 |         59.35 |          58.56 |        61.21 |           56.3  |             44.15 |             58.84 |         7.62 |             69.23 | short              |               -2.58 |                 -2.83 |               nan    |
|    524 | ERAS     | ERAS    | US       |                5.4  |             49.95 |         46.4  |         54.26 |          53.49 |        43.77 |           47    |             33.12 |              8.68 |         8.77 |             65.82 | swing              |               -0.86 |                 -2.72 |                -0.96 |
|    677 | HIMS     | HIMS    | US       |                5.96 |             38.61 |         34.19 |         45.11 |          43.04 |        31.9  |           34.84 |             46.77 |             11.67 |         9.53 |             69.68 | swing              |               -2.8  |                 -2.71 |               nan    |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.88

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
- Excluded by hard/data filters: **280**
- Event watch (otherwise eligible): **4**
- Final eligible: **716**
- Eligible change vs previous stored run: **-9**

Top exclusion categories:
- liquidity: 224
- price: 167
- market_cap: 165
- price_history: 13
- data_confidence: 11
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 7 | 4 |  | 3 | 2 | main,value,quality_value |
| FRO | 5 |  | 6 |  | 2 | main,pullback |
| AVAH | 8 |  | 2 |  | 2 | main,pullback |
| TNK | 19 | 12 | 9 | 9 | 1 | pullback,quality_value |
| DDI | 52 | 1 |  | 1 | 1 | value,quality_value |
| IRWD | 71 | 2 |  | 2 | 1 | value,quality_value |
| HMC | 79 | 15 | 10 | 8 | 1 | pullback,quality_value |
| NVDA | 96 | 6 |  | 4 | 1 | value,quality_value |
| GSL | 132 | 3 | 158 | 6 | 1 | value,quality_value |
| IHS | 264 | 8 |  | 7 | 1 | value,quality_value |
| BBWI | 573 | 7 | 277 | 10 | 1 | value,quality_value |
| STNE | 651 | 5 |  | 5 | 1 | value,quality_value |
| VLO | 1 |  |  |  | 1 | main |
| DK | 2 |  |  |  | 1 | main |
| MPC | 3 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (VLO, DK, MPC, SM, CMBT.BR, OKTA, BMAG.VI)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (ARGX.BR, FIGR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | HMC | value+pullback | 69.24 | 57.21 | 68.58 | 73.26 | 84.90 | 77.24 | 68.42 |
| 2 | TNK | value+pullback | 67.36 | 57.66 | 60.24 | 74.06 | 78.46 | 80.25 | 74.05 |
| 3 | GSL | value+pullback | 64.54 | 81.02 | 47.62 | 69.02 | 35.30 | 72.22 | 65.03 |
| 4 | INVA | value+pullback | 63.36 | 61.24 | 60.85 | 76.05 | 36.43 | 73.63 | 45.43 |
| 5 | XNET | value+pullback | 63.35 | 59.36 | 58.05 | 57.83 | 87.24 | 68.14 | 44.78 |
| 6 | BBWI | value+pullback | 63.33 | 78.03 | 56.28 | 72.54 | 34.80 | 57.43 | 47.49 |
| 7 | MFA | value+pullback | 62.14 | 58.02 | 68.20 | 76.97 | 35.85 | 62.79 | 42.10 |
| 8 | ALL-PH | value+pullback | 61.25 | 60.66 | 64.91 | 69.23 | 46.08 | 59.18 | 44.35 |
| 9 | UNIT | value+pullback | 60.86 | 80.26 | 59.28 | 66.38 | 29.85 | 45.10 | 47.24 |
| 10 | LYFT | value+pullback | 59.98 | 61.66 | 76.96 | 55.42 | 52.12 | 43.59 | 54.97 |
| 11 | NOVO-B.CO | value+pullback | 59.47 | 57.45 | 74.43 | 64.07 | 49.20 | 45.49 | 50.70 |
| 12 | MAGN | value+pullback | 59.24 | 68.92 | 50.73 | 62.32 | 37.97 | 63.67 | 47.92 |
| 13 | VOLV-B.ST | value+pullback | 58.89 | 61.97 | 63.39 | 52.87 | 62.07 | 51.54 | 52.83 |
| 14 | DDI | value | 57.39 | 69.69 | 47.26 | 91.77 | 61.32 | 82.93 | 70.35 |
| 15 | GL9.IR | pullback | 56.64 | 43.87 | 65.73 | 97.87 | 76.87 | 89.21 | 64.95 |
| 16 | KSS | value+pullback | 56.35 | 76.95 | 42.31 | 51.52 | 62.23 | 43.70 | 58.91 |
| 17 | IRWD | value | 56.12 | 70.04 | 50.69 | 84.41 | 66.07 | 79.19 | 68.96 |
| 18 | BP | pullback | 54.86 | 57.08 | 73.72 | 85.35 | 77.32 | 79.50 | 64.52 |
| 19 | NVDA | value | 54.51 | 61.64 | 50.50 | 88.51 | 73.71 | 76.84 | 67.39 |
| 20 | CAKE | pullback | 53.79 | 37.08 | 76.74 | 87.54 | 67.19 | 73.76 | 72.67 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 9/10 | 10/10 | 9/10 | 1/10 | 69.2 | 3 / 7 |
| Top 25 | 21/25 | 23/25 | 24/25 | 20/25 | 2/25 | 68.3 | 12 / 13 |
| Top 50 | 46/50 | 48/50 | 49/50 | 45/50 | 2/50 | 68.9 | 24 / 26 |

Top-10 market-cap mix: small_1_5b=5, mid_5_20b=2, large_20_100b=3
Top-10 sparse-data names: BMAG.VI (missing quality,revisions; conf=60.0)
