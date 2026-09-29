# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-29

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

- **EUROPE:** 78.3/100
- **OTHER:** 66.5/100
- **US:** 77.7/100

## Main multi-horizon ranking

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE      | HPE      | US       |               73.07 |             84.82 |         90.25 |         87.81 |          81.84 |        71.93 |           74.42 |             82.15 |             45.23 |         6.95 |             72.34 | short              |                3.46 |                  1    |               nan    |
|      2 | VLO      | VLO      | US       |               98.58 |             84.43 |         84.67 |         86.66 |          84.2  |        78.92 |           86.42 |             81.72 |             53.98 |         3.65 |             69.68 | swing              |               -1.31 |                  1.43 |                 1.24 |
|      3 | AMC      | AMC      | US       |                2.58 |             84.14 |         87.66 |         91.71 |          80.62 |        79.29 |           82.69 |             78.44 |            nan    |         9.51 |             65.07 | swing              |                7.95 |                  5.05 |                 4.56 |
|      4 | FRO      | FRO      | US       |                9.41 |             82.26 |         82.9  |         83.07 |          81.62 |        78.58 |           91.27 |             65.51 |             54.16 |         5.19 |             73.14 | swing              |               -2.65 |                  0.58 |                 0.52 |
|      5 | MU       | MU       | US       |             1046.19 |             81.18 |         78.2  |         72.63 |          85.79 |        84.16 |           94.59 |             83.57 |             66.66 |         8.16 |             73.14 | medium             |                0.41 |                  2.45 |                 1.9  |
|      6 | DHT      | DHT      | US       |                3.1  |             80.07 |         81.76 |         81.02 |          79.12 |        78.34 |           88.4  |             69.86 |             56.96 |         4.55 |             73.14 | short              |               -2    |                  0.73 |                 0.44 |
|      7 | DELL     | DELL     | US       |              303.67 |             79.08 |         80.04 |         82.25 |          78.11 |        66.49 |           72.88 |             73.33 |             31.45 |         7.82 |             72.23 | swing              |               -4.54 |                 -0.63 |                -0.63 |
|      8 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.87 |             78.99 |         72.2  |         77.65 |          81.24 |        80.34 |           96.13 |             69.96 |             63.78 |         3.77 |             73.14 | medium             |               -5.19 |                  0.56 |                 0.68 |
|      9 | PSX      | PSX      | US       |               89.35 |             78.97 |         75.37 |         83.75 |          81.15 |        76.8  |           79.6  |             83.93 |             56.48 |         3.89 |             73.14 | swing              |               -4.89 |                  0.78 |                 0.92 |
|     10 | SMTC     | SMTC     | US       |               14.34 |             77.73 |         85.27 |         79.27 |          76.18 |        62.26 |           74.43 |             85.21 |             11.38 |         8.5  |             73.14 | short              |                6.89 |                  0.51 |               nan    |
|     11 | BP       | BP       | US       |              100.57 |             77.45 |         81.71 |         75.81 |          73.56 |        79.09 |           87.95 |             91.35 |             62.18 |         4.53 |             72.34 | short              |               15.22 |                  4.26 |               nan    |
|     12 | AMD      | AMD      | US       |              872.15 |             77.43 |         82.35 |         78.86 |          76.01 |        62.61 |           80.29 |             74.06 |              8.76 |         7.2  |             69.09 | short              |                5.32 |                  2.01 |                 0.87 |
|     13 | PBF      | PBF      | US       |                7.75 |             77.36 |         79.02 |         80.71 |          75.7  |        71.93 |           50.81 |             74.78 |             83.96 |         7.63 |             72.68 | swing              |               -1.23 |                  0.9  |                 0.8  |
|     14 | WT       | WT       | US       |                3.2  |             77.22 |         76.5  |         83.03 |          77.93 |        66.15 |           72.16 |             83.83 |             28.84 |         5.83 |             73.14 | swing              |                3.27 |                  2.77 |                 2.44 |
|     15 | SHEL     | SHEL     | US       |              241.8  |             76.78 |         82.43 |         78.04 |          72.19 |        75.53 |           74.51 |             84.47 |             69.81 |         3.04 |             72.8  | short              |               11.68 |                  3.46 |                 2.71 |
|     16 | SHELL.AS | SHELL.AS | EUROPE   |              241.21 |             76.73 |         79.54 |         74.84 |          73.44 |        78.63 |           93.37 |             80.7  |             65.3  |         2.49 |             73.14 | short              |                2.58 |                  2.53 |                 2.42 |
|     17 | TRMD     | TRMD     | US       |                3.2  |             76.65 |         78.73 |         75.83 |          74.3  |        77.47 |           82.69 |             42.88 |             76.6  |         5.64 |             73.14 | short              |              nan    |                nan    |               nan    |
|     18 | REP.MC   | REP.MC   | EUROPE   |               32.38 |             76.37 |         79.76 |         78.62 |          74.12 |        69.93 |           59.87 |             84.42 |             71.46 |         4.01 |             73.14 | short              |                1.71 |                  1.43 |                 1.16 |
|     19 | KIN.BR   | KIN.BR   | EUROPE   |                1.35 |             76.2  |         76.25 |         80.57 |          76.15 |        66.34 |           89.6  |             75.91 |             21.13 |         3.7  |             73.14 | swing              |               -1.55 |                 -0.5  |                -0.38 |
|     20 | TWLO     | TWLO     | US       |               38.74 |             76.04 |         86.32 |         79.6  |          72.48 |        60.47 |           77.61 |             56.23 |             11.71 |         6.9  |             72.34 | short              |                4.8  |                nan    |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.22 |                  92.17 |                    81.43 |                 79.92 |              87.24 |                71.33 |                   28.67 |           62.77 |             80.3  |       0.142 |         nan |       nan |        1.78 |         4.64 |          4.71 |        5.3  |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              241.21 |                  62.18 |                    73.06 |                 76.56 |              68.6  |                87.52 |                   12.48 |           93.37 |             80.7  |     nan     |         nan |       nan |      nan    |         9.64 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              100.57 |                  61.9  |                    72.63 |                 76.17 |              68.86 |                84.18 |                   15.82 |           87.95 |             91.35 |     nan     |         nan |       nan |      nan    |         8.6  |         21.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              241.8  |                  67.17 |                    71.9  |                 73.26 |              70.89 |                78.22 |                   21.78 |           74.51 |             84.47 |     nan     |         nan |       nan |      nan    |         9.28 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              173.44 |                  66.4  |                    70.13 |                 71.04 |              70.07 |                75.76 |                   24.24 |           67.46 |             86.21 |     nan     |         nan |       nan |      nan    |         8.53 |         11.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EC       | EC                                   | US       |               30.17 |                  65.84 |                    68.79 |                 69.58 |              68.59 |                72.48 |                   27.52 |           67.51 |             81.34 |     nan     |         nan |       nan |      nan    |         9.04 |          7.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.01 |                  61.59 |                    68.32 |                 70.88 |              65.37 |                71.99 |                   28.01 |           81.07 |             80.69 |     nan     |         nan |       nan |      nan    |         4.21 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                                  | US       |               15.21 |                  55.19 |                    67.46 |                 71.26 |              62.87 |                84.87 |                   15.13 |           87.66 |             78.55 |     nan     |         nan |       nan |      nan    |        12.86 |         20.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.87 |                  54.78 |                    67.35 |                 71.61 |              61.36 |                82.91 |                   17.09 |           96.13 |             69.96 |     nan     |         nan |       nan |      nan    |         9.21 |          6.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX      | CVX                                  | US       |              355.79 |                  61.83 |                    67.23 |                 68.75 |              66.43 |                74.2  |                   25.8  |           67.87 |             85.54 |     nan     |         nan |       nan |      nan    |        14.6  |         19.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.95 |                  56.59 |                    66.86 |                 70.34 |              61.06 |                81.81 |                   18.19 |           96.91 |             55.82 |     nan     |         nan |       nan |      nan    |        10.96 |         14.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.1  |                  57.44 |                    66.8  |                 70.05 |              62.29 |                77.47 |                   22.53 |           88.4  |             69.86 |     nan     |         nan |       nan |      nan    |        10.21 |          7.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN                                  | US       |               45.18 |                  61.63 |                    66.71 |                 68.55 |              64.17 |                71.66 |                   28.34 |           78.87 |             68.98 |     nan     |         nan |       nan |      nan    |         8.67 |         10.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | PBR      | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              116.96 |                  66.22 |                    66.39 |                 66.81 |              67.43 |                69.29 |                   30.71 |           62.77 |             72.82 |       0.137 |         nan |       nan |        1.84 |         5.18 |          5.21 |        5.83 |                 nan |              nan |                  12 |                  0.63 |
|          nan | COP      | COP                                  | US       |              133.08 |                  61.98 |                    66.32 |                 67.71 |              65.02 |                71.01 |                   28.99 |           71.01 |             76.15 |     nan     |         nan |       nan |      nan    |        13.05 |         16.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | XOM      | XOM                                  | US       |              587.33 |                  59.5  |                    66.24 |                 68.24 |              64.65 |                74.94 |                   25.06 |           70.93 |             83.26 |     nan     |         nan |       nan |      nan    |        14.67 |         20.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               24.32 |                  55.79 |                    66.23 |                 69.8  |              60.19 |                81.22 |                   18.78 |           97.63 |             54.06 |     nan     |         nan |       nan |      nan    |        11.71 |         11.97 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.41 |                  56.72 |                    66.18 |                 69.61 |              61.11 |                76.24 |                   23.76 |           91.27 |             65.51 |     nan     |         nan |       nan |      nan    |        10.51 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              114.69 |                  63.44 |                    66.15 |                 67.07 |              64.14 |                71.22 |                   28.78 |           77.5  |             56.41 |     nan     |         nan |       nan |      nan    |         9.73 |         13.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                                | EUROPE   |               20.76 |                  62.77 |                    65.9  |                 66.64 |              64.77 |                73.47 |                   26.53 |           71.39 |             63.49 |     nan     |         nan |       nan |      nan    |         8.98 |         11.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.22 |                  92.17 |                    81.43 |                 79.92 |              87.24 |                71.33 |                   28.67 |           62.77 |             80.3  |       0.142 |         nan |       nan |        1.78 |         4.64 |          4.71 |         5.3 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              241.21 |                  62.18 |                    73.06 |                 76.56 |              68.6  |                87.52 |                   12.48 |           93.37 |             80.7  |     nan     |         nan |       nan |      nan    |         9.64 |         10.65 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              100.57 |                  61.9  |                    72.63 |                 76.17 |              68.86 |                84.18 |                   15.82 |           87.95 |             91.35 |     nan     |         nan |       nan |      nan    |         8.6  |         21.26 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              241.8  |                  67.17 |                    71.9  |                 73.26 |              70.89 |                78.22 |                   21.78 |           74.51 |             84.47 |     nan     |         nan |       nan |      nan    |         9.28 |         10.67 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.87 |                  54.78 |                    67.35 |                 71.61 |              61.36 |                82.91 |                   17.09 |           96.13 |             69.96 |     nan     |         nan |       nan |      nan    |         9.21 |          6.45 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                                  | US       |               15.21 |                  55.19 |                    67.46 |                 71.26 |              62.87 |                84.87 |                   15.13 |           87.66 |             78.55 |     nan     |         nan |       nan |      nan    |        12.86 |         20.79 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              173.44 |                  66.4  |                    70.13 |                 71.04 |              70.07 |                75.76 |                   24.24 |           67.46 |             86.21 |     nan     |         nan |       nan |      nan    |         8.53 |         11.19 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.01 |                  61.59 |                    68.32 |                 70.88 |              65.37 |                71.99 |                   28.01 |           81.07 |             80.69 |     nan     |         nan |       nan |      nan    |         4.21 |          6.01 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.95 |                  56.59 |                    66.86 |                 70.34 |              61.06 |                81.81 |                   18.19 |           96.91 |             55.82 |     nan     |         nan |       nan |      nan    |        10.96 |         14.89 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                                   | US       |             1046.19 |                  49.5  |                    64.68 |                 70.13 |              58    |                77.81 |                   22.19 |           94.59 |             83.57 |     nan     |         nan |       nan |      nan    |         6.54 |         24.45 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.1  |                  57.44 |                    66.8  |                 70.05 |              62.29 |                77.47 |                   22.53 |           88.4  |             69.86 |     nan     |         nan |       nan |      nan    |        10.21 |          7.4  |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               24.32 |                  55.79 |                    66.23 |                 69.8  |              60.19 |                81.22 |                   18.78 |           97.63 |             54.06 |     nan     |         nan |       nan |      nan    |        11.71 |         11.97 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.41 |                  56.72 |                    66.18 |                 69.61 |              61.11 |                76.24 |                   23.76 |           91.27 |             65.51 |     nan     |         nan |       nan |      nan    |        10.51 |          7.16 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | EC       | EC                                   | US       |               30.17 |                  65.84 |                    68.79 |                 69.58 |              68.59 |                72.48 |                   27.52 |           67.51 |             81.34 |     nan     |         nan |       nan |      nan    |         9.04 |          7.95 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                  | US       |               14.59 |                  54.42 |                    65.33 |                 68.82 |              61.1  |                79.65 |                   20.35 |           84.04 |             75.81 |     nan     |         nan |       nan |      nan    |        10.25 |         22.54 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX      | CVX                                  | US       |              355.79 |                  61.83 |                    67.23 |                 68.75 |              66.43 |                74.2  |                   25.8  |           67.87 |             85.54 |     nan     |         nan |       nan |      nan    |        14.6  |         19.86 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN                                  | US       |               45.18 |                  61.63 |                    66.71 |                 68.55 |              64.17 |                71.66 |                   28.34 |           78.87 |             68.98 |     nan     |         nan |       nan |      nan    |         8.67 |         10.23 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | XOM      | XOM                                  | US       |              587.33 |                  59.5  |                    66.24 |                 68.24 |              64.65 |                74.94 |                   25.06 |           70.93 |             83.26 |     nan     |         nan |       nan |      nan    |        14.67 |         20.65 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | ABI.BR   | ABI.BR                               | EUROPE   |              129.77 |                  51.91 |                    64.14 |                 67.96 |              59.48 |                81.25 |                   18.75 |           84.75 |             74.83 |     nan     |         nan |       nan |      nan    |        15.12 |         16.15 |       nan   |                 nan |              nan |                   5 |                  0.26 |
|          nan | COP      | COP                                  | US       |              133.08 |                  61.98 |                    66.32 |                 67.71 |              65.02 |                71.01 |                   28.99 |           71.01 |             76.15 |     nan     |         nan |       nan |      nan    |        13.05 |         16.83 |       nan   |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO       | US       |               98.58 |                     0.06 |    -0.01 |      0.11 |                  72.11 |                        83.69 |         84.67 |         86.66 |          84.2  |        78.92 |           86.42 |             81.72 |         3.65 |
|               2 | SMTC      | SMTC      | US       |               14.34 |                     0.06 |    -0.01 |      0.33 |                  74.94 |                        81.55 |         85.27 |         79.27 |          76.18 |        62.26 |           74.43 |             85.21 |         8.5  |
|               3 | FRO       | FRO       | US       |                9.41 |                     0.06 |    -0.03 |      0.16 |                  74.92 |                        80.86 |         82.9  |         83.07 |          81.62 |        78.58 |           91.27 |             65.51 |         5.19 |
|               4 | PSX       | PSX       | US       |               89.35 |                     0.08 |    -0.03 |      0.04 |                  67.38 |                        80.49 |         75.37 |         83.75 |          81.15 |        76.8  |           79.6  |             83.93 |         3.89 |
|               5 | DHT       | DHT       | US       |                3.1  |                     0.06 |    -0.02 |      0.11 |                  75.58 |                        80.37 |         81.76 |         81.02 |          79.12 |        78.34 |           88.4  |             69.86 |         4.55 |
|               6 | MU        | MU        | US       |             1046.19 |                     0.04 |     0.01 |      0.13 |                  57.81 |                        79.22 |         78.2  |         72.63 |          85.79 |        84.16 |           94.59 |             83.57 |         8.16 |
|               7 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.87 |                     0.07 |    -0.02 |      0.07 |                  65.1  |                        78.31 |         72.2  |         77.65 |          81.24 |        80.34 |           96.13 |             69.96 |         3.77 |
|               8 | DELL      | DELL      | US       |              303.67 |                     0.08 |    -0.06 |      0.19 |                  73.73 |                        77.76 |         80.04 |         82.25 |          78.11 |        66.49 |           72.88 |             73.33 |         7.82 |
|               9 | AMD       | AMD       | US       |              872.15 |                     0.04 |    -0.01 |      0.31 |                  62.75 |                        77.75 |         82.35 |         78.86 |          76.01 |        62.61 |           80.29 |             74.06 |         7.2  |
|              10 | WT        | WT        | US       |                3.2  |                     0.03 |     0.01 |     -0.02 |                  53.25 |                        76.51 |         76.5  |         83.03 |          77.93 |        66.15 |           72.16 |             83.83 |         5.83 |
|              11 | NAT       | NAT       | US       |                1.45 |                     0.06 |    -0.03 |      0.2  |                  78.02 |                        76.15 |         81.08 |         75.97 |          72.82 |        68.86 |           87.16 |             43.19 |         4.75 |
|              12 | PAA       | PAA       | US       |               15.21 |                     0.06 |    -0.02 |     -0.04 |                  73.01 |                        75.59 |         61.99 |         70.64 |          74.68 |        76.15 |           87.66 |             78.55 |         2.04 |
|              13 | EQNR      | EQNR      | US       |               88.07 |                     0.08 |    -0.01 |      0.02 |                  59.3  |                        74.91 |         70.85 |         76.05 |          74.14 |        74.57 |           75.88 |             85.42 |         5.73 |
|              14 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.21 |                     0.07 |     0.01 |      0.11 |                  60.9  |                        74.87 |         80.96 |         74.65 |          73.1  |        72.48 |           69.47 |             75.76 |         5.42 |
|              15 | CVX       | CVX       | US       |              355.79 |                     0.05 |     0.01 |      0.02 |                  65.33 |                        74.55 |         76.7  |         72.74 |          66.78 |        66.37 |           67.87 |             85.54 |         3.57 |
|              16 | C5H.IR    | C5H.IR    | EUROPE   |                1.7  |                     0.03 |     0.01 |      0.06 |                  49.51 |                        74.27 |         78.25 |         68.14 |          71.25 |        74.03 |           98.08 |             53.99 |         2.77 |
|              17 | DOCU      | DOCU      | US       |               11    |                     0.07 |    -0.02 |      0.05 |                  69.69 |                        73.89 |         72.88 |         78.24 |          66.34 |        59.26 |           61.14 |             80.57 |         7.92 |
|              18 | HOOD      | HOOD      | US       |               92.03 |                     0.07 |    -0.06 |      0.12 |                  80.06 |                        73.85 |         72.9  |         72.36 |          63.58 |        52.61 |           67.89 |             78.71 |         8.89 |
|              19 | UGP       | UGP       | US       |                6.68 |                     0.07 |    -0.06 |      0.11 |                  77.84 |                        73.65 |         68.47 |         78.37 |          72.52 |        67.2  |           62.41 |             68.67 |         5.04 |
|              20 | GTLB      | GTLB      | US       |                6.77 |                     0.08 |    -0.07 |      0.03 |                  75.86 |                        73.38 |         67.23 |         79.17 |          64.31 |        49.06 |           58.04 |             72.08 |         8.45 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | TLRY     | Tilray Brands, Inc. | OTHER    |                 0.5 |             26.04 |         27.28 |         21.94 |           24.8 |        29.63 |           34.83 |             34.22 |             27.74 |         8.94 |             77.79 | long               |                0.85 |                  -0.3 |                 -0.1 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      3 | AMC      | AMC    | US       |                2.58 |             84.14 |         87.66 |         91.71 |          80.62 |        79.29 |           82.69 |             78.44 |            nan    |         9.51 |             65.07 | swing              |                7.95 |                  5.05 |                 4.56 |
|    326 | ITRG     | ITRG   | US       |                0.46 |             56.11 |         39.32 |         56.07 |          56.16 |        64.53 |           57.64 |             61.4  |             82.1  |         8.27 |             68.32 | long               |                0.32 |                  4.52 |                 4.84 |
|     11 | BP       | BP     | US       |              100.57 |             77.45 |         81.71 |         75.81 |          73.56 |        79.09 |           87.95 |             91.35 |             62.18 |         4.53 |             72.34 | short              |               15.22 |                  4.26 |               nan    |
|    356 | COST     | COST   | US       |              359.55 |             55.11 |         67.88 |         53.51 |          55.21 |        55.02 |           77.13 |             79.72 |             10.04 |         2.77 |             66.66 | short              |               14.27 |                  4.01 |                 3.3  |
|     67 | NNBR     | NNBR   | US       |                0.27 |             70.06 |         77.64 |         71.98 |          68.15 |        50.44 |           37.06 |             93.54 |             23.22 |         8.62 |             72.11 | short              |               20.94 |                  3.93 |                 2.8  |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    676 | PAH3.DE  | PAH3.DE | EUROPE   |                7.75 |             29.58 |         25.4  |         25.29 |          33.75 |        57.59 |          nan    |             24.43 |             94.86 |         5.22 |             70.3  | long               |              -15.77 |                 -4.38 |                -3.59 |
|    646 | TIT.MI   | TIT.MI  | EUROPE   |               15.09 |             35.89 |         35.52 |         36.26 |          40.87 |        31.3  |           19.57 |             52.9  |             17.84 |         2.3  |             71.32 | medium             |              -13.54 |                 -3.68 |                -3.28 |
|    628 | BAS.DE   | BAS.DE  | EUROPE   |               43.57 |             38.64 |         43.7  |         40.99 |          36.29 |        34.6  |           30.8  |             27.12 |             30.51 |         2.2  |             67.86 | short              |               -2.6  |                 -3.38 |               nan    |
|    581 | NCNO     | NCNO    | US       |                1.73 |             43.44 |         29.44 |         52.86 |          46.14 |        40.74 |           21.58 |             51.53 |             54.56 |         7.74 |             71.66 | swing              |               -8.02 |                 -3.28 |                -2.52 |
|    681 | VOW.DE   | VOW.DE  | EUROPE   |               35.82 |             28.62 |         29.88 |         22.34 |          27.35 |        51.81 |          nan    |              3.31 |             92.35 |         5.6  |             70.3  | long               |              -10.54 |                 -3.26 |                -2.39 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91

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
- Excluded by hard/data filters: **303**
- Event watch (otherwise eligible): **1**
- Final eligible: **696**
- Eligible change vs previous stored run: **-13**

Top exclusion categories:
- liquidity: 242
- price: 187
- market_cap: 166
- price_history: 21
- data_confidence: 15
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| VLO | 2 |  | 1 |  | 2 | main,pullback |
| FRO | 4 |  | 3 |  | 2 | main,pullback |
| MU | 5 |  | 6 |  | 2 | main,pullback |
| DHT | 6 |  | 5 |  | 2 | main,pullback |
| DELL | 7 |  | 8 |  | 2 | main,pullback |
| CMBT.BR | 8 |  | 7 |  | 2 | main,pullback |
| PSX | 9 |  | 4 |  | 2 | main,pullback |
| SMTC | 10 |  | 2 |  | 2 | main,pullback |
| PBR-A | 21 | 1 | 22 | 1 | 1 | value,quality_value |
| PBR | 61 | 2 | 23 | 2 | 1 | value,quality_value |
| ADAM | 292 | 7 |  | 5 | 1 | value,quality_value |
| INVA | 298 | 6 |  | 6 | 1 | value,quality_value |
| ALL-PH | 419 | 3 | 208 | 3 | 1 | value,quality_value |
| AD | 450 | 8 |  | 8 | 1 | value,quality_value |
| MOMO | 598 | 4 | 369 | 4 | 1 | value,quality_value |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
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
| 1 | PBR-A | value+pullback | 76.19 | 92.17 | 67.29 | 62.77 | 80.30 | 71.33 | 75.57 |
| 2 | PBR | value+pullback | 67.51 | 66.22 | 68.35 | 62.77 | 72.82 | 69.29 | 71.11 |
| 3 | HRTG | value+pullback | 63.48 | 56.71 | 74.73 | 60.86 | 68.42 | 59.06 | 63.73 |
| 4 | ALL-PH | value+pullback | 63.30 | 67.41 | 59.58 | 76.20 | 42.24 | 62.65 | 52.87 |
| 5 | GTN | value+pullback | 61.33 | 60.06 | 67.73 | 76.52 | 39.89 | 54.58 | 53.50 |
| 6 | IRS | value+pullback | 61.17 | 55.97 | 61.53 | 75.63 | 42.38 | 67.06 | 47.16 |
| 7 | MOMO | value+pullback | 58.94 | 66.59 | 38.63 | 80.19 | 26.73 | 73.02 | 41.64 |
| 8 | GAB | value+pullback | 57.91 | 59.59 | 70.56 | 52.12 |  | 47.91 | 45.37 |
| 9 | PAA | pullback | 56.23 | 55.19 | 73.01 | 87.66 | 78.55 | 84.87 | 72.66 |
| 10 | VLO | pullback | 55.58 | 47.74 | 72.11 | 86.42 | 81.72 | 82.07 | 84.43 |
| 11 | BEN | pullback | 55.28 | 54.42 | 76.66 | 84.04 | 75.81 | 79.65 | 70.94 |
| 12 | ABI.BR | pullback | 55.22 | 51.91 | 75.09 | 84.75 | 74.83 | 81.25 | 55.71 |
| 13 | DHT | pullback | 54.64 | 57.44 | 75.58 | 88.40 | 69.86 | 77.47 | 80.07 |
| 14 | ORSTED.CO | pullback | 54.48 | 48.48 | 80.43 | 64.73 | 97.26 | 74.68 | 55.75 |
| 15 | ARGX.BR | pullback | 54.29 | 36.15 | 65.46 | 93.05 | 80.09 | 79.78 | 61.68 |
| 16 | CMBT.BR | pullback | 54.27 | 54.78 | 65.10 | 96.13 | 69.96 | 82.91 | 78.99 |
| 17 | FRO | pullback | 54.22 | 56.72 | 74.92 | 91.27 | 65.51 | 76.24 | 82.26 |
| 18 | AOD | pullback | 53.10 | 50.98 | 75.35 | 82.36 |  | 84.53 | 67.80 |
| 19 | PSX | pullback | 52.96 | 51.17 | 67.38 | 79.60 | 83.93 | 78.91 | 78.97 |
| 20 | MU | pullback | 52.56 | 49.50 | 57.81 | 94.59 | 83.57 | 77.81 | 81.18 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 10 / 0 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 73.1 | 22 / 3 |
| Top 50 | 50/50 | 49/50 | 49/50 | 48/50 | 0/50 | 72.7 | 34 / 16 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=2, large_20_100b=3, mega_100b_plus=2
