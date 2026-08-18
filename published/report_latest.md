# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-18

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

- **EUROPE:** 89.3/100
- **OTHER:** 82.9/100
- **US:** 85.6/100

## Main multi-horizon ranking

|   rank | symbol   | name                               | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | AKER.OL  | Aker ASA                           | EUROPE   |                9.86 |             80.93 |         84.82 |         79.7  |          82.15 |        76.41 |           82.97 |             91.91 |             54.17 |         3.36 |             74.34 | short              |                2.44 |                  1.98 |                  nan |
|      2 | ECO      | Okeanis Eco Tankers Corp.          | OTHER    |                2.12 |             79.33 |         85.88 |         80.06 |          78.6  |        67.83 |           86.18 |             86.33 |             18.5  |         4.34 |             80.75 | short              |               -1.72 |                nan    |                  nan |
|      3 | AVAH     | Aveanna Healthcare Holdings Inc.   | US       |                2.39 |             79.27 |         85.8  |         83.7  |          74.84 |        71.62 |           70.32 |             72.25 |             66.33 |         6.85 |             86.02 | short              |               10.8  |                nan    |                  nan |
|      4 | CLMT     | Calumet, Inc.                      | US       |                3.67 |             78.35 |         82.13 |         80.42 |          76.27 |        67.16 |           74.81 |             76.52 |             39.56 |         5.14 |             81.5  | short              |                0.73 |                nan    |                  nan |
|      5 | PARR     | Par Pacific Holdings, Inc.         | US       |                3.55 |             77.52 |         77.26 |         77.85 |          77.77 |        73.19 |           74.32 |             69.04 |             65.99 |         6.47 |             85.6  | swing              |                1.48 |                 -0.65 |                  nan |
|      6 | PBF      | PBF Energy Inc.                    | US       |                7.69 |             77.38 |         84.44 |         82.12 |          72.64 |        60.27 |           45.05 |             78.63 |             55.18 |         6.59 |             85.47 | short              |               -0.88 |                 -3.06 |                  nan |
|      7 | LFST     | LifeStance Health Group, Inc.      | US       |                4.14 |             76.64 |         79.02 |         81.33 |          74.26 |        63.32 |           56.14 |             76.96 |             46.39 |         5.65 |             84.64 | swing              |                3.9  |                 -0.84 |                  nan |
|      8 | DINO     | HF Sinclair Corporation            | US       |               14.59 |             76.42 |         76.96 |         78.33 |          75.88 |        69.99 |           65.51 |             74.77 |             65.67 |         4.77 |             87.29 | swing              |                6.03 |                 -1.36 |                  nan |
|      9 | RNG      | RingCentral, Inc.                  | US       |                4.62 |             75.59 |         80.98 |         78.78 |          72.41 |        68.58 |           53.19 |             62.47 |             81.14 |         6.85 |             88.1  | short              |              nan    |                nan    |                  nan |
|     10 | OSCR     | Oscar Health, Inc.                 | US       |                8.41 |             75.4  |         73.04 |         78.28 |          77.76 |        72.14 |           58.69 |             76.15 |             79.87 |         8.37 |             85.21 | swing              |                8.4  |                  0.25 |                  nan |
|     11 | MU       | Micron Technology, Inc.            | US       |              987.27 |             75.25 |         75.14 |         75.37 |          79.98 |        74.76 |           84.82 |             67.63 |             50.47 |         7.77 |             88.9  | medium             |              nan    |                  0.28 |                  nan |
|     12 | SNDK     | Sandisk Corporation                | US       |              225.4  |             75.03 |         76.14 |         70.78 |          78.14 |        73.91 |           79.67 |             69.88 |             55.95 |         8.51 |             88.73 | medium             |               -0.73 |                  0.2  |                  nan |
|     13 | BAX      | BAX                                | US       |               11.57 |             74.73 |         73.77 |         81.43 |          75.58 |        73.88 |           79.92 |             94.15 |             62.97 |         5.8  |             63.95 | swing              |               -1.32 |                  0.49 |                  nan |
|     14 | HPE      | Hewlett Packard Enterprise Company | US       |               65.91 |             74.72 |         76.04 |         79.12 |          73.4  |        66.14 |           52.11 |             61.41 |             69.52 |         6.35 |             88.03 | swing              |               -5.32 |                 -2.1  |                  nan |
|     15 | DELL     | Dell Technologies Inc.             | US       |              267.87 |             74.46 |         76.39 |         79.03 |          72.53 |        62.48 |           58.99 |             57.1  |             46.93 |         7.4  |             86.78 | swing              |               -0.91 |                 -1.83 |                  nan |
|     16 | STX      | Seagate Technology Holdings plc    | OTHER    |              195.11 |             74.2  |         76.81 |         71.6  |          77.02 |        70.28 |           83.1  |             74.51 |             38.48 |         7.41 |             88.81 | medium             |               -2.34 |                  0.66 |                  nan |
|     17 | ANET     | Arista Networks, Inc.              | US       |              219.9  |             74.05 |         78.27 |         76.77 |          71.34 |        63.97 |           80.14 |             79.02 |             22.51 |         5.83 |             90.12 | short              |                7.84 |                  0.76 |                  nan |
|     18 | NOEJ.DE  | NOEJ.DE                            | EUROPE   |                0.59 |             73.98 |         77.88 |         75.43 |          72.54 |        66.89 |           95.98 |             87.56 |             20.57 |         4.36 |             61.25 | short              |              nan    |                nan    |                  nan |
|     19 | CHYM     | Chime Financial, Inc.              | US       |               10.29 |             73.85 |         84.04 |         81.33 |          66.38 |        58.05 |           51.11 |             79.25 |             49.96 |         7.71 |             87.56 | short              |                2.25 |                 -0.41 |                  nan |
|     20 | GH       | GH                                 | US       |               18.75 |             73.43 |         61.75 |         76.89 |          76.21 |        70.64 |           60.74 |             75.29 |            nan    |         6.74 |             60.66 | swing              |               -0.69 |                nan    |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                         | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BMY      | Bristol-Myers Squibb Company | US       |              114.07 |                  86.99 |                    82.23 |                 80.13 |              82.76 |                77.07 |                   22.93 |           80.15 |             62.59 |       0.061 |         nan |       nan |        8.77 |         9.86 |         14.05 |        2.26 |                 nan |              nan |                  12 |                  0.63 |
|            2 | INVA     | Innoviva, Inc.               | US       |                1.31 |                  88    |                    78.83 |                 78.09 |              80.69 |                78.91 |                   21.09 |           87.87 |             31.27 |       0.073 |         nan |       nan |        6.48 |         9.48 |          4.92 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|            3 | DTG.DE   | Daimler Truck Holding AG     | EUROPE   |               34.93 |                  84.3  |                    76.23 |                 73.67 |              80.85 |                78.23 |                   21.77 |           59.57 |             60.69 |       0.155 |         nan |       nan |       14.34 |         9.67 |         31.47 |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|            4 | AKER.OL  | Aker ASA                     | EUROPE   |                9.86 |                  72.26 |                    75.62 |                 77.5  |              73.76 |                69.7  |                   30.3  |           82.97 |             91.91 |       0.112 |         nan |       nan |        5.36 |        55.54 |          3.83 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            5 | HRB      | H&R Block, Inc.              | US       |                5.34 |                  79.98 |                    75.59 |                 75.18 |              77.79 |                75    |                   25    |           71.51 |             67.06 |       0.101 |         nan |       nan |        7.11 |         7.26 |          9.48 |        0.68 |                 nan |              nan |                  12 |                  0.63 |
|            6 | SNDK     | Sandisk Corporation          | US       |              225.4  |                  75.79 |                    75.31 |                 75.17 |              74.35 |                71.1  |                   28.9  |           79.67 |             69.88 |       0.03  |         nan |       nan |       20.72 |         6.76 |         22.27 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | NTGY.MC  | Naturgy Energy Group, S.A.   | EUROPE   |               26.77 |                  82.49 |                    74.73 |                 72.17 |              77.21 |                76.34 |                   23.66 |           69.93 |             40.74 |       0.066 |         nan |       nan |        8.13 |        13.83 |         13.32 |        6.98 |                 nan |              nan |                  11 |                  0.58 |
|            8 | BHC      | Bausch Health Companies Inc. | OTHER    |                2.13 |                  82.77 |                    74.42 |                 73.67 |              74.43 |                60.1  |                   39.9  |           85.56 |             40.17 |       0.583 |         nan |       nan |        5.72 |         1.57 |        nan    |        0.01 |                 nan |              nan |                  10 |                  0.53 |
|            9 | GEN      | Gen Digital Inc.             | US       |               14.18 |                  86.57 |                    73.96 |                 70.84 |              76.49 |                48.05 |                   51.95 |           65.67 |             55.06 |       0.094 |         nan |       nan |        9.98 |         8.3  |         16.71 |        1.43 |                 nan |              nan |                  12 |                  0.63 |
|           10 | ADBE     | Adobe Inc.                   | US       |               87.25 |                  84.12 |                    73.92 |                 69.7  |              75.25 |                54.59 |                   45.41 |           65.49 |             48.58 |       0.091 |         nan |       nan |       10.53 |         9.24 |         15.1  |        0.64 |                 nan |              nan |                  11 |                  0.58 |
|           11 | FE       | FirstEnergy Corp.            | US       |               23.7  |                  78.34 |                    73.92 |                 72.34 |              73.91 |                68.71 |                   31.29 |           76.3  |             51.36 |      -0.073 |         nan |       nan |       10.67 |        16.08 |         25.36 |        1.68 |                 nan |              nan |                  12 |                  0.63 |
|           12 | GPN      | Global Payments Inc.         | US       |               20.66 |                  86.25 |                    73.1  |                 67.56 |              75.66 |                55.47 |                   44.53 |           60.27 |             35.7  |       0.329 |         nan |       nan |        9.58 |         5.68 |         44.09 |        0.27 |                 nan |              nan |                  12 |                  0.63 |
|           13 | ADT      | ADT Inc.                     | US       |                4.53 |                  84.6  |                    72.95 |                 70.46 |              76.27 |                56    |                   44    |           64.28 |             52.78 |       0.228 |         nan |       nan |        4.8  |         7.25 |         10.41 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|           14 | CNC      | Centene Corporation          | US       |               27.49 |                  90.49 |                    72.95 |                 67    |              79.16 |                41.06 |                   58.94 |           40.77 |             66.19 |       0.303 |         nan |       nan |        4.55 |        12.12 |        nan    |        0.92 |                 nan |              nan |                  10 |                  0.53 |
|           15 | OSCR     | Oscar Health, Inc.           | US       |                8.41 |                  84.58 |                    72.77 |                 71.43 |              77.24 |                48.5  |                   51.5  |           58.69 |             76.15 |       0.071 |         nan |       nan |        2.52 |        16.76 |         25.24 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           16 | FSLR     | First Solar, Inc.            | US       |               20.23 |                  85.79 |                    72.18 |                 66.65 |              75.34 |                57.82 |                   42.18 |           58.52 |             31.63 |       0.068 |         nan |       nan |        9.17 |         9.44 |         23.05 |        0.61 |                 nan |              nan |                  11 |                  0.58 |
|           17 | GM       | General Motors Company       | US       |               65.93 |                  85.35 |                    71.69 |                 65.71 |              77.52 |                58.86 |                   41.14 |           41.07 |             54.7  |       0.287 |         nan |       nan |       10.92 |         5.74 |         38.7  |        0.34 |                 nan |              nan |                  12 |                  0.63 |
|           18 | SM       | SM Energy Company            | US       |                7.29 |                  77.76 |                    71.65 |                 70.2  |              70.86 |                58.91 |                   41.09 |           79.81 |             42.77 |       0.174 |         nan |       nan |        4.76 |         4.83 |          5.98 |        0.6  |                 nan |              nan |                  12 |                  0.63 |
|           19 | ALL-PH   | The Allstate Corporation     | US       |               24.5  |                  82.39 |                    71.64 |                 68.35 |              73.47 |                61.05 |                   38.95 |           69.52 |             31.57 |       0.535 |         nan |       nan |        0.5  |       nan    |          3.34 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           20 | STNE     | StoneCo Ltd.                 | OTHER    |                1.85 |                  85.75 |                    71.34 |                 67.19 |              74.89 |                56.41 |                   43.59 |           62.6  |             29.92 |       0.672 |         nan |       nan |        1.54 |         3.97 |          3.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BMY      | Bristol-Myers Squibb Company                           | US       |              114.07 |                  86.99 |                    82.23 |                 80.13 |              82.76 |                77.07 |                   22.93 |           80.15 |             62.59 |       0.061 |         nan |       nan |        8.77 |         9.86 |         14.05 |        2.26 |                 nan |              nan |                  12 |                  0.63 |
|            2 | INVA     | Innoviva, Inc.                                         | US       |                1.31 |                  88    |                    78.83 |                 78.09 |              80.69 |                78.91 |                   21.09 |           87.87 |             31.27 |       0.073 |         nan |       nan |        6.48 |         9.48 |          4.92 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|            4 | AKER.OL  | Aker ASA                                               | EUROPE   |                9.86 |                  72.26 |                    75.62 |                 77.5  |              73.76 |                69.7  |                   30.3  |           82.97 |             91.91 |       0.112 |         nan |       nan |        5.36 |        55.54 |          3.83 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            5 | HRB      | H&R Block, Inc.                                        | US       |                5.34 |                  79.98 |                    75.59 |                 75.18 |              77.79 |                75    |                   25    |           71.51 |             67.06 |       0.101 |         nan |       nan |        7.11 |         7.26 |          9.48 |        0.68 |                 nan |              nan |                  12 |                  0.63 |
|            6 | SNDK     | Sandisk Corporation                                    | US       |              225.4  |                  75.79 |                    75.31 |                 75.17 |              74.35 |                71.1  |                   28.9  |           79.67 |             69.88 |       0.03  |         nan |       nan |       20.72 |         6.76 |         22.27 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | BHC      | Bausch Health Companies Inc.                           | OTHER    |                2.13 |                  82.77 |                    74.42 |                 73.67 |              74.43 |                60.1  |                   39.9  |           85.56 |             40.17 |       0.583 |         nan |       nan |        5.72 |         1.57 |        nan    |        0.01 |                 nan |              nan |                  10 |                  0.53 |
|            3 | DTG.DE   | Daimler Truck Holding AG                               | EUROPE   |               34.93 |                  84.3  |                    76.23 |                 73.67 |              80.85 |                78.23 |                   21.77 |           59.57 |             60.69 |       0.155 |         nan |       nan |       14.34 |         9.67 |         31.47 |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|           11 | FE       | FirstEnergy Corp.                                      | US       |               23.7  |                  78.34 |                    73.92 |                 72.34 |              73.91 |                68.71 |                   31.29 |           76.3  |             51.36 |      -0.073 |         nan |       nan |       10.67 |        16.08 |         25.36 |        1.68 |                 nan |              nan |                  12 |                  0.63 |
|            7 | NTGY.MC  | Naturgy Energy Group, S.A.                             | EUROPE   |               26.77 |                  82.49 |                    74.73 |                 72.17 |              77.21 |                76.34 |                   23.66 |           69.93 |             40.74 |       0.066 |         nan |       nan |        8.13 |        13.83 |         13.32 |        6.98 |                 nan |              nan |                  11 |                  0.58 |
|           15 | OSCR     | Oscar Health, Inc.                                     | US       |                8.41 |                  84.58 |                    72.77 |                 71.43 |              77.24 |                48.5  |                   51.5  |           58.69 |             76.15 |       0.071 |         nan |       nan |        2.52 |        16.76 |         25.24 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | GEN      | Gen Digital Inc.                                       | US       |               14.18 |                  86.57 |                    73.96 |                 70.84 |              76.49 |                48.05 |                   51.95 |           65.67 |             55.06 |       0.094 |         nan |       nan |        9.98 |         8.3  |         16.71 |        1.43 |                 nan |              nan |                  12 |                  0.63 |
|          nan | AOD      | Abrdn Total Dynamic Dividend Fund                      | OTHER    |                0.98 |                  50.16 |                    65.92 |                 70.64 |              61.08 |                88.02 |                   11.98 |           84.7  |             91.23 |     nan     |         nan |       nan |      nan    |       nan    |          4.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | ADT      | ADT Inc.                                               | US       |                4.53 |                  84.6  |                    72.95 |                 70.46 |              76.27 |                56    |                   44    |           64.28 |             52.78 |       0.228 |         nan |       nan |        4.8  |         7.25 |         10.41 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|           18 | SM       | SM Energy Company                                      | US       |                7.29 |                  77.76 |                    71.65 |                 70.2  |              70.86 |                58.91 |                   41.09 |           79.81 |             42.77 |       0.174 |         nan |       nan |        4.76 |         4.83 |          5.98 |        0.6  |                 nan |              nan |                  12 |                  0.63 |
|          nan | PAH3.DE  | PAH3.DE                                                | EUROPE   |                8.38 |                  62.03 |                    68.2  |                 70.12 |              67.5  |                79.82 |                   20.18 |          nan    |             84.66 |     nan     |         nan |       nan |      nan    |         1.85 |         88.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           43 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.6  |                  60.18 |                    67.73 |                 69.76 |              66.64 |                78.63 |                   21.37 |           68.6  |             91.57 |       0.027 |         nan |       nan |      nan    |       nan    |          3.8  |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           10 | ADBE     | Adobe Inc.                                             | US       |               87.25 |                  84.12 |                    73.92 |                 69.7  |              75.25 |                54.59 |                   45.41 |           65.49 |             48.58 |       0.091 |         nan |       nan |       10.53 |         9.24 |         15.1  |        0.64 |                 nan |              nan |                  11 |                  0.58 |
|           44 | ORA.PA   | Orange S.A.                                            | EUROPE   |               43.04 |                  67.06 |                    67.71 |                 69.69 |              66.89 |                66.48 |                   33.52 |           78.31 |             66.41 |       0.149 |         nan |       nan |        7.57 |        13.83 |         10.94 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|           36 | MATV     | Mativ Holdings, Inc.                                   | US       |                0.58 |                  68.74 |                    68.07 |                 69.67 |              66.92 |                71.35 |                   28.65 |           84.63 |             45.85 |       0.271 |         nan |       nan |        7.54 |         9.78 |          7.46 |        3.77 |                 nan |              nan |                  12 |                  0.63 |
|           46 | TAL      | TAL Education Group                                    | OTHER    |                5.6  |                  61.09 |                    67.09 |                 69.18 |              64.59 |                82.54 |                   17.46 |           82.73 |             57.47 |       0.065 |         nan |       nan |        8.29 |         9.97 |          7.3  |        2.71 |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                         | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-----------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX                          | US       |               11.57 |                     0.08 |    -0.06 |      0.18 |                  72.03 |                        81.63 |         73.77 |         81.43 |          75.58 |        73.88 |           79.92 |             94.15 |         5.8  |
|               2 | PLTR     | Palantir Technologies Inc.   | US       |              358.26 |                     0.04 |    -0.02 |      0.27 |                  69.04 |                        79.6  |         79.31 |         71.91 |          64.5  |        59.46 |           90.47 |             76.64 |         7.7  |
|               3 | FIGS     | FIGS, Inc.                   | US       |                2.06 |                     0.04 |    -0.01 |      0.38 |                  67.33 |                        75.67 |         74.05 |         66    |          68.65 |        63.25 |           83.95 |             78.37 |         7.53 |
|               4 | GH       | GH                           | US       |               18.75 |                     0.05 |    -0.04 |      0.08 |                  77.81 |                        73.56 |         61.75 |         76.89 |          76.21 |        70.64 |           60.74 |             75.29 |         6.74 |
|               5 | ABNB     | Airbnb, Inc.                 | US       |               92.76 |                     0.03 |    -0.03 |      0.24 |                  64.71 |                        72.86 |         74.76 |         71.02 |          65.42 |        58.76 |           80.83 |             64.05 |         5.11 |
|               6 | CHYM     | Chime Financial, Inc.        | US       |               10.29 |                     0.04 |     0.01 |      0.41 |                  57.21 |                        72.71 |         84.04 |         81.33 |          66.38 |        58.05 |           51.11 |             79.25 |         7.71 |
|               7 | DSFIR.AS | DSFIR.AS                     | EUROPE   |               21.57 |                     0.07 |    -0.07 |      0.02 |                  81.02 |                        72.7  |         50.09 |         67.21 |          65.51 |        56.02 |           77.7  |             76    |         5.52 |
|               8 | GLBE     | Global-E Online Ltd.         | OTHER    |                5.98 |                     0.03 |     0    |      0.13 |                  53.82 |                        71.6  |         70.72 |         68.17 |          65.13 |        62.57 |           90.9  |             66.63 |         5.21 |
|               9 | OKTA     | OKTA                         | US       |               21.7  |                     0.08 |    -0.05 |     -0.03 |                  72.81 |                        71.51 |         47.89 |         72.96 |          70.39 |        57.74 |           62.91 |             76.83 |         7.46 |
|              10 | DXCM     | DexCom, Inc.                 | US       |               28.94 |                     0.03 |     0.01 |      0.17 |                  55.13 |                        71.23 |         77.16 |         72.35 |          64.56 |        63.71 |           80.31 |             55.43 |         5.85 |
|              11 | RNG      | RingCentral, Inc.            | US       |                4.62 |                     0.05 |     0    |      0.58 |                  69.41 |                        70.91 |         80.98 |         78.78 |          72.41 |        68.58 |           53.19 |             62.47 |         6.85 |
|              12 | SHOP     | Shopify Inc.                 | OTHER    |              165.25 |                     0.06 |    -0.04 |      0.19 |                  78.65 |                        70.85 |         72.48 |         68.74 |          58.18 |        51.31 |           63.93 |             66.85 |         7.18 |
|              13 | BMRN     | BioMarin Pharmaceutical Inc. | US       |               11.15 |                     0.05 |    -0.03 |      0.13 |                  75    |                        70.53 |         72.37 |         70.52 |          62.25 |        60.13 |           52.71 |             83.73 |         4.11 |
|              14 | OMDA     | Omada Health, Inc.           | US       |                1.26 |                     0.05 |    -0.05 |     -0.01 |                  81.98 |                        70.3  |         61.04 |         72.61 |          65.1  |        53.04 |           54.71 |             71.73 |         7.99 |
|              15 | CRWD     | CRWD                         | US       |              188.19 |                     0.05 |    -0.05 |      0.08 |                  84.51 |                        69.8  |         60.84 |         74.64 |          64.44 |        42.74 |           35.05 |             85.31 |         6.69 |
|              16 | TAL      | TAL Education Group          | OTHER    |                5.6  |                     0.07 |    -0.07 |      0.13 |                  83.4  |                        69.78 |         64.2  |         54.51 |          56.62 |        64.89 |           82.73 |             57.47 |         5.47 |
|              17 | CAI      | Caris Life Sciences, Inc.    | US       |                5.28 |                     0.08 |    -0.08 |      0.38 |                  78.97 |                        69.2  |         69.83 |         62.38 |          51.92 |        52.3  |           65.44 |             62.36 |         8.8  |
|              18 | PGEN     | Precigen, Inc.               | US       |                2.02 |                     0.08 |    -0.05 |      0.31 |                  68.48 |                        69.08 |         71.61 |         72.5  |          66.63 |        56.29 |           56.94 |             74.5  |         7.85 |
|              19 | CTSH     | CTSH                         | US       |               23.14 |                     0.04 |    -0.03 |      0.27 |                  71.57 |                        69.06 |         67.24 |         56.53 |          56.31 |        71.04 |           82.5  |             54.68 |         7.71 |
|              20 | NET      | Cloudflare, Inc.             | US       |               94.45 |                     0.07 |    -0.01 |      0.13 |                  64.57 |                        69.03 |         73.31 |         75.09 |          64.96 |        49.61 |           52.99 |             74.71 |         6.45 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | CRDO     | Credo Technology Group Holding Ltd  | OTHER    |               45.57 |             76.46 |         79.99 |         77.85 |          75.08 |        65.94 |           90.04 |             62.03 |             18.85 |         8.18 |             88.37 | short              |               -3.13 |                  0.39 |                  nan |
|    nan | RBRK     | Rubrik, Inc.                        | US       |               17.97 |             69.12 |         79.72 |         77.51 |          60.73 |        48.2  |           51.6  |             61.43 |             21.76 |         7.8  |             84.58 | short              |               -4.64 |                 -0.43 |                  nan |
|    nan | CMBT.BR  | Cmb.Tech NV                         | EUROPE   |                4.38 |             67.31 |         70.49 |         65.38 |          69.23 |        62.79 |           72.72 |             75.86 |             35.4  |         3.23 |             82.33 | short              |              nan    |                 -0.63 |                  nan |
|    nan | NAT      | Nordic American Tankers Limited     | OTHER    |                1.25 |             66.1  |         66.37 |         69.21 |          65.82 |        52.44 |           60.63 |             70.11 |              9.36 |         4.83 |             82.85 | swing              |              nan    |                 -1.21 |                  nan |
|    nan | MRVL     | Marvell Technology, Inc.            | US       |              181.72 |             65.93 |         66.13 |         65.74 |          66.64 |        53.38 |           56.36 |             58.88 |             19.99 |         7.98 |             89.59 | medium             |                4.6  |                 -0.01 |                  nan |
|    nan | P        | Everpure, Inc.                      | US       |               33.6  |             65.17 |         76.98 |         72.65 |          57.7  |        46.74 |           49.04 |             55.93 |             17.61 |         7.27 |             88.66 | short              |              nan    |                 -1.04 |                  nan |
|    nan | PANW     | Palo Alto Networks, Inc.            | US       |              264.6  |             65.13 |         63.72 |         72.69 |          66.53 |        52.29 |           59.42 |             53.3  |             13.59 |         5.9  |             89.43 | swing              |               -2.5  |                 -2.45 |                  nan |
|    nan | VEEV     | Veeva Systems Inc.                  | US       |               33.45 |             65.06 |         71.64 |         69.37 |          60.75 |        60.31 |           79.89 |             47.15 |             42    |         5.85 |             89.74 | short              |              nan    |                nan    |                  nan |
|    nan | KIN.BR   | Kinepolis Group NV                  | EUROPE   |                1.1  |             64.51 |         67.75 |         71.89 |          61.28 |        49.49 |           49.84 |             58.43 |             27.16 |         8.5  |             84.4  | swing              |               -3.2  |                 -0.58 |                  nan |
|    nan | HMY      | Harmony Gold Mining Company Limited | OTHER    |               10.93 |             64.18 |         70.58 |         58.88 |          56.8  |        69.49 |           71.53 |             46.14 |             88.84 |         5.79 |             83.49 | short              |              nan    |                nan    |                  nan |
|    nan | WDAY     | Workday, Inc.                       | US       |               40.8  |             63.61 |         76.94 |         68.11 |          57.86 |        59.11 |           64.58 |             47.78 |             59.88 |         7.58 |             89.8  | short              |               -6.36 |                 -1    |                  nan |
|    nan | ESTC     | Elastic N.V.                        | OTHER    |                7.55 |             62.7  |         76.58 |         69.43 |          55.97 |        53.03 |           49.87 |             50.49 |             56.61 |         6.71 |             87.09 | short              |               12.57 |                 -1.17 |                  nan |
|    nan | RNW      | ReNew Energy Global Plc             | OTHER    |                2.15 |             62.33 |         74.9  |         66.51 |          58.15 |        57.03 |           48.98 |             58.91 |             69.12 |         8.5  |             83.2  | short              |              -14.3  |                 -1.32 |                  nan |
|    nan | NVDA     | NVIDIA Corporation                  | US       |             4708.83 |             60.96 |         68.14 |         56.87 |          60.43 |        61.49 |           84.64 |             54.28 |             31.74 |         5.17 |             89.53 | short              |               -2.14 |                  1.87 |                  nan |
|    nan | PD       | PagerDuty, Inc.                     | US       |                0.77 |             60.6  |         64.6  |         68.33 |          56.6  |        55.15 |           43.84 |             42.5  |             78.47 |         8    |             86.86 | swing              |               11.58 |                 -0.91 |                  nan |
|    nan | S        | SentinelOne, Inc.                   | US       |                6.44 |             58.14 |         63.16 |         63.59 |          53.11 |        43.69 |           33.56 |             43.16 |             40.1  |         6.36 |             83.85 | swing              |               -8.56 |                 -2.95 |                  nan |
|    nan | TGT      | Target Corporation                  | US       |               59.26 |             58.08 |         58.93 |         59.98 |          57.24 |        52.02 |           47.5  |             53.7  |             49.6  |         8.5  |             89.56 | swing              |              nan    |                 -3.02 |                  nan |
|    nan | VIG.VI   | Vienna Insurance Group AG           | EUROPE   |                8.87 |             57.9  |         56.85 |         53.98 |          58.96 |        63.55 |           59.52 |             47.31 |             71.85 |         2.35 |             78.49 | long               |                9.37 |                 -0.68 |                  nan |
|    nan | AEG      | Aegon Ltd.                          | OTHER    |               12.06 |             57.86 |         61.78 |         62.8  |          53.94 |        43.63 |           22.32 |             67.25 |             47.24 |         8.5  |             74.51 | swing              |                0.4  |                 -2.19 |                  nan |
|    nan | VIK      | Viking Holdings Ltd                 | OTHER    |               38.49 |             57.78 |         50.58 |         57.92 |          63.22 |        57.65 |           78.98 |             58.34 |             24.05 |         8.5  |             87.86 | medium             |                1.08 |                 -1.83 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    266 | TXN      | Texas Instruments Incorporated | US       |              223.23 |             57.26 |         52.72 |         53.84 |          65.2  |        60.68 |           67.62 |             77.75 |             32.91 |         5.63 |             89.85 | medium             |              nan    |                  3.67 |                  nan |
|    301 | RGNX     | REGENXBIO Inc.                 | US       |                0.65 |             56.02 |         65.5  |         61.39 |          50.66 |        42.56 |           47.98 |             31.7  |             20.75 |         8.59 |             78.24 | short              |               -0.8  |                  3.24 |                  nan |
|    428 | INSM     | Insmed Incorporated            | US       |               24.21 |             50.12 |         65.68 |         55.37 |          44.88 |        40.37 |           37.35 |             77.38 |             20.79 |         7.86 |             81.48 | short              |               -0.01 |                  3.18 |                  nan |
|    467 | NFLX     | Netflix, Inc.                  | US       |              273.5  |             47.48 |         57.4  |         38.65 |          43.5  |        51.46 |           73.4  |             42.94 |             41.27 |         5.48 |             90.62 | short              |                1.15 |                  2.84 |                  nan |
|    170 | AMD      | Advanced Micro Devices, Inc.   | US       |              713.7  |             61.36 |         55.39 |         63.01 |          70.6  |        59.71 |           70.62 |             69.65 |             20.12 |         6.97 |             89.9  | medium             |                0.72 |                  2.55 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    511 | CRBG     | Corebridge Financial, Inc. | US       |               12.78 |             45.14 |         52.65 |         49.2  |          40.63 |        41.09 |           28.13 |             35.01 |             61.86 |         4.8  |             82.36 | short              |              -14.83 |                 -5.79 |                  nan |
|    225 | ABCL     | AbCellera Biologics Inc.   | OTHER    |                2.97 |             58.93 |         69.7  |         65.75 |          52.11 |        41.13 |           25.77 |             37.15 |             41.21 |         8.24 |             79.65 | short              |                3.79 |                 -4.98 |                  nan |
|    550 | SDGR     | SDGR                       | US       |                1.12 |             42.89 |         51.94 |         49.86 |          35.93 |        31.16 |           20.56 |              3.86 |             46.94 |         7.35 |             61.57 | short              |               -2.76 |                 -4.95 |                  nan |
|    393 | ABSI     | ABSI                       | US       |                1.37 |             52.24 |         57.05 |         57.17 |          47.43 |        31.75 |            8.13 |             18.9  |             32.65 |         9.02 |             59.2  | swing              |               -0.42 |                 -4.93 |                  nan |
|    570 | IDIA.SW  | Idorsia Ltd                | EUROPE   |                1.66 |             41.5  |         34.13 |         49.09 |          47.99 |        35.02 |           27.92 |             36.92 |             14.36 |         6.76 |             81.25 | swing              |              -13.18 |                 -4.85 |                  nan |

## Duplicate-security checks

- SHELL.AS duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- KRX.IR duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- LYG duplicates LLOYL.XC (security_id=ISIN:GB00B3KSB568)
- GL9.IR duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- RYA.IR duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)
- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- IR5B.IR duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.93
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
- Excluded by hard/data filters: **294**
- Event watch (otherwise eligible): **52**
- Final eligible: **654**
- Eligible change vs previous stored run: **-56**

Top exclusion categories:
- liquidity: 231
- price: 174
- market_cap: 124
- price_history: 21
- data_confidence: 14
- duplicate_listing: 9
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AKER.OL | 1 | 4 |  | 3 | 2 | main,value,quality_value |
| OSCR | 10 | 15 |  | 10 | 1 | main,quality_value |
| SNDK | 12 | 6 |  | 5 | 1 | value,quality_value |
| HRB | 35 | 5 |  | 4 | 1 | value,quality_value |
| BMY | 100 | 1 | 35 | 1 | 1 | value,quality_value |
| BHC | 104 | 8 |  | 6 | 1 | value,quality_value |
| DTG.DE | 197 | 3 | 79 | 7 | 1 | value,quality_value |
| NTGY.MC | 334 | 7 | 168 | 9 | 1 | value,quality_value |
| INVA | 445 | 2 | 195 | 2 | 1 | value,quality_value |
| ECO | 2 | 226 |  | 85 | 1 | main |
| AVAH | 3 | 51 |  | 34 | 1 | main |
| CLMT | 4 | 246 |  | 122 | 1 | main |
| PARR | 5 | 84 |  | 43 | 1 | main |
| PBF | 6 | 375 |  | 348 | 1 | main |
| LFST | 7 | 206 |  | 154 | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **0** (none)
- Adaptive in Value Top 10: **5** (DTG.DE, SNDK, NTGY.MC, BHC, ADBE)
- Adaptive in Quality Value Top 10: **5** (SNDK, BHC, DTG.DE, FE, NTGY.MC)
- Adaptive in Pullback Top 10: **2** (FIGS, GLBE)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | TAL | value+pullback | 73.84 | 61.09 | 83.40 | 82.73 | 57.47 | 82.54 | 60.41 |
| 2 | BMY | value+pullback | 72.95 | 86.99 | 52.62 | 80.15 | 62.59 | 77.07 | 65.38 |
| 3 | INVA | value+pullback | 72.73 | 88.00 | 56.96 | 87.87 | 31.27 | 78.91 | 49.00 |
| 4 | CRI | value+pullback | 72.31 | 78.34 | 84.13 | 76.27 | 28.65 | 67.38 | 48.83 |
| 5 | DTG.DE | value+pullback | 72.14 | 84.30 | 64.79 | 59.57 | 60.69 | 78.23 | 60.13 |
| 6 | MOMO | value+pullback | 71.55 | 75.91 | 77.03 | 65.65 | 50.89 | 72.93 | 43.51 |
| 7 | ADBE | value+pullback | 71.36 | 84.12 | 82.11 | 65.49 | 48.58 | 54.59 | 50.87 |
| 8 | GEN | value+pullback | 70.86 | 86.57 | 79.71 | 65.67 | 55.06 | 48.05 | 59.84 |
| 9 | MONC.MI | value+pullback | 68.91 | 55.64 | 76.60 | 83.65 | 41.12 | 82.07 | 41.71 |
| 10 | FE | value+pullback | 68.29 | 78.34 | 57.84 | 76.30 | 51.36 | 68.71 | 50.08 |
| 11 | DG.PA | value+pullback | 68.28 | 80.70 | 79.80 | 54.99 | 38.86 | 59.93 | 43.62 |
| 12 | GM | value+pullback | 68.14 | 85.35 | 76.52 | 41.07 | 54.70 | 58.86 | 52.57 |
| 13 | MATV | value+pullback | 67.76 | 68.74 | 62.35 | 84.63 | 45.85 | 71.35 | 66.79 |
| 14 | ALL | value+pullback | 67.66 | 62.61 | 76.28 | 69.52 | 61.99 | 65.90 | 59.65 |
| 15 | NTGY.MC | value+pullback | 67.53 | 82.49 | 51.82 | 69.93 | 40.74 | 76.34 | 54.63 |
| 16 | ADT | value+pullback | 67.38 | 84.60 | 63.50 | 64.28 | 52.78 | 56.00 | 49.32 |
| 17 | ORA.PA | value+pullback | 67.16 | 67.06 | 61.44 | 78.31 | 66.41 | 66.48 | 53.71 |
| 18 | 0P6O.IL | value+pullback | 66.93 | 73.71 | 74.67 | 56.44 |  | 63.41 | 35.47 |
| 19 | DAL | value+pullback | 66.78 | 81.36 | 73.53 | 54.68 | 72.17 | 42.86 | 62.74 |
| 20 | INFY | value+pullback | 66.45 | 79.97 | 83.22 | 55.19 | 28.76 | 52.50 | 41.67 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 85.3 | 10 / 0 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 85.6 | 23 / 2 |
| Top 50 | 50/50 | 50/50 | 49/50 | 49/50 | 0/50 | 85.2 | 42 / 8 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=4
