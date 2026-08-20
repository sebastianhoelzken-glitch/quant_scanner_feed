# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-20

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

- **EUROPE:** 89.1/100
- **OTHER:** 78.9/100
- **US:** 87.0/100

## Main multi-horizon ranking

|   rank | symbol    | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | AKER.OL   | Aker ASA            | EUROPE   |                9.76 |             78.36 |         83.48 |         76.57 |          80.16 |        73.92 |           85.42 |             82.7  |             43.1  |         3.49 |             74.34 | short              |               19.27 |                 -0.71 |                  nan |
|      2 | SSABBH.HE | SSABBH.HE           | EUROPE   |                9.46 |             77.8  |         71.88 |         75.02 |          80.58 |        81.63 |           65.94 |            nan    |            100    |         3.37 |             62.84 | long               |                1.58 |                 -1.14 |                  nan |
|      3 | HALO      | HALO                | US       |               10.55 |             77.67 |         83.31 |         81.1  |          74.25 |        72.81 |           85.36 |             71.24 |             57.15 |         5.55 |             66.48 | short              |               -2.12 |                  0.47 |                  nan |
|      4 | TKA.DE    | TKA.DE              | EUROPE   |                8.07 |             76.37 |         72.55 |         73.96 |          78.77 |        79.73 |          nan    |             85.68 |             71.29 |         6.49 |             64.66 | long               |                3.82 |                 -0.11 |                  nan |
|      5 | BAYN.DE   | BAYN.DE             | EUROPE   |               48.15 |             76.25 |         66.32 |         74.43 |          78.07 |        81.97 |          nan    |             91.99 |             71.67 |         6.12 |             64.66 | long               |                5.41 |                  2.5  |                  nan |
|      6 | PBF       | PBF                 | US       |                7.57 |             75.72 |         77.98 |         78.01 |          73.47 |        69.73 |           50.22 |             60.8  |             92.15 |         7.04 |             67.05 | swing              |               -3.16 |                 -3.39 |                  nan |
|      7 | CRGY      | CRGY                | US       |                4.56 |             75.45 |         78.83 |         66.99 |          73.24 |        77.66 |           71.36 |             85.07 |             96.08 |         6.08 |             67.05 | short              |              nan    |                nan    |                  nan |
|      8 | PSX       | PSX                 | US       |               83.89 |             75.01 |         75.42 |         75.39 |          74.63 |        72.74 |           80.99 |             58.13 |             63.72 |         3.43 |             67.5  | short              |               -2.5  |                 -1.41 |                  nan |
|      9 | RMAX      | RMAX                | US       |                0.69 |             74.82 |         82.67 |         82.88 |          66.98 |        56.78 |           20.4  |             91.14 |             83.59 |         7.23 |             67.05 | swing              |              nan    |                 -2.35 |                  nan |
|     10 | BION.SW   | BB Biotech AG       | EUROPE   |                3.26 |             74.66 |         75.43 |         71.68 |          73.89 |        78.07 |           86.1  |             57.44 |             79.56 |         2.23 |             79.55 | long               |               10.49 |                  0.92 |                  nan |
|     11 | TWST      | TWST                | US       |                7.71 |             74.6  |         85.12 |         81.08 |          68.12 |        48.61 |           47.45 |             79.25 |              7.51 |         7    |             64.66 | short              |              nan    |                 -1.27 |                  nan |
|     12 | HRB       | H&R Block, Inc.     | US       |                5.56 |             74.44 |         78.46 |         79.05 |          70.43 |        68.45 |           80.29 |             68.27 |             56.68 |         6.15 |             84.76 | swing              |               10.99 |                 -2.28 |                  nan |
|     13 | HPE       | HPE                 | US       |               60.76 |             74.31 |         59.26 |         77.48 |          78.44 |        71.14 |           70.82 |             76.21 |             59.72 |         6.81 |             65.68 | medium             |               -4.9  |                 -2.36 |                  nan |
|     14 | CCC       | CCC                 | US       |                3.78 |             74.08 |         80.52 |         77.34 |          70.83 |        70.1  |           86.79 |             81.92 |             57.26 |         7.89 |             66.02 | short              |               -2.61 |                  1.19 |                  nan |
|     15 | BCRX      | BCRX                | US       |                2.22 |             73.98 |         58.8  |         70.77 |          77.18 |        77.63 |           85.39 |             93.93 |             72.81 |         5.84 |             66.59 | long               |               -0.61 |                  2.55 |                  nan |
|     16 | SBLK      | SBLK                | US       |                2.91 |             73.9  |         76.67 |         68.88 |          71.8  |        75.99 |           75.84 |             63.47 |             86.98 |         3.88 |             67.16 | short              |               -1    |                nan    |                  nan |
|     17 | U         | U                   | US       |               17.9  |             73.65 |         82.6  |         83.31 |          64.69 |        48.39 |           45.16 |             96.36 |             21.71 |         8.31 |             67.5  | swing              |               -2.96 |                 -0.24 |                  nan |
|     18 | AUTL      | AUTL                | US       |                0.58 |             73.47 |         86.23 |         77.45 |          66.45 |        69.49 |           56.75 |             59.83 |             99.46 |         7.83 |             63.64 | short              |                1.97 |                 -2.17 |                  nan |
|     19 | SHELL.AS  | SHELL.AS            | EUROPE   |              220.39 |             73.4  |         74.13 |         67.91 |          72.66 |        78.78 |           92.34 |             56.07 |             75.05 |         2.58 |             67.5  | long               |                4.29 |                  1.43 |                  nan |
|     20 | TNK       | Teekay Tankers Ltd. | OTHER    |                2.72 |             73.34 |         80.01 |         74.04 |          72.63 |        68.62 |           81.59 |             74.15 |             38.13 |         4.95 |             84.89 | short              |                0.89 |                  0.95 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                            | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:--------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | INVA     | Innoviva, Inc.                  | US       |                1.34 |                  83.04 |                    76.24 |                 76.09 |              77.53 |                77.94 |                   22.06 |           85.84 |             37.17 |       0.071 |         nan |       nan |        6.67 |         9.72 |          4.93 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|            2 | STNE     | StoneCo Ltd.                    | OTHER    |                1.89 |                  85.75 |                    74.97 |                 72.61 |              76.56 |                61.5  |                   38.5  |           76.68 |             37.48 |       0.622 |         nan |       nan |        1.61 |         4.07 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | BAX      | Baxter International Inc.       | US       |               11.89 |                  85.04 |                    74.09 |                 70.12 |              77.51 |                60.84 |                   39.16 |           58.96 |             53.27 |       0.073 |         nan |       nan |       11.29 |        13.08 |        nan    |       36.68 |                 nan |              nan |                  11 |                  0.58 |
|            4 | BION.SW  | BB Biotech AG                   | EUROPE   |                3.26 |                  72.28 |                    73.76 |                 75.73 |              73.46 |                87.08 |                   12.92 |           86.1  |             57.44 |       0.807 |         nan |       nan |      nan    |       -84.38 |          2.26 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            5 | 0QXR.IL  | Stellantis N.V.                 | OTHER    |               25.94 |                  74.27 |                    73.68 |                 74.17 |              72.77 |                66.75 |                   33.25 |           78.44 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|            6 | 0Q2N.IL  | K+S Aktiengesellschaft          | OTHER    |                3    |                  73.31 |                    72.91 |                 72.38 |              73.77 |                75.58 |                   24.42 |           68.78 |            nan    |       0.247 |         nan |       nan |        1.54 |       nan    |          2.79 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHELL.AS | SHELL.AS                        | EUROPE   |              220.39 |                  66.6  |                    71.5  |                 73.3  |              67.76 |                78.92 |                   21.08 |           92.34 |             56.07 |     nan     |         nan |       nan |      nan    |         9.98 |         10.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | 0P6O.IL  | Volkswagen AG                   | OTHER    |               41.47 |                  66.87 |                    70.51 |                 72.06 |              68.34 |                74.23 |                   25.77 |           80.11 |            nan    |       0.417 |         nan |       nan |        7.45 |       nan    |          2.7  |        0.68 |                 nan |              nan |                   9 |                  0.47 |
|            8 | PARR     | Par Pacific Holdings, Inc.      | US       |                3.34 |                  68.27 |                    69.38 |                 71.08 |              68.25 |                69.96 |                   30.04 |           80.43 |             65.03 |       0.021 |         nan |       nan |        3.78 |         6.53 |          4.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | NWL.MI   | NewPrinces S.p.A.               | EUROPE   |                0.66 |                  68.97 |                    68.53 |                 69.69 |              69.74 |                80.66 |                   19.34 |           72.85 |             55.61 |       1.004 |         nan |       nan |        5.23 |      -117.15 |          2.06 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           10 | SDF.DE   | K+S Aktiengesellschaft        N | EUROPE   |                2.72 |                  64.97 |                    68.51 |                 71.16 |              65.94 |                75.19 |                   24.81 |           88.83 |             56.25 |       0.126 |         nan |       nan |        1.92 |        15.36 |          2.57 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN      | BEN                             | US       |               14.91 |                  58.42 |                    67.56 |                 70.62 |              63.08 |                79.82 |                   20.18 |           89.55 |             66.5  |     nan     |         nan |       nan |      nan    |        10.76 |         23.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                         | EUROPE   |               17.53 |                  61.61 |                    67.44 |                 69.61 |              62.42 |                77.16 |                   22.84 |           96.21 |             41.75 |     nan     |         nan |       nan |      nan    |        10.17 |         13.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                             | US       |              119.27 |                  62.9  |                    67.41 |                 68.94 |              64.61 |                74.64 |                   25.36 |           82.44 |             58.86 |     nan     |         nan |       nan |      nan    |        10.31 |         14.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | DXC      | DXC Technology Company          | US       |                1.5  |                  85.93 |                    67    |                 60.85 |              73.13 |                44.03 |                   55.97 |           42.31 |             33.31 |       0.506 |         nan |       nan |        3.09 |         3.67 |         14.28 |        0.49 |                 nan |              nan |                  10 |                  0.53 |
|           12 | SMWB     | Similarweb Ltd.                 | OTHER    |                0.64 |                  72.1  |                    66.81 |                 65.3  |              69.67 |                61.33 |                   38.67 |           54.35 |             67.11 |       0.039 |         nan |       nan |     -115.29 |        26.73 |        nan    |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           13 | PAH3.DE  | Porsche Automobil Holding SE    | EUROPE   |                8.49 |                  79.46 |                    66.81 |                 63.68 |              74.49 |                63.75 |                   36.25 |           38.62 |             58.07 |      -0.05  |         nan |       nan |     -234.42 |         1.88 |         89.42 |        0.05 |                 nan |              nan |                  10 |                  0.53 |
|           14 | HRB      | H&R Block, Inc.                 | US       |                5.56 |                  59.75 |                    66.71 |                 69.26 |              64.32 |                80.38 |                   19.62 |           80.29 |             68.27 |       0.097 |         nan |       nan |        7.36 |         7.57 |          9.18 |        0.68 |                 nan |              nan |                  12 |                  0.63 |
|           15 | IHS      | IHS Holding Limited             | OTHER    |                2.43 |                  69.67 |                    66.3  |                 66.96 |              68.97 |                58.26 |                   41.74 |           57.58 |             83.14 |      -0.115 |         nan |       nan |        7.47 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           16 | DBX      | Dropbox, Inc.                   | US       |                6.38 |                  78.75 |                    66.18 |                 61.73 |              70.28 |                55.15 |                   44.85 |           50.13 |             36.57 |       0.106 |         nan |       nan |       12.35 |        10.35 |         18.68 |       16.81 |                 nan |              nan |                  11 |                  0.58 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                            | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:--------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | INVA     | Innoviva, Inc.                  | US       |                1.34 |                  83.04 |                    76.24 |                 76.09 |              77.53 |                77.94 |                   22.06 |           85.84 |             37.17 |       0.071 |         nan |       nan |        6.67 |         9.72 |          4.93 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|            4 | BION.SW  | BB Biotech AG                   | EUROPE   |                3.26 |                  72.28 |                    73.76 |                 75.73 |              73.46 |                87.08 |                   12.92 |           86.1  |             57.44 |       0.807 |         nan |       nan |      nan    |       -84.38 |          2.26 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            5 | 0QXR.IL  | Stellantis N.V.                 | OTHER    |               25.94 |                  74.27 |                    73.68 |                 74.17 |              72.77 |                66.75 |                   33.25 |           78.44 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SHELL.AS | SHELL.AS                        | EUROPE   |              220.39 |                  66.6  |                    71.5  |                 73.3  |              67.76 |                78.92 |                   21.08 |           92.34 |             56.07 |     nan     |         nan |       nan |      nan    |         9.98 |         10.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | STNE     | StoneCo Ltd.                    | OTHER    |                1.89 |                  85.75 |                    74.97 |                 72.61 |              76.56 |                61.5  |                   38.5  |           76.68 |             37.48 |       0.622 |         nan |       nan |        1.61 |         4.07 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | 0Q2N.IL  | K+S Aktiengesellschaft          | OTHER    |                3    |                  73.31 |                    72.91 |                 72.38 |              73.77 |                75.58 |                   24.42 |           68.78 |            nan    |       0.247 |         nan |       nan |        1.54 |       nan    |          2.79 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | 0P6O.IL  | Volkswagen AG                   | OTHER    |               41.47 |                  66.87 |                    70.51 |                 72.06 |              68.34 |                74.23 |                   25.77 |           80.11 |            nan    |       0.417 |         nan |       nan |        7.45 |       nan    |          2.7  |        0.68 |                 nan |              nan |                   9 |                  0.47 |
|           10 | SDF.DE   | K+S Aktiengesellschaft        N | EUROPE   |                2.72 |                  64.97 |                    68.51 |                 71.16 |              65.94 |                75.19 |                   24.81 |           88.83 |             56.25 |       0.126 |         nan |       nan |        1.92 |        15.36 |          2.57 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|            8 | PARR     | Par Pacific Holdings, Inc.      | US       |                3.34 |                  68.27 |                    69.38 |                 71.08 |              68.25 |                69.96 |                   30.04 |           80.43 |             65.03 |       0.021 |         nan |       nan |        3.78 |         6.53 |          4.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BEN      | BEN                             | US       |               14.91 |                  58.42 |                    67.56 |                 70.62 |              63.08 |                79.82 |                   20.18 |           89.55 |             66.5  |     nan     |         nan |       nan |      nan    |        10.76 |         23.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | BAX      | Baxter International Inc.       | US       |               11.89 |                  85.04 |                    74.09 |                 70.12 |              77.51 |                60.84 |                   39.16 |           58.96 |             53.27 |       0.073 |         nan |       nan |       11.29 |        13.08 |        nan    |       36.68 |                 nan |              nan |                  11 |                  0.58 |
|            9 | NWL.MI   | NewPrinces S.p.A.               | EUROPE   |                0.66 |                  68.97 |                    68.53 |                 69.69 |              69.74 |                80.66 |                   19.34 |           72.85 |             55.61 |       1.004 |         nan |       nan |        5.23 |      -117.15 |          2.06 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BIRG.IR  | BIRG.IR                         | EUROPE   |               17.53 |                  61.61 |                    67.44 |                 69.61 |              62.42 |                77.16 |                   22.84 |           96.21 |             41.75 |     nan     |         nan |       nan |      nan    |        10.17 |         13.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | HRB      | H&R Block, Inc.                 | US       |                5.56 |                  59.75 |                    66.71 |                 69.26 |              64.32 |                80.38 |                   19.62 |           80.29 |             68.27 |       0.097 |         nan |       nan |        7.36 |         7.57 |          9.18 |        0.68 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY      | BMY                             | US       |              119.27 |                  62.9  |                    67.41 |                 68.94 |              64.61 |                74.64 |                   25.36 |           82.44 |             58.86 |     nan     |         nan |       nan |      nan    |        10.31 |         14.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           22 | AKER.OL  | Aker ASA                        | EUROPE   |                9.76 |                  54.49 |                    64.67 |                 68.67 |              59.97 |                69.26 |                   30.74 |           85.42 |             82.7  |       0.114 |         nan |       nan |        5.31 |        54.78 |          3.77 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|          nan | CRGY     | CRGY                            | US       |                4.56 |                  58.17 |                    65.08 |                 67.4  |              63.14 |                70.8  |                   29.2  |           71.36 |             85.07 |     nan     |         nan |       nan |      nan    |         6.26 |        167.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           15 | IHS      | IHS Holding Limited             | OTHER    |                2.43 |                  69.67 |                    66.3  |                 66.96 |              68.97 |                58.26 |                   41.74 |           57.58 |             83.14 |      -0.115 |         nan |       nan |        7.47 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SBLK     | SBLK                            | US       |                2.91 |                  61.18 |                    65.2  |                 66.58 |              63.08 |                70.46 |                   29.54 |           75.84 |             63.47 |     nan     |         nan |       nan |      nan    |         8.48 |         11.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           35 | DLO      | DLocal Limited                  | OTHER    |                3.63 |                  53.87 |                    62.39 |                 66.42 |              57.82 |                71.31 |                   28.69 |           88.74 |             61.96 |       0.097 |         nan |       nan |       13.53 |        12.65 |         20.14 |      nan    |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BCRX     | BCRX                     | US       |                2.22 |                     0.05 |    -0.05 |      0.04 |                  81.5  |                        78.78 |         58.8  |         70.77 |          77.18 |        77.63 |           85.39 |             93.93 |         5.84 |
|               2 | HRB      | H&R Block, Inc.          | US       |                5.56 |                     0.04 |    -0.04 |      0.32 |                  69.23 |                        76.21 |         78.46 |         79.05 |          70.43 |        68.45 |           80.29 |             68.27 |         6.15 |
|               3 | HPE      | HPE                      | US       |               60.76 |                     0.11 |    -0.1  |      0.1  |                  63.73 |                        73.89 |         59.26 |         77.48 |          78.44 |        71.14 |           70.82 |             76.21 |         6.81 |
|               4 | QNST     | QuinStreet, Inc.         | US       |                1.04 |                     0.04 |     0.01 |      0.35 |                  59.99 |                        72.07 |         79.4  |         74.09 |          65.18 |        59.5  |           67.5  |             65.85 |         6.91 |
|               5 | SYENS.BR | SYENS.BR                 | EUROPE   |                8.22 |                     0.02 |    -0    |      0.16 |                  51.4  |                        71.96 |         77.86 |         73.39 |          62.63 |        57.53 |           59.03 |             90.05 |         5.08 |
|               6 | KRMN     | KRMN                     | US       |                6.66 |                     0.06 |    -0.06 |      0.23 |                  82.92 |                        71.21 |         61.3  |         43.37 |          49.47 |        54.1  |           88.65 |             69.3  |         8.74 |
|               7 | ACX.MC   | Acerinox, S.A.           | EUROPE   |                4.36 |                     0.05 |    -0.04 |      0.05 |                  80.4  |                        70.84 |         57.23 |         67.91 |          70.61 |        65.16 |           67.16 |             75.97 |         4.41 |
|               8 | OKTA     | OKTA                     | US       |               21.2  |                     0.09 |    -0.04 |      0.03 |                  62.05 |                        70.37 |         51.05 |         72.14 |          70.23 |        58.71 |           69.42 |             74.03 |         7.49 |
|               9 | JHX      | JHX                      | US       |               15.14 |                     0.03 |    -0.02 |      0.22 |                  60.55 |                        70.36 |         74.91 |         75.28 |          62.92 |        57.44 |           57.22 |             81.31 |         6.76 |
|              10 | TGB      | TGB                      | US       |                2.68 |                     0.04 |    -0.03 |      0.12 |                  70.04 |                        70.27 |         71.94 |         70.15 |          67.71 |        66.57 |           54.98 |             85.32 |         7.49 |
|              11 | SU.PA    | Schneider Electric S.E.  | EUROPE   |              165.26 |                     0.05 |    -0.05 |      0.1  |                  83.93 |                        69.76 |         63.39 |         61.45 |          62.31 |        58.8  |           77.72 |             66.21 |         4.66 |
|              12 | PANW     | PANW                     | US       |              253.21 |                     0.09 |    -0.07 |      0.07 |                  68.77 |                        69.35 |         56.93 |         72.99 |          67.73 |        49.93 |           55.36 |             76.46 |         6.57 |
|              13 | BEN      | BEN                      | US       |               14.91 |                     0.05 |     0.01 |      0.05 |                  64.38 |                        69.35 |         63.01 |         63.61 |          72.71 |        77.06 |           89.55 |             66.5  |         3.11 |
|              14 | OUT1V.HE | OUT1V.HE                 | EUROPE   |                2.59 |                     0.05 |    -0.03 |     -0.01 |                  78.81 |                        68.97 |         55.63 |         59.91 |          71.49 |        72.39 |           63.33 |             96.84 |         4.48 |
|              15 | BB       | BlackBerry Limited       | OTHER    |                4.22 |                     0.07 |    -0.05 |     -0.07 |                  74.42 |                        68.83 |         36.38 |         62.74 |          71.99 |        62.24 |           82.02 |             65.98 |         7.53 |
|              16 | GEO      | Geo Group Inc (The) REIT | US       |                3.49 |                     0.03 |    -0.02 |     -0.02 |                  64.79 |                        68.65 |         52.62 |         71.69 |          70.48 |        59.86 |           66.11 |             65.77 |         5.4  |
|              17 | KTOS     | KTOS                     | US       |                9.82 |                     0.06 |    -0.05 |      0.26 |                  81.24 |                        68.51 |         64.2  |         50.95 |          46.09 |        46.72 |           61.23 |             79.85 |         8.76 |
|              18 | SIKA.SW  | Sika AG                  | EUROPE   |               31.59 |                     0.05 |    -0.04 |      0.17 |                  81.57 |                        68.42 |         66.22 |         66.4  |          59.28 |        57.01 |           71.47 |             57.96 |         5.33 |
|              19 | BFLY     | Butterfly Network, Inc.  | US       |                2.11 |                     0.05 |    -0.03 |      0.39 |                  79.25 |                        68.41 |         68.42 |         76.85 |          67.88 |        51.69 |           34.63 |             74.47 |         8.19 |
|              20 | DELL     | DELL                     | US       |              244.16 |                     0.12 |    -0.1  |     -0.01 |                  61.84 |                        68.3  |         43.76 |         71.25 |          73.35 |        63.44 |           71.04 |             61.29 |         7.72 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | SNOW     | Snowflake Inc.                                       | US       |               97.28 |             65.67 |         69.87 |         74.98 |          61.46 |        45.85 |           45.82 |             64.08 |             14.21 |         8.09 |             86.02 | swing              |               -5.8  |                 -1.28 |                  nan |
|    nan | NTAP     | NetApp, Inc.                                         | US       |               32.96 |             65.45 |         63.71 |         72.22 |          67.18 |        58.52 |           57.87 |             56.29 |             44.07 |         6.48 |             88.78 | swing              |              -11.42 |                 -3    |                  nan |
|    nan | PD       | PagerDuty, Inc.                                      | US       |                0.81 |             62.39 |         72.41 |         68.95 |          55.82 |        52.06 |           47.54 |             47.64 |             64.1  |         8.14 |             86.86 | short              |               -0.25 |                 -1.64 |                  nan |
|    nan | NTNX     | Nutanix, Inc.                                        | US       |               15.27 |             61.32 |         68.67 |         67.75 |          54.89 |        45.37 |           44.41 |             55.15 |             37.1  |         6.27 |             87.84 | short              |               -8.57 |                 -1.13 |                  nan |
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4550.76 |             57.45 |         55.05 |         51.85 |          59.86 |        62.08 |           89.78 |             58.51 |             29.89 |         5.43 |             89.53 | long               |               -5.43 |                 -1.31 |                  nan |
|    nan | GOLD     | Gold.com, Inc.                                       | US       |                1.14 |             56.12 |         68.66 |         55.75 |          56.5  |        53.89 |           52.34 |             83.78 |             31.06 |         5.91 |             77.94 | short              |                2.51 |                  0.31 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.85 |             53.42 |         45.51 |         56.56 |          52.64 |        54.19 |           36.16 |             46.8  |             68.76 |         8.32 |             85.47 | swing              |               -5.56 |                 -1.24 |                  nan |
|    nan | EDR.MC   | EDREAMS ODIGEO, S.A.                                 | EUROPE   |                0.57 |             51.02 |         51.31 |         57.64 |          50.72 |        47.26 |           62.84 |             35.77 |             42.85 |         8.08 |             83.05 | swing              |                1.69 |                 -2.42 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1489.3  |             50.29 |         31.49 |         42.28 |          58.31 |        61.59 |           86.39 |             61.64 |             31.1  |         6.03 |             89.81 | long               |               -2.5  |                 -0.85 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |             49.81 |         42.75 |         45.29 |          54.33 |        62.76 |           80.42 |             42.65 |             53.77 |         3.83 |             75.81 | long               |                1.35 |                  0.01 |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.                              | US       |                3.42 |             47.22 |         46.29 |         46.98 |          47.46 |        58.68 |           55.58 |             43    |             80.84 |         7.35 |             87.87 | long               |              nan    |                  0.24 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             46.98 |         39.43 |         41.95 |          52.02 |        65.68 |           68.23 |             55.13 |             89.82 |         4.18 |             82.14 | long               |                0.08 |                  0.12 |                  nan |
|    nan | ATHM     | Autohome Inc.                                        | OTHER    |                2.24 |             44.45 |         49.86 |         49.73 |          39.17 |        36.98 |           33.87 |             29.37 |             40.11 |         8.5  |             78.73 | short              |                1.99 |                  0.37 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.77 |             44.43 |         52.37 |         34.91 |          40.63 |        48.23 |           46.65 |             67.9  |             58.62 |         6.91 |             77.1  | short              |                2.73 |                  1.77 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.93 |             39.44 |         42.06 |         27.26 |          36.83 |        46.94 |           60.87 |             18.42 |             43.93 |         8.96 |             78.45 | long               |                6.8  |                  1.08 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.9  |             37.25 |         28.28 |         33.53 |          40.98 |        52.75 |           44.01 |             44.89 |             82.02 |         6.04 |             78.58 | long               |               -1.68 |                 -0.23 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.24 |             36.78 |         25.53 |         33.39 |          40.17 |        53.77 |           41.55 |             38.93 |             94.22 |         7.01 |             78.43 | long               |               -1.58 |                 -0.28 |                  nan |
|    nan | AT1.DE   | Aroundtown SA                                        | EUROPE   |                2.15 |             29.87 |         26.77 |         24.12 |          32.98 |        44.1  |           54    |             34.87 |             53.93 |         5.45 |             75.53 | long               |                7.16 |                 -1.2  |                  nan |
|    nan | DQ       | Daqo New Energy Corp.                                | OTHER    |                0.82 |             24.69 |         48.98 |         22.06 |          21.24 |        27.33 |           24.7  |             25.61 |             39.73 |         8.5  |             76.14 | short              |               -6.04 |                 -0.34 |                  nan |
|    nan | LI       | Li Auto Inc.                                         | OTHER    |               10.76 |             23.11 |         41.36 |         22.32 |          21.87 |        23.89 |           24.13 |             37.57 |             26.55 |         6.61 |             76.54 | short              |              nan    |                  0.03 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    419 | TEM      | TEM     | US       |                9.54 |             52.26 |         74.48 |         60.45 |          44.06 |        32.85 |           30.9  |             82.28 |              4.83 |         9.02 |             63.64 | short              |               10.16 |                  3    |                  nan |
|    340 | BBIO     | BBIO    | US       |               14.17 |             55.05 |         54.41 |         57.52 |          55.68 |        48.68 |           68.13 |             51.7  |              1.66 |         4.72 |             65.57 | swing              |                0.05 |                  2.65 |                  nan |
|    331 | HIMS     | HIMS    | US       |                6.26 |             55.49 |         54.03 |         65.22 |          56.96 |        40.14 |           36.25 |             95.51 |             16.31 |         9.42 |             67.5  | swing              |                3.66 |                  2.64 |                  nan |
|     15 | BCRX     | BCRX    | US       |                2.22 |             73.98 |         58.8  |         70.77 |          77.18 |        77.63 |           85.39 |             93.93 |             72.81 |         5.84 |             66.59 | long               |               -0.61 |                  2.55 |                  nan |
|      5 | BAYN.DE  | BAYN.DE | EUROPE   |               48.15 |             76.25 |         66.32 |         74.43 |          78.07 |        81.97 |          nan    |             91.99 |             71.67 |         6.12 |             64.66 | long               |                5.41 |                  2.5  |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    601 | NBIS     | NBIS   | US       |               52.57 |             43    |         44.43 |         41.22 |          48.09 |        41.58 |           53.88 |              1.09 |             20.38 |         8.87 |             64.66 | medium             |              -11.14 |                 -7    |                  nan |
|    387 | ABCL     | ABCL   | US       |                3.36 |             53.36 |         72.16 |         62.88 |          43.84 |        31.63 |            9.75 |             12.62 |             40.75 |         9.01 |             63.64 | short              |               -2.01 |                 -6.5  |                  nan |
|    489 | BNP.PA   | BNP.PA | EUROPE   |              117.03 |             49.4  |         41.96 |         52.59 |          49.16 |        49.63 |           16.8  |             19.78 |             91.22 |         2.64 |             67.5  | swing              |                2.04 |                 -5.58 |                  nan |
|    563 | MATV     | MATV   | US       |                0.58 |             45.5  |         64.29 |         47.45 |          33.64 |        43.55 |           27.75 |              4.98 |             81.2  |         8.05 |             67.05 | short              |              nan    |                 -5.5  |                  nan |
|    478 | ACA.PA   | ACA.PA | EUROPE   |               57.99 |             49.78 |         51.16 |         55.89 |          48    |        48.4  |           11.49 |             35.8  |             93.01 |         1.95 |             67.5  | swing              |               -0.65 |                 -5.07 |                  nan |

## Duplicate-security checks

- KRX.IR duplicates HEADL.XC (security_id=ISIN:PLCTHQM00018)
- GL9.IR duplicates HEADL.XC (security_id=ISIN:PLCTHQM00018)
- TEK.L duplicates HEADL.XC (security_id=ISIN:PLCTHQM00018)
- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- VTYL.XC duplicates HEADL.XC (security_id=ISIN:PLCTHQM00018)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)

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
- Excluded by hard/data filters: **286**
- Event watch (otherwise eligible): **20**
- Final eligible: **694**
- Eligible change vs previous stored run: **-7**

Top exclusion categories:
- liquidity: 231
- price: 173
- market_cap: 153
- price_history: 19
- data_confidence: 15
- duplicate_listing: 6
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| BION.SW | 10 | 4 |  | 2 | 2 | main,value,quality_value |
| PARR | 34 | 8 | 53 | 8 | 1 | value,quality_value |
| 0Q2N.IL | 107 | 6 |  | 5 | 1 | value,quality_value |
| BAX | 127 | 3 | 31 | 9 | 1 | value,quality_value |
| SDF.DE | 133 | 10 |  | 7 | 1 | value,quality_value |
| INVA | 421 | 1 |  | 1 | 1 | value,quality_value |
| 0QXR.IL | 443 | 5 |  | 3 | 1 | value,quality_value |
| NWL.MI | 541 | 9 | 199 | 10 | 1 | value,quality_value |
| 0P6O.IL | 560 | 7 |  | 6 | 1 | value,quality_value |
| STNE | 645 | 2 |  | 4 | 1 | value,quality_value |
| AKER.OL | 1 | 22 |  | 12 | 1 | main |
| SSABBH.HE | 2 |  |  |  | 1 | main |
| HALO | 3 |  |  |  | 1 | main |
| TKA.DE | 4 |  |  |  | 1 | main |
| BAYN.DE | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (HALO, TKA.DE, BAYN.DE, PBF, CRGY, PSX, RMAX)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (SYENS.BR, KRMN)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | HRB | value+pullback | 70.18 | 59.75 | 69.23 | 80.29 | 68.27 | 80.38 | 74.44 |
| 2 | BAX | value+pullback | 69.57 | 85.04 | 70.90 | 58.96 | 53.27 | 60.84 | 63.89 |
| 3 | NWL.MI | value+pullback | 68.84 | 68.97 | 62.11 | 72.85 | 55.61 | 80.66 | 47.11 |
| 4 | SMWB | value+pullback | 67.29 | 72.10 | 74.13 | 54.35 | 67.11 | 61.33 | 64.01 |
| 5 | PAH3.DE | value+pullback | 66.94 | 79.46 | 75.03 | 38.62 | 58.07 | 63.75 | 38.57 |
| 6 | ACX.MC | value+pullback | 65.88 | 55.54 | 80.40 | 67.16 | 75.97 | 57.22 | 66.54 |
| 7 | 0P6O.IL | value+pullback | 63.94 | 66.87 | 48.08 | 80.11 |  | 74.23 | 45.76 |
| 8 | ETG | value+pullback | 63.70 | 57.57 | 52.24 | 67.27 | 82.43 | 75.18 | 60.14 |
| 9 | CNC | value+pullback | 62.68 | 77.88 | 72.51 | 37.36 | 65.57 | 45.17 | 61.02 |
| 10 | DBX | value+pullback | 62.60 | 78.75 | 67.09 | 50.13 | 36.57 | 55.15 | 58.23 |
| 11 | GENI | value+pullback | 62.08 | 70.83 | 55.24 | 51.47 | 82.14 | 55.42 | 61.89 |
| 12 | NEXI.MI | value+pullback | 61.89 | 73.52 | 71.87 | 54.53 | 42.65 | 47.12 | 55.69 |
| 13 | DOM.ST | value+pullback | 61.82 | 64.68 | 70.32 | 63.40 | 31.08 | 61.10 | 35.07 |
| 14 | PARR | value+pullback | 61.63 | 68.27 | 34.36 | 80.43 | 65.03 | 69.96 | 70.49 |
| 15 | TV | value+pullback | 61.24 | 69.76 | 77.79 | 45.47 | 30.29 | 55.07 | 36.03 |
| 16 | MSFT | value+pullback | 60.75 | 58.21 | 68.20 | 62.64 | 63.35 | 52.52 | 57.58 |
| 17 | ORCL | value+pullback | 60.53 | 69.90 | 73.72 | 52.21 | 56.15 | 38.42 | 42.39 |
| 18 | PKX | value+pullback | 60.16 | 58.67 | 42.26 | 78.22 | 67.48 | 67.57 | 59.61 |
| 19 | WKC | value+pullback | 59.82 | 57.82 | 50.60 | 58.15 | 74.73 | 68.13 | 64.74 |
| 20 | VOW3.DE | value+pullback | 58.87 | 71.70 | 49.50 | 59.17 | 43.04 | 59.06 | 43.49 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 8/10 | 9/10 | 10/10 | 7/10 | 0/10 | 67.0 | 3 / 7 |
| Top 25 | 23/25 | 24/25 | 25/25 | 22/25 | 0/25 | 67.0 | 8 / 17 |
| Top 50 | 48/50 | 48/50 | 49/50 | 45/50 | 0/50 | 67.0 | 15 / 35 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=2, mid_5_20b=5, large_20_100b=2
