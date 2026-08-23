# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-23

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

- **EUROPE:** 86.5/100
- **OTHER:** 74.8/100
- **US:** 84.5/100

## Main multi-horizon ranking

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PBF      | PBF    | US       |                7.46 |             81.16 |         82.15 |         85.84 |          80.17 |        75.25 |           52.54 |             74.16 |             93.24 |         7.14 |             69.23 | swing              |                3.25 |                  0.7  |                  nan |
|      2 | SM       | SM     | US       |                7.58 |             79.45 |         79.73 |         75.84 |          79.17 |        83.06 |           80.72 |             69.4  |             97.24 |         7.05 |             68.66 | long               |                4.26 |                  1.22 |                  nan |
|      3 | CRGY     | CRGY   | US       |                4.74 |             78.86 |         82.98 |         76.15 |          76.97 |        80.74 |           73.07 |             82.32 |             96.04 |         6.19 |             67.05 | short              |                0.82 |                nan    |                  nan |
|      4 | ERO      | ERO    | US       |                3.52 |             78.84 |         88.28 |         77.79 |          75.09 |        79.89 |           84.88 |             48.14 |             79.98 |         7.57 |             69.68 | short              |                0.08 |                  1.1  |                  nan |
|      5 | DHT      | DHT    | US       |                2.74 |             78.82 |         80.04 |         74.92 |          77.6  |        80.77 |           89.73 |             66.2  |             71.4  |         4.29 |             69.68 | long               |                3.92 |                  0.94 |                  nan |
|      6 | AVAH     | AVAH   | US       |                2.46 |             78.68 |         86.18 |         82.45 |          74.91 |        72.66 |           93.53 |             51.25 |             44.1  |         7.37 |             68.66 | short              |               10.13 |                  2.1  |                  nan |
|      7 | HALO     | HALO   | US       |               10.51 |             78.19 |         85.25 |         81.98 |          74.39 |        73.77 |           86.35 |             56.02 |             57.97 |         5.59 |             68.66 | short              |              nan    |                nan    |                  nan |
|      8 | KIN.BR   | KIN.BR | EUROPE   |                1.2  |             76.82 |         81.25 |         80.93 |          72.72 |        64.63 |           88.21 |             66.02 |             22.5  |         4.17 |             69.68 | short              |                5.73 |                  1.91 |                  nan |
|      9 | JCAP     | JCAP   | US       |                1.1  |             76.61 |         74.01 |         76.94 |          76.28 |        83.61 |           86.44 |             87.98 |             85.31 |         5.55 |             67.64 | long               |                1.06 |                nan    |                  nan |
|     10 | PR       | PR     | US       |               17.03 |             76.51 |         77.14 |         75.49 |          76.7  |        76.32 |           77.23 |             70.76 |             71.78 |         4.19 |             68.32 | short              |                3.64 |                  1.25 |                  nan |
|     11 | APA      | APA    | US       |               13.02 |             76.51 |         82.17 |         74.09 |          76.72 |        76.29 |           77.76 |             65.54 |             73.33 |         5.49 |             68.66 | short              |                5.4  |                  1.61 |                  nan |
|     12 | AUTL     | AUTL   | US       |                0.55 |             76.44 |         88.97 |         80.35 |          70.18 |        72.52 |           54.23 |             70.97 |             99.5  |         7.98 |             65.82 | short              |                3.36 |                  0.68 |                  nan |
|     13 | TALO     | TALO   | US       |                2.5  |             76.3  |         83.9  |         75.41 |          77.19 |        75.13 |           70.33 |             92.2  |             68.29 |         5.56 |             67.5  | short              |                0.58 |                nan    |                  nan |
|     14 | WT       | WT     | US       |                3.05 |             76.1  |         80.22 |         78.36 |          73.83 |        66.58 |           74.87 |             73.6  |             36.8  |         5.36 |             69.68 | short              |                2.36 |                  1    |                  nan |
|     15 | U        | U      | US       |               17.69 |             75.56 |         84.65 |         86.08 |          66.48 |        50.04 |           45.73 |             92.09 |             19.58 |         8.33 |             69.68 | swing              |                0.1  |                 -0.13 |                  nan |
|     16 | OVV      | OVV    | US       |               15.83 |             75.52 |         74.88 |         74.93 |          76.65 |        76.1  |           67.77 |             78.9  |             81.99 |         3.94 |             69.34 | medium             |                2.64 |                  0.75 |                  nan |
|     17 | SBLK     | SBLK   | US       |                2.92 |             75.4  |         78.38 |         71.87 |          73.01 |        77.79 |           76.6  |             52.3  |             88.29 |         4.04 |             69.34 | short              |               -0.84 |                nan    |                  nan |
|     18 | CAKE     | CAKE   | US       |                4.83 |             74.98 |         82.21 |         78.35 |          71.61 |        64.51 |           86.45 |             43.99 |             23.23 |         5.79 |             67.18 | short              |                0.73 |                nan    |                  nan |
|     19 | DELL     | DELL   | US       |              244.6  |             74.94 |         51.78 |         81.07 |          81.48 |        68.8  |           71.36 |             85.07 |             35.5  |         7.77 |             68.77 | medium             |                0.88 |                 -0.09 |                  nan |
|     20 | CVE      | CVE    | US       |               52    |             74.79 |         77.63 |         72.41 |          75.74 |        73.84 |           79.06 |             67.26 |             61.78 |         4.78 |             69.68 | short              |                5.11 |                  1.35 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                                          | EUROPE   |                3.3  |                  78.19 |                    76.08 |                 76.99 |              77.45 |                85.69 |                   14.31 |           81.41 |             57.31 |       0.801 |         nan |       nan |      nan    |       -84.98 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            2 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.61 |                  70.74 |                    74.12 |                 77.09 |              73.03 |                81.05 |                   18.95 |           87.37 |             75.06 |       0.172 |         nan |       nan |        4.31 |         2.91 |          5.43 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | STNE     | StoneCo Ltd.                                           | OTHER    |                1.85 |                  75.05 |                    72.28 |                 72.32 |              71.21 |                70.57 |                   29.43 |           85.05 |             44.68 |       0.633 |         nan |       nan |        1.61 |         4.03 |          3.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | 0Q2N.IL  | K+S Aktiengesellschaft                                 | OTHER    |                3.2  |                  72.71 |                    70.31 |                 68.94 |              72.32 |                70.78 |                   29.22 |           61.05 |            nan    |       0.232 |         nan |       nan |        1.54 |       nan    |          2.98 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | GSL      | Global Ship Lease Inc New                              | OTHER    |                1.35 |                  75.67 |                    69.49 |                 68.46 |              70.93 |                72.87 |                   27.13 |           73.91 |             33.37 |       0.082 |         nan |       nan |        3.78 |         4.95 |          4.28 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|          nan | ADAM     | ADAM                                                   | US       |                0.77 |                  65.09 |                    69.26 |                 70.87 |              65.68 |                75.48 |                   24.52 |           89.65 |             52.27 |     nan     |         nan |       nan |      nan    |         7.96 |          5.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                                    | US       |                2.74 |                  61.85 |                    69.18 |                 71.81 |              65.1  |                77.48 |                   22.52 |           89.73 |             66.2  |     nan     |         nan |       nan |      nan    |        10.54 |          6.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.65 |                  69.59 |                    69.15 |                 70.95 |              69.29 |                75.26 |                   24.74 |           79.57 |             56.36 |       1.028 |         nan |       nan |        5.16 |      -114.47 |          2.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.39 |                  68.27 |                    68.88 |                 70.39 |              67.72 |                69.06 |                   30.94 |           80.43 |             61.33 |       0.021 |         nan |       nan |        3.86 |         6.69 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | YALA     | Yalla Group Limited                                    | OTHER    |                0.73 |                  69.16 |                    68.74 |                 70.19 |              67.33 |                76.6  |                   23.4  |           87.83 |             37.45 |     nan     |         nan |       nan |        0.21 |         6.56 |          7.42 |        0.59 |                 nan |              nan |                   8 |                  0.42 |
|            9 | MC.PA    | LVMH Moët Hennessy - Louis Vuitton, Société Européenne | EUROPE   |              223.07 |                  66.73 |                    68.52 |                 68.07 |              66.71 |                71.58 |                   28.42 |           74.57 |             57.76 |       0.052 |         nan |       nan |       12.45 |        17.75 |         20.62 |        1.84 |                 nan |              nan |                  12 |                  0.63 |
|           10 | AKER.OL  | Aker ASA                                               | EUROPE   |               10.12 |                  64.7  |                    68.23 |                 70.02 |              64.49 |                69.18 |                   30.82 |           89.4  |             54.49 |       0.11  |         nan |       nan |        5.44 |        56.69 |          3.91 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|           11 | IHS      | IHS Holding Limited                                    | OTHER    |                2.43 |                  72.39 |                    67.99 |                 68.23 |              71.42 |                61.14 |                   38.86 |           56.2  |             82.92 |      -0.114 |         nan |       nan |        7.5  |        15.27 |          5.15 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BEN      | BEN                                                    | US       |               14.93 |                  57.54 |                    67.85 |                 71.26 |              63.15 |                81.39 |                   18.61 |           90.2  |             70.72 |     nan     |         nan |       nan |      nan    |        10.84 |         23.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | WB       | Weibo Corporation                                      | OTHER    |                1.48 |                  78.6  |                    67.77 |                 63.88 |              69.99 |                63.75 |                   36.25 |           64.25 |             19.21 |     nan     |         nan |       nan |        1.98 |         5.34 |          5.81 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SM       | SM                                                     | US       |                7.58 |                  63.39 |                    67.57 |                 69.4  |              64.92 |                68.53 |                   31.47 |           80.72 |             69.4  |     nan     |         nan |       nan |      nan    |         4.98 |          6.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                                               | EUROPE   |              220.22 |                  65.32 |                    66.96 |                 67.92 |              62.92 |                71.06 |                   28.94 |           92.86 |             31    |     nan     |         nan |       nan |      nan    |        10.07 |         10.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | UNIT     | Uniti Group Inc.                                       | US       |                2.07 |                  80.26 |                    66.77 |                 63.82 |              68.61 |                44.87 |                   55.13 |           67.41 |             27.45 |      -0.107 |         nan |       nan |        9.1  |       -14.04 |          2.6  |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BMY      | BMY                                                    | US       |              117.21 |                  63.07 |                    66.23 |                 67.41 |              63.43 |                71.82 |                   28.18 |           82.45 |             50.92 |     nan     |         nan |       nan |      nan    |        10.22 |         14.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                   | US       |              220.49 |                  67.18 |                    65.84 |                 65.55 |              64.63 |                66.19 |                   33.81 |           75.48 |             43.49 |     nan     |         nan |       nan |      nan    |        10.58 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.61 |                  70.74 |                    74.12 |                 77.09 |              73.03 |                81.05 |                   18.95 |           87.37 |             75.06 |       0.172 |         nan |       nan |        4.31 |         2.91 |          5.43 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            1 | BION.SW  | BB Biotech AG                                          | EUROPE   |                3.3  |                  78.19 |                    76.08 |                 76.99 |              77.45 |                85.69 |                   14.31 |           81.41 |             57.31 |       0.801 |         nan |       nan |      nan    |       -84.98 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            3 | STNE     | StoneCo Ltd.                                           | OTHER    |                1.85 |                  75.05 |                    72.28 |                 72.32 |              71.21 |                70.57 |                   29.43 |           85.05 |             44.68 |       0.633 |         nan |       nan |        1.61 |         4.03 |          3.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT      | DHT                                                    | US       |                2.74 |                  61.85 |                    69.18 |                 71.81 |              65.1  |                77.48 |                   22.52 |           89.73 |             66.2  |     nan     |         nan |       nan |      nan    |        10.54 |          6.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                                    | US       |               14.93 |                  57.54 |                    67.85 |                 71.26 |              63.15 |                81.39 |                   18.61 |           90.2  |             70.72 |     nan     |         nan |       nan |      nan    |        10.84 |         23.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.65 |                  69.59 |                    69.15 |                 70.95 |              69.29 |                75.26 |                   24.74 |           79.57 |             56.36 |       1.028 |         nan |       nan |        5.16 |      -114.47 |          2.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | ADAM     | ADAM                                                   | US       |                0.77 |                  65.09 |                    69.26 |                 70.87 |              65.68 |                75.48 |                   24.52 |           89.65 |             52.27 |     nan     |         nan |       nan |      nan    |         7.96 |          5.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.39 |                  68.27 |                    68.88 |                 70.39 |              67.72 |                69.06 |                   30.94 |           80.43 |             61.33 |       0.021 |         nan |       nan |        3.86 |         6.69 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | YALA     | Yalla Group Limited                                    | OTHER    |                0.73 |                  69.16 |                    68.74 |                 70.19 |              67.33 |                76.6  |                   23.4  |           87.83 |             37.45 |     nan     |         nan |       nan |        0.21 |         6.56 |          7.42 |        0.59 |                 nan |              nan |                   8 |                  0.42 |
|           10 | AKER.OL  | Aker ASA                                               | EUROPE   |               10.12 |                  64.7  |                    68.23 |                 70.02 |              64.49 |                69.18 |                   30.82 |           89.4  |             54.49 |       0.11  |         nan |       nan |        5.44 |        56.69 |          3.91 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SM       | SM                                                     | US       |                7.58 |                  63.39 |                    67.57 |                 69.4  |              64.92 |                68.53 |                   31.47 |           80.72 |             69.4  |     nan     |         nan |       nan |      nan    |         4.98 |          6.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           15 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               37.08 |                  55.89 |                    65.02 |                 69.09 |              63    |                79.81 |                   20.19 |           77.54 |             83.93 |       0.039 |         nan |       nan |        7.16 |         6.73 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|            4 | 0Q2N.IL  | K+S Aktiengesellschaft                                 | OTHER    |                3.2  |                  72.71 |                    70.31 |                 68.94 |              72.32 |                70.78 |                   29.22 |           61.05 |            nan    |       0.232 |         nan |       nan |        1.54 |       nan    |          2.98 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | GSL      | Global Ship Lease Inc New                              | OTHER    |                1.35 |                  75.67 |                    69.49 |                 68.46 |              70.93 |                72.87 |                   27.13 |           73.91 |             33.37 |       0.082 |         nan |       nan |        3.78 |         4.95 |          4.28 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|           11 | IHS      | IHS Holding Limited                                    | OTHER    |                2.43 |                  72.39 |                    67.99 |                 68.23 |              71.42 |                61.14 |                   38.86 |           56.2  |             82.92 |      -0.114 |         nan |       nan |        7.5  |        15.27 |          5.15 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | MC.PA    | LVMH Moët Hennessy - Louis Vuitton, Société Européenne | EUROPE   |              223.07 |                  66.73 |                    68.52 |                 68.07 |              66.71 |                71.58 |                   28.42 |           74.57 |             57.76 |       0.052 |         nan |       nan |       12.45 |        17.75 |         20.62 |        1.84 |                 nan |              nan |                  12 |                  0.63 |
|          nan | KDP      | KDP                                                    | US       |               37.34 |                  54.64 |                    64.61 |                 68    |              59.9  |                76.79 |                   23.21 |           87.19 |             67.32 |     nan     |         nan |       nan |      nan    |        12.64 |         32.36 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                                               | EUROPE   |              220.22 |                  65.32 |                    66.96 |                 67.92 |              62.92 |                71.06 |                   28.94 |           92.86 |             31    |     nan     |         nan |       nan |      nan    |        10.07 |         10.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY                                                   | US       |                4.74 |                  58.63 |                    65.29 |                 67.58 |              63.15 |                70.56 |                   29.44 |           73.07 |             82.32 |     nan     |         nan |       nan |      nan    |         6.55 |        175.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                                | EUROPE   |               18.08 |                  57.41 |                    64.87 |                 67.52 |              59.47 |                76.77 |                   23.23 |           94.77 |             43.16 |     nan     |         nan |       nan |      nan    |        10.5  |         14.2  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                           | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | JCAP     | JCAP                           | US       |                1.1  |                     0.07 |    -0.07 |      0.12 |                  81.56 |                        81.19 |         74.01 |         76.94 |          76.28 |        83.61 |           86.44 |             87.98 |         5.55 |
|               2 | NTAP     | NTAP                           | US       |               32.31 |                     0.07 |    -0.07 |      0.15 |                  81.47 |                        80.64 |         67.2  |         80.69 |          78.84 |        70.37 |           88.04 |             69.76 |         6.32 |
|               3 | KRX.IR   | KRX.IR                         | EUROPE   |               18.1  |                     0.03 |    -0.01 |      0.32 |                  58.17 |                        78.95 |         82.14 |         73.92 |          68.73 |        65.46 |           94.66 |             68.18 |         5.21 |
|               4 | DELL     | DELL                           | US       |              244.6  |                     0.11 |    -0.1  |      0.01 |                  68.21 |                        77.8  |         51.78 |         81.07 |          81.48 |        68.8  |           71.36 |             85.07 |         7.77 |
|               5 | CAKE     | CAKE                           | US       |                4.83 |                     0.03 |    -0    |      0.34 |                  57.81 |                        73.67 |         82.21 |         78.35 |          71.61 |        64.51 |           86.45 |             43.99 |         5.79 |
|               6 | BAX      | BAX                            | US       |               11.66 |                     0.07 |    -0.01 |      0.18 |                  65.25 |                        73.65 |         73.96 |         75.73 |          69.94 |        70.88 |           78.17 |             69.1  |         6.01 |
|               7 | SHOP     | SHOP                           | US       |              165.84 |                     0.06 |    -0.03 |      0.31 |                  78.23 |                        73.54 |         76.15 |         69.41 |          56.91 |        50.49 |           68.62 |             66.72 |         7.73 |
|               8 | JHX      | JHX                            | US       |               15.13 |                     0.02 |    -0.02 |      0.15 |                  55.46 |                        72.94 |         75.37 |         79.65 |          70.39 |        63.8  |           59.87 |             85.51 |         5.99 |
|               9 | BEN      | BEN                            | US       |               14.93 |                     0.04 |     0.01 |      0.06 |                  58.18 |                        72.48 |         67.85 |         70.22 |          77.26 |        80.37 |           90.2  |             70.72 |         3.17 |
|              10 | SYENS.BR | SYENS.BR                       | EUROPE   |                8.15 |                     0.03 |    -0.03 |      0.12 |                  64.95 |                        72.37 |         72.36 |         70.04 |          61.98 |        57.51 |           66.59 |             87.52 |         5.17 |
|              11 | DAR      | DAR                            | US       |                8.88 |                     0.04 |    -0.02 |      0.05 |                  65.99 |                        72.21 |         67.56 |         69.12 |          76.93 |        80.25 |           93.14 |             60.85 |         3.88 |
|              12 | BILL     | BILL                           | US       |                4.08 |                     0.07 |    -0.04 |      0.1  |                  74.26 |                        71.98 |         66.3  |         71.55 |          65.52 |        67.86 |           56.58 |             91.69 |         7.08 |
|              13 | HPE      | HPE                            | US       |               60.61 |                     0.11 |    -0.09 |      0.12 |                  65.09 |                        71.68 |         60.42 |         77.2  |          77.45 |        71.6  |           72.95 |             58.18 |         6.85 |
|              14 | EXK      | EXK                            | US       |                2.69 |                     0.03 |    -0    |      0.36 |                  58.72 |                        71.46 |         78.33 |         61.34 |          61.62 |        68.86 |           60.56 |             75.85 |         8.23 |
|              15 | CART     | CART                           | US       |                9.88 |                     0.02 |     0.02 |      0.18 |                  46.15 |                        71.33 |         78.35 |         76.42 |          70.59 |        69.31 |           69.74 |             75.24 |         5.66 |
|              16 | GENI     | GENI                           | US       |                1.85 |                     0.04 |    -0.04 |      0.24 |                  71.56 |                        71.31 |         72.5  |         73.86 |          65.8  |        68.87 |           66.34 |             69.21 |         9.13 |
|              17 | PARR     | Par Pacific Holdings, Inc.     | US       |                3.39 |                     0.08 |    -0.02 |      0.02 |                  59.2  |                        71.28 |         64.49 |         74.23 |          77.9  |        74.91 |           80.43 |             61.33 |         6.85 |
|              18 | ADAM     | ADAM                           | US       |                0.77 |                     0.03 |    -0.02 |      0.15 |                  59.52 |                        70.91 |         72.43 |         70.51 |          75.82 |        83.07 |           89.65 |             52.27 |         3.02 |
|              19 | RBRK     | RBRK                           | US       |               17.64 |                     0.05 |    -0.02 |      0.37 |                  72.34 |                        70.64 |         75.97 |         77.66 |          60.63 |        45.33 |           55.74 |             65.38 |         8.16 |
|              20 | IRWD     | Ironwood Pharmaceuticals, Inc. | US       |                0.61 |                     0.03 |    -0    |      0.16 |                  56.35 |                        70.49 |         66.61 |         60.51 |          73.51 |        82.28 |           87.37 |             75.06 |         6.51 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4453.39 |             58.33 |         54.07 |         53.86 |          62.58 |        66.13 |           94.07 |             64.9  |             33.41 |         5.58 |             89.49 | long               |                2.31 |                 -0.7  |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.71 |             53.86 |         37.02 |         52.58 |          55.14 |        61.05 |           54.32 |             50.53 |             74.03 |         8.45 |             85.47 | long               |                2.74 |                 -1.83 |                  nan |
|    nan | JOYY     | JOYY Inc.                                            | OTHER    |                3.18 |             53.18 |         52.48 |         58.5  |          53.89 |        46.89 |           49.12 |             45.25 |             28.56 |         8.5  |             82.25 | swing              |              nan    |                 -0.15 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |             49.9  |         46.91 |         43.14 |          52.88 |        63.71 |           83.23 |             42.67 |             54.47 |         3.89 |             75.81 | long               |               -0.52 |                 -0.06 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1501.03 |             49.51 |         34.46 |         42.33 |          56.68 |        59.92 |           81.17 |             57.49 |             33.73 |         6.16 |             89.83 | long               |               -3.08 |                 -0.93 |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.                              | US       |                3.36 |             47.99 |         45.59 |         45.33 |          50.38 |        64.71 |           69.38 |             48.42 |             85.43 |         7.48 |             87.88 | long               |              nan    |                  2.86 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             45.32 |         42.16 |         40.52 |          48.49 |        61.19 |           61.05 |             52.97 |             85.93 |         4.33 |             82.14 | long               |               -1.97 |                 -0.24 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.71 |             38.86 |         41    |         31.6  |          36.72 |        41.73 |           42.43 |             67.71 |             44.52 |         7.07 |             77.1  | long               |               -1.96 |                 -0.5  |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.88 |             37.44 |         30.61 |         33.79 |          41.1  |        53.06 |           47.52 |             43.23 |             78.34 |         6.28 |             78.58 | long               |               -1.42 |                 -1.74 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.21 |             37.31 |         27.81 |         33.93 |          40.69 |        54.7  |           44.85 |             37.1  |             92.92 |         8.5  |             78.43 | long               |               -1.04 |                 -1.48 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.85 |             33.67 |         33.27 |         20.96 |          34.08 |        44.52 |           61.41 |             17.66 |             41.11 |         8.99 |             78.45 | long               |               -3.1  |                 -0.22 |                  nan |
|    nan | LI       | Li Auto Inc.                                         | OTHER    |               10.95 |             29    |         50.38 |         27.1  |          27.04 |        30.91 |           38.8  |             37.33 |             26.11 |         6.79 |             76.54 | short              |              nan    |                nan    |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    614 | CYH      | Community Health Systems, Inc. | US       |                0.36 |             43.83 |         50.56 |         37.33 |          38.57 |        49.09 |           40.47 |             23.73 |             77.27 |         7.77 |             81.72 | short              |               -1.61 |                  4.1  |                  nan |
|    461 | EDIT     | EDIT                           | US       |                0.41 |             52.55 |         67.03 |         55.48 |          49.62 |        45.05 |           48.67 |             28.91 |             38.21 |         9.06 |             66.84 | short              |               11.07 |                  3.57 |                  nan |
|    673 | LKFT     | Lakefront Biotherapeutics NV   | OTHER    |                1.61 |             37.23 |         54.18 |         35.68 |          35.53 |        38.79 |           39.04 |             45.93 |             40.15 |         4.99 |             76.99 | short              |               -1.4  |                  3.54 |                  nan |
|    174 | HOOD     | HOOD                           | US       |               83.25 |             63.66 |         70.96 |         68.17 |          59.14 |        50.55 |           66.56 |             63.12 |             12.77 |         8.65 |             68.2  | short              |                8.2  |                  3.34 |                  nan |
|    186 | ORIC     | ORIC                           | US       |                1.26 |             63.09 |         73.96 |         71.03 |          55.15 |        48.07 |           34.43 |             53.83 |             43.67 |         8.49 |             65.82 | short              |               14.67 |                  3.02 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    487 | OUST     | OUST                         | US       |                2.37 |             51.72 |         45.29 |         55.58 |          57.92 |        47.87 |           50.75 |             56.35 |             24.57 |         9.16 |             66.84 | medium             |               -2.03 |                 -3.1  |                  nan |
|    246 | W        | W                            | US       |               11.91 |             60.92 |         71.15 |         65.88 |          55.96 |        49.27 |           56.48 |             53.1  |             19.78 |         8.75 |             66.39 | short              |              nan    |                 -3.05 |                  nan |
|    394 | UTZ      | UTZ                          | US       |                1.73 |             55.36 |         52.5  |         73.54 |          58.23 |        47.55 |           24.54 |             66.94 |             51.2  |         9    |             69.68 | swing              |               -3.93 |                 -2.89 |                  nan |
|    205 | NNBR     | NNBR                         | US       |                0.27 |             62.39 |         60.25 |         73.5  |          64.53 |        48.86 |           35.02 |             64.72 |             31    |         9.07 |             68.66 | swing              |               -3.41 |                 -2.84 |                  nan |
|    398 | LNC      | Lincoln National Corporation | US       |                6.91 |             55.26 |         49.9  |         57.16 |          54.33 |        56.19 |           44.17 |             62.61 |             73.25 |         4.77 |             82.17 | swing              |               -0.38 |                 -2.73 |                  nan |

## Duplicate-security checks

- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

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
- Excluded by hard/data filters: **280**
- Event watch (otherwise eligible): **12**
- Final eligible: **708**
- Eligible change vs previous stored run: **-6**

Top exclusion categories:
- liquidity: 230
- price: 166
- market_cap: 161
- price_history: 17
- data_confidence: 12
- asset_type: 1
- delisted: 1
- duplicate_listing: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| JCAP | 9 |  | 1 |  | 2 | main,pullback |
| AKER.OL | 21 | 10 |  | 7 | 1 | value,quality_value |
| PARR | 23 | 7 | 17 | 5 | 1 | value,quality_value |
| BION.SW | 38 | 1 |  | 2 | 1 | value,quality_value |
| IRWD | 59 | 2 | 20 | 1 | 1 | value,quality_value |
| GSL | 164 | 5 |  | 10 | 1 | value,quality_value |
| 0Q2N.IL | 193 | 4 |  | 9 | 1 | value,quality_value |
| YALA | 484 | 8 |  | 6 | 1 | value,quality_value |
| NWL.MI | 600 | 6 | 192 | 4 | 1 | value,quality_value |
| STNE | 659 | 3 |  | 3 | 1 | value,quality_value |
| PBF | 1 |  |  |  | 1 | main |
| SM | 2 |  |  |  | 1 | main |
| CRGY | 3 |  |  |  | 1 | main |
| ERO | 4 |  |  |  | 1 | main |
| DHT | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (SM, CRGY, ERO, DHT, AVAH, HALO, KIN.BR, PR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (SYENS.BR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 74.40 | 69.59 | 83.61 | 79.57 | 56.36 | 75.26 | 44.92 |
| 2 | IRWD | value+pullback | 72.13 | 70.74 | 56.35 | 87.37 | 75.06 | 81.05 | 70.06 |
| 3 | MC.PA | value+pullback | 67.52 | 66.73 | 64.90 | 74.57 | 57.76 | 71.58 | 43.23 |
| 4 | PARR | value+pullback | 67.29 | 68.27 | 59.20 | 80.43 | 61.33 | 69.06 | 74.57 |
| 5 | ETG | value+pullback | 63.43 | 55.12 | 53.19 | 68.30 | 80.49 | 76.53 | 60.44 |
| 6 | INVA | value+pullback | 63.24 | 56.71 | 59.44 | 83.38 | 34.71 | 76.94 | 44.95 |
| 7 | MFA | value+pullback | 61.30 | 57.72 | 66.21 | 77.94 | 33.01 | 62.21 | 41.28 |
| 8 | MSFT | value+pullback | 61.27 | 58.21 | 70.21 | 60.95 | 66.29 | 52.43 | 59.63 |
| 9 | UNIT | value+pullback | 60.92 | 80.26 | 60.06 | 67.41 | 27.45 | 44.87 | 42.83 |
| 10 | TV | value+pullback | 60.76 | 67.97 | 74.47 | 42.79 | 30.42 | 61.47 | 37.96 |
| 11 | ALL-PH | value+pullback | 60.67 | 61.86 | 63.20 | 69.50 | 39.75 | 59.57 | 43.01 |
| 12 | ORCL | value+pullback | 59.88 | 69.90 | 74.09 | 47.06 | 58.79 | 37.26 | 42.13 |
| 13 | VOLV-B.ST | value+pullback | 59.65 | 69.47 | 54.83 | 51.96 | 59.94 | 56.59 | 52.06 |
| 14 | ONIT | value+pullback | 58.65 | 72.98 | 59.74 | 61.82 | 42.09 | 41.70 | 42.05 |
| 15 | BION.SW | value | 58.54 | 78.19 | 30.95 | 81.41 | 57.31 | 85.69 | 73.00 |
| 16 | JCAP | pullback | 58.22 | 58.18 | 81.56 | 86.44 | 87.98 | 80.33 | 76.61 |
| 17 | XNET | value+pullback | 57.71 | 61.49 | 40.47 | 53.95 | 80.24 | 65.12 | 42.73 |
| 18 | WKC | value+pullback | 57.19 | 57.82 | 40.04 | 58.15 | 75.05 | 68.04 | 66.93 |
| 19 | KYN | value+pullback | 55.58 | 57.90 | 51.74 | 54.71 | 54.46 | 58.13 | 52.84 |
| 20 | NTAP | pullback | 55.30 | 40.28 | 81.47 | 88.04 | 69.76 | 73.75 | 74.61 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 68.7 | 2 / 8 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 68.8 | 8 / 17 |
| Top 50 | 50/50 | 50/50 | 50/50 | 50/50 | 0/50 | 68.7 | 21 / 29 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=4
