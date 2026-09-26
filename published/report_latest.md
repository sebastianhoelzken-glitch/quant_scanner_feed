# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-26

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

- **EUROPE:** 77.7/100
- **OTHER:** 68.5/100
- **US:** 82.8/100

## Main multi-horizon ranking

|   rank | symbol    | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE       | HPE                          | US       |               73.45 |             84    |         89.51 |         86.91 |          81.08 |        72.09 |           70.78 |             80.79 |             53.06 |         6.89 |             72.34 | short              |                2.64 |                  0.84 |               nan    |
|      2 | DELL      | DELL                         | US       |              314.64 |             83.64 |         86.33 |         86.51 |          80.94 |        68.49 |           71.67 |             85.82 |             35.06 |         7.82 |             72.23 | swing              |                0.02 |                  0.28 |                 0.06 |
|      3 | CMBT.BR   | CMBT.BR                      | EUROPE   |                4.88 |             82.91 |         74.95 |         82.21 |          84.85 |        83.61 |           95.66 |             76.73 |             67.16 |         3.67 |             73.14 | medium             |               -1.27 |                  1.35 |                 1.27 |
|      4 | MU        | MU                           | US       |             1074.59 |             82.87 |         80.11 |         72.93 |          85.84 |        85.63 |           95.1  |             80.96 |             74.13 |         8.1  |             73.14 | medium             |                2.1  |                  2.79 |                 2.15 |
|      5 | VLO       | VLO                          | US       |               98.01 |             82.66 |         79.63 |         86.12 |          84.51 |        80.81 |           85.04 |             80.98 |             64.62 |         3.56 |             69.68 | swing              |               -3.09 |                  1.07 |                 0.98 |
|      6 | FRO       | FRO                          | US       |                9.34 |             81.88 |         80.09 |         82.74 |          82.63 |        81.12 |           90.5  |             68.39 |             64.69 |         5.02 |             73.14 | swing              |               -3.04 |                  0.5  |                 0.46 |
|      7 | AMC       | AMC                          | US       |                2.31 |             81.2  |         81.96 |         86.3  |          80.43 |        79.82 |           86.21 |             78.78 |            nan    |         9.48 |             65.07 | swing              |                5    |                  4.46 |                 4.12 |
|      8 | P         | P                            | US       |               36.91 |             80.9  |         94.28 |         88.67 |          73.13 |        59.07 |           68.47 |             91.15 |             13.45 |         8.14 |             72.68 | short              |                3.53 |                  3.25 |                 2.37 |
|      9 | PSX       | PSX                          | US       |               89.72 |             80.44 |         75.24 |         84.72 |          82.2  |        78.67 |           78.2  |             85.48 |             65.95 |         3.81 |             73.14 | swing              |               -3.42 |                  1.07 |                 1.14 |
|     10 | NAT       | NAT                          | US       |                1.44 |             79.56 |         80.33 |         80.78 |          78.79 |        73.63 |           86.52 |             69.25 |             42.38 |         4.61 |             73.14 | swing              |               -1    |                  0.3  |                 0.29 |
|     11 | DHT       | DHT                          | US       |                3.09 |             79.54 |         77.84 |         79.61 |          79.48 |        80.68 |           87.98 |             69.92 |             68.43 |         4.45 |             73.14 | long               |               -2.52 |                  0.63 |                 0.36 |
|     12 | SMTC      | SMTC                         | US       |               14.96 |             79.27 |         84.92 |         82.31 |          76.23 |        62.14 |           72.18 |             84.15 |             14.77 |         8.45 |             73.14 | short              |                8.43 |                  0.82 |               nan    |
|     13 | OKTA      | OKTA                         | US       |               30    |             77.85 |         86.13 |         81.8  |          73.9  |        60.4  |           70.32 |             69.52 |             16.58 |         7.85 |             71.77 | short              |               -0.68 |                  0.82 |                 0.84 |
|     14 | REP.MC    | REP.MC                       | EUROPE   |               32.76 |             77.77 |         83.59 |         80.79 |          74.76 |        71.31 |           57.82 |             81.9  |             75.25 |         3.81 |             73.14 | short              |                3.12 |                  1.71 |                 1.37 |
|     15 | SHELL.AS  | SHELL.AS                     | EUROPE   |              239.93 |             77.7  |         81.21 |         75.36 |          73.62 |        80.05 |           92.42 |             78.88 |             68.06 |         2.44 |             73.14 | short              |                3.55 |                  2.73 |                 2.57 |
|     16 | KIN.BR    | KIN.BR                       | EUROPE   |                1.35 |             77.09 |         79.95 |         80.44 |          74.23 |        64.85 |           88.28 |             64.85 |             18.21 |         3.67 |             73.14 | swing              |               -0.66 |                 -0.32 |                -0.25 |
|     17 | BIRG.IR   | BIRG.IR                      | EUROPE   |               18.96 |             76.64 |         78.27 |         74.93 |          75.54 |        77.74 |           96.3  |             66.46 |             59.9  |         2.19 |             73.14 | short              |                0.91 |                  1.98 |                 1.68 |
|     18 | SHEL      | SHEL                         | US       |              240.17 |             75.87 |         78.26 |         75.2  |          70.78 |        76.53 |           72.57 |             79.2  |             81.26 |         2.95 |             72.8  | short              |               10.76 |                  3.28 |                 2.58 |
|     19 | SSABBH.HE | SSABBH.HE                    | EUROPE   |                9.22 |             74.71 |         57.43 |         70.62 |          78.8  |        81.66 |           69.8  |            nan    |             99.84 |         4.25 |             62.84 | long               |               -0.47 |                nan    |               nan    |
|     20 | AMD       | Advanced Micro Devices, Inc. | US       |              905.06 |             74.31 |         77.27 |         76.08 |          72.54 |        60.55 |           67.56 |             71.67 |             22.23 |         7.4  |             89.16 | short              |                2.19 |                  1.39 |                 0.4  |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                2.98 |                  73.97 |                    74.45 |                 76.12 |              74.65 |                86.7  |                   13.3  |           84.64 |             57.81 |       0.877 |         nan |       nan |      nan    |       -77.69 |          2.08 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | BBWI     | Bath & Body Works, Inc.              | US       |                2.92 |                  82.54 |                    71.46 |                 67.63 |              72.25 |                52.58 |                   47.42 |           70.25 |             33.57 |       0.231 |         nan |       nan |        5.52 |         5.9  |          4.32 |        0.68 |                 nan |              nan |                  11 |                  0.58 |
|            3 | NVDA     | NVIDIA Corporation                   | US       |             4777.92 |                  61.64 |                    70.87 |                 72.66 |              66.07 |                76.98 |                   23.02 |           86.5  |             78.34 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.45 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL     | SHEL                                 | US       |              240.17 |                  66.68 |                    70.36 |                 71.39 |              69.56 |                75.73 |                   24.27 |           72.57 |             79.2  |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              239.93 |                  58.17 |                    70.24 |                 74.1  |              65.35 |                86.55 |                   13.45 |           92.42 |             78.88 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.41 |                  68.48 |                    69.71 |                 71.65 |              68.61 |                68.59 |                   31.41 |           80.43 |             69.54 |       0.021 |         nan |       nan |        3.8  |         5.6  |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.88 |                  57.16 |                    69.7  |                 73.9  |              64.14 |                85.06 |                   14.94 |           95.66 |             76.73 |     nan     |         nan |       nan |      nan    |         9.23 |          6.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.09 |                  63.86 |                    69.63 |                 71.91 |              66.97 |                72.05 |                   27.95 |           81.35 |             80.16 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.72 |                  74.83 |                    69.09 |                 69.3  |              70.53 |                68.5  |                   31.5  |           75.5  |             43.21 |       0.643 |         nan |       nan |        4.54 |      -125.84 |          2.17 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | INVA     | Innoviva, Inc.                       | US       |                1.32 |                  64.71 |                    69.05 |                 71.47 |              66.44 |                82.36 |                   17.64 |           89.82 |             50.25 |       0.074 |         nan |       nan |        6.4  |         9.38 |          4.81 |        0.25 |                 nan |              nan |                  10 |                  0.53 |
|            7 | EMBC     | Embecta Corp.                        | US       |                0.29 |                  72.47 |                    69.03 |                 69.16 |              69.82 |                62.5  |                   37.5  |           70.34 |             63.92 |       0.413 |         nan |       nan |        5.76 |         3.35 |          4.01 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.47 |                  79.55 |                    69.02 |                 67.19 |              74.38 |                50.88 |                   49.12 |           47.39 |             79.45 |       0.143 |         nan |       nan |        1.78 |         4.61 |          4.68 |        5.44 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                                  | US       |                3.09 |                  60.96 |                    68.78 |                 71.54 |              64.83 |                77.48 |                   22.52 |           87.98 |             69.92 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1480.63 |                  60.81 |                    68.24 |                 68.83 |              62.31 |                78.39 |                   21.61 |           92.29 |             44.22 |       0.018 |         nan |       nan |       32.9  |        18.2  |         44.94 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.96 |                  56.22 |                    68.17 |                 72.09 |              62.42 |                85.01 |                   14.99 |           96.3  |             66.46 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |               99.96 |                  56.04 |                    67.96 |                 71.83 |              63.74 |                81.6  |                   18.4  |           85.29 |             87.03 |     nan     |         nan |       nan |      nan    |         8.98 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | STNE     | StoneCo Ltd.                         | OTHER    |                1.89 |                  68.99 |                    67.5  |                 67.42 |              64.85 |                66.52 |                   33.48 |           86.35 |             32.06 |       0.635 |         nan |       nan |        1.61 |         4.12 |          3.48 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO      | FRO                                  | US       |                9.34 |                  58.17 |                    67.34 |                 70.63 |              62.6  |                77.12 |                   22.88 |           90.5  |             68.39 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                                  | US       |               15.15 |                  56.08 |                    67.21 |                 70.64 |              63.01 |                83.25 |                   16.75 |           85.75 |             76.52 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.58 |                  62.97 |                    67.16 |                 68.49 |              64.14 |                76.04 |                   23.96 |           84.29 |             51.18 |     nan     |         nan |       nan |      nan    |         8.67 |          7.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG              | EUROPE   |                2.98 |                  73.97 |                    74.45 |                 76.12 |              74.65 |                86.7  |                   13.3  |           84.64 |             57.81 |       0.877 |         nan |       nan |      nan    |       -77.69 |          2.08 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                   | EUROPE   |              239.93 |                  58.17 |                    70.24 |                 74.1  |              65.35 |                86.55 |                   13.45 |           92.42 |             78.88 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.88 |                  57.16 |                    69.7  |                 73.9  |              64.14 |                85.06 |                   14.94 |           95.66 |             76.73 |     nan     |         nan |       nan |      nan    |         9.23 |          6.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA     | NVIDIA Corporation         | US       |             4777.92 |                  61.64 |                    70.87 |                 72.66 |              66.07 |                76.98 |                   23.02 |           86.5  |             78.34 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.45 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                    | EUROPE   |               18.96 |                  56.22 |                    68.17 |                 72.09 |              62.42 |                85.01 |                   14.99 |           96.3  |             66.46 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                         | US       |                7.09 |                  63.86 |                    69.63 |                 71.91 |              66.97 |                72.05 |                   27.95 |           81.35 |             80.16 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                         | US       |               99.96 |                  56.04 |                    67.96 |                 71.83 |              63.74 |                81.6  |                   18.4  |           85.29 |             87.03 |     nan     |         nan |       nan |      nan    |         8.98 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc. | US       |                3.41 |                  68.48 |                    69.71 |                 71.65 |              68.61 |                68.59 |                   31.41 |           80.43 |             69.54 |       0.021 |         nan |       nan |        3.8  |         5.6  |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT      | DHT                        | US       |                3.09 |                  60.96 |                    68.78 |                 71.54 |              64.83 |                77.48 |                   22.52 |           87.98 |             69.92 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | INVA     | Innoviva, Inc.             | US       |                1.32 |                  64.71 |                    69.05 |                 71.47 |              66.44 |                82.36 |                   17.64 |           89.82 |             50.25 |       0.074 |         nan |       nan |        6.4  |         9.38 |          4.81 |        0.25 |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                       | US       |              240.17 |                  66.68 |                    70.36 |                 71.39 |              69.56 |                75.73 |                   24.27 |           72.57 |             79.2  |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                        | US       |               15.15 |                  56.08 |                    67.21 |                 70.64 |              63.01 |                83.25 |                   16.75 |           85.75 |             76.52 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                        | US       |                9.34 |                  58.17 |                    67.34 |                 70.63 |              62.6  |                77.12 |                   22.88 |           90.5  |             68.39 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                        | US       |               14.75 |                  56.79 |                    66.67 |                 69.85 |              62.72 |                79.7  |                   20.3  |           84.44 |             74.84 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                         | US       |             1074.59 |                  49.09 |                    64.17 |                 69.61 |              57.37 |                77.35 |                   22.65 |           95.1  |             80.96 |     nan     |         nan |       nan |      nan    |         6.79 |         24.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NWL.MI   | NewPrinces S.p.A.          | EUROPE   |                0.72 |                  74.83 |                    69.09 |                 69.3  |              70.53 |                68.5  |                   31.5  |           75.5  |             43.21 |       0.643 |         nan |       nan |        4.54 |      -125.84 |          2.17 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | EMBC     | Embecta Corp.              | US       |                0.29 |                  72.47 |                    69.03 |                 69.16 |              69.82 |                62.5  |                   37.5  |           70.34 |             63.92 |       0.413 |         nan |       nan |        5.76 |         3.35 |          4.01 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | A5G.IR   | A5G.IR                     | EUROPE   |               24.5  |                  55.44 |                    65.63 |                 69.1  |              59.79 |                80.47 |                   19.53 |           96    |             53.84 |     nan     |         nan |       nan |      nan    |        11.79 |         12.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | AVGO     | Broadcom Inc.              | US       |             1480.63 |                  60.81 |                    68.24 |                 68.83 |              62.31 |                78.39 |                   21.61 |           92.29 |             44.22 |       0.018 |         nan |       nan |       32.9  |        18.2  |         44.94 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | C5H.IR   | C5H.IR                     | EUROPE   |                1.65 |                  53.59 |                    64.87 |                 68.73 |              58.5  |                80.69 |                   19.31 |           97.73 |             53.87 |     nan     |         nan |       nan |      nan    |        10.34 |         10.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name               | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:-------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO                | US       |               98.01 |                     0.06 |    -0.06 |      0.12 |                  84.21 |                        84.85 |         79.63 |         86.12 |          84.51 |        80.81 |           85.04 |             80.98 |         3.56 |
|               2 | CMBT.BR   | CMBT.BR            | EUROPE   |                4.88 |                     0.07 |    -0.05 |      0.06 |                  75.94 |                        83.14 |         74.95 |         82.21 |          84.85 |        83.61 |           95.66 |             76.73 |         3.67 |
|               3 | PSX       | PSX                | US       |               89.72 |                     0.07 |    -0.06 |      0.07 |                  81.77 |                        83.09 |         75.24 |         84.72 |          82.2  |        78.67 |           78.2  |             85.48 |         3.81 |
|               4 | FRO       | FRO                | US       |                9.34 |                     0.07 |    -0.07 |      0.16 |                  81.39 |                        81.94 |         80.09 |         82.74 |          82.63 |        81.12 |           90.5  |             68.39 |         5.02 |
|               5 | NAT       | NAT                | US       |                1.44 |                     0.06 |    -0.06 |      0.19 |                  83.85 |                        80.66 |         80.33 |         80.78 |          78.79 |        73.63 |           86.52 |             69.25 |         4.61 |
|               6 | DHT       | DHT                | US       |                3.09 |                     0.06 |    -0.06 |      0.13 |                  83.92 |                        80.47 |         77.84 |         79.61 |          79.48 |        80.68 |           87.98 |             69.92 |         4.45 |
|               7 | DELL      | DELL               | US       |              314.64 |                     0.04 |    -0.01 |      0.19 |                  66.28 |                        80.41 |         86.33 |         86.51 |          80.94 |        68.49 |           71.67 |             85.82 |         7.82 |
|               8 | BP        | BP                 | US       |               99.96 |                     0.06 |    -0.01 |      0.04 |                  70.65 |                        77.75 |         74.07 |         72.52 |          71.64 |        78.34 |           85.29 |             87.03 |         4.46 |
|               9 | CIRSA.MC  | CIRSA.MC           | EUROPE   |                3.2  |                     0.04 |    -0.02 |      0.37 |                  68.63 |                        76.7  |         82.46 |         78.04 |          69.01 |        68.95 |           81.93 |             58.62 |         5.34 |
|              10 | EQNR      | EQNR               | US       |               87.93 |                     0.08 |    -0.04 |      0.02 |                  69.28 |                        75.06 |         64.19 |         74.65 |          73.75 |        75.47 |           73.65 |             84.06 |         5.62 |
|              11 | C5H.IR    | C5H.IR             | EUROPE   |                1.65 |                     0.06 |     0.01 |      0.05 |                  66.53 |                        74.9  |         74.6  |         67.8  |          72.07 |        76.31 |           97.73 |             53.87 |         2.69 |
|              12 | NESTE.HE  | NESTE.HE           | EUROPE   |               26.13 |                     0.05 |    -0.02 |      0.09 |                  74.77 |                        74.18 |         75.95 |         72.61 |          68.3  |        60.77 |           60.6  |             85.82 |         4.94 |
|              13 | PAA       | PAA                | US       |               15.15 |                     0.06 |    -0.04 |     -0.04 |                  75.96 |                        73.95 |         55.49 |         67.86 |          73.4  |        76.76 |           85.75 |             76.52 |         2.05 |
|              14 | SHEL      | SHEL               | US       |              240.17 |                     0.03 |     0.01 |      0.06 |                  52.79 |                        73.44 |         78.26 |         75.2  |          70.78 |        76.53 |           72.57 |             79.2  |         2.95 |
|              15 | ARGX.BR   | ARGX.BR            | EUROPE   |               52.88 |                     0.07 |    -0.03 |     -0.06 |                  68.06 |                        73.03 |         55.08 |         64.78 |          68.08 |        60.92 |           91.8  |             80.48 |         6.14 |
|              16 | NTNX      | NTNX               | US       |               16.18 |                     0.03 |    -0.03 |     -0.03 |                  61.95 |                        73    |         60.23 |         73.54 |          68.44 |        62.48 |           93.79 |             54.55 |         6.44 |
|              17 | FORTUM.HE | FORTUM.HE          | EUROPE   |               21.01 |                     0.05 |    -0.05 |      0.13 |                  83.13 |                        72.94 |         75.89 |         64.76 |          57.38 |        51.46 |           64.44 |             64.24 |         4.65 |
|              18 | GTLB      | GTLB               | US       |                6.86 |                     0.07 |    -0.05 |      0.05 |                  76.83 |                        72.85 |         69.84 |         79.05 |          63.29 |        48.52 |           55.11 |             71.87 |         8.37 |
|              19 | NVDA      | NVIDIA Corporation | US       |             4777.92 |                     0.02 |     0.01 |     -0.01 |                  46.65 |                        72.76 |         72.12 |         73.43 |          71.51 |        69.11 |           86.5  |             78.34 |         5.81 |
|              20 | DINO      | DINO               | US       |               16.7  |                     0.08 |    -0.08 |      0.1  |                  75.71 |                        72.74 |         70.89 |         81.28 |          75.36 |        69.11 |           48.87 |             73.11 |         4.63 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol    | name                     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | INDU-C.ST | AB Industrivärden (publ) | EUROPE   |               20.71 |             66    |         67.26 |         63.81 |          67.31 |        64.74 |           81.11 |             77.99 |             32.77 |         2.45 |             64.78 | medium             |               10.85 |                  3.48 |                 2.65 |
|    nan | TLRY      | Tilray Brands, Inc.      | OTHER    |                0.51 |             29.05 |         31.82 |         21.62 |          26.28 |        33.77 |           44.15 |             31.59 |             32.86 |         8.92 |             78.44 | long               |                3.86 |                  0.31 |                 0.35 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    231 | ITRG     | ITRG       | OTHER    |                0.49 |             60.94 |         50.02 |         59.29 |          62.58 |        72.76 |           76.92 |             63.53 |             85.79 |         8.16 |             68.32 | long               |                5.14 |                  5.48 |                 5.57 |
|    318 | HUT      | HUT        | US       |               10.49 |             57.83 |         67.04 |         54.93 |          60.73 |        46.57 |           37.79 |             78    |             18.93 |         8.56 |             66.84 | short              |              nan    |                  4.82 |               nan    |
|      7 | AMC      | AMC        | US       |                2.31 |             81.2  |         81.96 |         86.3  |          80.43 |        79.82 |           86.21 |             78.78 |            nan    |         9.48 |             65.07 | swing              |                5    |                  4.46 |                 4.12 |
|    216 | VZLA     | VZLA       | OTHER    |                1.23 |             61.39 |         50.94 |         61.23 |          61.56 |        62.15 |           87.56 |            nan    |             31.03 |         8.31 |             61.82 | long               |                3.88 |                  4.15 |               nan    |
|    584 | ZH       | Zhihu Inc. | OTHER    |                0.28 |             44.28 |         68.77 |         51.46 |          37.1  |        31.13 |           31.3  |             25.28 |             33.07 |         6.3  |             82.17 | short              |                5.24 |                  4.08 |                 3.04 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    460 | TEVA     | TEVA    | US       |               40.18 |             52.32 |         66.25 |         57.78 |          46.86 |        39.41 |           12.25 |             29.98 |             51.78 |         4.78 |             72.34 | short              |               -2.69 |                 -3.48 |                -3.6  |
|    672 | PAH3.DE  | PAH3.DE | EUROPE   |                7.89 |             34.51 |         28.98 |         30.9  |          38.13 |        62.4  |          nan    |             27.22 |             97.94 |         5.17 |             70.3  | long               |              -10.83 |                 -3.39 |                -2.85 |
|    642 | BAS.DE   | BAS.DE  | EUROPE   |               44.59 |             39.97 |         45.08 |         42.89 |          37.06 |        34.5  |           26.54 |             31.31 |             28.98 |         2.2  |             67.86 | short              |               -1.27 |                 -3.11 |               nan    |
|    639 | PIRC.MI  | PIRC.MI | EUROPE   |                7.03 |             40.07 |         49.68 |         43.22 |          36.92 |        36.07 |           15.46 |             21.92 |             60.15 |         2.12 |             71.32 | short              |               -4    |                 -3    |                -2.86 |
|    657 | 0JHU.IL  | 0JHU.IL | OTHER    |                8.25 |             37.85 |         23.69 |         32.43 |          43.26 |        74.56 |          nan    |            nan    |            100    |         5.18 |             60    | long               |                0.24 |                 -2.98 |                -3.13 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.85

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
- Event watch (otherwise eligible): **2**
- Final eligible: **705**
- Eligible change vs previous stored run: **-4**

Top exclusion categories:
- liquidity: 235
- price: 187
- market_cap: 163
- price_history: 19
- data_confidence: 9
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| DELL | 2 |  | 7 |  | 2 | main,pullback |
| CMBT.BR | 3 |  | 2 |  | 2 | main,pullback |
| VLO | 5 |  | 1 |  | 2 | main,pullback |
| FRO | 6 |  | 4 |  | 2 | main,pullback |
| PSX | 9 |  | 3 |  | 2 | main,pullback |
| NAT | 10 |  | 5 |  | 2 | main,pullback |
| NVDA | 48 | 3 | 19 | 2 | 1 | value,quality_value |
| PARR | 59 | 4 | 33 | 3 | 1 | value,quality_value |
| PBR-A | 78 | 8 | 41 | 10 | 1 | value,quality_value |
| EMBC | 150 | 7 |  | 6 | 1 | value,quality_value |
| BION.SW | 208 | 1 | 125 | 1 | 1 | value,quality_value |
| NWL.MI | 317 | 5 | 92 | 5 | 1 | value,quality_value |
| INVA | 417 | 6 | 130 | 4 | 1 | value,quality_value |
| AVGO | 422 | 9 | 136 | 7 | 1 | value,quality_value |
| STNE | 611 | 10 | 321 | 9 | 1 | value,quality_value |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **2** (MU, AMC)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 72.61 | 73.97 | 58.42 | 84.64 | 57.81 | 86.70 | 61.73 |
| 2 | INVA | value+pullback | 69.38 | 64.71 | 59.99 | 89.82 | 50.25 | 82.36 | 54.09 |
| 3 | PARR | value+pullback | 69.32 | 68.48 | 64.14 | 80.43 | 69.54 | 68.59 | 70.70 |
| 4 | AVGO | value+pullback | 69.29 | 60.81 | 68.41 | 92.29 | 44.22 | 78.39 | 54.01 |
| 5 | NWL.MI | value+pullback | 67.95 | 74.83 | 64.63 | 75.50 | 43.21 | 68.50 | 57.83 |
| 6 | GSL | value+pullback | 67.85 | 66.98 | 74.01 | 76.20 | 30.21 | 74.02 | 60.63 |
| 7 | PBR-A | value+pullback | 67.75 | 79.55 | 74.65 | 47.39 | 79.45 | 50.88 | 69.35 |
| 8 | NVDA | value+pullback | 66.36 | 61.64 | 46.65 | 86.50 | 78.34 | 76.98 | 71.82 |
| 9 | VOLV-B.ST | value+pullback | 64.76 | 64.98 | 69.50 | 62.48 | 62.76 | 61.22 | 53.31 |
| 10 | IRS | value+pullback | 63.37 | 67.28 | 69.38 | 63.58 | 40.42 | 61.30 | 46.44 |
| 11 | STNE | value+pullback | 62.17 | 68.99 | 48.05 | 86.35 | 32.06 | 66.52 | 42.84 |
| 12 | WB | value+pullback | 61.99 | 71.47 | 62.83 | 73.42 | 17.62 | 60.36 | 37.60 |
| 13 | 0Q2N.IL | value+pullback | 61.89 | 66.81 | 55.17 | 61.39 |  | 69.24 | 58.44 |
| 14 | GAB | value+pullback | 61.64 | 55.91 | 65.66 | 54.68 | 77.76 | 62.38 | 51.16 |
| 15 | AVK | value+pullback | 61.55 | 58.66 | 71.14 | 62.64 | 49.52 | 59.07 | 47.33 |
| 16 | SAP.DE | value+pullback | 60.07 | 59.67 | 48.48 | 74.09 | 55.05 | 67.16 | 62.97 |
| 17 | SDF.DE | value+pullback | 59.93 | 59.63 | 57.21 | 73.47 | 40.32 | 63.44 | 55.21 |
| 18 | BCE | value+pullback | 59.73 | 59.29 | 52.87 | 80.43 | 53.42 | 56.57 | 42.39 |
| 19 | VIPS | value+pullback | 59.62 | 65.95 | 51.86 | 81.14 | 24.92 | 61.02 | 42.02 |
| 20 | PBR | value+pullback | 58.23 | 55.90 | 71.10 | 47.39 | 69.38 | 48.22 | 63.71 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 72.9 | 8 / 2 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 73.1 | 16 / 9 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 72.7 | 26 / 24 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=1, large_20_100b=4, mega_100b_plus=2
