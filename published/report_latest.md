# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-24

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

- **EUROPE:** 86.7/100
- **OTHER:** 74.3/100
- **US:** 84.4/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PBF      | PBF                        | US       |                7.46 |             81.19 |         82.21 |         85.91 |          80.17 |        75.14 |           52.17 |             74.6  |             93.15 |         7.15 |             69.23 | swing              |                0.03 |                  0.46 |                  nan |
|      2 | SM       | SM                         | US       |                7.57 |             79.32 |         79.64 |         75.72 |          79    |        82.84 |           80.4  |             69.23 |             97.2  |         7.07 |             68.66 | long               |               -0.13 |                  0.95 |                  nan |
|      3 | ERO      | ERO                        | US       |                3.52 |             78.96 |         88.4  |         78.06 |          75.28 |        79.86 |           84.6  |             49.28 |             79.7  |         7.58 |             69.68 | short              |                0.12 |                  1.6  |                  nan |
|      4 | DHT      | DHT                        | US       |                2.73 |             78.9  |         80.12 |         75.06 |          77.68 |        80.74 |           89.57 |             66.47 |             71.26 |         4.3  |             69.68 | long               |                0.08 |                  0.78 |                  nan |
|      5 | CRGY     | CRGY                       | US       |                4.73 |             78.77 |         82.96 |         76.23 |          76.96 |        80.58 |           72.6  |             82.93 |             96    |         6.2  |             67.05 | short              |               -0.09 |                nan    |                  nan |
|      6 | AVAH     | AVAH                       | US       |                2.46 |             78.53 |         86.14 |         82.31 |          74.76 |        72.49 |           93.49 |             50.75 |             43.73 |         7.38 |             68.66 | short              |               -0.15 |                  1.93 |                  nan |
|      7 | HALO     | HALO                       | US       |               10.5  |             78.4  |         85.36 |         82.22 |          74.59 |        73.83 |           86.1  |             57.15 |             57.98 |         5.6  |             68.66 | short              |                0.22 |                 -0.28 |                  nan |
|      8 | KIN.BR   | KIN.BR                     | EUROPE   |                1.2  |             78.08 |         82.4  |         82.62 |          73.76 |        65.93 |           85.8  |             65.57 |             27    |         4.18 |             69.68 | swing              |                1.25 |                  1.64 |                  nan |
|      9 | JCAP     | JCAP                       | US       |                1.1  |             76.62 |         74.02 |         76.98 |          76.27 |        83.53 |           86.37 |             87.66 |             85.1  |         5.56 |             67.64 | long               |                0.01 |                nan    |                  nan |
|     10 | PR       | PR                         | US       |               17.02 |             76.45 |         77.2  |         75.58 |          76.69 |        76.2  |           76.9  |             70.95 |             71.65 |         4.2  |             68.32 | short              |               -0.06 |                  1.15 |                  nan |
|     11 | AUTL     | AUTL                       | US       |                0.55 |             76.36 |         88.95 |         80.35 |          70.1  |        72.38 |           53.84 |             70.98 |             99.5  |         7.99 |             65.82 | short              |               -0.07 |                  0.97 |                  nan |
|     12 | APA      | APA                        | US       |               13.01 |             76.35 |         82.17 |         74.1  |          76.61 |        76.09 |           77.34 |             65.59 |             73.21 |         5.5  |             68.66 | short              |               -0.16 |                  1.26 |                  nan |
|     13 | WT       | WT                         | US       |                3.05 |             76.2  |         80.32 |         78.51 |          73.89 |        66.46 |           74.59 |             74.19 |             36.36 |         5.37 |             69.68 | short              |                0.1  |                nan    |                  nan |
|     14 | TALO     | TALO                       | US       |                2.5  |             75.92 |         83.65 |         75.07 |          76.77 |        74.7  |           69.92 |             90.98 |             68.13 |         5.57 |             67.5  | short              |               -0.38 |                nan    |                  nan |
|     15 | SBLK     | SBLK                       | US       |                2.91 |             75.52 |         78.58 |         72.23 |          73.26 |        77.79 |           76    |             53.66 |             88.35 |         4.05 |             69.34 | short              |                0.12 |                  0.13 |                  nan |
|     16 | OVV      | OVV                        | US       |               15.81 |             75.43 |         74.92 |         74.93 |          76.57 |        75.93 |           67.37 |             78.95 |             81.98 |         3.95 |             69.34 | medium             |               -0.08 |                  0.57 |                  nan |
|     17 | U        | U                          | US       |               17.67 |             75.29 |         84.51 |         85.77 |          66.07 |        49.59 |           45.23 |             91.09 |             19.16 |         8.35 |             69.68 | swing              |               -0.27 |                 -0.26 |                  nan |
|     18 | CAKE     | CAKE                       | US       |                4.82 |             75.21 |         82.36 |         78.58 |          71.84 |        64.58 |           86.51 |             45.01 |             22.84 |         5.8  |             67.18 | short              |                0.23 |                nan    |                  nan |
|     19 | DK       | DK                         | US       |                3.74 |             75.21 |         81.41 |         79.91 |          70.5  |        58.1  |           55.82 |             59.09 |             33.16 |         6.79 |             69.68 | short              |                5.3  |                nan    |                  nan |
|     20 | PARR     | Par Pacific Holdings, Inc. | US       |                3.39 |             75.15 |         64.93 |         74.94 |          78.49 |        75.35 |           80.43 |             62.7  |             65.67 |         6.81 |             85.72 | medium             |                0.58 |                 -0.3  |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.3  |                  78.01 |                    76.19 |                 77.2  |              77.46 |                85.97 |                   14.03 |           81.92 |             58.15 |       0.801 |         nan |       nan |      nan    |       -84.98 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            2 | 0QXR.IL  | Stellantis N.V.                      | OTHER    |               14.49 |                  78.07 |                    75.41 |                 75.19 |              75.41 |                64.76 |                   35.24 |           76.27 |            nan    |       0.446 |         nan |       nan |        1.16 |       nan    |          0.73 |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.61 |                  72.14 |                    74.62 |                 77.26 |              74.07 |                80.97 |                   19.03 |           85.29 |             75.56 |       0.172 |         nan |       nan |        4.31 |         2.91 |          5.43 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | STNE     | StoneCo Ltd.                         | OTHER    |                1.85 |                  75.05 |                    72.42 |                 72.52 |              71.36 |                70.78 |                   29.22 |           85.05 |             45.77 |       0.633 |         nan |       nan |        1.61 |         4.03 |          3.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.14 |                  71.97 |                    71.34 |                 70.69 |              72.34 |                73.84 |                   26.16 |           66.5  |            nan    |       0.236 |         nan |       nan |        1.54 |       nan    |          2.92 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | SDF.DE   | K+S Aktiengesellschaft        N      | EUROPE   |                2.93 |                  68.2  |                    70.53 |                 72.82 |              68.4  |                75.51 |                   24.49 |           88.98 |             57.06 |       0.116 |         nan |       nan |        2.06 |        16.59 |          2.77 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|            7 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.65 |                  68.97 |                    69.43 |                 71.06 |              70.04 |                81.82 |                   18.18 |           77.1  |             56.51 |       1.028 |         nan |       nan |        5.16 |      -114.47 |          2.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            8 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.39 |                  68.27 |                    69.06 |                 70.64 |              67.91 |                69.35 |                   30.65 |           80.43 |             62.7  |       0.021 |         nan |       nan |        3.86 |         6.69 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT      | DHT                                  | US       |                2.73 |                  61.61 |                    69.04 |                 71.71 |              64.95 |                77.46 |                   22.54 |           89.57 |             66.47 |     nan     |         nan |       nan |      nan    |        10.54 |          6.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ADAM     | ADAM                                 | US       |                0.76 |                  64.88 |                    69.02 |                 70.61 |              65.43 |                75.19 |                   24.81 |           89.5  |             51.75 |     nan     |         nan |       nan |      nan    |         7.96 |          5.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | YALA     | Yalla Group Limited                  | OTHER    |                0.73 |                  69.16 |                    68.86 |                 70.35 |              67.45 |                76.79 |                   23.21 |           87.83 |             38.34 |     nan     |         nan |       nan |        0.21 |         5.88 |          7.42 |        0.59 |                 nan |              nan |                   8 |                  0.42 |
|           10 | 0P6O.IL  | Volkswagen AG                        | OTHER    |               41.51 |                  65.02 |                    68.7  |                 70.26 |              66.53 |                72.58 |                   27.42 |           78.3  |            nan    |       0.417 |         nan |       nan |        7.45 |       nan    |          2.7  |        0.69 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BEN      | BEN                                  | US       |               14.91 |                  57.49 |                    67.9  |                 71.34 |              63.17 |                81.54 |                   18.46 |           90.33 |             71.04 |     nan     |         nan |       nan |      nan    |        10.84 |         23.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.57 |                  63.39 |                    67.47 |                 69.25 |              64.86 |                68.27 |                   31.73 |           80.4  |             69.23 |     nan     |         nan |       nan |      nan    |         4.98 |          6.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              220.22 |                  65.32 |                    66.91 |                 67.81 |              63.11 |                70.91 |                   29.09 |           91.2  |             33.2  |     nan     |         nan |       nan |      nan    |        10.06 |         10.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | UNIT     | Uniti Group Inc.                     | US       |                2.07 |                  80.01 |                    66.49 |                 63.48 |              68.43 |                44.62 |                   55.38 |           66.4  |             27.9  |      -0.107 |         nan |       nan |        9.1  |       -14.04 |          2.6  |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BMY      | BMY                                  | US       |              117.12 |                  62.97 |                    66.35 |                 67.57 |              63.56 |                72.16 |                   27.84 |           82.25 |             52.33 |     nan     |         nan |       nan |      nan    |        10.22 |         14.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              220.31 |                  67.23 |                    65.86 |                 65.55 |              64.76 |                66.15 |                   33.85 |           74.8  |             44.51 |     nan     |         nan |       nan |      nan    |        10.58 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              100.87 |                  73.63 |                    65.8  |                 64.78 |              69    |                49.63 |                   50.37 |           54.53 |             70.48 |       0.154 |         nan |       nan |        1.75 |         7    |          4.35 |        4.31 |                 nan |              nan |                  12 |                  0.63 |
|           13 | VOW3.DE  | Volkswagen AG                        | EUROPE   |               37.61 |                  70.95 |                    65.78 |                 63.89 |              66.81 |                61.58 |                   38.42 |           63.05 |             46.44 |       0.375 |         nan |       nan |       13.82 |         3.19 |          7.19 |        0.69 |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                            | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:--------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.  | US       |                0.61 |                  72.14 |                    74.62 |                 77.26 |              74.07 |                80.97 |                   19.03 |           85.29 |             75.56 |       0.172 |         nan |       nan |        4.31 |         2.91 |          5.43 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            1 | BION.SW  | BB Biotech AG                   | EUROPE   |                3.3  |                  78.01 |                    76.19 |                 77.2  |              77.46 |                85.97 |                   14.03 |           81.92 |             58.15 |       0.801 |         nan |       nan |      nan    |       -84.98 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            2 | 0QXR.IL  | Stellantis N.V.                 | OTHER    |               14.49 |                  78.07 |                    75.41 |                 75.19 |              75.41 |                64.76 |                   35.24 |           76.27 |            nan    |       0.446 |         nan |       nan |        1.16 |       nan    |          0.73 |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|            6 | SDF.DE   | K+S Aktiengesellschaft        N | EUROPE   |                2.93 |                  68.2  |                    70.53 |                 72.82 |              68.4  |                75.51 |                   24.49 |           88.98 |             57.06 |       0.116 |         nan |       nan |        2.06 |        16.59 |          2.77 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|            4 | STNE     | StoneCo Ltd.                    | OTHER    |                1.85 |                  75.05 |                    72.42 |                 72.52 |              71.36 |                70.78 |                   29.22 |           85.05 |             45.77 |       0.633 |         nan |       nan |        1.61 |         4.03 |          3.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT      | DHT                             | US       |                2.73 |                  61.61 |                    69.04 |                 71.71 |              64.95 |                77.46 |                   22.54 |           89.57 |             66.47 |     nan     |         nan |       nan |      nan    |        10.54 |          6.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                             | US       |               14.91 |                  57.49 |                    67.9  |                 71.34 |              63.17 |                81.54 |                   18.46 |           90.33 |             71.04 |     nan     |         nan |       nan |      nan    |        10.84 |         23.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | NWL.MI   | NewPrinces S.p.A.               | EUROPE   |                0.65 |                  68.97 |                    69.43 |                 71.06 |              70.04 |                81.82 |                   18.18 |           77.1  |             56.51 |       1.028 |         nan |       nan |        5.16 |      -114.47 |          2.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | 0Q2N.IL  | K+S Aktiengesellschaft          | OTHER    |                3.14 |                  71.97 |                    71.34 |                 70.69 |              72.34 |                73.84 |                   26.16 |           66.5  |            nan    |       0.236 |         nan |       nan |        1.54 |       nan    |          2.92 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            8 | PARR     | Par Pacific Holdings, Inc.      | US       |                3.39 |                  68.27 |                    69.06 |                 70.64 |              67.91 |                69.35 |                   30.65 |           80.43 |             62.7  |       0.021 |         nan |       nan |        3.86 |         6.69 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ADAM     | ADAM                            | US       |                0.76 |                  64.88 |                    69.02 |                 70.61 |              65.43 |                75.19 |                   24.81 |           89.5  |             51.75 |     nan     |         nan |       nan |      nan    |         7.96 |          5.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | YALA     | Yalla Group Limited             | OTHER    |                0.73 |                  69.16 |                    68.86 |                 70.35 |              67.45 |                76.79 |                   23.21 |           87.83 |             38.34 |     nan     |         nan |       nan |        0.21 |         5.88 |          7.42 |        0.59 |                 nan |              nan |                   8 |                  0.42 |
|           10 | 0P6O.IL  | Volkswagen AG                   | OTHER    |               41.51 |                  65.02 |                    68.7  |                 70.26 |              66.53 |                72.58 |                   27.42 |           78.3  |            nan    |       0.417 |         nan |       nan |        7.45 |       nan    |          2.7  |        0.69 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SM       | SM                              | US       |                7.57 |                  63.39 |                    67.47 |                 69.25 |              64.86 |                68.27 |                   31.73 |           80.4  |             69.23 |     nan     |         nan |       nan |      nan    |         4.98 |          6.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP      | KDP                             | US       |               37.3  |                  54.64 |                    64.74 |                 68.16 |              60.06 |                77.03 |                   22.97 |           86.96 |             68.54 |     nan     |         nan |       nan |      nan    |        12.64 |         32.36 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                         | EUROPE   |               18.08 |                  58.52 |                    65.41 |                 67.86 |              60.33 |                76.54 |                   23.46 |           93.69 |             44.18 |     nan     |         nan |       nan |      nan    |        10.5  |         14.2  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                        | EUROPE   |              220.22 |                  65.32 |                    66.91 |                 67.81 |              63.11 |                70.91 |                   29.09 |           91.2  |             33.2  |     nan     |         nan |       nan |      nan    |        10.06 |         10.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                             | US       |              117.12 |                  62.97 |                    66.35 |                 67.57 |              63.56 |                72.16 |                   27.84 |           82.25 |             52.33 |     nan     |         nan |       nan |      nan    |        10.22 |         14.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY                            | US       |                4.73 |                  58.6  |                    65.24 |                 67.53 |              63.17 |                70.49 |                   29.51 |           72.6  |             82.93 |     nan     |         nan |       nan |      nan    |         6.55 |        175.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                              | US       |               62.43 |                  61.2  |                    65.07 |                 66.43 |              61.33 |                73.73 |                   26.27 |           87.32 |             40    |     nan     |         nan |       nan |      nan    |        12.11 |         14.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                           | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | JCAP     | JCAP                           | US       |                1.1  |                     0.07 |    -0.07 |      0.12 |                  81.56 |                        81.14 |         74.02 |         76.98 |          76.27 |        83.53 |           86.37 |             87.66 |         5.56 |
|               2 | NTAP     | NTAP                           | US       |               32.28 |                     0.07 |    -0.07 |      0.15 |                  81.47 |                        80.66 |         67.2  |         80.71 |          78.85 |        70.34 |           87.99 |             69.9  |         6.32 |
|               3 | KRX.IR   | KRX.IR                         | EUROPE   |               18.1  |                     0.03 |    -0.01 |      0.32 |                  58.17 |                        79.3  |         83.43 |         75.76 |          69.94 |        66.73 |           93.4  |             67.88 |         5.22 |
|               4 | DELL     | DELL                           | US       |              244.4  |                     0.11 |    -0.1  |      0.01 |                  68.21 |                        77.68 |         51.74 |         81.01 |          81.34 |        68.6  |           70.99 |             84.93 |         7.78 |
|               5 | CAKE     | CAKE                           | US       |                4.82 |                     0.03 |    -0    |      0.34 |                  57.81 |                        73.91 |         82.36 |         78.58 |          71.84 |        64.58 |           86.51 |             45.01 |         5.8  |
|               6 | BAX      | BAX                            | US       |               11.65 |                     0.07 |    -0.01 |      0.18 |                  65.25 |                        73.64 |         74    |         75.81 |          69.95 |        70.75 |           77.9  |             69.12 |         6.03 |
|               7 | SHOP     | SHOP                           | US       |              165.71 |                     0.06 |    -0.03 |      0.31 |                  78.23 |                        73.51 |         76.18 |         69.45 |          56.86 |        50.29 |           68.37 |             66.72 |         7.73 |
|               8 | JHX      | JHX                            | US       |               15.11 |                     0.02 |    -0.02 |      0.15 |                  55.46 |                        72.79 |         75.33 |         79.58 |          70.26 |        63.57 |           59.55 |             85.13 |         6    |
|               9 | DAR      | DAR                            | US       |                8.88 |                     0.04 |    -0.02 |      0.05 |                  65.99 |                        72.7  |         67.81 |         69.6  |          77.33 |        80.38 |           93    |             62.68 |         3.89 |
|              10 | BEN      | BEN                            | US       |               14.91 |                     0.04 |     0.01 |      0.06 |                  58.18 |                        72.6  |         67.91 |         70.31 |          77.37 |        80.4  |           90.33 |             71.04 |         3.18 |
|              11 | PARR     | Par Pacific Holdings, Inc.     | US       |                3.39 |                     0.08 |    -0.02 |      0.02 |                  59.2  |                        71.84 |         64.93 |         74.94 |          78.49 |        75.35 |           80.43 |             62.7  |         6.81 |
|              12 | BILL     | BILL                           | US       |                4.07 |                     0.07 |    -0.04 |      0.1  |                  74.26 |                        71.81 |         66.34 |         71.54 |          65.36 |        67.56 |           55.86 |             91.56 |         7.09 |
|              13 | HPE      | HPE                            | US       |               60.56 |                     0.11 |    -0.09 |      0.12 |                  65.09 |                        71.75 |         60.48 |         77.35 |          77.44 |        71.32 |           72.1  |             59.26 |         6.86 |
|              14 | CART     | CART                           | US       |                9.87 |                     0.02 |     0.02 |      0.18 |                  46.15 |                        71.39 |         78.46 |         76.6  |          70.68 |        69.29 |           69.47 |             75.64 |         5.68 |
|              15 | SYENS.BR | SYENS.BR                       | EUROPE   |                8.15 |                     0.03 |    -0.03 |      0.12 |                  64.95 |                        71.27 |         73.09 |         71.31 |          61.97 |        57.27 |           59.65 |             86.97 |         5.18 |
|              16 | GENI     | GENI                           | US       |                1.85 |                     0.04 |    -0.04 |      0.24 |                  71.56 |                        71.22 |         72.48 |         73.84 |          65.7  |        68.62 |           65.9  |             69.23 |         9.14 |
|              17 | ADAM     | ADAM                           | US       |                0.76 |                     0.03 |    -0.02 |      0.15 |                  59.52 |                        70.78 |         72.38 |         70.43 |          75.7  |        82.92 |           89.5  |             51.75 |         3.04 |
|              18 | BVS      | Bioventus Inc.                 | US       |                0.84 |                     0.06 |     0.01 |      0.22 |                  66.73 |                        70.74 |         77.22 |         74.63 |          70.04 |        61.64 |           68.86 |             55.65 |         5.68 |
|              19 | IRWD     | Ironwood Pharmaceuticals, Inc. | US       |                0.61 |                     0.03 |    -0    |      0.16 |                  56.35 |                        70.28 |         66.87 |         61.01 |          73.58 |        82.07 |           85.29 |             75.56 |         6.53 |
|              20 | AVNT     | AVNT                           | US       |                3.5  |                     0.04 |    -0.04 |      0.19 |                  69.8  |                        70.13 |         73.63 |         70.68 |          63.64 |        67.05 |           67    |             62.93 |         5.62 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4449.7  |             58.31 |         54.02 |         54.01 |          62.6  |        65.88 |           93.02 |             65.94 |             33.68 |         8.5  |             89.49 | long               |               -0.02 |                 -0.91 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.71 |             51.35 |         35.21 |         50.29 |          52.41 |        57.29 |           47.84 |             51.92 |             73.58 |         8.5  |             85.47 | long               |               -2.51 |                 -1.53 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1499.79 |             49.89 |         34.54 |         42.6  |          57.19 |        60.41 |           82.07 |             58.78 |             33.86 |         6.17 |             89.83 | long               |                0.39 |                 -0.58 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |             48.25 |         45.87 |         41.72 |          50.63 |        60.31 |           77.18 |             43.05 |             52.63 |         3.9  |             75.81 | long               |               -1.65 |                 -0.04 |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.                              | US       |                3.35 |             46.67 |         44.46 |         43.8  |          48.89 |        62.59 |           67.72 |             49.85 |             83.15 |         8.5  |             87.88 | long               |               -1.31 |                nan    |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             45.61 |         42.13 |         40.51 |          49.08 |        62.02 |           64.9  |             53.47 |             83.87 |         4.34 |             82.14 | long               |                0.28 |                 -0.26 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.71 |             39.22 |         41.28 |         32.11 |          37.16 |        42.07 |           42.43 |             68.53 |             44.52 |         8.5  |             77.1  | long               |                0.36 |                 -0.5  |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.88 |             36.75 |         29.83 |         32.98 |          40.52 |        52.69 |           45.83 |             44.09 |             81.26 |         6.23 |             78.58 | long               |               -0.7  |                 -0.44 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.21 |             36.44 |         27.03 |         32.99 |          39.88 |        53.86 |           43.47 |             37.55 |             93.85 |         8.5  |             78.43 | long               |               -0.88 |                 -0.38 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.85 |             34.03 |         33.6  |         21.43 |          34.46 |        44.83 |           61.41 |             17.96 |             41.11 |         8.99 |             78.45 | long               |                0.36 |                  0.28 |                  nan |
|    nan | AT1.DE   | Aroundtown SA                                        | EUROPE   |                2.12 |             32.35 |         26.83 |         27.65 |          37.06 |        47.91 |           54.37 |             48.52 |             59.38 |         8.5  |             75.91 | long               |               -3.22 |                  1.93 |                  nan |
|    nan | LI       | Li Auto Inc.                                         | OTHER    |               10.95 |             25.42 |         49.2  |         25.63 |          23.46 |        25.22 |           25.05 |             37.82 |             25.86 |         8.5  |             76.54 | short              |               -3.58 |                nan    |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name              | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    178 | HOOD     | HOOD              | US       |               83.18 |             63.51 |         70.9  |         68.06 |          58.95 |        50.25 |           66.21 |             62.74 |             12.27 |         8.66 |             68.2  | short              |               -0.15 |                  3.65 |                  nan |
|    442 | 0QXR.IL  | Stellantis N.V.   | OTHER    |               14.49 |             53.84 |         52.47 |         40    |          55.2  |        72.41 |           76.27 |            nan    |             93.55 |         8.85 |             70.77 | long               |               -2.55 |                  3.04 |                  nan |
|    139 | MRNA     | MRNA              | US       |               49.57 |             65.28 |         82.9  |         71.53 |          59.04 |        40.84 |           22.31 |             57.93 |             18.89 |         8.07 |             65.82 | short              |               -0.01 |                  3.03 |                  nan |
|    605 | NWL.MI   | NewPrinces S.p.A. | EUROPE   |                0.65 |             44.68 |         36.5  |         39.2  |          50.16 |        66.67 |           77.1  |             56.51 |             85.9  |         4.54 |             77.9  | long               |               -0.24 |                  2.79 |                  nan |
|    387 | TEM      | TEM               | US       |               11.22 |             56.02 |         78.46 |         66.35 |          45.68 |        33.38 |           31.22 |             61.14 |              4.53 |         9.1  |             65.82 | short              |                0.16 |                  2.78 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name          | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    650 | AMV0.DE  | Aumovio SE    | EUROPE   |                3.66 |             41.24 |         43.39 |         31.71 |          39.09 |        50.85 |           50.83 |             33.34 |             73.49 |         6.04 |             75.5  | long               |              -14.58 |                 -3.6  |                  nan |
|    539 | CRWD     | CRWD          | US       |              167.23 |             49.31 |         41.08 |         59.63 |          57.54 |        40.03 |           40.07 |             51.58 |              1.53 |         6.92 |             69.68 | swing              |               -4.66 |                 -3.58 |                  nan |
|    707 | HFG.DE   | HelloFresh SE | EUROPE   |                0.41 |             26.57 |         24.06 |         21.88 |          29.09 |        38.42 |           39.86 |             38.69 |             54.88 |         6.84 |             80.92 | long               |               -5.22 |                 -3.58 |                  nan |
|    251 | W        | W             | US       |               11.9  |             60.96 |         71.18 |         66    |          55.92 |        48.93 |           55.59 |             53.79 |             19.45 |         8.75 |             66.39 | short              |                0.04 |                 -2.73 |                  nan |
|    203 | RNW      | RNW           | US       |                2.12 |             62.84 |         68.93 |         61.55 |          57.67 |        64.14 |          nan    |             48.45 |             80.34 |         6.09 |             66.84 | short              |                0.13 |                 -2.65 |                  nan |

## Duplicate-security checks

- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- VTYL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
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
- Excluded by hard/data filters: **280**
- Event watch (otherwise eligible): **12**
- Final eligible: **708**
- Eligible change vs previous stored run: **+0**

Top exclusion categories:
- liquidity: 229
- price: 166
- market_cap: 160
- price_history: 17
- data_confidence: 11
- duplicate_listing: 4
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| JCAP | 9 |  | 1 |  | 2 | main,pullback |
| PARR | 20 | 8 | 11 | 8 | 1 | value,quality_value |
| BION.SW | 29 | 1 |  | 2 | 1 | value,quality_value |
| IRWD | 61 | 3 | 19 | 1 | 1 | value,quality_value |
| SDF.DE | 78 | 6 |  | 4 | 1 | value,quality_value |
| 0Q2N.IL | 137 | 5 |  | 7 | 1 | value,quality_value |
| 0QXR.IL | 442 | 2 |  | 3 | 1 | value,quality_value |
| YALA | 480 | 9 |  | 9 | 1 | value,quality_value |
| 0P6O.IL | 568 | 10 |  | 10 | 1 | value,quality_value |
| NWL.MI | 605 | 7 | 205 | 6 | 1 | value,quality_value |
| STNE | 658 | 4 |  | 5 | 1 | value,quality_value |
| PBF | 1 |  |  |  | 1 | main |
| SM | 2 |  |  |  | 1 | main |
| ERO | 3 |  |  |  | 1 | main |
| DHT | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (SM, ERO, DHT, CRGY, AVAH, HALO, KIN.BR, PR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 75.17 | 68.97 | 83.61 | 77.10 | 56.51 | 81.82 | 44.68 |
| 2 | IRWD | value+pullback | 72.27 | 72.14 | 56.35 | 85.29 | 75.56 | 80.97 | 70.22 |
| 3 | PARR | value+pullback | 67.48 | 68.27 | 59.20 | 80.43 | 62.70 | 69.35 | 75.15 |
| 4 | INVA | value+pullback | 65.27 | 61.14 | 59.44 | 85.49 | 36.05 | 78.21 | 46.25 |
| 5 | ETG | value+pullback | 63.51 | 55.12 | 53.19 | 68.30 | 81.03 | 76.66 | 60.57 |
| 6 | 0P6O.IL | value+pullback | 62.38 | 65.02 | 46.44 | 78.30 |  | 72.58 | 47.66 |
| 7 | PKX | value+pullback | 61.37 | 55.25 | 61.19 | 75.78 | 70.26 | 55.55 | 54.40 |
| 8 | ALL-PH | value+pullback | 61.33 | 62.32 | 63.20 | 69.47 | 42.86 | 60.63 | 43.49 |
| 9 | MSFT | value+pullback | 61.26 | 58.21 | 70.21 | 59.95 | 67.73 | 52.37 | 59.96 |
| 10 | MFA | value+pullback | 60.93 | 57.72 | 66.21 | 75.97 | 33.73 | 61.44 | 41.14 |
| 11 | UNIT | value+pullback | 60.69 | 80.01 | 60.06 | 66.40 | 27.90 | 44.62 | 42.65 |
| 12 | DOM.ST | value+pullback | 60.58 | 60.35 | 65.81 | 66.43 | 29.47 | 65.54 | 36.13 |
| 13 | ORCL | value+pullback | 60.02 | 69.90 | 74.09 | 46.85 | 60.10 | 37.47 | 42.47 |
| 14 | VOW3.DE | value+pullback | 59.39 | 70.95 | 46.78 | 63.05 | 46.44 | 61.58 | 45.78 |
| 15 | BION.SW | value | 58.70 | 78.01 | 30.95 | 81.92 | 58.15 | 85.97 | 73.85 |
| 16 | ONIT | value+pullback | 58.61 | 72.70 | 59.74 | 61.69 | 42.81 | 41.64 | 42.12 |
| 17 | JCAP | pullback | 58.14 | 58.02 | 81.56 | 86.37 | 87.66 | 80.17 | 76.62 |
| 18 | XNET | value+pullback | 57.79 | 61.49 | 40.47 | 53.95 | 80.78 | 65.30 | 43.25 |
| 19 | WKC | value+pullback | 57.31 | 57.82 | 40.04 | 58.15 | 75.83 | 68.22 | 67.42 |
| 20 | CHTR | value+pullback | 56.35 | 61.11 | 74.06 | 53.45 | 43.93 | 35.45 | 45.13 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 68.7 | 2 / 8 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 68.7 | 7 / 18 |
| Top 50 | 49/50 | 50/50 | 50/50 | 49/50 | 0/50 | 68.7 | 22 / 28 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=4
