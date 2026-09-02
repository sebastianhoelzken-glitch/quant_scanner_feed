# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-02

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

- **EUROPE:** 85.7/100
- **OTHER:** 69.0/100
- **US:** 80.9/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.54 |             82.08 |         82.53 |         79.36 |          81.63 |        82.97 |           95.16 |             62.56 |             68.64 |         4.05 |             69.68 | long               |                4.2  |                  2.22 |                 1.63 |
|      2 | FRO      | FRO                        | US       |                8.49 |             81.2  |         81.88 |         80.52 |          80.42 |        81.97 |           90.65 |             69.87 |             69.22 |         5.51 |             69.68 | long               |                2.56 |                  0.88 |                 0.42 |
|      3 | KIN.BR   | KIN.BR                     | EUROPE   |                1.27 |             79.36 |         83.51 |         83.7  |          75.21 |        66.44 |           89.33 |             63.37 |             21.06 |         4.02 |             69.68 | swing              |                7.81 |                  0.65 |                 0.05 |
|      4 | ANF      | ANF                        | US       |                5.38 |             78.67 |         89.62 |         81    |          76.26 |        76.34 |           86.24 |             66.57 |             62.52 |         8.56 |             67.64 | short              |                4.95 |                  2.18 |               nan    |
|      5 | DINO     | DINO                       | US       |               15.91 |             78.25 |         83.69 |         82.54 |          73.96 |        65.95 |           48.31 |             70.84 |             71.96 |         4.47 |             69.68 | short              |                5.84 |                  2.12 |                 2.37 |
|      6 | PAGP     | PAGP                       | US       |                5.71 |             77.62 |         83.06 |         78.43 |          76.8  |        74.5  |           82.8  |             80.61 |             55.51 |         1.85 |             66.7  | short              |                1.32 |                  1.19 |               nan    |
|      7 | NAT      | NAT                        | US       |                1.26 |             77.58 |         77.11 |         79.41 |          78.04 |        75.15 |           85.74 |             72.96 |             49.07 |         4.9  |             69.68 | swing              |                1.23 |                  1    |                 0.73 |
|      8 | BAYN.DE  | BAYN.DE                    | EUROPE   |               48.02 |             77.57 |         62.89 |         77.86 |          81.23 |        77.28 |          nan    |             87.05 |             62.95 |         6.3  |             66.84 | medium             |                4.06 |                  1.41 |                 0.71 |
|      9 | PR       | PR                         | US       |               17.15 |             77.08 |         83.35 |         78.2  |          75.87 |        75.95 |           76.5  |             70.58 |             72.6  |         4.41 |             68.32 | short              |                1.94 |                  1.51 |                 1.08 |
|     10 | AVAH     | AVAH                       | US       |                2.53 |             77.05 |         84.95 |         80.89 |          73.2  |        70.96 |           92.9  |             51.06 |             42.16 |         7.52 |             68.66 | short              |               -0.7  |                  0.64 |               nan    |
|     11 | OKTA     | OKTA                       | US       |               25.04 |             76.98 |         84.98 |         79.57 |          74.38 |        60.44 |           68.76 |             80.89 |             18.74 |         7.68 |             68.32 | short              |               -0.5  |                  0.32 |                 0.12 |
|     12 | DEZ.DE   | DEZ.DE                     | EUROPE   |                1.92 |             76.92 |         90.45 |         79.85 |          69.56 |        73.99 |          nan    |             82.35 |             68.4  |         6.42 |             66.84 | short              |                3.32 |                  1.35 |               nan    |
|     13 | PSX      | PSX                        | US       |               86.56 |             76.86 |         83.5  |         79.32 |          74.4  |        71.86 |           77.99 |             51.5  |             61.26 |         3.58 |             69.68 | short              |                5.55 |                nan    |               nan    |
|     14 | CRGY     | CRGY                       | US       |                4    |             76.56 |         84.32 |         76.09 |          72.16 |        77.04 |           69.97 |             64.33 |             94.84 |         6.23 |             69.23 | short              |                3.19 |                  1.68 |               nan    |
|     15 | PBF      | PBF                        | US       |                7.65 |             76.18 |         81.31 |         79.39 |          72.97 |        69.51 |           51.08 |             53.78 |             87.68 |         7.53 |             69.23 | short              |                2.82 |                  2.77 |                 3.6  |
|     16 | BION.SW  | BB Biotech AG              | EUROPE   |                3.26 |             76.12 |         74.45 |         75.7  |          76.55 |        81.19 |           85.52 |             57.76 |             84.76 |         2.3  |             78.9  | long               |               16.08 |                  3.6  |                 3.46 |
|     17 | DAR      | DAR                        | US       |                9.2  |             75.97 |         81.99 |         69.62 |          74.13 |        77.8  |           91.28 |             54.68 |             65.98 |         4.4  |             67.86 | short              |                1.59 |                  2.33 |               nan    |
|     18 | SM       | SM                         | US       |                7.79 |             75.82 |         84.28 |         73.62 |          72.12 |        78.01 |           79.11 |             46.53 |             95.55 |         7.24 |             68.66 | short              |               -3.31 |                  2.08 |                 1.77 |
|     19 | PARR     | Par Pacific Holdings, Inc. | US       |                3.45 |             75.78 |         68.21 |         74.44 |          78.68 |        77.11 |           83.23 |             61.15 |             70.5  |         7.02 |             85.07 | medium             |               -2.05 |                  2.36 |                 2.61 |
|     20 | ABN.AS   | ABN.AS                     | EUROPE   |               33.97 |             75.19 |         75.15 |         77.43 |          75.23 |        70.73 |           75.95 |             60.08 |             55.33 |         2.88 |             69.68 | swing              |                1.94 |                  0.86 |                 0.87 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.26 |                  73.76 |                    74.49 |                 76.27 |              74.53 |                86.9  |                   13.1  |           85.52 |             57.76 |       0.807 |         nan |       nan |      nan    |       -84.38 |          2.26 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | 0P6O.IL  | Volkswagen AG                        | OTHER    |               42.2  |                  73.72 |                    74.04 |                 74.8  |              72.8  |                69.11 |                   30.89 |           80.16 |            nan    |       0.41  |         nan |       nan |        7.45 |       nan    |          2.74 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|            3 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.31 |                  73.09 |                    73.65 |                 73.32 |              74.29 |                79.11 |                   20.89 |           70.25 |            nan    |       0.224 |         nan |       nan |        1.54 |       nan    |          3.09 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            4 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.54 |                  69.44 |                    73.34 |                 75.68 |              70.82 |                83.16 |                   16.84 |           92.69 |             58.61 |       0.155 |         nan |       nan |        0.74 |         5.21 |          5.04 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.61 |                  72.52 |                    72.29 |                 73.7  |              72.69 |                78.17 |                   21.83 |           78.88 |             64.14 |       0.173 |         nan |       nan |        4.3  |         2.85 |          5.41 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | SAP.DE   | SAP SE                               | EUROPE   |              212.67 |                  70.26 |                    71.86 |                 71.48 |              69.28 |                76.31 |                   23.69 |           83.91 |             49.61 |       0.043 |         nan |       nan |       17.98 |        22.02 |         27.58 |        1.89 |                 nan |              nan |                  12 |                  0.63 |
|            7 | STNE     | StoneCo Ltd.                         | OTHER    |                1.92 |                  75.56 |                    71.33 |                 70.64 |              70.35 |                69.36 |                   30.64 |           84.18 |             34.59 |       0.612 |         nan |       nan |        1.62 |         4.16 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | SDF.DE   | K+S Aktiengesellschaft               | EUROPE   |                3.05 |                  67.26 |                    71.11 |                 72.43 |              68    |                78.77 |                   21.23 |           89.01 |             53.93 |       0.112 |         nan |       nan |        2.13 |        14.63 |          2.88 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              220.89 |                  62.12 |                    70.9  |                 73.8  |              66.66 |                82.97 |                   17.03 |           91.6  |             70.04 |     nan     |         nan |       nan |      nan    |        10.07 |         10.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.45 |                  71.23 |                    70.73 |                 72.22 |              69.62 |                67.91 |                   32.09 |           83.23 |             61.15 |       0.021 |         nan |       nan |        3.9  |         6.77 |          4.69 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.38 |                  76.42 |                    69.99 |                 68.9  |              71.59 |                73.32 |                   26.68 |           73.8  |             33.74 |       0.081 |         nan |       nan |        3.83 |         5.02 |          4.34 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|           11 | BBWI     | Bath & Body Works, Inc.              | US       |                3.23 |                  81.83 |                    69.59 |                 65.33 |              71.14 |                49.65 |                   50.35 |           64.56 |             32.8  |       0.204 |         nan |       nan |        5.86 |         6.64 |          5.06 |        0.72 |                 nan |              nan |                  11 |                  0.58 |
|           12 | AMV0.DE  | Aumovio SE                           | EUROPE   |                3.57 |                  72.75 |                    69.51 |                 67.73 |              72.15 |                72.65 |                   27.35 |           56.21 |             66.98 |       1.122 |         nan |       nan |        2.78 |         6.59 |        nan    |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | FRO      | FRO                                  | US       |                8.49 |                  60.79 |                    68.97 |                 72    |              64.56 |                76.69 |                   23.31 |           90.65 |             69.87 |     nan     |         nan |       nan |      nan    |        10.28 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | IHS      | IHS Holding Limited                  | OTHER    |                2.45 |                  74.37 |                    68.79 |                 68.73 |              72.69 |                60.25 |                   39.75 |           55.09 |             82.99 |      -0.114 |         nan |       nan |        7.5  |        15.27 |          5.15 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | NLY      | NLY                                  | US       |               14.68 |                  68.9  |                    68.13 |                 68.22 |              65.22 |                69.98 |                   30.02 |           88.8  |             30.08 |     nan     |         nan |       nan |      nan    |         7.27 |          5.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | HRB      | H&R Block, Inc.                      | US       |                5.4  |                  60.66 |                    67.78 |                 70.74 |              64.81 |                79.1  |                   20.9  |           84.96 |             68.94 |       0.1   |         nan |       nan |        7.2  |         7.37 |          9.08 |        0.67 |                 nan |              nan |                  12 |                  0.63 |
|           15 | WB       | Weibo Corporation                    | OTHER    |                1.44 |                  78.6  |                    67.63 |                 63.55 |              69.99 |                63.48 |                   36.52 |           62.8  |             19.72 |     nan     |         nan |       nan |        1.87 |         5.3  |          5.62 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|           16 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              107.26 |                  79.06 |                    67.35 |                 64.87 |              72.79 |                49.32 |                   50.68 |           45.65 |             69.88 |       0.146 |         nan |       nan |        1.77 |         7.4  |          4.6  |        4.14 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.54 |                  56.79 |                    67.04 |                 70.66 |              61.46 |                79.5  |                   20.5  |           95.16 |             62.56 |     nan     |         nan |       nan |      nan    |         8.7  |          6.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.26 |                  73.76 |                    74.49 |                 76.27 |              74.53 |                86.9  |                   13.1  |           85.52 |             57.76 |       0.807 |         nan |       nan |      nan    |       -84.38 |          2.26 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            4 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  69.44 |                    73.34 |                 75.68 |              70.82 |                83.16 |                   16.84 |           92.69 |             58.61 |       0.155 |         nan |       nan |        0.74 |         5.21 |          5.04 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | 0P6O.IL  | Volkswagen AG                    | OTHER    |               42.2  |                  73.72 |                    74.04 |                 74.8  |              72.8  |                69.11 |                   30.89 |           80.16 |            nan    |       0.41  |         nan |       nan |        7.45 |       nan    |          2.74 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              220.89 |                  62.12 |                    70.9  |                 73.8  |              66.66 |                82.97 |                   17.03 |           91.6  |             70.04 |     nan     |         nan |       nan |      nan    |        10.07 |         10.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.61 |                  72.52 |                    72.29 |                 73.7  |              72.69 |                78.17 |                   21.83 |           78.88 |             64.14 |       0.173 |         nan |       nan |        4.3  |         2.85 |          5.41 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | 0Q2N.IL  | K+S Aktiengesellschaft           | OTHER    |                3.31 |                  73.09 |                    73.65 |                 73.32 |              74.29 |                79.11 |                   20.89 |           70.25 |            nan    |       0.224 |         nan |       nan |        1.54 |       nan    |          3.09 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            8 | SDF.DE   | K+S Aktiengesellschaft           | EUROPE   |                3.05 |                  67.26 |                    71.11 |                 72.43 |              68    |                78.77 |                   21.23 |           89.01 |             53.93 |       0.112 |         nan |       nan |        2.13 |        14.63 |          2.88 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|            9 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.45 |                  71.23 |                    70.73 |                 72.22 |              69.62 |                67.91 |                   32.09 |           83.23 |             61.15 |       0.021 |         nan |       nan |        3.9  |         6.77 |          4.69 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO      | FRO                              | US       |                8.49 |                  60.79 |                    68.97 |                 72    |              64.56 |                76.69 |                   23.31 |           90.65 |             69.87 |     nan     |         nan |       nan |      nan    |        10.28 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | SAP.DE   | SAP SE                           | EUROPE   |              212.67 |                  70.26 |                    71.86 |                 71.48 |              69.28 |                76.31 |                   23.69 |           83.91 |             49.61 |       0.043 |         nan |       nan |       17.98 |        22.02 |         27.58 |        1.89 |                 nan |              nan |                  12 |                  0.63 |
|           14 | HRB      | H&R Block, Inc.                  | US       |                5.4  |                  60.66 |                    67.78 |                 70.74 |              64.81 |                79.1  |                   20.9  |           84.96 |             68.94 |       0.1   |         nan |       nan |        7.2  |         7.37 |          9.08 |        0.67 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR  | CMBT.BR                          | EUROPE   |                4.54 |                  56.79 |                    67.04 |                 70.66 |              61.46 |                79.5  |                   20.5  |           95.16 |             62.56 |     nan     |         nan |       nan |      nan    |         8.7  |          6.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | STNE     | StoneCo Ltd.                     | OTHER    |                1.92 |                  75.56 |                    71.33 |                 70.64 |              70.35 |                69.36 |                   30.64 |           84.18 |             34.59 |       0.612 |         nan |       nan |        1.62 |         4.16 |          3.66 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | KDP      | KDP                              | US       |               37.35 |                  55.46 |                    66.01 |                 69.46 |              61.54 |                79.62 |                   20.38 |           86.59 |             72.72 |     nan     |         nan |       nan |      nan    |        12.58 |         32.21 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           18 | HMC      | Honda Motor Co., Ltd.            | OTHER    |               35.77 |                  60.11 |                    65.58 |                 68.91 |              64.48 |                71.42 |                   28.58 |           74.55 |             83.4  |       0.04  |         nan |       nan |        7.16 |         6.46 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|           10 | GSL      | Global Ship Lease, Inc.          | OTHER    |                1.38 |                  76.42 |                    69.99 |                 68.9  |              71.59 |                73.32 |                   26.68 |           73.8  |             33.74 |       0.081 |         nan |       nan |        3.83 |         5.02 |          4.34 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | NAT      | NAT                              | US       |                1.26 |                  55.48 |                    65.41 |                 68.81 |              61    |                76.43 |                   23.57 |           85.74 |             72.96 |     nan     |         nan |       nan |      nan    |        15.19 |         11.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAGP     | PAGP                             | US       |                5.71 |                  52.04 |                    64.87 |                 68.73 |              60.56 |                83.48 |                   16.52 |           82.8  |             80.61 |     nan     |         nan |       nan |      nan    |        13.24 |         81.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | IHS      | IHS Holding Limited              | OTHER    |                2.45 |                  74.37 |                    68.79 |                 68.73 |              72.69 |                60.25 |                   39.75 |           55.09 |             82.99 |      -0.114 |         nan |       nan |        7.5  |        15.27 |          5.15 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR   | AGS.BR                           | EUROPE   |               15.73 |                  61.84 |                    66.83 |                 68.41 |              63.58 |                76.79 |                   23.21 |           84.86 |             52.32 |     nan     |         nan |       nan |      nan    |         8.73 |          7.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                                | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | HRB      | H&R Block, Inc.                                     | US       |                5.4  |                     0.06 |    -0.04 |      0.11 |                  80.08 |                        77.9  |         72.1  |         77.11 |          71.77 |        69.86 |           84.96 |             68.94 |         6.34 |
|               2 | ARGX.BR  | ARGX.BR                                             | EUROPE   |               55.44 |                     0.02 |     0.01 |      0.22 |                  48.93 |                        77.33 |         82.77 |         75.57 |          68.61 |        61.53 |           92.77 |             67.02 |         6.14 |
|               3 | AVAH     | AVAH                                                | US       |                2.53 |                     0.03 |    -0.01 |      0.44 |                  55.7  |                        77.07 |         84.95 |         80.89 |          73.2  |        70.96 |           92.9  |             51.06 |         7.52 |
|               4 | CMBT.BR  | CMBT.BR                                             | EUROPE   |                4.54 |                     0.02 |     0.01 |      0.12 |                  42.36 |                        76.04 |         82.53 |         79.36 |          81.63 |        82.97 |           95.16 |             62.56 |         4.05 |
|               5 | MGTX     | MGTX                                                | US       |                1.17 |                     0.05 |    -0.05 |      0.15 |                  83.31 |                        75.55 |         68.92 |         77.33 |          73.05 |        61.89 |           69.95 |             69.34 |         6.86 |
|               6 | TNK      | Teekay Tankers Ltd.                                 | OTHER    |                2.63 |                     0.04 |    -0.02 |      0.15 |                  67.35 |                        75.51 |         78.23 |         75.38 |          72.27 |        69.68 |           74.06 |             76.51 |         5.17 |
|               7 | NAT      | NAT                                                 | US       |                1.26 |                     0.02 |     0    |      0.1  |                  46.06 |                        74.71 |         77.11 |         79.41 |          78.04 |        75.15 |           85.74 |             72.96 |         4.9  |
|               8 | KRX.IR   | KRX.IR                                              | EUROPE   |               18.23 |                     0.03 |    -0.01 |      0.21 |                  55.71 |                        74.71 |         80.75 |         71.12 |          66.55 |        64.2  |           97.19 |             43.58 |         5.31 |
|               9 | CCC      | CCC                                                 | US       |                3.67 |                     0.05 |    -0.03 |      0.14 |                  74.71 |                        74.21 |         71.02 |         72.65 |          66.19 |        68.6  |           86.38 |             62.7  |         8.07 |
|              10 | GL9.IR   | GL9.IR                                              | EUROPE   |                5.45 |                     0.05 |    -0    |      0.01 |                  70.72 |                        74.16 |         58.57 |         65.24 |          76.44 |        71.53 |           97.19 |             76.61 |         2.32 |
|              11 | VWS.CO   | VWS.CO                                              | EUROPE   |               27.29 |                     0.04 |    -0.01 |      0.19 |                  65.21 |                        73.94 |         79.1  |         67.34 |          65.45 |        61.34 |           86.43 |             48.83 |         5.81 |
|              12 | GGN      | GAMCO Global Gold, Natural Resources & Income Trust | US       |                0.75 |                     0.02 |    -0.02 |      0.13 |                  59.15 |                        73.73 |         74.39 |         63.55 |          59.84 |        59.78 |           78.14 |             80.27 |         2.29 |
|              13 | CHYM     | Chime Financial, Inc.                               | US       |               10.32 |                     0.05 |    -0.04 |      0.27 |                  81.02 |                        72.96 |         75.72 |         75.69 |          65.47 |        58.56 |           62.8  |             69.3  |         7.84 |
|              14 | NTNX     | NTNX                                                | US       |               15.52 |                     0.05 |     0    |      0.08 |                  63.61 |                        72.26 |         71    |         70.31 |          66.61 |        61.63 |           94.93 |             54.92 |         7.04 |
|              15 | SYENS.BR | SYENS.BR                                            | EUROPE   |                8.08 |                     0.04 |    -0    |      0.02 |                  61.55 |                        72.17 |         67.04 |         75.55 |          68.57 |        56.99 |           63.3  |             83.36 |         5.37 |
|              16 | ABNB     | ABNB                                                | US       |               94.09 |                     0.04 |    -0.04 |      0.22 |                  74.82 |                        71.84 |         76.21 |         73.62 |          63.6  |        54.21 |           67.67 |             59.85 |         4.96 |
|              17 | BION.SW  | BB Biotech AG                                       | EUROPE   |                3.26 |                     0.02 |    -0.02 |      0.1  |                  52.31 |                        71.46 |         74.45 |         75.7  |          76.55 |        81.19 |           85.52 |             57.76 |         2.3  |
|              18 | GEO      | The GEO Group, Inc.                                 | US       |                3.46 |                     0.07 |    -0.05 |     -0.02 |                  77.35 |                        71.46 |         50.82 |         70.04 |          73.9  |        68.17 |           74.35 |             66.42 |         5.72 |
|              19 | DLO      | DLO                                                 | US       |                3.76 |                     0.05 |    -0.05 |     -0.03 |                  77.84 |                        71.38 |         57.61 |         69.5  |          65.96 |        64.53 |           73.54 |             68.3  |         6.07 |
|              20 | ELF      | e.l.f. Beauty, Inc.                                 | US       |                5.36 |                     0.03 |    -0    |      0.2  |                  57.35 |                        71.25 |         72.63 |         70.07 |          61.11 |        57.81 |           86.23 |             60.57 |         8.6  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | SNOW     | Snowflake Inc.                                       | US       |               95.41 |             61.54 |         61.48 |         69.16 |          61.6  |        47.92 |           47.79 |             59.29 |             25.39 |         8.5  |             85.38 | swing              |               -4.98 |                 -0.27 |                 0.28 |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.09 |             53.13 |         53.71 |         42.82 |          52.55 |        62.4  |           82.66 |             42.75 |             53.47 |         8.5  |             75.81 | long               |                2.72 |                  3.45 |                 3.35 |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1513.89 |             51.5  |         42.62 |         43.49 |          59.51 |        60.55 |           84.11 |             65.3  |             28.45 |         8.5  |             89.18 | long               |               -0.61 |                  0.3  |                 0.22 |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.69 |             44.19 |         32.11 |         39.45 |          48.93 |        62.85 |           60.38 |             53.15 |             93.7  |         8.5  |             82.14 | long               |                0.49 |                 -0.23 |                -0.06 |
|    nan | MTRX     | Matrix Service Company                               | US       |                0.26 |             43.91 |         38.7  |         38.74 |          49.08 |        60.17 |           56.01 |             61.98 |             87.11 |         8.5  |             80.44 | long               |                2.63 |                  1.33 |                 1.46 |
|    nan | ORCL     | Oracle Corporation                                   | US       |              350.39 |             40.04 |         38.86 |         35.36 |          41.23 |        45.32 |           56.09 |             59.81 |             35    |         7.94 |             89.54 | long               |               -3.36 |                 -1.21 |                -1.3  |
|    nan | SHOE     | Shoe Station Group Inc.                              | US       |                0.3  |             30.18 |         22.93 |         25.99 |          34.38 |        45.54 |           35.15 |             39.12 |             74.69 |         7.12 |             84.21 | long               |               -1.7  |                  0.51 |               nan    |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    265 | IHS      | IHS Holding Limited          | OTHER    |                2.45 |             59.6  |         59.69 |         56.36 |          59.51 |        61.75 |           55.09 |             82.99 |             65.66 |         2.54 |             72.29 | long               |               -0.25 |                  4.07 |                 4.01 |
|    650 | LKFT     | Lakefront Biotherapeutics NV | OTHER    |                1.61 |             41.14 |         55.96 |         40.17 |          37.75 |        42.1  |           38.24 |             45.81 |             47.73 |         5.15 |             76.99 | short              |                0.87 |                  3.95 |                 3.33 |
|     37 | AGS.BR   | AGS.BR                       | EUROPE   |               15.73 |             72.09 |         70.37 |         71.65 |          72.53 |        74.73 |           84.86 |             52.32 |             69.01 |         1.16 |             69.68 | long               |                2.21 |                  3.92 |                 3.52 |
|    148 | SHEL.L   | SHEL.L                       | EUROPE   |            18882    |             64.65 |         68.45 |         57    |          60.85 |        69.04 |          nan    |            nan    |            nan    |         2.97 |             55.84 | long               |               13.86 |                  3.76 |                 3.35 |
|     46 | SDF.DE   | K+S Aktiengesellschaft       | EUROPE   |                3.05 |             71.23 |         79.81 |         66.79 |          68.05 |        74.41 |           89.01 |             53.93 |             67.2  |         3.88 |             74.23 | short              |               14.64 |                  3.71 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                             | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    447 | AMC      | AMC Entertainment Holdings, Inc. | US       |                1.98 |             52.49 |         47.97 |         63.35 |          57    |        46.5  |           44.64 |             66.52 |             40.98 |         9.13 |             78.47 | swing              |              -20.92 |                 -3.56 |                -2.48 |
|    696 | FVRR     | Fiverr International Ltd.        | OTHER    |                0.29 |             33.2  |         34.57 |         25.04 |          31.84 |        45.4  |           50.69 |             15.4  |             70.39 |         8.52 |             84.81 | long               |              -12.28 |                 -2.61 |                -2.58 |
|    707 | LBTYA    | Liberty Global Ltd.              | OTHER    |                3.09 |             29.93 |         36.95 |         27.46 |          29.18 |        30.68 |           19.66 |             43.78 |             37.94 |         5.27 |             79.2  | short              |               -1.38 |                 -2.49 |                -2.26 |
|    712 | LBTYK    | Liberty Global Ltd.              | OTHER    |                3.04 |             28.65 |         42.74 |         27.36 |          27.58 |        29.71 |           19.66 |             37.23 |             38.7  |         4.7  |             72.93 | short              |               -1.78 |                 -2.36 |                -2.22 |
|    642 | ZIP      | ZIP                              | US       |                0.29 |             41.86 |         37.5  |         53.16 |          46.21 |        30.06 |           19.32 |             53.23 |             17.58 |         9.51 |             67.75 | swing              |               -2.84 |                 -2.01 |                -0.88 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.89

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
- Excluded by hard/data filters: **274**
- Event watch (otherwise eligible): **7**
- Final eligible: **719**
- Eligible change vs previous stored run: **+3**

Top exclusion categories:
- liquidity: 231
- price: 167
- market_cap: 122
- price_history: 12
- data_confidence: 10
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| CMBT.BR | 1 |  | 4 |  | 2 | main,pullback |
| NAT | 7 |  | 7 |  | 2 | main,pullback |
| AVAH | 10 |  | 3 |  | 2 | main,pullback |
| BION.SW | 16 | 1 | 17 | 1 | 1 | value,quality_value |
| PARR | 19 | 9 |  | 7 | 1 | value,quality_value |
| HRB | 39 | 14 | 1 | 9 | 1 | pullback,quality_value |
| SDF.DE | 46 | 8 |  | 6 | 1 | value,quality_value |
| DDI | 55 | 4 | 26 | 2 | 1 | value,quality_value |
| 0Q2N.IL | 67 | 3 |  | 5 | 1 | value,quality_value |
| IRWD | 86 | 5 | 59 | 4 | 1 | value,quality_value |
| SAP.DE | 185 | 6 | 32 | 8 | 1 | value,quality_value |
| 0P6O.IL | 492 | 2 |  | 3 | 1 | value,quality_value |
| STNE | 644 | 7 |  | 10 | 1 | value,quality_value |
| FRO | 2 |  |  |  | 1 | main |
| KIN.BR | 3 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (CMBT.BR, FRO, KIN.BR, ANF, DINO, PAGP, PR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (CMBT.BR, KRX.IR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | HRB | value+pullback | 73.68 | 60.66 | 80.08 | 84.96 | 68.94 | 79.10 | 71.94 |
| 2 | BION.SW | value+pullback | 71.19 | 73.76 | 52.31 | 85.52 | 57.76 | 86.90 | 76.12 |
| 3 | IRWD | value+pullback | 71.05 | 72.52 | 61.68 | 78.88 | 64.14 | 78.17 | 68.17 |
| 4 | DDI | value+pullback | 69.63 | 69.44 | 49.61 | 92.69 | 58.61 | 83.16 | 70.51 |
| 5 | SAP.DE | value+pullback | 69.27 | 70.26 | 61.52 | 83.91 | 49.61 | 76.31 | 63.12 |
| 6 | TNK | value+pullback | 69.00 | 58.08 | 67.35 | 74.06 | 76.51 | 79.88 | 73.82 |
| 7 | CEF | value+pullback | 68.31 | 58.24 | 79.52 | 67.13 | 80.27 | 64.32 | 56.37 |
| 8 | GEO | value+pullback | 66.90 | 55.54 | 77.35 | 74.35 | 66.42 | 65.53 | 69.10 |
| 9 | HMC | value+pullback | 66.72 | 60.11 | 59.53 | 74.55 | 83.40 | 71.42 | 66.56 |
| 10 | AMV0.DE | value+pullback | 65.44 | 72.75 | 55.85 | 56.21 | 66.98 | 72.65 | 45.50 |
| 11 | GSL | value+pullback | 65.35 | 76.42 | 53.27 | 73.80 | 33.74 | 73.32 | 65.70 |
| 12 | UNIT | value+pullback | 65.19 | 80.26 | 80.23 | 63.19 | 28.76 | 43.49 | 42.36 |
| 13 | XNET | value+pullback | 65.00 | 59.67 | 68.31 | 57.83 | 80.27 | 66.58 | 43.48 |
| 14 | MFA | value+pullback | 63.50 | 58.87 | 73.27 | 77.53 | 34.32 | 62.33 | 40.86 |
| 15 | ETG | value+pullback | 62.99 | 55.06 | 50.69 | 69.45 | 80.27 | 76.76 | 60.64 |
| 16 | WKC | value+pullback | 62.56 | 58.31 | 54.52 | 67.70 | 75.06 | 68.90 | 68.27 |
| 17 | INVA | value+pullback | 61.13 | 64.00 | 49.55 | 73.67 | 35.68 | 74.58 | 49.57 |
| 18 | ALL-PH | value+pullback | 60.58 | 62.53 | 63.57 | 70.71 | 39.15 | 57.06 | 43.75 |
| 19 | NWL | value+pullback | 59.81 | 55.79 | 63.65 | 72.10 | 61.37 | 51.06 | 65.48 |
| 20 | MAGN | value+pullback | 59.35 | 72.36 | 58.49 | 52.90 | 36.30 | 57.25 | 45.84 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 10/10 | 10/10 | 9/10 | 0/10 | 69.2 | 3 / 7 |
| Top 25 | 23/25 | 25/25 | 25/25 | 23/25 | 0/25 | 69.7 | 6 / 19 |
| Top 50 | 46/50 | 50/50 | 50/50 | 46/50 | 0/50 | 69.5 | 15 / 35 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=5, large_20_100b=1
