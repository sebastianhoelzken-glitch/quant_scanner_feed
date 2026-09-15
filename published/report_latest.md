# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-15

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

- **EUROPE:** 79.3/100
- **OTHER:** 69.3/100
- **US:** 80.7/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC                        | US       |               96.03 |             86.52 |         86.79 |         90.17 |          86.25 |        79.38 |           85.81 |             87.05 |             53.81 |         4.11 |             73.14 | swing              |              nan    |                nan    |               nan    |
|      2 | FRO      | FRO                        | US       |                9.7  |             86.36 |         89.28 |         87.44 |          85.27 |        80.84 |           92.52 |             79.91 |             54.46 |         5.5  |             73.14 | short              |                2.38 |                nan    |               nan    |
|      3 | VLO      | VLO                        | US       |               95.1  |             85.6  |         86.14 |         88.15 |          85.06 |        79.22 |           86.45 |             81.62 |             54.81 |         3.49 |             69.68 | swing              |                1.24 |                  0.56 |               nan    |
|      4 | SM       | SM                         | US       |                8.01 |             85.43 |         88.49 |         85.24 |          82.8  |        85.63 |           83.11 |             79.85 |             92.57 |         7.05 |             72.11 | short              |                1.09 |                  2.77 |                 2.3  |
|      5 | DK       | DK                         | US       |                3.93 |             84.12 |         88.59 |         88.06 |          80.19 |        68.95 |           56.13 |             93.19 |             55.25 |         7.34 |             73.14 | short              |                1.99 |                  0.94 |                 0.42 |
|      6 | AVAH     | AVAH                       | US       |                2.71 |             83.51 |         89.22 |         86.93 |          80.08 |        73.25 |           93.66 |             67.42 |             32.82 |         7.72 |             72.11 | short              |                4.93 |                  2.62 |                 2.36 |
|      7 | CRGY     | CRGY                       | US       |                4.95 |             83.31 |         88.6  |         84.13 |          79.82 |        82.5  |           72.08 |             89.39 |             90.38 |         6.33 |             69.23 | short              |               -0.5  |                  0.8  |                 0.28 |
|      8 | DELL     | DELL                       | US       |              293    |             82.27 |         85.73 |         84.47 |          80.07 |        67.15 |           73.91 |             81.83 |             27.95 |         7.82 |             72.23 | short              |                1.74 |                  0.39 |                -0.19 |
|      9 | NAT      | NAT                        | US       |                1.39 |             81.96 |         87.45 |         84.29 |          79.63 |        72.67 |           88.52 |             67.6  |             34.99 |         4.97 |             73.14 | short              |                4.58 |                  2    |               nan    |
|     10 | DINO     | DINO                       | US       |               16.39 |             81.31 |         83.89 |         87.14 |          78.72 |        69.11 |           50.49 |             85.36 |             69.29 |         4.51 |             73.14 | swing              |                2.16 |                nan    |               nan    |
|     11 | KIN.BR   | KIN.BR                     | EUROPE   |                1.29 |             80.85 |         86.95 |         84.28 |          77.42 |        67.17 |           88.22 |             78.59 |             19.8  |         3.8  |             73.14 | short              |                1.99 |                  0.9  |                 0.71 |
|     12 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.85 |             79.8  |         82.48 |         79.59 |          79.93 |        79.67 |           95.58 |             54.03 |             61.72 |         4.04 |             73.14 | short              |                3.91 |                  2.08 |                 0.87 |
|     13 | ANF      | ANF                        | US       |                5.15 |             79.73 |         82.61 |         81.76 |          77.7  |        75.93 |           89.26 |             65.82 |             54.29 |         8.62 |             67.64 | short              |                0.03 |                  0.09 |                -1.01 |
|     14 | PARR     | Par Pacific Holdings, Inc. | US       |                3.53 |             79.68 |         73.97 |         79.24 |          80.97 |        80.12 |           83.23 |             74.7  |             73.52 |         7.12 |             84.91 | medium             |               -0.14 |                  0.28 |                 0.05 |
|     15 | APA      | APA                        | US       |               13.61 |             79.37 |         85.92 |         80.8  |          77.93 |        75.99 |           76.44 |             79.08 |             62.64 |         5.86 |             72.11 | short              |                2.1  |                  0.63 |                 0.33 |
|     16 | DHT      | DHT                        | US       |                3.08 |             79.14 |         85.96 |         80.94 |          77.34 |        76.07 |           90.16 |             57.79 |             52.68 |         4.69 |             73.14 | short              |                2.23 |                  1.36 |                 0.85 |
|     17 | TALO     | TALO                       | US       |                2.54 |             79.07 |         85.5  |         80.83 |          77.32 |        73.97 |           68.57 |             94.55 |             61.53 |         5.72 |             69.68 | short              |              nan    |                nan    |               nan    |
|     18 | UGP      | UGP                        | US       |                6.84 |             78.3  |         82.8  |         82.48 |          74.11 |        67.34 |           63.79 |             66.41 |             54.69 |         4.66 |             72.11 | short              |                7.96 |                 -0.03 |                -0.76 |
|     19 | SHELL.AS | SHELL.AS                   | EUROPE   |              239.68 |             78.27 |         83.41 |         76.85 |          74.88 |        79.68 |           91.82 |             82.72 |             63.17 |         2.39 |             73.14 | short              |               -1.22 |                  3.09 |                 2.38 |
|     20 | OKTA     | OKTA                       | US       |               28.11 |             77.95 |         90.94 |         83.45 |          72.44 |        58.35 |           68.95 |             67.35 |             12.26 |         7.83 |             72.11 | short              |                4.29 |                  1.28 |                 0.4  |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.53 |                  74.38 |                    74.11 |                 76.02 |              73.67 |                70.24 |                   29.76 |           83.23 |             74.7  |       0.02  |         nan |       nan |        3.96 |         6.05 |          4.79 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.06 |                  73.04 |                    72.9  |                 72.5  |              70.89 |                82.73 |                   17.27 |           88.4  |             34.15 |       0.855 |         nan |       nan |      nan    |       -79.66 |          2.13 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | IRWD      | Ironwood Pharmaceuticals, Inc.       | US       |                0.59 |                  70.04 |                    71.86 |                 73.97 |              70.49 |                82.01 |                   17.99 |           88.8  |             52.99 |       0.177 |         nan |       nan |        4.23 |         2.78 |          5.28 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL      | SHEL                                 | US       |              237.87 |                  66.69 |                    71.58 |                 72.98 |              70.54 |                78.2  |                   21.8  |           74.29 |             84.45 |     nan     |         nan |       nan |      nan    |         9.33 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              239.68 |                  59.5  |                    71.48 |                 75.28 |              66.88 |                87.59 |                   12.41 |           91.82 |             82.72 |     nan     |         nan |       nan |      nan    |         9.67 |         10.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | DDI       | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.54 |                  66.18 |                    71.36 |                 74.01 |              68.86 |                80.69 |                   19.31 |           88.39 |             66.89 |       0.156 |         nan |       nan |        0.71 |         5.17 |          5    |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | NVDA      | NVIDIA Corporation                   | US       |             4393.72 |                  61.64 |                    71.06 |                 72.96 |              66.22 |                77.18 |                   22.82 |           86.9  |             79.47 |       0.008 |         nan |       nan |       25.14 |        13.51 |         26.7  |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|            6 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.42 |                  77.93 |                    70.79 |                 69.25 |              72.87 |                76.68 |                   23.32 |           72.98 |             29.58 |       0.078 |         nan |       nan |        3.92 |         5.16 |          4.46 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|            7 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               60.46 |                  84.11 |                    70.43 |                 65.75 |              74.67 |                53.74 |                   46.26 |           52.72 |             44.39 |       0.035 |         nan |       nan |       15.94 |        13.47 |         19.06 |        0.99 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP        | BP                                   | US       |              102.03 |                  59.55 |                    70.3  |                 73.86 |              66.27 |                82.37 |                   17.63 |           87.41 |             85.67 |     nan     |         nan |       nan |      nan    |         9.36 |         21.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | BBWI      | Bath & Body Works, Inc.              | US       |                3.11 |                  80.81 |                    69.85 |                 65.87 |              70.75 |                51.42 |                   48.58 |           67.31 |             33.13 |       0.212 |         nan |       nan |        5.75 |         6.4  |          4.7  |        0.76 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SM        | SM                                   | US       |                8.01 |                  62.59 |                    69.3  |                 71.88 |              66.2  |                73.07 |                   26.93 |           83.11 |             79.85 |     nan     |         nan |       nan |      nan    |         5.01 |          6.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | STNE      | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.54 |                    69.3  |                 68.85 |              67.47 |                67.75 |                   32.25 |           85.87 |             30.52 |       0.602 |         nan |       nan |        1.63 |         4.31 |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.61 |                  79.55 |                    69.16 |                 67.46 |              74.58 |                51.2  |                   48.8  |           47.39 |             80.93 |       0.14  |         nan |       nan |        1.8  |         4.74 |          4.82 |        5.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO       | FRO                                  | US       |                9.7  |                  56.79 |                    68.67 |                 72.8  |              63.43 |                80.87 |                   19.13 |           92.52 |             79.91 |     nan     |         nan |       nan |      nan    |        11.11 |          7.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | AVGO      | Broadcom Inc.                        | US       |             1419.33 |                  60.81 |                    68.03 |                 68.54 |              62.12 |                77.98 |                   22.02 |           92.11 |             43.01 |       0.019 |         nan |       nan |       32.17 |        17.78 |         43.86 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | NLY       | NLY                                  | US       |               14.2  |                  67.67 |                    67.4  |                 67.66 |              64.14 |                70.06 |                   29.94 |           89.93 |             28.1  |     nan     |         nan |       nan |      nan    |         7.02 |          5.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                              | EUROPE   |               18.94 |                  56.13 |                    67.13 |                 70.79 |              61.44 |                82.92 |                   17.08 |           95.74 |             61.05 |     nan     |         nan |       nan |      nan    |        10.98 |         14.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR    | AGS.BR                               | EUROPE   |               15.7  |                  62.94 |                    66.99 |                 68.3  |              63.84 |                75.73 |                   24.27 |           85.13 |             48.93 |     nan     |         nan |       nan |      nan    |         8.76 |          7.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | UNIT      | Uniti Group Inc.                     | US       |                2.03 |                  75.92 |                    66.94 |                 64.7  |              67.91 |                58.19 |                   41.81 |           70.59 |             27.73 |      -0.109 |         nan |       nan |        9.11 |       -13.69 |          2.53 |        0.17 |                 nan |              nan |                   9 |                  0.47 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.53 |                  74.38 |                    74.11 |                 76.02 |              73.67 |                70.24 |                   29.76 |           83.23 |             74.7  |       0.02  |         nan |       nan |        3.96 |         6.05 |          4.79 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              239.68 |                  59.5  |                    71.48 |                 75.28 |              66.88 |                87.59 |                   12.41 |           91.82 |             82.72 |     nan     |         nan |       nan |      nan    |         9.67 |         10.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  66.18 |                    71.36 |                 74.01 |              68.86 |                80.69 |                   19.31 |           88.39 |             66.89 |       0.156 |         nan |       nan |        0.71 |         5.17 |          5    |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.59 |                  70.04 |                    71.86 |                 73.97 |              70.49 |                82.01 |                   17.99 |           88.8  |             52.99 |       0.177 |         nan |       nan |        4.23 |         2.78 |          5.28 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                               | US       |              102.03 |                  59.55 |                    70.3  |                 73.86 |              66.27 |                82.37 |                   17.63 |           87.41 |             85.67 |     nan     |         nan |       nan |      nan    |         9.36 |         21.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                             | US       |              237.87 |                  66.69 |                    71.58 |                 72.98 |              70.54 |                78.2  |                   21.8  |           74.29 |             84.45 |     nan     |         nan |       nan |      nan    |         9.33 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NVDA     | NVIDIA Corporation               | US       |             4393.72 |                  61.64 |                    71.06 |                 72.96 |              66.22 |                77.18 |                   22.82 |           86.9  |             79.47 |       0.008 |         nan |       nan |       25.14 |        13.51 |         26.7  |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                              | US       |                9.7  |                  56.79 |                    68.67 |                 72.8  |              63.43 |                80.87 |                   19.13 |           92.52 |             79.91 |     nan     |         nan |       nan |      nan    |        11.11 |          7.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.06 |                  73.04 |                    72.9  |                 72.5  |              70.89 |                82.73 |                   17.27 |           88.4  |             34.15 |       0.855 |         nan |       nan |      nan    |       -79.66 |          2.13 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SM       | SM                               | US       |                8.01 |                  62.59 |                    69.3  |                 71.88 |              66.2  |                73.07 |                   26.93 |           83.11 |             79.85 |     nan     |         nan |       nan |      nan    |         5.01 |          6.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                          | EUROPE   |               18.94 |                  56.13 |                    67.13 |                 70.79 |              61.44 |                82.92 |                   17.08 |           95.74 |             61.05 |     nan     |         nan |       nan |      nan    |        10.98 |         14.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                           | EUROPE   |               24.25 |                  54.28 |                    66.35 |                 70.33 |              60.42 |                83.41 |                   16.59 |           95.62 |             63.23 |     nan     |         nan |       nan |      nan    |        11.67 |         11.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                              | US       |               15.73 |                  54.03 |                    66.07 |                 69.86 |              61.12 |                83.33 |                   16.67 |           88.87 |             72.18 |     nan     |         nan |       nan |      nan    |        13.66 |         22.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                              | US       |               14.67 |                  55.98 |                    66.32 |                 69.7  |              61.89 |                79.86 |                   20.14 |           86.86 |             72.07 |     nan     |         nan |       nan |      nan    |        10.53 |         22.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                          | EUROPE   |                4.85 |                  57.15 |                    66.02 |                 69.27 |              60.41 |                76.99 |                   23.01 |           95.58 |             54.03 |     nan     |         nan |       nan |      nan    |         9.36 |          6.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | GSL      | Global Ship Lease, Inc.          | OTHER    |                1.42 |                  77.93 |                    70.79 |                 69.25 |              72.87 |                76.68 |                   23.32 |           72.98 |             29.58 |       0.078 |         nan |       nan |        3.92 |         5.16 |          4.46 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|            9 | STNE     | StoneCo Ltd.                     | OTHER    |                1.98 |                  72.54 |                    69.3  |                 68.85 |              67.47 |                67.75 |                   32.25 |           85.87 |             30.52 |       0.602 |         nan |       nan |        1.63 |         4.31 |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | AVGO     | Broadcom Inc.                    | US       |             1419.33 |                  60.81 |                    68.03 |                 68.54 |              62.12 |                77.98 |                   22.02 |           92.11 |             43.01 |       0.019 |         nan |       nan |       32.17 |        17.78 |         43.86 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | MU       | MU                               | US       |              900.12 |                  49.28 |                    63.32 |                 68.52 |              56.34 |                75.07 |                   24.93 |           96.28 |             73.44 |     nan     |         nan |       nan |      nan    |         5.92 |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                              | US       |               95.1  |                  49.4  |                    63.85 |                 68.44 |              58.56 |                82.38 |                   17.62 |           86.45 |             81.62 |     nan     |         nan |       nan |      nan    |        10.81 |         15.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                       | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | KIN.BR   | KIN.BR                     | EUROPE   |                1.29 |                     0.03 |     0    |      0.17 |                  54.28 |                        81.05 |         86.95 |         84.28 |          77.42 |        67.17 |           88.22 |             78.59 |         3.8  |
|               2 | ANF      | ANF                        | US       |                5.15 |                     0.08 |    -0.06 |      0.3  |                  75.87 |                        80.41 |         82.61 |         81.76 |          77.7  |        75.93 |           89.26 |             65.82 |         8.62 |
|               3 | AMC      | AMC                        | US       |                1.92 |                     0.07 |    -0.06 |      0    |                  75.54 |                        79.94 |         57.4  |         74.44 |          80.02 |        80.29 |           86.29 |             94.19 |         9.67 |
|               4 | DELL     | DELL                       | US       |              293    |                     0.06 |     0.02 |      0.09 |                  63.22 |                        79.41 |         85.73 |         84.47 |          80.07 |        67.15 |           73.91 |             81.83 |         7.82 |
|               5 | SRAIL.SW | SRAIL.SW                   | EUROPE   |                3.06 |                     0.08 |    -0.01 |      0.21 |                  57.45 |                        76.48 |         82.93 |         76.72 |          70.66 |        63.32 |           76.96 |             73.37 |         5.57 |
|               6 | PARR     | Par Pacific Holdings, Inc. | US       |                3.53 |                     0.03 |     0    |      0.02 |                  57    |                        76.02 |         73.97 |         79.24 |          80.97 |        80.12 |           83.23 |             74.7  |         7.12 |
|               7 | BE       | BE                         | US       |               65.3  |                     0.07 |     0.02 |      0.12 |                  55.02 |                        75.77 |         77.45 |         63.31 |          72.05 |        62.8  |           86.75 |             76.29 |         9.14 |
|               8 | WT       | WT                         | US       |                2.98 |                     0.09 |    -0.08 |     -0    |                  73.86 |                        75.18 |         57.88 |         75.74 |          74.5  |        64.96 |           73.82 |             76.42 |         5.85 |
|               9 | WDAY     | WDAY                       | US       |               40.37 |                     0.06 |    -0.01 |     -0.02 |                  69.21 |                        75.02 |         63.91 |         75.65 |          68.49 |        63.46 |           75.78 |             77.75 |         8.67 |
|              10 | KRX.IR   | KRX.IR                     | EUROPE   |               17.31 |                     0.09 |    -0.07 |     -0.04 |                  71.8  |                        74.67 |         52.69 |         66.96 |          72.51 |        67.96 |           97.67 |             72.55 |         5.57 |
|              11 | BEN      | BEN                        | US       |               14.67 |                     0.04 |    -0.04 |     -0.01 |                  74.94 |                        73.46 |         56.11 |         68.08 |          76.76 |        77.31 |           86.86 |             72.07 |         3.31 |
|              12 | PAGP     | PAGP                       | US       |                5.63 |                     0.02 |     0    |      0.08 |                  45.85 |                        73.35 |         81    |         72.81 |          71.38 |        70.69 |           85.01 |             59.75 |         1.77 |
|              13 | HOOD     | HOOD                       | US       |               88.66 |                     0.08 |    -0.06 |      0.2  |                  71.89 |                        73    |         74.65 |         72.06 |          61.82 |        51.64 |           67.73 |             75.63 |         8.95 |
|              14 | SNOW     | SNOW                       | US       |              101.13 |                     0.07 |    -0.01 |      0.01 |                  67.17 |                        72.9  |         72.37 |         80.66 |          68.18 |        47.19 |           43.37 |             92.12 |         8.04 |
|              15 | XP       | XP                         | US       |                8.58 |                     0.02 |    -0.01 |      0.24 |                  53.21 |                        72.67 |         81.93 |         70.88 |          62.36 |        66.86 |           60.27 |             77.8  |         6.16 |
|              16 | ASRNL.AS | ASRNL.AS                   | EUROPE   |               14.76 |                     0.02 |    -0.01 |      0.06 |                  51.24 |                        72.44 |         77.91 |         72.4  |          70.18 |        68.35 |           78.98 |             66.69 |         1.09 |
|              17 | HMC      | Honda Motor Co., Ltd.      | OTHER    |               36.37 |                     0.03 |    -0.01 |      0.03 |                  54.72 |                        72.04 |         67.86 |         72.67 |          67.93 |        69.58 |           73.85 |             84.87 |         3.74 |
|              18 | CRM      | CRM                        | US       |              184.16 |                     0.02 |     0    |      0.32 |                  48.27 |                        72.01 |         85.87 |         76.67 |          60.06 |        55.88 |           65.11 |             58.75 |         7.89 |
|              19 | MU       | MU                         | US       |              900.12 |                     0.1  |    -0.09 |     -0.05 |                  68.95 |                        71.98 |         44.91 |         62.73 |          83.43 |        85.09 |           96.28 |             73.44 |         8.32 |
|              20 | NVDA     | NVIDIA Corporation         | US       |             4393.72 |                     0.08 |    -0.08 |     -0.06 |                  77.65 |                        71.29 |         52    |         60.68 |          67.58 |        69.16 |           86.9  |             79.47 |         5.91 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              351.49 |             42.62 |         44.76 |         34.48 |          40.48 |        45.66 |           67.55 |             44.62 |             22.39 |         3.34 |             89.74 | long               |                1.11 |                  1.49 |                 1.55 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                  | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    167 | STR.VI   | STR.VI                | EUROPE   |               12.35 |             63.93 |         87.48 |         70.07 |          57.79 |        49.23 |          nan    |             57.08 |             29.81 |         5.61 |             66.84 | short              |               -1.43 |                  4.2  |               nan    |
|    236 | ACN      | ACN                   | US       |              102.92 |             60.97 |         72.77 |         59.34 |          55.31 |        62.61 |           82.17 |             53.75 |             46.15 |         8.48 |             67.64 | short              |                4.4  |                  4.14 |               nan    |
|    113 | CTSH     | CTSH                  | US       |               24.9  |             67.09 |         72.84 |         64.33 |          60.52 |        69.84 |           85.76 |             51.17 |             64.37 |         8.16 |             70.75 | short              |               10.62 |                  4.09 |                 4.11 |
|     55 | RBRK     | RBRK                  | US       |               17.79 |             72.65 |         75.65 |         80.61 |          69.64 |        50.87 |           54.79 |             90.27 |              1.79 |         8.71 |             72.23 | swing              |               16.01 |                  3.95 |                 3.41 |
|     86 | HMC      | Honda Motor Co., Ltd. | OTHER    |               36.37 |             68.76 |         67.86 |         72.67 |          67.93 |        69.58 |           73.85 |             84.87 |             72.29 |         3.74 |             81.4  | swing              |                4.75 |                  3.89 |                 3.16 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    482 | HQL      | Abrdn Life Sciences Investors        | US       |                0.52 |             51.87 |         45.18 |         61.38 |          57.75 |        45.98 |           46.6  |            nan    |             22.92 |         2.59 |             59.6  | swing              |                0.2  |                 -4.2  |                -3.59 |
|    445 | GOLD     | Gold.com, Inc.                       | US       |                1.19 |             52.86 |         70.85 |         52.85 |          52.87 |        49.56 |           38.71 |             69.08 |             36.24 |         7.14 |             77.52 | short              |               -1.66 |                 -3.94 |               nan    |
|    546 | ASA      | ASA Gold and Precious Metals Limited | US       |                0.93 |             49.3  |         46.11 |         43.29 |          52.5  |        60.24 |           63.65 |            nan    |             51.95 |         5.88 |             63.1  | long               |               -5.84 |                 -3.71 |                -3.35 |
|    711 | TLRY     | Tilray Brands, Inc.                  | OTHER    |                0.49 |             21.68 |         21.45 |         18.16 |          21.91 |        26.83 |           32.29 |             31.03 |             26.02 |         8.89 |             78.44 | long               |                0.82 |                 -3    |                -1.85 |
|    636 | NOKIA.HE | Nokia Oyj                            | EUROPE   |               48.09 |             42.13 |         31.51 |         34.07 |          50.39 |        50.18 |           43.13 |             52.29 |             49.91 |         7.34 |             87.82 | medium             |               -1.39 |                 -2.82 |                -2.44 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.89
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
- Excluded by hard/data filters: **286**
- Event watch (otherwise eligible): **1**
- Final eligible: **713**
- Eligible change vs previous stored run: **-4**

Top exclusion categories:
- liquidity: 228
- price: 183
- market_cap: 168
- price_history: 16
- data_confidence: 11
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 14 | 1 | 6 | 1 | 2 | value,pullback,quality_value |
| DELL | 8 |  | 4 |  | 2 | main,pullback |
| PBR-A | 63 | 10 |  | 10 | 1 | value,quality_value |
| GSL | 90 | 6 |  | 6 | 1 | value,quality_value |
| DDI | 95 | 4 | 35 | 2 | 1 | value,quality_value |
| NVDA | 164 | 5 | 20 | 4 | 1 | value,quality_value |
| BION.SW | 180 | 2 | 121 | 5 | 1 | value,quality_value |
| IRWD | 190 | 3 | 77 | 3 | 1 | value,quality_value |
| STNE | 549 | 9 | 178 | 7 | 1 | value,quality_value |
| MPC | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| VLO | 3 |  |  |  | 1 | main |
| SM | 4 |  |  |  | 1 | main |
| DK | 5 |  |  |  | 1 | main |
| AVAH | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (MPC, FRO, VLO, SM, DK, AVAH, CRGY, NAT, DINO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | IRWD | value+pullback | 75.19 | 70.04 | 76.64 | 88.80 | 52.99 | 82.01 | 62.96 |
| 2 | NVDA | value+pullback | 74.32 | 61.64 | 77.65 | 86.90 | 79.47 | 77.18 | 64.13 |
| 3 | BION.SW | value+pullback | 71.65 | 73.04 | 66.06 | 88.40 | 34.15 | 82.73 | 63.42 |
| 4 | DDI | value+pullback | 70.80 | 66.18 | 59.45 | 88.39 | 66.89 | 80.69 | 68.33 |
| 5 | PARR | value+pullback | 70.57 | 74.38 | 57.00 | 83.23 | 74.70 | 70.24 | 79.68 |
| 6 | ETG | value+pullback | 70.33 | 55.84 | 77.89 | 67.00 | 84.53 | 78.00 | 60.11 |
| 7 | STNE | value+pullback | 68.30 | 72.54 | 68.24 | 85.87 | 30.52 | 67.75 | 49.00 |
| 8 | UNIT | value+pullback | 68.08 | 75.92 | 81.23 | 70.59 | 27.73 | 58.19 | 42.13 |
| 9 | VOLV-B.ST | value+pullback | 67.37 | 84.11 | 76.17 | 52.72 | 44.39 | 53.74 | 51.22 |
| 10 | EMBC | value+pullback | 66.28 | 70.30 | 73.27 | 61.23 | 63.25 | 56.81 | 57.68 |
| 11 | WKC | value+pullback | 65.85 | 59.17 | 65.11 | 67.70 | 77.95 | 69.34 | 66.98 |
| 12 | BBWI | value+pullback | 65.11 | 80.81 | 68.70 | 67.31 | 33.13 | 51.42 | 43.11 |
| 13 | ATNI | value+pullback | 64.86 | 73.18 | 74.56 | 46.96 | 51.03 | 60.59 | 55.26 |
| 14 | HMC | value+pullback | 64.75 | 56.60 | 54.72 | 73.85 | 84.87 | 72.62 | 68.76 |
| 15 | DEC | value+pullback | 64.02 | 63.07 | 80.26 | 62.03 | 51.21 | 53.04 | 56.21 |
| 16 | XNET | value+pullback | 64.01 | 59.31 | 64.00 | 56.69 | 84.81 | 66.19 | 44.02 |
| 17 | INVA | value+pullback | 63.43 | 58.05 | 59.38 | 84.97 | 30.64 | 76.82 | 46.88 |
| 18 | AVK | value+pullback | 63.34 | 56.03 | 78.74 | 61.18 |  | 63.35 | 47.46 |
| 19 | IRS | value+pullback | 61.75 | 65.15 | 47.19 | 80.04 | 40.64 | 71.67 | 58.15 |
| 20 | JD | value+pullback | 61.50 | 64.90 | 69.95 | 57.76 | 40.15 | 59.30 | 41.10 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 72.7 | 1 / 9 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 72.1 | 6 / 19 |
| Top 50 | 49/50 | 50/50 | 49/50 | 48/50 | 0/50 | 72.1 | 11 / 39 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=3, large_20_100b=2, mega_100b_plus=1
