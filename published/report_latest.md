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

- **EUROPE:** 81.2/100
- **OTHER:** 68.2/100
- **US:** 82.5/100

## Main multi-horizon ranking

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC     | US       |               95.45 |             86.24 |         76.79 |         88.1  |          88.29 |        84.39 |           85.53 |             89.65 |             71.69 |         4.26 |             73.14 | medium             |               -0.9  |                nan    |               nan    |
|      2 | MU       | MU      | US       |             1079.84 |             83.73 |         82.04 |         75.44 |          86.14 |        85.41 |           95.76 |             79.72 |             71.1  |         8.21 |             73.14 | medium             |                2.96 |                  2.96 |                 2.28 |
|      3 | VLO      | VLO     | US       |               94.72 |             82.84 |         76.57 |         85.1  |          85.09 |        80.58 |           86.55 |             81.53 |             59.89 |         3.56 |             69.68 | swing              |               -2.91 |                  1.11 |                 1.01 |
|      4 | HPE      | HPE     | US       |               70.67 |             82.71 |         89.41 |         84.13 |          81.28 |        72.58 |           74.86 |             80.42 |             50.03 |         7    |             72.34 | short              |                1.35 |                  0.58 |               nan    |
|      5 | DELL     | DELL    | US       |              304.42 |             82.65 |         88.14 |         84.55 |          80.75 |        68    |           74.35 |             85.81 |             29.41 |         7.82 |             72.23 | short              |               -0.97 |                  0.09 |                -0.09 |
|      6 | FRO      | FRO     | US       |                9.31 |             82.09 |         82.97 |         79.87 |          83.6  |        81.22 |           92.18 |             80.34 |             58.59 |         5.53 |             73.14 | medium             |               -2.82 |                  0.54 |                 0.49 |
|      7 | CMBT.BR  | CMBT.BR | EUROPE   |                4.89 |             81.87 |         78.39 |         81.33 |          84.18 |        82.4  |           96.34 |             76.76 |             62.75 |         3.62 |             73.14 | medium             |               -2.32 |                  1.14 |                 1.11 |
|      8 | AMC      | AMC     | US       |                2.31 |             81.16 |         82.2  |         86.66 |          80.13 |        79.58 |           85.57 |             78.76 |            nan    |         9.56 |             65.07 | swing              |                4.97 |                  4.45 |                 4.12 |
|      9 | GH       | GH      | US       |               20.74 |             81.04 |         78.47 |         86.45 |          83.61 |        76.36 |           63.45 |             87.88 |            nan    |         6.99 |             68.36 | swing              |              nan    |                nan    |               nan    |
|     10 | PSX      | PSX     | US       |               89.8  |             80.9  |         76.81 |         85.17 |          83.37 |        78.44 |           81.12 |             85.05 |             59.42 |         3.77 |             73.14 | swing              |               -2.96 |                  1.17 |                 1.21 |
|     11 | HSHP     | HSHP    | US       |                0.75 |             80.2  |         83.32 |         80.82 |          79.58 |        70.54 |           87.27 |            nan    |             29.56 |         4.83 |             62.84 | short              |               -2.61 |                nan    |               nan    |
|     12 | DHT      | DHT     | US       |                3.01 |             78.91 |         77.12 |         75.59 |          80.69 |        81.36 |           89.85 |             82.72 |             64.52 |         4.68 |             73.14 | long               |               -3.16 |                  0.5  |                 0.26 |
|     13 | TRMD     | TRMD    | US       |                3.1  |             78.89 |         81.83 |         74.81 |          76.51 |        81.27 |           86.4  |             49.47 |             84.69 |         5.48 |             69.68 | short              |              nan    |                nan    |               nan    |
|     14 | OKTA     | OKTA    | US       |               29.98 |             78.19 |         90.16 |         84.07 |          72.32 |        59.28 |           70.6  |             68.22 |             14.24 |         7.81 |             72.11 | short              |               -0.33 |                  0.89 |                 0.89 |
|     15 | HALO     | HALO    | US       |               11.4  |             78.09 |         80.86 |         81.35 |          75.31 |        71.97 |           87.64 |             51.12 |             47.79 |         5.95 |             72.11 | swing              |                1.98 |                nan    |               nan    |
|     16 | NAT      | NAT     | US       |                1.41 |             77.74 |         80.22 |         77.3  |          78.18 |        72.9  |           87.98 |             69.63 |             38.16 |         4.8  |             73.14 | short              |               -2.82 |                 -0.07 |                 0.02 |
|     17 | FSM      | FSM     | US       |                3.15 |             77.31 |         71.84 |         77.22 |          77.4  |        80.69 |           80.52 |             70.25 |             83.4  |         7.22 |             73.14 | long               |                1.94 |                  3.47 |                 2.95 |
|     18 | REP.MC   | REP.MC  | EUROPE   |               32.6  |             77    |         80.83 |         80.05 |          73.94 |        70.18 |           59.46 |             78.55 |             71.15 |         3.73 |             73.14 | short              |                2.34 |                  1.56 |                 1.25 |
|     19 | P        | P       | US       |               32.23 |             76.86 |         88.01 |         82.68 |          71.04 |        58.57 |           72.29 |             85.82 |             11.49 |         8.13 |             72.68 | short              |               -0.51 |                  2.45 |                 1.76 |
|     20 | KIN.BR   | KIN.BR  | EUROPE   |                1.35 |             76.4  |         78.87 |         79.18 |          73.93 |        64.93 |           90.22 |             63.76 |             17.5  |         3.73 |             73.14 | swing              |               -1.35 |                 -0.46 |                -0.35 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.06 |                  73.97 |                    74.47 |                 76.15 |              74.67 |                86.73 |                   13.27 |           84.64 |             57.97 |       0.858 |         nan |       nan |      nan    |       -79.36 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHEL      | SHEL                                 | US       |              233.82 |                  66.67 |                    71.25 |                 72.62 |              69.91 |                77.54 |                   22.46 |           76.28 |             79.48 |     nan     |         nan |       nan |      nan    |         9.07 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              235.22 |                  57.98 |                    70.84 |                 74.94 |              65.73 |                88.1  |                   11.9  |           93.79 |             81.24 |     nan     |         nan |       nan |      nan    |         9.39 |         10.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA      | NVIDIA Corporation                   | US       |             4820.51 |                  60.87 |                    70.79 |                 72.8  |              65.82 |                77.54 |                   22.46 |           86.9  |             80.36 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.93 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT       | DHT                                  | US       |                3.01 |                  59.42 |                    70.25 |                 73.92 |              65.83 |                82.07 |                   17.93 |           89.85 |             82.72 |     nan     |         nan |       nan |      nan    |         9.97 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  75.89 |                    70.2  |                 70.27 |              73.07 |                57.67 |                   42.33 |           61.58 |             80.47 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.74 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.89 |                  57.24 |                    69.93 |                 74.18 |              64.28 |                85.5  |                   14.5  |           96.34 |             76.76 |     nan     |         nan |       nan |      nan    |         9.32 |          6.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.46 |                  68.48 |                    69.8  |                 71.77 |              68.7  |                68.71 |                   31.29 |           80.43 |             70.24 |       0.021 |         nan |       nan |        3.86 |         5.72 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | EMBC      | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    69.66 |                 69.69 |              70.61 |                62.46 |                   37.54 |           70.56 |             63.78 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | STNE      | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.17 |                    69.44 |                 69.01 |              67.46 |                68.16 |                   31.84 |           85.87 |             32.29 |       0.608 |         nan |       nan |        1.62 |         4.3  |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM        | SM                                   | US       |                7.04 |                  62.65 |                    69.18 |                 71.72 |              66.02 |                72.63 |                   27.37 |           83.5  |             78.39 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | BBWI      | Bath & Body Works, Inc.              | US       |                3.02 |                  74.85 |                    69.17 |                 66.71 |              67.99 |                59.29 |                   40.71 |           75.98 |             34.27 |       0.221 |         nan |       nan |        5.64 |         6.16 |          4.44 |        0.69 |                 nan |              nan |                  11 |                  0.58 |
|            8 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  74.83 |                    69.14 |                 69.37 |              70.59 |                68.7  |                   31.3  |           75.5  |             43.43 |       0.612 |         nan |       nan |        4.72 |      -132.26 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            9 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.21 |                  71.06 |                    69.09 |                 67.92 |              70.82 |                69.85 |                   30.15 |           61.12 |            nan    |       0.231 |         nan |       nan |        1.54 |       nan    |          2.99 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BP        | BP                                   | US       |               96.82 |                  57.34 |                    68.93 |                 72.76 |              64.55 |                82.06 |                   17.94 |           87.6  |             84.99 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                                  | US       |                9.31 |                  56.25 |                    68.33 |                 72.53 |              63.08 |                80.78 |                   19.22 |           92.18 |             80.34 |     nan     |         nan |       nan |      nan    |        10.47 |          7.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | AVGO      | Broadcom Inc.                        | US       |             1517.87 |                  60.81 |                    68.24 |                 68.81 |              62.31 |                78.51 |                   21.49 |           92.29 |             44    |       0.018 |         nan |       nan |       33.98 |        18.81 |         46.56 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|           11 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               59.36 |                  74.09 |                    67.92 |                 65.22 |              70.17 |                59.84 |                   40.16 |           55.24 |             60.62 |       0.036 |         nan |       nan |       15.88 |        13.18 |         18.64 |        0.96 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY       | BMY                                  | US       |              110.91 |                  61.82 |                    67.66 |                 69.55 |              64.81 |                76.36 |                   23.64 |           81.79 |             65.54 |     nan     |         nan |       nan |      nan    |         9.48 |         13.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | IHS       | IHS Holding Limited                  | OTHER    |                2.49 |                  72.61 |                    67.57 |                 67.5  |              71.13 |                61.17 |                   38.83 |           55.59 |             78.38 |      -0.114 |         nan |       nan |        7.52 |        15.35 |          5.18 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  73.97 |                    74.47 |                 76.15 |              74.67 |                86.73 |                   13.27 |           84.64 |             57.97 |       0.858 |         nan |       nan |      nan    |       -79.36 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              235.22 |                  57.98 |                    70.84 |                 74.94 |              65.73 |                88.1  |                   11.9  |           93.79 |             81.24 |     nan     |         nan |       nan |      nan    |         9.39 |         10.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.89 |                  57.24 |                    69.93 |                 74.18 |              64.28 |                85.5  |                   14.5  |           96.34 |             76.76 |     nan     |         nan |       nan |      nan    |         9.32 |          6.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.01 |                  59.42 |                    70.25 |                 73.92 |              65.83 |                82.07 |                   17.93 |           89.85 |             82.72 |     nan     |         nan |       nan |      nan    |         9.97 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA     | NVIDIA Corporation                   | US       |             4820.51 |                  60.87 |                    70.79 |                 72.8  |              65.82 |                77.54 |                   22.46 |           86.9  |             80.36 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.93 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP       | BP                                   | US       |               96.82 |                  57.34 |                    68.93 |                 72.76 |              64.55 |                82.06 |                   17.94 |           87.6  |             84.99 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              233.82 |                  66.67 |                    71.25 |                 72.62 |              69.91 |                77.54 |                   22.46 |           76.28 |             79.48 |     nan     |         nan |       nan |      nan    |         9.07 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.31 |                  56.25 |                    68.33 |                 72.53 |              63.08 |                80.78 |                   19.22 |           92.18 |             80.34 |     nan     |         nan |       nan |      nan    |        10.47 |          7.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.46 |                  68.48 |                    69.8  |                 71.77 |              68.7  |                68.71 |                   31.29 |           80.43 |             70.24 |       0.021 |         nan |       nan |        3.86 |         5.72 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM       | SM                                   | US       |                7.04 |                  62.65 |                    69.18 |                 71.72 |              66.02 |                72.63 |                   27.37 |           83.5  |             78.39 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.76 |                  54.69 |                    67.28 |                 71.41 |              61.26 |                84.96 |                   15.04 |           96.63 |             65.97 |     nan     |         nan |       nan |      nan    |        10.84 |         14.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                                  | US       |               95.45 |                  51.34 |                    65.77 |                 70.38 |              60.87 |                82.98 |                   17.02 |           85.53 |             89.65 |     nan     |         nan |       nan |      nan    |         8.27 |         13.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  75.89 |                    70.2  |                 70.27 |              73.07 |                57.67 |                   42.33 |           61.58 |             80.47 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.74 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|            5 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    69.66 |                 69.69 |              70.61 |                62.46 |                   37.54 |           70.56 |             63.78 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                  | US       |              110.91 |                  61.82 |                    67.66 |                 69.55 |              64.81 |                76.36 |                   23.64 |           81.79 |             65.54 |     nan     |         nan |       nan |      nan    |         9.48 |         13.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  74.83 |                    69.14 |                 69.37 |              70.59 |                68.7  |                   31.3  |           75.5  |             43.43 |       0.612 |         nan |       nan |        4.72 |      -132.26 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | MU       | MU                                   | US       |             1079.84 |                  48.25 |                    63.61 |                 69.17 |              56.58 |                77.05 |                   22.95 |           95.76 |             79.72 |     nan     |         nan |       nan |      nan    |         6.9  |         23.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | STNE     | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.17 |                    69.44 |                 69.01 |              67.46 |                68.16 |                   31.84 |           85.87 |             32.29 |       0.608 |         nan |       nan |        1.62 |         4.3  |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | VLO      | VLO                                  | US       |               94.72 |                  50.67 |                    64.57 |                 69.01 |              59.45 |                82.26 |                   17.74 |           86.55 |             81.53 |     nan     |         nan |       nan |      nan    |        10.12 |         16.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                  | US       |               14.68 |                  54.9  |                    65.46 |                 68.91 |              60.94 |                79.37 |                   20.63 |           86.44 |             71.23 |     nan     |         nan |       nan |      nan    |        10.42 |         22.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | MPC      | MPC      | US       |               95.45 |                     0.08 |    -0.05 |      0.07 |                  68.18 |                        84.83 |         76.79 |         88.1  |          88.29 |        84.39 |           85.53 |             89.65 |         4.26 |
|               2 | PSX      | PSX      | US       |               89.8  |                     0.06 |    -0.03 |      0.06 |                  74.5  |                        82.74 |         76.81 |         85.17 |          83.37 |        78.44 |           81.12 |             85.05 |         3.77 |
|               3 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.89 |                     0.07 |    -0.02 |      0.11 |                  70.51 |                        82.02 |         78.39 |         81.33 |          84.18 |        82.4  |           96.34 |             76.76 |         3.62 |
|               4 | VLO      | VLO      | US       |               94.72 |                     0.09 |    -0.05 |      0.09 |                  65.45 |                        81.91 |         76.57 |         85.1  |          85.09 |        80.58 |           86.55 |             81.53 |         3.56 |
|               5 | FRO      | FRO      | US       |                9.31 |                     0.08 |    -0.02 |      0.15 |                  62.78 |                        81.39 |         82.97 |         79.87 |          83.6  |        81.22 |           92.18 |             80.34 |         5.53 |
|               6 | DELL     | DELL     | US       |              304.42 |                     0.06 |     0.02 |      0.28 |                  63.22 |                        81.29 |         88.14 |         84.55 |          80.75 |        68    |           74.35 |             85.81 |         7.82 |
|               7 | DHT      | DHT      | US       |                3.01 |                     0.08 |    -0.03 |      0.09 |                  64.88 |                        78.67 |         77.12 |         75.59 |          80.69 |        81.36 |           89.85 |             82.72 |         4.68 |
|               8 | NAT      | NAT      | US       |                1.41 |                     0.07 |    -0.03 |      0.13 |                  66.91 |                        78.19 |         80.22 |         77.3  |          78.18 |        72.9  |           87.98 |             69.63 |         4.8  |
|               9 | SHELL.AS | SHELL.AS | EUROPE   |              235.22 |                     0.04 |    -0.02 |      0.04 |                  63.11 |                        77.74 |         74.65 |         73.07 |          73.52 |        79.66 |           93.79 |             81.24 |         2.4  |
|              10 | GH       | GH       | US       |               20.74 |                     0.03 |     0.01 |      0.09 |                  54.36 |                        77.25 |         78.47 |         86.45 |          83.61 |        76.36 |           63.45 |             87.88 |         6.99 |
|              11 | AVAH     | AVAH     | US       |                2.52 |                     0.09 |    -0.08 |     -0.04 |                  74.89 |                        76.37 |         56.81 |         76.8  |          77.61 |        72.91 |           92.73 |             54.62 |         7.71 |
|              12 | BP       | BP       | US       |               96.82 |                     0.07 |    -0.07 |     -0    |                  81.04 |                        75.67 |         61.74 |         66.5  |          71.53 |        78.07 |           87.6  |             84.99 |         4.49 |
|              13 | SHEL     | SHEL     | US       |              233.82 |                     0.05 |    -0.05 |      0.01 |                  82.99 |                        75.1  |         67.16 |         70.96 |          71.1  |        77.06 |           76.28 |             79.48 |         3.02 |
|              14 | DAR      | DAR      | US       |                8.48 |                     0.1  |    -0.08 |     -0.02 |                  67.9  |                        74.79 |         52.9  |         67.27 |          77.87 |        83.32 |           90.85 |             85.37 |         4.62 |
|              15 | DINO     | DINO     | US       |               16.54 |                     0.1  |    -0.06 |      0.1  |                  62.23 |                        74.66 |         70.6  |         84.28 |          79.41 |        71.17 |           51.03 |             86.56 |         4.56 |
|              16 | C5H.IR   | C5H.IR   | EUROPE   |                1.66 |                     0.05 |    -0.01 |      0.06 |                  71.26 |                        74.56 |         72.75 |         65.13 |          70.63 |        74.72 |           97.85 |             52.84 |         2.67 |
|              17 | MT.AS    | MT.AS    | EUROPE   |               47.99 |                     0.06 |    -0.01 |     -0.01 |                  74.57 |                        74.51 |         61.43 |         73.91 |          77.07 |        74.11 |           71.88 |             79.94 |         4.96 |
|              18 | BIRG.IR  | BIRG.IR  | EUROPE   |               18.76 |                     0.03 |    -0.02 |      0.04 |                  59.98 |                        74.12 |         71.8  |         70.18 |          73.69 |        76.1  |           96.63 |             65.97 |         2.22 |
|              19 | EQNR     | EQNR     | US       |               86.45 |                     0.1  |    -0.1  |     -0.03 |                  72.7  |                        74.02 |         53.72 |         70.76 |          74.05 |        75.25 |           76.16 |             83.38 |         5.58 |
|              20 | APA      | APA      | US       |               12.93 |                     0.11 |    -0.11 |     -0.01 |                  68.9  |                        73.59 |         58.11 |         71.59 |          75.42 |        78.66 |           77.25 |             80.08 |         5.94 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              347.91 |             41.43 |         39.25 |          34.4 |           43.6 |        50.37 |           77.39 |              44.8 |                26 |          8.5 |             89.81 | long               |                0.58 |                  1.27 |                 1.25 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    199 | ITRG     | ITRG                | US       |                0.51 |             62.63 |         65.83 |         59.43 |          57.78 |        66.42 |           60.49 |             63.55 |             85.24 |         8.18 |             68.32 | long               |                6.83 |                  5.82 |                 5.82 |
|     22 | AMS.SW   | AMS.SW              | EUROPE   |                2.43 |             75.88 |         85.39 |         81.61 |          70.15 |        51.95 |           53.45 |             88.21 |              8.97 |         8.66 |             73.14 | short              |                4.8  |                  5.25 |               nan    |
|      8 | AMC      | AMC                 | US       |                2.31 |             81.16 |         82.2  |         86.66 |          80.13 |        79.58 |           85.57 |             78.76 |            nan    |         9.56 |             65.07 | swing              |                4.97 |                  4.45 |                 4.12 |
|    195 | VZLA     | VZLA                | US       |                1.33 |             62.76 |         76.5  |         67.89 |          57.63 |        54.12 |           60.63 |            nan    |             39.59 |         8.36 |             61.82 | short              |                5.25 |                  4.43 |               nan    |
|    280 | IHS      | IHS Holding Limited | OTHER    |                2.49 |             59.57 |         63.85 |         56.31 |          57.71 |        61.43 |           55.59 |             78.38 |             64.23 |         2.06 |             72.86 | short              |               -0.64 |                  4.1  |                 4.16 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                  | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    703 | MGPI     | MGP Ingredients, Inc. | US       |                0.25 |             25.16 |         22.5  |         20.39 |          27.81 |        36.49 |           43.7  |             25.97 |             45.6  |         6.21 |             84.71 | long               |                0.37 |                 -3.36 |               nan    |
|    426 | TEVA     | TEVA                  | US       |               40.2  |             52.98 |         66.77 |         58.52 |          47.43 |        38.66 |           12.91 |             29.43 |             47.59 |         4.7  |             72.34 | short              |               -2.03 |                 -3.35 |                -3.5  |
|    584 | FRSH     | FRSH                  | US       |                2.83 |             44.32 |         38.07 |         57.72 |          47.87 |        40.77 |           30.89 |             30.35 |             43.3  |         7.6  |             72.11 | swing              |               -2.07 |                 -2.86 |                -2.18 |
|    626 | BAS.DE   | BAS.DE                | EUROPE   |               44.68 |             41.47 |         54.52 |         44.83 |          38.11 |        34.4  |           28.14 |             29.56 |             27.49 |         2.05 |             67.86 | short              |                0.22 |                 -2.81 |               nan    |
|    372 | STR.VI   | STR.VI                | EUROPE   |               12.21 |             55.22 |         76.32 |         60.73 |          49.71 |        42.72 |          nan    |             33.07 |             29.7  |         5.45 |             66.84 | short              |               -0.89 |                 -2.53 |               nan    |

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
| VLO | 3 |  | 4 |  | 2 | main,pullback |
| DELL | 5 |  | 6 |  | 2 | main,pullback |
| FRO | 6 |  | 5 |  | 2 | main,pullback |
| CMBT.BR | 7 |  | 3 |  | 2 | main,pullback |
| GH | 9 |  | 10 |  | 2 | main,pullback |
| PSX | 10 |  | 2 |  | 2 | main,pullback |
| PARR | 32 | 4 | 22 | 3 | 1 | value,quality_value |
| PBR-A | 43 | 3 | 23 | 4 | 1 | value,quality_value |
| NVDA | 58 | 2 |  | 2 | 1 | value,quality_value |
| EMBC | 165 | 5 |  | 5 | 1 | value,quality_value |
| BION.SW | 181 | 1 | 107 | 1 | 1 | value,quality_value |
| 0Q2N.IL | 229 | 9 |  | 10 | 1 | value,quality_value |
| NWL.MI | 249 | 8 | 50 | 6 | 1 | value,quality_value |
| AVGO | 290 | 10 |  | 8 | 1 | value,quality_value |

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
| 1 | NWL.MI | value+pullback | 71.44 | 74.83 | 78.32 | 75.50 | 43.43 | 68.70 | 60.64 |
| 2 | BION.SW | value+pullback | 71.01 | 73.97 | 51.93 | 84.64 | 57.97 | 86.73 | 63.35 |
| 3 | PARR | value+pullback | 69.84 | 68.48 | 65.86 | 80.43 | 70.24 | 68.71 | 74.19 |
| 4 | PBR-A | value+pullback | 68.69 | 75.89 | 68.43 | 61.58 | 80.47 | 57.67 | 73.13 |
| 5 | 0Q2N.IL | value+pullback | 67.90 | 71.06 | 73.79 | 61.12 |  | 69.85 | 61.54 |
| 6 | STNE | value+pullback | 66.99 | 72.17 | 62.40 | 85.87 | 32.29 | 68.16 | 49.36 |
| 7 | VOLV-B.ST | value+pullback | 66.57 | 74.09 | 72.10 | 55.24 | 60.62 | 59.84 | 54.18 |
| 8 | GSL | value+pullback | 65.82 | 70.19 | 59.10 | 77.16 | 30.43 | 76.85 | 62.58 |
| 9 | BCE | value+pullback | 65.46 | 59.29 | 73.54 | 80.43 | 57.50 | 57.35 | 43.76 |
| 10 | CNC | value+pullback | 63.33 | 71.92 | 69.23 | 50.47 | 64.38 | 52.21 | 60.04 |
| 11 | INVA | value+pullback | 63.32 | 63.47 | 45.55 | 90.78 | 31.37 | 80.70 | 51.05 |
| 12 | UNIT | value+pullback | 63.06 | 80.01 | 70.08 | 64.98 | 29.04 | 44.43 | 42.96 |
| 13 | WB | value+pullback | 62.48 | 71.47 | 64.82 | 73.42 | 17.58 | 60.33 | 40.67 |
| 14 | RCI | value+pullback | 62.47 | 64.38 | 55.10 | 89.13 | 42.73 | 58.69 | 42.45 |
| 15 | HMC | value+pullback | 61.51 | 57.07 | 46.50 | 75.65 | 81.35 | 66.42 | 69.05 |
| 16 | IRS | value+pullback | 61.15 | 68.25 | 60.56 | 61.40 | 40.96 | 61.14 | 51.40 |
| 17 | PERI | value+pullback | 59.25 | 66.14 | 47.60 | 50.87 | 74.29 | 62.26 | 43.03 |
| 18 | ORC | value+pullback | 58.90 | 60.76 | 55.47 | 75.90 | 34.98 | 59.62 | 41.45 |
| 19 | BP | pullback | 58.31 | 57.34 | 81.04 | 87.60 | 84.99 | 82.06 | 69.01 |
| 20 | CMBT.BR | pullback | 56.85 | 57.24 | 70.51 | 96.34 | 76.76 | 85.50 | 81.87 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 8/10 | 8/10 | 0/10 | 72.7 | 4 / 6 |
| Top 25 | 25/25 | 24/25 | 23/25 | 22/25 | 0/25 | 72.7 | 8 / 17 |
| Top 50 | 50/50 | 48/50 | 48/50 | 46/50 | 0/50 | 72.7 | 22 / 28 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=1, large_20_100b=5, mega_100b_plus=2
