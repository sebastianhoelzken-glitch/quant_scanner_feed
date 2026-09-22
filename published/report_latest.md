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

- **EUROPE:** 79.6/100
- **OTHER:** 65.5/100
- **US:** 81.5/100

## Main multi-horizon ranking

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC     | US       |              102.33 |             87.15 |         86.19 |         89.88 |          88.11 |        83.87 |           84.77 |             90.02 |             71.31 |         4.2  |             73.14 | swing              |               -0.63 |                nan    |               nan    |
|      2 | VLO      | VLO     | US       |               98.64 |             85.74 |         86.51 |         87.28 |          84.98 |        80.09 |           86.15 |             81.62 |             59.21 |         3.5  |             69.68 | swing              |              nan    |                 -0.05 |               nan    |
|      3 | FRO      | FRO     | US       |                9.66 |             84.92 |         89.61 |         85.04 |          84.79 |        81.38 |           91.69 |             80.33 |             58.83 |         5.48 |             73.14 | short              |               -1.91 |                 -0.29 |                -0.48 |
|      4 | CMBT.BR  | CMBT.BR | EUROPE   |                5.04 |             84.19 |         86.57 |         83.71 |          84.66 |        82.13 |           96.4  |             78.08 |             60.03 |         3.78 |             73.14 | short              |               -1.05 |                 -0.5  |                -0.6  |
|      5 | PSX      | PSX     | US       |               90.98 |             83.86 |         83.87 |         86.89 |          83.85 |        78.7  |           80.31 |             87.16 |             61.15 |         3.73 |             73.14 | swing              |              nan    |                nan    |               nan    |
|      6 | DELL     | DELL    | US       |              318.64 |             83.62 |         91.59 |         86.55 |          80.68 |        67.76 |           73.57 |             85.89 |             30    |         7.75 |             72.23 | short              |               -0.84 |                  0.03 |               nan    |
|      7 | HSHP     | HSHP    | US       |                0.77 |             82.8  |         90.8  |         85.4  |          80.2  |        69.98 |           86.54 |            nan    |             28.83 |         4.77 |             62.84 | short              |              nan    |                nan    |               nan    |
|      8 | DHT      | DHT     | US       |                3.15 |             82.07 |         85.93 |         81.71 |          82.42 |        81.14 |           89.19 |             82.71 |             63.46 |         4.56 |             73.14 | short              |               -3.52 |                 -0.67 |                -1.07 |
|      9 | HPE      | HPE     | US       |               71.4  |             81.36 |         89.52 |         83.22 |          79.5  |        71.46 |           73.8  |             73.49 |             51.4  |         6.91 |             72.34 | short              |               -0.86 |                  1.45 |               nan    |
|     10 | MU       | MU      | US       |             1027.06 |             80.77 |         77.07 |         68.27 |          84.46 |        84.96 |           95.4  |             80.91 |             72.02 |         8.22 |             73.14 | long               |                2.07 |                  1.72 |                 1.08 |
|     11 | NAT      | NAT     | US       |                1.48 |             80.56 |         88.1  |         82    |          79.12 |        72.61 |           87.57 |             69.63 |             36.88 |         4.78 |             73.14 | short              |               -2.07 |                 -0.31 |                -0.46 |
|     12 | DINO     | DINO    | US       |               16.93 |             80.28 |         81.22 |         85.99 |          79.34 |        71.07 |           50.38 |             86.85 |             76.71 |         4.5  |             73.14 | swing              |               -1.77 |                 -0.27 |                -0.37 |
|     13 | PBF      | PBF     | US       |                7.48 |             78.59 |         68.13 |         81.59 |          80.22 |        76.96 |           53.65 |             88.13 |             91.87 |         7.58 |             72.68 | swing              |               -3.28 |                 -0.12 |                -0.24 |
|     14 | OKTA     | OKTA    | US       |               29.14 |             78.53 |         89.79 |         84.01 |          73.05 |        60.16 |           72.47 |             69.48 |             14.74 |         7.73 |             71.77 | short              |              nan    |                  0.18 |                 0.1  |
|     15 | KIN.BR   | KIN.BR  | EUROPE   |                1.36 |             77.75 |         80.67 |         80.81 |          74.83 |        65.35 |           89.68 |             64.88 |             17.39 |         3.76 |             73.14 | swing              |               -1.46 |                 -0.25 |                -0.17 |
|     16 | P        | P       | US       |               32.99 |             77.37 |         87.31 |         83.1  |          71.63 |        58.59 |           71.73 |             85.93 |             11.61 |         8.05 |             72.68 | short              |                6.45 |                  2.95 |                 2.34 |
|     17 | SB       | SB      | US       |                0.88 |             77.07 |         81.11 |         78.09 |          76.05 |        72.64 |           70.35 |             69.17 |             64.93 |         4.21 |             72.34 | short              |               -6.24 |                 -0.46 |                -0.67 |
|     18 | UGP      | UGP     | US       |                7.05 |             76.47 |         79.16 |         82.63 |          73.78 |        66.66 |           59.35 |             68.45 |             58.16 |         4.64 |             72.11 | swing              |               -0.76 |                 -0.13 |                -0.68 |
|     19 | AMC      | AMC     | US       |                2.25 |             76.19 |         80.65 |         74.53 |          75.65 |        76.74 |           85.19 |             79.37 |            nan    |         9.66 |             65.07 | short              |                1.22 |                 -0.58 |                -1.76 |
|     20 | HALO     | HALO    | US       |               11.02 |             76.11 |         77.24 |         79.74 |          74.98 |        72.27 |           86.84 |             51.91 |             50.76 |         5.86 |             72.11 | swing              |               -2.38 |                nan    |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.02 |                  76.12 |                    75.72 |                 77.21 |              76.29 |                86.85 |                   13.15 |           84.64 |             58.48 |       0.868 |         nan |       nan |      nan    |       -78.45 |          2.1  |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.57 |                  65.67 |                    72.61 |                 75.86 |              69.42 |                85.37 |                   14.63 |           93.42 |             67.67 |       0.15  |         nan |       nan |        0.87 |         5.37 |          5.2  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              234.83 |                  59.06 |                    71.6  |                 75.59 |              66.69 |                88.35 |                   11.65 |           93.44 |             82.68 |     nan     |         nan |       nan |      nan    |         9.38 |         10.44 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | BBWI     | Bath & Body Works, Inc.              | US       |                2.97 |                  78.11 |                    71.59 |                 68.84 |              71.03 |                63.08 |                   36.92 |           76.3  |             34.34 |       0.224 |         nan |       nan |        5.59 |         6.07 |          4.44 |        0.71 |                 nan |              nan |                  11 |                  0.58 |
|            4 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.77 |                  75.32 |                    71.49 |                 71.92 |              74.02 |                65.28 |                   34.72 |           64.7  |             80.4  |       0.143 |         nan |       nan |        1.79 |         4.66 |          4.73 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|            5 | NVDA     | NVIDIA Corporation                   | US       |             4782.81 |                  60.87 |                    70.86 |                 72.89 |              65.89 |                77.59 |                   22.41 |           86.9  |             80.91 |       0.008 |         nan |       nan |       27.11 |        14.5  |         28.75 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                                  | US       |                3.15 |                  60.17 |                    70.57 |                 74.08 |              66.35 |                81.97 |                   18.03 |           89.19 |             82.71 |     nan     |         nan |       nan |      nan    |        10.46 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | STNE     | StoneCo Ltd.                         | OTHER    |                1.95 |                  75    |                    70.48 |                 69.62 |              69.17 |                66.12 |                   33.88 |           84.18 |             32.73 |       0.616 |         nan |       nan |        1.62 |         4.26 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | EMBC     | Embecta Corp.                        | US       |                0.26 |                  73.36 |                    69.64 |                 69.63 |              70.7  |                63.65 |                   36.35 |           69.73 |             64.25 |       0.46  |         nan |       nan |        5.64 |         3.01 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.04 |                  56.33 |                    69.58 |                 74.01 |              63.78 |                85.65 |                   14.35 |           96.4  |             78.08 |     nan     |         nan |       nan |      nan    |         9.61 |          6.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.2  |                  62.7  |                    69.22 |                 71.73 |              66.26 |                72.75 |                   27.25 |           82.3  |             80.18 |     nan     |         nan |       nan |      nan    |         4.39 |          6.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.66 |                  56.95 |                    68.64 |                 72.69 |              63.55 |                80.63 |                   19.37 |           91.69 |             80.33 |     nan     |         nan |       nan |      nan    |        10.88 |          7.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  74.83 |                    68.56 |                 68.58 |              69.96 |                67.42 |                   32.58 |           75.5  |             39.47 |       0.616 |         nan |       nan |        4.33 |      -132.92 |          2.29 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1508.05 |                  60.81 |                    68.26 |                 68.85 |              62.34 |                78.52 |                   21.48 |           92.29 |             44.24 |       0.018 |         nan |       nan |       33.8  |        18.71 |         46.32 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | MPC      | MPC                                  | US       |              102.33 |                  55.67 |                    68.17 |                 72.17 |              63.99 |                82.83 |                   17.17 |           84.77 |             90.02 |     nan     |         nan |       nan |      nan    |         8.54 |         13.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              232.03 |                  67.25 |                    68.17 |                 68.51 |              67.03 |                70.47 |                   29.53 |           75.17 |             59.24 |     nan     |         nan |       nan |      nan    |         9.13 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.58 |                  65.4  |                    68.14 |                 70.42 |              66.52 |                68.82 |                   31.18 |           80.43 |             70.42 |       0.02  |         nan |       nan |        3.97 |         5.93 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                  | US       |              111.43 |                  62.25 |                    67.99 |                 69.84 |              65.23 |                76.48 |                   23.52 |           81.56 |             66.46 |     nan     |         nan |       nan |      nan    |         9.54 |         13.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              174.76 |                  64.46 |                    67.81 |                 68.65 |              67.49 |                73.25 |                   26.75 |           67.25 |             78.94 |     nan     |         nan |       nan |      nan    |         8.88 |         11.37 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.17 |                  70.11 |                    67.77 |                 66.44 |              69.7  |                68.06 |                   31.94 |           58.88 |            nan    |       0.234 |         nan |       nan |        1.54 |       nan    |          2.95 |      nan    |                 nan |              nan |                   8 |                  0.42 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.02 |                  76.12 |                    75.72 |                 77.21 |              76.29 |                86.85 |                   13.15 |           84.64 |             58.48 |       0.868 |         nan |       nan |      nan    |       -78.45 |          2.1  |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.57 |                  65.67 |                    72.61 |                 75.86 |              69.42 |                85.37 |                   14.63 |           93.42 |             67.67 |       0.15  |         nan |       nan |        0.87 |         5.37 |          5.2  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              234.83 |                  59.06 |                    71.6  |                 75.59 |              66.69 |                88.35 |                   11.65 |           93.44 |             82.68 |     nan     |         nan |       nan |      nan    |         9.38 |         10.44 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.15 |                  60.17 |                    70.57 |                 74.08 |              66.35 |                81.97 |                   18.03 |           89.19 |             82.71 |     nan     |         nan |       nan |      nan    |        10.46 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.04 |                  56.33 |                    69.58 |                 74.01 |              63.78 |                85.65 |                   14.35 |           96.4  |             78.08 |     nan     |         nan |       nan |      nan    |         9.61 |          6.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NVDA     | NVIDIA Corporation                   | US       |             4782.81 |                  60.87 |                    70.86 |                 72.89 |              65.89 |                77.59 |                   22.41 |           86.9  |             80.91 |       0.008 |         nan |       nan |       27.11 |        14.5  |         28.75 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                                  | US       |                9.66 |                  56.95 |                    68.64 |                 72.69 |              63.55 |                80.63 |                   19.37 |           91.69 |             80.33 |     nan     |         nan |       nan |      nan    |        10.88 |          7.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                                  | US       |              102.33 |                  55.67 |                    68.17 |                 72.17 |              63.99 |                82.83 |                   17.17 |           84.77 |             90.02 |     nan     |         nan |       nan |      nan    |         8.54 |         13.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.77 |                  75.32 |                    71.49 |                 71.92 |              74.02 |                65.28 |                   34.72 |           64.7  |             80.4  |       0.143 |         nan |       nan |        1.79 |         4.66 |          4.73 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM       | SM                                   | US       |                7.2  |                  62.7  |                    69.22 |                 71.73 |              66.26 |                72.75 |                   27.25 |           82.3  |             80.18 |     nan     |         nan |       nan |      nan    |         4.39 |          6.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               19.08 |                  53.98 |                    67.16 |                 71.46 |              61.02 |                85.59 |                   14.41 |           96.8  |             67.5  |     nan     |         nan |       nan |      nan    |        11.03 |         14.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.58 |                  65.4  |                    68.14 |                 70.42 |              66.52 |                68.82 |                   31.18 |           80.43 |             70.42 |       0.02  |         nan |       nan |        3.97 |         5.93 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                  | US       |              111.43 |                  62.25 |                    67.99 |                 69.84 |              65.23 |                76.48 |                   23.52 |           81.56 |             66.46 |     nan     |         nan |       nan |      nan    |         9.54 |         13.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | EMBC     | Embecta Corp.                        | US       |                0.26 |                  73.36 |                    69.64 |                 69.63 |              70.7  |                63.65 |                   36.35 |           69.73 |             64.25 |       0.46  |         nan |       nan |        5.64 |         3.01 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | STNE     | StoneCo Ltd.                         | OTHER    |                1.95 |                  75    |                    70.48 |                 69.62 |              69.17 |                66.12 |                   33.88 |           84.18 |             32.73 |       0.616 |         nan |       nan |        1.62 |         4.26 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | MU       | MU                                   | US       |             1027.06 |                  48.98 |                    64.13 |                 69.61 |              57.26 |                77.24 |                   22.76 |           95.4  |             80.91 |     nan     |         nan |       nan |      nan    |         6.57 |         23.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                  | US       |               14.89 |                  55.73 |                    65.97 |                 69.3  |              61.64 |                79.39 |                   20.61 |           85.91 |             72.25 |     nan     |         nan |       nan |      nan    |        10.58 |         22.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.84 |                  61.45 |                    67.13 |                 68.96 |              63.46 |                77.84 |                   22.16 |           87.29 |             52.05 |     nan     |         nan |       nan |      nan    |         8.82 |          7.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1508.05 |                  60.81 |                    68.26 |                 68.85 |              62.34 |                78.52 |                   21.48 |           92.29 |             44.24 |       0.018 |         nan |       nan |       33.8  |        18.71 |         46.32 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|            3 | BBWI     | Bath & Body Works, Inc.              | US       |                2.97 |                  78.11 |                    71.59 |                 68.84 |              71.03 |                63.08 |                   36.92 |           76.3  |             34.34 |       0.224 |         nan |       nan |        5.59 |         6.07 |          4.44 |        0.71 |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:-------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | MPC       | MPC                                  | US       |              102.33 |                     0.05 |     0.01 |      0.12 |                  65.22 |                        85.18 |         86.19 |         89.88 |          88.11 |        83.87 |           84.77 |             90.02 |         4.2  |
|               2 | PSX       | PSX                                  | US       |               90.98 |                     0.05 |     0.02 |      0.08 |                  59.59 |                        81.52 |         83.87 |         86.89 |          83.85 |        78.7  |           80.31 |             87.16 |         3.73 |
|               3 | DHT       | DHT                                  | US       |                3.15 |                     0.04 |     0.01 |      0.13 |                  54.65 |                        81.41 |         85.93 |         81.71 |          82.42 |        81.14 |           89.19 |             82.71 |         4.56 |
|               4 | AVAH      | AVAH                                 | US       |                2.56 |                     0.07 |    -0.07 |      0.02 |                  83.48 |                        79.22 |         68.48 |         79.58 |          77.87 |        72.85 |           92.75 |             55.68 |         7.66 |
|               5 | SHELL.AS  | SHELL.AS                             | EUROPE   |              234.83 |                     0.04 |    -0.04 |      0.04 |                  69.63 |                        78.53 |         74    |         73.67 |          74.31 |        79.96 |           93.44 |             82.68 |         2.41 |
|               6 | DAR       | DAR                                  | US       |                8.7  |                     0.07 |    -0.03 |     -0.04 |                  71.74 |                        77.27 |         56.79 |         71.1  |          79.33 |        83.27 |           90.38 |             85.9  |         4.59 |
|               7 | ARGX.BR   | ARGX.BR                              | EUROPE   |               53.97 |                     0.06 |     0    |     -0.02 |                  69.67 |                        75.62 |         64.47 |         68.87 |          70.68 |        62.88 |           93.54 |             80.16 |         6.04 |
|               8 | EQNR      | EQNR                                 | US       |               87.76 |                     0.07 |    -0.05 |     -0.01 |                  74.19 |                        75.38 |         61.39 |         72.84 |          73.8  |        75.58 |           76.15 |             84    |         5.52 |
|               9 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.58 |                     0.05 |     0    |      0.04 |                  67.85 |                        74.31 |         72.2  |         74.97 |          74.71 |        73.83 |           80.43 |             70.42 |         7    |
|              10 | C5H.IR    | C5H.IR                               | EUROPE   |                1.66 |                     0.05 |     0.01 |      0.07 |                  65.35 |                        74.14 |         75.62 |         65.13 |          69.49 |        73.82 |           97.96 |             46.25 |         2.68 |
|              11 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.77 |                     0.04 |    -0.02 |      0.12 |                  68.09 |                        74.12 |         77.82 |         74.91 |          71.82 |        74.14 |           64.7  |             80.4  |         3.73 |
|              12 | FORTUM.HE | FORTUM.HE                            | EUROPE   |               21.23 |                     0.05 |    -0.01 |      0.16 |                  68.77 |                        73.9  |         80.31 |         67.36 |          59.34 |        53.35 |           67.24 |             66.5  |         4.58 |
|              13 | PBR       | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              115.81 |                     0.05 |    -0.02 |      0.11 |                  76.37 |                        72.89 |         76.18 |         71.14 |          68.48 |        70.8  |           64.7  |             69.33 |         4.43 |
|              14 | GEN       | GEN                                  | US       |               15.2  |                     0.07 |    -0.07 |      0.01 |                  81.33 |                        72.71 |         60.63 |         72.08 |          68.92 |        70.52 |           77.53 |             59.75 |         5.7  |
|              15 | NESTE.HE  | NESTE.HE                             | EUROPE   |               26.25 |                     0.03 |     0.01 |      0.07 |                  48.69 |                        72.12 |         79.12 |         74.19 |          68.78 |        60.66 |           62.53 |             84.97 |         4.77 |
|              16 | MT.AS     | MT.AS                                | EUROPE   |               47.45 |                     0.07 |    -0    |      0.01 |                  64.38 |                        71.7  |         62.48 |         71.48 |          75.99 |        73.72 |           71.12 |             80.51 |         5.03 |
|              17 | DOCU      | DOCU                                 | US       |               11.16 |                     0.05 |    -0.02 |      0.11 |                  70.02 |                        71.57 |         75.72 |         75.55 |          63.95 |        59.26 |           63.61 |             69.92 |         7.82 |
|              18 | ASRNL.AS  | ASRNL.AS                             | EUROPE   |               14.87 |                     0.02 |     0    |      0.06 |                  46.4  |                        71.39 |         76.77 |         71.09 |          69.67 |        68.17 |           81.43 |             65.06 |         1.09 |
|              19 | OSCR      | OSCR                                 | US       |                8.41 |                     0.07 |    -0.07 |     -0.02 |                  80.48 |                        71.2  |         55.41 |         70.83 |          73.3  |        61.63 |           54.43 |             85.51 |         8.14 |
|              20 | FSM       | FSM                                  | US       |                3.03 |                     0.08 |     0.01 |     -0.03 |                  50.88 |                        71.07 |         61.65 |         73.55 |          77.18 |        80.48 |           80.06 |             71.02 |         7.19 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |               347.1 |             40.84 |         38.32 |         34.76 |          43.36 |        50.34 |           77.39 |             44.99 |                26 |          8.5 |              89.8 | long               |               -0.85 |                  0.17 |                 0.33 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     16 | P        | P                      | US       |               32.99 |             77.37 |         87.31 |         83.1  |          71.63 |        58.59 |           71.73 |             85.93 |             11.61 |         8.05 |             72.68 | short              |                6.45 |                  2.95 |                 2.34 |
|    319 | VZLA     | VZLA                   | US       |                1.26 |             57.51 |         69.58 |         59.81 |          55.21 |        53.52 |           60.26 |            nan    |             41.58 |         8.32 |             61.82 | short              |               -0.81 |                  2.91 |                 2.52 |
|    635 | TV       | Grupo Televisa, S.A.B. | OTHER    |                1.18 |             41    |         45.12 |         29.37 |          36.89 |        47.88 |           46.77 |             26.26 |             68.89 |         6.66 |             81.56 | long               |                8.53 |                  2.84 |                 2.55 |
|    423 | ABSI     | ABSI                   | US       |                1.47 |             53.61 |         65.5  |         57.93 |          49.3  |        30.28 |            3.93 |             39.44 |             21.68 |         9.15 |             69.27 | short              |               -3.47 |                  2.76 |                 2.34 |
|    320 | AMV0.DE  | AMV0.DE                | EUROPE   |                3.56 |             57.48 |         54.14 |         47.8  |          60.82 |        75.88 |           91.58 |             57.09 |             83.51 |         6.15 |             71.32 | long               |               -0.64 |                  2.59 |                 1.99 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    405 | CRM      | CRM     | US       |              169.49 |             54.36 |         64.66 |         59.72 |          47.34 |        48.99 |           66.19 |             15.15 |             30.87 |         7.81 |             69.27 | short              |              -15.89 |                 -3.14 |                -2.36 |
|    617 | 0P6O.IL  | 0P6O.IL | OTHER    |               40.99 |             42.29 |         44.85 |         34.54 |          39.72 |        63.63 |          nan    |            nan    |             83.33 |         5.41 |             60    | long               |               -4.89 |                 -2.89 |                -2.47 |
|    186 | CXW      | CXW     | US       |                2.79 |             62.99 |         48.44 |         63.81 |          69.02 |        62.17 |           56.97 |             66.92 |             53.84 |         5.29 |             72.34 | medium             |              -11.68 |                 -2.85 |                -2.6  |
|    584 | EGY      | EGY     | US       |                0.55 |             44.4  |         53.77 |         46.38 |          42.41 |        40    |           36.47 |             31.18 |             23.23 |         5.59 |             69.68 | short              |               -3.03 |                 -2.64 |                -2.07 |
|    199 | BP       | BP      | US       |               96.82 |             62.23 |         52.89 |         58.45 |          66.02 |        75.24 |           86.98 |             64.73 |             67.01 |         4.48 |             72.34 | long               |               -3.64 |                 -2.57 |                -2.37 |

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
- Excluded by hard/data filters: **290**
- Event watch (otherwise eligible): **1**
- Final eligible: **709**
- Eligible change vs previous stored run: **-3**

Top exclusion categories:
- liquidity: 235
- price: 186
- market_cap: 160
- price_history: 18
- data_confidence: 10
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 34 | 10 | 9 | 5 | 2 | value,pullback,quality_value |
| MPC | 1 |  | 1 |  | 2 | main,pullback |
| PSX | 5 |  | 2 |  | 2 | main,pullback |
| DHT | 8 |  | 3 |  | 2 | main,pullback |
| DDI | 27 | 2 |  | 2 | 1 | value,quality_value |
| PBR-A | 33 | 4 | 11 | 4 | 1 | value,quality_value |
| NVDA | 57 | 5 |  | 3 | 1 | value,quality_value |
| EMBC | 201 | 7 | 88 | 6 | 1 | value,quality_value |
| BION.SW | 216 | 1 | 115 | 1 | 1 | value,quality_value |
| AVGO | 301 | 9 |  | 8 | 1 | value,quality_value |
| STNE | 545 | 6 | 150 | 7 | 1 | value,quality_value |
| BBWI | 647 | 3 |  | 9 | 1 | value,quality_value |
| VLO | 2 |  |  |  | 1 | main |
| FRO | 3 |  |  |  | 1 | main |
| CMBT.BR | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **5** (FRO, DELL, HSHP, HPE, MU)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 71.08 | 76.12 | 49.33 | 84.64 | 58.48 | 86.85 | 61.72 |
| 2 | PBR-A | value+pullback | 70.42 | 75.32 | 68.09 | 64.70 | 80.40 | 65.28 | 74.53 |
| 3 | STNE | value+pullback | 69.61 | 75.00 | 71.94 | 84.18 | 32.73 | 66.12 | 47.75 |
| 4 | PARR | value+pullback | 69.45 | 65.40 | 67.85 | 80.43 | 70.42 | 68.82 | 74.27 |
| 5 | PBR | value+pullback | 67.54 | 64.35 | 76.37 | 64.70 | 69.33 | 62.51 | 70.97 |
| 6 | VOLV-B.ST | value+pullback | 64.85 | 74.09 | 68.93 | 55.24 | 53.78 | 58.64 | 53.15 |
| 7 | 0Q2N.IL | value+pullback | 64.67 | 70.11 | 64.79 | 58.88 |  | 68.06 | 61.93 |
| 8 | AMCX | value+pullback | 64.35 | 64.18 | 69.62 | 47.83 | 66.79 | 69.20 | 64.53 |
| 9 | RCI | value+pullback | 64.34 | 61.73 | 69.68 | 84.40 | 42.77 | 57.32 | 45.22 |
| 10 | EMBC | value+pullback | 63.67 | 73.36 | 48.18 | 69.73 | 64.25 | 63.65 | 62.17 |
| 11 | BCE | value+pullback | 63.35 | 57.11 | 79.04 | 68.54 | 57.97 | 51.92 | 44.51 |
| 12 | GSL | value+pullback | 63.06 | 70.51 | 48.55 | 76.18 | 30.65 | 76.39 | 65.92 |
| 13 | JD | value+pullback | 62.78 | 68.72 | 60.81 | 65.87 | 46.61 | 62.12 | 45.46 |
| 14 | BHF | value+pullback | 62.14 | 71.37 | 56.44 | 51.80 | 55.94 | 66.27 | 42.75 |
| 15 | GNW | value+pullback | 61.94 | 60.45 | 85.76 | 26.13 | 85.36 | 49.53 | 57.94 |
| 16 | UNIT | value+pullback | 61.81 | 80.01 | 64.97 | 64.98 | 29.24 | 44.48 | 42.43 |
| 17 | MFA | value+pullback | 61.02 | 58.14 | 70.64 | 76.63 | 26.38 | 58.94 | 41.57 |
| 18 | ORC | value+pullback | 59.80 | 60.76 | 58.92 | 75.90 | 35.20 | 59.69 | 40.43 |
| 19 | WB | value+pullback | 59.30 | 68.55 | 65.43 | 63.60 | 17.51 | 55.46 | 40.77 |
| 20 | DDI | value | 57.55 | 65.67 | 30.95 | 93.42 | 67.67 | 85.37 | 75.29 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 10/10 | 9/10 | 0/10 | 73.1 | 5 / 5 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 72.7 | 10 / 15 |
| Top 50 | 50/50 | 48/50 | 49/50 | 47/50 | 0/50 | 73.1 | 26 / 24 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=1, mid_5_20b=2, large_20_100b=3, mega_100b_plus=3
