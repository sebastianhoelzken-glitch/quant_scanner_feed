# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-30

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
- **OTHER:** 74.3/100
- **US:** 84.5/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.61 |             81.52 |         79.91 |         80.84 |          83.37 |        82.2  |           96.24 |             81.26 |             60.41 |         3.82 |             69.68 | medium             |                0.71 |                  5.37 |                  nan |
|      2 | FRO      | FRO                        | US       |                8.49 |             80.42 |         78.5  |         82.42 |          80.79 |        80.04 |          nan    |             81.26 |             69.72 |         5.27 |             66.84 | swing              |               -0.84 |                  1.08 |                  nan |
|      3 | NAT      | NAT                        | US       |                1.24 |             80.24 |         65.06 |         81.31 |          82.73 |        79.16 |           88.97 |             86.95 |             49.35 |         4.66 |             69.68 | medium             |                0.56 |                  1.46 |                  nan |
|      4 | OKTA     | OKTA                       | US       |               25.08 |             78.93 |         85.66 |         82.52 |          75.33 |        61.19 |           70.18 |             80.43 |             16.7  |         7.57 |             68.32 | short              |               -0.73 |                  3.32 |                  nan |
|      5 | SM       | SM                         | US       |                7.52 |             78.34 |         75.99 |         78    |          78.68 |        82.66 |           80.87 |             66.14 |             96.87 |         7.01 |             68.66 | long               |                8.41 |                 -0.12 |                  nan |
|      6 | AVAH     | AVAH                       | US       |                2.51 |             78.2  |         86.53 |         81.83 |          74.58 |        72.08 |           93.04 |             53.16 |             42    |         7.39 |             68.66 | short              |                1.15 |                 -0.19 |                  nan |
|      7 | DK       | DK                         | US       |                3.82 |             77.67 |         79.25 |         85.45 |          76.09 |        61.69 |           55.15 |             84.6  |             34.29 |         6.84 |             69.68 | swing              |                0.48 |                  1.45 |                  nan |
|      8 | PAGP     | PAGP                       | US       |                5.62 |             76.51 |         77.94 |         76.28 |          76.73 |        74.52 |           83.44 |             76.91 |             54.66 |         1.78 |             66.7  | short              |                0.4  |                nan    |                  nan |
|      9 | RNG      | RNG                        | US       |                5    |             75.66 |         81.45 |         84.2  |          69.86 |        55.84 |           22.78 |             82.75 |             62.16 |         7.15 |             67.75 | swing              |                0.5  |                  0.9  |                  nan |
|     10 | AMC      | AMC                        | US       |                2    |             75.28 |         52.56 |         75.29 |          75.26 |        75.88 |           84.81 |             61.45 |            nan    |         9.66 |             63.43 | long               |                0.58 |                  0.18 |                  nan |
|     11 | DOCM.SW  | DOCM.SW                    | EUROPE   |                0.6  |             75.27 |         80.05 |         80.22 |          70.48 |        58.15 |           53.13 |             76.11 |             40.93 |         7.18 |             66.84 | swing              |                0.86 |                nan    |                  nan |
|     12 | PARR     | Par Pacific Holdings, Inc. | US       |                3.41 |             74.97 |         60.32 |         74.63 |          78.6  |        75.31 |           80.43 |             61.83 |             64.67 |         6.86 |             85.07 | medium             |               -2.84 |                  0.06 |                  nan |
|     13 | SRAIL.SW | SRAIL.SW                   | EUROPE   |                3.23 |             74.94 |         85.29 |         78.29 |          71.59 |        63.97 |           80.49 |             76.24 |             28.38 |         5.47 |             69.68 | short              |                0.71 |                nan    |                  nan |
|     14 | HPE      | HPE                        | US       |               59.78 |             74.8  |         59.33 |         77.02 |          80.55 |        72.59 |           70.03 |             81.3  |             57.99 |         6.68 |             67.86 | medium             |                0.5  |                 -0.33 |                  nan |
|     15 | BMAG.VI  | Bajaj Mobility AG          | EUROPE   |                1.09 |             74.52 |         82.71 |         80.32 |          68.72 |        53.79 |           45.65 |             81.19 |             26.91 |         6.58 |             66.3  | short              |               -0.56 |                  0.54 |                  nan |
|     16 | PR       | PR                         | US       |               16.41 |             74.45 |         66.83 |         73.02 |          75.89 |        77.26 |           77.64 |             71.5  |             74.2  |         4.11 |             68.32 | long               |                0.7  |                 -0.35 |                  nan |
|     17 | GH       | GH                         | US       |               18.7  |             74.42 |         51.27 |         75.7  |          79.48 |        73.15 |           61.52 |             79.67 |            nan    |         6.48 |             64.91 | medium             |              nan    |                nan    |                  nan |
|     18 | SSRM     | SSRM                       | US       |                6.68 |             74.33 |         79.57 |         73.66 |          71.44 |        75    |           65.06 |             74.32 |             83.77 |         7.05 |             68.32 | short              |                0.36 |                 -0.03 |                  nan |
|     19 | WDAY     | WDAY                       | US       |               42.58 |             74.3  |         82.69 |         79.86 |          68.74 |        63.05 |           73.66 |             80.48 |             40.72 |         8.42 |             68.2  | short              |                0.45 |                  1.68 |                  nan |
|     20 | APA      | APA                        | US       |               12.86 |             73.86 |         73.2  |         72.39 |          74.53 |        74.95 |           74.74 |             60.11 |             74.47 |         5.54 |             68.66 | long               |                0.38 |                  1.02 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.21 |                  78.71 |                    80    |                 79.84 |              80.43 |                87.34 |                   12.66 |           77.39 |            nan    |       0.231 |         nan |       nan |        1.54 |       nan    |          2.99 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            2 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.3  |                  77.45 |                    74.57 |                 73.26 |              73.26 |                82.13 |                   17.87 |           88.1  |             27.11 |       0.8   |         nan |       nan |      nan    |       -85.14 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              215.49 |                  66.43 |                    73.75 |                 76.22 |              69.91 |                83.86 |                   16.14 |           93.09 |             69.82 |     nan     |         nan |       nan |      nan    |         9.85 |         10.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               63.89 |                  85.5  |                    73.23 |                 69.25 |              77.63 |                55.29 |                   44.71 |           53.23 |             61.19 |       0.034 |         nan |       nan |       16.41 |        13.99 |         19.76 |        1.45 |                 nan |              nan |                  12 |                  0.63 |
|            4 | DDI       | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  66.75 |                    72.22 |                 74.98 |              69.16 |                83.83 |                   16.17 |           93.42 |             60.13 |       0.154 |         nan |       nan |        0.77 |         5.24 |          5.07 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.38 |                  79.95 |                    71.47 |                 70.16 |              73.37 |                68.77 |                   31.23 |           74.89 |             34.29 |       0.081 |         nan |       nan |        3.83 |         5.02 |          4.39 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            6 | STNE      | StoneCo Ltd.                         | OTHER    |                1.93 |                  75.23 |                    71.15 |                 70.48 |              70.11 |                69.45 |                   30.55 |           84.18 |             34.43 |       0.609 |         nan |       nan |        1.62 |         4.16 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | NVDA      | NVIDIA Corporation                   | US       |             4533.49 |                  60.87 |                    70.44 |                 72.38 |              64.99 |                77.03 |                   22.97 |           89.96 |             72.98 |       0.008 |         nan |       nan |       25.93 |        14.21 |         28.81 |        0.63 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.61 |                  55.99 |                    69.82 |                 74.42 |              64.01 |                86.5  |                   13.5  |           96.24 |             81.26 |     nan     |         nan |       nan |      nan    |         8.86 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | IRWD      | Ironwood Pharmaceuticals, Inc.       | US       |                0.59 |                  65.93 |                    69.61 |                 72.44 |              67.77 |                76.63 |                   23.37 |           86.05 |             65.06 |       0.179 |         nan |       nan |        4.2  |         2.75 |          5.36 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.41 |                  67.73 |                    68.64 |                 70.23 |              67.39 |                69.14 |                   30.86 |           80.43 |             61.83 |       0.021 |         nan |       nan |        3.85 |         6.67 |          4.63 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | IHS       | IHS Holding Limited                  | OTHER    |                2.44 |                  73.2  |                    68.57 |                 68.61 |              72.4  |                63.13 |                   36.87 |           54.84 |             83.29 |      -0.115 |         nan |       nan |        7.48 |        15.2  |          5.1  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | BBWI      | Bath & Body Works, Inc.              | US       |                3.34 |                  75.72 |                    68.55 |                 65.96 |              68.28 |                57.34 |                   42.66 |           72.54 |             34.36 |       0.197 |         nan |       nan |        5.95 |         6.85 |          4.89 |        0.68 |                 nan |              nan |                  11 |                  0.58 |
|          nan | AGS.BR    | AGS.BR                               | EUROPE   |               15.64 |                  62.38 |                    68.15 |                 70    |              64.55 |                78.88 |                   21.12 |           87.77 |             54.35 |     nan     |         nan |       nan |      nan    |         8.66 |          7.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NAT       | NAT                                  | US       |                1.24 |                  54.35 |                    67.78 |                 72.2  |              62.77 |                83.02 |                   16.98 |           88.97 |             86.95 |     nan     |         nan |       nan |      nan    |        14.88 |         26.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY       | NLY                                  | US       |               14.99 |                  67.77 |                    67.63 |                 67.9  |              64.5  |                70.46 |                   29.54 |           89.21 |             30.24 |     nan     |         nan |       nan |      nan    |         7.41 |          5.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |               99.09 |                  79.06 |                    67.56 |                 65.14 |              73.01 |                49.86 |                   50.14 |           45.65 |             71.16 |       0.158 |         nan |       nan |        1.74 |         6.82 |          4.18 |        4.02 |                 nan |              nan |                  12 |                  0.63 |
|           13 | DAC       | Danaos Corporation                   | OTHER    |                2.37 |                  64.59 |                    67.36 |                 69.47 |              66.34 |                79.15 |                   20.85 |           80.65 |             55.82 |       0.002 |         nan |       nan |        4.03 |         6.15 |          5.12 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP        | BP                                   | US       |               93.68 |                  56.81 |                    67.31 |                 70.78 |              63.02 |                79.97 |                   20.03 |           86.51 |             77.29 |     nan     |         nan |       nan |      nan    |         9.51 |         20.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS  | ASRNL.AS                             | EUROPE   |               14.59 |                  57.85 |                    66.93 |                 69.62 |              63.43 |                81.82 |                   18.18 |           82.97 |             70.49 |     nan     |         nan |       nan |      nan    |        11.25 |         14.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0Q2N.IL   | K+S Aktiengesellschaft           | OTHER    |                3.21 |                  78.71 |                    80    |                 79.84 |              80.43 |                87.34 |                   12.66 |           77.39 |            nan    |       0.231 |         nan |       nan |        1.54 |       nan    |          2.99 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHELL.AS  | SHELL.AS                         | EUROPE   |              215.49 |                  66.43 |                    73.75 |                 76.22 |              69.91 |                83.86 |                   16.14 |           93.09 |             69.82 |     nan     |         nan |       nan |      nan    |         9.85 |         10.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | DDI       | DoubleDown Interactive Co., Ltd. | OTHER    |                0.55 |                  66.75 |                    72.22 |                 74.98 |              69.16 |                83.83 |                   16.17 |           93.42 |             60.13 |       0.154 |         nan |       nan |        0.77 |         5.24 |          5.07 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR   | CMBT.BR                          | EUROPE   |                4.61 |                  55.99 |                    69.82 |                 74.42 |              64.01 |                86.5  |                   13.5  |           96.24 |             81.26 |     nan     |         nan |       nan |      nan    |         8.86 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | BION.SW   | BB Biotech AG                    | EUROPE   |                3.3  |                  77.45 |                    74.57 |                 73.26 |              73.26 |                82.13 |                   17.87 |           88.1  |             27.11 |       0.8   |         nan |       nan |      nan    |       -85.14 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            8 | IRWD      | Ironwood Pharmaceuticals, Inc.   | US       |                0.59 |                  65.93 |                    69.61 |                 72.44 |              67.77 |                76.63 |                   23.37 |           86.05 |             65.06 |       0.179 |         nan |       nan |        4.2  |         2.75 |          5.36 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | NVDA      | NVIDIA Corporation               | US       |             4533.49 |                  60.87 |                    70.44 |                 72.38 |              64.99 |                77.03 |                   22.97 |           89.96 |             72.98 |       0.008 |         nan |       nan |       25.93 |        14.21 |         28.81 |        0.63 |                 nan |              nan |                  12 |                  0.63 |
|          nan | NAT       | NAT                              | US       |                1.24 |                  54.35 |                    67.78 |                 72.2  |              62.77 |                83.02 |                   16.98 |           88.97 |             86.95 |     nan     |         nan |       nan |      nan    |        14.88 |         26.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                               | US       |               93.68 |                  56.81 |                    67.31 |                 70.78 |              63.02 |                79.97 |                   20.03 |           86.51 |             77.29 |     nan     |         nan |       nan |      nan    |         9.51 |         20.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | STNE      | StoneCo Ltd.                     | OTHER    |                1.93 |                  75.23 |                    71.15 |                 70.48 |              70.11 |                69.45 |                   30.55 |           84.18 |             34.43 |       0.609 |         nan |       nan |        1.62 |         4.16 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | PARR      | Par Pacific Holdings, Inc.       | US       |                3.41 |                  67.73 |                    68.64 |                 70.23 |              67.39 |                69.14 |                   30.86 |           80.43 |             61.83 |       0.021 |         nan |       nan |        3.85 |         6.67 |          4.63 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | GSL       | Global Ship Lease, Inc.          | OTHER    |                1.38 |                  79.95 |                    71.47 |                 70.16 |              73.37 |                68.77 |                   31.23 |           74.89 |             34.29 |       0.081 |         nan |       nan |        3.83 |         5.02 |          4.39 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | AGS.BR    | AGS.BR                           | EUROPE   |               15.64 |                  62.38 |                    68.15 |                 70    |              64.55 |                78.88 |                   21.12 |           87.77 |             54.35 |     nan     |         nan |       nan |      nan    |         8.66 |          7.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS  | ASRNL.AS                         | EUROPE   |               14.59 |                  57.85 |                    66.93 |                 69.62 |              63.43 |                81.82 |                   18.18 |           82.97 |             70.49 |     nan     |         nan |       nan |      nan    |        11.25 |         14.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | DAC       | Danaos Corporation               | OTHER    |                2.37 |                  64.59 |                    67.36 |                 69.47 |              66.34 |                79.15 |                   20.85 |           80.65 |             55.82 |       0.002 |         nan |       nan |        4.03 |         6.15 |          5.12 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|            3 | VOLV-B.ST | AB Volvo (publ)                  | EUROPE   |               63.89 |                  85.5  |                    73.23 |                 69.25 |              77.63 |                55.29 |                   44.71 |           53.23 |             61.19 |       0.034 |         nan |       nan |       16.41 |        13.99 |         19.76 |        1.45 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR   | BIRG.IR                          | EUROPE   |               17.7  |                  58.68 |                    66.2  |                 68.89 |              60.73 |                78.08 |                   21.92 |           96.55 |             44.27 |     nan     |         nan |       nan |      nan    |        10.27 |         13.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | IHS       | IHS Holding Limited              | OTHER    |                2.44 |                  73.2  |                    68.57 |                 68.61 |              72.4  |                63.13 |                   36.87 |           54.84 |             83.29 |      -0.115 |         nan |       nan |        7.48 |        15.2  |          5.1  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           17 | HMC       | Honda Motor Co., Ltd.            | OTHER    |               35.68 |                  58.96 |                    65.22 |                 68.53 |              64.27 |                74.54 |                   25.46 |           72.83 |             84.08 |       0.04  |         nan |       nan |        7.16 |         6.42 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|          nan | GL9.IR    | GL9.IR                           | EUROPE   |                5.36 |                  43.11 |                    62.16 |                 68.24 |              54.36 |                88.23 |                   11.77 |           97.78 |             74.39 |     nan     |         nan |       nan |      nan    |        15.31 |         26.72 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                       | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | NAT      | NAT                        | US       |                1.24 |                     0.04 |    -0.03 |      0.04 |                  67.2  |                        81.57 |         65.06 |         81.31 |          82.73 |        79.16 |           88.97 |             86.95 |         4.66 |
|               2 | AVAH     | AVAH                       | US       |                2.51 |                     0.04 |     0.01 |      0.42 |                  55.64 |                        78.19 |         86.53 |         81.83 |          74.58 |        72.08 |           93.04 |             53.16 |         7.39 |
|               3 | GH       | GH                         | US       |               18.7  |                     0.06 |    -0.05 |     -0    |                  86.47 |                        75.07 |         51.27 |         75.7  |          79.48 |        73.15 |           61.52 |             79.67 |         6.48 |
|               4 | PR       | PR                         | US       |               16.41 |                     0.05 |    -0.04 |      0.07 |                  80.02 |                        74.77 |         66.83 |         73.02 |          75.89 |        77.26 |           77.64 |             71.5  |         4.11 |
|               5 | SSRM     | SSRM                       | US       |                6.68 |                     0.05 |    -0.01 |      0.46 |                  70.81 |                        74.57 |         79.57 |         73.66 |          71.44 |        75    |           65.06 |             74.32 |         7.05 |
|               6 | SM       | SM                         | US       |                7.52 |                     0.03 |    -0.02 |      0.13 |                  58.11 |                        73.81 |         75.99 |         78    |          78.68 |        82.66 |           80.87 |             66.14 |         7.01 |
|               7 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.65 |                     0.04 |    -0.03 |      0.12 |                  66.49 |                        73.56 |         74.37 |         74.43 |          72.11 |        69.42 |           74.06 |             77.08 |         5.13 |
|               8 | PARR     | Par Pacific Holdings, Inc. | US       |                3.41 |                     0.05 |    -0    |     -0.08 |                  68.4  |                        72.93 |         60.32 |         74.63 |          78.6  |        75.31 |           80.43 |             61.83 |         6.86 |
|               9 | KRX.IR   | KRX.IR                     | EUROPE   |               18.37 |                     0.02 |     0.01 |      0.27 |                  43.75 |                        72.65 |         80.57 |         68.76 |          64.34 |        62.7  |           96.62 |             43.17 |         5.14 |
|              10 | IAG      | IAG                        | US       |               10.15 |                     0.07 |    -0.03 |      0.45 |                  68.35 |                        72.49 |         76.28 |         62.15 |          65.54 |        75.75 |           74.42 |             61.43 |         7.65 |
|              11 | CVE      | CVE                        | US       |               50.26 |                     0.04 |    -0.04 |      0.05 |                  74.12 |                        72.24 |         63.37 |         71.45 |          75.51 |        73.41 |           76.32 |             67.57 |         4.76 |
|              12 | NVDA     | NVIDIA Corporation         | US       |             4533.49 |                     0.05 |     0.01 |      0.08 |                  61.26 |                        72.2  |         68.14 |         62.58 |          67.15 |        67.26 |           89.96 |             72.98 |         5.77 |
|              13 | MP       | MP                         | US       |                8.63 |                     0.07 |    -0.07 |      0.36 |                  82.36 |                        71.96 |         69.69 |         50.9  |          48.95 |        46.49 |           58.04 |             87.68 |         8.79 |
|              14 | HMC      | Honda Motor Co., Ltd.      | OTHER    |               35.68 |                     0.05 |    -0.05 |      0.06 |                  78    |                        71.94 |         58.54 |         66.12 |          64.66 |        69.7  |           72.83 |             84.08 |         3.69 |
|              15 | VWS.CO   | VWS.CO                     | EUROPE   |               27.72 |                     0.02 |     0.02 |      0.21 |                  47.16 |                        71.93 |         79.25 |         64.87 |          64.52 |        60.87 |           89.22 |             49.24 |         5.55 |
|              16 | BAX      | BAX                        | US       |               11.66 |                     0.08 |    -0.01 |     -0    |                  58.84 |                        71.86 |         58.06 |         74.78 |          71.83 |        70.35 |           75.5  |             70.28 |         5.98 |
|              17 | FSM      | FSM                        | US       |                3.13 |                     0.04 |     0.02 |      0.45 |                  58.77 |                        71.83 |         81.08 |         64.19 |          62.37 |        75.63 |           77.52 |             46.48 |         7.1  |
|              18 | TOST     | TOST                       | US       |               17.53 |                     0.05 |    -0.04 |      0.09 |                  79.12 |                        71.51 |         62.45 |         71.39 |          61.56 |        55.09 |           66.45 |             71.04 |         6.83 |
|              19 | AG       | AG                         | US       |                8.83 |                     0.05 |    -0.02 |      0.38 |                  69.26 |                        71.29 |         71.06 |         47.85 |          58    |        66.65 |           89.34 |             50.01 |         8.4  |
|              20 | CRGY     | CRGY                       | US       |                3.86 |                     0.04 |    -0.04 |      0.19 |                  70.47 |                        71.22 |         73.84 |         72.17 |          71.43 |        78.11 |           71.01 |             63.49 |         6    |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1514.17 |             50.18 |         39.32 |         42.83 |          57.53 |        60.03 |           82.27 |             57.78 |             32.32 |         6.03 |             89.18 | long               |                0.43 |                  0.38 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |             45.52 |         38.83 |         38.76 |          52.22 |        63.86 |           84.91 |             43.07 |             54.6  |         3.74 |             75.81 | long               |               -0.39 |                 -1.27 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             45.33 |         39.96 |         41.26 |          49.4  |        61.74 |           58.79 |             54.1  |             89.63 |         4.17 |             82.14 | long               |               -1.31 |                  0.01 |                  nan |
|    nan | ORCL     | Oracle Corporation                                   | US       |              374.99 |             43.46 |         60.94 |         40.63 |          42.11 |        44.82 |           48.63 |             61.02 |             42.08 |         7.94 |             89.54 | short              |                0.14 |                  0.3  |                  nan |
|    nan | MTRX     | Matrix Service Company                               | US       |                0.26 |             39.27 |         34.15 |         35.57 |          42.97 |        49.63 |           42.59 |             63.08 |             74.58 |         5.91 |             80.44 | long               |               -0.31 |                nan    |                  nan |
|    nan | SHOE     | Shoe Station Group Inc.                              | US       |                0.32 |             29.63 |         23.17 |         25.58 |          33.67 |        43.01 |           38.55 |             40.73 |             62.47 |         6.68 |             84.21 | long               |               -1.5  |                nan    |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | CMBT.BR  | CMBT.BR | EUROPE   |                4.61 |             81.52 |         79.91 |         80.84 |          83.37 |        82.2  |           96.24 |             81.26 |             60.41 |         3.82 |             69.68 | medium             |                0.71 |                  5.37 |                  nan |
|     48 | CRWD     | CRWD    | US       |              192.99 |             70.96 |         77.67 |         75.63 |          66.28 |        44.39 |           36.51 |             88.77 |              1.58 |         7.37 |             69.68 | short              |                0.41 |                  3.36 |                  nan |
|     50 | CRM      | CRM     | US       |              181.82 |             70.81 |         83.67 |         78.62 |          63.01 |        58.28 |           63.69 |             74.07 |             39.74 |         7.65 |             68.66 | short              |                0.75 |                  3.33 |                  nan |
|      4 | OKTA     | OKTA    | US       |               25.08 |             78.93 |         85.66 |         82.52 |          75.33 |        61.19 |           70.18 |             80.43 |             16.7  |         7.57 |             68.32 | short              |               -0.73 |                  3.32 |                  nan |
|    107 | HPQ      | HPQ     | US       |               23.75 |             66.42 |         73.37 |         70.85 |          61.99 |        57.08 |           32.4  |             68.86 |             81.33 |         6.54 |             66.73 | short              |                0.9  |                  2.89 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    705 | DNUT     | DNUT                         | US       |                0.52 |             34.59 |         56.08 |         36.95 |          32.24 |        30.61 |           21.54 |             39.95 |             25.87 |         6.89 |             69.68 | short              |                0.11 |                 -3.72 |                  nan |
|    724 | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.61 |             23.53 |         19.71 |         18.53 |          27.36 |        36.38 |           36.87 |             34.46 |             52.06 |         6.73 |             77.68 | long               |               -7.02 |                 -3.34 |                  nan |
|    323 | TGB      | TGB                          | OTHER    |                2.9  |             58.14 |         74.43 |         59.73 |          56.56 |        55.91 |           63.74 |             44.01 |             33.54 |         7.66 |             69.23 | short              |               -4.65 |                 -3.12 |                  nan |
|    579 | ENI.MI   | ENI.MI                       | EUROPE   |               65.67 |             47.78 |         34.35 |         41.75 |          53.82 |        56.74 |           58.87 |             31.3  |             58.48 |         3.41 |             67.86 | long               |                0.34 |                 -2.68 |                  nan |
|    310 | NWSA     | NWSA                         | US       |               14.36 |             58.61 |         70.54 |         64.93 |          52.29 |        46.36 |           42.68 |             47.36 |             39.35 |         4.09 |             67.86 | short              |                0.23 |                 -2.54 |                  nan |

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
- Excluded by hard/data filters: **270**
- Event watch (otherwise eligible): **6**
- Final eligible: **724**
- Eligible change vs previous stored run: **+1**

Top exclusion categories:
- liquidity: 226
- market_cap: 202
- price: 162
- data_confidence: 49
- price_history: 14
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 12 | 9 | 8 | 7 | 2 | value,pullback,quality_value |
| NAT | 3 |  | 1 |  | 2 | main,pullback |
| SM | 5 |  | 6 |  | 2 | main,pullback |
| AVAH | 6 |  | 2 |  | 2 | main,pullback |
| 0Q2N.IL | 37 | 1 |  | 1 | 1 | value,quality_value |
| DDI | 46 | 4 |  | 2 | 1 | value,quality_value |
| BION.SW | 73 | 2 | 117 | 3 | 1 | value,quality_value |
| IRWD | 88 | 8 | 49 | 4 | 1 | value,quality_value |
| NVDA | 92 | 7 | 12 | 5 | 1 | value,quality_value |
| GSL | 143 | 5 | 167 | 8 | 1 | value,quality_value |
| VOLV-B.ST | 385 | 3 | 238 | 10 | 1 | value,quality_value |
| STNE | 659 | 6 |  | 6 | 1 | value,quality_value |
| CMBT.BR | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| OKTA | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **6** (CMBT.BR, FRO, OKTA, DK, PAGP, RNG)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (KRX.IR, IAG)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | IRWD | value+pullback | 73.31 | 65.93 | 75.14 | 86.05 | 65.06 | 76.63 | 67.54 |
| 2 | HMC | value+pullback | 71.43 | 58.96 | 78.00 | 72.83 | 84.08 | 74.54 | 65.39 |
| 3 | NVDA | value+pullback | 69.78 | 60.87 | 61.26 | 89.96 | 72.98 | 77.03 | 67.21 |
| 4 | PARR | value+pullback | 69.50 | 67.73 | 68.40 | 80.43 | 61.83 | 69.14 | 74.97 |
| 5 | TNK | value+pullback | 68.74 | 57.66 | 66.49 | 74.06 | 77.08 | 80.02 | 73.24 |
| 6 | BION.SW | value+pullback | 67.24 | 77.45 | 46.59 | 88.10 | 27.11 | 82.13 | 68.65 |
| 7 | VOLV-B.ST | value+pullback | 66.22 | 85.50 | 61.62 | 53.23 | 61.19 | 55.29 | 56.07 |
| 8 | XNET | value+pullback | 64.81 | 59.23 | 67.50 | 57.83 | 81.19 | 66.85 | 42.99 |
| 9 | BBWI | value+pullback | 63.51 | 75.72 | 60.06 | 72.54 | 34.36 | 57.34 | 44.89 |
| 10 | GSL | value+pullback | 63.12 | 79.95 | 42.85 | 74.89 | 34.29 | 68.77 | 65.04 |
| 11 | MFA | value+pullback | 62.47 | 59.27 | 66.23 | 79.81 | 34.33 | 63.63 | 43.25 |
| 12 | INVA | value+pullback | 61.34 | 58.54 | 52.87 | 79.49 | 35.71 | 75.33 | 47.16 |
| 13 | WKC | value+pullback | 60.14 | 57.82 | 51.15 | 58.15 | 76.08 | 68.36 | 67.25 |
| 14 | ALL-PH | value+pullback | 59.57 | 60.13 | 58.76 | 71.05 | 42.60 | 59.63 | 45.57 |
| 15 | UNIT | value+pullback | 59.25 | 80.26 | 53.90 | 65.89 | 28.68 | 44.70 | 48.95 |
| 16 | 0Q2N.IL | value | 57.69 | 78.71 | 35.62 | 77.39 |  | 87.34 | 71.39 |
| 17 | BP | pullback | 56.92 | 56.81 | 80.88 | 86.51 | 77.29 | 79.97 | 64.59 |
| 18 | DDI | value | 56.82 | 66.75 | 46.34 | 93.42 | 60.13 | 83.83 | 70.99 |
| 19 | GL9.IR | pullback | 55.93 | 43.11 | 64.71 | 97.78 | 74.39 | 88.23 | 64.15 |
| 20 | NAT | pullback | 55.45 | 54.35 | 67.20 | 88.97 | 86.95 | 83.02 | 80.24 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 10/10 | 9/10 | 8/10 | 0/10 | 68.5 | 4 / 6 |
| Top 25 | 24/25 | 25/25 | 23/25 | 22/25 | 0/25 | 68.3 | 13 / 12 |
| Top 50 | 47/50 | 49/50 | 48/50 | 44/50 | 0/50 | 68.7 | 22 / 28 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=3, large_20_100b=1
