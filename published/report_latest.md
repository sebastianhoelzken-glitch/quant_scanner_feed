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

- **EUROPE:** 77.8/100
- **OTHER:** 67.5/100
- **US:** 83.2/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE       | HPE       | US       |               73.45 |             84.06 |         89.55 |         86.99 |          81.12 |        72    |           70.64 |             80.85 |             52.76 |         6.91 |             72.34 | short              |                2.7  |                  0.85 |               nan    |
|      2 | DELL      | DELL      | US       |              314.64 |             83.77 |         86.41 |         86.63 |          81.13 |        68.81 |           71.99 |             85.97 |             35.69 |         7.82 |             72.23 | swing              |                0.15 |                  0.31 |                 0.08 |
|      3 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.88 |             83.49 |         75.72 |         83.16 |          85.44 |        83.81 |           96.14 |             77.17 |             65.23 |         3.66 |             73.14 | medium             |               -0.7  |                  1.46 |                 1.35 |
|      4 | MU        | MU        | US       |             1074.59 |             82.69 |         80.23 |         72.92 |          85.65 |        85.15 |           94.95 |             80.93 |             72.55 |         8.1  |             73.14 | medium             |                1.92 |                  2.75 |                 2.12 |
|      5 | VLO       | VLO       | US       |               98.01 |             82.23 |         79.69 |         86.09 |          84.28 |        80.17 |           84.63 |             81.06 |             62.79 |         3.57 |             69.68 | swing              |               -3.52 |                  0.98 |                 0.91 |
|      6 | FRO       | FRO       | US       |                9.34 |             81.74 |         80.2  |         82.87 |          82.64 |        80.83 |           90.84 |             68.44 |             62.96 |         5.03 |             73.14 | swing              |               -3.18 |                  0.47 |                 0.44 |
|      7 | AMC       | AMC       | US       |                2.31 |             81.19 |         82.12 |         86.4  |          80.27 |        79.49 |           85.61 |             78.82 |            nan    |         9.48 |             65.07 | swing              |                5    |                  4.46 |                 4.12 |
|      8 | PSX       | PSX       | US       |               90.15 |             80.26 |         75.48 |         84.87 |          82.2  |        78.32 |           78.26 |             85.82 |             64.3  |         3.81 |             73.14 | swing              |               -3.6  |                  1.04 |                 1.12 |
|      9 | ERO       | ERO       | US       |                3.47 |             79.77 |         71.8  |         78.73 |          80.82 |        81.63 |           83.7  |             68.3  |             78.45 |         7.74 |             73.14 | long               |              nan    |                nan    |               nan    |
|     10 | DHT       | DHT       | US       |                3.09 |             79.77 |         77.98 |         79.86 |          79.67 |        80.55 |           88.56 |             70.07 |             66.9  |         4.44 |             73.14 | long               |               -2.3  |                  0.67 |                 0.39 |
|     11 | NAT       | NAT       | US       |                1.44 |             79.68 |         80.4  |         80.93 |          78.96 |        73.8  |           86.77 |             69.25 |             42.55 |         4.61 |             73.14 | swing              |               -0.88 |                  0.32 |                 0.31 |
|     12 | SMTC      | SMTC      | US       |               14.96 |             79.39 |         84.93 |         82.45 |          76.33 |        62.2  |           71.96 |             84.21 |             15.11 |         8.45 |             73.14 | short              |                8.55 |                  0.84 |               nan    |
|     13 | REP.MC    | REP.MC    | EUROPE   |               32.76 |             78.68 |         84.28 |         81.76 |          75.6  |        71.89 |           59.39 |             82.14 |             73.21 |         3.81 |             73.14 | short              |                4.03 |                  1.89 |                 1.5  |
|     14 | SHELL.AS  | SHELL.AS  | EUROPE   |              239.93 |             78.25 |         81.93 |         76.21 |          74.11 |        80.28 |           92.95 |             78.94 |             66.52 |         2.45 |             73.14 | short              |                4.1  |                  2.84 |                 2.65 |
|     15 | KIN.BR    | KIN.BR    | EUROPE   |                1.35 |             77.8  |         80.61 |         81.32 |          74.99 |        65.7  |           89.04 |             64.75 |             18.66 |         3.69 |             73.14 | swing              |                0.05 |                 -0.18 |                -0.14 |
|     16 | OKTA      | OKTA      | US       |               30    |             77.39 |         86.04 |         81.63 |          73.16 |        59.08 |           67.56 |             69.51 |             15.73 |         7.85 |             72.11 | short              |               -1.13 |                  0.73 |                 0.77 |
|     17 | HALO      | HALO      | US       |               11.37 |             77.33 |         80.09 |         80.08 |          74.58 |        71.44 |           84.05 |             51.8  |             51.83 |         6.04 |             72.11 | short              |                1.22 |                nan    |               nan    |
|     18 | P         | P         | US       |               36.91 |             77.15 |         92.41 |         84.96 |          69.34 |        56.46 |           67.66 |             76.15 |             12.85 |         8.16 |             72.68 | short              |               -0.22 |                  2.5  |                 1.81 |
|     19 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.96 |             77.01 |         78.99 |         75.81 |          76.04 |        77.99 |           96.89 |             66.26 |             58.33 |         2.18 |             73.14 | short              |                1.28 |                  2.06 |                 1.73 |
|     20 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.22 |             76    |         58.28 |         71.98 |          80.03 |        82.73 |           71.6  |            nan    |             98.82 |         4.26 |             62.84 | long               |                0.82 |                nan    |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                2.98 |                  73.97 |                    74.47 |                 76.15 |              74.67 |                86.77 |                   13.23 |           84.64 |             57.91 |       0.877 |         nan |       nan |      nan    |       -77.69 |          2.08 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | BBWI      | Bath & Body Works, Inc.              | US       |                2.92 |                  82.54 |                    71.49 |                 67.67 |              72.28 |                52.64 |                   47.36 |           70.25 |             33.77 |       0.231 |         nan |       nan |        5.52 |         5.9  |          4.32 |        0.68 |                 nan |              nan |                  11 |                  0.58 |
|            3 | NVDA      | NVIDIA Corporation                   | US       |             4777.92 |                  61.64 |                    70.98 |                 72.83 |              66.13 |                77.14 |                   22.86 |           86.9  |             78.63 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.45 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL      | SHEL                                 | US       |              240.17 |                  66.47 |                    70.23 |                 71.29 |              69.44 |                75.71 |                   24.29 |           72.36 |             79.5  |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM        | SM                                   | US       |                7.09 |                  64.18 |                    69.89 |                 72.15 |              67.22 |                72.19 |                   27.81 |           81.65 |             80.17 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              239.93 |                  57.21 |                    69.82 |                 73.85 |              64.71 |                86.84 |                   13.16 |           92.95 |             78.94 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.41 |                  68.48 |                    69.77 |                 71.72 |              68.67 |                68.68 |                   31.32 |           80.43 |             69.96 |       0.021 |         nan |       nan |        3.8  |         5.6  |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.88 |                  56.8  |                    69.68 |                 73.99 |              64    |                85.45 |                   14.55 |           96.14 |             77.17 |     nan     |         nan |       nan |      nan    |         9.23 |          6.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.72 |                  74.83 |                    69.12 |                 69.34 |              70.56 |                68.55 |                   31.45 |           75.5  |             43.4  |       0.643 |         nan |       nan |        4.54 |      -125.84 |          2.17 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | EMBC      | Embecta Corp.                        | US       |                0.29 |                  72.47 |                    69.11 |                 69.27 |              69.91 |                62.66 |                   37.34 |           70.34 |             64.48 |       0.413 |         nan |       nan |        5.76 |         3.35 |          4.01 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.47 |                  79.55 |                    69.07 |                 67.25 |              74.43 |                50.99 |                   49.01 |           47.39 |             79.75 |       0.143 |         nan |       nan |        1.78 |         4.61 |          4.68 |        5.44 |                 nan |              nan |                  12 |                  0.63 |
|            8 | INVA      | Innoviva, Inc.                       | US       |                1.32 |                  64.71 |                    69.05 |                 71.46 |              66.44 |                82.36 |                   17.64 |           89.82 |             50.22 |       0.074 |         nan |       nan |        6.4  |         9.38 |          4.81 |        0.25 |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT       | DHT                                  | US       |                3.09 |                  60.08 |                    68.43 |                 71.36 |              64.28 |                77.83 |                   22.17 |           88.56 |             70.07 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA    | TTE.PA                               | EUROPE   |              176.64 |                  63.99 |                    68.33 |                 69.43 |              67.99 |                74.81 |                   25.19 |           66.93 |             84.57 |     nan     |         nan |       nan |      nan    |         8.7  |         11.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | AVGO      | Broadcom Inc.                        | US       |             1480.63 |                  60.81 |                    68.27 |                 68.86 |              62.34 |                78.46 |                   21.54 |           92.29 |             44.36 |       0.018 |         nan |       nan |       32.9  |        18.2  |         45.58 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR   | BIRG.IR                              | EUROPE   |               18.96 |                  56    |                    68.15 |                 72.15 |              62.29 |                85.25 |                   14.75 |           96.89 |             66.26 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               58.57 |                  74.59 |                    67.97 |                 65.03 |              70.7  |                59.52 |                   40.48 |           52.45 |             62.84 |       0.036 |         nan |       nan |       15.57 |        13.06 |         18.47 |        0.93 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP        | BP                                   | US       |               99.96 |                  55.6  |                    67.65 |                 71.56 |              63.42 |                81.47 |                   18.53 |           84.92 |             87.3  |     nan     |         nan |       nan |      nan    |         8.98 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.07 |                  68.76 |                    67.59 |                 66.69 |              68.96 |                69.77 |                   30.23 |           61.12 |            nan    |       0.242 |         nan |       nan |        1.54 |       nan    |          2.85 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | AGS.BR    | AGS.BR                               | EUROPE   |               15.57 |                  63.4  |                    67.59 |                 68.94 |              64.49 |                76.41 |                   23.59 |           85.25 |             50.88 |     nan     |         nan |       nan |      nan    |         8.67 |          7.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG              | EUROPE   |                2.98 |                  73.97 |                    74.47 |                 76.15 |              74.67 |                86.77 |                   13.23 |           84.64 |             57.91 |       0.877 |         nan |       nan |      nan    |       -77.69 |          2.08 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.88 |                  56.8  |                    69.68 |                 73.99 |              64    |                85.45 |                   14.55 |           96.14 |             77.17 |     nan     |         nan |       nan |      nan    |         9.23 |          6.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                   | EUROPE   |              239.93 |                  57.21 |                    69.82 |                 73.85 |              64.71 |                86.84 |                   13.16 |           92.95 |             78.94 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA     | NVIDIA Corporation         | US       |             4777.92 |                  61.64 |                    70.98 |                 72.83 |              66.13 |                77.14 |                   22.86 |           86.9  |             78.63 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.45 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM       | SM                         | US       |                7.09 |                  64.18 |                    69.89 |                 72.15 |              67.22 |                72.19 |                   27.81 |           81.65 |             80.17 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                    | EUROPE   |               18.96 |                  56    |                    68.15 |                 72.15 |              62.29 |                85.25 |                   14.75 |           96.89 |             66.26 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc. | US       |                3.41 |                  68.48 |                    69.77 |                 71.72 |              68.67 |                68.68 |                   31.32 |           80.43 |             69.96 |       0.021 |         nan |       nan |        3.8  |         5.6  |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                         | US       |               99.96 |                  55.6  |                    67.65 |                 71.56 |              63.42 |                81.47 |                   18.53 |           84.92 |             87.3  |     nan     |         nan |       nan |      nan    |         8.98 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | INVA     | Innoviva, Inc.             | US       |                1.32 |                  64.71 |                    69.05 |                 71.46 |              66.44 |                82.36 |                   17.64 |           89.82 |             50.22 |       0.074 |         nan |       nan |        6.4  |         9.38 |          4.81 |        0.25 |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT      | DHT                        | US       |                3.09 |                  60.08 |                    68.43 |                 71.36 |              64.28 |                77.83 |                   22.17 |           88.56 |             70.07 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                       | US       |              240.17 |                  66.47 |                    70.23 |                 71.29 |              69.44 |                75.71 |                   24.29 |           72.36 |             79.5  |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                        | US       |                9.34 |                  57.84 |                    67.24 |                 70.6  |              62.4  |                77.29 |                   22.71 |           90.84 |             68.44 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                        | US       |               15.15 |                  55.81 |                    67.09 |                 70.58 |              62.82 |                83.34 |                   16.66 |           86.03 |             76.39 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                        | US       |               14.75 |                  56.71 |                    66.87 |                 70.15 |              62.75 |                80.22 |                   19.78 |           85.51 |             74.81 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                     | EUROPE   |              176.64 |                  63.99 |                    68.33 |                 69.43 |              67.99 |                74.81 |                   25.19 |           66.93 |             84.57 |     nan     |         nan |       nan |      nan    |         8.7  |         11.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                         | US       |             1074.59 |                  48.67 |                    63.88 |                 69.36 |              57.04 |                77.26 |                   22.74 |           94.95 |             80.93 |     nan     |         nan |       nan |      nan    |         6.79 |         24.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NWL.MI   | NewPrinces S.p.A.          | EUROPE   |                0.72 |                  74.83 |                    69.12 |                 69.34 |              70.56 |                68.55 |                   31.45 |           75.5  |             43.4  |       0.643 |         nan |       nan |        4.54 |      -125.84 |          2.17 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | EMBC     | Embecta Corp.              | US       |                0.29 |                  72.47 |                    69.11 |                 69.27 |              69.91 |                62.66 |                   37.34 |           70.34 |             64.48 |       0.413 |         nan |       nan |        5.76 |         3.35 |          4.01 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | A5G.IR   | A5G.IR                     | EUROPE   |               24.5  |                  55.43 |                    65.73 |                 69.24 |              59.81 |                80.66 |                   19.34 |           96.46 |             53.86 |     nan     |         nan |       nan |      nan    |        11.79 |         12.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                     | EUROPE   |               15.57 |                  63.4  |                    67.59 |                 68.94 |              64.49 |                76.41 |                   23.59 |           85.25 |             50.88 |     nan     |         nan |       nan |      nan    |         8.67 |          7.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name               | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:-------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO                | US       |               98.01 |                     0.06 |    -0.06 |      0.12 |                  84.21 |                        84.76 |         79.69 |         86.09 |          84.28 |        80.17 |           84.63 |             81.06 |         3.57 |
|               2 | CMBT.BR   | CMBT.BR            | EUROPE   |                4.88 |                     0.07 |    -0.05 |      0.06 |                  75.94 |                        83.78 |         75.72 |         83.16 |          85.44 |        83.81 |           96.14 |             77.17 |         3.66 |
|               3 | PSX       | PSX                | US       |               90.15 |                     0.07 |    -0.06 |      0.07 |                  81.77 |                        83.22 |         75.48 |         84.87 |          82.2  |        78.32 |           78.26 |             85.82 |         3.81 |
|               4 | FRO       | FRO                | US       |                9.34 |                     0.07 |    -0.07 |      0.16 |                  81.39 |                        82.08 |         80.2  |         82.87 |          82.64 |        80.83 |           90.84 |             68.44 |         5.03 |
|               5 | NAT       | NAT                | US       |                1.44 |                     0.06 |    -0.06 |      0.19 |                  83.85 |                        80.78 |         80.4  |         80.93 |          78.96 |        73.8  |           86.77 |             69.25 |         4.61 |
|               6 | DHT       | DHT                | US       |                3.09 |                     0.06 |    -0.06 |      0.13 |                  83.92 |                        80.74 |         77.98 |         79.86 |          79.67 |        80.55 |           88.56 |             70.07 |         4.44 |
|               7 | DELL      | DELL               | US       |              314.64 |                     0.04 |    -0.01 |      0.19 |                  66.28 |                        80.55 |         86.41 |         86.63 |          81.13 |        68.81 |           71.99 |             85.97 |         7.82 |
|               8 | BP        | BP                 | US       |               99.96 |                     0.06 |    -0.01 |      0.04 |                  70.65 |                        77.75 |         74.15 |         72.64 |          71.42 |        77.73 |           84.92 |             87.3  |         4.48 |
|               9 | CIRSA.MC  | CIRSA.MC           | EUROPE   |                3.2  |                     0.04 |    -0.02 |      0.37 |                  68.63 |                        77.08 |         82.99 |         78.91 |          69.59 |        69.28 |           82.47 |             58.62 |         5.32 |
|              10 | C5H.IR    | C5H.IR             | EUROPE   |                1.65 |                     0.06 |     0.01 |      0.05 |                  66.53 |                        75.33 |         75.32 |         68.68 |          72.58 |        76.56 |           98.05 |             53.88 |         2.67 |
|              11 | EQNR      | EQNR               | US       |               87.93 |                     0.08 |    -0.04 |      0.02 |                  69.28 |                        74.93 |         64.19 |         74.66 |          73.48 |        74.72 |           72.88 |             84.26 |         5.63 |
|              12 | NESTE.HE  | NESTE.HE           | EUROPE   |               26.13 |                     0.05 |    -0.02 |      0.09 |                  74.77 |                        74.89 |         76.78 |         73.85 |          69.42 |        61.97 |           61.6  |             86.4  |         4.95 |
|              13 | DAR       | DAR                | US       |                8.5  |                     0.09 |    -0.06 |     -0    |                  64.43 |                        74.78 |         57.25 |         68.95 |          77.39 |        84.47 |           90.22 |             83.97 |         4.73 |
|              14 | PAA       | PAA                | US       |               15.15 |                     0.06 |    -0.04 |     -0.04 |                  75.96 |                        74.02 |         55.49 |         67.93 |          73.41 |        76.65 |           86.03 |             76.39 |         2.05 |
|              15 | FORTUM.HE | FORTUM.HE          | EUROPE   |               21.01 |                     0.05 |    -0.05 |      0.13 |                  83.13 |                        73.89 |         76.75 |         65.95 |          58.66 |        53.12 |           67.06 |             64.2  |         4.63 |
|              16 | ARGX.BR   | ARGX.BR            | EUROPE   |               52.56 |                     0.07 |    -0.03 |     -0.06 |                  68.06 |                        73.71 |         55.72 |         65.79 |          68.92 |        61.78 |           92.56 |             80.62 |         6.14 |
|              17 | SHEL      | SHEL               | US       |              240.17 |                     0.03 |     0.01 |      0.06 |                  52.79 |                        73.5  |         78.36 |         75.37 |          70.69 |        76.19 |           72.36 |             79.5  |         2.96 |
|              18 | ARIS      | ARIS               | US       |                3.44 |                     0.08 |    -0.02 |     -0.11 |                  63.15 |                        73.42 |         52.38 |         69.69 |          78.12 |        85.25 |           87.35 |             77.53 |         7.83 |
|              19 | GTLB      | GTLB               | US       |                6.86 |                     0.07 |    -0.05 |      0.05 |                  76.83 |                        73.12 |         69.96 |         79.24 |          63.44 |        48.65 |           56    |             71.86 |         8.38 |
|              20 | NVDA      | NVIDIA Corporation | US       |             4777.92 |                     0.02 |     0.01 |     -0.01 |                  46.65 |                        73.04 |         72.17 |         73.73 |          71.73 |        69.26 |           86.9  |             78.63 |         5.81 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | TLRY     | Tilray Brands, Inc. | OTHER    |                0.51 |             28.89 |         31.85 |         21.53 |          25.93 |        32.84 |           44.15 |             31.77 |             29.36 |         8.91 |             78.44 | long               |                 3.7 |                  0.27 |                 0.32 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    302 | ITRG     | ITRG       | US       |                0.49 |             58.28 |         48.95 |         58.38 |          58.17 |        65.7  |           56.12 |             63.39 |             88.21 |         8.18 |             68.32 | long               |                2.48 |                  4.95 |                 5.17 |
|    321 | HUT      | HUT        | US       |               10.49 |             57.77 |         67.04 |         54.98 |          60.55 |        45.88 |           37.15 |             78.16 |             17.09 |         8.57 |             66.84 | short              |              nan    |                  4.81 |               nan    |
|      7 | AMC      | AMC        | US       |                2.31 |             81.19 |         82.12 |         86.4  |          80.27 |        79.49 |           85.61 |             78.82 |            nan    |         9.48 |             65.07 | swing              |                5    |                  4.46 |                 4.12 |
|    159 | GVR.IR   | GVR.IR     | EUROPE   |                1.19 |             64.72 |         61.81 |         56.67 |          67.64 |        73.85 |           92.47 |             62.95 |             62.32 |         2.67 |             73.14 | long               |              nan    |                  4.42 |               nan    |
|    577 | ZH       | Zhihu Inc. | OTHER    |                0.28 |             44.48 |         68.79 |         51.69 |          37.27 |        31.18 |           31.3  |             25.53 |             33.07 |         6.29 |             82.17 | short              |                5.43 |                  4.12 |                 3.07 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    452 | TEVA     | TEVA    | US       |               40.18 |             52.52 |         66.28 |         58.03 |          47.01 |        39.31 |           12.8  |             29.95 |             50.5  |         4.8  |             72.34 | short              |               -2.49 |                 -3.44 |                -3.57 |
|    665 | PAH3.DE  | PAH3.DE | EUROPE   |                7.89 |             35.17 |         29.6  |         31.68 |          38.66 |        62.64 |          nan    |             27.25 |             96.79 |         5.16 |             70.3  | long               |              -10.18 |                 -3.26 |                -2.75 |
|    659 | 0JHU.IL  | 0JHU.IL | OTHER    |                8.25 |             37.27 |         23.29 |         31.81 |          42.72 |        74.04 |          nan    |            nan    |            100    |         5.18 |             60    | long               |               -0.34 |                 -3.09 |                -3.22 |
|    628 | BAS.DE   | BAS.DE  | EUROPE   |               43.41 |             41.38 |         46.02 |         44.19 |          38.57 |        36.45 |           29.96 |             31.65 |             29.28 |         2.21 |             67.86 | short              |                0.14 |                 -2.83 |               nan    |
|    631 | PIRC.MI  | PIRC.MI | EUROPE   |                7.03 |             41.08 |         50.47 |         44.24 |          37.91 |        37.09 |           18.02 |             21.94 |             58.55 |         2.12 |             71.32 | short              |               -2.99 |                 -2.8  |                -2.71 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
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
- Excluded by hard/data filters: **296**
- Event watch (otherwise eligible): **1**
- Final eligible: **703**
- Eligible change vs previous stored run: **-6**

Top exclusion categories:
- liquidity: 236
- price: 189
- market_cap: 165
- price_history: 20
- data_confidence: 11
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| DELL | 2 |  | 7 |  | 2 | main,pullback |
| CMBT.BR | 3 |  | 2 |  | 2 | main,pullback |
| VLO | 5 |  | 1 |  | 2 | main,pullback |
| FRO | 6 |  | 4 |  | 2 | main,pullback |
| PSX | 8 |  | 3 |  | 2 | main,pullback |
| DHT | 10 |  | 6 |  | 2 | main,pullback |
| NVDA | 50 | 3 | 20 | 2 | 1 | value,quality_value |
| PARR | 66 | 4 | 34 | 3 | 1 | value,quality_value |
| PBR-A | 80 | 7 | 41 | 10 | 1 | value,quality_value |
| EMBC | 154 | 6 |  | 6 | 1 | value,quality_value |
| BION.SW | 211 | 1 | 116 | 1 | 1 | value,quality_value |
| NWL.MI | 295 | 5 | 89 | 5 | 1 | value,quality_value |
| INVA | 415 | 8 | 126 | 4 | 1 | value,quality_value |
| AVGO | 416 | 9 | 131 | 7 | 1 | value,quality_value |
| BBWI | 654 | 2 |  | 8 | 1 | value,quality_value |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **3** (MU, AMC, ERO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 72.64 | 73.97 | 58.42 | 84.64 | 57.91 | 86.77 | 62.18 |
| 2 | INVA | value+pullback | 69.38 | 64.71 | 59.99 | 89.82 | 50.22 | 82.36 | 54.03 |
| 3 | PARR | value+pullback | 69.38 | 68.48 | 64.14 | 80.43 | 69.96 | 68.68 | 70.92 |
| 4 | GSL | value+pullback | 69.33 | 70.34 | 74.01 | 75.72 | 30.45 | 76.64 | 62.14 |
| 5 | AVGO | value+pullback | 69.32 | 60.81 | 68.41 | 92.29 | 44.36 | 78.46 | 53.99 |
| 6 | NWL.MI | value+pullback | 67.98 | 74.83 | 64.63 | 75.50 | 43.40 | 68.55 | 58.44 |
| 7 | PBR-A | value+pullback | 67.81 | 79.55 | 74.65 | 47.39 | 79.75 | 50.99 | 69.79 |
| 8 | NVDA | value+pullback | 66.48 | 61.64 | 46.65 | 86.90 | 78.63 | 77.14 | 71.95 |
| 9 | VOLV-B.ST | value+pullback | 65.81 | 74.59 | 69.50 | 52.45 | 62.84 | 59.52 | 54.22 |
| 10 | IRS | value+pullback | 63.22 | 67.73 | 69.38 | 62.56 | 40.83 | 60.47 | 46.39 |
| 11 | 0Q2N.IL | value+pullback | 62.54 | 68.76 | 55.17 | 61.12 |  | 69.77 | 58.97 |
| 12 | STNE | value+pullback | 62.19 | 68.99 | 48.05 | 86.35 | 32.20 | 66.55 | 42.85 |
| 13 | WB | value+pullback | 62.02 | 71.47 | 62.83 | 73.42 | 17.82 | 60.40 | 37.60 |
| 14 | AVK | value+pullback | 61.59 | 56.65 | 71.14 | 62.64 |  | 62.10 | 46.95 |
| 15 | BCE | value+pullback | 59.78 | 59.29 | 52.87 | 80.43 | 53.72 | 56.68 | 42.44 |
| 16 | VIPS | value+pullback | 59.32 | 64.76 | 51.86 | 81.14 | 25.22 | 61.15 | 41.81 |
| 17 | PBR | value+pullback | 58.26 | 55.90 | 71.10 | 47.39 | 69.50 | 48.27 | 64.14 |
| 18 | CMBT.BR | pullback | 58.21 | 56.80 | 75.94 | 96.14 | 77.17 | 85.45 | 83.49 |
| 19 | VLO | pullback | 58.08 | 49.49 | 84.21 | 84.63 | 81.06 | 81.13 | 82.23 |
| 20 | ALL-PH | value+pullback | 57.94 | 61.14 | 49.33 | 70.31 | 43.53 | 61.81 | 52.11 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 7 / 3 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 73.1 | 14 / 11 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 72.7 | 26 / 24 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=1, large_20_100b=3, mega_100b_plus=2
