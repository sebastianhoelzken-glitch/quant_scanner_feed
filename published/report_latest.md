# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-22

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

- **EUROPE:** 81.4/100
- **OTHER:** 65.3/100
- **US:** 82.2/100

## Main multi-horizon ranking

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC     | US       |               98.43 |             87.05 |         86.33 |         90.02 |          87.76 |        82.57 |           84.52 |             89.5  |             65.96 |         4.19 |             73.14 | swing              |               -0.73 |                nan    |               nan    |
|      2 | VLO      | VLO     | US       |               98.64 |             85.94 |         86.77 |         87.68 |          85.12 |        79.83 |           85.51 |             81.72 |             57.91 |         3.5  |             69.68 | swing              |              nan    |                 -0.02 |               nan    |
|      3 | FRO      | FRO     | US       |                9.66 |             85.32 |         89.93 |         85.57 |          85.06 |        81.35 |           91.62 |             80.62 |             57.62 |         5.54 |             73.14 | short              |               -1.51 |                 -0.21 |                -0.42 |
|      4 | PSX      | PSX     | US       |               91.42 |             84.1  |         84.06 |         87.37 |          84.14 |        78.67 |           80.08 |             87.69 |             59.92 |         3.73 |             73.14 | swing              |              nan    |                nan    |               nan    |
|      5 | DELL     | DELL    | US       |              318.64 |             84.06 |         92.31 |         87.2  |          80.93 |        67.74 |           73.64 |             85.89 |             28.7  |         7.85 |             72.23 | short              |               -0.4  |                  0.12 |               nan    |
|      6 | HSHP     | HSHP    | US       |                0.77 |             83.47 |         91.34 |         86.16 |          80.78 |        70.54 |           86.51 |            nan    |             29.37 |         4.79 |             62.84 | short              |              nan    |                nan    |               nan    |
|      7 | CMBT.BR  | CMBT.BR | EUROPE   |                5.03 |             83.41 |         86.14 |         82.24 |          84.44 |        82.38 |           95.9  |             77.68 |             61.98 |         3.91 |             73.14 | short              |               -1.82 |                 -0.65 |                -0.72 |
|      8 | DHT      | DHT     | US       |                3.15 |             82.43 |         86.25 |         82.2  |          82.65 |        81.15 |           89.36 |             82.96 |             62.05 |         4.57 |             73.14 | short              |               -3.16 |                 -0.6  |                -1.02 |
|      9 | HPE      | HPE     | US       |               71.4  |             81.88 |         90.12 |         83.87 |          79.9  |        71.59 |           74.19 |             73.87 |             50.04 |         6.99 |             72.34 | short              |               -0.34 |                  1.55 |               nan    |
|     10 | MU       | MU      | US       |             1027.06 |             81.2  |         77.6  |         68.82 |          84.8  |        85.11 |           95.5  |             81.25 |             71.33 |         8.31 |             73.14 | long               |                2.5  |                  1.81 |                 1.15 |
|     11 | NAT      | NAT     | US       |                1.48 |             80.99 |         88.42 |         82.56 |          79.41 |        72.56 |           87.23 |             69.88 |             35.82 |         4.8  |             73.14 | short              |               -1.65 |                 -0.22 |                -0.39 |
|     12 | DINO     | DINO    | US       |               16.93 |             80.47 |         81.46 |         86.45 |          79.48 |        70.81 |           49.98 |             86.91 |             75.09 |         4.52 |             73.14 | swing              |               -1.58 |                 -0.23 |                -0.34 |
|     13 | GH       | GH      | US       |               20.33 |             79.65 |         74.33 |         84.84 |          83.36 |        75.95 |           62.46 |             88.38 |            nan    |         7.03 |             68.36 | swing              |              nan    |                nan    |               nan    |
|     14 | TRMD     | TRMD    | US       |                3.32 |             79.23 |         87.37 |         78.39 |          76.92 |        80.07 |           85.78 |             48.29 |             80.94 |         5.44 |             69.68 | short              |              nan    |                nan    |               nan    |
|     15 | PBF      | PBF     | US       |                7.48 |             78.71 |         67.92 |         81.83 |          80.4  |        77.03 |           53.31 |             88.42 |             91.33 |         7.7  |             72.68 | swing              |               -3.16 |                 -0.1  |                -0.22 |
|     16 | OKTA     | OKTA    | US       |               29.14 |             78.61 |         89.9  |         84.4  |          72.82 |        59.5  |           69.85 |             69.83 |             14.95 |         7.84 |             72.11 | short              |              nan    |                  0.2  |                 0.12 |
|     17 | NTAP     | NTAP    | US       |               33.9  |             78.1  |         79.2  |         80.92 |          77    |        65.26 |           74.52 |             82.22 |             26.38 |         5.72 |             72.11 | swing              |                1.44 |                nan    |               nan    |
|     18 | KIN.BR   | KIN.BR  | EUROPE   |                1.34 |             77.91 |         82.26 |         80.95 |          74.88 |        65.57 |           88.97 |             65.02 |             19.51 |         3.75 |             73.14 | short              |               -1.3  |                 -0.22 |                -0.14 |
|     19 | P        | P       | US       |               32.99 |             77.69 |         87.84 |         83.59 |          71.79 |        58.63 |           71.62 |             86.25 |             11.07 |         8.2  |             72.68 | short              |                6.77 |                  3.02 |                 2.38 |
|     20 | SB       | SB      | US       |                0.88 |             77.51 |         81.43 |         78.65 |          76.37 |        72.73 |           70.59 |             69.44 |             63.65 |         4.21 |             72.34 | short              |               -5.79 |                 -0.37 |                -0.6  |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.03 |                  76.12 |                    75.75 |                 77.25 |              76.32 |                86.87 |                   13.13 |           84.64 |             58.72 |       0.865 |         nan |       nan |      nan    |       -78.75 |          2.11 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.57 |                  65.67 |                    72.64 |                 75.9  |              69.44 |                85.41 |                   14.59 |           93.42 |             67.86 |       0.15  |         nan |       nan |        0.87 |         5.37 |          5.2  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | BBWI     | Bath & Body Works, Inc.              | US       |                2.97 |                  78.11 |                    71.58 |                 68.83 |              71.01 |                63.01 |                   36.99 |           76.3  |             34.34 |       0.224 |         nan |       nan |        5.59 |         6.07 |          4.44 |        0.71 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              232.89 |                  59.16 |                    71.54 |                 75.47 |              66.73 |                88.12 |                   11.88 |           92.89 |             82.71 |     nan     |         nan |       nan |      nan    |         9.31 |         10.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.77 |                  75.31 |                    71.49 |                 71.93 |              74.02 |                65.28 |                   34.72 |           64.7  |             80.5  |       0.143 |         nan |       nan |        1.79 |         4.66 |          4.73 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|            5 | NVDA     | NVIDIA Corporation                   | US       |             4782.81 |                  60.87 |                    70.88 |                 72.93 |              65.91 |                77.63 |                   22.37 |           86.9  |             81.12 |       0.008 |         nan |       nan |       27.11 |        14.5  |         28.75 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|            6 | STNE     | StoneCo Ltd.                         | OTHER    |                1.95 |                  75    |                    70.46 |                 69.6  |              69.15 |                66.06 |                   33.94 |           84.18 |             32.63 |       0.616 |         nan |       nan |        1.62 |         4.26 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.03 |                  58.15 |                    70.41 |                 74.55 |              64.94 |                85.01 |                   14.99 |           95.9  |             77.68 |     nan     |         nan |       nan |      nan    |         9.59 |          6.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.15 |                  59.41 |                    70.2  |                 73.84 |              65.85 |                82.11 |                   17.89 |           89.36 |             82.96 |     nan     |         nan |       nan |      nan    |        10.46 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | EMBC     | Embecta Corp.                        | US       |                0.26 |                  73.36 |                    69.65 |                 69.66 |              70.72 |                63.64 |                   36.36 |           69.73 |             64.44 |       0.46  |         nan |       nan |        5.64 |         3.01 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM       | SM                                   | US       |                7.2  |                  63.14 |                    69.44 |                 71.89 |              66.53 |                72.56 |                   27.44 |           82.34 |             80.07 |     nan     |         nan |       nan |      nan    |         4.4  |          6.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.77 |                  74.83 |                    69.12 |                 69.37 |              70.55 |                68.18 |                   31.82 |           75.5  |             43.97 |       0.608 |         nan |       nan |        4.33 |      -134.67 |          2.32 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1508.05 |                  60.81 |                    68.29 |                 68.89 |              62.37 |                78.55 |                   21.45 |           92.29 |             44.48 |       0.018 |         nan |       nan |       33.8  |        18.71 |         46.32 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|           10 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.58 |                  65.4  |                    68.16 |                 70.46 |              66.54 |                68.82 |                   31.18 |           80.43 |             70.68 |       0.02  |         nan |       nan |        3.97 |         5.93 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO      | FRO                                  | US       |                9.66 |                  56.09 |                    68.15 |                 72.33 |              62.95 |                80.58 |                   19.42 |           91.62 |             80.62 |     nan     |         nan |       nan |      nan    |        10.88 |          7.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               19.18 |                  55.87 |                    68.13 |                 72.14 |              62.35 |                85.38 |                   14.62 |           96.26 |             67.5  |     nan     |         nan |       nan |      nan    |        11.09 |         15.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              232.03 |                  66.88 |                    68.09 |                 68.52 |              66.85 |                70.79 |                   29.21 |           75.47 |             59.58 |     nan     |         nan |       nan |      nan    |         9.13 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              111.43 |                  61.53 |                    67.53 |                 69.47 |              64.67 |                76.36 |                   23.64 |           81.55 |             66.23 |     nan     |         nan |       nan |      nan    |         9.54 |         13.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.19 |                  69.38 |                    67.29 |                 66.05 |              69.11 |                68    |                   32    |           58.88 |            nan    |       0.232 |         nan |       nan |        1.54 |       nan    |          2.97 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | MOMO     | Hello Group Inc.                     | OTHER    |                0.62 |                  78.36 |                    67.28 |                 63.97 |              71.03 |                67.3  |                   32.7  |           59.47 |             24.99 |       0.838 |         nan |       nan |       -5.96 |         4.82 |          4.94 |        0.89 |                 nan |              nan |                   9 |                  0.47 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.03 |                  76.12 |                    75.75 |                 77.25 |              76.32 |                86.87 |                   13.13 |           84.64 |             58.72 |       0.865 |         nan |       nan |      nan    |       -78.75 |          2.11 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.57 |                  65.67 |                    72.64 |                 75.9  |              69.44 |                85.41 |                   14.59 |           93.42 |             67.86 |       0.15  |         nan |       nan |        0.87 |         5.37 |          5.2  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              232.89 |                  59.16 |                    71.54 |                 75.47 |              66.73 |                88.12 |                   11.88 |           92.89 |             82.71 |     nan     |         nan |       nan |      nan    |         9.31 |         10.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.03 |                  58.15 |                    70.41 |                 74.55 |              64.94 |                85.01 |                   14.99 |           95.9  |             77.68 |     nan     |         nan |       nan |      nan    |         9.59 |          6.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.15 |                  59.41 |                    70.2  |                 73.84 |              65.85 |                82.11 |                   17.89 |           89.36 |             82.96 |     nan     |         nan |       nan |      nan    |        10.46 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NVDA     | NVIDIA Corporation                   | US       |             4782.81 |                  60.87 |                    70.88 |                 72.93 |              65.91 |                77.63 |                   22.37 |           86.9  |             81.12 |       0.008 |         nan |       nan |       27.11 |        14.5  |         28.75 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                                  | US       |                9.66 |                  56.09 |                    68.15 |                 72.33 |              62.95 |                80.58 |                   19.42 |           91.62 |             80.62 |     nan     |         nan |       nan |      nan    |        10.88 |          7.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               19.18 |                  55.87 |                    68.13 |                 72.14 |              62.35 |                85.38 |                   14.62 |           96.26 |             67.5  |     nan     |         nan |       nan |      nan    |        11.09 |         15.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.77 |                  75.31 |                    71.49 |                 71.93 |              74.02 |                65.28 |                   34.72 |           64.7  |             80.5  |       0.143 |         nan |       nan |        1.79 |         4.66 |          4.73 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM       | SM                                   | US       |                7.2  |                  63.14 |                    69.44 |                 71.89 |              66.53 |                72.56 |                   27.44 |           82.34 |             80.07 |     nan     |         nan |       nan |      nan    |         4.4  |          6.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.58 |                  65.4  |                    68.16 |                 70.46 |              66.54 |                68.82 |                   31.18 |           80.43 |             70.68 |       0.02  |         nan |       nan |        3.97 |         5.93 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | MPC      | MPC                                  | US       |               98.43 |                  50.64 |                    65.12 |                 69.73 |              60.27 |                82.56 |                   17.44 |           84.52 |             89.5  |     nan     |         nan |       nan |      nan    |         9.25 |         13.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | EMBC     | Embecta Corp.                        | US       |                0.26 |                  73.36 |                    69.65 |                 69.66 |              70.72 |                63.64 |                   36.36 |           69.73 |             64.44 |       0.46  |         nan |       nan |        5.64 |         3.01 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | STNE     | StoneCo Ltd.                         | OTHER    |                1.95 |                  75    |                    70.46 |                 69.6  |              69.15 |                66.06 |                   33.94 |           84.18 |             32.63 |       0.616 |         nan |       nan |        1.62 |         4.26 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                  | US       |              111.43 |                  61.53 |                    67.53 |                 69.47 |              64.67 |                76.36 |                   23.64 |           81.55 |             66.23 |     nan     |         nan |       nan |      nan    |         9.54 |         13.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                                   | US       |             1027.06 |                  48.4  |                    63.84 |                 69.42 |              56.87 |                77.21 |                   22.79 |           95.5  |             81.25 |     nan     |         nan |       nan |      nan    |         6.57 |         23.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.77 |                  74.83 |                    69.12 |                 69.37 |              70.55 |                68.18 |                   31.82 |           75.5  |             43.97 |       0.608 |         nan |       nan |        4.33 |      -134.67 |          2.32 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BEN      | BEN                                  | US       |               14.89 |                  55.38 |                    65.85 |                 69.26 |              61.41 |                79.57 |                   20.43 |           86.35 |             72.07 |     nan     |         nan |       nan |      nan    |        10.58 |         22.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1508.05 |                  60.81 |                    68.29 |                 68.89 |              62.37 |                78.55 |                   21.45 |           92.29 |             44.48 |       0.018 |         nan |       nan |       33.8  |        18.71 |         46.32 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PSX      | PSX                                  | US       |               91.42 |                  52.42 |                    64.96 |                 68.86 |              61.03 |                80.66 |                   19.34 |           80.08 |             87.69 |     nan     |         nan |       nan |      nan    |        10.51 |         14.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | MPC      | MPC                                  | US       |               98.43 |                     0.05 |     0.01 |      0.12 |                  65.22 |                        85.12 |         86.33 |         90.02 |          87.76 |        82.57 |           84.52 |             89.5  |         4.19 |
|               2 | PSX      | PSX                                  | US       |               91.42 |                     0.05 |     0.02 |      0.08 |                  59.59 |                        81.8  |         84.06 |         87.37 |          84.14 |        78.67 |           80.08 |             87.69 |         3.73 |
|               3 | DHT      | DHT                                  | US       |                3.15 |                     0.04 |     0.01 |      0.13 |                  54.65 |                        81.64 |         86.25 |         82.2  |          82.65 |        81.15 |           89.36 |             82.96 |         4.57 |
|               4 | AVAH     | AVAH                                 | US       |                2.56 |                     0.07 |    -0.07 |      0.02 |                  83.48 |                        79.41 |         68.54 |         80.08 |          78.11 |        72.74 |           92.36 |             55.88 |         7.78 |
|               5 | SHELL.AS | SHELL.AS                             | EUROPE   |              232.89 |                     0.04 |    -0.03 |      0.03 |                  71.63 |                        78.03 |         72.6  |         72.21 |          73.7  |        80.36 |           92.89 |             82.71 |         2.39 |
|               6 | DAR      | DAR                                  | US       |                8.7  |                     0.07 |    -0.03 |     -0.04 |                  71.74 |                        77.5  |         56.76 |         71.32 |          79.44 |        83.19 |           90.78 |             86.13 |         4.59 |
|               7 | ARGX.BR  | ARGX.BR                              | EUROPE   |               53.98 |                     0.05 |     0    |      0    |                  66.84 |                        75.81 |         68.21 |         71.5  |          70.58 |        62.48 |           93.1  |             76.08 |         6.13 |
|               8 | EQNR     | EQNR                                 | US       |               87.76 |                     0.07 |    -0.05 |     -0.01 |                  74.19 |                        75.36 |         61.32 |         73.2  |          73.71 |        75.15 |           75    |             84.17 |         5.54 |
|               9 | APA      | APA                                  | US       |               13.37 |                     0.08 |    -0.03 |      0.01 |                  65.78 |                        74.87 |         68.22 |         75.06 |          75.91 |        78.1  |           76.91 |             80.63 |         5.93 |
|              10 | WDAY     | WDAY                                 | US       |               40.29 |                     0.07 |    -0.01 |     -0.04 |                  63.44 |                        74.81 |         57.46 |         75.91 |          68.64 |        64.53 |           76.18 |             80.64 |         8.62 |
|              11 | C5H.IR   | C5H.IR                               | EUROPE   |                1.67 |                     0.05 |     0.01 |      0.1  |                  62.06 |                        74.44 |         77.36 |         66.68 |          69.49 |        74.48 |           97.77 |             45.95 |         2.71 |
|              12 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.77 |                     0.04 |    -0.02 |      0.12 |                  68.09 |                        74.25 |         78.05 |         75.08 |          71.78 |        74.16 |           64.7  |             80.5  |         3.75 |
|              13 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.58 |                     0.05 |     0    |      0.04 |                  67.85 |                        73.94 |         71.49 |         74.14 |          74.23 |        73.41 |           80.43 |             70.68 |         7.04 |
|              14 | GEN      | GEN                                  | US       |               15.2  |                     0.07 |    -0.07 |      0.01 |                  81.33 |                        72.97 |         60.53 |         72.47 |          69.12 |        70.61 |           77.77 |             59.86 |         5.75 |
|              15 | PBR      | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              115.81 |                     0.05 |    -0.02 |      0.11 |                  76.37 |                        72.89 |         76.17 |         71.18 |          68.45 |        70.79 |           64.7  |             69.41 |         4.45 |
|              16 | CIRSA.MC | CIRSA.MC                             | EUROPE   |                3.26 |                     0.02 |    -0    |      0.38 |                  48.93 |                        72.88 |         81.4  |         78.44 |          68.08 |        67.28 |           80.02 |             58.94 |         5.5  |
|              17 | OSCR     | OSCR                                 | US       |                8.41 |                     0.07 |    -0.07 |     -0.02 |                  80.48 |                        71.28 |         55.14 |         71.01 |          73.55 |        61.76 |           54.27 |             85.66 |         8.24 |
|              18 | FSM      | FSM                                  | US       |                3.03 |                     0.08 |     0.01 |     -0.03 |                  50.88 |                        71.23 |         61.45 |         73.91 |          77.19 |        80.35 |           79.81 |             71.23 |         7.3  |
|              19 | PANW     | PANW                                 | US       |              264.9  |                     0.03 |    -0.01 |      0.04 |                  56.42 |                        70.99 |         75.15 |         79.03 |          70.63 |        51.37 |           50.08 |             86.68 |         7.6  |
|              20 | MT.AS    | MT.AS                                | EUROPE   |               47.3  |                     0.07 |     0    |      0    |                  61.23 |                        70.79 |         61.9  |         71.27 |          76.19 |        73.69 |           69.27 |             80.78 |         5.02 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |               347.1 |             40.64 |         37.97 |         34.67 |          43.32 |        50.35 |           77.39 |             45.39 |                26 |          8.5 |              89.8 | long               |               -1.05 |                  0.13 |                  0.3 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     19 | P        | P                      | US       |               32.99 |             77.69 |         87.84 |         83.59 |          71.79 |        58.63 |           71.62 |             86.25 |             11.07 |         8.2  |             72.68 | short              |                6.77 |                  3.02 |                 2.38 |
|    309 | VZLA     | VZLA                   | US       |                1.26 |             57.93 |         69.84 |         60.35 |          55.52 |        53.93 |           60.56 |            nan    |             41.8  |         8.42 |             61.82 | short              |               -0.39 |                  2.99 |                 2.58 |
|    411 | 0QXR.IL  | 0QXR.IL                | OTHER    |               25.94 |             54.11 |         56.1  |         43.41 |          52.12 |        64.14 |           80    |            nan    |             57.14 |         9.15 |             61.02 | long               |               14.8  |                  2.94 |                 2.8  |
|    413 | ABSI     | ABSI                   | US       |                1.47 |             53.99 |         65.86 |         58.39 |          49.59 |        30.62 |            3.96 |             39.58 |             22.22 |         9.23 |             69.27 | short              |               -3.1  |                  2.83 |                 2.4  |
|    643 | TV       | Grupo Televisa, S.A.B. | OTHER    |                1.18 |             40.95 |         45.05 |         29.29 |          36.84 |        47.88 |           46.77 |             26.45 |             68.89 |         6.7  |             81.56 | long               |                8.48 |                  2.83 |                 2.54 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    394 | CRM      | CRM     | US       |              169.49 |             54.74 |         65.11 |         60.1  |          47.46 |        49.39 |           66.1  |             15.2  |             31.75 |         7.96 |             69.27 | short              |              -15.5  |                 -3.06 |                -2.3  |
|    184 | CXW      | CXW     | US       |                2.79 |             63.2  |         48.3  |         64.02 |          69.42 |        62.38 |           57.76 |             67.43 |             52.31 |         5.33 |             72.34 | medium             |              -11.48 |                 -2.81 |                -2.57 |
|    598 | EGY      | EGY     | US       |                0.55 |             44.4  |         53.48 |         46.37 |          42.43 |        40.05 |           36.42 |             30.9  |             22.92 |         5.65 |             69.68 | short              |               -3.03 |                 -2.64 |                -2.06 |
|    610 | 0P6O.IL  | 0P6O.IL | OTHER    |               41.8  |             43.61 |         47.42 |         35.05 |          39.79 |        64.44 |          nan    |            nan    |             85.71 |         5.41 |             60    | long               |               -3.57 |                 -2.62 |                -2.27 |
|    206 | BP       | BP      | US       |               96.83 |             62.1  |         52.55 |         58.37 |          65.82 |        74.94 |           86.53 |             64.98 |             66.04 |         4.52 |             72.34 | long               |               -3.78 |                 -2.6  |                -2.39 |

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
- Excluded by hard/data filters: **283**
- Event watch (otherwise eligible): **1**
- Final eligible: **716**
- Eligible change vs previous stored run: **+4**

Top exclusion categories:
- liquidity: 227
- price: 177
- market_cap: 150
- price_history: 18
- data_confidence: 10
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 1 |  | 2 | main,pullback |
| PSX | 4 |  | 2 |  | 2 | main,pullback |
| DHT | 8 |  | 3 |  | 2 | main,pullback |
| DDI | 35 | 2 |  | 2 | 1 | value,quality_value |
| PBR-A | 38 | 4 | 12 | 4 | 1 | value,quality_value |
| PARR | 41 | 10 | 13 | 5 | 1 | value,quality_value |
| NVDA | 63 | 5 |  | 3 | 1 | value,quality_value |
| BION.SW | 200 | 1 | 92 | 1 | 1 | value,quality_value |
| EMBC | 207 | 7 | 79 | 6 | 1 | value,quality_value |
| NWL.MI | 212 | 8 |  | 8 | 1 | value,quality_value |
| AVGO | 312 | 9 |  | 9 | 1 | value,quality_value |
| STNE | 560 | 6 | 141 | 7 | 1 | value,quality_value |
| BBWI | 659 | 3 |  | 10 | 1 | value,quality_value |
| VLO | 2 |  |  |  | 1 | main |
| FRO | 3 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **6** (FRO, DELL, HSHP, CMBT.BR, HPE, MU)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (SHELL.AS)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 72.34 | 76.12 | 54.26 | 84.64 | 58.72 | 86.87 | 62.41 |
| 2 | PBR-A | value+pullback | 70.43 | 75.31 | 68.09 | 64.70 | 80.50 | 65.28 | 74.62 |
| 3 | STNE | value+pullback | 69.59 | 75.00 | 71.94 | 84.18 | 32.63 | 66.06 | 47.57 |
| 4 | PARR | value+pullback | 69.48 | 65.40 | 67.85 | 80.43 | 70.68 | 68.82 | 73.78 |
| 5 | PBR | value+pullback | 67.54 | 64.33 | 76.37 | 64.70 | 69.41 | 62.50 | 70.99 |
| 6 | 0Q2N.IL | value+pullback | 66.26 | 69.38 | 72.05 | 58.88 |  | 68.00 | 62.31 |
| 7 | VOLV-B.ST | value+pullback | 65.87 | 74.09 | 73.02 | 55.24 | 53.88 | 58.56 | 54.05 |
| 8 | RCI | value+pullback | 64.36 | 61.73 | 69.68 | 84.40 | 42.98 | 57.33 | 45.06 |
| 9 | AMCX | value+pullback | 64.36 | 64.18 | 69.62 | 47.83 | 66.94 | 69.17 | 64.85 |
| 10 | EMBC | value+pullback | 63.68 | 73.36 | 48.18 | 69.73 | 64.44 | 63.64 | 62.10 |
| 11 | BCE | value+pullback | 63.36 | 57.11 | 79.04 | 68.54 | 57.95 | 51.94 | 44.20 |
| 12 | JD | value+pullback | 62.82 | 68.72 | 60.81 | 65.87 | 46.89 | 62.14 | 45.21 |
| 13 | GSL | value+pullback | 62.61 | 68.96 | 48.55 | 76.18 | 30.76 | 76.43 | 66.31 |
| 14 | BHF | value+pullback | 62.07 | 71.26 | 56.44 | 51.80 | 55.71 | 66.22 | 42.51 |
| 15 | GNW | value+pullback | 61.83 | 60.05 | 85.76 | 26.13 | 85.48 | 49.56 | 57.56 |
| 16 | UNIT | value+pullback | 61.81 | 80.01 | 64.97 | 64.98 | 29.23 | 44.46 | 42.13 |
| 17 | MFA | value+pullback | 61.03 | 58.14 | 70.64 | 76.63 | 26.36 | 58.97 | 41.39 |
| 18 | ORC | value+pullback | 59.82 | 60.76 | 58.92 | 75.90 | 35.27 | 59.74 | 40.19 |
| 19 | WB | value+pullback | 59.29 | 68.55 | 65.43 | 63.60 | 17.46 | 55.41 | 40.43 |
| 20 | AF.PA | value+pullback | 57.79 | 67.45 | 66.87 | 46.58 | 59.38 | 39.55 | 49.66 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 10/10 | 9/10 | 0/10 | 73.1 | 4 / 6 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 72.3 | 8 / 17 |
| Top 50 | 49/50 | 47/50 | 48/50 | 44/50 | 0/50 | 72.5 | 24 / 26 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=1, mid_5_20b=2, large_20_100b=4, mega_100b_plus=2
