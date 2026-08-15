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

- **EUROPE:** 91.2/100
- **OTHER:** 77.0/100
- **US:** 87.4/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PBF       | PBF       | US       |                7.36 |             93.12 |         87.29 |         92.92 |          95.18 |        93.31 |             nan |               nan |             90.15 |         6.94 |             62.84 | medium             |                0.5  |                   nan |                  nan |
|      2 | RMAX      | RMAX      | US       |                0.6  |             86.84 |         87.19 |         89.06 |          84.47 |        86.48 |             nan |               nan |             91.02 |         7.03 |             62.84 | swing              |               -0.04 |                   nan |                  nan |
|      3 | DINO      | DINO      | US       |               14.39 |             86.48 |         79.59 |         86.4  |          88.72 |        86.57 |             nan |               nan |             82.49 |         3.87 |             62.84 | medium             |                0.12 |                   nan |                  nan |
|      4 | UMAC      | UMAC      | US       |                1.47 |             86.25 |         89.87 |         93.47 |          82.63 |        64.53 |             nan |               nan |             42.68 |         9.07 |             60    | swing              |                2.09 |                   nan |                  nan |
|      5 | HPE       | HPE       | US       |               67.18 |             86.22 |         84.16 |         92.04 |          88.28 |        74    |             nan |               nan |             57.99 |         6.69 |             62.84 | swing              |                0.02 |                   nan |                  nan |
|      6 | HRB       | HRB       | US       |                5.91 |             86.09 |         89.33 |         92.76 |          79.37 |        82.84 |             nan |               nan |             93.41 |         6.85 |             61.93 | swing              |                0.17 |                   nan |                  nan |
|      7 | ABCL      | ABCL      | US       |                3.02 |             85.88 |         90.23 |         95.49 |          81.52 |        64.26 |             nan |               nan |             46.1  |         9    |             60    | swing              |               -0.1  |                   nan |                  nan |
|      8 | ZD        | ZD        | US       |                1.64 |             85.05 |         67.49 |         83.39 |          87.28 |        86.72 |             nan |               nan |             88.06 |         5.16 |             62.84 | medium             |               -0.01 |                   nan |                  nan |
|      9 | MPC       | MPC       | US       |               86.25 |             84.79 |         83.22 |         88.77 |          86.36 |        76.65 |             nan |               nan |             65.15 |         3.8  |             62.84 | swing              |               -0.23 |                   nan |                  nan |
|     10 | GH        | GH        | US       |               18.23 |             84.26 |         47.25 |         78.87 |          89.65 |        95.58 |             nan |               nan |            nan    |         6.68 |             59.09 | long               |               -0.14 |                   nan |                  nan |
|     11 | DELL      | DELL      | US       |              274.03 |             83.88 |         83.38 |         91.85 |          84.37 |        60.64 |             nan |               nan |             34.07 |         7.61 |             61.93 | swing              |                0.24 |                   nan |                  nan |
|     12 | MGTX      | MGTX      | US       |                1.12 |             83.85 |         68.46 |         81.34 |          86.84 |        86.37 |             nan |               nan |            nan    |         5.93 |             59.09 | medium             |              nan    |                   nan |                  nan |
|     13 | GPN       | GPN       | US       |               21.28 |             83.58 |         83.14 |         84.01 |          73.57 |        84.07 |             nan |               nan |             96.71 |         5.47 |             62.84 | long               |                0.06 |                   nan |                  nan |
|     14 | CAKE      | CAKE      | US       |                4.88 |             83.53 |         89.34 |         90.48 |          77.72 |        54.15 |             nan |               nan |             28.13 |         5.52 |             62.84 | swing              |                0.13 |                   nan |                  nan |
|     15 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.73 |             83.51 |         78.47 |         80.24 |          86.77 |        95.04 |             nan |               nan |             99.81 |         3.23 |             60    | long               |               -0.68 |                   nan |                  nan |
|     16 | TXG       | TXG       | US       |                6.31 |             83.04 |         87.46 |         89.48 |          78.61 |        44.75 |             nan |               nan |              6.67 |         6.9  |             62.84 | swing              |               -0.01 |                   nan |                  nan |
|     17 | NWL       | NWL       | US       |                2.3  |             82.97 |         82.49 |         86.8  |          77.32 |        83.46 |             nan |               nan |             88.53 |         8.01 |             62.84 | swing              |                0.14 |                   nan |                  nan |
|     18 | ANRO      | ANRO      | US       |                1.09 |             82.35 |         83.46 |         84.96 |          81.24 |        61.99 |             nan |               nan |             38.29 |         7.1  |             60    | swing              |                0.98 |                   nan |                  nan |
|     19 | OSCR      | OSCR      | US       |                8.74 |             82.24 |         81.91 |         86.76 |          82.58 |        64.92 |             nan |               nan |             45.58 |         8.2  |             62.84 | swing              |               -0.05 |                   nan |                  nan |
|     20 | OPRT      | OPRT      | US       |                0.31 |             82.19 |         78.15 |         85.89 |          78.49 |        87.76 |             nan |               nan |             98.49 |         7.96 |             62.84 | long               |               -0.15 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | VOW3.DE  | Volkswagen AG                                        | EUROPE   |               36.96 |                  80.21 |                    75.95 |                 74.09 |              78.53 |                71.84 |                   28.16 |           64.44 |            nan    |       0.382 |         nan |       nan |       13.78 |         3.13 |          7.07 |        0.68 |                 nan |              nan |                  11 |                  0.58 |
|            2 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.12 |                  72.71 |                    75.71 |                 78.5  |              74.33 |                89.6  |                   10.4  |           94.26 |             58.53 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.62 |                  73.82 |                    75.65 |                 78.2  |              74.88 |                81.97 |                   18.03 |           88.88 |             69.77 |       0.171 |         nan |       nan |        4.32 |         2.93 |          5.46 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.27 |                    73.66 |                 73.4  |              72.88 |                74.82 |                   25.18 |           86.96 |             37.79 |       0.617 |         nan |       nan |        1.48 |         4.1  |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ACA.PA   | ACA.PA                                               | EUROPE   |               61.12 |                  68.19 |                    73.14 |                 73.96 |              72.81 |                91.3  |                    8.7  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.13 |         10    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.75 |                  62.68 |                    72.35 |                 76.36 |              66.79 |                76.04 |                   23.96 |           99.19 |             79.69 |       0.113 |         nan |       nan |        5.32 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            6 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.48 |                  72.12 |                    72.17 |                 73.9  |              71.62 |                69.59 |                   30.41 |           81.06 |             71.61 |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | NN.AS    | NN.AS                                                | EUROPE   |               20.48 |                  64.37 |                    71.78 |                 73.02 |              71.29 |                98.94 |                    1.06 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.03 |         11.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               15.31 |                  64.53 |                    71.78 |                 72.99 |              71.29 |                98.36 |                    1.64 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          8.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BNP.PA   | BNP.PA                                               | EUROPE   |              122.86 |                  68.13 |                    71.58 |                 72.16 |              71.35 |                84.23 |                   15.77 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.54 |          9.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  76.49 |                    70.86 |                 69.57 |              73.46 |                71.26 |                   28.74 |           64.51 |             55.59 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                                                 | US       |              215.86 |                  67.84 |                    70.8  |                 71.29 |              70.6  |                81.66 |                   18.34 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PRU      | PRU                                                  | US       |               37.3  |                  67.46 |                    70.63 |                 71.16 |              70.42 |                82.28 |                   17.72 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.5  |         11.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              215.21 |                  66.9  |                    70.62 |                 71.24 |              70.38 |                84.27 |                   15.73 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.7  |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | 0Q2N.IL  | K+S Aktiengesellschaft                               | OTHER    |                2.84 |                  69.34 |                    69.89 |                 69.58 |              70.5  |                75.14 |                   24.86 |           66.69 |            nan    |       0.261 |         nan |       nan |        1.54 |       nan    |          2.65 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | ARCC     | ARCC                                                 | US       |               12.33 |                  64.44 |                    69.81 |                 70.71 |              69.45 |                89.5  |                   10.5  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.28 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ADAM     | ADAM                                                 | US       |                0.79 |                  67.05 |                    69.8  |                 70.26 |              69.62 |                79.9  |                   20.1  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.24 |          6.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  71.21 |                    69.45 |                 70.78 |              68.62 |                71.8  |                   28.2  |           85.32 |             44.25 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|           10 | IHS      | IHS Holding Limited                                  | OTHER    |                2.44 |                  73.77 |                    69.06 |                 69.23 |              72.7  |                62.52 |                   37.48 |           56.64 |             83.28 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                                  | US       |              112.67 |                  64.61 |                    68.57 |                 69.23 |              68.31 |                83.08 |                   16.92 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.12 |                  72.71 |                    75.71 |                 78.5  |              74.33 |                89.6  |                   10.4  |           94.26 |             58.53 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.62 |                  73.82 |                    75.65 |                 78.2  |              74.88 |                81.97 |                   18.03 |           88.88 |             69.77 |       0.171 |         nan |       nan |        4.32 |         2.93 |          5.46 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.75 |                  62.68 |                    72.35 |                 76.36 |              66.79 |                76.04 |                   23.96 |           99.19 |             79.69 |       0.113 |         nan |       nan |        5.32 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            1 | VOW3.DE  | Volkswagen AG                                        | EUROPE   |               36.96 |                  80.21 |                    75.95 |                 74.09 |              78.53 |                71.84 |                   28.16 |           64.44 |            nan    |       0.382 |         nan |       nan |       13.78 |         3.13 |          7.07 |        0.68 |                 nan |              nan |                  11 |                  0.58 |
|          nan | ACA.PA   | ACA.PA                                               | EUROPE   |               61.12 |                  68.19 |                    73.14 |                 73.96 |              72.81 |                91.3  |                    8.7  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.13 |         10    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.48 |                  72.12 |                    72.17 |                 73.9  |              71.62 |                69.59 |                   30.41 |           81.06 |             71.61 |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.27 |                    73.66 |                 73.4  |              72.88 |                74.82 |                   25.18 |           86.96 |             37.79 |       0.617 |         nan |       nan |        1.48 |         4.1  |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | NN.AS    | NN.AS                                                | EUROPE   |               20.48 |                  64.37 |                    71.78 |                 73.02 |              71.29 |                98.94 |                    1.06 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.03 |         11.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               15.31 |                  64.53 |                    71.78 |                 72.99 |              71.29 |                98.36 |                    1.64 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          8.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BNP.PA   | BNP.PA                                               | EUROPE   |              122.86 |                  68.13 |                    71.58 |                 72.16 |              71.35 |                84.23 |                   15.77 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.54 |          9.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                 | US       |              215.86 |                  67.84 |                    70.8  |                 71.29 |              70.6  |                81.66 |                   18.34 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              215.21 |                  66.9  |                    70.62 |                 71.24 |              70.38 |                84.27 |                   15.73 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.7  |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PRU      | PRU                                                  | US       |               37.3  |                  67.46 |                    70.63 |                 71.16 |              70.42 |                82.28 |                   17.72 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.5  |         11.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  71.21 |                    69.45 |                 70.78 |              68.62 |                71.8  |                   28.2  |           85.32 |             44.25 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | ARCC     | ARCC                                                 | US       |               12.33 |                  64.44 |                    69.81 |                 70.71 |              69.45 |                89.5  |                   10.5  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.28 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ADAM     | ADAM                                                 | US       |                0.79 |                  67.05 |                    69.8  |                 70.26 |              69.62 |                79.9  |                   20.1  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.24 |          6.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | 0Q2N.IL  | K+S Aktiengesellschaft                               | OTHER    |                2.84 |                  69.34 |                    69.89 |                 69.58 |              70.5  |                75.14 |                   24.86 |           66.69 |            nan    |       0.261 |         nan |       nan |        1.54 |       nan    |          2.65 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  76.49 |                    70.86 |                 69.57 |              73.46 |                71.26 |                   28.74 |           64.51 |             55.59 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                                  | US       |              112.67 |                  64.61 |                    68.57 |                 69.23 |              68.31 |                83.08 |                   16.92 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | IHS      | IHS Holding Limited                                  | OTHER    |                2.44 |                  73.77 |                    69.06 |                 69.23 |              72.7  |                62.52 |                   37.48 |           56.64 |             83.28 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:-----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | INDU-C.ST | AB Industrivärden (publ)                             | EUROPE   |               20.37 |                     0.08 |    -0.06 |     -0    |                  74.54 |                        69.18 |         45.63 |         58.79 |          67.38 |        66.74 |           83.27 |             79.69 |         2.43 |
|               2 | INDU-A.ST | AB Industrivärden (publ)                             | EUROPE   |               20.46 |                     0.08 |    -0.06 |     -0.01 |                  73.26 |                        68.21 |         40.84 |         57.23 |          66.19 |        64.04 |           83.27 |             79.69 |         2.56 |
|               3 | IRWD      | Ironwood Pharmaceuticals, Inc.                       | US       |                0.62 |                     0.02 |    -0    |      0.12 |                  52.87 |                        67.89 |         63.44 |         57.88 |          69.64 |        80.85 |           88.88 |             69.77 |         6.44 |
|               4 | MSFT      | Microsoft Corporation                                | US       |             3178.69 |                     0.02 |    -0.01 |      0.26 |                  52.5  |                        66.26 |         72.73 |         66.04 |          55.94 |        52.24 |           60.78 |             65.76 |         5.6  |
|               5 | ALL       | The Allstate Corporation                             | US       |               57.12 |                     0.05 |    -0.02 |      0.05 |                  73.72 |                        66.04 |         58.97 |         64.18 |          61.42 |        55.39 |           67.81 |             62.18 |         2.99 |
|               6 | AMZN      | Amazon.com, Inc.                                     | US       |             2448.02 |                     0.08 |    -0.04 |      0.06 |                  70.87 |                        65.38 |         58.27 |         55.62 |          60.83 |        60.05 |           80.86 |             62.97 |         5.58 |
|               7 | LLY       | Eli Lilly and Company                                | US       |              909.38 |                     0.04 |    -0    |      0    |                  62.9  |                        63.52 |         50.78 |         56.46 |          62.25 |        60.78 |           80.13 |             65.49 |         4.12 |
|               8 | WKC       | World Kinect Corporation                             | US       |                1.6  |                     0.1  |    -0.01 |     -0.01 |                  43.77 |                        62.66 |         52.42 |         67.45 |          69.17 |        64.14 |           56.82 |             73.4  |         4.81 |
|               9 | AVGO      | Broadcom Inc.                                        | US       |             1615.59 |                     0.08 |    -0.08 |      0.06 |                  78.27 |                        62.58 |         47.15 |         49.25 |          59.84 |        61.43 |           82.97 |             64.17 |         6.04 |
|              10 | GOLD      | Gold.com, Inc.                                       | US       |                1.1  |                     0.02 |     0.01 |      0.15 |                  42.92 |                        62.26 |         67.28 |         53.94 |          55.17 |        52.43 |           48.4  |             83.34 |         5.64 |
|              11 | CLW       | Clearwater Paper Corporation                         | US       |                0.3  |                     0.08 |    -0.08 |      0.34 |                  78.34 |                        60.08 |         64.34 |         60.89 |          46.72 |        40.69 |           33.96 |             62.45 |         6.77 |
|              12 | GAIN      | Gladstone Investment Corporatio                      | US       |                0.56 |                     0.03 |    -0.02 |     -0.01 |                  61.9  |                        60.01 |         52.23 |         55.23 |          58.18 |        53.77 |           64.83 |             67.61 |         3.12 |
|              13 | LNC       | Lincoln National Corporation                         | US       |                7.52 |                     0.03 |    -0.01 |      0.08 |                  60.68 |                        59.92 |         65.93 |         65.23 |          56.35 |        55.98 |           43.09 |             61.55 |         4.56 |
|              14 | V         | Visa Inc.                                            | US       |              587.49 |                     0.02 |     0.01 |      0.02 |                  44.34 |                        59.09 |         56.94 |         58.18 |          54.18 |        49.45 |           68.95 |             63.7  |         2.83 |
|              15 | GSL       | Global Ship Lease Inc New                            | OTHER    |                1.31 |                     0.05 |    -0.01 |      0.05 |                  70.66 |                        59    |         57.55 |         53.84 |          60.97 |        67.79 |           70.81 |             36.4  |         3.64 |
|              16 | CION      | CION Investment Corporation                          | US       |                0.32 |                     0.02 |     0    |      0.23 |                  48.34 |                        57.91 |         69.93 |         53.26 |          43.99 |        47.67 |           34.77 |             58.27 |         6.17 |
|              17 | GTN       | Gray Media, Inc.                                     | US       |                0.46 |                     0.03 |    -0.03 |      0.32 |                  62.22 |                        57.66 |         64.74 |         55.45 |          48.05 |        53.94 |           48.38 |             41.86 |         5.74 |
|              18 | GOOGL     | Alphabet Inc.                                        | US       |             3655.43 |                     0.08 |    -0.02 |     -0    |                  59.75 |                        57.63 |         45.79 |         44.19 |          57.95 |        57.22 |           76.3  |             70.11 |         4.74 |
|              19 | HTD       | John Hancock Tax-Advantaged Dividend Income Fund     | US       |                0.78 |                     0.02 |     0.01 |     -0    |                  43.93 |                        57.37 |         52.14 |         55.31 |          56.79 |        56.49 |           56.19 |             79.21 |         1.87 |
|              20 | IRS       | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                     0.06 |    -0.02 |     -0.03 |                  71.8  |                        57.07 |         42.11 |         45.19 |          55.13 |        65.12 |           85.32 |             44.25 |         3.96 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4712.46 |             63.99 |         67.03 |         56.98 |          62.57 |        65.42 |           94.57 |             59.36 |             30.53 |         5.42 |             89.53 | short              |               -0.26 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.88 |             59.61 |         58.6  |         60.62 |          56.66 |        61.46 |           54.97 |             49.2  |             71.96 |         8.32 |             85.47 | long               |               -0.98 |                   nan |                  nan |
|    nan | JOYY     | JOYY Inc.                    | OTHER    |                3.18 |             53.33 |         52.15 |         58.56 |          54.51 |        48.34 |           48.68 |             49.76 |             32.12 |         4.75 |             81.91 | swing              |              nan    |                   nan |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.      | US       |                3.38 |             46.04 |         35    |         42.66 |          49.43 |        62.46 |           67.44 |             45.51 |             78.89 |         7.44 |             87.57 | long               |                1.06 |                   nan |                  nan |
|    nan | ATHM     | Autohome Inc.                | OTHER    |                2.26 |             42.58 |         51.22 |         48.08 |          37.07 |        34.85 |           32.54 |             25.76 |             36.59 |         5.9  |             78.55 | short              |                1.46 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.89 |             38.44 |         25.68 |         34.3  |          42.58 |        54.17 |           50.26 |             47.34 |             77.74 |         6.16 |             78.58 | long               |                0.39 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.29 |             38.19 |         28.4  |         35.19 |          41.19 |        53.98 |           47.64 |             41.32 |             85.58 |         7.16 |             78.43 | long               |                0.29 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             37.19 |         32.47 |         31.5  |          41.92 |        59.47 |           70.69 |             25.54 |             79.41 |         4.74 |             81.52 | long               |                0.53 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.76 |             35.73 |         39.93 |         24.59 |          31.54 |        40.22 |           44.83 |             37.83 |             49.64 |         6.98 |             75.4  | long               |                2.43 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.89 |             34.04 |         30.48 |         22.55 |          37.61 |        49.27 |           68.02 |             20.01 |             44.44 |         9.01 |             77.55 | long               |                1.01 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             26.37 |         52.84 |         22.98 |          22.23 |        29.77 |           24.32 |             27.32 |             50    |         7.69 |             75.24 | short              |                0.78 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.4  |             22.9  |         28.09 |         21.72 |          22.3  |        23.51 |           22.35 |             38.29 |             23.38 |         6.79 |             76.61 | short              |                2.41 |                   nan |                  nan |

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
- liquidity: 231
- price: 173
- market_cap: 159
- data_confidence: 23
- price_history: 22
- asset_type: 1
- delisted: 1
- duplicate_listing: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| IRWD | 239 | 3 | 3 | 2 | 2 | value,pullback,quality_value |
| AKER.OL | 22 | 5 |  | 3 | 1 | value,quality_value |
| PARR | 71 | 6 |  | 5 | 1 | value,quality_value |
| BION.SW | 170 | 2 |  | 1 | 1 | value,quality_value |
| IHS | 418 | 10 |  | 10 | 1 | value,quality_value |
| 0Q2N.IL | 487 | 8 |  | 8 | 1 | value,quality_value |
| IRS | 541 | 9 | 20 | 7 | 1 | value,quality_value |
| MOMO | 584 | 7 | 31 | 9 | 1 | value,quality_value |
| STNE | 657 | 4 |  | 6 | 1 | value,quality_value |
| VOW3.DE | 675 | 1 |  | 4 | 1 | value,quality_value |
| PBF | 1 |  |  |  | 1 | main |
| RMAX | 2 |  |  |  | 1 | main |
| DINO | 3 |  |  |  | 1 | main |
| UMAC | 4 |  |  |  | 1 | main |
| HPE | 5 |  |  |  | 1 | main |

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
| 1 | AVGO | value+pullback | 72.15 | 59.62 | 78.27 | 82.97 | 64.17 | 79.18 | 54.54 |
| 2 | IRWD | value+pullback | 72.07 | 73.82 | 52.87 | 88.88 | 69.77 | 81.97 | 66.54 |
| 3 | VOW3.DE | value+pullback | 71.18 | 80.21 | 72.32 | 64.44 |  | 71.84 | 38.12 |
| 4 | IRS | value+pullback | 70.90 | 71.21 | 71.80 | 85.32 | 44.25 | 71.80 | 50.16 |
| 5 | MOMO | value+pullback | 70.18 | 76.49 | 71.01 | 64.51 | 55.59 | 71.26 | 46.38 |
| 6 | GSL | value+pullback | 67.89 | 71.46 | 70.66 | 70.81 | 36.40 | 72.65 | 59.26 |
| 7 | 0P6O.IL | value+pullback | 67.20 | 63.11 | 70.96 | 74.71 |  | 71.63 | 41.49 |
| 8 | 0Q2N.IL | value+pullback | 65.15 | 69.34 | 57.28 | 66.69 |  | 75.14 | 53.58 |
| 9 | VOLV-B.ST | value+pullback | 63.79 | 67.88 | 65.36 | 59.27 | 59.00 | 61.50 | 53.76 |
| 10 | SDF.DE | value+pullback | 63.25 | 57.54 | 54.92 | 80.57 | 55.81 | 72.94 | 51.34 |
| 11 | PBR-A | value+pullback | 61.97 | 73.63 | 65.72 | 54.53 | 57.87 | 47.45 | 53.16 |
| 12 | MAGN | value+pullback | 61.91 | 67.52 | 47.38 | 60.00 | 71.84 | 68.13 | 52.25 |
| 13 | 1VOW3.MI | value+pullback | 61.54 | 63.55 | 64.72 | 64.44 | 35.49 | 65.40 | 39.54 |
| 14 | CNXC | value+pullback | 60.73 | 83.95 | 70.58 | 45.38 | 32.02 | 39.43 | 39.91 |
| 15 | ALL-PH | value+pullback | 60.60 | 61.97 | 65.08 | 67.81 | 39.29 | 58.19 | 43.30 |
| 16 | AF.PA | value+pullback | 60.41 | 66.50 | 77.15 | 47.91 | 56.31 | 41.80 | 51.27 |
| 17 | BHF | value+pullback | 60.03 | 70.28 | 55.64 | 51.85 | 43.26 | 64.65 | 43.67 |
| 18 | BION.SW | value | 59.72 | 72.71 | 40.38 | 94.26 | 58.53 | 89.60 | 70.00 |
| 19 | MFA | value+pullback | 59.15 | 57.89 | 53.52 | 79.81 | 36.20 | 64.04 | 45.11 |
| 20 | WKC | value+pullback | 58.65 | 60.34 | 43.77 | 56.82 | 73.40 | 68.70 | 65.79 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 0/10 | 0/10 | 9/10 | 0/10 | 10/10 | 62.8 | 10 / 0 |
| Top 25 | 1/25 | 1/25 | 23/25 | 1/25 | 24/25 | 62.8 | 24 / 1 |
| Top 50 | 2/50 | 2/50 | 48/50 | 2/50 | 48/50 | 62.8 | 44 / 6 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=4, large_20_100b=2
Top-10 sparse-data names: PBF (missing quality,revisions; conf=62.8), RMAX (missing quality,revisions; conf=62.8), DINO (missing quality,revisions; conf=62.8), UMAC (missing quality,revisions; conf=60.0), HPE (missing quality,revisions; conf=62.8), HRB (missing quality,revisions; conf=61.9), ABCL (missing quality,revisions; conf=60.0), ZD (missing quality,revisions; conf=62.8), MPC (missing quality,revisions; conf=62.8), GH (missing quality,revisions,valuation; conf=59.1)
