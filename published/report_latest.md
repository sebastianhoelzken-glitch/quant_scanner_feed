# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-23

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
- **OTHER:** 66.7/100
- **US:** 82.5/100

## Main multi-horizon ranking

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC     | US       |               95.45 |             86.15 |         76.82 |         88.05 |          88.2  |        84.25 |           85.28 |             89.68 |             71.58 |         4.25 |             73.14 | medium             |               -1    |                nan    |               nan    |
|      2 | MU       | MU      | US       |             1079.84 |             83.74 |         82.07 |         75.43 |          86.14 |        85.4  |           95.8  |             79.78 |             70.99 |         8.21 |             73.14 | medium             |                2.97 |                  2.96 |                 2.28 |
|      3 | VLO      | VLO     | US       |               94.72 |             82.73 |         76.56 |         85.06 |          85    |        80.47 |           86.25 |             81.53 |             59.94 |         3.56 |             69.68 | swing              |               -3.01 |                  1.09 |                 0.99 |
|      4 | HPE      | HPE     | US       |               70.67 |             82.71 |         89.41 |         84.17 |          81.25 |        72.51 |           74.71 |             80.46 |             49.95 |         7    |             72.34 | short              |                1.35 |                  0.58 |               nan    |
|      5 | DELL     | DELL    | US       |              304.42 |             82.65 |         88.13 |         84.57 |          80.73 |        67.96 |           74.22 |             85.84 |             29.44 |         7.82 |             72.23 | short              |               -0.97 |                  0.09 |                -0.09 |
|      6 | FRO      | FRO     | US       |                9.31 |             82.06 |         82.95 |         79.86 |          83.54 |        81.16 |           92    |             80.35 |             58.65 |         5.53 |             73.14 | medium             |               -2.86 |                  0.54 |                 0.49 |
|      7 | CMBT.BR  | CMBT.BR | EUROPE   |                4.88 |             81.72 |         77.87 |         81.19 |          84.06 |        82.25 |           96.23 |             76.73 |             62.34 |         3.61 |             73.14 | medium             |               -2.47 |                  1.11 |                 1.09 |
|      8 | AMC      | AMC     | US       |                2.31 |             81.17 |         82.26 |         86.7  |          80.07 |        79.47 |           85.38 |             78.76 |            nan    |         9.56 |             65.07 | swing              |                4.97 |                  4.46 |                 4.12 |
|      9 | GH       | GH      | US       |               20.74 |             81.04 |         78.54 |         86.48 |          83.53 |        76.19 |           63.13 |             87.92 |            nan    |         6.99 |             68.36 | swing              |              nan    |                nan    |               nan    |
|     10 | PSX      | PSX     | US       |               89.8  |             80.82 |         76.79 |         85.15 |          83.3  |        78.35 |           80.87 |             85.08 |             59.47 |         3.77 |             73.14 | swing              |               -3.04 |                  1.15 |                 1.2  |
|     11 | HSHP     | HSHP    | US       |                0.75 |             80.18 |         83.44 |         80.83 |          79.53 |        70.54 |           87.09 |            nan    |             29.85 |         4.83 |             62.84 | short              |               -2.62 |                nan    |               nan    |
|     12 | DHT      | DHT     | US       |                3.01 |             78.9  |         77.11 |         75.58 |          80.68 |        81.35 |           89.81 |             82.76 |             64.53 |         4.68 |             73.14 | long               |               -3.17 |                  0.5  |                 0.26 |
|     13 | TRMD     | TRMD    | US       |                3.1  |             78.84 |         81.88 |         74.82 |          76.48 |        81.2  |           86.24 |             49.52 |             84.61 |         5.48 |             69.68 | short              |              nan    |                nan    |               nan    |
|     14 | OKTA     | OKTA    | US       |               29.98 |             78.24 |         90.22 |         84.13 |          72.35 |        59.29 |           70.56 |             68.49 |             14.25 |         7.8  |             72.11 | short              |               -0.28 |                  0.9  |                 0.9  |
|     15 | HALO     | HALO    | US       |               11.4  |             78.05 |         80.88 |         81.32 |          75.22 |        71.85 |           87.33 |             51.2  |             47.81 |         5.95 |             72.11 | swing              |                1.94 |                nan    |               nan    |
|     16 | NAT      | NAT     | US       |                1.41 |             77.65 |         80.23 |         77.21 |          78.09 |        72.81 |           87.8  |             69.63 |             38.18 |         4.8  |             73.14 | short              |               -2.91 |                 -0.09 |                 0    |
|     17 | FSM      | FSM     | US       |                3.15 |             77.27 |         71.91 |         77.22 |          77.33 |        80.58 |           80.33 |             70.25 |             83.26 |         7.22 |             73.14 | long               |                1.91 |                  3.46 |                 2.95 |
|     18 | REP.MC   | REP.MC  | EUROPE   |               32.58 |             76.89 |         80.81 |         79.97 |          73.82 |        69.98 |           59.32 |             78.61 |             70.68 |         3.72 |             73.14 | short              |                2.24 |                  1.54 |                 1.24 |
|     19 | P        | P       | US       |               32.23 |             76.83 |         88.07 |         82.68 |          70.98 |        58.49 |           72.13 |             85.86 |             11.4  |         8.13 |             72.68 | short              |               -0.53 |                  2.44 |                 1.76 |
|     20 | KIN.BR   | KIN.BR  | EUROPE   |                1.35 |             76.39 |         78.99 |         79.1  |          73.8  |        64.72 |           89.9  |             63.75 |             17.24 |         3.73 |             73.14 | swing              |               -1.35 |                 -0.46 |                -0.35 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.06 |                  73.97 |                    74.48 |                 76.16 |              74.68 |                86.75 |                   13.25 |           84.64 |             58    |       0.858 |         nan |       nan |      nan    |       -79.36 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHEL      | SHEL                                 | US       |              233.82 |                  66.76 |                    71.25 |                 72.59 |              69.95 |                77.42 |                   22.58 |           76.05 |             79.49 |     nan     |         nan |       nan |      nan    |         9.07 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              235.1  |                  57.98 |                    70.81 |                 74.9  |              65.72 |                88.03 |                   11.97 |           93.64 |             81.29 |     nan     |         nan |       nan |      nan    |         9.39 |         10.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA      | NVIDIA Corporation                   | US       |             4820.51 |                  60.87 |                    70.8  |                 72.81 |              65.83 |                77.55 |                   22.45 |           86.9  |             80.38 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.93 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT       | DHT                                  | US       |                3.01 |                  59.52 |                    70.31 |                 73.96 |              65.91 |                82.07 |                   17.93 |           89.81 |             82.76 |     nan     |         nan |       nan |      nan    |         9.97 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  75.89 |                    70.2  |                 70.27 |              73.07 |                57.67 |                   42.33 |           61.58 |             80.48 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.74 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.88 |                  57.43 |                    70.01 |                 74.23 |              64.4  |                85.45 |                   14.55 |           96.23 |             76.73 |     nan     |         nan |       nan |      nan    |         9.3  |          6.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.46 |                  68.48 |                    69.8  |                 71.77 |              68.7  |                68.71 |                   31.29 |           80.43 |             70.24 |       0.021 |         nan |       nan |        3.86 |         5.72 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | EMBC      | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    69.67 |                 69.7  |              70.61 |                62.46 |                   37.54 |           70.56 |             63.81 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | STNE      | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.17 |                    69.45 |                 69.02 |              67.47 |                68.16 |                   31.84 |           85.87 |             32.3  |       0.608 |         nan |       nan |        1.62 |         4.3  |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | BBWI      | Bath & Body Works, Inc.              | US       |                3.02 |                  74.85 |                    69.17 |                 66.72 |              67.99 |                59.29 |                   40.71 |           75.98 |             34.32 |       0.221 |         nan |       nan |        5.64 |         6.16 |          4.44 |        0.69 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SM        | SM                                   | US       |                7.04 |                  62.76 |                    69.16 |                 71.66 |              66.08 |                72.47 |                   27.53 |           83.13 |             78.44 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  74.83 |                    69.15 |                 69.38 |              70.59 |                68.72 |                   31.28 |           75.5  |             43.47 |       0.61  |         nan |       nan |        4.72 |      -132.62 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            9 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.2  |                  71.06 |                    69.09 |                 67.92 |              70.82 |                69.84 |                   30.16 |           61.12 |            nan    |       0.231 |         nan |       nan |        1.54 |       nan    |          2.98 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BP        | BP                                   | US       |               96.82 |                  57.34 |                    68.88 |                 72.69 |              64.54 |                81.95 |                   18.05 |           87.34 |             85.04 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | AVGO      | Broadcom Inc.                        | US       |             1517.87 |                  60.81 |                    68.24 |                 68.82 |              62.32 |                78.52 |                   21.48 |           92.29 |             44.04 |       0.018 |         nan |       nan |       33.98 |        18.81 |         46.56 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO       | FRO                                  | US       |                9.31 |                  56.15 |                    68.23 |                 72.42 |              62.99 |                80.7  |                   19.3  |           92    |             80.35 |     nan     |         nan |       nan |      nan    |        10.47 |          7.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               59.38 |                  74.09 |                    67.93 |                 65.22 |              70.18 |                59.84 |                   40.16 |           55.24 |             60.66 |       0.036 |         nan |       nan |       15.88 |        13.19 |         18.65 |        0.96 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY       | BMY                                  | US       |              110.91 |                  62.02 |                    67.79 |                 69.66 |              64.97 |                76.4  |                   23.6  |           81.78 |             65.62 |     nan     |         nan |       nan |      nan    |         9.48 |         13.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | IHS       | IHS Holding Limited                  | OTHER    |                2.49 |                  72.61 |                    67.58 |                 67.51 |              71.13 |                61.18 |                   38.82 |           55.59 |             78.4  |      -0.114 |         nan |       nan |        7.52 |        15.35 |          5.18 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  73.97 |                    74.48 |                 76.16 |              74.68 |                86.75 |                   13.25 |           84.64 |             58    |       0.858 |         nan |       nan |      nan    |       -79.36 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              235.1  |                  57.98 |                    70.81 |                 74.9  |              65.72 |                88.03 |                   11.97 |           93.64 |             81.29 |     nan     |         nan |       nan |      nan    |         9.39 |         10.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.88 |                  57.43 |                    70.01 |                 74.23 |              64.4  |                85.45 |                   14.55 |           96.23 |             76.73 |     nan     |         nan |       nan |      nan    |         9.3  |          6.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.01 |                  59.52 |                    70.31 |                 73.96 |              65.91 |                82.07 |                   17.93 |           89.81 |             82.76 |     nan     |         nan |       nan |      nan    |         9.97 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA     | NVIDIA Corporation                   | US       |             4820.51 |                  60.87 |                    70.8  |                 72.81 |              65.83 |                77.55 |                   22.45 |           86.9  |             80.38 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.93 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP       | BP                                   | US       |               96.82 |                  57.34 |                    68.88 |                 72.69 |              64.54 |                81.95 |                   18.05 |           87.34 |             85.04 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              233.82 |                  66.76 |                    71.25 |                 72.59 |              69.95 |                77.42 |                   22.58 |           76.05 |             79.49 |     nan     |         nan |       nan |      nan    |         9.07 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.31 |                  56.15 |                    68.23 |                 72.42 |              62.99 |                80.7  |                   19.3  |           92    |             80.35 |     nan     |         nan |       nan |      nan    |        10.47 |          7.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.46 |                  68.48 |                    69.8  |                 71.77 |              68.7  |                68.71 |                   31.29 |           80.43 |             70.24 |       0.021 |         nan |       nan |        3.86 |         5.72 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM       | SM                                   | US       |                7.04 |                  62.76 |                    69.16 |                 71.66 |              66.08 |                72.47 |                   27.53 |           83.13 |             78.44 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.78 |                  54.16 |                    66.95 |                 71.14 |              60.88 |                84.95 |                   15.05 |           96.52 |             65.98 |     nan     |         nan |       nan |      nan    |        10.86 |         14.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                                  | US       |               95.45 |                  51.34 |                    65.71 |                 70.31 |              60.85 |                82.87 |                   17.13 |           85.28 |             89.68 |     nan     |         nan |       nan |      nan    |         8.27 |         13.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  75.89 |                    70.2  |                 70.27 |              73.07 |                57.67 |                   42.33 |           61.58 |             80.48 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.74 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|            5 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    69.67 |                 69.7  |              70.61 |                62.46 |                   37.54 |           70.56 |             63.81 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                  | US       |              110.91 |                  62.02 |                    67.79 |                 69.66 |              64.97 |                76.4  |                   23.6  |           81.78 |             65.62 |     nan     |         nan |       nan |      nan    |         9.48 |         13.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  74.83 |                    69.15 |                 69.38 |              70.59 |                68.72 |                   31.28 |           75.5  |             43.47 |       0.61  |         nan |       nan |        4.72 |      -132.62 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | MU       | MU                                   | US       |             1079.84 |                  48.51 |                    63.78 |                 69.31 |              56.78 |                77.1  |                   22.9  |           95.8  |             79.78 |     nan     |         nan |       nan |      nan    |         6.9  |         23.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | STNE     | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.17 |                    69.45 |                 69.02 |              67.47 |                68.16 |                   31.84 |           85.87 |             32.3  |       0.608 |         nan |       nan |        1.62 |         4.3  |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BEN      | BEN                                  | US       |               14.68 |                  54.88 |                    65.5  |                 68.96 |              60.95 |                79.47 |                   20.53 |           86.58 |             71.3  |     nan     |         nan |       nan |      nan    |        10.42 |         22.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                                  | US       |               94.72 |                  50.67 |                    64.5  |                 68.91 |              59.42 |                82.12 |                   17.88 |           86.25 |             81.53 |     nan     |         nan |       nan |      nan    |        10.12 |         16.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | MPC      | MPC      | US       |               95.45 |                     0.08 |    -0.05 |      0.07 |                  68.18 |                        84.76 |         76.82 |         88.05 |          88.2  |        84.25 |           85.28 |             89.68 |         4.25 |
|               2 | PSX      | PSX      | US       |               89.8  |                     0.06 |    -0.03 |      0.06 |                  74.5  |                        82.69 |         76.79 |         85.15 |          83.3  |        78.35 |           80.87 |             85.08 |         3.77 |
|               3 | VLO      | VLO      | US       |               94.72 |                     0.09 |    -0.05 |      0.09 |                  65.45 |                        81.83 |         76.56 |         85.06 |          85    |        80.47 |           86.25 |             81.53 |         3.56 |
|               4 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.88 |                     0.07 |    -0.03 |      0.11 |                  69.81 |                        81.82 |         77.87 |         81.19 |          84.06 |        82.25 |           96.23 |             76.73 |         3.61 |
|               5 | FRO      | FRO      | US       |                9.31 |                     0.08 |    -0.02 |      0.15 |                  62.78 |                        81.34 |         82.95 |         79.86 |          83.54 |        81.16 |           92    |             80.35 |         5.53 |
|               6 | DELL     | DELL     | US       |              304.42 |                     0.06 |     0.02 |      0.28 |                  63.22 |                        81.27 |         88.13 |         84.57 |          80.73 |        67.96 |           74.22 |             85.84 |         7.82 |
|               7 | DHT      | DHT      | US       |                3.01 |                     0.08 |    -0.03 |      0.09 |                  64.88 |                        78.67 |         77.11 |         75.58 |          80.68 |        81.35 |           89.81 |             82.76 |         4.68 |
|               8 | NAT      | NAT      | US       |                1.41 |                     0.07 |    -0.03 |      0.13 |                  66.91 |                        78.15 |         80.23 |         77.21 |          78.09 |        72.81 |           87.8  |             69.63 |         4.8  |
|               9 | SHELL.AS | SHELL.AS | EUROPE   |              235.1  |                     0.04 |    -0.01 |      0.05 |                  62.89 |                        77.69 |         74.68 |         73.01 |          73.41 |        79.46 |           93.64 |             81.29 |         2.4  |
|              10 | GH       | GH       | US       |               20.74 |                     0.03 |     0.01 |      0.09 |                  54.36 |                        77.21 |         78.54 |         86.48 |          83.53 |        76.19 |           63.13 |             87.92 |         6.99 |
|              11 | AVAH     | AVAH     | US       |                2.52 |                     0.09 |    -0.08 |     -0.04 |                  74.89 |                        76.34 |         56.8  |         76.76 |          77.58 |        72.85 |           92.61 |             54.67 |         7.7  |
|              12 | BP       | BP       | US       |               96.82 |                     0.07 |    -0.07 |     -0    |                  81.04 |                        75.62 |         61.82 |         66.49 |          71.47 |        77.94 |           87.34 |             85.04 |         4.48 |
|              13 | SHEL     | SHEL     | US       |              233.82 |                     0.05 |    -0.05 |      0.01 |                  82.99 |                        75.03 |         67.14 |         70.91 |          71.04 |        76.96 |           76.05 |             79.49 |         3.02 |
|              14 | DAR      | DAR      | US       |                8.48 |                     0.1  |    -0.08 |     -0.02 |                  67.9  |                        74.81 |         52.89 |         67.25 |          77.88 |        83.34 |           90.94 |             85.42 |         4.62 |
|              15 | DINO     | DINO     | US       |               16.54 |                     0.1  |    -0.06 |      0.1  |                  62.23 |                        74.59 |         70.62 |         84.25 |          79.31 |        71.03 |           50.68 |             86.6  |         4.56 |
|              16 | C5H.IR   | C5H.IR   | EUROPE   |                1.67 |                     0.05 |     0    |      0.07 |                  64.73 |                        74.5  |         74.58 |         66.03 |          70.74 |        74.31 |           97.84 |             52.87 |         2.64 |
|              17 | MT.AS    | MT.AS    | EUROPE   |               48.14 |                     0.05 |    -0.01 |     -0.01 |                  74.21 |                        74.35 |         61.77 |         73.94 |          76.82 |        73.65 |           71.25 |             80    |         4.96 |
|              18 | BIRG.IR  | BIRG.IR  | EUROPE   |               18.78 |                     0.02 |    -0.02 |      0.05 |                  55.73 |                        74.33 |         73.54 |         70.87 |          73.83 |        75.97 |           96.52 |             65.98 |         2.2  |
|              19 | EQNR     | EQNR     | US       |               86.45 |                     0.1  |    -0.1  |     -0.03 |                  72.7  |                        73.92 |         53.66 |         70.7  |          73.95 |        75.09 |           75.73 |             83.42 |         5.58 |
|              20 | APA      | APA      | US       |               12.93 |                     0.11 |    -0.11 |     -0.01 |                  68.9  |                        73.59 |         58.17 |         71.58 |          75.4  |        78.64 |           77.22 |             80.13 |         5.93 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              347.91 |             41.45 |          39.3 |         34.43 |          43.61 |        50.36 |           77.39 |             44.81 |                26 |          8.5 |             89.81 | long               |                0.61 |                  1.28 |                 1.25 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    199 | ITRG     | ITRG                | US       |                0.51 |             62.68 |         65.9  |         59.46 |          57.74 |        66.34 |           60.43 |             63.6  |             85.08 |         8.18 |             68.32 | long               |                6.88 |                  5.83 |                 5.83 |
|     24 | AMS.SW   | AMS.SW              | EUROPE   |                2.36 |             75.09 |         84.96 |         80.31 |          69.88 |        51.99 |           53.26 |             88.25 |              9.64 |         8.65 |             73.14 | short              |                4.02 |                  5.09 |               nan    |
|      8 | AMC      | AMC                 | US       |                2.31 |             81.17 |         82.26 |         86.7  |          80.07 |        79.47 |           85.38 |             78.76 |            nan    |         9.56 |             65.07 | swing              |                4.97 |                  4.46 |                 4.12 |
|    194 | VZLA     | VZLA                | US       |                1.33 |             62.81 |         76.59 |         67.97 |          57.65 |        54.16 |           60.6  |            nan    |             39.8  |         8.37 |             61.82 | short              |                5.3  |                  4.44 |               nan    |
|    280 | IHS      | IHS Holding Limited | OTHER    |                2.49 |             59.57 |         63.94 |         56.32 |          57.71 |        61.43 |           55.59 |             78.4  |             64.23 |         2.06 |             72.86 | short              |               -0.64 |                  4.1  |                 4.16 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                  | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    703 | MGPI     | MGP Ingredients, Inc. | US       |                0.25 |             25.17 |         22.53 |         20.39 |          27.81 |        36.49 |           43.7  |             26.01 |             45.6  |         6.2  |             84.71 | long               |                0.38 |                 -3.36 |               nan    |
|    428 | TEVA     | TEVA                  | US       |               40.2  |             53    |         66.89 |         58.58 |          47.42 |        38.59 |           12.81 |             29.5  |             47.47 |         4.7  |             72.34 | short              |               -2.01 |                 -3.35 |                -3.5  |
|    585 | FRSH     | FRSH                  | US       |                2.83 |             44.24 |         38.03 |         57.68 |          47.8  |        40.68 |           30.68 |             30.35 |             43.28 |         7.59 |             72.11 | swing              |               -2.16 |                 -2.87 |                -2.19 |
|    623 | BAS.DE   | BAS.DE                | EUROPE   |               44.68 |             41.52 |         54.66 |         44.92 |          38.13 |        34.44 |           28.28 |             29.56 |             27.46 |         2.04 |             67.86 | short              |                0.28 |                 -2.8  |               nan    |
|    370 | STR.VI   | STR.VI                | EUROPE   |               12.26 |             55.32 |         76.61 |         60.91 |          49.74 |        42.59 |          nan    |             33.07 |             29.39 |         5.45 |             66.84 | short              |               -0.79 |                 -2.51 |               nan    |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
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
- Excluded by hard/data filters: **293**
- Event watch (otherwise eligible): **1**
- Final eligible: **706**
- Eligible change vs previous stored run: **-3**

Top exclusion categories:
- liquidity: 237
- price: 185
- market_cap: 162
- price_history: 17
- data_confidence: 9
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 1 |  | 2 | main,pullback |
| VLO | 3 |  | 3 |  | 2 | main,pullback |
| DELL | 5 |  | 6 |  | 2 | main,pullback |
| FRO | 6 |  | 5 |  | 2 | main,pullback |
| CMBT.BR | 7 |  | 4 |  | 2 | main,pullback |
| GH | 9 |  | 10 |  | 2 | main,pullback |
| PSX | 10 |  | 2 |  | 2 | main,pullback |
| PARR | 32 | 4 | 22 | 3 | 1 | value,quality_value |
| PBR-A | 44 | 3 | 23 | 4 | 1 | value,quality_value |
| NVDA | 59 | 2 |  | 2 | 1 | value,quality_value |
| EMBC | 163 | 5 |  | 5 | 1 | value,quality_value |
| BION.SW | 183 | 1 | 107 | 1 | 1 | value,quality_value |
| 0Q2N.IL | 229 | 9 |  | 10 | 1 | value,quality_value |
| NWL.MI | 248 | 8 | 53 | 6 | 1 | value,quality_value |
| AVGO | 289 | 10 |  | 8 | 1 | value,quality_value |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **6** (MU, HPE, DELL, FRO, AMC, GH)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **4** (FRO, DELL, NAT, GH)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 71.02 | 73.97 | 51.93 | 84.64 | 58.00 | 86.75 | 63.30 |
| 2 | NWL.MI | value+pullback | 70.37 | 74.83 | 74.00 | 75.50 | 43.47 | 68.72 | 60.73 |
| 3 | PARR | value+pullback | 69.84 | 68.48 | 65.86 | 80.43 | 70.24 | 68.71 | 74.18 |
| 4 | PBR-A | value+pullback | 68.69 | 75.89 | 68.43 | 61.58 | 80.48 | 57.67 | 73.13 |
| 5 | 0Q2N.IL | value+pullback | 67.90 | 71.06 | 73.79 | 61.12 |  | 69.84 | 61.51 |
| 6 | STNE | value+pullback | 67.00 | 72.17 | 62.40 | 85.87 | 32.30 | 68.16 | 49.38 |
| 7 | VOLV-B.ST | value+pullback | 66.68 | 74.09 | 72.55 | 55.24 | 60.66 | 59.84 | 54.31 |
| 8 | GSL | value+pullback | 65.51 | 69.15 | 59.10 | 77.16 | 30.46 | 76.86 | 62.46 |
| 9 | BCE | value+pullback | 65.46 | 59.29 | 73.54 | 80.43 | 57.52 | 57.36 | 43.80 |
| 10 | CNC | value+pullback | 63.34 | 71.92 | 69.23 | 50.47 | 64.40 | 52.22 | 60.02 |
| 11 | INVA | value+pullback | 63.32 | 63.47 | 45.55 | 90.78 | 31.38 | 80.71 | 51.12 |
| 12 | UNIT | value+pullback | 63.06 | 80.01 | 70.08 | 64.98 | 29.09 | 44.43 | 42.99 |
| 13 | WB | value+pullback | 62.49 | 71.47 | 64.82 | 73.42 | 17.61 | 60.34 | 40.71 |
| 14 | RCI | value+pullback | 62.47 | 64.38 | 55.10 | 89.13 | 42.75 | 58.69 | 42.47 |
| 15 | HMC | value+pullback | 61.51 | 57.07 | 46.50 | 75.65 | 81.36 | 66.42 | 69.61 |
| 16 | IRS | value+pullback | 61.15 | 68.25 | 60.56 | 61.40 | 40.97 | 61.14 | 51.40 |
| 17 | PERI | value+pullback | 59.26 | 66.14 | 47.60 | 50.87 | 74.31 | 62.26 | 43.06 |
| 18 | ORC | value+pullback | 58.91 | 60.76 | 55.47 | 75.90 | 35.02 | 59.63 | 41.50 |
| 19 | BP | pullback | 58.25 | 57.34 | 81.04 | 87.34 | 85.04 | 81.95 | 68.98 |
| 20 | DEC | value+pullback | 56.84 | 66.06 | 56.77 | 64.01 | 32.42 | 49.92 | 44.00 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 8/10 | 8/10 | 0/10 | 72.7 | 4 / 6 |
| Top 25 | 25/25 | 24/25 | 23/25 | 22/25 | 0/25 | 72.7 | 8 / 17 |
| Top 50 | 50/50 | 48/50 | 48/50 | 46/50 | 0/50 | 72.7 | 22 / 28 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=1, large_20_100b=5, mega_100b_plus=2
