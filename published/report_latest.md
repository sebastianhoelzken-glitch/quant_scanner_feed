# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-14

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

- **EUROPE:** 90.1/100
- **OTHER:** 73.1/100
- **US:** 88.8/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PBF       | PBF       | US       |                7.64 |             93.72 |         92.92 |         94.81 |          94.53 |        92.73 |          nan    |            nan    |             90.84 |         7.18 |             62.84 | swing              |                1.04 |                   nan |                  nan |
|      2 | HPE       | HPE       | US       |               68.7  |             86.05 |         84.61 |         93.3  |          87.49 |        72.93 |          nan    |            nan    |             57.65 |         6.93 |             62.84 | swing              |                0.81 |                   nan |                  nan |
|      3 | ZD        | ZD        | US       |                1.66 |             85.73 |         74.6  |         85.06 |          86.69 |        86.41 |          nan    |            nan    |             88.67 |         5.52 |             62.84 | medium             |                1.67 |                   nan |                  nan |
|      4 | DINO      | DINO      | US       |               14.17 |             85.34 |         78.94 |         84.11 |          87.62 |        86.56 |          nan    |            nan    |             84.9  |         4.21 |             62.84 | medium             |                2.1  |                   nan |                  nan |
|      5 | MPC       | MPC       | US       |               86.8  |             85.11 |         85.41 |         88.38 |          84.81 |        74.9  |          nan    |            nan    |             63.88 |         4.16 |             62.84 | swing              |              nan    |                   nan |                  nan |
|      6 | DK        | DK        | US       |                3.63 |             84.96 |         85.52 |         89    |          84.4  |        67.23 |          nan    |            nan    |             48.28 |         6.69 |             62.84 | swing              |              nan    |                   nan |                  nan |
|      7 | AKER.OL   | Aker ASA  | EUROPE   |                9.61 |             84.6  |         87.9  |         80.04 |          85.01 |        84.18 |           98.84 |             80.49 |             63.77 |         3.67 |             73.32 | short              |               13.59 |                   nan |                  nan |
|      8 | ABCL      | ABCL      | US       |                2.92 |             84.54 |         89.9  |         94.17 |          79.18 |        62.78 |          nan    |            nan    |             46.58 |         9.1  |             60    | swing              |                0.71 |                   nan |                  nan |
|      9 | DELL      | DELL      | US       |              277.12 |             84.51 |         85.66 |         92.02 |          83.36 |        59.47 |          nan    |            nan    |             33.7  |         7.77 |             61.93 | swing              |                0.91 |                   nan |                  nan |
|     10 | HRB       | HRB       | US       |                5.86 |             84.39 |         87.93 |         89.95 |          76.89 |        80.85 |          nan    |            nan    |             93.65 |         7.18 |             61.93 | swing              |                1.11 |                   nan |                  nan |
|     11 | TWST      | TWST      | US       |                6.81 |             83.94 |         89.57 |         91.3  |          78.32 |        46.43 |          nan    |            nan    |             11.14 |         6.87 |             60    | swing              |                0.63 |                   nan |                  nan |
|     12 | VLO       | VLO       | US       |               85.63 |             83.77 |         82.48 |         87.49 |          85.06 |        75.13 |          nan    |            nan    |             63.55 |         3.54 |             62.84 | swing              |                0.62 |                   nan |                  nan |
|     13 | TXG       | TXG       | US       |                6.57 |             83.5  |         89.43 |         90.28 |          77.58 |        43.53 |          nan    |            nan    |              6.2  |         7.1  |             62.84 | swing              |                0.79 |                   nan |                  nan |
|     14 | GPN       | GPN       | US       |               21.76 |             83.27 |         83.27 |         85.6  |          72.79 |        83.28 |          nan    |            nan    |             96.46 |         5.81 |             62.84 | swing              |                1.16 |                   nan |                  nan |
|     15 | QNST      | QNST      | US       |                1.03 |             82.8  |         89.93 |         87.86 |          77.74 |        71.93 |          nan    |            nan    |             68.73 |         7.94 |             62.84 | short              |                0.97 |                   nan |                  nan |
|     16 | PSX       | PSX       | US       |               80.89 |             82.56 |         82.94 |         85.4  |          82.18 |        76.68 |          nan    |            nan    |             69.26 |         3.55 |             62.84 | swing              |              nan    |                   nan |                  nan |
|     17 | CAKE      | CAKE      | US       |                4.83 |             82.15 |         88.15 |         88.7  |          76.14 |        53.51 |          nan    |            nan    |             29.23 |         5.86 |             62.84 | swing              |                0.73 |                   nan |                  nan |
|     18 | EC        | EC        | US       |               30.69 |             82.13 |         66.18 |         80.69 |          84.51 |        83.57 |          nan    |            nan    |             80.3  |         4.48 |             62.84 | medium             |              nan    |                   nan |                  nan |
|     19 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.69 |             81.92 |         75.97 |         78.58 |          85.25 |        92.91 |          nan    |            nan    |             98.65 |         3.59 |             60    | long               |                0.08 |                   nan |                  nan |
|     20 | CRSR      | CRSR      | US       |                1.26 |             81.62 |         86.52 |         89.05 |          76.72 |        65.15 |          nan    |            nan    |             56.09 |         8.91 |             62.84 | swing              |                0.78 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                           | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc. | US       |                0.58 |                  75.21 |                    76.6  |                 79.31 |              75.62 |                80.16 |                   19.84 |           91.54 |             70.34 |       0.181 |         nan |       nan |        4.17 |         2.77 |          5.16 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BION.SW  | BB Biotech AG                  | EUROPE   |                3.16 |                  73.33 |                    75.73 |                 78.29 |              74.8  |                88.99 |                   11.01 |           91.89 |             59.79 |       0.834 |         nan |       nan |      nan    |       -81.64 |          2.19 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | AKER.OL  | Aker ASA                       | EUROPE   |                9.61 |                  67.72 |                    75.16 |                 78.54 |              70.35 |                75.2  |                   24.8  |           98.84 |             80.49 |       0.115 |         nan |       nan |        5.28 |        54.32 |          3.74 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|          nan | ACA.PA   | ACA.PA                         | EUROPE   |               60.82 |                  67.45 |                    72.19 |                 72.99 |              71.88 |                89.6  |                   10.4  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.09 |          9.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | MOMO     | Hello Group Inc.               | OTHER    |                0.74 |                  76.41 |                    71.98 |                 70.98 |              74.39 |                76.24 |                   23.76 |           66.72 |             56.52 |       0.574 |         nan |       nan |       -5.14 |         5.36 |          8.58 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            5 | SM       | SM Energy Company              | US       |                6.69 |                  73.62 |                    71.12 |                 70.66 |              70.08 |                65.57 |                   34.43 |           79.13 |             52.75 |       0.191 |         nan |       nan |        4.53 |         4.41 |          5.75 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BNP.PA   | BNP.PA                         | EUROPE   |              123.19 |                  68.16 |                    70.98 |                 71.45 |              70.79 |                81.31 |                   18.69 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          9.72 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                          | EUROPE   |               20.35 |                  63.12 |                    70.79 |                 72.07 |              70.28 |                98.94 |                    1.06 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.97 |         11.54 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                           | US       |              215.4  |                  68.64 |                    70.75 |                 71.1  |              70.61 |                78.49 |                   21.51 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.2  |          9.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                         | EUROPE   |               15.14 |                  63.42 |                    70.74 |                 71.96 |              70.25 |                97.56 |                    2.44 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.47 |          7.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                       | EUROPE   |              213.26 |                  67.06 |                    70.1  |                 70.61 |              69.9  |                81.25 |                   18.75 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.62 |          9.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CA.PA    | CA.PA                          | EUROPE   |               11.13 |                  65.17 |                    69.61 |                 70.35 |              69.32 |                85.88 |                   14.12 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.41 |         12.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ADAM     | ADAM                           | US       |                0.79 |                  67.71 |                    69.52 |                 69.82 |              69.4  |                76.15 |                   23.85 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.22 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                            | US       |              114.54 |                  66.34 |                    69.29 |                 69.78 |              69.09 |                80.1  |                   19.9  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.86 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | MAGN     | Magnera Corporation            | US       |                0.38 |                  73.82 |                    69.23 |                 69.3  |              72.65 |                68.03 |                   31.97 |           60    |             72.5  |       0.531 |         nan |       nan |        6.4  |         7.47 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|          nan | ET       | ET                             | US       |               62    |                  61.6  |                    69.13 |                 70.38 |              68.63 |                96.74 |                    3.26 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        11.86 |         14.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | STNE     | StoneCo Ltd.                   | OTHER    |                2.16 |                  70.98 |                    69.01 |                 68.71 |              68.03 |                66.51 |                   33.49 |           77.48 |             49.5  |       0.179 |         nan |       nan |        1.21 |         4.37 |          3.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | HMC      | Honda Motor Company, Ltd.      | OTHER    |               35.11 |                  60.33 |                    68.68 |                 72.96 |              66.48 |                81.45 |                   18.55 |           84.06 |             83.83 |       0.041 |         nan |       nan |        7.16 |         6.29 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|            9 | AMCX     | AMC Global Media Inc.          | US       |                0.43 |                  73.8  |                    68.48 |                 66.27 |              73.81 |                72.46 |                   27.54 |           42.97 |             76.33 |       2.025 |         nan |       nan |        7.02 |         4.34 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|          nan | PBR-A    | PBR-A                          | US       |               95.78 |                  69.38 |                    68.45 |                 68.29 |              68.51 |                65.01 |                   34.99 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         6.56 |          4.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.58 |                  75.21 |                    76.6  |                 79.31 |              75.62 |                80.16 |                   19.84 |           91.54 |             70.34 |       0.181 |         nan |       nan |        4.17 |         2.77 |          5.16 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.61 |                  67.72 |                    75.16 |                 78.54 |              70.35 |                75.2  |                   24.8  |           98.84 |             80.49 |       0.115 |         nan |       nan |        5.28 |        54.32 |          3.74 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            2 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.16 |                  73.33 |                    75.73 |                 78.29 |              74.8  |                88.99 |                   11.01 |           91.89 |             59.79 |       0.834 |         nan |       nan |      nan    |       -81.64 |          2.19 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | ACA.PA   | ACA.PA                                               | EUROPE   |               60.82 |                  67.45 |                    72.19 |                 72.99 |              71.88 |                89.6  |                   10.4  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.09 |          9.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | HMC      | Honda Motor Company, Ltd.                            | OTHER    |               35.11 |                  60.33 |                    68.68 |                 72.96 |              66.48 |                81.45 |                   18.55 |           84.06 |             83.83 |       0.041 |         nan |       nan |        7.16 |         6.29 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|          nan | NN.AS    | NN.AS                                                | EUROPE   |               20.35 |                  63.12 |                    70.79 |                 72.07 |              70.28 |                98.94 |                    1.06 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.97 |         11.54 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               15.14 |                  63.42 |                    70.74 |                 71.96 |              70.25 |                97.56 |                    2.44 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.47 |          7.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | XNET     | Xunlei Limited                                       | OTHER    |                0.28 |                  59.74 |                    68.4  |                 71.58 |              64.53 |                75.1  |                   24.9  |           85.71 |             80    |     nan     |         nan |       nan |        3.54 |       nan    |          0.38 |        2.58 |                 nan |              nan |                   6 |                  0.32 |
|          nan | BNP.PA   | BNP.PA                                               | EUROPE   |              123.19 |                  68.16 |                    70.98 |                 71.45 |              70.79 |                81.31 |                   18.69 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          9.72 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                 | US       |              215.4  |                  68.64 |                    70.75 |                 71.1  |              70.61 |                78.49 |                   21.51 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.2  |          9.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.74 |                  76.41 |                    71.98 |                 70.98 |              74.39 |                76.24 |                   23.76 |           66.72 |             56.52 |       0.574 |         nan |       nan |       -5.14 |         5.36 |          8.58 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            5 | SM       | SM Energy Company                                    | US       |                6.69 |                  73.62 |                    71.12 |                 70.66 |              70.08 |                65.57 |                   34.43 |           79.13 |             52.75 |       0.191 |         nan |       nan |        4.53 |         4.41 |          5.75 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              213.26 |                  67.06 |                    70.1  |                 70.61 |              69.9  |                81.25 |                   18.75 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.62 |          9.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                                                   | US       |               62    |                  61.6  |                    69.13 |                 70.38 |              68.63 |                96.74 |                    3.26 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        11.86 |         14.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CA.PA    | CA.PA                                                | EUROPE   |               11.13 |                  65.17 |                    69.61 |                 70.35 |              69.32 |                85.88 |                   14.12 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.41 |         12.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ADAM     | ADAM                                                 | US       |                0.79 |                  67.71 |                    69.52 |                 69.82 |              69.4  |                76.15 |                   23.85 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.22 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                                  | US       |              114.54 |                  66.34 |                    69.29 |                 69.78 |              69.09 |                80.1  |                   19.9  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.86 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  69.21 |                    68.18 |                 69.63 |              67.11 |                71.47 |                   28.53 |           84.58 |             44.17 |     nan     |         nan |       nan |        3.93 |       162.2  |          4.73 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            6 | MAGN     | Magnera Corporation                                  | US       |                0.38 |                  73.82 |                    69.23 |                 69.3  |              72.65 |                68.03 |                   31.97 |           60    |             72.5  |       0.531 |         nan |       nan |        6.4  |         7.47 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|          nan | AED.BR   | AED.BR                                               | EUROPE   |                5.68 |                  62.16 |                    68.25 |                 69.27 |              67.85 |                90.59 |                    9.41 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        12.35 |          5.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                              | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | INDU-C.ST | AB Industrivärden (publ)          | EUROPE   |               20.56 |                     0.07 |    -0.05 |      0    |                  79.69 |                        70.53 |         46.97 |         59.92 |          68.12 |        67.1  |           82.71 |             80.49 |         2.51 |
|               2 | INDU-A.ST | AB Industrivärden (publ)          | EUROPE   |               20.66 |                     0.07 |    -0.06 |     -0.01 |                  78.19 |                        69.46 |         42.59 |         58.24 |          66.79 |        63.88 |           82.71 |             80.49 |         2.67 |
|               3 | HMC       | Honda Motor Company, Ltd.         | OTHER    |               35.11 |                     0.02 |     0.02 |      0.08 |                  44.39 |                        68.98 |         65.82 |         65.86 |          64.51 |        72.59 |           84.06 |             83.83 |         3.86 |
|               4 | ALL       | The Allstate Corporation          | US       |               57.12 |                     0.05 |    -0.05 |      0.08 |                  85.22 |                        68.68 |         60.84 |         65.61 |          62.16 |        56.01 |           68.32 |             62.84 |         3.1  |
|               5 | HRTG      | Heritage Insurance Holdings, Inc. | US       |                0.86 |                     0.06 |    -0.06 |      0.25 |                  86.84 |                        68.19 |         69.7  |         69.57 |          60.48 |        55.7  |           59.63 |             55.9  |         5.99 |
|               6 | AMZN      | Amazon.com, Inc.                  | US       |             2480.28 |                     0.07 |    -0.03 |      0.06 |                  71.35 |                        67.23 |         61.6  |         56.57 |          62.08 |        61.64 |           81.16 |             63.28 |         5.8  |
|               7 | IRWD      | Ironwood Pharmaceuticals, Inc.    | US       |                0.58 |                     0.08 |    -0.04 |      0.05 |                  69.59 |                        66.69 |         53.51 |         54.79 |          70.52 |        82.72 |           91.54 |             70.34 |         6.52 |
|               8 | SLDE      | Slide Insurance Holdings, Inc.    | US       |                2.19 |                     0.02 |     0.01 |      0.05 |                  48.61 |                        65.08 |         65.52 |         66.06 |          65.57 |        62.43 |           76.03 |             63.73 |         5.8  |
|               9 | CLW       | Clearwater Paper Corporation      | US       |                0.31 |                     0.06 |    -0.04 |      0.35 |                  80.37 |                        64.54 |         67.46 |         64.13 |          51.32 |        47.84 |           46.5  |             63.06 |         6.89 |
|              10 | DAC       | Danaos Corporation                | OTHER    |                2.22 |                     0.02 |    -0.02 |      0.08 |                  54.47 |                        64.49 |         66.23 |         63.62 |          67.46 |        66.36 |           74.57 |             55.3  |         3.35 |
|              11 | PKX       | POSCO Holdings Inc.               | OTHER    |               14.84 |                     0.03 |     0.01 |      0.11 |                  53.07 |                        64.19 |         58.25 |         39.41 |          52.89 |        63.91 |           83.88 |             68.88 |         6.16 |
|              12 | AVGO      | Broadcom Inc.                     | US       |             1724.03 |                     0.02 |    -0.01 |      0.12 |                  53.08 |                        64.08 |         61.47 |         55.51 |          61.8  |        62.1  |           78.23 |             64.96 |         6.2  |
|              13 | YPF       | YPF Sociedad Anónima              | OTHER    |               16.82 |                     0.06 |    -0    |      0.02 |                  69.41 |                        63.87 |         51.1  |         61.62 |          67.33 |        64.2  |           64.49 |             65.04 |         5.08 |
|              14 | WKC       | World Kinect Corporation          | US       |                1.65 |                     0.08 |    -0    |      0    |                  57.6  |                        63.02 |         57.51 |         68.5  |          65.98 |        57.43 |           46.33 |             72.4  |         4.98 |
|              15 | LLY       | Eli Lilly and Company             | US       |              935.05 |                     0.02 |     0.01 |      0.03 |                  44.14 |                        62.96 |         60.01 |         60.73 |          64.75 |        62.21 |           84.42 |             60.58 |         4.21 |
|              16 | MSFT      | Microsoft Corporation             | US       |             3199.99 |                     0.02 |    -0.01 |      0.24 |                  49.75 |                        62.88 |         71.05 |         64.75 |          54.45 |        51.86 |           54.76 |             59.61 |         5.77 |
|              17 | DSX       | Diana Shipping Inc.               | OTHER    |                0.27 |                     0.03 |    -0.02 |      0.18 |                  60.85 |                        62.35 |         65.05 |         49.77 |          55.99 |        60.73 |           60.31 |             57.57 |         4.65 |
|              18 | LNC       | Lincoln National Corporation      | US       |                7.52 |                     0.04 |    -0.03 |      0.08 |                  68.13 |                        62.01 |         66.41 |         67.19 |          58.16 |        56.44 |           44.18 |             62.37 |         4.74 |
|              19 | MA        | Mastercard Incorporated           | US       |              430.82 |                     0.02 |    -0.02 |      0.03 |                  52.35 |                        59.75 |         57.09 |         56.8  |          51.67 |        48.83 |           71.6  |             60.23 |         3.26 |
|              20 | GOOGL     | Alphabet Inc.                     | US       |             3673.85 |                     0.08 |    -0.03 |     -0.02 |                  62.88 |                        58.78 |         44.69 |         44.27 |          59.86 |        59.43 |           81.74 |             71.02 |         4.92 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4732.85 |             65.59 |         68.59 |         58.33 |          63.86 |        67.32 |           92.75 |             61.3  |             39.44 |         5.63 |             89.54 | short              |               14    |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.93 |             63.7  |         65.2  |         62.98 |          59.3  |        64.43 |           55.86 |             49.71 |             78.41 |         8.45 |             85.47 | short              |               -2.72 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.02 |             41.01 |         54.05 |         40.47 |          36.21 |        41.55 |           28.96 |             29.94 |             63.09 |         4.56 |             74.95 | short              |               -0.81 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.93 |             39.24 |         29.06 |         35.39 |          43.1  |        54.44 |           50.26 |             48.68 |             77.74 |         6.29 |             78.58 | long               |                3.68 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.32 |             38.07 |         30.53 |         34.77 |          41.37 |        54.11 |           47.64 |             42.66 |             85.58 |         7.21 |             78.43 | long               |                3.72 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.9  |             35.9  |         36.39 |         21.58 |          35.4  |        46.04 |           64.09 |             19.66 |             39.33 |         9.09 |             77.55 | long               |               -4.25 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             35.89 |         30.53 |         29.36 |          41.25 |        58.34 |           72    |             25.9  |             75.22 |         4.96 |             81.52 | long               |               -1.58 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             33.15 |         39.62 |         23.08 |          29.23 |        37.07 |           38.42 |             37.81 |             48.67 |         7.16 |             75.4  | short              |               -4.67 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.88 |             26.29 |         58.69 |         23.73 |          21.77 |        28.84 |           21.62 |             27.76 |             49.43 |         7.84 |             75.24 | short              |               -7.11 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.45 |             24.79 |         27.67 |         22.34 |          23.68 |        25.89 |           24.14 |             38.23 |             27.82 |         6.96 |             76.61 | short              |               -2    |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.93
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.91

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
- Event watch (otherwise eligible): **10**
- Final eligible: **704**
- Eligible change vs previous stored run: **+7**

Top exclusion categories:
- liquidity: 239
- price: 173
- market_cap: 152
- data_confidence: 25
- price_history: 23
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AKER.OL | 7 | 3 |  | 2 | 2 | main,value,quality_value |
| HMC | 229 | 8 | 3 | 4 | 2 | value,pullback,quality_value |
| IRWD | 292 | 1 | 7 | 1 | 2 | value,pullback,quality_value |
| BION.SW | 119 | 2 |  | 3 | 1 | value,quality_value |
| SM | 202 | 5 |  | 7 | 1 | value,quality_value |
| MAGN | 499 | 6 |  | 9 | 1 | value,quality_value |
| XNET | 531 | 10 |  | 5 | 1 | value,quality_value |
| MOMO | 583 | 4 | 29 | 6 | 1 | value,quality_value |
| PBF | 1 |  |  |  | 1 | main |
| HPE | 2 |  |  |  | 1 | main |
| ZD | 3 |  |  |  | 1 | main |
| DINO | 4 |  |  |  | 1 | main |
| MPC | 5 |  |  |  | 1 | main |
| DK | 6 |  |  |  | 1 | main |
| ABCL | 8 |  |  |  | 1 | main |

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
| 1 | IRWD | value+pullback | 76.76 | 75.21 | 69.59 | 91.54 | 70.34 | 80.16 | 62.66 |
| 2 | MOMO | value+pullback | 70.72 | 76.41 | 67.55 | 66.72 | 56.52 | 76.24 | 45.93 |
| 3 | IRS | value+pullback | 69.69 | 69.21 | 70.14 | 84.58 | 44.17 | 71.47 | 49.40 |
| 4 | GSL | value+pullback | 67.39 | 67.53 | 72.25 | 75.00 | 37.08 | 70.58 | 55.51 |
| 5 | STNE | value+pullback | 66.73 | 70.98 | 62.26 | 77.48 | 49.50 | 66.51 | 42.82 |
| 6 | INVA | value+pullback | 66.62 | 58.46 | 71.85 | 80.26 | 39.02 | 75.88 | 41.01 |
| 7 | HMC | value+pullback | 66.48 | 60.33 | 44.39 | 84.06 | 83.83 | 81.45 | 65.84 |
| 8 | VOLV-B.ST | value+pullback | 64.74 | 72.97 | 70.20 | 50.75 | 60.29 | 58.31 | 53.61 |
| 9 | AVGO | value+pullback | 64.40 | 57.79 | 53.08 | 78.23 | 64.96 | 77.82 | 61.63 |
| 10 | PKX | value+pullback | 62.90 | 57.07 | 53.07 | 83.88 | 68.88 | 65.19 | 55.57 |
| 11 | DAC | value+pullback | 62.18 | 56.68 | 54.47 | 74.57 | 55.30 | 74.22 | 66.30 |
| 12 | AF.PA | value+pullback | 61.85 | 67.98 | 85.54 | 39.08 | 61.89 | 40.11 | 52.02 |
| 13 | BHF | value+pullback | 60.96 | 69.36 | 59.95 | 51.65 | 44.61 | 64.80 | 44.32 |
| 14 | ALL-PH | value+pullback | 60.76 | 61.47 | 64.99 | 68.32 | 39.78 | 59.24 | 43.62 |
| 15 | BION.SW | value | 59.56 | 73.33 | 34.40 | 91.89 | 59.79 | 88.99 | 72.15 |
| 16 | AKER.OL | value | 58.23 | 67.72 | 30.95 | 98.84 | 80.49 | 75.20 | 84.60 |
| 17 | MFA | value+pullback | 58.08 | 58.09 | 47.35 | 80.96 | 36.98 | 64.85 | 48.17 |
| 18 | BYD | value+pullback | 58.03 | 57.97 | 53.60 | 77.54 | 37.40 | 59.33 | 47.33 |
| 19 | MAU.PA | value+pullback | 57.78 | 61.88 | 59.93 | 58.70 | 53.08 | 50.61 | 50.80 |
| 20 | LNC | value+pullback | 56.22 | 56.66 | 68.13 | 44.18 | 62.37 | 46.63 | 62.28 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 1/10 | 1/10 | 10/10 | 1/10 | 9/10 | 62.8 | 10 / 0 |
| Top 25 | 1/25 | 1/25 | 25/25 | 1/25 | 24/25 | 62.8 | 23 / 2 |
| Top 50 | 2/50 | 2/50 | 50/50 | 2/50 | 48/50 | 62.8 | 44 / 6 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=4, large_20_100b=2, mega_100b_plus=1
Top-10 sparse-data names: PBF (missing quality,revisions; conf=62.8), HPE (missing quality,revisions; conf=62.8), ZD (missing quality,revisions; conf=62.8), DINO (missing quality,revisions; conf=62.8), MPC (missing quality,revisions; conf=62.8), DK (missing quality,revisions; conf=62.8), ABCL (missing quality,revisions; conf=60.0), DELL (missing quality,revisions; conf=61.9), HRB (missing quality,revisions; conf=61.9)
