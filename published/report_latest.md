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

- **EUROPE:** 80.2/100
- **OTHER:** 70.9/100
- **US:** 82.5/100

## Main multi-horizon ranking

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC     | US       |               95.45 |             86.28 |         76.72 |         88.16 |          88.33 |        84.41 |           85.43 |             89.78 |             71.8  |         4.19 |             73.14 | medium             |               -0.86 |                nan    |               nan    |
|      2 | MU       | MU      | US       |             1079.84 |             83.81 |         82.13 |         75.76 |          86.38 |        85.5  |           95.67 |             80.4  |             71.24 |         8.2  |             73.14 | medium             |                3.05 |                  2.98 |                 2.29 |
|      3 | VLO      | VLO     | US       |               94.72 |             82.87 |         76.51 |         85.06 |          85.07 |        80.68 |           86.48 |             81.31 |             60.45 |         3.55 |             69.68 | medium             |               -2.87 |                  1.11 |                 1.01 |
|      4 | DELL     | DELL    | US       |              304.42 |             82.55 |         87.8  |         84.43 |          80.66 |        67.91 |           74.26 |             85.48 |             29.34 |         7.79 |             72.23 | short              |               -1.07 |                  0.06 |                -0.11 |
|      5 | CMBT.BR  | CMBT.BR | EUROPE   |                4.96 |             82.02 |         81.92 |         81.9  |          84.27 |        82.13 |           96.42 |             77.02 |             60.67 |         3.74 |             73.14 | medium             |               -2.16 |                  1.17 |                 1.13 |
|      6 | FRO      | FRO     | US       |                9.31 |             81.91 |         82.58 |         79.77 |          83.54 |        81.24 |           92.02 |             79.77 |             59.14 |         5.47 |             73.14 | medium             |               -3.01 |                  0.51 |                 0.46 |
|      7 | AMC      | AMC     | US       |                2.31 |             81.08 |         82.08 |         86.66 |          80.08 |        79.45 |           85.27 |             78.67 |            nan    |         9.55 |             65.07 | swing              |                4.89 |                  4.44 |                 4.11 |
|      8 | PSX      | PSX     | US       |               89.8  |             80.95 |         76.64 |         85.18 |          83.39 |        78.52 |           80.93 |             85    |             59.97 |         3.72 |             73.14 | swing              |               -2.91 |                  1.18 |                 1.22 |
|      9 | HPE      | HPE     | US       |               70.67 |             80.86 |         88.32 |         82.2  |          79.52 |        71.64 |           74.93 |             72.75 |             50.43 |         6.94 |             72.34 | short              |               -0.49 |                  0.21 |               nan    |
|     10 | GH       | GH      | US       |               20.74 |             80.83 |         78.04 |         86.44 |          83.61 |        76.35 |           63.45 |             87.87 |            nan    |         6.95 |             68.36 | swing              |              nan    |                nan    |               nan    |
|     11 | HSHP     | HSHP    | US       |                0.75 |             80.2  |         82.85 |         80.79 |          79.62 |        70.58 |           87.07 |            nan    |             29.92 |         4.79 |             62.84 | short              |               -2.6  |                nan    |               nan    |
|     12 | DHT      | DHT     | US       |                3.01 |             78.91 |         77.05 |         75.7  |          80.78 |        81.51 |           89.64 |             83.04 |             65.17 |         4.63 |             73.14 | long               |               -3.15 |                  0.5  |                 0.26 |
|     13 | TRMD     | TRMD    | US       |                3.1  |             78.47 |         81.07 |         74.23 |          75.99 |        80.94 |           86.18 |             46.95 |             84.94 |         5.41 |             69.68 | short              |              nan    |                nan    |               nan    |
|     14 | OKTA     | OKTA    | US       |               29.98 |             78.2  |         89.98 |         84.08 |          72.33 |        59.18 |           70.07 |             68.39 |             14.45 |         7.77 |             72.11 | short              |               -0.32 |                  0.89 |                 0.89 |
|     15 | HALO     | HALO    | US       |               11.4  |             78.12 |         80.82 |         81.37 |          75.41 |        72.11 |           87.62 |             51.19 |             48.18 |         5.88 |             72.11 | swing              |                2.01 |                nan    |               nan    |
|     16 | NAT      | NAT     | US       |                1.41 |             77.76 |         80.13 |         77.31 |          78.21 |        72.89 |           87.79 |             69.84 |             38.35 |         4.74 |             73.14 | short              |               -2.81 |                 -0.07 |                 0.02 |
|     17 | FSM      | FSM     | US       |                3.15 |             77.54 |         71.74 |         77.4  |          77.68 |        80.87 |           80.54 |             70.67 |             83.61 |         7.19 |             73.14 | long               |                2.17 |                  3.52 |                 2.99 |
|     18 | KIN.BR   | KIN.BR  | EUROPE   |                1.36 |             77.15 |         79.54 |         80.41 |          74.77 |        65.37 |           90.47 |             63.89 |             16.8  |         3.68 |             73.14 | swing              |               -0.6  |                 -0.31 |                -0.24 |
|     19 | P        | P       | US       |               32.23 |             76.91 |         87.98 |         82.68 |          71.13 |        58.62 |           72.21 |             85.73 |             11.48 |         8.11 |             72.68 | short              |               -0.46 |                  2.46 |                 1.77 |
|     20 | UGP      | UGP     | US       |                7.15 |             76.01 |         78.35 |         82.61 |          73.68 |        66.72 |           60.31 |             67.34 |             56.36 |         4.59 |             72.11 | swing              |               -0.45 |                  0.77 |                 0.29 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.06 |                  73.97 |                    74.49 |                 76.17 |              74.69 |                86.8  |                   13.2  |           84.64 |             58.02 |       0.858 |         nan |       nan |      nan    |       -79.36 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              234.07 |                  59    |                    71.51 |                 75.49 |              66.53 |                88.31 |                   11.69 |           93.87 |             81.54 |     nan     |         nan |       nan |      nan    |         9.35 |         10.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL      | SHEL                                 | US       |              233.82 |                  66.67 |                    71.25 |                 72.61 |              69.95 |                77.61 |                   22.39 |           76.02 |             79.75 |     nan     |         nan |       nan |      nan    |         9.07 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA      | NVIDIA Corporation                   | US       |             4820.51 |                  60.87 |                    70.81 |                 72.82 |              65.84 |                77.6  |                   22.4  |           86.9  |             80.43 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.93 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT       | DHT                                  | US       |                3.01 |                  59.54 |                    70.34 |                 73.99 |              65.96 |                82.17 |                   17.83 |           89.64 |             83.04 |     nan     |         nan |       nan |      nan    |         9.97 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  75.89 |                    70.21 |                 70.28 |              73.08 |                57.73 |                   42.27 |           61.58 |             80.51 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.74 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.96 |                  57.14 |                    69.9  |                 74.18 |              64.22 |                85.39 |                   14.61 |           96.42 |             77.02 |     nan     |         nan |       nan |      nan    |         9.44 |          6.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.46 |                  68.48 |                    69.82 |                 71.79 |              68.72 |                68.78 |                   31.22 |           80.43 |             70.33 |       0.021 |         nan |       nan |        3.86 |         5.72 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | EMBC      | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    69.7  |                 69.75 |              70.65 |                62.53 |                   37.47 |           70.56 |             64.07 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | STNE      | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.17 |                    69.46 |                 69.04 |              67.49 |                68.19 |                   31.81 |           85.87 |             32.45 |       0.608 |         nan |       nan |        1.62 |         4.3  |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM        | SM                                   | US       |                7.04 |                  62.65 |                    69.19 |                 71.72 |              66.07 |                72.69 |                   27.31 |           83.24 |             78.78 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | BBWI      | Bath & Body Works, Inc.              | US       |                3.02 |                  74.85 |                    69.18 |                 66.73 |              68.01 |                59.33 |                   40.67 |           75.98 |             34.36 |       0.221 |         nan |       nan |        5.64 |         6.16 |          4.44 |        0.69 |                 nan |              nan |                  11 |                  0.58 |
|            8 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.77 |                  74.83 |                    69.16 |                 69.39 |              70.6  |                68.75 |                   31.25 |           75.5  |             43.51 |       0.602 |         nan |       nan |        4.72 |      -134.45 |          2.32 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            9 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.18 |                  71.06 |                    69.11 |                 67.94 |              70.83 |                69.92 |                   30.08 |           61.12 |            nan    |       0.233 |         nan |       nan |        1.54 |       nan    |          2.96 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BP        | BP                                   | US       |               96.82 |                  57.31 |                    68.94 |                 72.77 |              64.57 |                82.2  |                   17.8  |           87.55 |             85.09 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                                  | US       |                9.31 |                  56.33 |                    68.27 |                 72.41 |              63.05 |                80.64 |                   19.36 |           92.02 |             79.77 |     nan     |         nan |       nan |      nan    |        10.47 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | AVGO      | Broadcom Inc.                        | US       |             1517.87 |                  60.81 |                    68.25 |                 68.82 |              62.32 |                78.55 |                   21.45 |           92.29 |             44    |       0.018 |         nan |       nan |       33.98 |        18.81 |         46.56 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | TTE.PA    | TTE.PA                               | EUROPE   |              172.64 |                  64.15 |                    67.99 |                 69.02 |              67.25 |                74.13 |                   25.87 |           69.83 |             77.17 |     nan     |         nan |       nan |      nan    |         8.83 |         11.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               60.32 |                  74.09 |                    67.95 |                 65.25 |              70.2  |                59.93 |                   40.07 |           55.24 |             60.72 |       0.035 |         nan |       nan |       15.88 |        13.4  |         18.94 |        0.96 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY       | BMY                                  | US       |              110.91 |                  61.82 |                    67.64 |                 69.51 |              64.83 |                76.34 |                   23.66 |           81.5  |             65.76 |     nan     |         nan |       nan |      nan    |         9.48 |         13.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  73.97 |                    74.49 |                 76.17 |              74.69 |                86.8  |                   13.2  |           84.64 |             58.02 |       0.858 |         nan |       nan |      nan    |       -79.36 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              234.07 |                  59    |                    71.51 |                 75.49 |              66.53 |                88.31 |                   11.69 |           93.87 |             81.54 |     nan     |         nan |       nan |      nan    |         9.35 |         10.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.96 |                  57.14 |                    69.9  |                 74.18 |              64.22 |                85.39 |                   14.61 |           96.42 |             77.02 |     nan     |         nan |       nan |      nan    |         9.44 |          6.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.01 |                  59.54 |                    70.34 |                 73.99 |              65.96 |                82.17 |                   17.83 |           89.64 |             83.04 |     nan     |         nan |       nan |      nan    |         9.97 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA     | NVIDIA Corporation                   | US       |             4820.51 |                  60.87 |                    70.81 |                 72.82 |              65.84 |                77.6  |                   22.4  |           86.9  |             80.43 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.93 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP       | BP                                   | US       |               96.82 |                  57.31 |                    68.94 |                 72.77 |              64.57 |                82.2  |                   17.8  |           87.55 |             85.09 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              233.82 |                  66.67 |                    71.25 |                 72.61 |              69.95 |                77.61 |                   22.39 |           76.02 |             79.75 |     nan     |         nan |       nan |      nan    |         9.07 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.31 |                  56.33 |                    68.27 |                 72.41 |              63.05 |                80.64 |                   19.36 |           92.02 |             79.77 |     nan     |         nan |       nan |      nan    |        10.47 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.46 |                  68.48 |                    69.82 |                 71.79 |              68.72 |                68.78 |                   31.22 |           80.43 |             70.33 |       0.021 |         nan |       nan |        3.86 |         5.72 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM       | SM                                   | US       |                7.04 |                  62.65 |                    69.19 |                 71.72 |              66.07 |                72.69 |                   27.31 |           83.24 |             78.78 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.82 |                  53.33 |                    66.58 |                 70.91 |              60.35 |                85.22 |                   14.78 |           96.81 |             66.18 |     nan     |         nan |       nan |      nan    |        10.88 |         14.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                                  | US       |               95.45 |                  51.39 |                    65.81 |                 70.41 |              60.93 |                83.1  |                   16.9  |           85.43 |             89.78 |     nan     |         nan |       nan |      nan    |         8.27 |         13.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  75.89 |                    70.21 |                 70.28 |              73.08 |                57.73 |                   42.27 |           61.58 |             80.51 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.74 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|            5 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    69.7  |                 69.75 |              70.65 |                62.53 |                   37.47 |           70.56 |             64.07 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                  | US       |              110.91 |                  61.82 |                    67.64 |                 69.51 |              64.83 |                76.34 |                   23.66 |           81.5  |             65.76 |     nan     |         nan |       nan |      nan    |         9.48 |         13.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.77 |                  74.83 |                    69.16 |                 69.39 |              70.6  |                68.75 |                   31.25 |           75.5  |             43.51 |       0.602 |         nan |       nan |        4.72 |      -134.45 |          2.32 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | MU       | MU                                   | US       |             1079.84 |                  48.12 |                    63.63 |                 69.22 |              56.6  |                77.26 |                   22.74 |           95.67 |             80.4  |     nan     |         nan |       nan |      nan    |         6.9  |         24.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | STNE     | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.17 |                    69.46 |                 69.04 |              67.49 |                68.19 |                   31.81 |           85.87 |             32.45 |       0.608 |         nan |       nan |        1.62 |         4.3  |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              172.64 |                  64.15 |                    67.99 |                 69.02 |              67.25 |                74.13 |                   25.87 |           69.83 |             77.17 |     nan     |         nan |       nan |      nan    |         8.83 |         11.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                                  | US       |               94.72 |                  50.78 |                    64.59 |                 68.99 |              59.48 |                82.17 |                   17.83 |           86.48 |             81.31 |     nan     |         nan |       nan |      nan    |        10.12 |         15.72 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | MPC       | MPC       | US       |               95.45 |                     0.08 |    -0.05 |      0.07 |                  68.18 |                        84.86 |         76.72 |         88.16 |          88.33 |        84.41 |           85.43 |             89.78 |         4.19 |
|               2 | PSX       | PSX       | US       |               89.8  |                     0.06 |    -0.03 |      0.06 |                  74.5  |                        82.7  |         76.64 |         85.18 |          83.39 |        78.52 |           80.93 |             85    |         3.72 |
|               3 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.96 |                     0.05 |     0.01 |      0.1  |                  68.66 |                        82.1  |         81.92 |         81.9  |          84.27 |        82.13 |           96.42 |             77.02 |         3.74 |
|               4 | VLO       | VLO       | US       |               94.72 |                     0.09 |    -0.05 |      0.09 |                  65.45 |                        81.84 |         76.51 |         85.06 |          85.07 |        80.68 |           86.48 |             81.31 |         3.55 |
|               5 | FRO       | FRO       | US       |                9.31 |                     0.08 |    -0.02 |      0.15 |                  62.78 |                        81.07 |         82.58 |         79.77 |          83.54 |        81.24 |           92.02 |             79.77 |         5.47 |
|               6 | DELL      | DELL      | US       |              304.42 |                     0.06 |     0.02 |      0.28 |                  63.22 |                        81.06 |         87.8  |         84.43 |          80.66 |        67.91 |           74.26 |             85.48 |         7.79 |
|               7 | DHT       | DHT       | US       |                3.01 |                     0.08 |    -0.03 |      0.09 |                  64.88 |                        78.64 |         77.05 |         75.7  |          80.78 |        81.51 |           89.64 |             83.04 |         4.63 |
|               8 | SHELL.AS  | SHELL.AS  | EUROPE   |              234.07 |                     0.04 |    -0.04 |      0.03 |                  73.9  |                        78.4  |         72.44 |         72.63 |          73.87 |        79.74 |           93.87 |             81.54 |         2.36 |
|               9 | NAT       | NAT       | US       |                1.41 |                     0.07 |    -0.03 |      0.13 |                  66.91 |                        78.14 |         80.13 |         77.31 |          78.21 |        72.89 |           87.79 |             69.84 |         4.74 |
|              10 | GH        | GH        | US       |               20.74 |                     0.03 |     0.01 |      0.09 |                  54.36 |                        77.24 |         78.04 |         86.44 |          83.61 |        76.35 |           63.45 |             87.87 |         6.95 |
|              11 | AVAH      | AVAH      | US       |                2.52 |                     0.09 |    -0.08 |     -0.04 |                  74.89 |                        76.34 |         56.42 |         76.75 |          77.64 |        72.96 |           92.66 |             54.62 |         7.68 |
|              12 | BP        | BP        | US       |               96.82 |                     0.07 |    -0.07 |     -0    |                  81.04 |                        75.62 |         61.47 |         66.38 |          71.62 |        78.24 |           87.55 |             85.09 |         4.42 |
|              13 | SHEL      | SHEL      | US       |              233.82 |                     0.05 |    -0.05 |      0.01 |                  82.99 |                        75.03 |         66.91 |         70.83 |          71.19 |        77.22 |           76.02 |             79.75 |         2.96 |
|              14 | DAR       | DAR       | US       |                8.48 |                     0.1  |    -0.08 |     -0.02 |                  67.9  |                        74.77 |         52.6  |         67.26 |          77.9  |        83.45 |           90.66 |             85.51 |         4.57 |
|              15 | DINO      | DINO      | US       |               16.54 |                     0.1  |    -0.06 |      0.1  |                  62.23 |                        74.67 |         70.56 |         84.34 |          79.46 |        71.27 |           50.9  |             86.54 |         4.52 |
|              16 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.82 |                     0.02 |     0    |      0.04 |                  48    |                        74.28 |         75.58 |         71.42 |          74.45 |        75.9  |           96.81 |             66.18 |         2.16 |
|              17 | EQNR      | EQNR      | US       |               86.45 |                     0.1  |    -0.1  |     -0.03 |                  72.7  |                        74.1  |         53.54 |         70.79 |          74.19 |        75.52 |           76.32 |             83.59 |         5.51 |
|              18 | FORTUM.HE | FORTUM.HE | EUROPE   |               21.14 |                     0.05 |    -0.01 |      0.16 |                  68.4  |                        73.8  |         79.62 |         67.28 |          59.56 |        54.01 |           69.23 |             65.87 |         4.5  |
|              19 | ARGX.BR   | ARGX.BR   | EUROPE   |               53.2  |                     0.06 |    -0    |     -0.03 |                  67.36 |                        73.64 |         60.36 |         66.74 |          69.49 |        62.17 |           94.23 |             75.48 |         6.02 |
|              20 | APA       | APA       | US       |               12.93 |                     0.11 |    -0.11 |     -0.01 |                  68.9  |                        73.52 |         57.93 |         71.51 |          75.4  |        78.73 |           76.86 |             80.37 |         5.88 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              347.91 |             41.23 |         38.77 |         34.38 |          43.68 |        50.44 |           77.39 |             44.92 |                26 |          8.5 |             89.81 | long               |                0.38 |                  1.23 |                 1.22 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    246 | ITRG     | ITRG                | OTHER    |                0.51 |             60.85 |         65.05 |         57.58 |          56.92 |        64.12 |           70.58 |             63.2  |             66.08 |         8.17 |             68.32 | short              |                5.05 |                  5.46 |                 5.55 |
|     46 | AMS.SW   | AMS.SW              | EUROPE   |                2.26 |             72.83 |         82.32 |         75.47 |          70.19 |        53.32 |           55.46 |             88.24 |             11.68 |         8.64 |             73.14 | short              |                1.76 |                  4.64 |               nan    |
|    193 | VZLA     | VZLA                | US       |                1.33 |             62.93 |         76.41 |         67.96 |          57.9  |        54.43 |           60.72 |            nan    |             40.16 |         8.34 |             61.82 | short              |                5.42 |                  4.46 |               nan    |
|      7 | AMC      | AMC                 | US       |                2.31 |             81.08 |         82.08 |         86.66 |          80.08 |        79.45 |           85.27 |             78.67 |            nan    |         9.55 |             65.07 | swing              |                4.89 |                  4.44 |                 4.11 |
|    273 | IHS      | IHS Holding Limited | OTHER    |                2.49 |             59.68 |         63.18 |         56.32 |          57.82 |        61.53 |           55.59 |             78.45 |             64.23 |         2.04 |             72.86 | short              |               -0.53 |                  4.12 |                 4.18 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                  | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    658 | SAF.PA   | SAF.PA                | EUROPE   |              137.57 |             37.74 |         48.85 |         36.85 |          38.62 |        35.85 |           53.2  |             20.1  |              5.7  |         3.9  |             73.14 | short              |              nan    |                 -3.41 |               nan    |
|    699 | MGPI     | MGP Ingredients, Inc. | US       |                0.25 |             25.12 |         22.43 |         20.35 |          27.8  |        36.5  |           43.7  |             26    |             45.6  |         6.18 |             84.71 | long               |                0.33 |                 -3.37 |               nan    |
|    423 | TEVA     | TEVA                  | US       |               40.2  |             53.02 |         66.39 |         58.55 |          47.48 |        38.7  |           12.8  |             29.29 |             47.93 |         4.65 |             72.34 | short              |               -1.99 |                 -3.34 |                -3.5  |
|    584 | FRSH     | FRSH                  | US       |                2.83 |             44.31 |         37.87 |         57.62 |          47.89 |        40.74 |           30.51 |             30.39 |             43.58 |         7.57 |             72.11 | swing              |               -2.09 |                 -2.86 |                -2.18 |
|    612 | BAS.DE   | BAS.DE                | EUROPE   |               44.59 |             42.41 |         54.98 |         45.41 |          39.42 |        35.59 |           31.31 |             29.91 |             26.24 |         2.01 |             67.86 | short              |                1.17 |                 -2.63 |               nan    |

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
- Excluded by hard/data filters: **297**
- Event watch (otherwise eligible): **1**
- Final eligible: **702**
- Eligible change vs previous stored run: **-7**

Top exclusion categories:
- liquidity: 239
- price: 186
- market_cap: 167
- price_history: 18
- data_confidence: 10
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 1 |  | 2 | main,pullback |
| VLO | 3 |  | 4 |  | 2 | main,pullback |
| DELL | 4 |  | 6 |  | 2 | main,pullback |
| CMBT.BR | 5 |  | 3 |  | 2 | main,pullback |
| FRO | 6 |  | 5 |  | 2 | main,pullback |
| PSX | 8 |  | 2 |  | 2 | main,pullback |
| GH | 10 |  | 10 |  | 2 | main,pullback |
| PARR | 30 | 4 | 21 | 3 | 1 | value,quality_value |
| PBR-A | 40 | 3 | 23 | 4 | 1 | value,quality_value |
| NVDA | 60 | 2 |  | 2 | 1 | value,quality_value |
| EMBC | 164 | 5 |  | 5 | 1 | value,quality_value |
| BION.SW | 191 | 1 | 101 | 1 | 1 | value,quality_value |
| NWL.MI | 214 | 8 |  | 6 | 1 | value,quality_value |
| 0Q2N.IL | 218 | 9 |  | 10 | 1 | value,quality_value |
| AVGO | 281 | 10 |  | 8 | 1 | value,quality_value |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (MU, DELL, CMBT.BR, FRO, AMC, HPE, GH)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **5** (CMBT.BR, FRO, DELL, NAT, GH)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 71.31 | 73.97 | 53.02 | 84.64 | 58.02 | 86.80 | 62.95 |
| 2 | PARR | value+pullback | 69.86 | 68.48 | 65.86 | 80.43 | 70.33 | 68.78 | 74.55 |
| 3 | PBR-A | value+pullback | 68.71 | 75.89 | 68.43 | 61.58 | 80.51 | 57.73 | 73.45 |
| 4 | STNE | value+pullback | 67.02 | 72.17 | 62.40 | 85.87 | 32.45 | 68.19 | 49.25 |
| 5 | 0Q2N.IL | value+pullback | 65.73 | 71.06 | 65.06 | 61.12 |  | 69.92 | 61.72 |
| 6 | GSL | value+pullback | 65.53 | 69.15 | 59.10 | 77.16 | 30.53 | 76.91 | 62.31 |
| 7 | BCE | value+pullback | 65.50 | 59.29 | 73.54 | 80.43 | 57.72 | 57.47 | 43.84 |
| 8 | VOLV-B.ST | value+pullback | 64.81 | 74.09 | 64.97 | 55.24 | 60.72 | 59.93 | 55.69 |
| 9 | CNC | value+pullback | 63.38 | 71.92 | 69.23 | 50.47 | 64.65 | 52.30 | 60.10 |
| 10 | INVA | value+pullback | 63.33 | 63.47 | 45.55 | 90.78 | 31.35 | 80.75 | 50.85 |
| 11 | UNIT | value+pullback | 63.06 | 80.01 | 70.08 | 64.98 | 29.00 | 44.48 | 42.92 |
| 12 | RCI | value+pullback | 62.50 | 64.38 | 55.10 | 89.13 | 42.87 | 58.77 | 42.54 |
| 13 | WB | value+pullback | 62.49 | 71.47 | 64.82 | 73.42 | 17.57 | 60.38 | 40.47 |
| 14 | HMC | value+pullback | 61.54 | 57.07 | 46.50 | 75.65 | 81.49 | 66.49 | 69.41 |
| 15 | IRS | value+pullback | 61.17 | 68.25 | 60.56 | 61.40 | 41.05 | 61.22 | 51.50 |
| 16 | PERI | value+pullback | 59.29 | 66.14 | 47.60 | 50.87 | 74.50 | 62.35 | 43.15 |
| 17 | ORC | value+pullback | 58.91 | 60.76 | 55.47 | 75.90 | 34.91 | 59.67 | 41.33 |
| 18 | SHELL.AS | pullback | 58.37 | 59.00 | 73.90 | 93.87 | 81.54 | 88.31 | 73.25 |
| 19 | BP | pullback | 58.34 | 57.31 | 81.04 | 87.55 | 85.09 | 82.20 | 69.00 |
| 20 | JD | value+pullback | 56.66 | 58.74 | 59.80 | 57.39 | 46.45 | 54.15 | 45.36 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 8/10 | 8/10 | 0/10 | 72.7 | 3 / 7 |
| Top 25 | 25/25 | 24/25 | 23/25 | 22/25 | 0/25 | 72.7 | 9 / 16 |
| Top 50 | 50/50 | 49/50 | 48/50 | 47/50 | 0/50 | 72.7 | 23 / 27 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=1, large_20_100b=5, mega_100b_plus=2
