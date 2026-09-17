# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-17

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

- **EUROPE:** 80.9/100
- **OTHER:** 70.7/100
- **US:** 78.6/100

## Main multi-horizon ranking

|   rank | symbol   | name                             | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | CMBT.BR  | CMBT.BR                          | EUROPE   |                5.08 |             86.68 |         87.04 |         87.24 |          86.33 |        84.98 |           94.99 |             74.51 |             69.47 |         3.96 |             73.14 | swing              |                4.97 |                  2.66 |                 1.88 |
|      2 | FRO      | FRO                              | US       |               10.36 |             86.39 |         87.94 |         87.79 |          84.99 |        80.93 |           92.19 |             77.26 |             56.84 |         5.65 |             73.14 | short              |                0.8  |                  1.65 |                 1.17 |
|      3 | VLO      | VLO                              | US       |              100.64 |             86.02 |         86.35 |         89.83 |          85.69 |        80.5  |           86.92 |             80.98 |             59.67 |         3.46 |             69.68 | swing              |                0.27 |                  0.3  |               nan    |
|      4 | DHT      | DHT                              | US       |                3.22 |             85.43 |         87.72 |         86.89 |          83.97 |        81.55 |           90.48 |             80.2  |             61.89 |         4.79 |             73.14 | short              |                1.86 |                  1.81 |                 0.95 |
|      5 | DELL     | DELL                             | US       |              310.42 |             83.46 |         91.2  |         86.62 |          80.3  |        68.59 |           74.67 |             79.78 |             34    |         7.92 |             72.23 | short              |                1.37 |                  0.69 |                -0.29 |
|      6 | SM       | SM                               | US       |                7.87 |             83.33 |         81.23 |         83.5  |          83.17 |        86.55 |           82.91 |             79.77 |             96.05 |         7.22 |             72.11 | long               |               -3.73 |                  0.13 |                -0.77 |
|      7 | AVAH     | AVAH                             | US       |                2.7  |             82.94 |         86.99 |         85.58 |          80.3  |        74.62 |           94.39 |             65.23 |             38.4  |         7.86 |             72.11 | short              |               -0.02 |                  1.9  |                 1.45 |
|      8 | NAT      | NAT                              | US       |                1.47 |             82.1  |         87.07 |         84.52 |          79.69 |        73.42 |           88.19 |             66.9  |             39.12 |         5.08 |             73.14 | short              |                0.44 |                  1.24 |                 0.76 |
|      9 | DINO     | DINO                             | US       |               17.56 |             81.61 |         83.92 |         88.87 |          79.29 |        70.11 |           51.08 |             85.43 |             72.35 |         4.5  |             73.14 | swing              |                0.42 |                  0.46 |                -0.24 |
|     10 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.69 |             79.98 |         80.69 |         83.49 |          79.28 |        73.42 |           73.32 |             75.77 |             57.68 |         7.15 |             84.98 | swing              |                0.26 |                  0.19 |                -0.6  |
|     11 | SHELL.AS | SHELL.AS                         | EUROPE   |              239.55 |             79.38 |         80.75 |         78    |          77.11 |        83.27 |           91.82 |             82.15 |             74.49 |         2.44 |             73.14 | long               |               -1.02 |                  0.57 |                -0.15 |
|     12 | SB       | SB                               | US       |                0.77 |             79.37 |         84.27 |         81.01 |          77.74 |        73.86 |           69.98 |             73.7  |             66.74 |         4.37 |             68.89 | short              |                3.18 |                  1.76 |                 1.1  |
|     13 | PBF      | PBF                              | US       |                7.8  |             79.19 |         74.16 |         85.66 |          81.56 |        76.82 |           53.52 |             86.39 |             92.12 |         7.85 |             72.68 | swing              |                0.11 |                 -0.32 |                -1.16 |
|     14 | AMC      | AMC                              | US       |                2.06 |             79.08 |         78.77 |         77.43 |          79.39 |        80.07 |           87.36 |             93.47 |            nan    |         9.71 |             66.89 | long               |                0.75 |                  0.78 |                 0.34 |
|     15 | KIN.BR   | KIN.BR                           | EUROPE   |                1.32 |             78.99 |         85.7  |         82.63 |          75.35 |        66.26 |           87.58 |             63.38 |             21.48 |         3.87 |             73.14 | short              |                0.15 |                  0.17 |                 0.02 |
|     16 | TKA.DE   | TKA.DE                           | EUROPE   |                9.59 |             78.6  |         84.94 |         82.27 |          74.93 |        67.54 |          nan    |             58.05 |             57.03 |         7.32 |             70.3  | short              |                2.18 |                  1.77 |                 0.96 |
|     17 | OKTA     | OKTA                             | US       |               28.5  |             77.63 |         90.87 |         82.73 |          72.52 |        59.1  |           70.55 |             66.51 |             14.02 |         7.93 |             72.11 | short              |               -0.3  |                  0.98 |                 0.86 |
|     18 | HAFN     | HAFN                             | US       |                4.21 |             77.53 |         84.79 |         81.72 |          73.34 |        70.58 |           75.31 |             59.15 |             58.63 |         5.69 |             69.68 | short              |                0.65 |                  1.43 |               nan    |
|     19 | CXW      | CXW                              | US       |                2.99 |             77.26 |         82.26 |         80.6  |          73.92 |        64.21 |           56.69 |             77.5  |             51.2  |         5.12 |             72.34 | short              |               -0.17 |                  0.08 |                -0.46 |
|     20 | TEN      | Tsakos Energy Navigation Limited | OTHER    |                1.37 |             77.24 |         83.55 |         80.35 |          74.14 |        65.9  |           83.08 |             63.17 |             24.15 |         4.62 |             78.7  | short              |                1    |                  0.92 |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0QXR.IL  | Stellantis N.V.                      | OTHER    |               14.03 |                  82.01 |                    79.15 |                 78.68 |              79.56 |                69.75 |                   30.25 |           78.03 |            nan    |       0.461 |         nan |       nan |        1.16 |       nan    |          0.7  |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            2 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.05 |                  75.21 |                    75.3  |                 77.04 |              75.33 |                85.98 |                   14.02 |           86.96 |             57.11 |       0.855 |         nan |       nan |      nan    |       -79.66 |          2.13 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.09 |                  81.38 |                    75.08 |                 75.2  |              78.14 |                64.23 |                   35.77 |           67.84 |             79.89 |       0.142 |         nan |       nan |        1.79 |         4.7  |          4.95 |        5.46 |                 nan |              nan |                  12 |                  0.63 |
|            4 | CRM      | Salesforce, Inc.                     | US       |              178.71 |                  81.05 |                    74.11 |                 70.99 |              75.3  |                56.05 |                   43.95 |           63.27 |             68.61 |       0.086 |         nan |       nan |       18.39 |        15.64 |         23.41 |        0.87 |                 nan |              nan |                  12 |                  0.63 |
|            5 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  67.42 |                    73.45 |                 76.43 |              70.47 |                85.9  |                   14.1  |           94.01 |             64.7  |       0.154 |         nan |       nan |        0.75 |         5.22 |          5.05 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.25 |                  72.06 |                    72.22 |                 71.83 |              72.92 |                76.34 |                   23.66 |           68.7  |            nan    |       0.228 |         nan |       nan |        1.54 |       nan    |          3.03 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | SWON.SW  | SoftwareOne Holding AG               | EUROPE   |                2.08 |                  68.08 |                    72.09 |                 73.38 |              70.12 |                77.19 |                   22.81 |           81.42 |             72.07 |       0.229 |         nan |       nan |       11.86 |        10.83 |         51.08 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHEL     | SHEL                                 | US       |              237.02 |                  66.43 |                    71.25 |                 72.69 |              69.98 |                77.75 |                   22.25 |           75.57 |             81.61 |     nan     |         nan |       nan |      nan    |         9.26 |         10.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              239.55 |                  59.13 |                    71.17 |                 74.98 |              66.51 |                87.31 |                   12.69 |           91.82 |             82.15 |     nan     |         nan |       nan |      nan    |         9.61 |         10.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | BBWI     | Bath & Body Works, Inc.              | US       |                2.92 |                  77.56 |                    70.77 |                 68.02 |              70.02 |                60.33 |                   39.67 |           76.37 |             33.2  |       0.227 |         nan |       nan |        5.57 |         6    |          4.39 |        0.73 |                 nan |              nan |                  11 |                  0.58 |
|            9 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.6  |                  68.38 |                    70.72 |                 73.04 |              68.99 |                79.71 |                   20.29 |           88.79 |             54.08 |       0.177 |         nan |       nan |        4.23 |         2.78 |          5.15 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.08 |                  59.37 |                    70.39 |                 74.16 |              65.22 |                83.42 |                   16.58 |           94.99 |             74.51 |     nan     |         nan |       nan |      nan    |         9.74 |          6.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              101.3  |                  59.06 |                    69.77 |                 73.35 |              65.64 |                81.58 |                   18.42 |           87.57 |             84.3  |     nan     |         nan |       nan |      nan    |         9.32 |         22.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.22 |                  58.86 |                    69.65 |                 73.34 |              65.05 |                81.35 |                   18.65 |           90.48 |             80.2  |     nan     |         nan |       nan |      nan    |        10.93 |          7.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | STNE     | StoneCo Ltd.                         | OTHER    |                1.94 |                  72.4  |                    69.39 |                 68.77 |              67.71 |                68.59 |                   31.41 |           84.18 |             32.42 |       0.614 |         nan |       nan |        1.62 |         4.27 |          3.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | TALO     | Talos Energy Inc.                    | US       |                2.52 |                  70.62 |                    69.28 |                 70.84 |              72.05 |                75.86 |                   24.14 |           65.42 |             75.49 |       0.189 |         nan |       nan |        3.24 |        10.5  |        nan    |      nan    |                 nan |              nan |                   9 |                  0.47 |
|          nan | SM       | SM                                   | US       |                7.87 |                  62.24 |                    68.98 |                 71.59 |              65.86 |                72.6  |                   27.4  |           82.91 |             79.77 |     nan     |         nan |       nan |      nan    |         4.86 |          7.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.82 |                  72.35 |                    68.93 |                 69.35 |              69.98 |                77.39 |                   22.61 |           76.99 |             39.6  |       0.572 |         nan |       nan |        4.37 |      -142.98 |          2.46 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           13 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.42 |                  69.67 |                    68.21 |                 68.51 |              67.53 |                79.62 |                   20.38 |           82.61 |             30.41 |       0.079 |         nan |       nan |        3.9  |         5.12 |          4.45 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO      | FRO                                  | US       |               10.36 |                  56.64 |                    68.05 |                 72.06 |              62.83 |                79.56 |                   20.44 |           92.19 |             77.26 |     nan     |         nan |       nan |      nan    |        11.8  |          7.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0QXR.IL  | Stellantis N.V.                      | OTHER    |               14.03 |                  82.01 |                    79.15 |                 78.68 |              79.56 |                69.75 |                   30.25 |           78.03 |            nan    |       0.461 |         nan |       nan |        1.16 |       nan    |          0.7  |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            2 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.05 |                  75.21 |                    75.3  |                 77.04 |              75.33 |                85.98 |                   14.02 |           86.96 |             57.11 |       0.855 |         nan |       nan |      nan    |       -79.66 |          2.13 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            5 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  67.42 |                    73.45 |                 76.43 |              70.47 |                85.9  |                   14.1  |           94.01 |             64.7  |       0.154 |         nan |       nan |        0.75 |         5.22 |          5.05 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.09 |                  81.38 |                    75.08 |                 75.2  |              78.14 |                64.23 |                   35.77 |           67.84 |             79.89 |       0.142 |         nan |       nan |        1.79 |         4.7  |          4.95 |        5.46 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              239.55 |                  59.13 |                    71.17 |                 74.98 |              66.51 |                87.31 |                   12.69 |           91.82 |             82.15 |     nan     |         nan |       nan |      nan    |         9.61 |         10.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.08 |                  59.37 |                    70.39 |                 74.16 |              65.22 |                83.42 |                   16.58 |           94.99 |             74.51 |     nan     |         nan |       nan |      nan    |         9.74 |          6.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | SWON.SW  | SoftwareOne Holding AG               | EUROPE   |                2.08 |                  68.08 |                    72.09 |                 73.38 |              70.12 |                77.19 |                   22.81 |           81.42 |             72.07 |       0.229 |         nan |       nan |       11.86 |        10.83 |         51.08 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|          nan | BP       | BP                                   | US       |              101.3  |                  59.06 |                    69.77 |                 73.35 |              65.64 |                81.58 |                   18.42 |           87.57 |             84.3  |     nan     |         nan |       nan |      nan    |         9.32 |         22.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.22 |                  58.86 |                    69.65 |                 73.34 |              65.05 |                81.35 |                   18.65 |           90.48 |             80.2  |     nan     |         nan |       nan |      nan    |        10.93 |          7.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.6  |                  68.38 |                    70.72 |                 73.04 |              68.99 |                79.71 |                   20.29 |           88.79 |             54.08 |       0.177 |         nan |       nan |        4.23 |         2.78 |          5.15 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                                 | US       |              237.02 |                  66.43 |                    71.25 |                 72.69 |              69.98 |                77.75 |                   22.25 |           75.57 |             81.61 |     nan     |         nan |       nan |      nan    |         9.26 |         10.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |               10.36 |                  56.64 |                    68.05 |                 72.06 |              62.83 |                79.56 |                   20.44 |           92.19 |             77.26 |     nan     |         nan |       nan |      nan    |        11.8  |          7.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.25 |                  72.06 |                    72.22 |                 71.83 |              72.92 |                76.34 |                   23.66 |           68.7  |            nan    |       0.228 |         nan |       nan |        1.54 |       nan    |          3.03 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SM       | SM                                   | US       |                7.87 |                  62.24 |                    68.98 |                 71.59 |              65.86 |                72.6  |                   27.4  |           82.91 |             79.77 |     nan     |         nan |       nan |      nan    |         4.86 |          7.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | CRM      | Salesforce, Inc.                     | US       |              178.71 |                  81.05 |                    74.11 |                 70.99 |              75.3  |                56.05 |                   43.95 |           63.27 |             68.61 |       0.086 |         nan |       nan |       18.39 |        15.64 |         23.41 |        0.87 |                 nan |              nan |                  12 |                  0.63 |
|           11 | TALO     | Talos Energy Inc.                    | US       |                2.52 |                  70.62 |                    69.28 |                 70.84 |              72.05 |                75.86 |                   24.14 |           65.42 |             75.49 |       0.189 |         nan |       nan |        3.24 |        10.5  |        nan    |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           16 | SSL      | Sasol Limited                        | OTHER    |                7.94 |                  67.24 |                    67.76 |                 70.2  |              66.34 |                65.1  |                   34.9  |           83.45 |             62.1  |       0.004 |         nan |       nan |        1.61 |         5.13 |         13.11 |        0.07 |                 nan |              nan |                  11 |                  0.58 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               24.49 |                  55.4  |                    66.08 |                 69.65 |              60.49 |                81.35 |                   18.65 |           94.28 |             59.64 |     nan     |         nan |       nan |      nan    |        11.79 |         12.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EOG      | EOG                                  | US       |               65.89 |                  57.54 |                    66.53 |                 69.51 |              62.65 |                77.76 |                   22.24 |           84.46 |             72.24 |     nan     |         nan |       nan |      nan    |         9.84 |         11.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           18 | NVDA     | NVIDIA Corporation                   | US       |             4476.7  |                  55.37 |                    67.04 |                 69.45 |              61.14 |                74.46 |                   25.54 |           86.27 |             78.69 |       0.008 |         nan |       nan |       25.5  |        13.7  |         26.8  |        0.46 |                 nan |              nan |                  12 |                  0.63 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | SM       | SM                                   | US       |                7.87 |                     0.08 |     0    |      0.08 |                  56.57 |                        78.78 |         81.23 |         83.5  |          83.17 |        86.55 |           82.91 |             79.77 |         7.22 |
|               2 | BP       | BP                                   | US       |              101.3  |                     0.03 |    -0.01 |      0.05 |                  59.53 |                        78.11 |         78.04 |         71.32 |          72.27 |        77.94 |           87.57 |             84.3  |         4.61 |
|               3 | SSL      | Sasol Limited                        | OTHER    |                7.94 |                     0.05 |    -0.02 |      0.21 |                  76.18 |                        77.99 |         81.12 |         73.05 |          72.7  |        76.96 |           83.45 |             62.1  |         5.08 |
|               4 | SHELL.AS | SHELL.AS                             | EUROPE   |              239.55 |                     0.02 |     0.02 |      0.04 |                  43.32 |                        77.56 |         80.75 |         78    |          77.11 |        83.27 |           91.82 |             82.15 |         2.44 |
|               5 | EQNR     | EQNR                                 | US       |               90.84 |                     0.03 |    -0.02 |      0.06 |                  64.4  |                        75.51 |         75.16 |         78.36 |          75.64 |        74.22 |           75.88 |             76.6  |         5.72 |
|               6 | BE       | BE                                   | US       |               68.93 |                     0.03 |     0    |      0.29 |                  52.06 |                        75.48 |         78.17 |         63.37 |          71.59 |        62.56 |           86.51 |             75.22 |         9.24 |
|               7 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.09 |                     0.03 |    -0.01 |      0.19 |                  59.83 |                        75.2  |         81.34 |         76.19 |          71.84 |        75.63 |           67.84 |             79.89 |         3.83 |
|               8 | PBF      | PBF                                  | US       |                7.8  |                     0.03 |    -0.01 |      0.01 |                  57.73 |                        75.15 |         74.16 |         85.66 |          81.56 |        76.82 |           53.52 |             86.39 |         7.85 |
|               9 | AGRO     | AGRO                                 | US       |                1.45 |                     0.07 |    -0.07 |      0.18 |                  82.81 |                        75.11 |         74.2  |         67.59 |          67.54 |        76.18 |           67.49 |             80.6  |         7.31 |
|              10 | SBLK     | Star Bulk Carriers Corp.             | OTHER    |                3.11 |                     0.05 |    -0.01 |      0.06 |                  69.1  |                        75.07 |         75.36 |         75.18 |          75.98 |        73.36 |           87.59 |             63.38 |         4.55 |
|              11 | SWON.SW  | SoftwareOne Holding AG               | EUROPE   |                2.08 |                     0.05 |     0.01 |      0.1  |                  67.51 |                        74.61 |         74.77 |         70.35 |          68.8  |        69.64 |           81.42 |             72.07 |         6.43 |
|              12 | SHEL     | SHEL                                 | US       |              237.02 |                     0.03 |     0    |      0.04 |                  56.81 |                        74.49 |         77.23 |         73.54 |          71.49 |        77.18 |           75.57 |             81.61 |         3.08 |
|              13 | TALO     | Talos Energy Inc.                    | US       |                2.52 |                     0.05 |    -0.01 |      0.06 |                  69.02 |                        73.43 |         77.34 |         76.54 |          73.19 |        71.7  |           65.42 |             75.49 |         6.12 |
|              14 | TYRES.HE | Nokian Renkaat Oyj                   | EUROPE   |                2.19 |                     0.04 |    -0.02 |      0    |                  70.45 |                        73.29 |         59.82 |         71.63 |          71.97 |        61.83 |           80.23 |             72.41 |         6.42 |
|              15 | MUR      | MUR                                  | US       |                4.74 |                     0.05 |    -0.01 |      0.09 |                  72.7  |                        73.2  |         73.96 |         64.81 |          65.7  |        70.72 |           66.79 |             79.72 |         6.27 |
|              16 | KRX.IR   | KRX.IR                               | EUROPE   |               17.43 |                     0.08 |    -0.05 |     -0.03 |                  71.62 |                        73.17 |         52.08 |         68.53 |          71.9  |        66.87 |           94.57 |             61.67 |         5.68 |
|              17 | PBR      | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              116.79 |                     0.04 |    -0    |      0.18 |                  61.52 |                        73.01 |         80.54 |         71.74 |          67.02 |        69.28 |           67.84 |             66.3  |         4.52 |
|              18 | KOS      | KOS                                  | US       |                1.48 |                     0.07 |     0    |      0.05 |                  60.81 |                        72.94 |         71.24 |         73.56 |          75.14 |        74.76 |           65.78 |             92.6  |         8.81 |
|              19 | PR       | Permian Resources Corporation        | US       |               16.66 |                     0.06 |    -0.02 |      0.03 |                  76.18 |                        72.94 |         68.23 |         71.28 |          70.65 |        68.31 |           75.66 |             71.62 |         4.85 |
|              20 | HPE      | HPE                                  | US       |               65.21 |                     0.09 |    -0.04 |      0.02 |                  61.94 |                        72.9  |         70.41 |         76.33 |          78.79 |        71.94 |           73.6  |             71.5  |         7.09 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              343.53 |                40 |         36.96 |         33.45 |          43.04 |        50.25 |           77.39 |             45.44 |                26 |         3.36 |             89.74 | long               |               -1.33 |                 -0.06 |                 0.15 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name            | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     46 | PANW     | PANW            | US       |              266.33 |             72.82 |         75.57 |         78.57 |          70.07 |        50.8  |           49.31 |             83.08 |              6.82 |         7.69 |             73.14 | swing              |                3.14 |                  4.55 |                 3.92 |
|     22 | RBRK     | RBRK            | US       |               18.73 |             76.41 |         85    |         83.48 |          69.33 |        51.18 |           55.09 |             88.06 |              4    |         8.75 |             72.23 | short              |                0.98 |                  3.94 |                 3.27 |
|    410 | AMP.MI   | Amplifon S.p.A. | EUROPE   |                3.06 |             54.67 |         48.64 |         56.03 |          54.29 |        55.06 |           56.52 |             43.87 |             68.93 |         6.55 |             85.82 | swing              |               13.54 |                  3.3  |               nan    |
|     35 | NTSK     | NTSK            | US       |                6.12 |             74.49 |         89.61 |         83.5  |          65.48 |        45.35 |           51.38 |             84.68 |              1.98 |         9.34 |             64.96 | short              |                0.21 |                  3.24 |                 2.12 |
|    132 | FTRE     | FTRE            | US       |                1.65 |             65.73 |         78.22 |         71.86 |          59.59 |        44.52 |           21.91 |             58.09 |             39.2  |         8.12 |             73.14 | short              |                1.92 |                  3.16 |                 2.66 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    608 | AMV0.DE  | Aumovio SE                   | EUROPE   |                3.73 |             44.55 |         51.81 |         36.5  |          39.81 |        49.3  |           49.23 |             28.77 |             73.41 |         6.36 |             82.99 | short              |              -15.71 |                 -4.39 |                -4.13 |
|    648 | 0QXR.IL  | Stellantis N.V.              | OTHER    |               14.03 |             39.4  |         22.11 |         29.1  |          49.7  |        70.43 |           78.03 |            nan    |             90.85 |         9.15 |             69.59 | long               |               -0.81 |                 -3.89 |                -3.22 |
|    574 | APH      | APH                          | US       |              165.13 |             46.94 |         42.58 |         42.86 |          51.01 |        53.82 |           80.91 |             27.72 |             19.99 |         6.17 |             73.14 | long               |               -2.11 |                 -3.64 |               nan    |
|    316 | HMY      | HMY                          | US       |               10.41 |             58.03 |         50.73 |         53.34 |          62.71 |        73.81 |           84.36 |             32.06 |             84.34 |         8.24 |             73.14 | long               |               -1.43 |                 -3.46 |               nan    |
|    616 | PAH3.DE  | Porsche Automobil Holding SE | EUROPE   |                8.93 |             44.2  |         62.75 |         44.34 |          40.66 |        44.05 |           34.78 |             59.2  |             59.82 |         5.38 |             75.77 | short              |              -11.46 |                 -3.28 |                -3.11 |

## Duplicate-security checks

- SDLFL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)
- VTYL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
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
- Excluded by hard/data filters: **293**
- Event watch (otherwise eligible): **1**
- Final eligible: **706**
- Eligible change vs previous stored run: **-7**

Top exclusion categories:
- liquidity: 235
- price: 179
- market_cap: 157
- price_history: 23
- data_confidence: 14
- duplicate_listing: 4
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PBR-A | 23 | 3 | 7 | 4 | 2 | value,pullback,quality_value |
| SM | 6 |  | 1 |  | 2 | main,pullback |
| SSL | 31 | 16 | 3 | 10 | 1 | pullback,quality_value |
| CRM | 74 | 4 |  | 8 | 1 | value,quality_value |
| SWON.SW | 75 | 7 | 11 | 5 | 1 | value,quality_value |
| DDI | 87 | 5 | 47 | 3 | 1 | value,quality_value |
| 0Q2N.IL | 89 | 6 |  | 7 | 1 | value,quality_value |
| BION.SW | 106 | 2 | 63 | 2 | 1 | value,quality_value |
| IRWD | 137 | 9 |  | 6 | 1 | value,quality_value |
| 0QXR.IL | 648 | 1 |  | 1 | 1 | value,quality_value |
| CMBT.BR | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| VLO | 3 |  |  |  | 1 | main |
| DHT | 4 |  |  |  | 1 | main |
| DELL | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (CMBT.BR, FRO, VLO, DHT, DELL, NAT, DINO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **4** (BP, SHELL.AS, BE, AGRO)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 73.30 | 75.21 | 59.14 | 86.96 | 57.11 | 85.98 | 67.27 |
| 2 | SWON.SW | value+pullback | 72.16 | 68.08 | 67.51 | 81.42 | 72.07 | 77.19 | 69.99 |
| 3 | 0Q2N.IL | value+pullback | 71.78 | 72.06 | 78.37 | 68.70 |  | 76.34 | 68.66 |
| 4 | TALO | value+pullback | 70.97 | 70.62 | 69.02 | 65.42 | 75.49 | 75.86 | 74.86 |
| 5 | SSL | value+pullback | 70.97 | 67.24 | 76.18 | 83.45 | 62.10 | 65.10 | 75.00 |
| 6 | NVDA | value+pullback | 70.74 | 55.37 | 73.72 | 86.27 | 78.69 | 74.46 | 64.23 |
| 7 | PBR-A | value+pullback | 70.38 | 81.38 | 59.83 | 67.84 | 79.89 | 64.23 | 75.91 |
| 8 | DDI | value+pullback | 69.98 | 67.42 | 48.01 | 94.01 | 64.70 | 85.90 | 68.83 |
| 9 | SDF.DE | value+pullback | 69.89 | 64.73 | 76.08 | 87.81 | 39.31 | 71.76 | 66.20 |
| 10 | ETG | value+pullback | 69.54 | 55.84 | 74.90 | 68.49 | 81.91 | 77.98 | 57.38 |
| 11 | AVGO | value+pullback | 69.34 | 59.34 | 71.42 | 93.10 | 43.55 | 76.83 | 47.12 |
| 12 | STNE | value+pullback | 68.57 | 72.40 | 69.05 | 84.18 | 32.42 | 68.59 | 48.79 |
| 13 | 0P6O.IL | value+pullback | 66.49 | 64.38 | 65.79 | 77.88 |  | 70.23 | 56.73 |
| 14 | APA | value+pullback | 65.25 | 65.34 | 71.00 | 62.14 | 61.98 | 61.89 | 70.69 |
| 15 | GSL | value+pullback | 64.17 | 69.67 | 47.67 | 82.61 | 30.41 | 79.62 | 69.22 |
| 16 | UNIT | value+pullback | 63.57 | 80.01 | 72.06 | 65.23 | 29.20 | 44.25 | 39.85 |
| 17 | AVK | value+pullback | 63.25 | 55.60 | 79.07 | 63.12 |  | 61.69 | 44.57 |
| 18 | PBR | value+pullback | 63.02 | 62.12 | 61.52 | 67.84 | 66.30 | 61.01 | 70.51 |
| 19 | BHF | value+pullback | 62.32 | 72.83 | 56.96 | 52.45 | 52.28 | 65.66 | 39.91 |
| 20 | SYENS.BR | value+pullback | 62.14 | 56.55 | 78.43 | 63.24 | 44.78 | 58.02 | 59.47 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 73.1 | 3 / 7 |
| Top 25 | 24/25 | 25/25 | 24/25 | 23/25 | 0/25 | 72.3 | 7 / 18 |
| Top 50 | 49/50 | 50/50 | 49/50 | 48/50 | 0/50 | 72.5 | 16 / 34 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=4, mega_100b_plus=2
