# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-21

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

- **EUROPE:** 78.5/100
- **OTHER:** 64.2/100
- **US:** 79.7/100

## Main multi-horizon ranking

|   rank | symbol    | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC       | MPC                        | US       |              103.97 |             87.72 |         87.59 |         93.1  |          87.85 |        81.48 |           84.06 |             90.05 |             61.91 |         4.12 |             73.14 | swing              |                0.68 |                nan    |               nan    |
|      2 | FRO       | FRO                        | US       |                9.97 |             86.88 |         88.22 |         88.43 |          85.54 |        81.24 |           91.64 |             80.14 |             56.36 |         5.63 |             73.14 | swing              |                0.71 |                  0.26 |                -0.15 |
|      3 | DHT       | DHT                        | US       |                3.27 |             85.63 |         88.12 |         87.26 |          84.01 |        81.3  |           89.48 |             83.98 |             59.61 |         4.76 |             73.14 | short              |                1.05 |                  0.41 |                -0.25 |
|      4 | DELL      | DELL                       | US       |              314.72 |             84.55 |         89.79 |         87.65 |          81.45 |        68.8  |           73.08 |             85.84 |             33.14 |         7.95 |             72.23 | short              |                0.84 |                  0.49 |                -0.49 |
|      5 | DK        | DK                         | US       |                4.17 |             84.32 |         90.3  |         88.53 |          80.11 |        69    |           55.41 |             93.4  |             56.13 |         7.41 |             73.14 | short              |                0.4  |                 -0.14 |                -0.36 |
|      6 | CMBT.BR   | CMBT.BR                    | EUROPE   |                5.12 |             84.25 |         87.08 |         83.98 |          84.52 |        82.02 |           95.83 |             76.72 |             61.01 |         4.02 |             73.14 | short              |                0.08 |                  0.51 |                 0.19 |
|      7 | SB        | SB                         | US       |                0.91 |             83.36 |         90.22 |         86.31 |          80.41 |        75.01 |           70.29 |             83.22 |             64.14 |         4.38 |             72.34 | short              |                1.46 |                  1.43 |                 0.76 |
|      8 | NAT       | NAT                        | US       |                1.52 |             82.74 |         87.05 |         85.38 |          80.09 |        73.03 |           87.14 |             69.8  |             36.77 |         5.05 |             73.14 | short              |                0.93 |                  0.21 |                -0.11 |
|      9 | HPE       | HPE                        | US       |               70.28 |             82.33 |         84.59 |         84.4  |          80.25 |        72.16 |           73.64 |             74.04 |             52.38 |         7.12 |             72.34 | short              |                0.89 |                  1.59 |                 0.97 |
|     10 | PBF       | PBF                        | US       |                7.97 |             82.11 |         83.09 |         87.89 |          81.13 |        75.97 |           51.56 |             87.9  |             90.14 |         7.81 |             72.68 | swing              |                0.58 |                  0.61 |                 0.17 |
|     11 | DINO      | DINO                       | US       |               17.95 |             82.03 |         84.98 |         89.39 |          79.08 |        69.17 |           48.8  |             87.09 |             70.56 |         4.5  |             73.14 | swing              |                0.5  |                  0.17 |                -0.31 |
|     12 | SM        | SM                         | US       |                7.66 |             81.22 |         65.64 |         79.85 |          82.6  |        86.25 |           82.02 |             78.95 |             95.59 |         7.2  |             72.11 | long               |                1.19 |                 -1.17 |                -1.27 |
|     13 | CRGY      | CRGY                       | US       |                4.76 |             79.89 |         68.35 |         79.58 |          80.2  |        84.25 |           72.36 |             90.14 |             94.71 |         6.62 |             72.68 | long               |                1.16 |                 -1.08 |                -1.4  |
|     14 | PARR      | Par Pacific Holdings, Inc. | US       |                3.68 |             79.31 |         81.6  |         81.22 |          77.41 |        73.12 |           77.17 |             76.63 |             56.29 |         7.1  |             84.98 | short              |                0.25 |                 -0.08 |                -0.16 |
|     15 | MU        | MU                         | US       |              999.68 |             78.72 |         73.57 |         67.35 |          83.87 |        84.94 |           95.72 |             76.04 |             72.83 |         8.39 |             73.14 | long               |                1.01 |                  1.52 |                 1.22 |
|     16 | DAR       | DAR                        | US       |                8.99 |             78.5  |         68.65 |         76.02 |          80.98 |        83.95 |           92.28 |             86.42 |             65.94 |         4.72 |             71.32 | long               |                1.18 |                nan    |               nan    |
|     17 | HALO      | HALO                       | US       |               11.12 |             78.44 |         81.78 |         81.91 |          75.11 |        71.66 |           84.71 |             53.15 |             50.24 |         6.05 |             72.11 | swing              |              nan    |                nan    |               nan    |
|     18 | KIN.BR    | KIN.BR                     | EUROPE   |                1.33 |             77.96 |         84.45 |         81.29 |          74.63 |        65.33 |           88.42 |             65.53 |             20    |         3.96 |             73.14 | short              |               -0.4  |                 -0.17 |                -0.5  |
|     19 | SSABBH.HE | SSABBH.HE                  | EUROPE   |                9.42 |             77.67 |         76.22 |         73.17 |          79.11 |        80.46 |           68.12 |            nan    |             98.75 |         4.47 |             62.84 | long               |              nan    |                  0.61 |               nan    |
|     20 | AVAH      | AVAH                       | US       |                2.6  |             77.66 |         76.92 |         82.19 |          78.39 |        73.32 |           92.76 |             56.32 |             39.86 |         7.86 |             72.11 | swing              |               -1.18 |                 -1.06 |                -1.06 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.05 |                  76.12 |                    75.77 |                 77.28 |              76.33 |                86.84 |                   13.16 |           84.64 |             58.92 |       0.857 |         nan |       nan |      nan    |       -79.51 |          2.13 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  65.67 |                    72.69 |                 75.96 |              69.49 |                85.5  |                   14.5  |           93.42 |             68.21 |       0.154 |         nan |       nan |        0.76 |         5.23 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              235.97 |                  59.79 |                    71.77 |                 75.59 |              67.11 |                87.65 |                   12.35 |           92.44 |             82.88 |     nan     |         nan |       nan |      nan    |         9.43 |         10.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.28 |                  75.18 |                    71.39 |                 71.83 |              73.9  |                65.02 |                   34.98 |           64.63 |             80.61 |       0.143 |         nan |       nan |        1.79 |         4.68 |          4.75 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|            4 | BBWI     | Bath & Body Works, Inc.              | US       |                3.06 |                  75.58 |                    71.17 |                 68.68 |              70.38 |                69.51 |                   30.49 |           76.3  |             34.45 |       0.218 |         nan |       nan |        5.67 |         6.24 |          4.57 |        0.71 |                 nan |              nan |                  11 |                  0.58 |
|            5 | NVDA     | NVIDIA Corporation                   | US       |             4676.83 |                  60.87 |                    70.84 |                 72.88 |              65.87 |                77.48 |                   22.52 |           86.9  |             80.93 |       0.008 |         nan |       nan |       26.5  |        14.17 |         28.1  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.12 |                  58.62 |                    70.48 |                 74.51 |              65.08 |                84.44 |                   15.56 |           95.83 |             76.72 |     nan     |         nan |       nan |      nan    |         9.77 |          6.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.27 |                  58.42 |                    69.76 |                 73.58 |              65.24 |                82.13 |                   17.87 |           89.48 |             83.98 |     nan     |         nan |       nan |      nan    |        10.85 |          7.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.66 |                  64    |                    69.67 |                 71.94 |              66.92 |                71.93 |                   28.07 |           82.02 |             78.95 |     nan     |         nan |       nan |      nan    |         4.71 |          6.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.77 |                  74.54 |                    68.95 |                 69.23 |              70.32 |                68.04 |                   31.96 |           75.5  |             44.08 |       0.606 |         nan |       nan |        4.33 |      -134.96 |          2.32 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | EMBC     | Embecta Corp.                        | US       |                0.26 |                  71.15 |                    68.72 |                 68.96 |              69.46 |                65.4  |                   34.6  |           69.73 |             64.66 |       0.461 |         nan |       nan |        5.64 |         3    |          3.6  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | STNE     | StoneCo Ltd.                         | OTHER    |                1.91 |                  71.4  |                    68.48 |                 67.97 |              66.55 |                65.99 |                   34.01 |           84.18 |             32.68 |       0.628 |         nan |       nan |        1.61 |         4.17 |          3.6  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1487.53 |                  60.81 |                    68.24 |                 68.83 |              62.31 |                78.34 |                   21.66 |           92.29 |             44.27 |       0.018 |         nan |       nan |       33.34 |        18.45 |         45.67 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               19.08 |                  55.34 |                    67.81 |                 71.9  |              61.94 |                85.02 |                   14.98 |           96.25 |             67.88 |     nan     |         nan |       nan |      nan    |        11.03 |         14.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              175.22 |                  65.29 |                    67.77 |                 68.32 |              67.87 |                71.92 |                   28.08 |           65.13 |             79.14 |     nan     |         nan |       nan |      nan    |         8.9  |         11.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EOG      | EOG                                  | US       |               65.92 |                  59.54 |                    67.62 |                 70.26 |              64.39 |                77.66 |                   22.34 |           81.99 |             75.46 |     nan     |         nan |       nan |      nan    |         9.74 |         11.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.25 |                  69.88 |                    67.57 |                 66.28 |              69.47 |                67.83 |                   32.17 |           58.88 |            nan    |       0.228 |         nan |       nan |        1.54 |       nan    |          3.02 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | FRO      | FRO                                  | US       |                9.97 |                  55.13 |                    67.5  |                 71.78 |              62.16 |                80.26 |                   19.74 |           91.64 |             80.14 |     nan     |         nan |       nan |      nan    |        11.23 |          7.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.87 |                  62.57 |                    67.32 |                 68.83 |              64.08 |                76.91 |                   23.09 |           85.42 |             51.92 |     nan     |         nan |       nan |      nan    |         8.83 |          7.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              112.25 |                  60.68 |                    67.29 |                 69.42 |              64.29 |                76.72 |                   23.28 |           81.69 |             67.87 |     nan     |         nan |       nan |      nan    |         9.61 |         13.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.05 |                  76.12 |                    75.77 |                 77.28 |              76.33 |                86.84 |                   13.16 |           84.64 |             58.92 |       0.857 |         nan |       nan |      nan    |       -79.51 |          2.13 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  65.67 |                    72.69 |                 75.96 |              69.49 |                85.5  |                   14.5  |           93.42 |             68.21 |       0.154 |         nan |       nan |        0.76 |         5.23 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              235.97 |                  59.79 |                    71.77 |                 75.59 |              67.11 |                87.65 |                   12.35 |           92.44 |             82.88 |     nan     |         nan |       nan |      nan    |         9.43 |         10.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.12 |                  58.62 |                    70.48 |                 74.51 |              65.08 |                84.44 |                   15.56 |           95.83 |             76.72 |     nan     |         nan |       nan |      nan    |         9.77 |          6.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.27 |                  58.42 |                    69.76 |                 73.58 |              65.24 |                82.13 |                   17.87 |           89.48 |             83.98 |     nan     |         nan |       nan |      nan    |        10.85 |          7.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NVDA     | NVIDIA Corporation                   | US       |             4676.83 |                  60.87 |                    70.84 |                 72.88 |              65.87 |                77.48 |                   22.52 |           86.9  |             80.93 |       0.008 |         nan |       nan |       26.5  |        14.17 |         28.1  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM       | SM                                   | US       |                7.66 |                  64    |                    69.67 |                 71.94 |              66.92 |                71.93 |                   28.07 |           82.02 |             78.95 |     nan     |         nan |       nan |      nan    |         4.71 |          6.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               19.08 |                  55.34 |                    67.81 |                 71.9  |              61.94 |                85.02 |                   14.98 |           96.25 |             67.88 |     nan     |         nan |       nan |      nan    |        11.03 |         14.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.28 |                  75.18 |                    71.39 |                 71.83 |              73.9  |                65.02 |                   34.98 |           64.63 |             80.61 |       0.143 |         nan |       nan |        1.79 |         4.68 |          4.75 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                                  | US       |                9.97 |                  55.13 |                    67.5  |                 71.78 |              62.16 |                80.26 |                   19.74 |           91.64 |             80.14 |     nan     |         nan |       nan |      nan    |        11.23 |          7.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                                  | US       |              103.97 |                  52.18 |                    66.01 |                 70.4  |              61.45 |                82.65 |                   17.35 |           84.06 |             90.05 |     nan     |         nan |       nan |      nan    |         9.79 |         14.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EOG      | EOG                                  | US       |               65.92 |                  59.54 |                    67.62 |                 70.26 |              64.39 |                77.66 |                   22.34 |           81.99 |             75.46 |     nan     |         nan |       nan |      nan    |         9.74 |         11.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              112.25 |                  60.68 |                    67.29 |                 69.42 |              64.29 |                76.72 |                   23.28 |           81.69 |             67.87 |     nan     |         nan |       nan |      nan    |         9.61 |         13.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.77 |                  74.54 |                    68.95 |                 69.23 |              70.32 |                68.04 |                   31.96 |           75.5  |             44.08 |       0.606 |         nan |       nan |        4.33 |      -134.96 |          2.32 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | OXY      | OXY                                  | US       |               51.25 |                  53.09 |                    65.09 |                 69.08 |              60.57 |                78.21 |                   21.79 |           84.24 |             82.64 |     nan     |         nan |       nan |      nan    |        14.58 |         17.36 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | EMBC     | Embecta Corp.                        | US       |                0.26 |                  71.15 |                    68.72 |                 68.96 |              69.46 |                65.4  |                   34.6  |           69.73 |             64.66 |       0.461 |         nan |       nan |        5.64 |         3    |          3.6  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           17 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.68 |                  61.91 |                    66.25 |                 68.87 |              64.5  |                68.13 |                   31.87 |           77.17 |             76.63 |       0.019 |         nan |       nan |        4.07 |         6.1  |          4.95 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.87 |                  62.57 |                    67.32 |                 68.83 |              64.08 |                76.91 |                   23.09 |           85.42 |             51.92 |     nan     |         nan |       nan |      nan    |         8.83 |          7.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1487.53 |                  60.81 |                    68.24 |                 68.83 |              62.31 |                78.34 |                   21.66 |           92.29 |             44.27 |       0.018 |         nan |       nan |       33.34 |        18.45 |         45.67 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP       | BP                                   | US       |              100.04 |                  58.69 |                    66.15 |                 68.81 |              62.2  |                74.51 |                   25.49 |           85.68 |             65.31 |     nan     |         nan |       nan |      nan    |         9.13 |         21.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | DELL     | DELL                                 | US       |              314.72 |                     0.03 |     0    |      0.31 |                  57.79 |                        81.06 |         89.79 |         87.65 |          81.45 |        68.8  |           73.08 |             85.84 |         7.95 |
|               2 | BE       | BE                                   | US       |               68.17 |                     0.05 |    -0.04 |      0.31 |                  80.85 |                        79.74 |         76.62 |         61.12 |          71.77 |        63.37 |           86.48 |             80.07 |         9.23 |
|               3 | AVAH     | AVAH                                 | US       |                2.6  |                     0.05 |    -0.03 |      0.05 |                  75.84 |                        79.47 |         76.92 |         82.19 |          78.39 |        73.32 |           92.76 |             56.32 |         7.86 |
|               4 | SHELL.AS | SHELL.AS                             | EUROPE   |              235.97 |                     0.03 |    -0    |      0.04 |                  57.57 |                        78.93 |         78.76 |         74.93 |          74.69 |        80.04 |           92.44 |             82.88 |         2.55 |
|               5 | DAR      | DAR                                  | US       |                8.99 |                     0.03 |     0    |     -0.04 |                  57.06 |                        77.99 |         68.65 |         76.02 |          80.98 |        83.95 |           92.28 |             86.42 |         4.72 |
|               6 | CRGY     | CRGY                                 | US       |                4.76 |                     0.1  |    -0.05 |      0.01 |                  60.8  |                        76.9  |         68.35 |         79.58 |          80.2  |        84.25 |           72.36 |             90.14 |         6.62 |
|               7 | TALO     | TALO                                 | US       |                2.47 |                     0.07 |    -0.04 |     -0.04 |                  71.35 |                        76.49 |         60.81 |         76.04 |          77.05 |        76.38 |           67.85 |             94.64 |         5.84 |
|               8 | HPE      | HPE                                  | US       |               70.28 |                     0.02 |    -0.02 |      0.15 |                  54.04 |                        76.23 |         84.59 |         84.4  |          80.25 |        72.16 |           73.64 |             74.04 |         7.12 |
|               9 | NVDA     | NVIDIA Corporation                   | US       |             4676.83 |                     0.03 |     0.02 |      0.03 |                  52.54 |                        76    |         77.21 |         68.96 |          69.53 |        68.8  |           86.9  |             80.93 |         5.88 |
|              10 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.68 |                     0.02 |    -0    |      0.16 |                  52.92 |                        75.67 |         81.6  |         81.22 |          77.41 |        73.12 |           77.17 |             76.63 |         7.1  |
|              11 | SRAIL.SW | SRAIL.SW                             | EUROPE   |                3.15 |                     0.05 |     0.01 |      0.23 |                  66.13 |                        75.54 |         83.43 |         72.38 |          65.89 |        60.38 |           78.22 |             55.05 |         5.68 |
|              12 | SM       | SM                                   | US       |                7.66 |                     0.1  |    -0.03 |     -0.01 |                  48.76 |                        75.48 |         65.64 |         79.85 |          82.6  |        86.25 |           82.02 |             78.95 |         7.2  |
|              13 | PR       | PR                                   | US       |               16.61 |                     0.06 |    -0.04 |     -0.04 |                  75.61 |                        74.91 |         59.21 |         73.02 |          75.51 |        77.42 |           77.07 |             77.66 |         4.67 |
|              14 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.28 |                     0.04 |    -0.02 |      0.14 |                  64.94 |                        74.9  |         80.28 |         76.69 |          71.96 |        74.82 |           64.63 |             80.61 |         3.85 |
|              15 | CIRSA.MC | CIRSA.MC                             | EUROPE   |                3.27 |                     0.02 |     0.01 |      0.38 |                  44.37 |                        73.57 |         83.83 |         79.44 |          68.24 |        66.71 |           80.3  |             59.59 |         5.64 |
|              16 | PBR      | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              116.8  |                     0.04 |    -0.02 |      0.13 |                  69.87 |                        73.43 |         79.19 |         73.06 |          68.73 |        71.62 |           64.63 |             69.53 |         4.55 |
|              17 | WT       | WT                                   | US       |                3.05 |                     0.08 |    -0.04 |      0.02 |                  66.66 |                        73.3  |         66.41 |         76.23 |          74.26 |        65.62 |           73.84 |             69.41 |         6.08 |
|              18 | C5H.IR   | C5H.IR                               | EUROPE   |                1.64 |                     0.07 |    -0.01 |      0.07 |                  67.68 |                        73.27 |         73.22 |         66.33 |          69.34 |        74.6  |           97.85 |             46.24 |         2.84 |
|              19 | MT.AS    | MT.AS                                | EUROPE   |               47.49 |                     0.07 |    -0.02 |      0.01 |                  69.99 |                        72.93 |         62.99 |         72.57 |          76.96 |        73.76 |           69.13 |             82.15 |         5.25 |
|              20 | OXY      | OXY                                  | US       |               51.25 |                     0.07 |    -0.04 |     -0.04 |                  71.7  |                        72.68 |         54.4  |         65.36 |          69.6  |        74.08 |           84.24 |             82.64 |         5.2  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              345.98 |             41.67 |          40.4 |         35.01 |          42.93 |        49.99 |           77.39 |              45.4 |                26 |          3.3 |              89.8 | long               |               -0.42 |                  0.07 |                 0.16 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    187 | 0QXR.IL  | 0QXR.IL | OTHER    |               13.98 |             62.99 |         61.57 |         59.7  |          64.42 |        80.74 |           85.71 |            nan    |             95.65 |         9.2  |             61.02 | long               |                2.93 |                  4.56 |                 3.34 |
|    342 | ABSI     | ABSI    | US       |                1.44 |             57.06 |         67.02 |         62.93 |          51.18 |        31.51 |            3.95 |             40.03 |             21.84 |         9.22 |             69.27 | short              |                0.8  |                  3.55 |                 3.29 |
|    297 | VSAT     | VSAT    | US       |                9.17 |             58.53 |         65.66 |         61.53 |          55.53 |        40.07 |           26.21 |             58.51 |             14.77 |         7.87 |             73.14 | short              |                0.58 |                  2.86 |               nan    |
|    164 | INTC     | INTC    | US       |              500.23 |             64    |         77.64 |         61.76 |          66.25 |        49.44 |           45.2  |             85.83 |             11.81 |         8.29 |             73.14 | short              |                0.19 |                  2.84 |               nan    |
|     73 | SBSW     | SBSW    | US       |                7.35 |             69.9  |         68.62 |         70.78 |          69.02 |        72.41 |           57.46 |             92.4  |             82.66 |         8.47 |             69.68 | long               |                0.53 |                  2.75 |                 2.34 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    561 | PTEN     | PTEN                       | US       |                3.91 |             47.5  |         46.41 |         53.92 |          48.59 |        41.13 |           26.91 |             41.41 |             27.13 |         7.28 |             73.14 | swing              |                0.25 |                 -3.85 |                -3.21 |
|    565 | EGY      | EGY                        | US       |                0.56 |             47.4  |         60.27 |         50.46 |          44.35 |        41.09 |           34.12 |             37.86 |             26.55 |         5.78 |             69.68 | short              |              nan    |                 -2.84 |                -2.47 |
|    291 | BTE      | BTE                        | US       |                2.95 |             58.83 |         60.67 |         62.21 |          56.98 |        52.37 |           41.11 |             50.56 |             44.02 |         5.76 |             69.68 | swing              |                0.52 |                 -2.71 |                -2.38 |
|    414 | NOG      | NOG                        | US       |                2.33 |             53.96 |         42.49 |         61.28 |          52.73 |        55.19 |           18.04 |             71.38 |             92.12 |         7.38 |             68.2  | swing              |              nan    |                 -2.51 |                -2.06 |
|    626 | DEC      | Diversified Energy Company | US       |                0.83 |             43.75 |         36.04 |         41.38 |          46.12 |        57.01 |           64.54 |             32.86 |             63.93 |         5.61 |             82.82 | long               |                5.24 |                 -2.5  |                -1.6  |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
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
- Excluded by hard/data filters: **280**
- Event watch (otherwise eligible): **1**
- Final eligible: **719**
- Eligible change vs previous stored run: **+6**

Top exclusion categories:
- liquidity: 223
- price: 179
- market_cap: 152
- price_history: 19
- data_confidence: 11
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| NVDA | 81 | 5 | 9 | 3 | 2 | value,pullback,quality_value |
| DELL | 4 |  | 1 |  | 2 | main,pullback |
| HPE | 9 |  | 8 |  | 2 | main,pullback |
| PARR | 14 | 17 | 10 | 7 | 1 | pullback,quality_value |
| PBR-A | 30 | 3 | 14 | 4 | 1 | value,quality_value |
| DDI | 51 | 2 | 33 | 2 | 1 | value,quality_value |
| BION.SW | 137 | 1 | 86 | 1 | 1 | value,quality_value |
| NWL.MI | 197 | 6 |  | 5 | 1 | value,quality_value |
| EMBC | 248 | 7 |  | 6 | 1 | value,quality_value |
| AVGO | 398 | 9 | 122 | 8 | 1 | value,quality_value |
| BBWI | 650 | 4 | 381 | 9 | 1 | value,quality_value |
| MPC | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| DHT | 3 |  |  |  | 1 | main |
| DK | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (MPC, FRO, DHT, CMBT.BR, SB, NAT, PBF)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **3** (BE, SHELL.AS, CRGY)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 73.03 | 76.12 | 56.95 | 84.64 | 58.92 | 86.84 | 65.31 |
| 2 | PBR-A | value+pullback | 69.55 | 75.18 | 64.94 | 64.63 | 80.61 | 65.02 | 75.75 |
| 3 | DDI | value+pullback | 69.05 | 65.67 | 45.68 | 93.42 | 68.21 | 85.50 | 72.70 |
| 4 | STNE | value+pullback | 68.31 | 71.40 | 71.20 | 84.18 | 32.68 | 65.99 | 46.02 |
| 5 | AVGO | value+pullback | 68.06 | 60.81 | 63.52 | 92.29 | 44.27 | 78.34 | 54.55 |
| 6 | NVDA | value+pullback | 68.02 | 60.87 | 52.54 | 86.90 | 80.93 | 77.48 | 69.24 |
| 7 | 0Q2N.IL | value+pullback | 66.85 | 69.88 | 73.97 | 58.88 |  | 67.83 | 65.44 |
| 8 | VOLV-B.ST | value+pullback | 66.56 | 74.09 | 75.46 | 55.24 | 54.57 | 58.62 | 55.41 |
| 9 | PBR | value+pullback | 66.00 | 64.78 | 69.87 | 64.63 | 69.53 | 62.25 | 72.34 |
| 10 | BBWI | value+pullback | 65.54 | 75.58 | 56.31 | 76.30 | 34.45 | 69.51 | 40.61 |
| 11 | RCI | value+pullback | 64.80 | 61.25 | 71.98 | 84.40 | 43.27 | 57.21 | 47.29 |
| 12 | PARR | value+pullback | 64.67 | 61.91 | 52.92 | 77.17 | 76.63 | 68.13 | 79.31 |
| 13 | UNIT | value+pullback | 64.13 | 80.01 | 74.52 | 64.98 | 29.04 | 44.21 | 40.93 |
| 14 | BCE | value+pullback | 63.34 | 57.11 | 79.05 | 68.54 | 58.02 | 51.80 | 44.33 |
| 15 | BHF | value+pullback | 62.14 | 70.59 | 57.69 | 51.67 | 55.75 | 66.07 | 43.37 |
| 16 | JD | value+pullback | 61.26 | 68.72 | 54.75 | 65.87 | 46.76 | 62.01 | 43.94 |
| 17 | MFA | value+pullback | 61.07 | 58.14 | 70.89 | 76.63 | 26.36 | 58.89 | 38.70 |
| 18 | AMCX | value+pullback | 61.06 | 64.18 | 56.39 | 47.83 | 67.09 | 69.14 | 62.90 |
| 19 | GNW | value+pullback | 60.78 | 60.87 | 81.14 | 26.26 | 85.48 | 48.72 | 59.20 |
| 20 | IRS | value+pullback | 60.74 | 67.99 | 59.35 | 61.40 | 40.96 | 61.00 | 52.27 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 73.1 | 3 / 7 |
| Top 25 | 25/25 | 24/25 | 25/25 | 24/25 | 0/25 | 72.7 | 7 / 18 |
| Top 50 | 50/50 | 48/50 | 49/50 | 47/50 | 0/50 | 72.3 | 18 / 32 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=3, large_20_100b=1, mega_100b_plus=2
