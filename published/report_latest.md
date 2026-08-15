# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-15

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

- **EUROPE:** 90.8/100
- **OTHER:** 78.4/100
- **US:** 87.4/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PBF       | PBF       | US       |                7.36 |             92.7  |         87.36 |         92.84 |          94.83 |        92.55 |             nan |               nan |             88.99 |         6.98 |             62.84 | medium             |                0.08 |                   nan |                  nan |
|      2 | RMAX      | RMAX      | US       |                0.6  |             86.59 |         87.03 |         89.08 |          84.29 |        86.15 |             nan |               nan |             90.58 |         7.05 |             62.84 | swing              |               -0.29 |                   nan |                  nan |
|      3 | DINO      | DINO      | US       |               14.39 |             86.19 |         79.69 |         86.32 |          88.4  |        86.05 |             nan |               nan |             81.77 |         3.86 |             62.84 | medium             |               -0.17 |                   nan |                  nan |
|      4 | HPE       | HPE       | US       |               67.18 |             86.11 |         84.17 |         91.99 |          88.05 |        73.56 |             nan |               nan |             57.36 |         6.73 |             62.84 | swing              |               -0.09 |                   nan |                  nan |
|      5 | HRB       | HRB       | US       |                5.91 |             85.86 |         89.65 |         92.67 |          78.93 |        82.08 |             nan |               nan |             92.29 |         6.87 |             61.93 | swing              |               -0.05 |                   nan |                  nan |
|      6 | ABCL      | ABCL      | US       |                3.02 |             85.86 |         90.26 |         95.48 |          81.45 |        64.11 |             nan |               nan |             45.91 |         9    |             60    | swing              |               -0.12 |                   nan |                  nan |
|      7 | ZD        | ZD        | US       |                1.64 |             84.77 |         67.1  |         83.28 |          87.03 |        86.25 |             nan |               nan |             87.4  |         5.19 |             62.84 | medium             |               -0.3  |                   nan |                  nan |
|      8 | MPC       | MPC       | US       |               89.66 |             84.54 |         83.25 |         88.65 |          85.83 |        75.43 |             nan |               nan |             63.15 |         3.8  |             62.84 | swing              |               -0.48 |                   nan |                  nan |
|      9 | GH        | GH        | US       |               18.23 |             84.2  |         47.28 |         78.87 |          89.53 |        95.39 |             nan |               nan |            nan    |         6.74 |             59.09 | long               |               -0.2  |                   nan |                  nan |
|     10 | DELL      | DELL      | US       |              274.03 |             83.79 |         83.36 |         91.81 |          84.22 |        60.32 |             nan |               nan |             33.61 |         7.64 |             61.93 | swing              |                0.15 |                   nan |                  nan |
|     11 | MGTX      | MGTX      | US       |                1.12 |             83.78 |         68.27 |         81.27 |          86.76 |        86.28 |             nan |               nan |            nan    |         5.95 |             59.09 | medium             |              nan    |                   nan |                  nan |
|     12 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.73 |             83.5  |         78.16 |         80.22 |          86.77 |        95.08 |             nan |               nan |             99.81 |         3.23 |             60    | long               |               -0.69 |                   nan |                  nan |
|     13 | GPN       | GPN       | US       |               21.28 |             83.44 |         83.13 |         84.05 |          73.33 |        83.75 |             nan |               nan |             96.35 |         5.5  |             62.84 | swing              |               -0.08 |                   nan |                  nan |
|     14 | CAKE      | CAKE      | US       |                4.88 |             83.43 |         89.38 |         90.38 |          77.48 |        53.79 |             nan |               nan |             27.59 |         5.55 |             62.84 | swing              |                0.03 |                   nan |                  nan |
|     15 | TXG       | TXG       | US       |                6.31 |             83.03 |         87.5  |         89.49 |          78.56 |        44.7  |             nan |               nan |              6.65 |         6.94 |             62.84 | swing              |               -0.02 |                   nan |                  nan |
|     16 | NWL       | NWL       | US       |                2.3  |             82.7  |         82.34 |         86.77 |          77.1  |        83.05 |             nan |               nan |             87.94 |         8.04 |             62.84 | swing              |               -0.14 |                   nan |                  nan |
|     17 | RBI.VI    | RBI.VI    | EUROPE   |               20.65 |             82.33 |         77.61 |         84.51 |          85.32 |        80.16 |             nan |               nan |             72.3  |         3.53 |             62.84 | medium             |               -2.27 |                   nan |                  nan |
|     18 | ANRO      | ANRO      | US       |                1.09 |             82.19 |         83.38 |         84.9  |          81.01 |        61.68 |             nan |               nan |             37.97 |         7.15 |             60    | swing              |                0.82 |                   nan |                  nan |
|     19 | OPRT      | OPRT      | US       |                0.31 |             82.13 |         78.29 |         85.88 |          78.38 |        87.65 |             nan |               nan |             98.41 |         7.98 |             62.84 | long               |               -0.21 |                   nan |                  nan |
|     20 | OSCR      | OSCR      | US       |                8.74 |             82.13 |         81.89 |         86.69 |          82.36 |        64.49 |             nan |               nan |             44.92 |         8.23 |             62.84 | swing              |               -0.17 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | VOW3.DE  | Volkswagen AG                                        | EUROPE   |               36.96 |                  80.21 |                    75.94 |                 74.09 |              78.53 |                71.8  |                   28.2  |           64.44 |            nan    |       0.382 |         nan |       nan |       13.78 |         3.13 |          7.07 |        0.68 |                 nan |              nan |                  11 |                  0.58 |
|            2 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.12 |                  72.71 |                    75.73 |                 78.53 |              74.35 |                89.63 |                   10.37 |           94.26 |             58.66 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.62 |                  73.82 |                    75.65 |                 78.2  |              74.88 |                81.95 |                   18.05 |           88.88 |             69.81 |       0.171 |         nan |       nan |        4.32 |         2.93 |          5.46 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.27 |                    73.69 |                 73.43 |              72.91 |                74.85 |                   25.15 |           86.96 |             37.97 |       0.617 |         nan |       nan |        1.48 |         4.1  |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ACA.PA   | ACA.PA                                               | EUROPE   |               61.12 |                  68.3  |                    73.22 |                 74.05 |              72.9  |                91.29 |                    8.71 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.13 |         10    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.75 |                  62.68 |                    72.35 |                 76.38 |              66.8  |                76.05 |                   23.95 |           99.19 |             79.76 |       0.113 |         nan |       nan |        5.32 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            6 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.48 |                  72.12 |                    72.16 |                 73.89 |              71.6  |                69.55 |                   30.45 |           81.06 |             71.58 |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               15.31 |                  64.51 |                    71.77 |                 72.98 |              71.28 |                98.36 |                    1.64 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          8.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BNP.PA   | BNP.PA                                               | EUROPE   |              122.86 |                  68.28 |                    71.72 |                 72.29 |              71.49 |                84.31 |                   15.69 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.54 |          9.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  76.49 |                    70.87 |                 69.59 |              73.47 |                71.27 |                   28.73 |           64.51 |             55.69 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                                                 | US       |              215.86 |                  67.9  |                    70.85 |                 71.35 |              70.66 |                81.68 |                   18.32 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              215.21 |                  67.13 |                    70.81 |                 71.42 |              70.56 |                84.3  |                   15.7  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.72 |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ARCC     | ARCC                                                 | US       |               12.33 |                  64.56 |                    69.94 |                 70.83 |              69.58 |                89.65 |                   10.35 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.28 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | 0Q2N.IL  | K+S Aktiengesellschaft                               | OTHER    |                2.84 |                  69.34 |                    69.89 |                 69.58 |              70.49 |                75.11 |                   24.89 |           66.69 |            nan    |       0.261 |         nan |       nan |        1.54 |       nan    |          2.65 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | ADAM     | ADAM                                                 | US       |                0.79 |                  66.71 |                    69.58 |                 70.05 |              69.39 |                80.07 |                   19.93 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.24 |          6.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  71.21 |                    69.44 |                 70.77 |              68.61 |                71.77 |                   28.23 |           85.32 |             44.23 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|           10 | IHS      | IHS Holding Limited                                  | OTHER    |                2.44 |                  73.77 |                    69.06 |                 69.22 |              72.69 |                62.52 |                   37.48 |           56.64 |             83.25 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                                  | US       |              112.67 |                  64.77 |                    68.72 |                 69.38 |              68.46 |                83.2  |                   16.8  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | AVGO     | Broadcom Inc.                                        | US       |             1615.59 |                  59.62 |                    68.29 |                 69.09 |              63.6  |                79.17 |                   20.83 |           82.97 |             64.26 |       0.015 |         nan |       nan |       45.5  |        20.12 |         65.39 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | AIG      | AIG                                                  | US       |               34.63 |                  63.58 |                    68.16 |                 68.93 |              67.86 |                84.98 |                   15.02 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.73 |         13.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.12 |                  72.71 |                    75.73 |                 78.53 |              74.35 |                89.63 |                   10.37 |           94.26 |             58.66 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.62 |                  73.82 |                    75.65 |                 78.2  |              74.88 |                81.95 |                   18.05 |           88.88 |             69.81 |       0.171 |         nan |       nan |        4.32 |         2.93 |          5.46 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.75 |                  62.68 |                    72.35 |                 76.38 |              66.8  |                76.05 |                   23.95 |           99.19 |             79.76 |       0.113 |         nan |       nan |        5.32 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            1 | VOW3.DE  | Volkswagen AG                                        | EUROPE   |               36.96 |                  80.21 |                    75.94 |                 74.09 |              78.53 |                71.8  |                   28.2  |           64.44 |            nan    |       0.382 |         nan |       nan |       13.78 |         3.13 |          7.07 |        0.68 |                 nan |              nan |                  11 |                  0.58 |
|          nan | ACA.PA   | ACA.PA                                               | EUROPE   |               61.12 |                  68.3  |                    73.22 |                 74.05 |              72.9  |                91.29 |                    8.71 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.13 |         10    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.48 |                  72.12 |                    72.16 |                 73.89 |              71.6  |                69.55 |                   30.45 |           81.06 |             71.58 |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.27 |                    73.69 |                 73.43 |              72.91 |                74.85 |                   25.15 |           86.96 |             37.97 |       0.617 |         nan |       nan |        1.48 |         4.1  |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               15.31 |                  64.51 |                    71.77 |                 72.98 |              71.28 |                98.36 |                    1.64 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          8.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BNP.PA   | BNP.PA                                               | EUROPE   |              122.86 |                  68.28 |                    71.72 |                 72.29 |              71.49 |                84.31 |                   15.69 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.54 |          9.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              215.21 |                  67.13 |                    70.81 |                 71.42 |              70.56 |                84.3  |                   15.7  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.72 |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                 | US       |              215.86 |                  67.9  |                    70.85 |                 71.35 |              70.66 |                81.68 |                   18.32 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ARCC     | ARCC                                                 | US       |               12.33 |                  64.56 |                    69.94 |                 70.83 |              69.58 |                89.65 |                   10.35 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.28 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  71.21 |                    69.44 |                 70.77 |              68.61 |                71.77 |                   28.23 |           85.32 |             44.23 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | ADAM     | ADAM                                                 | US       |                0.79 |                  66.71 |                    69.58 |                 70.05 |              69.39 |                80.07 |                   19.93 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.24 |          6.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  76.49 |                    70.87 |                 69.59 |              73.47 |                71.27 |                   28.73 |           64.51 |             55.69 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            8 | 0Q2N.IL  | K+S Aktiengesellschaft                               | OTHER    |                2.84 |                  69.34 |                    69.89 |                 69.58 |              70.49 |                75.11 |                   24.89 |           66.69 |            nan    |       0.261 |         nan |       nan |        1.54 |       nan    |          2.65 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BMY      | BMY                                                  | US       |              112.67 |                  64.77 |                    68.72 |                 69.38 |              68.46 |                83.2  |                   16.8  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | IHS      | IHS Holding Limited                                  | OTHER    |                2.44 |                  73.77 |                    69.06 |                 69.22 |              72.69 |                62.52 |                   37.48 |           56.64 |             83.25 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | AVGO     | Broadcom Inc.                                        | US       |             1615.59 |                  59.62 |                    68.29 |                 69.09 |              63.6  |                79.17 |                   20.83 |           82.97 |             64.26 |       0.015 |         nan |       nan |       45.5  |        20.12 |         65.39 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | AGN.AS   | AGN.AS                                               | EUROPE   |               12.16 |                  60.79 |                    67.86 |                 69.04 |              67.39 |                93.79 |                    6.21 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.05 |         13.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:-----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | INDU-C.ST | AB Industrivärden (publ)                             | EUROPE   |               20.37 |                     0.08 |    -0.06 |     -0    |                  74.54 |                        69.19 |         45.69 |         58.78 |          67.39 |        66.75 |           83.27 |             79.76 |         2.39 |
|               2 | INDU-A.ST | AB Industrivärden (publ)                             | EUROPE   |               20.46 |                     0.08 |    -0.06 |     -0.01 |                  73.26 |                        68.22 |         40.95 |         57.23 |          66.19 |        64.04 |           83.27 |             79.76 |         2.54 |
|               3 | IRWD      | Ironwood Pharmaceuticals, Inc.                       | US       |                0.62 |                     0.02 |    -0    |      0.12 |                  52.87 |                        67.9  |         63.45 |         57.86 |          69.61 |        80.85 |           88.88 |             69.81 |         6.46 |
|               4 | MSFT      | Microsoft Corporation                                | US       |             3178.69 |                     0.02 |    -0.01 |      0.26 |                  52.5  |                        66.3  |         72.78 |         66.02 |          55.94 |        52.26 |           60.78 |             65.86 |         5.62 |
|               5 | ALL       | The Allstate Corporation                             | US       |               57.12 |                     0.05 |    -0.02 |      0.05 |                  73.72 |                        66.03 |         59.06 |         64.14 |          61.41 |        55.4  |           67.81 |             62.28 |         2.98 |
|               6 | AMZN      | Amazon.com, Inc.                                     | US       |             2448.02 |                     0.08 |    -0.04 |      0.06 |                  70.87 |                        65.4  |         58.31 |         55.59 |          60.76 |        60.02 |           80.86 |             62.95 |         5.58 |
|               7 | LLY       | Eli Lilly and Company                                | US       |              909.38 |                     0.04 |    -0    |      0    |                  62.9  |                        63.5  |         50.73 |         56.43 |          62.26 |        60.81 |           80.13 |             65.49 |         4.12 |
|               8 | WKC       | World Kinect Corporation                             | US       |                1.6  |                     0.1  |    -0.01 |     -0.01 |                  43.77 |                        62.67 |         52.6  |         67.46 |          69.16 |        64.15 |           56.82 |             73.43 |         4.81 |
|               9 | AVGO      | Broadcom Inc.                                        | US       |             1615.59 |                     0.08 |    -0.08 |      0.06 |                  78.27 |                        62.59 |         47.15 |         49.24 |          59.85 |        61.42 |           82.97 |             64.26 |         6.07 |
|              10 | GOLD      | Gold.com, Inc.                                       | US       |                1.1  |                     0.02 |     0.01 |      0.15 |                  42.92 |                        62.24 |         67.23 |         53.97 |          55.19 |        52.43 |           48.4  |             83.36 |         5.64 |
|              11 | LNC       | Lincoln National Corporation                         | US       |                7.52 |                     0.03 |    -0.01 |      0.08 |                  60.68 |                        60.06 |         66.2  |         65.32 |          56.34 |        55.97 |           43.09 |             61.63 |         4.58 |
|              12 | GAIN      | Gladstone Investment Corporatio                      | US       |                0.56 |                     0.03 |    -0.02 |     -0.01 |                  61.9  |                        60.03 |         52.44 |         55.27 |          58.18 |        53.74 |           64.83 |             67.59 |         3.07 |
|              13 | CLW       | Clearwater Paper Corporation                         | US       |                0.3  |                     0.08 |    -0.08 |      0.34 |                  78.34 |                        60.01 |         64.19 |         60.92 |          46.69 |        40.67 |           33.96 |             62.48 |         6.79 |
|              14 | V         | Visa Inc.                                            | US       |              587.49 |                     0.02 |     0.01 |      0.02 |                  44.34 |                        59.1  |         56.94 |         58.18 |          54.18 |        49.44 |           68.95 |             63.82 |         2.82 |
|              15 | GSL       | Global Ship Lease Inc New                            | OTHER    |                1.31 |                     0.05 |    -0.01 |      0.05 |                  70.66 |                        59.07 |         57.66 |         53.86 |          61.01 |        67.8  |           70.81 |             36.5  |         3.63 |
|              16 | CION      | CION Investment Corporation                          | US       |                0.32 |                     0.02 |     0    |      0.23 |                  48.34 |                        57.85 |         69.8  |         53.25 |          43.97 |        47.67 |           34.77 |             58.34 |         6.17 |
|              17 | GTN       | Gray Media, Inc.                                     | US       |                0.46 |                     0.03 |    -0.03 |      0.32 |                  62.22 |                        57.8  |         64.98 |         55.54 |          48.09 |        53.94 |           48.38 |             41.99 |         5.76 |
|              18 | GOOGL     | Alphabet Inc.                                        | US       |             3655.43 |                     0.08 |    -0.02 |     -0    |                  59.75 |                        57.68 |         45.86 |         44.19 |          57.97 |        57.22 |           76.3  |             70.18 |         4.74 |
|              19 | HTD       | John Hancock Tax-Advantaged Dividend Income Fund     | US       |                0.78 |                     0.02 |     0.01 |     -0    |                  43.93 |                        57.36 |         52.24 |         55.29 |          56.75 |        56.47 |           56.19 |             79.28 |         1.87 |
|              20 | IRS       | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                     0.06 |    -0.02 |     -0.03 |                  71.8  |                        56.86 |         41.89 |         44.77 |          54.8  |        64.82 |           85.32 |             44.23 |         3.98 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4712.46 |             64    |         66.99 |         57.02 |          62.59 |        65.42 |           94.57 |             59.52 |             30.53 |         5.41 |             89.53 | short              |               -0.25 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.88 |             59.6  |         58.51 |         60.69 |          56.69 |        61.46 |           54.97 |             49.24 |             71.96 |         8.34 |             85.47 | long               |               -0.99 |                   nan |                  nan |
|    nan | JOYY     | JOYY Inc.                    | OTHER    |                3.18 |             53.43 |         52.31 |         58.67 |          54.56 |        48.38 |           48.68 |             49.92 |             32.12 |         4.74 |             81.91 | swing              |              nan    |                   nan |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.      | US       |                3.38 |             46.02 |         35.06 |         42.64 |          49.4  |        62.46 |           67.44 |             45.59 |             78.89 |         7.45 |             87.57 | long               |                1.03 |                   nan |                  nan |
|    nan | ATHM     | Autohome Inc.                | OTHER    |                2.26 |             42.61 |         51.3  |         48.13 |          37.08 |        34.84 |           32.54 |             25.82 |             36.59 |         5.92 |             78.55 | short              |                1.49 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.89 |             38.41 |         25.71 |         34.25 |          42.56 |        54.17 |           50.26 |             47.47 |             77.74 |         6.16 |             78.58 | long               |                0.36 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.29 |             38.17 |         28.52 |         35.16 |          41.17 |        53.97 |           47.64 |             41.42 |             85.58 |         7.18 |             78.43 | long               |                0.27 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             37.24 |         32.55 |         31.54 |          41.94 |        59.49 |           70.69 |             25.72 |             79.41 |         4.73 |             81.52 | long               |                0.57 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.76 |             35.6  |         39.7  |         24.58 |          31.51 |        40.19 |           44.83 |             37.78 |             49.64 |         7.01 |             75.4  | long               |                2.3  |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.89 |             34.05 |         30.51 |         22.57 |          37.59 |        49.26 |           68.02 |             20.09 |             44.44 |         9.03 |             77.55 | long               |                1.01 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             26.38 |         52.82 |         23    |          22.24 |        29.76 |           24.32 |             27.32 |             50    |         7.71 |             75.24 | short              |                0.78 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.4  |             22.95 |         28.2  |         21.8  |          22.36 |        23.55 |           22.35 |             38.46 |             23.38 |         6.8  |             76.61 | short              |                2.46 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
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
- Excluded by hard/data filters: **284**
- Event watch (otherwise eligible): **12**
- Final eligible: **704**
- Eligible change vs previous stored run: **-2**

Top exclusion categories:
- liquidity: 229
- price: 173
- market_cap: 159
- data_confidence: 24
- price_history: 24
- asset_type: 1
- delisted: 1
- duplicate_listing: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| IRWD | 241 | 3 | 3 | 2 | 2 | value,pullback,quality_value |
| AKER.OL | 23 | 5 |  | 3 | 1 | value,quality_value |
| PARR | 71 | 6 |  | 5 | 1 | value,quality_value |
| BION.SW | 173 | 2 |  | 1 | 1 | value,quality_value |
| IHS | 425 | 10 |  | 10 | 1 | value,quality_value |
| 0Q2N.IL | 493 | 8 |  | 9 | 1 | value,quality_value |
| IRS | 541 | 9 | 20 | 7 | 1 | value,quality_value |
| MOMO | 579 | 7 | 31 | 8 | 1 | value,quality_value |
| STNE | 656 | 4 |  | 6 | 1 | value,quality_value |
| VOW3.DE | 674 | 1 |  | 4 | 1 | value,quality_value |
| PBF | 1 |  |  |  | 1 | main |
| RMAX | 2 |  |  |  | 1 | main |
| DINO | 3 |  |  |  | 1 | main |
| HPE | 4 |  |  |  | 1 | main |
| HRB | 5 |  |  |  | 1 | main |

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
| 1 | AVGO | value+pullback | 72.16 | 59.62 | 78.27 | 82.97 | 64.26 | 79.17 | 54.54 |
| 2 | IRWD | value+pullback | 72.07 | 73.82 | 52.87 | 88.88 | 69.81 | 81.95 | 66.53 |
| 3 | VOW3.DE | value+pullback | 71.17 | 80.21 | 72.32 | 64.44 |  | 71.80 | 38.14 |
| 4 | IRS | value+pullback | 70.89 | 71.21 | 71.80 | 85.32 | 44.23 | 71.77 | 49.79 |
| 5 | MOMO | value+pullback | 70.20 | 76.49 | 71.01 | 64.51 | 55.69 | 71.27 | 46.36 |
| 6 | GSL | value+pullback | 67.91 | 71.46 | 70.66 | 70.81 | 36.50 | 72.68 | 59.33 |
| 7 | 0P6O.IL | value+pullback | 67.20 | 63.11 | 70.96 | 74.71 |  | 71.61 | 41.51 |
| 8 | 0Q2N.IL | value+pullback | 65.15 | 69.34 | 57.28 | 66.69 |  | 75.11 | 53.21 |
| 9 | VOLV-B.ST | value+pullback | 63.81 | 67.88 | 65.36 | 59.27 | 59.12 | 61.53 | 53.78 |
| 10 | SDF.DE | value+pullback | 63.25 | 57.54 | 54.92 | 80.57 | 55.86 | 72.92 | 51.34 |
| 11 | PBR-A | value+pullback | 61.99 | 73.63 | 65.72 | 54.53 | 57.99 | 47.47 | 53.15 |
| 12 | MAGN | value+pullback | 61.92 | 67.52 | 47.38 | 60.00 | 71.96 | 68.11 | 52.26 |
| 13 | 1VOW3.MI | value+pullback | 61.54 | 63.55 | 64.72 | 64.44 | 35.56 | 65.39 | 39.58 |
| 14 | CNXC | value+pullback | 60.73 | 83.95 | 70.58 | 45.38 | 32.09 | 39.42 | 39.91 |
| 15 | ALL-PH | value+pullback | 60.57 | 61.97 | 65.08 | 67.81 | 39.12 | 58.16 | 43.21 |
| 16 | AF.PA | value+pullback | 60.41 | 66.50 | 77.15 | 47.91 | 56.32 | 41.77 | 51.26 |
| 17 | BHF | value+pullback | 60.05 | 70.28 | 55.64 | 51.85 | 43.40 | 64.69 | 43.68 |
| 18 | BION.SW | value | 59.74 | 72.71 | 40.38 | 94.26 | 58.66 | 89.63 | 70.08 |
| 19 | WKC | value+pullback | 58.65 | 60.34 | 43.77 | 56.82 | 73.43 | 68.70 | 65.80 |
| 20 | MFA | value+pullback | 58.20 | 57.89 | 49.63 | 79.81 | 36.30 | 64.13 | 45.25 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 0/10 | 0/10 | 9/10 | 0/10 | 10/10 | 62.8 | 10 / 0 |
| Top 25 | 1/25 | 1/25 | 23/25 | 1/25 | 24/25 | 62.8 | 24 / 1 |
| Top 50 | 2/50 | 2/50 | 48/50 | 2/50 | 48/50 | 62.8 | 44 / 6 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=2, mid_5_20b=4, large_20_100b=2, mega_100b_plus=1
Top-10 sparse-data names: PBF (missing quality,revisions; conf=62.8), RMAX (missing quality,revisions; conf=62.8), DINO (missing quality,revisions; conf=62.8), HPE (missing quality,revisions; conf=62.8), HRB (missing quality,revisions; conf=61.9), ABCL (missing quality,revisions; conf=60.0), ZD (missing quality,revisions; conf=62.8), MPC (missing quality,revisions; conf=62.8), GH (missing quality,revisions,valuation; conf=59.1), DELL (missing quality,revisions; conf=61.9)
