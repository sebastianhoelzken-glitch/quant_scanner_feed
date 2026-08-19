# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-19

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

- **EUROPE:** 91.2/100
- **OTHER:** 74.8/100
- **US:** 85.4/100

## Main multi-horizon ranking

|   rank | symbol    | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HALO      | HALO                       | US       |               10.28 |             79.79 |         86.37 |         83.35 |          75.45 |        76.24 |           86.29 |             69.28 |             60.86 |         5.4  |             66.48 | short              |              nan    |                  0.88 |                  nan |
|      2 | HPE       | HPE                        | US       |               63.67 |             79.21 |         77.39 |         83.88 |          81.03 |        73.51 |           71.48 |             73.86 |             59.68 |         6.73 |             65.68 | swing              |               -1.3  |                 -1.4  |                  nan |
|      3 | PBF       | PBF                        | US       |                7.7  |             78.89 |         83.15 |         82.13 |          75.65 |        72.25 |           51.49 |             56.39 |             92.94 |         6.97 |             67.05 | short              |                1.23 |                 -2.75 |                  nan |
|      4 | MU        | MU                         | US       |              917.3  |             78.67 |         57.16 |         72.53 |          84.81 |        85.78 |           95.59 |             59.16 |             77.39 |         8.06 |             67.5  | long               |               -1.43 |                nan    |                  nan |
|      5 | FRO       | FRO                        | US       |                8.36 |             77.83 |         78.21 |         76.04 |          77.89 |        77.78 |           84.2  |             63.61 |             67.96 |         5.09 |             67.5  | short              |              nan    |                  0.67 |                  nan |
|      6 | PSX       | PSX                        | US       |               83.88 |             77.51 |         79    |         79.33 |          76.02 |        74.2  |           78.72 |             54.1  |             65.78 |         3.29 |             67.5  | swing              |                1.27 |                nan    |                  nan |
|      7 | NAT       | NAT                        | US       |                1.27 |             77.03 |         75.71 |         80.35 |          78.34 |        71.29 |           78.7  |             73.37 |             43.83 |         4.43 |             66.7  | swing              |                1.65 |                nan    |                  nan |
|      8 | NTAP      | NTAP                       | US       |               34.63 |             76.87 |         79.52 |         80.57 |          74.22 |        66.93 |           86.19 |             52.17 |             28.18 |         6.14 |             65.45 | swing              |                0.76 |                 -0.72 |                  nan |
|      9 | AMC       | AMC                        | US       |                1.83 |             76.86 |         60.49 |         80.15 |          76.78 |        76.94 |           83.01 |             79.64 |            nan    |         9.62 |             61.25 | swing              |                1.03 |                nan    |                  nan |
|     10 | CCC       | CCC                        | US       |                3.63 |             76.69 |         82.11 |         80.02 |          73.12 |        73.37 |           86.72 |             80.6  |             61.72 |         7.94 |             66.02 | short              |                4.31 |                  1.72 |                  nan |
|     11 | PARR      | Par Pacific Holdings, Inc. | US       |                3.48 |             76.67 |         68.78 |         75.04 |          79.58 |        78.3  |           83.7  |             65.25 |             74.67 |         6.63 |             85.72 | medium             |               -4.14 |                  0.29 |                  nan |
|     12 | U         | U                          | US       |               17.76 |             76.61 |         85.92 |         86.96 |          67.3  |        50.74 |           43.59 |             97.23 |             23.79 |         8.32 |             67.5  | swing              |                0.4  |                  0.35 |                  nan |
|     13 | BAX       | BAX                        | US       |               11.58 |             76.38 |         75.78 |         83.82 |          76.97 |        74.94 |           76.26 |             97.59 |             64.26 |         5.8  |             66.02 | swing              |                0.17 |                  0.58 |                  nan |
|     14 | HAE       | HAE                        | US       |                4.11 |             76.32 |         82.29 |         83.35 |          70.36 |        58.73 |           52.09 |             69.64 |             39.82 |         6.45 |             66.14 | swing              |              nan    |                nan    |                  nan |
|     15 | SSABBH.HE | SSABBH.HE                  | EUROPE   |                9.46 |             76.22 |         72.41 |         72.24 |          80.04 |        82.7  |           74.69 |            nan    |             98.54 |         3.22 |             62.84 | long               |              nan    |                 -1.59 |                  nan |
|     16 | RNW       | RNW                        | US       |                2.15 |             76.09 |         76.6  |         75.59 |          73.9  |        78.51 |           84.56 |             85.06 |             81.52 |         6.09 |             65.68 | long               |               -0.04 |                  1.29 |                  nan |
|     17 | ZD        | ZD                         | US       |                1.63 |             75.87 |         73.24 |         82.82 |          78.5  |        72.87 |           51.55 |             89.16 |             88.11 |         5.24 |             67.05 | swing              |              nan    |                 -1.84 |                  nan |
|     18 | NOEJ.DE   | NOEJ.DE                    | EUROPE   |                0.58 |             75.67 |         81.84 |         76.3  |          75.05 |        69.76 |           95.1  |             89.88 |             28.07 |         4.05 |             65.68 | short              |               -1.32 |                nan    |                  nan |
|     19 | DHT       | DHT                        | US       |                2.69 |             75.02 |         77.39 |         69.97 |          72.68 |        77.35 |           88.26 |             42.77 |             73.81 |         4.13 |             67.5  | short              |                0.89 |                  0.11 |                  nan |
|     20 | SBLK      | SBLK                       | US       |                2.9  |             74.89 |         80.49 |         71.59 |          72.65 |        77.13 |           73.95 |             59.76 |             88.02 |         3.7  |             67.16 | short              |              nan    |                nan    |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | STNE      | StoneCo Ltd.                                           | OTHER    |                1.82 |                  77.2  |                    73.74 |                 73.42 |              72.6  |                72.49 |                   27.51 |           87.42 |             39.66 |       0.647 |         nan |       nan |        1.6  |         3.91 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | PARR      | Par Pacific Holdings, Inc.                             | US       |                3.48 |                  73.92 |                    72.55 |                 74.01 |              71.8  |                66.92 |                   33.08 |           83.7  |             65.25 |       0.02  |         nan |       nan |        3.92 |         6.81 |          4.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | VOLV-B.ST | AB Volvo (publ)                                        | EUROPE   |               62.8  |                  80.14 |                    71.3  |                 68.06 |              74.5  |                60.44 |                   39.56 |           56.18 |             59.22 |       0.035 |         nan |       nan |       16.12 |        13.67 |         19.34 |        1.42 |                 nan |              nan |                  12 |                  0.63 |
|            4 | MOMO      | Hello Group Inc.                                       | OTHER    |                0.73 |                  76.43 |                    70.88 |                 69.58 |              73.64 |                71.68 |                   28.32 |           63.46 |             57.11 |       0.573 |         nan |       nan |       -5.15 |         5.36 |          8.73 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                                               | EUROPE   |              219.31 |                  64.74 |                    70.24 |                 72.24 |              66.08 |                78.69 |                   21.31 |           93.41 |             53.01 |     nan     |         nan |       nan |      nan    |         9.94 |         10.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAH3.DE   | PAH3.DE                                                | EUROPE   |                8.38 |                  63.93 |                    69.54 |                 71.29 |              68.9  |                80.06 |                   19.94 |          nan    |             84.58 |     nan     |         nan |       nan |      nan    |         1.85 |         88.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | BION.SW   | BB Biotech AG                                          | EUROPE   |                3.25 |                  72.85 |                    68.66 |                 66.9  |              66.64 |                77.81 |                   22.19 |           88.72 |              1.77 |       0.809 |         nan |       nan |      nan    |       -84.22 |          2.25 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            6 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras                   | OTHER    |               96.76 |                  79.16 |                    67.92 |                 65.74 |              72.8  |                49.83 |                   50.17 |           49.57 |             68.37 |       0.162 |         nan |       nan |        1.72 |         6.65 |          4.12 |        4.02 |                 nan |              nan |                  12 |                  0.63 |
|            7 | IHS       | IHS Holding Limited                                    | OTHER    |                2.43 |                  73.36 |                    67.61 |                 67.14 |              72.13 |                61.24 |                   38.76 |           50.04 |             82.9  |      -0.115 |         nan |       nan |        7.47 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | GSL       | Global Ship Lease, Inc.                                | OTHER    |                1.34 |                  70.72 |                    67.32 |                 67.25 |              67.51 |                71.21 |                   28.79 |           76.3  |             37.79 |       0.083 |         nan |       nan |        3.73 |         4.88 |          4.23 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | VOW.DE    | VOW.DE                                                 | EUROPE   |               37.45 |                  67.85 |                    66.97 |                 66.68 |              67.07 |                65.4  |                   34.6  |          nan    |             64.46 |     nan     |         nan |       nan |      nan    |         2.75 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN       | BEN                                                    | US       |               14.91 |                  58.59 |                    66.78 |                 69.52 |              62.65 |                77.98 |                   22.02 |           87.25 |             64.34 |     nan     |         nan |       nan |      nan    |        10.76 |         23.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY       | BMY                                                    | US       |              116.48 |                  63.13 |                    66.59 |                 67.76 |              64.16 |                72.78 |                   27.22 |           80.07 |             56.14 |     nan     |         nan |       nan |      nan    |        10.07 |         14.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | UNIT      | Uniti Group Inc.                                       | US       |                2.08 |                  80.26 |                    66.53 |                 63.39 |              68.82 |                44.64 |                   55.36 |           64.36 |             29.93 |      -0.107 |         nan |       nan |        9.09 |       -13.96 |          2.58 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|          nan | VOW3.DE   | VOW3.DE                                                | EUROPE   |               36.9  |                  68.68 |                    66.4  |                 65.72 |              66.65 |                61.81 |                   38.19 |          nan    |             60.72 |     nan     |         nan |       nan |      nan    |         3.13 |          7.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                                                | EUROPE   |               18.03 |                  58.73 |                    65.45 |                 67.9  |              60.04 |                76.71 |                   23.29 |           96.14 |             39.52 |     nan     |         nan |       nan |      nan    |        10.47 |         14.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET        | ET                                                     | US       |               63.68 |                  62.06 |                    65.37 |                 66.56 |              61.73 |                73.35 |                   26.65 |           87.45 |             38.43 |     nan     |         nan |       nan |      nan    |        12.24 |         14.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | ETG       | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.58 |                  59.24 |                    65.29 |                 66.93 |              64.21 |                74.44 |                   25.56 |           67.48 |             81.58 |       0.027 |         nan |       nan |      nan    |       nan    |          3.72 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | FRO       | FRO                                                    | US       |                8.36 |                  58.46 |                    65.25 |                 67.74 |              61.46 |                72.29 |                   27.71 |           84.2  |             63.61 |     nan     |         nan |       nan |      nan    |        10.7  |         10.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                                                    | US       |                2.69 |                  61.63 |                    65.1  |                 66.64 |              61.17 |                69.52 |                   30.48 |           88.26 |             42.77 |     nan     |         nan |       nan |      nan    |        10.27 |          6.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | PARR      | Par Pacific Holdings, Inc.                             | US       |                3.48 |                  73.92 |                    72.55 |                 74.01 |              71.8  |                66.92 |                   33.08 |           83.7  |             65.25 |       0.02  |         nan |       nan |        3.92 |         6.81 |          4.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            1 | STNE      | StoneCo Ltd.                                           | OTHER    |                1.82 |                  77.2  |                    73.74 |                 73.42 |              72.6  |                72.49 |                   27.51 |           87.42 |             39.66 |       0.647 |         nan |       nan |        1.6  |         3.91 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                                               | EUROPE   |              219.31 |                  64.74 |                    70.24 |                 72.24 |              66.08 |                78.69 |                   21.31 |           93.41 |             53.01 |     nan     |         nan |       nan |      nan    |         9.94 |         10.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAH3.DE   | PAH3.DE                                                | EUROPE   |                8.38 |                  63.93 |                    69.54 |                 71.29 |              68.9  |                80.06 |                   19.94 |          nan    |             84.58 |     nan     |         nan |       nan |      nan    |         1.85 |         88.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | MOMO      | Hello Group Inc.                                       | OTHER    |                0.73 |                  76.43 |                    70.88 |                 69.58 |              73.64 |                71.68 |                   28.32 |           63.46 |             57.11 |       0.573 |         nan |       nan |       -5.15 |         5.36 |          8.73 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BEN       | BEN                                                    | US       |               14.91 |                  58.59 |                    66.78 |                 69.52 |              62.65 |                77.98 |                   22.02 |           87.25 |             64.34 |     nan     |         nan |       nan |      nan    |        10.76 |         23.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | VOLV-B.ST | AB Volvo (publ)                                        | EUROPE   |               62.8  |                  80.14 |                    71.3  |                 68.06 |              74.5  |                60.44 |                   39.56 |           56.18 |             59.22 |       0.035 |         nan |       nan |       16.12 |        13.67 |         19.34 |        1.42 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR   | BIRG.IR                                                | EUROPE   |               18.03 |                  58.73 |                    65.45 |                 67.9  |              60.04 |                76.71 |                   23.29 |           96.14 |             39.52 |     nan     |         nan |       nan |      nan    |        10.47 |         14.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY       | BMY                                                    | US       |              116.48 |                  63.13 |                    66.59 |                 67.76 |              64.16 |                72.78 |                   27.22 |           80.07 |             56.14 |     nan     |         nan |       nan |      nan    |        10.07 |         14.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                                                    | US       |                8.36 |                  58.46 |                    65.25 |                 67.74 |              61.46 |                72.29 |                   27.71 |           84.2  |             63.61 |     nan     |         nan |       nan |      nan    |        10.7  |         10.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AOD       | Abrdn Total Dynamic Dividend Fund                      | OTHER    |                0.97 |                  52.3  |                    64.13 |                 67.61 |              60.5  |                81.73 |                   18.27 |           78.46 |             81.32 |     nan     |         nan |       nan |      nan    |       nan    |          4.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | GSL       | Global Ship Lease, Inc.                                | OTHER    |                1.34 |                  70.72 |                    67.32 |                 67.25 |              67.51 |                71.21 |                   28.79 |           76.3  |             37.79 |       0.083 |         nan |       nan |        3.73 |         4.88 |          4.23 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            7 | IHS       | IHS Holding Limited                                    | OTHER    |                2.43 |                  73.36 |                    67.61 |                 67.14 |              72.13 |                61.24 |                   38.76 |           50.04 |             82.9  |      -0.115 |         nan |       nan |        7.47 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | ETG       | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.58 |                  59.24 |                    65.29 |                 66.93 |              64.21 |                74.44 |                   25.56 |           67.48 |             81.58 |       0.027 |         nan |       nan |      nan    |       nan    |          3.72 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            5 | BION.SW   | BB Biotech AG                                          | EUROPE   |                3.25 |                  72.85 |                    68.66 |                 66.9  |              66.64 |                77.81 |                   22.19 |           88.72 |              1.77 |       0.809 |         nan |       nan |      nan    |       -84.22 |          2.25 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           18 | TNK       | Teekay Tankers Ltd.                                    | OTHER    |                2.66 |                  52.79 |                    62.78 |                 66.71 |              59.8  |                80.1  |                   19.9  |           79.57 |             73.67 |       0.073 |         nan |       nan |        3.75 |         8.18 |          5.25 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | MU        | MU                                                     | US       |              917.3  |                  51.81 |                    62.47 |                 66.68 |              55.94 |                70.65 |                   29.35 |           95.59 |             59.16 |     nan     |         nan |       nan |      nan    |         6.07 |         21.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE    | VOW.DE                                                 | EUROPE   |               37.45 |                  67.85 |                    66.97 |                 66.68 |              67.07 |                65.4  |                   34.6  |          nan    |             64.46 |     nan     |         nan |       nan |      nan    |         2.75 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                                                    | US       |                2.69 |                  61.63 |                    65.1  |                 66.64 |              61.17 |                69.52 |                   30.48 |           88.26 |             42.77 |     nan     |         nan |       nan |      nan    |        10.27 |          6.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET        | ET                                                     | US       |               63.68 |                  62.06 |                    65.37 |                 66.56 |              61.73 |                73.35 |                   26.65 |           87.45 |             38.43 |     nan     |         nan |       nan |      nan    |        12.24 |         14.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.58 |                     0.09 |    -0.06 |      0.17 |                  69.9  |                        82.29 |         75.78 |         83.82 |          76.97 |        74.94 |           76.26 |             97.59 |         5.8  |
|               2 | BCRX     | BCRX     | US       |                2.14 |                     0.08 |    -0.06 |      0.03 |                  70.91 |                        76.91 |         56.45 |         70.42 |          78.76 |        80.06 |           84.64 |             94.22 |         5.67 |
|               3 | ZETA     | ZETA     | US       |                6.12 |                     0.05 |    -0.03 |      0.33 |                  75.04 |                        74.94 |         80.71 |         82.15 |          67.72 |        53.71 |           49.04 |             85.36 |         7.48 |
|               4 | SNOW     | SNOW     | US       |               97.35 |                     0.04 |    -0.03 |      0.2  |                  66.59 |                        74.87 |         74.99 |         84.33 |          67.96 |        47.53 |           42.64 |             94.58 |         8.84 |
|               5 | JHX      | JHX      | US       |               14.68 |                     0.06 |    -0.06 |      0.18 |                  86.03 |                        74.7  |         73.53 |         76.17 |          64.67 |        60.45 |           58.45 |             80.12 |         6.8  |
|               6 | PLTR     | PLTR     | US       |              355.89 |                     0.04 |    -0.02 |      0.29 |                  68.29 |                        74.53 |         77.61 |         66.05 |          58.06 |        54.92 |           89.8  |             50.12 |         8.39 |
|               7 | SYENS.BR | SYENS.BR | EUROPE   |                8.25 |                     0.02 |     0    |      0.16 |                  46.39 |                        73.98 |         78.82 |         71.48 |          62.71 |        58.43 |           70.12 |             90.6  |         5.06 |
|               8 | GENI     | GENI     | US       |                1.8  |                     0.11 |    -0.04 |      0.13 |                  50.01 |                        73.96 |         70.42 |         77.51 |          71.16 |        72.57 |           65.07 |             97.95 |         9.12 |
|               9 | NET      | NET      | US       |               92.64 |                     0.09 |    -0.02 |      0.11 |                  55.07 |                        73.91 |         74.98 |         80.43 |          70.01 |        52.37 |           57.06 |             93.49 |         6.77 |
|              10 | PANW     | PANW     | US       |              263.26 |                     0.06 |    -0.03 |      0.09 |                  78.05 |                        73.09 |         68.35 |         78.49 |          70.05 |        52.21 |           55.42 |             73.73 |         6.47 |
|              11 | QNST     | QNST     | US       |                1.03 |                     0.06 |    -0.01 |      0.28 |                  71.41 |                        73    |         80.66 |         75.86 |          69.49 |        71.35 |           83.75 |             34.7  |         7.79 |
|              12 | OKTA     | OKTA     | US       |               21.79 |                     0.07 |    -0.04 |      0.02 |                  72.26 |                        72.82 |         54.91 |         75.84 |          71.99 |        59.89 |           66.92 |             71.2  |         7.44 |
|              13 | NWL      | NWL      | US       |                2.18 |                     0.07 |    -0.04 |      0.14 |                  73.46 |                        72.68 |         70.65 |         81.45 |          69.44 |        64.72 |           33.11 |             95.42 |         8.08 |
|              14 | CRWD     | CRWD     | US       |              187.18 |                     0.06 |    -0.04 |      0.11 |                  82.07 |                        72.25 |         67.1  |         78.19 |          67.3  |        45.85 |           39.89 |             85.78 |         6.67 |
|              15 | FSLY     | FSLY     | US       |                3.66 |                     0.11 |    -0.08 |      0.28 |                  56.34 |                        71.67 |         76.53 |         80.6  |          71.51 |        52.92 |           40.33 |             99.04 |         8.5  |
|              16 | DNOW     | DNOW     | US       |                2.49 |                     0.05 |    -0.04 |      0.12 |                  83.02 |                        71.41 |         71.1  |         70.11 |          59.83 |        57.87 |           48.98 |             90.72 |         5.02 |
|              17 | BFLY     | BFLY     | US       |                2.07 |                     0.07 |    -0.04 |      0.32 |                  71.72 |                        71.38 |         74.31 |         80.36 |          70.04 |        52.11 |           47.1  |             73.49 |         8.36 |
|              18 | KRX.IR   | KRX.IR   | EUROPE   |               18.23 |                     0.02 |    -0.02 |      0.33 |                  58.72 |                        71.32 |         75.74 |         67.21 |          61.31 |        60.8  |           96.63 |             35.42 |         5.04 |
|              19 | DCH      | DCH      | US       |                1.33 |                     0.06 |    -0.06 |      0.18 |                  85.87 |                        71.21 |         68.57 |         61.45 |          62.25 |        69.06 |           45.95 |             99.04 |         7.41 |
|              20 | NTSK     | NTSK     | US       |                5.36 |                     0.05 |    -0    |      0.15 |                  68.52 |                        71.02 |         75.92 |         74.96 |          59.72 |        43.68 |           51.82 |             82.77 |         9.15 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4595.03 |             62.88 |         64.12 |         55.68 |          62.02 |        63.74 |           92.75 |             59.93 |             27.88 |         5.4  |             89.53 | short              |                1.07 |                 -0.28 |                  nan |
|    nan | PD       | PagerDuty, Inc.                                      | US       |                0.78 |             62.64 |         70.23 |         69.16 |          56.11 |        51.43 |           48.92 |             50.35 |             58.04 |         8.2  |             86.86 | short              |                2.96 |                 -1.66 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.83 |             58.98 |         53.82 |         59.46 |          58.49 |        64.81 |           57.97 |             48.92 |             78.33 |         8.38 |             87.57 | long               |               -4.05 |                 -0.32 |                  nan |
|    nan | JOYY     | JOYY Inc.                                            | OTHER    |                3.21 |             56.21 |         56.3  |         61.21 |          56.12 |        49.09 |           49.34 |             49.92 |             33.17 |         4.68 |             82.25 | swing              |                2.29 |                nan    |                  nan |
|    nan | GOLD     | Gold.com, Inc.                                       | US       |                1.05 |             53.61 |         53.66 |         50.39 |          55.22 |        53.57 |           49.49 |             83.45 |             33.04 |         5.68 |             77.94 | medium             |               -4.98 |                 -0.12 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1560.83 |             52.8  |         38.28 |         46.41 |          59.19 |        60.61 |           83.57 |             63.38 |             28.73 |         6.02 |             89.81 | long               |               -1.35 |                 -0.11 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.05 |             48.47 |         39.23 |         42.44 |          54.49 |        64.62 |           84.59 |             43.33 |             56.01 |         3.78 |             75.81 | long               |               -1.71 |                 -0.08 |                  nan |
|    nan | MTRX     | Matrix Service Company                               | US       |                0.28 |             43.48 |         39.28 |         41.06 |          45.9  |        49.46 |           40.38 |             61.05 |             67.74 |         5.82 |             80.44 | long               |              nan    |                 -1.66 |                  nan |
|    nan | ATHM     | Autohome Inc.                                        | OTHER    |                2.18 |             42.46 |         46.38 |         49.33 |          38.55 |        35.94 |           32.89 |             31.87 |             36.79 |         8.5  |             78.73 | swing              |                2.75 |                  0.27 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.74 |             41.7  |         42.52 |         32.87 |          40.89 |        48.06 |           52.35 |             67.69 |             50.46 |         7    |             77.1  | long               |                0.36 |                  1.68 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.89 |             38.94 |         30.05 |         34.92 |          42.95 |        54.63 |           52.15 |             47.44 |             75.88 |         6.14 |             78.58 | long               |               -7.19 |                  0.18 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.27 |             38.36 |         27.37 |         34.69 |          42.02 |        56.19 |           52.87 |             36.98 |             87.31 |         7.06 |             78.48 | long               |               -6.38 |                  0.09 |                  nan |
|    nan | WB       | Weibo Corporation                                    | OTHER    |                1.61 |             37.3  |         32.67 |         32.41 |          41.93 |        58.14 |           68.2  |             26.08 |             78.81 |         8.5  |             82.41 | long               |                1.72 |                  0.13 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.86 |             32.64 |         25.82 |         23.21 |          39.46 |        52.36 |           73.79 |             19.44 |             47.71 |         9.02 |             78.45 | long               |               -2.13 |                 -0.08 |                  nan |
|    nan | DQ       | Daqo New Energy Corp.                                | OTHER    |                0.81 |             30.74 |         50.28 |         24.36 |          25.7  |        35.77 |           31.96 |             27.18 |             58.86 |         8.5  |             76.14 | short              |               -1.99 |                  1.03 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    210 | ARGX.BR  | ARGX.BR  | EUROPE   |               54.6  |             62.43 |         78.48 |         64.41 |          60.44 |        58.61 |           94.16 |             43.86 |              8.43 |         5.71 |             67.5  | short              |              nan    |                  4.89 |                  nan |
|    279 | KLAC     | KLAC     | US       |              219.72 |             59.64 |         40.74 |         53.68 |          68.88 |        65.61 |           95.4  |             55.18 |             14.15 |         8.16 |             65.45 | medium             |               -1.01 |                  2.96 |                  nan |
|     23 | BCRX     | BCRX     | US       |                2.14 |             74.59 |         56.45 |         70.42 |          78.76 |        80.06 |           84.64 |             94.22 |             76.69 |         5.67 |             66.59 | long               |              nan    |                  2.7  |                  nan |
|    414 | YMM      | YMM      | US       |                7.95 |             54.05 |         37.95 |         51.65 |          56.45 |        63.11 |           53.31 |             82.29 |             79.03 |         6.19 |             65.11 | long               |               -0.08 |                  2.64 |                  nan |
|    650 | STLAM.MI | STLAM.MI | EUROPE   |               17.11 |             39.36 |         34.72 |         36.15 |          42.56 |        49.43 |           19.65 |             87.11 |             90.31 |         6.82 |             66.48 | long               |                0.15 |                  2.63 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    493 | RBI.VI   | RBI.VI | EUROPE   |               20.32 |             50.46 |         57.46 |         54.69 |          46.23 |        39.62 |           12.46 |              9.52 |             66.2  |         3.58 |             66.14 | short              |               -1.04 |                 -6.83 |                  nan |
|    555 | BNP.PA   | BNP.PA | EUROPE   |              119.81 |             47.35 |         47.09 |         51.39 |          47.62 |        46.48 |           27.13 |             19.64 |             72.2  |         2.51 |             67.5  | swing              |               -4.53 |                 -6.35 |                  nan |
|    386 | ABCL     | ABCL   | US       |                2.94 |             55.37 |         74.99 |         65.28 |          45.46 |        33.9  |            8.88 |             10.12 |             44.36 |         9.03 |             63.64 | short              |                0.51 |                 -6.12 |                  nan |
|    634 | UCG.MI   | UCG.MI | EUROPE   |              124.81 |             40.98 |         42.8  |         45.97 |          39.16 |        34.55 |            9.86 |             23.86 |             56.53 |         3.47 |             66.14 | swing              |               -4.26 |                 -5.84 |                  nan |
|    374 | UMAC     | UMAC   | OTHER    |                1.32 |             55.73 |         71.04 |         59.09 |          52.38 |        44.74 |           53.87 |              7.11 |             25.71 |         9.12 |             64.66 | short              |                0.33 |                 -5.68 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.90

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
- Excluded by hard/data filters: **284**
- Event watch (otherwise eligible): **15**
- Final eligible: **701**
- Eligible change vs previous stored run: **-1**

Top exclusion categories:
- liquidity: 231
- price: 173
- market_cap: 151
- price_history: 18
- data_confidence: 15
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 11 | 2 |  | 1 | 1 | value,quality_value |
| GSL | 161 | 8 |  | 5 | 1 | value,quality_value |
| BION.SW | 163 | 5 |  | 8 | 1 | value,quality_value |
| ETG | 229 | 10 | 74 | 7 | 1 | value,quality_value |
| IHS | 328 | 7 |  | 6 | 1 | value,quality_value |
| VOLV-B.ST | 425 | 3 | 257 | 4 | 1 | value,quality_value |
| MOMO | 561 | 4 | 277 | 3 | 1 | value,quality_value |
| STNE | 644 | 1 |  | 2 | 1 | value,quality_value |
| HALO | 1 |  |  |  | 1 | main |
| HPE | 2 |  |  |  | 1 | main |
| PBF | 3 |  |  |  | 1 | main |
| MU | 4 |  |  |  | 1 | main |
| FRO | 5 |  |  |  | 1 | main |
| PSX | 6 |  |  |  | 1 | main |
| NAT | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (HALO, PBF, MU, FRO, PSX, NAT, NTAP, AMC, CCC)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (SYENS.BR, GENI)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | MOMO | value+pullback | 68.76 | 76.43 | 65.05 | 63.46 | 57.11 | 71.68 | 46.90 |
| 2 | ETG | value+pullback | 64.51 | 59.24 | 54.29 | 67.48 | 81.58 | 74.44 | 61.85 |
| 3 | VOLV-B.ST | value+pullback | 64.36 | 80.14 | 55.52 | 56.18 | 59.22 | 60.44 | 53.73 |
| 4 | MSFT | value+pullback | 63.41 | 58.21 | 79.51 | 61.01 | 64.64 | 52.25 | 58.72 |
| 5 | PBR-A | value+pullback | 62.81 | 79.16 | 59.31 | 49.57 | 68.37 | 49.83 | 57.75 |
| 6 | ALL-PH | value+pullback | 62.61 | 62.66 | 70.91 | 67.68 | 43.17 | 58.11 | 43.79 |
| 7 | AMCX | value+pullback | 62.09 | 65.95 | 54.11 | 45.85 | 78.07 | 70.43 | 68.40 |
| 8 | WKC | value+pullback | 62.03 | 62.72 | 47.36 | 66.52 | 74.41 | 69.78 | 68.85 |
| 9 | TV | value+pullback | 61.60 | 69.44 | 75.88 | 44.85 | 31.97 | 59.35 | 38.19 |
| 10 | MFA | value+pullback | 61.48 | 57.89 | 61.83 | 79.81 | 37.58 | 64.62 | 44.81 |
| 11 | ONIT | value+pullback | 59.74 | 70.05 | 68.82 | 58.76 | 45.15 | 40.94 | 43.64 |
| 12 | PKX | value+pullback | 59.19 | 60.09 | 58.78 | 52.98 | 68.14 | 58.51 | 53.04 |
| 13 | PBR | value+pullback | 58.62 | 65.45 | 61.88 | 49.57 | 63.12 | 48.85 | 56.40 |
| 14 | CHTR | value+pullback | 58.42 | 61.19 | 85.49 | 52.85 | 41.75 | 32.95 | 43.63 |
| 15 | CNC | value+pullback | 58.14 | 69.55 | 55.90 | 44.22 | 66.36 | 50.16 | 59.87 |
| 16 | CNXC | value+pullback | 56.68 | 83.22 | 60.46 | 43.28 | 31.70 | 34.70 | 36.73 |
| 17 | GL9.IR | pullback | 56.58 | 42.62 | 74.58 | 97.69 | 63.49 | 84.65 | 64.03 |
| 18 | BYD | value+pullback | 56.27 | 57.49 | 44.93 | 77.54 | 41.24 | 60.18 | 48.15 |
| 19 | LYFT | value+pullback | 56.10 | 60.59 | 68.46 | 55.07 | 46.30 | 39.60 | 56.55 |
| 20 | ORCL | value+pullback | 56.10 | 69.90 | 57.06 | 49.72 | 58.22 | 37.95 | 41.90 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 66.6 | 1 / 9 |
| Top 25 | 24/25 | 24/25 | 24/25 | 22/25 | 0/25 | 66.5 | 5 / 20 |
| Top 50 | 48/50 | 47/50 | 48/50 | 43/50 | 0/50 | 66.6 | 13 / 37 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=3, large_20_100b=3, mega_100b_plus=1
