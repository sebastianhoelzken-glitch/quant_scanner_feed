# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-13

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

- **EUROPE:** 81.6/100
- **OTHER:** 71.9/100
- **US:** 85.9/100

## Main multi-horizon ranking

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | AKER.OL  | Aker ASA                       | EUROPE   |                9.63 |             81.01 |         88.38 |         79.4  |          82.63 |        78.01 |           98.62 |             82.49 |             41.25 |         3.64 |             73.32 | short              |               -1.28 |                   nan |                  nan |
|      2 | PARR     | Par Pacific Holdings, Inc.     | US       |                3.49 |             76.9  |         77.3  |         76.5  |          77.92 |        72.52 |           73.91 |             72.47 |             61.57 |         6.75 |             85.65 | medium             |                2.36 |                   nan |                  nan |
|      3 | BION.SW  | BB Biotech AG                  | EUROPE   |                3.16 |             73.71 |         73.35 |         67.63 |          74.07 |        80.25 |           92.79 |             58.18 |             80.8  |         2.32 |             78.65 | long               |                1.36 |                   nan |                  nan |
|      4 | VSXY     | Victorias Secret & Co.         | US       |                6.33 |             70.72 |         65.01 |         76.03 |          74.16 |        67.28 |           60.29 |             69.82 |             55.13 |         7.83 |             86.67 | swing              |              -18.08 |                   nan |                  nan |
|      5 | TNK      | Teekay Tankers Ltd.            | OTHER    |                2.52 |             69.66 |         78.63 |         68.6  |          69.33 |        70    |           70.94 |             65.68 |             62.95 |         5.05 |             84.89 | short              |               -2.66 |                   nan |                  nan |
|      6 | FTNT     | Fortinet, Inc.                 | US       |              103.96 |             69.1  |         64.02 |         73.92 |          74.36 |        64.28 |           78.1  |             67.65 |             26    |         4.56 |             90.46 | medium             |              -16.82 |                   nan |                  nan |
|      7 | AMCX     | AMC Global Media Inc.          | US       |                0.43 |             68.95 |         72.04 |         71.12 |          66.79 |        63.33 |           48.6  |             70.31 |             81.23 |         7.58 |             85.14 | short              |                2.27 |                   nan |                  nan |
|      8 | PGEN     | Precigen, Inc.                 | US       |                2.07 |             68.38 |         71.17 |         72.21 |          65.58 |        53.2  |           46.87 |             79.41 |             25.05 |         8.04 |             75.55 | swing              |              -19.55 |                   nan |                  nan |
|      9 | EQNR.OL  | Equinor ASA                    | EUROPE   |               81.66 |             67.31 |         64.38 |         61.88 |          71.85 |        70.24 |           82.02 |             70.14 |             51.49 |         5.05 |             88.03 | medium             |              nan    |                   nan |                  nan |
|     10 | SU.PA    | Schneider Electric S.E.        | EUROPE   |              173.84 |             66.98 |         78.66 |         69.56 |          64.4  |        60.42 |           77.55 |             71.98 |             23.74 |         4.67 |             89.69 | short              |               -0.64 |                   nan |                  nan |
|     11 | SM       | SM Energy Company              | US       |                6.64 |             66.78 |         66.49 |         59.98 |          67.07 |        71.58 |           79.13 |             51.46 |             77.86 |         6.63 |             87.81 | long               |               -1.92 |                   nan |                  nan |
|     12 | TWN      | The Taiwan Fund, Inc.          | US       |                0.48 |             66.46 |         68.98 |         63.94 |          69.81 |        59.23 |           72.69 |             81.97 |             17.77 |         6.31 |             61.74 | medium             |               -0.44 |                   nan |                  nan |
|     13 | CSX      | CSX Corporation                | US       |               80.93 |             66.25 |         57.71 |         64.54 |          70.03 |        67.95 |           83.7  |             68.96 |             39.7  |         3.25 |             90.14 | medium             |               -0.72 |                   nan |                  nan |
|     14 | RBI.VI   | Raiffeisen Bank Internat. AG   | EUROPE   |               20.44 |             65.79 |         66.09 |         70.88 |          65.49 |        55.06 |           44.94 |             64.58 |             43.41 |         5.03 |             76.24 | swing              |              -14.19 |                   nan |                  nan |
|     15 | ASML.AS  | ASML Holding N.V.              | EUROPE   |              618.17 |             65.6  |         60.37 |         65.46 |          72.23 |        65.73 |           83.26 |             75.42 |             21.81 |         6.06 |             89.58 | medium             |                1.65 |                   nan |                  nan |
|     16 | KELYA    | Kelly Services, Inc.           | US       |                0.47 |             65.5  |         63.96 |         77.04 |          67.04 |        63.02 |           37.32 |             65.21 |             94    |         6.24 |             85.62 | swing              |                1.74 |                   nan |                  nan |
|     17 | BLMN     | Bloomin' Brands, Inc.          | US       |                0.82 |             65.46 |         71.19 |         67.79 |          63.11 |        63.12 |           48.91 |             50.72 |             80.62 |         7.7  |             87.69 | short              |              -15.94 |                   nan |                  nan |
|     18 | ETSY     | Etsy, Inc.                     | US       |                6.36 |             65.34 |         46.21 |         67.46 |          68.04 |        63.22 |           72.46 |             60.44 |             45.73 |         7.23 |             87.01 | medium             |               -8.85 |                   nan |                  nan |
|     19 | LTH      | Life Time Group Holdings, Inc. | US       |                8.55 |             65.26 |         63.57 |         69.43 |          66.95 |        57.99 |           60.63 |             63.37 |             33.82 |         4.62 |             87.94 | swing              |              -14.5  |                   nan |                  nan |
|     20 | RMAX     | RE/MAX Holdings, Inc.          | US       |                0.58 |             65.11 |         71.86 |         67.49 |          62.72 |        58.79 |           59.45 |             52.94 |             60.06 |         7.25 |             75.57 | short              |               -0.35 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                           | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | MOMO     | Hello Group Inc.               | OTHER    |                0.74 |                  83.8  |                    77.25 |                 75.92 |              80.28 |                80.32 |                   19.68 |           71.78 |             54.82 |       0.577 |         nan |       nan |       -5.14 |         5.35 |          8.57 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            2 | BION.SW  | BB Biotech AG                  | EUROPE   |                3.16 |                  72.82 |                    75.22 |                 77.84 |              74.03 |                87.66 |                   12.34 |           92.79 |             58.18 |       0.834 |         nan |       nan |      nan    |       -81.64 |          2.19 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | 0QXR.IL  | Stellantis N.V.                | OTHER    |               25.94 |                  75.3  |                    74.68 |                 74.97 |              74.12 |                69.38 |                   30.62 |           77.72 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.71 |                 nan |              nan |                   9 |                  0.47 |
|            4 | INVA     | Innoviva, Inc.                 | US       |                1.31 |                  80.83 |                    74.13 |                 73.8  |              75.59 |                75.91 |                   24.09 |           81.8  |             37.27 |       0.073 |         nan |       nan |        6.43 |         9.45 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|            5 | IRWD     | Ironwood Pharmaceuticals, Inc. | US       |                0.59 |                  71.02 |                    72.81 |                 75.21 |              71.74 |                78.43 |                   21.57 |           87.04 |             64.87 |       0.179 |         nan |       nan |        4.33 |         2.79 |          5.21 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | SM       | SM Energy Company              | US       |                6.64 |                  73.62 |                    70.97 |                 70.45 |              69.93 |                65.45 |                   34.55 |           79.13 |             51.46 |       0.192 |         nan |       nan |        4.53 |         4.41 |          5.71 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            7 | 0P6O.IL  | Volkswagen AG                  | OTHER    |               40.41 |                  65.73 |                    70.62 |                 72.47 |              68.13 |                77.72 |                   22.28 |           81.46 |            nan    |       0.428 |         nan |       nan |        7.45 |       nan    |          2.63 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|            8 | MTRX     | Matrix Service Company         | US       |                0.29 |                  82.91 |                    70.17 |                 68.18 |              75.59 |                54.62 |                   45.38 |           54.32 |             60.65 |       0.302 |         nan |       nan |      -46.91 |        16.86 |        nan    |        1.11 |                 nan |              nan |                  10 |                  0.53 |
|            9 | KELYA    | Kelly Services, Inc.           | US       |                0.47 |                  84.13 |                    69.27 |                 65.12 |              76.88 |                54.36 |                   45.64 |           37.32 |             65.21 |       0.137 |         nan |       nan |        8.88 |         8.64 |        nan    |        1.13 |                 nan |              nan |                  11 |                  0.58 |
|           10 | NWL.MI   | NewPrinces S.p.A.              | EUROPE   |                0.69 |                  65.9  |                    68.86 |                 71.37 |              68.14 |                83.45 |                   16.55 |           82.77 |             56.73 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           11 | PARR     | Par Pacific Holdings, Inc.     | US       |                3.49 |                  67.84 |                    68.62 |                 70.11 |              68.37 |                68.21 |                   31.79 |           73.91 |             72.47 |       0.02  |         nan |       nan |        3.81 |         6.07 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           12 | AMCX     | AMC Global Media Inc.          | US       |                0.43 |                  72.06 |                    66.91 |                 65.17 |              70.97 |                66.95 |                   33.05 |           48.6  |             70.31 |       2.014 |         nan |       nan |        6.98 |         4.37 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           13 | AKER.OL  | Aker ASA                       | EUROPE   |                9.63 |                  52.86 |                    66.32 |                 71.7  |              59.38 |                72.58 |                   27.42 |           98.62 |             82.49 |       0.115 |         nan |       nan |        5.23 |        54.32 |          3.74 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|           14 | PKX      | POSCO Holdings Inc.            | OTHER    |               14.87 |                  63.03 |                    65.94 |                 69.17 |              62.65 |                66.14 |                   33.86 |           91.37 |             53.66 |     nan     |         nan |       nan |        3.7  |         9.83 |         28.35 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           15 | UNIT     | Uniti Group Inc.               | US       |                2.03 |                  78.01 |                    65.92 |                 63.34 |              67.36 |                45.62 |                   54.38 |           67.63 |             29.88 |      -0.11  |         nan |       nan |        9.02 |       -13.6  |          2.51 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           16 | IHS      | IHS Holding Limited            | OTHER    |                2.45 |                  68.64 |                    65.62 |                 66.24 |              68.33 |                58.97 |                   41.03 |           56.31 |             82.87 |      -0.111 |         nan |       nan |        7.1  |        15.16 |          5.12 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           17 | AVGO     | Broadcom Inc.                  | US       |             1742.74 |                  53.89 |                    65.53 |                 67.07 |              59.59 |                80.12 |                   19.88 |           84.98 |             63.71 |       0.014 |         nan |       nan |       48.11 |        21.63 |         70.53 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           18 | EQNR.OL  | Equinor ASA                    | EUROPE   |               81.66 |                  58.24 |                    64.98 |                 67.13 |              60.82 |                65.95 |                   34.05 |           82.02 |             70.14 |       0.312 |         nan |       nan |       22.74 |         9.96 |         10.74 |        1.01 |                 nan |              nan |                  12 |                  0.63 |
|           19 | CNC      | Centene Corporation            | US       |               28.51 |                  73.32 |                    64.37 |                 60.22 |              66.94 |                47.53 |                   52.47 |           46.84 |             55.93 |       0.293 |         nan |       nan |        4.84 |        12.56 |        nan    |        1.17 |                 nan |              nan |                  10 |                  0.53 |
|           20 | TNK      | Teekay Tankers Ltd.            | OTHER    |                2.52 |                  62.49 |                    64.28 |                 65.98 |              63.89 |                68.52 |                   31.48 |           70.94 |             65.68 |       0.077 |         nan |       nan |        3.2  |         9.2  |          4.95 |        1.1  |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | BION.SW   | BB Biotech AG                                          | EUROPE   |                3.16 |                  72.82 |                    75.22 |                 77.84 |              74.03 |                87.66 |                   12.34 |           92.79 |             58.18 |       0.834 |         nan |       nan |      nan    |       -81.64 |          2.19 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            1 | MOMO      | Hello Group Inc.                                       | OTHER    |                0.74 |                  83.8  |                    77.25 |                 75.92 |              80.28 |                80.32 |                   19.68 |           71.78 |             54.82 |       0.577 |         nan |       nan |       -5.14 |         5.35 |          8.57 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            5 | IRWD      | Ironwood Pharmaceuticals, Inc.                         | US       |                0.59 |                  71.02 |                    72.81 |                 75.21 |              71.74 |                78.43 |                   21.57 |           87.04 |             64.87 |       0.179 |         nan |       nan |        4.33 |         2.79 |          5.21 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | 0QXR.IL   | Stellantis N.V.                                        | OTHER    |               25.94 |                  75.3  |                    74.68 |                 74.97 |              74.12 |                69.38 |                   30.62 |           77.72 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.71 |                 nan |              nan |                   9 |                  0.47 |
|            4 | INVA      | Innoviva, Inc.                                         | US       |                1.31 |                  80.83 |                    74.13 |                 73.8  |              75.59 |                75.91 |                   24.09 |           81.8  |             37.27 |       0.073 |         nan |       nan |        6.43 |         9.45 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|            7 | 0P6O.IL   | Volkswagen AG                                          | OTHER    |               40.41 |                  65.73 |                    70.62 |                 72.47 |              68.13 |                77.72 |                   22.28 |           81.46 |            nan    |       0.428 |         nan |       nan |        7.45 |       nan    |          2.63 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|           13 | AKER.OL   | Aker ASA                                               | EUROPE   |                9.63 |                  52.86 |                    66.32 |                 71.7  |              59.38 |                72.58 |                   27.42 |           98.62 |             82.49 |       0.115 |         nan |       nan |        5.23 |        54.32 |          3.74 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|           10 | NWL.MI    | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  65.9  |                    68.86 |                 71.37 |              68.14 |                83.45 |                   16.55 |           82.77 |             56.73 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | SM        | SM Energy Company                                      | US       |                6.64 |                  73.62 |                    70.97 |                 70.45 |              69.93 |                65.45 |                   34.55 |           79.13 |             51.46 |       0.192 |         nan |       nan |        4.53 |         4.41 |          5.71 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|           11 | PARR      | Par Pacific Holdings, Inc.                             | US       |                3.49 |                  67.84 |                    68.62 |                 70.11 |              68.37 |                68.21 |                   31.79 |           73.91 |             72.47 |       0.02  |         nan |       nan |        3.81 |         6.07 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           14 | PKX       | POSCO Holdings Inc.                                    | OTHER    |               14.87 |                  63.03 |                    65.94 |                 69.17 |              62.65 |                66.14 |                   33.86 |           91.37 |             53.66 |     nan     |         nan |       nan |        3.7  |         9.83 |         28.35 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            8 | MTRX      | Matrix Service Company                                 | US       |                0.29 |                  82.91 |                    70.17 |                 68.18 |              75.59 |                54.62 |                   45.38 |           54.32 |             60.65 |       0.302 |         nan |       nan |      -46.91 |        16.86 |        nan    |        1.11 |                 nan |              nan |                  10 |                  0.53 |
|           18 | EQNR.OL   | Equinor ASA                                            | EUROPE   |               81.66 |                  58.24 |                    64.98 |                 67.13 |              60.82 |                65.95 |                   34.05 |           82.02 |             70.14 |       0.312 |         nan |       nan |       22.74 |         9.96 |         10.74 |        1.01 |                 nan |              nan |                  12 |                  0.63 |
|           17 | AVGO      | Broadcom Inc.                                          | US       |             1742.74 |                  53.89 |                    65.53 |                 67.07 |              59.59 |                80.12 |                   19.88 |           84.98 |             63.71 |       0.014 |         nan |       nan |       48.11 |        21.63 |         70.53 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           16 | IHS       | IHS Holding Limited                                    | OTHER    |                2.45 |                  68.64 |                    65.62 |                 66.24 |              68.33 |                58.97 |                   41.03 |           56.31 |             82.87 |      -0.111 |         nan |       nan |        7.1  |        15.16 |          5.12 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           20 | TNK       | Teekay Tankers Ltd.                                    | OTHER    |                2.52 |                  62.49 |                    64.28 |                 65.98 |              63.89 |                68.52 |                   31.48 |           70.94 |             65.68 |       0.077 |         nan |       nan |        3.2  |         9.2  |          4.95 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|           39 | INDU-C.ST | AB Industrivärden (publ)                               | EUROPE   |               20.55 |                  44.04 |                    60.67 |                 65.91 |              54.75 |                82.18 |                   17.82 |           85.57 |             82.49 |       0.174 |         nan |       nan |        3.72 |       nan    |          3.61 |        5.47 |                 nan |              nan |                   9 |                  0.47 |
|           25 | ORC       | Orchid Island Capital, Inc.                            | US       |                1.15 |                  60.07 |                    63.16 |                 65.84 |              59.46 |                68.8  |                   31.2  |           90.99 |             38.27 |     nan     |         nan |       nan |      nan    |         6.42 |          3.77 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           23 | ETG       | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |                  55.41 |                    63.33 |                 65.51 |              61.68 |                75.32 |                   24.68 |           67.76 |             82.23 |       0.027 |         nan |       nan |      nan    |       nan    |          3.82 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           12 | AMCX      | AMC Global Media Inc.                                  | US       |                0.43 |                  72.06 |                    66.91 |                 65.17 |              70.97 |                66.95 |                   33.05 |           48.6  |             70.31 |       2.014 |         nan |       nan |        6.98 |         4.37 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                              | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | INDU-C.ST | AB Industrivärden (publ)          | EUROPE   |               20.55 |                     0.07 |    -0.05 |      0    |                  79.69 |                        72.32 |         48.33 |         61.75 |          69.34 |        67.03 |           85.57 |             82.49 |         2.45 |
|               2 | INDU-A.ST | AB Industrivärden (publ)          | EUROPE   |               20.65 |                     0.07 |    -0.06 |     -0.01 |                  78.19 |                        71.38 |         44.02 |         60.33 |          68.45 |        64.8  |           85.57 |             82.49 |         2.6  |
|               3 | FTNT      | Fortinet, Inc.                    | US       |              103.96 |                     0.03 |     0.02 |      0.02 |                  49.36 |                        70.13 |         64.02 |         73.92 |          74.36 |        64.28 |           78.1  |             67.65 |         4.56 |
|               4 | CSX       | CSX Corporation                   | US       |               80.93 |                     0.05 |    -0.01 |     -0.01 |                  70.73 |                        69.96 |         57.71 |         64.54 |          70.03 |        67.95 |           83.7  |             68.96 |         3.25 |
|               5 | VSXY      | Victorias Secret & Co.            | US       |                6.33 |                     0.08 |    -0.02 |      0.12 |                  60.18 |                        69.57 |         65.01 |         76.03 |          74.16 |        67.28 |           60.29 |             69.82 |         7.83 |
|               6 | ELF       | e.l.f. Beauty, Inc.               | US       |                4.71 |                     0.06 |    -0    |      0.24 |                  65.66 |                        69.32 |         67.52 |         64.65 |          55.94 |        54.56 |           84.08 |             59.33 |         8.35 |
|               7 | EQNR.OL   | Equinor ASA                       | EUROPE   |               81.66 |                     0.05 |     0.02 |      0.09 |                  64.17 |                        68.74 |         64.38 |         61.88 |          71.85 |        70.24 |           82.02 |             70.14 |         5.05 |
|               8 | GENI      | Genius Sports Limited             | OTHER    |                1.86 |                     0.07 |    -0.01 |      0.24 |                  65.87 |                        68.56 |         72.63 |         67.62 |          54.68 |        47.84 |           52.21 |             79.46 |         8.16 |
|               9 | HRTG      | Heritage Insurance Holdings, Inc. | US       |                0.86 |                     0.06 |    -0.06 |      0.25 |                  86.38 |                        68.14 |         69.4  |         69.44 |          60.42 |        56.31 |           60.5  |             55.71 |         5.88 |
|              10 | ALL       | The Allstate Corporation          | US       |               56.58 |                     0.06 |    -0.06 |      0.07 |                  84.44 |                        68.1  |         58.39 |         64.33 |          62.04 |        56.95 |           69.45 |             62.51 |         3.08 |
|              11 | PGEN      | Precigen, Inc.                    | US       |                2.07 |                     0.08 |    -0.04 |      0.34 |                  66.41 |                        67.35 |         71.17 |         72.21 |          65.58 |        53.2  |           46.87 |             79.41 |         8.04 |
|              12 | ETSY      | Etsy, Inc.                        | US       |                6.36 |                     0.08 |    -0.03 |     -0.04 |                  65.89 |                        67.17 |         46.21 |         67.46 |          68.04 |        63.22 |           72.46 |             60.44 |         7.23 |
|              13 | NNBR      | NN, Inc.                          | US       |                0.26 |                     0.06 |    -0.06 |      0.21 |                  81.78 |                        67.15 |         64.54 |         72.9  |          65.29 |        56.35 |           48.47 |             58.23 |         7.55 |
|              14 | AMZN      | Amazon.com, Inc.                  | US       |             2484.85 |                     0.06 |    -0.02 |      0.06 |                  72.1  |                        66.84 |         62.87 |         57.01 |          60.63 |        58.39 |           75.91 |             62.74 |         5.72 |
|              15 | BAX       | Baxter International Inc.         | US       |               12.09 |                     0.05 |     0    |      0.16 |                  65.23 |                        66    |         73.77 |         69.67 |          57.89 |        55.55 |           55.54 |             54.82 |         5.47 |
|              16 | CLOV      | Clover Health Investments, Corp.  | US       |                2.07 |                     0.06 |    -0.04 |      0.02 |                  77.08 |                        65.96 |         46.97 |         64.69 |          69.41 |        59.83 |           56.45 |             71.74 |         7.52 |
|              17 | IRWD      | Ironwood Pharmaceuticals, Inc.    | US       |                0.59 |                     0.07 |    -0.03 |      0.06 |                  72.38 |                        65.9  |         55.8  |         55.58 |          69.64 |        81.94 |           87.04 |             64.87 |         6.47 |
|              18 | CRCT      | Cricut, Inc.                      | US       |                1.06 |                     0.03 |    -0.03 |      0.25 |                  67.54 |                        65.34 |         73.23 |         70.29 |          56.21 |        49.51 |           43.7  |             65.68 |         6.47 |
|              19 | MSFT      | Microsoft Corporation             | US       |             3181.89 |                     0.02 |    -0.01 |      0.23 |                  53.77 |                        65.09 |         71.12 |         64.72 |          55.82 |        54.85 |           63.63 |             58.29 |         5.7  |
|              20 | TOST      | Toast, Inc.                       | US       |               17.18 |                     0.04 |    -0.01 |      0.13 |                  65.97 |                        64.75 |         66.36 |         67.41 |          56.94 |        54.53 |           60.25 |             60.66 |         7.09 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | WDAY     | Workday, Inc.                | US       |               37.53 |             63.99 |         73.25 |         67.18 |          58.25 |        60.8  |           67.96 |             56.25 |             61.04 |         7.64 |             89.8  | short              |                0.6  |                   nan |                  nan |
|    nan | NVDA     | NVIDIA Corporation           | US       |             4725.54 |             63.59 |         67.75 |         56.88 |          62.07 |        65.11 |           90.89 |             60.09 |             36.54 |         5.54 |             89.54 | short              |               -1.95 |                   nan |                  nan |
|    nan | SWON.SW  | SoftwareOne Holding AG       | EUROPE   |                2.05 |             63.09 |         60.21 |         60.94 |          65.25 |        65.78 |           76.99 |             58.14 |             53.56 |         5.91 |             85.3  | long               |                0.1  |                   nan |                  nan |
|    nan | ROST     | Ross Stores, Inc.            | US       |               67.78 |             62.46 |         53.38 |         62.68 |          66.51 |        62.25 |           78.89 |             62.36 |             27.66 |         3.75 |             88.99 | medium             |              nan    |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.88 |             59.56 |         60.49 |         61.16 |          54.95 |        58.63 |           36.17 |             48.46 |             83.72 |         8.42 |             85.47 | swing              |               -3.63 |                   nan |                  nan |
|    nan | DLO      | DLocal Limited               | OTHER    |                3.67 |             54.44 |         40.94 |         51.78 |          57.11 |        62.22 |           79.24 |             50.44 |             53.86 |         8.5  |             84.42 | long               |               -2.44 |                   nan |                  nan |
|    nan | ZEAL.CO  | Zealand Pharma A/S           | EUROPE   |                3.11 |             51.31 |         62.26 |         42.26 |          45.83 |        56.8  |           70.63 |             44.75 |             56.99 |         8.5  |             81.67 | short              |                2.48 |                   nan |                  nan |
|    nan | AFRM     | Affirm Holdings, Inc.        | US       |               22    |             46.8  |         42.96 |         52.72 |          50.63 |        42.4  |           54.86 |             51.15 |             13.97 |         7.88 |             78.49 | swing              |              nan    |                   nan |                  nan |
|    nan | COTY     | Coty Inc.                    | US       |                2.1  |             44.4  |         53.26 |         47.43 |          38.27 |        41.37 |           32.96 |             37.06 |             65.77 |         7.86 |             85.23 | short              |               -6.94 |                   nan |                  nan |
|    nan | STNE     | StoneCo Ltd.                 | OTHER    |                2.14 |             43.02 |         26.69 |         37.17 |          48.88 |        65.99 |           76.8  |             47.44 |             86.14 |         8.5  |             85.99 | long               |                1.02 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.01 |             39.88 |         51.22 |         38.69 |          35.23 |        41.08 |           28.39 |             28.38 |             64.42 |         4.46 |             74.95 | short              |               -0.8  |                   nan |                  nan |
|    nan | JD       | JD.com, Inc.                 | OTHER    |               33.87 |             37.96 |         32.58 |         34.49 |          41.44 |        44.63 |           45.32 |             49.98 |             52.54 |         8.5  |             86.72 | long               |              -15.77 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.92 |             37.52 |         26.71 |         33.45 |          41.6  |        53.33 |           49.1  |             46.08 |             78.76 |         6.19 |             78.58 | long               |               -2.78 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.31 |             36.63 |         28.5  |         33.23 |          40.03 |        53.13 |           46.72 |             40.56 |             86.54 |         7.13 |             78.43 | long               |               -3.33 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.62 |             36.05 |         30.44 |         29.13 |          41.66 |        59.6  |           75.26 |             24.2  |             76.43 |         4.93 |             81.52 | long               |               -2.49 |                   nan |                  nan |
|    nan | AT1.DE   | Aroundtown SA                | EUROPE   |                2.23 |             34.93 |         36.29 |         28.13 |          33.56 |        43.2  |           48.33 |             34.71 |             53.93 |         5.54 |             75.53 | long               |                3.59 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.89 |             32.39 |         33.78 |         20.06 |          31    |        39.58 |           43.47 |             19.28 |             45.75 |         9.08 |             77.55 | long               |               -6.41 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             32.38 |         37.08 |         22.61 |          28.13 |        36.63 |           26.9  |             37.3  |             63.41 |         7.08 |             75.4  | short              |               -1.53 |                   nan |                  nan |
|    nan | HFG.DE   | HelloFresh SE                | EUROPE   |                0.48 |             29.62 |         29.06 |         21.15 |          30.18 |        44.46 |           46.43 |             23.82 |             73.32 |         8.5  |             80.25 | long               |                6.48 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             23.46 |         57.61 |         22.73 |          19.21 |        24.19 |           14.44 |             26.8  |             42.74 |         7.74 |             75.24 | short              |               -4.52 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- VTYL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.95
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.95
- `risk_adj_mom_126d_rank` vs `dist_sma_200_rank`: r=0.91

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
- Excluded by hard/data filters: **797**
- Event watch (otherwise eligible): **21**
- Final eligible: **182**
- Eligible change vs previous stored run: **+78**

Top exclusion categories:
- market_cap: 712
- liquidity: 219
- price: 158
- data_confidence: 24
- price_history: 23
- duplicate_listing: 4
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| BION.SW | 3 | 2 |  | 1 | 2 | main,value,quality_value |
| VSXY | 4 | 60 | 5 | 62 | 2 | main,pullback |
| FTNT | 6 | 31 | 3 | 24 | 2 | main,pullback |
| EQNR.OL | 9 | 18 | 7 | 13 | 2 | main,pullback |
| AKER.OL | 1 | 13 |  | 7 | 1 | main,quality_value |
| PARR | 2 | 11 |  | 10 | 1 | main,quality_value |
| SM | 11 | 6 |  | 9 | 1 | value,quality_value |
| IRWD | 31 | 5 | 17 | 3 | 1 | value,quality_value |
| NWL.MI | 104 | 10 |  | 8 | 1 | value,quality_value |
| 0QXR.IL | 111 | 3 |  | 4 | 1 | value,quality_value |
| MOMO | 133 | 1 | 65 | 2 | 1 | value,quality_value |
| INVA | 145 | 4 | 73 | 5 | 1 | value,quality_value |
| 0P6O.IL | 153 | 7 |  | 6 | 1 | value,quality_value |
| TNK | 5 | 20 |  | 16 | 1 | main |
| AMCX | 7 | 12 |  | 20 | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **0** (none)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | IRWD | value+pullback | 74.63 | 71.02 | 72.38 | 87.04 | 64.87 | 78.43 | 62.72 |
| 2 | MOMO | value+pullback | 74.34 | 83.80 | 67.55 | 71.78 | 54.82 | 80.32 | 46.30 |
| 3 | INVA | value+pullback | 72.96 | 80.83 | 70.14 | 81.80 | 37.27 | 75.91 | 43.55 |
| 4 | 0P6O.IL | value+pullback | 71.65 | 65.73 | 76.67 | 81.46 |  | 77.72 | 40.62 |
| 5 | IRS | value+pullback | 66.10 | 60.48 | 67.90 | 82.83 | 43.65 | 70.94 | 48.25 |
| 6 | EQNR.OL | value+pullback | 66.02 | 58.24 | 64.17 | 82.02 | 70.14 | 65.95 | 67.31 |
| 7 | VOW3.DE | value+pullback | 65.04 | 68.27 | 78.78 | 63.31 | 35.88 | 58.87 | 36.75 |
| 8 | GSL | value+pullback | 64.56 | 61.75 | 67.50 | 71.48 | 37.07 | 73.67 | 57.72 |
| 9 | PKX | value+pullback | 64.00 | 63.03 | 51.17 | 91.37 | 53.66 | 66.14 | 55.24 |
| 10 | GENI | value+pullback | 63.69 | 67.66 | 65.87 | 52.21 | 79.46 | 55.77 | 61.15 |
| 11 | CLOV | value+pullback | 63.11 | 59.95 | 77.08 | 56.45 | 71.74 | 51.07 | 62.26 |
| 12 | MTRX | value+pullback | 62.91 | 82.91 | 51.57 | 54.32 | 60.65 | 54.62 | 49.38 |
| 13 | SUZ | value+pullback | 62.27 | 59.69 | 66.75 | 66.43 | 47.95 | 64.59 | 38.50 |
| 14 | YPF | value+pullback | 61.46 | 66.58 | 63.57 | 64.49 | 64.99 | 47.10 | 62.60 |
| 15 | ALL-PH | value+pullback | 60.81 | 62.28 | 62.22 | 69.45 | 40.96 | 60.30 | 44.71 |
| 16 | KELYA | value+pullback | 60.79 | 84.13 | 50.26 | 37.32 | 65.21 | 54.36 | 65.50 |
| 17 | VOW.DE | value+pullback | 60.70 | 58.90 | 74.35 | 63.31 | 32.46 | 58.51 | 34.15 |
| 18 | BHF | value+pullback | 60.69 | 68.11 | 61.12 | 51.98 | 42.69 | 64.54 | 43.83 |
| 19 | GDRX | value+pullback | 60.29 | 64.76 | 75.16 | 57.53 | 42.59 | 45.95 | 60.73 |
| 20 | LNC | value+pullback | 60.12 | 57.52 | 83.37 | 44.78 | 59.16 | 46.91 | 59.57 |
