# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-16

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

- **EUROPE:** 78.0/100
- **OTHER:** 65.4/100
- **US:** 79.1/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | SM       | SM                         | US       |                8.5  |             87.06 |         88.12 |         87.82 |          84.38 |        86.31 |           82.36 |             78.24 |             94.78 |         7.14 |             72.11 | short              |                1.68 |                  1.3  |                 0.75 |
|      2 | VLO      | VLO                        | US       |               98.99 |             85.75 |         86.14 |         89.43 |          85.35 |        79.78 |           86.11 |             81.44 |             57.9  |         3.49 |             69.68 | swing              |               -0.16 |                  0.16 |               nan    |
|      3 | FRO      | FRO                        | US       |                9.95 |             85.59 |         88.55 |         86.64 |          84.53 |        80.93 |           91.36 |             78.18 |             58.31 |         5.63 |             73.14 | short              |               -0.72 |                  0.35 |                -0.69 |
|      4 | CRGY     | CRGY                       | US       |                4.4  |             85.28 |         87.99 |         87.26 |          82.21 |        83.3  |           71.33 |             89.11 |             93.19 |         6.47 |             69.23 | short              |                1.74 |                  0.67 |                 0.12 |
|      5 | DK       | DK                         | US       |                4.14 |             85    |         90.25 |         89.51 |          80.49 |        69.36 |           55.67 |             92.96 |             58.15 |         7.45 |             73.14 | short              |                0.74 |                  0.65 |                 0.36 |
|      6 | DHT      | DHT                        | US       |                3.09 |             83.57 |         87.75 |         84.55 |          82.58 |        81.49 |           89.02 |             81.66 |             64.05 |         4.74 |             73.14 | short              |               -2.02 |                  1.53 |                 0.6  |
|      7 | AVAH     | AVAH                       | US       |                2.7  |             82.97 |         87.65 |         85.77 |          80.16 |        74.03 |           93.38 |             66.04 |             37.54 |         7.92 |             72.11 | short              |               -0.25 |                  2.11 |                 1.92 |
|      8 | DELL     | DELL                       | US       |              299.23 |             82.08 |         87.11 |         84.41 |          79.76 |        67.63 |           73.18 |             81.02 |             32.51 |         7.95 |             72.23 | short              |                0.1  |                  1.43 |                 1.15 |
|      9 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.92 |             81.71 |         83.42 |         81.55 |          81.75 |        81.66 |           95.73 |             56.69 |             64.88 |         4.02 |             73.14 | short              |               -1.63 |                  1.76 |                 0.46 |
|     10 | NAT      | NAT                        | US       |                1.44 |             81.67 |         87.29 |         84.09 |          79.24 |        72.94 |           87.74 |             66.96 |             38.08 |         5.09 |             73.14 | short              |               -0.43 |                  1.19 |               nan    |
|     11 | DINO     | DINO                       | US       |               17.28 |             81.19 |         83.58 |         88.22 |          78.8  |        69.28 |           50.36 |             84.64 |             70.81 |         4.51 |             73.14 | swing              |               -0.34 |                nan    |               nan    |
|     12 | APA      | APA                        | US       |               14.38 |             80.88 |         87.24 |         83.23 |          78.52 |        75.71 |           75.11 |             75.65 |             64.41 |         5.92 |             72.11 | short              |                1.65 |                  0.88 |                 0.08 |
|     13 | SHELL.AS | SHELL.AS                   | EUROPE   |              243    |             80.4  |         81.88 |         79.09 |          76.95 |        81.71 |           92.89 |             82.92 |             65.77 |         2.39 |             73.14 | short              |               -0.45 |                  0.79 |                -0.08 |
|     14 | PARR     | Par Pacific Holdings, Inc. | US       |                3.63 |             79.73 |         76.61 |         82.13 |          81.37 |        78.08 |           80.98 |             75.63 |             64.66 |         7.2  |             84.98 | swing              |                1.24 |                  0.3  |                 0.02 |
|     15 | PBF      | PBF                        | US       |                7.67 |             79.08 |         69.42 |         84.42 |          81.42 |        76.74 |           52.65 |             86.48 |             93.04 |         7.84 |             72.68 | swing              |                6.88 |                 -0.5  |                -1.04 |
|     16 | EQNR     | EQNR                       | US       |               93.94 |             79    |         84    |         81.33 |          76.67 |        73.74 |           75.58 |             76.3  |             56.8  |         5.67 |             68.66 | short              |                1.63 |                  0.23 |                -0.37 |
|     17 | KIN.BR   | KIN.BR                     | EUROPE   |                1.31 |             78.84 |         86.51 |         82.49 |          75.18 |        66.05 |           88.47 |             63.78 |             19.77 |         3.89 |             73.14 | short              |               -3.17 |                  0.06 |                -0.01 |
|     18 | KOS      | KOS                        | US       |                1.59 |             78.67 |         85.24 |         80.3  |          77.04 |        73.72 |           65.04 |             93    |             66.78 |         8.81 |             69.68 | short              |                5.26 |                  2.39 |                 1.96 |
|     19 | AMC      | AMC                        | US       |                1.97 |             78.33 |         67.61 |         77.68 |          79.33 |        78.99 |           84.81 |             93.57 |            nan    |         9.71 |             66.89 | medium             |                1.52 |                  2.12 |               nan    |
|     20 | OKTA     | OKTA                       | US       |               28.83 |             77.93 |         91.35 |         83.35 |          72.51 |        59.05 |           70.17 |             67.01 |             14.51 |         7.97 |             71.77 | short              |                0.33 |                  0.82 |                 0.06 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.03 |                  75.76 |                    75.45 |                 76.96 |              75.91 |                86.65 |                   13.35 |           84.94 |             57.59 |       0.863 |         nan |       nan |      nan    |       -78.9  |          2.11 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              243    |                  60.1  |                    72.12 |                 75.94 |              67.44 |                88.21 |                   11.79 |           92.89 |             82.92 |     nan     |         nan |       nan |      nan    |         9.76 |         10.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  64.28 |                    71.84 |                 75.2  |              68.34 |                85.97 |                   14.03 |           94.01 |             65.83 |       0.154 |         nan |       nan |        0.76 |         5.23 |          4.98 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | NVDA     | NVIDIA Corporation                   | US       |             4436.29 |                  61.64 |                    71    |                 72.86 |              66.15 |                77.1  |                   22.9  |           86.9  |             78.92 |       0.008 |         nan |       nan |       25.29 |        13.59 |         26.65 |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL     | SHEL                                 | US       |              244.9  |                  66.37 |                    70.83 |                 72.12 |              69.81 |                76.97 |                   23.03 |           73.84 |             81.68 |     nan     |         nan |       nan |      nan    |         9.57 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.63 |                  68.12 |                    70.62 |                 72.95 |              69.46 |                71.4  |                   28.6  |           80.98 |             75.63 |       0.02  |         nan |       nan |        4.04 |         6.04 |          4.79 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                                   | US       |              104.72 |                  59.14 |                    70.19 |                 73.84 |              66.13 |                82.46 |                   17.54 |           87.22 |             87.03 |     nan     |         nan |       nan |      nan    |         9.65 |         22.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              116.02 |                  75.89 |                    70.14 |                 70.18 |              73    |                57.51 |                   42.49 |           61.58 |             80.09 |       0.137 |         nan |       nan |        1.81 |         4.87 |          4.82 |        5.46 |                 nan |              nan |                  12 |                  0.63 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.58 |                  67.72 |                    70.13 |                 72.46 |              68.33 |                78.89 |                   21.11 |           88.41 |             53.71 |       0.182 |         nan |       nan |        4.15 |         2.71 |          5.27 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT      | DHT                                  | US       |                3.09 |                  59.49 |                    69.91 |                 73.45 |              65.61 |                81.18 |                   18.82 |           89.02 |             81.66 |     nan     |         nan |       nan |      nan    |        10.5  |          7.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | STNE     | StoneCo Ltd.                         | OTHER    |                1.93 |                  72.72 |                    69.58 |                 68.94 |              67.96 |                68.58 |                   31.42 |           84.18 |             32.58 |       0.617 |         nan |       nan |        1.62 |         4.22 |          3.7  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | BBWI     | Bath & Body Works, Inc.              | US       |                2.92 |                  77.31 |                    69.44 |                 66.37 |              69.08 |                55.79 |                   44.21 |           72.59 |             33.73 |       0.227 |         nan |       nan |        5.56 |         6    |          4.7  |        0.73 |                 nan |              nan |                  11 |                  0.58 |
|            9 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.71 |                  74.92 |                    69.26 |                 69.29 |              70.79 |                71.55 |                   28.45 |           75.54 |             39.74 |       0.935 |         nan |       nan |        5.43 |      -124.96 |          2.18 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           10 | AVGO     | Broadcom Inc.                        | US       |             1402.38 |                  62.75 |                    69.17 |                 69.52 |              63.59 |                77.99 |                   22.01 |           92.11 |             43.72 |       0.019 |         nan |       nan |       31.67 |        17.5  |         44.06 |        0.34 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM       | SM                                   | US       |                8.5  |                  61.49 |                    68.21 |                 70.79 |              65.05 |                72    |                   28    |           82.36 |             78.24 |     nan     |         nan |       nan |      nan    |         5.26 |          6.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.95 |                  56.92 |                    68.16 |                 72.1  |              63.11 |                79.49 |                   20.51 |           91.36 |             78.18 |     nan     |         nan |       nan |      nan    |        11.34 |          7.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.92 |                  58.7  |                    67.37 |                 70.54 |              61.96 |                77.95 |                   22.05 |           95.73 |             56.69 |     nan     |         nan |       nan |      nan    |         9.43 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.29 |                  67.86 |                    67.13 |                 66.4  |              68.27 |                69.91 |                   30.09 |           61.65 |            nan    |       0.226 |         nan |       nan |        1.54 |       nan    |          3.06 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | MOMO     | Hello Group Inc.                     | OTHER    |                0.62 |                  77.33 |                    66.97 |                 63.88 |              70.39 |                67.98 |                   32.02 |           60.68 |             24.78 |       0.841 |         nan |       nan |       -5.96 |         4.81 |          4.87 |        0.89 |                 nan |              nan |                   9 |                  0.47 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              178.69 |                  65.52 |                    66.95 |                 67.15 |              67.4  |                70.06 |                   29.94 |           62.94 |             76.16 |     nan     |         nan |       nan |      nan    |         9.28 |         11.72 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.03 |                  75.76 |                    75.45 |                 76.96 |              75.91 |                86.65 |                   13.35 |           84.94 |             57.59 |       0.863 |         nan |       nan |      nan    |       -78.9  |          2.11 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              243    |                  60.1  |                    72.12 |                 75.94 |              67.44 |                88.21 |                   11.79 |           92.89 |             82.92 |     nan     |         nan |       nan |      nan    |         9.76 |         10.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  64.28 |                    71.84 |                 75.2  |              68.34 |                85.97 |                   14.03 |           94.01 |             65.83 |       0.154 |         nan |       nan |        0.76 |         5.23 |          4.98 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                                   | US       |              104.72 |                  59.14 |                    70.19 |                 73.84 |              66.13 |                82.46 |                   17.54 |           87.22 |             87.03 |     nan     |         nan |       nan |      nan    |         9.65 |         22.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.09 |                  59.49 |                    69.91 |                 73.45 |              65.61 |                81.18 |                   18.82 |           89.02 |             81.66 |     nan     |         nan |       nan |      nan    |        10.5  |          7.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.63 |                  68.12 |                    70.62 |                 72.95 |              69.46 |                71.4  |                   28.6  |           80.98 |             75.63 |       0.02  |         nan |       nan |        4.04 |         6.04 |          4.79 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | NVDA     | NVIDIA Corporation                   | US       |             4436.29 |                  61.64 |                    71    |                 72.86 |              66.15 |                77.1  |                   22.9  |           86.9  |             78.92 |       0.008 |         nan |       nan |       25.29 |        13.59 |         26.65 |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.58 |                  67.72 |                    70.13 |                 72.46 |              68.33 |                78.89 |                   21.11 |           88.41 |             53.71 |       0.182 |         nan |       nan |        4.15 |         2.71 |          5.27 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                                 | US       |              244.9  |                  66.37 |                    70.83 |                 72.12 |              69.81 |                76.97 |                   23.03 |           73.84 |             81.68 |     nan     |         nan |       nan |      nan    |         9.57 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.95 |                  56.92 |                    68.16 |                 72.1  |              63.11 |                79.49 |                   20.51 |           91.36 |             78.18 |     nan     |         nan |       nan |      nan    |        11.34 |          7.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                8.5  |                  61.49 |                    68.21 |                 70.79 |              65.05 |                72    |                   28    |           82.36 |             78.24 |     nan     |         nan |       nan |      nan    |         5.26 |          6.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.92 |                  58.7  |                    67.37 |                 70.54 |              61.96 |                77.95 |                   22.05 |           95.73 |             56.69 |     nan     |         nan |       nan |      nan    |         9.43 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               23.84 |                  55.86 |                    66.77 |                 70.4  |              61.18 |                82.24 |                   17.76 |           94.8  |             61.53 |     nan     |         nan |       nan |      nan    |        11.48 |         11.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              116.02 |                  75.89 |                    70.14 |                 70.18 |              73    |                57.51 |                   42.49 |           61.58 |             80.09 |       0.137 |         nan |       nan |        1.81 |         4.87 |          4.82 |        5.46 |                 nan |              nan |                  12 |                  0.63 |
|           10 | AVGO     | Broadcom Inc.                        | US       |             1402.38 |                  62.75 |                    69.17 |                 69.52 |              63.59 |                77.99 |                   22.01 |           92.11 |             43.72 |       0.019 |         nan |       nan |       31.67 |        17.5  |         44.06 |        0.34 |                 nan |              nan |                  12 |                  0.63 |
|            9 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.71 |                  74.92 |                    69.26 |                 69.29 |              70.79 |                71.55 |                   28.45 |           75.54 |             39.74 |       0.935 |         nan |       nan |        5.43 |      -124.96 |          2.18 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | STNE     | StoneCo Ltd.                         | OTHER    |                1.93 |                  72.72 |                    69.58 |                 68.94 |              67.96 |                68.58 |                   31.42 |           84.18 |             32.58 |       0.617 |         nan |       nan |        1.62 |         4.22 |          3.7  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.81 |                  55.04 |                    65.16 |                 68.61 |              59.29 |                80.04 |                   19.96 |           95.86 |             52.47 |     nan     |         nan |       nan |      nan    |        10.9  |         14.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                                  | US       |               98.99 |                  49.07 |                    63.55 |                 68.15 |              58.27 |                82.16 |                   17.84 |           86.11 |             81.44 |     nan     |         nan |       nan |      nan    |        11.21 |         15.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EOG      | EOG                                  | US       |               70.91 |                  55.88 |                    65.11 |                 68.13 |              61.18 |                77.07 |                   22.93 |           83.28 |             70.71 |     nan     |         nan |       nan |      nan    |        10.44 |         11.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                             | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AMC      | AMC                              | US       |                1.97 |                     0.06 |    -0    |      0.05 |                  71.63 |                        80.58 |         67.61 |         77.68 |          79.33 |        78.99 |           84.81 |             93.57 |         9.71 |
|               2 | SRAIL.SW | SRAIL.SW                         | EUROPE   |                3.12 |                     0.06 |     0.01 |      0.26 |                  64.67 |                        79    |         85.88 |         79.04 |          71.44 |        63.62 |           77.5  |             72.39 |         5.69 |
|               3 | DELL     | DELL                             | US       |              299.23 |                     0.04 |     0.02 |      0.13 |                  57.47 |                        78.96 |         87.11 |         84.41 |          79.76 |        67.63 |           73.18 |             81.02 |         7.95 |
|               4 | BLSH     | BLSH                             | US       |                4.66 |                     0.06 |    -0    |      0.42 |                  69.91 |                        77.39 |         80.95 |         66.73 |          54.84 |        53.32 |           67.05 |             86.81 |         9.46 |
|               5 | PBF      | PBF                              | US       |                7.67 |                     0.05 |    -0.03 |     -0    |                  72.88 |                        76.64 |         69.42 |         84.42 |          81.42 |        76.74 |           52.65 |             86.48 |         7.84 |
|               6 | KRX.IR   | KRX.IR                           | EUROPE   |               17.58 |                     0.07 |    -0.06 |     -0.04 |                  78.29 |                        76.53 |         54.38 |         70.23 |          73.49 |        67.75 |           95.48 |             70.5  |         5.7  |
|               7 | BE       | BE                               | US       |               66.14 |                     0.06 |    -0.06 |      0.12 |                  83.78 |                        76.34 |         70.46 |         61.56 |          71.19 |        62.19 |           85.7  |             76.03 |         9.26 |
|               8 | SB       | SB                               | US       |                0.76 |                     0.06 |    -0.04 |      0.06 |                  77.53 |                        76.04 |         75.14 |         78.65 |          77.26 |        73.9  |           69.14 |             75.05 |         4.44 |
|               9 | A5G.IR   | A5G.IR                           | EUROPE   |               23.84 |                     0.02 |     0    |      0.07 |                  50.1  |                        73.99 |         76.57 |         71.24 |          74.48 |        75.19 |           94.8  |             61.53 |         2.41 |
|              10 | SYENS.BR | SYENS.BR                         | EUROPE   |                8    |                     0.04 |    -0.04 |     -0.03 |                  73.74 |                        73.2  |         56.63 |         74.52 |          69.2  |        57.53 |           63.99 |             80.57 |         5.52 |
|              11 | NTAP     | NTAP                             | US       |               32.3  |                     0.07 |     0    |     -0.07 |                  58.95 |                        73.12 |         60.47 |         74.08 |          76.72 |        66.13 |           75.44 |             80.96 |         5.88 |
|              12 | PAGP     | PAGP                             | US       |                5.62 |                     0.02 |    -0.01 |      0.08 |                  52.87 |                        72.95 |         78.02 |         72.96 |          71.87 |        71.75 |           84.02 |             61.32 |         1.77 |
|              13 | NTNX     | NTNX                             | US       |               15.91 |                     0.03 |     0.01 |      0.04 |                  51.02 |                        72.89 |         72.78 |         75.5  |          67.77 |        61.27 |           93.77 |             58.25 |         6.85 |
|              14 | BIRG.IR  | BIRG.IR                          | EUROPE   |               18.81 |                     0.02 |     0    |      0.07 |                  47.69 |                        72.5  |         76.62 |         68.66 |          72.35 |        75.97 |           95.86 |             52.47 |         2.32 |
|              15 | GL9.IR   | GL9.IR                           | EUROPE   |                5.16 |                     0.06 |    -0.05 |     -0.03 |                  82.3  |                        71.88 |         48.18 |         58.87 |          72.32 |        70.59 |           97.68 |             70.43 |         2.63 |
|              16 | HPE      | HPE                              | US       |               64.23 |                     0.1  |    -0    |     -0.03 |                  43.75 |                        71.29 |         66.96 |         75.46 |          80.8  |        73.27 |           72.6  |             83.15 |         7.1  |
|              17 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.55 |                     0.02 |     0    |      0.02 |                  47.29 |                        70.77 |         69.99 |         67.54 |          74.13 |        76.7  |           94.01 |             65.83 |         2.98 |
|              18 | WT       | WT                               | US       |                2.9  |                     0.12 |    -0.1  |     -0.04 |                  59.91 |                        70.41 |         49.24 |         71.17 |          74.02 |        65.94 |           72.58 |             75.49 |         6.04 |
|              19 | HTFL     | HTFL                             | US       |                3.64 |                     0.04 |     0.01 |      0.15 |                  59.02 |                        70.32 |         82.23 |         81.05 |          65.07 |        45.92 |           39.65 |             82.84 |         8.96 |
|              20 | NVDA     | NVIDIA Corporation               | US       |             4436.29 |                     0.08 |    -0.06 |     -0.06 |                  73.85 |                        70.19 |         53.67 |         59.79 |          66.89 |        68.73 |           86.9  |             78.92 |         5.9  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              346.13 |             41.33 |         39.67 |         34.41 |             43 |        50.22 |           77.39 |              45.4 |                26 |         3.45 |             89.74 | long               |               -3.12 |                   0.8 |                 0.84 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                             | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     34 | RBRK     | RBRK                             | US       |               18.46 |             75.42 |         81.97 |         82.16 |          68.88 |        50.18 |           54.04 |             88.62 |              1.79 |         8.81 |             72.23 | swing              |                3.17 |                  3.82 |                 3.34 |
|    109 | CTSH     | CTSH                             | US       |               25.92 |             67.78 |         73.66 |         64.31 |          60.56 |        71.25 |           85.66 |             52.5  |             71    |         8.25 |             70.75 | short              |                0.62 |                  3.65 |                 3.22 |
|     29 | TEN      | Tsakos Energy Navigation Limited | OTHER    |                1.33 |             76.25 |         83.59 |         79.57 |          72.92 |        64.71 |           76.32 |             64.11 |             29    |         4.66 |             78.7  | short              |                1.25 |                  3.58 |               nan    |
|    199 | ACN      | ACN                              | US       |              102.48 |             62.38 |         74.05 |         60.77 |          56.01 |        63.99 |           81.11 |             57.71 |             52.19 |         8.58 |             71.09 | short              |                1.61 |                  3.43 |               nan    |
|     85 | PANW     | PANW                             | US       |              265.68 |             69.68 |         72.76 |         74.46 |          66.59 |        48.59 |           48.95 |             69.19 |              6.52 |         7.7  |             73.14 | swing              |                1.03 |                  3.36 |                 2.61 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    648 | 0QXR.IL  | 0QXR.IL | OTHER    |               13.81 |             40.21 |         23.95 |         28.47 |          51.95 |        72.88 |           75    |            nan    |             97.22 |         9.49 |             61.02 | long               |                2.87 |                 -3.53 |                -2.83 |
|    363 | SBSW     | SBSW    | US       |                7.42 |             56.16 |         59.74 |         50.99 |          52.57 |        63.55 |           58    |             43.13 |             81.4  |         8.61 |             69.68 | long               |              -11.36 |                 -2.95 |               nan    |
|    335 | ASX      | ASX     | US       |               83.69 |             57.41 |         41.28 |         55.83 |          67.55 |        58.99 |           63.89 |             66.49 |             29.87 |         7.58 |             72.68 | medium             |                0.12 |                 -2.61 |                -2.54 |
|    557 | SXC      | SXC     | US       |                0.7  |             48.18 |         44.75 |         56.42 |          51.62 |        37.41 |           20.41 |             57.33 |             28.82 |         6.46 |             71.66 | swing              |               -2.63 |                 -2.55 |                -1.95 |
|    346 | ARGX.BR  | ARGX.BR | EUROPE   |               53.35 |             56.96 |         54.44 |         57.82 |          59.43 |        56.11 |           92.61 |             29.49 |              4.42 |         6.45 |             69.68 | medium             |               -3.47 |                 -2.34 |                -2.06 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
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
- Eligible change vs previous stored run: **-3**

Top exclusion categories:
- liquidity: 231
- price: 181
- market_cap: 160
- price_history: 20
- data_confidence: 13
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| DELL | 8 |  | 3 |  | 2 | main,pullback |
| PARR | 14 | 4 |  | 3 | 1 | value,quality_value |
| PBR-A | 36 | 5 |  | 6 | 1 | value,quality_value |
| DDI | 61 | 2 | 17 | 2 | 1 | value,quality_value |
| BION.SW | 180 | 1 | 84 | 1 | 1 | value,quality_value |
| NVDA | 182 | 3 | 20 | 4 | 1 | value,quality_value |
| IRWD | 215 | 6 | 103 | 5 | 1 | value,quality_value |
| NWL.MI | 302 | 9 |  | 8 | 1 | value,quality_value |
| STNE | 579 | 7 | 184 | 9 | 1 | value,quality_value |
| AVGO | 585 | 10 | 261 | 7 | 1 | value,quality_value |
| SM | 1 |  |  |  | 1 | main |
| VLO | 2 |  |  |  | 1 | main |
| FRO | 3 |  |  |  | 1 | main |
| CRGY | 4 |  |  |  | 1 | main |
| DK | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (SM, VLO, FRO, CRGY, DK, DHT, AVAH, CMBT.BR, NAT)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 73.59 | 75.76 | 60.13 | 84.94 | 57.59 | 86.65 | 63.40 |
| 2 | NVDA | value+pullback | 73.30 | 61.64 | 73.85 | 86.90 | 78.92 | 77.10 | 63.34 |
| 3 | IRWD | value+pullback | 70.59 | 67.72 | 63.44 | 88.41 | 53.71 | 78.89 | 61.90 |
| 4 | ETG | value+pullback | 69.92 | 56.25 | 78.74 | 67.90 | 78.15 | 76.80 | 57.76 |
| 5 | STNE | value+pullback | 69.74 | 72.72 | 73.28 | 84.18 | 32.58 | 68.58 | 47.07 |
| 6 | DDI | value+pullback | 68.98 | 64.28 | 47.29 | 94.01 | 65.83 | 85.97 | 72.06 |
| 7 | AVGO | value+pullback | 68.04 | 62.75 | 61.71 | 92.11 | 43.72 | 77.99 | 46.33 |
| 8 | UNIT | value+pullback | 66.31 | 80.01 | 83.12 | 65.23 | 29.10 | 44.18 | 43.10 |
| 9 | VOLV-B.ST | value+pullback | 65.46 | 70.20 | 77.57 | 59.68 | 44.58 | 58.00 | 50.70 |
| 10 | BHF | value+pullback | 64.13 | 73.03 | 63.99 | 51.59 | 53.66 | 65.57 | 40.73 |
| 11 | 0Q2N.IL | value+pullback | 64.11 | 67.86 | 62.08 | 61.65 |  | 69.91 | 66.51 |
| 12 | RCI | value+pullback | 63.87 | 58.70 | 74.43 | 85.78 | 35.42 | 56.24 | 49.76 |
| 13 | INVA | value+pullback | 63.83 | 58.01 | 62.06 | 83.36 | 31.87 | 76.07 | 47.53 |
| 14 | ORC | value+pullback | 63.58 | 63.46 | 70.39 | 76.18 | 35.38 | 59.89 | 38.88 |
| 15 | SAP.DE | value+pullback | 62.74 | 62.73 | 64.84 | 71.30 | 45.55 | 62.30 | 58.76 |
| 16 | GAB | value+pullback | 62.59 | 56.67 | 69.84 | 54.97 | 78.15 | 60.35 | 48.82 |
| 17 | MAGN | value+pullback | 62.34 | 72.36 | 57.56 | 68.70 | 34.02 | 62.68 | 44.01 |
| 18 | AVK | value+pullback | 61.81 | 55.35 | 76.77 | 62.38 | 49.55 | 58.48 | 46.05 |
| 19 | SDF.DE | value+pullback | 61.47 | 58.59 | 67.09 | 71.35 | 40.22 | 61.97 | 61.39 |
| 20 | MFA | value+pullback | 61.15 | 57.07 | 73.46 | 75.60 | 26.46 | 58.41 | 36.62 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 72.7 | 1 / 9 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 72.3 | 5 / 20 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 72.2 | 15 / 35 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=2, large_20_100b=1, mega_100b_plus=1
