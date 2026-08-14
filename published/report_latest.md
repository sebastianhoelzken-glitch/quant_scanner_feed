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

- **EUROPE:** 90.8/100
- **OTHER:** 76.8/100
- **US:** 87.3/100

## Main multi-horizon ranking

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PBF      | PBF      | US       |                7.36 |             92.25 |         86.98 |         92.47 |          94.65 |        92.03 |          nan    |            nan    |             88.02 |         6.98 |             62.84 | medium             |               -0.43 |                   nan |                  nan |
|      2 | RNG      | RNG      | US       |                4.65 |             88.67 |         91.61 |         91.27 |          86.07 |        78.39 |          nan    |            nan    |             69.37 |         7.05 |             61.93 | short              |              nan    |                   nan |                  nan |
|      3 | RMAX     | RMAX     | US       |                0.6  |             86.51 |         87.38 |         89.27 |          84.18 |        85.65 |          nan    |            nan    |             89.63 |         7.08 |             62.84 | swing              |               16.92 |                   nan |                  nan |
|      4 | HPE      | HPE      | US       |               67.18 |             86.2  |         84.27 |         92.08 |          88.12 |        73.51 |          nan    |            nan    |             57.09 |         6.71 |             62.84 | swing              |                0.96 |                   nan |                  nan |
|      5 | DINO     | DINO     | US       |               14.39 |             85.96 |         79.91 |         86.57 |          88.42 |        85.36 |          nan    |            nan    |             80.3  |         3.96 |             62.84 | medium             |                2.73 |                   nan |                  nan |
|      6 | ABCL     | ABCL     | US       |                3.02 |             85.95 |         90.32 |         95.5  |          81.59 |        64.32 |          nan    |            nan    |             46.1  |         8.99 |             60    | swing              |                2.13 |                   nan |                  nan |
|      7 | HRB      | HRB      | US       |                5.91 |             85.54 |         89.48 |         92.8  |          78.86 |        81.59 |          nan    |            nan    |             91.36 |         6.92 |             61.93 | swing              |                2.26 |                   nan |                  nan |
|      8 | MPC      | MPC      | US       |               86.25 |             85.01 |         83.65 |         89.02 |          86.36 |        76.4  |          nan    |            nan    |             64.59 |         3.88 |             62.84 | swing              |              nan    |                   nan |                  nan |
|      9 | ZD       | ZD       | US       |                1.64 |             84.54 |         67.12 |         83.38 |          87.05 |        85.7  |          nan    |            nan    |             86.09 |         5.21 |             62.84 | medium             |                0.48 |                   nan |                  nan |
|     10 | GH       | GH       | US       |               18.23 |             84.32 |         47.11 |         78.91 |          89.73 |        95.65 |          nan    |            nan    |            nan    |         6.73 |             59.09 | long               |              nan    |                   nan |                  nan |
|     11 | AKER.OL  | Aker ASA | EUROPE   |                9.75 |             83.67 |         84.16 |         77.26 |          83.96 |        83.39 |           98.84 |             82.87 |             63.77 |         3.36 |             73.32 | short              |               12.67 |                   nan |                  nan |
|     12 | DELL     | DELL     | US       |              274.03 |             83.65 |         83.51 |         91.59 |          83.8  |        59.24 |          nan    |            nan    |             31.68 |         7.62 |             61.93 | swing              |                0.05 |                   nan |                  nan |
|     13 | CAKE     | CAKE     | US       |                4.88 |             83.41 |         89.43 |         90.37 |          77.39 |        53.14 |          nan    |            nan    |             26.29 |         5.57 |             62.84 | swing              |                1.99 |                   nan |                  nan |
|     14 | GPN      | GPN      | US       |               21.28 |             83.14 |         83.28 |         84.16 |          73.07 |        83    |          nan    |            nan    |             94.99 |         5.53 |             62.84 | swing              |                1.03 |                   nan |                  nan |
|     15 | TXG      | TXG      | US       |                6.31 |             83.1  |         87.6  |         89.57 |          78.61 |        44.78 |          nan    |            nan    |              6.75 |         6.92 |             62.84 | swing              |                0.39 |                   nan |                  nan |
|     16 | NWL      | NWL      | US       |                2.3  |             82.52 |         82.63 |         86.85 |          76.93 |        82.41 |          nan    |            nan    |             86.8  |         8.03 |             62.84 | swing              |                2.58 |                   nan |                  nan |
|     17 | OSCR     | OSCR     | US       |                8.74 |             82.32 |         82.09 |         86.95 |          82.55 |        64.61 |          nan    |            nan    |             44.93 |         8.21 |             62.84 | swing              |                8.16 |                   nan |                  nan |
|     18 | AVAH     | AVAH     | US       |                2.32 |             82.16 |         91.11 |         89.85 |          74.47 |        64.09 |          nan    |            nan    |             50.33 |         7.17 |             62.84 | short              |              nan    |                   nan |                  nan |
|     19 | OPRT     | OPRT     | US       |                0.31 |             82.12 |         78.17 |         85.97 |          78.28 |        87.3  |          nan    |            nan    |             97.8  |         7.95 |             62.84 | long               |                3.02 |                   nan |                  nan |
|     20 | REPL     | REPL     | US       |                1.21 |             81.63 |         96.7  |         87.07 |          76.19 |        55.74 |          nan    |            nan    |             26.95 |         9.87 |             60    | short              |                1.15 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.12 |                  77.55 |                    84.13 |                 86.24 |              81.41 |                96.85 |                    3.15 |           95.5  |            nan    |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.75 |                  67.72 |                    75.53 |                 79.01 |              70.72 |                75.96 |                   24.04 |           98.84 |             82.87 |       0.113 |         nan |       nan |        5.28 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|          nan | KYN      | KYN                                                  | US       |                2.17 |                  67.62 |                    73.75 |                 74.78 |              73.34 |                96.25 |                    3.75 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         5.15 |          5.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.48 |                  72.57 |                    72.72 |                 74.72 |              71.81 |                68.27 |                   31.73 |           83.7  |             72.68 |       0.02  |         nan |       nan |        3.98 |         6.07 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ACA.PA   | ACA.PA                                               | EUROPE   |               61.12 |                  65.83 |                    71.23 |                 72.13 |              70.87 |                91.03 |                    8.97 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.13 |         10    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                                                   | US       |               62.63 |                  63.6  |                    70.77 |                 71.97 |              70.3  |                97.07 |                    2.93 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        12.03 |         14.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               15.31 |                  63.24 |                    70.74 |                 72    |              70.24 |                98.27 |                    1.73 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          8.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                 | US       |              215.92 |                  67.87 |                    70.58 |                 71.03 |              70.4  |                80.53 |                   19.47 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  75.52 |                    70.4  |                 69.25 |              72.94 |                71.09 |                   28.91 |           63.82 |             57.67 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BNP.PA   | BNP.PA                                               | EUROPE   |              122.86 |                  66.86 |                    70.39 |                 70.98 |              70.16 |                83.36 |                   16.64 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.54 |          9.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ARCC     | ARCC                                                 | US       |               12.33 |                  64.29 |                    69.64 |                 70.53 |              69.28 |                89.24 |                   10.76 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.28 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                                                | EUROPE   |               20.48 |                  61.6  |                    69.6  |                 70.94 |              69.07 |                98.94 |                    1.06 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.03 |         11.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  71.3  |                    69.45 |                 70.84 |              68.57 |                70.76 |                   29.24 |           85.55 |             45.01 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | CA.PA    | CA.PA                                                | EUROPE   |               11.18 |                  64.45 |                    69.44 |                 70.28 |              69.11 |                87.77 |                   12.23 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.44 |         12.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TRIN     | TRIN                                                 | US       |                1.41 |                  64.63 |                    69.26 |                 70.03 |              68.95 |                86.25 |                   13.75 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.61 |         10.43 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | MTRX     | Matrix Service Company                               | US       |                0.29 |                  74.81 |                    69.19 |                 69.76 |              70.85 |                60.45 |                   39.55 |           71.49 |             61.03 |       0.297 |         nan |       nan |      -46    |        17.14 |        nan    |        1.12 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                                  | US       |              112.67 |                  64.71 |                    68.52 |                 69.15 |              68.26 |                82.46 |                   17.54 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.74 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AIG      | AIG                                                  | US       |               34.63 |                  63.77 |                    68.13 |                 68.86 |              67.84 |                84.13 |                   15.87 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.73 |         13.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  73.16 |                    68.05 |                 67.14 |              67.84 |                62.9  |                   37.1  |           76.09 |             38.43 |       0.192 |         nan |       nan |        1.22 |         4.1  |          3.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              215.27 |                  63.69 |                    67.94 |                 68.65 |              67.66 |                83.51 |                   16.49 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.7  |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.12 |                  77.55 |                    84.13 |                 86.24 |              81.41 |                96.85 |                    3.15 |           95.5  |            nan    |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.75 |                  67.72 |                    75.53 |                 79.01 |              70.72 |                75.96 |                   24.04 |           98.84 |             82.87 |       0.113 |         nan |       nan |        5.28 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|          nan | KYN      | KYN                                                  | US       |                2.17 |                  67.62 |                    73.75 |                 74.78 |              73.34 |                96.25 |                    3.75 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         5.15 |          5.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.48 |                  72.57 |                    72.72 |                 74.72 |              71.81 |                68.27 |                   31.73 |           83.7  |             72.68 |       0.02  |         nan |       nan |        3.98 |         6.07 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ACA.PA   | ACA.PA                                               | EUROPE   |               61.12 |                  65.83 |                    71.23 |                 72.13 |              70.87 |                91.03 |                    8.97 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.13 |         10    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               15.31 |                  63.24 |                    70.74 |                 72    |              70.24 |                98.27 |                    1.73 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          8.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                                                   | US       |               62.63 |                  63.6  |                    70.77 |                 71.97 |              70.3  |                97.07 |                    2.93 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        12.03 |         14.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                 | US       |              215.92 |                  67.87 |                    70.58 |                 71.03 |              70.4  |                80.53 |                   19.47 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BNP.PA   | BNP.PA                                               | EUROPE   |              122.86 |                  66.86 |                    70.39 |                 70.98 |              70.16 |                83.36 |                   16.64 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.54 |          9.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                                                | EUROPE   |               20.48 |                  61.6  |                    69.6  |                 70.94 |              69.07 |                98.94 |                    1.06 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.03 |         11.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  71.3  |                    69.45 |                 70.84 |              68.57 |                70.76 |                   29.24 |           85.55 |             45.01 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | ARCC     | ARCC                                                 | US       |               12.33 |                  64.29 |                    69.64 |                 70.53 |              69.28 |                89.24 |                   10.76 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.28 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CA.PA    | CA.PA                                                | EUROPE   |               11.18 |                  64.45 |                    69.44 |                 70.28 |              69.11 |                87.77 |                   12.23 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.44 |         12.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TRIN     | TRIN                                                 | US       |                1.41 |                  64.63 |                    69.26 |                 70.03 |              68.95 |                86.25 |                   13.75 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.61 |         10.43 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | MTRX     | Matrix Service Company                               | US       |                0.29 |                  74.81 |                    69.19 |                 69.76 |              70.85 |                60.45 |                   39.55 |           71.49 |             61.03 |       0.297 |         nan |       nan |      -46    |        17.14 |        nan    |        1.12 |                 nan |              nan |                  10 |                  0.53 |
|           17 | HMC      | Honda Motor Company, Ltd.                            | OTHER    |               35.41 |                  58.33 |                    65.68 |                 69.27 |              64.39 |                77.67 |                   22.33 |           75    |             84.14 |       0.041 |         nan |       nan |        7.16 |         6.37 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|            4 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  75.52 |                    70.4  |                 69.25 |              72.94 |                71.09 |                   28.91 |           63.82 |             57.67 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                                  | US       |              112.67 |                  64.71 |                    68.52 |                 69.15 |              68.26 |                82.46 |                   17.54 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.74 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AIG      | AIG                                                  | US       |               34.63 |                  63.77 |                    68.13 |                 68.86 |              67.84 |                84.13 |                   15.87 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.73 |         13.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | HOPE     | HOPE                                                 | US       |                1.6  |                  62.29 |                    67.89 |                 68.82 |              67.52 |                88.4  |                   11.6  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.16 |         14.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | ALL      | The Allstate Corporation                             | US       |               57.12 |                     0.05 |    -0.02 |      0.05 |                  73.72 |                        66.56 |         58.83 |         64.39 |          61.89 |        56.05 |           69.27 |             63.05 |         3    |
|               2 | LLY      | Eli Lilly and Company                                | US       |              909.38 |                     0.04 |    -0    |      0    |                  64.17 |                        65.04 |         50.85 |         56.66 |          63.75 |        63.71 |           89.44 |             61.32 |         4.06 |
|               3 | AMZN     | Amazon.com, Inc.                                     | US       |             2448.02 |                     0.08 |    -0.04 |      0.06 |                  70.87 |                        64.96 |         57.94 |         55.31 |          60.53 |        59.84 |           78.99 |             63.72 |         5.63 |
|               4 | MSFT     | Microsoft Corporation                                | US       |             3178.69 |                     0.02 |    -0.01 |      0.26 |                  52.5  |                        63.88 |         70.62 |         63.04 |          53.68 |        51.66 |           58.17 |             60.37 |         5.57 |
|               5 | WKC      | World Kinect Corporation                             | US       |                1.6  |                     0.1  |    -0.01 |     -0.01 |                  43.77 |                        62.77 |         52.2  |         67.2  |          69.64 |        65.52 |           58.38 |             72.87 |         4.83 |
|               6 | GOLD     | Gold.com, Inc.                                       | US       |                1.1  |                     0.02 |     0.01 |      0.15 |                  42.92 |                        62.33 |         67.25 |         54.01 |          55.24 |        52.41 |           48.23 |             84.13 |         5.54 |
|               7 | AVGO     | Broadcom Inc.                                        | US       |             1615.59 |                     0.08 |    -0.08 |      0.06 |                  78.27 |                        61.46 |         45.86 |         47.79 |          58.89 |        61    |           79.84 |             65.7  |         6.04 |
|               8 | LNC      | Lincoln National Corporation                         | US       |                7.52 |                     0.03 |    -0.01 |      0.08 |                  60.68 |                        60.7  |         66.28 |         65.95 |          57.12 |        56.7  |           44.78 |             63.34 |         4.52 |
|               9 | GSL      | Global Ship Lease Inc New                            | OTHER    |                1.31 |                     0.05 |    -0.01 |      0.05 |                  70.66 |                        59.51 |         57.16 |         53.18 |          60.96 |        67.58 |           73.91 |             36.99 |         3.6  |
|              10 | CION     | CION Investment Corporation                          | US       |                0.32 |                     0.03 |    -0.01 |      0.22 |                  60.04 |                        59.21 |         68.14 |         52.69 |          44.14 |        48.31 |           36.04 |             59.47 |         6.13 |
|              11 | CLW      | Clearwater Paper Corporation                         | US       |                0.3  |                     0.08 |    -0.08 |      0.34 |                  78.34 |                        58.49 |         65.9  |         63.3  |          45.68 |        36.49 |           21.17 |             63.71 |         6.75 |
|              12 | YPF      | YPF Sociedad Anónima                                 | OTHER    |               16.96 |                     0.05 |     0.02 |      0.01 |                  60.84 |                        58.41 |         49.5  |         58.93 |          64.8  |        62.55 |           49.49 |             66.16 |         4.89 |
|              13 | V        | Visa Inc.                                            | US       |              587.49 |                     0.02 |     0.01 |      0.02 |                  44.34 |                        58.35 |         56.2  |         57.44 |          53.59 |        49.4  |           69.69 |             60.3  |         2.75 |
|              14 | HTD      | John Hancock Tax-Advantaged Dividend Income Fund     | US       |                0.78 |                     0.02 |     0.01 |     -0    |                  43.93 |                        58.18 |         52.74 |         55.97 |          57.34 |        56.66 |           56.29 |             82.33 |         1.81 |
|              15 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                     0.06 |    -0.02 |     -0.03 |                  71.8  |                        57.91 |         43.26 |         46.55 |          56.15 |        66.15 |           85.55 |             45.01 |         3.95 |
|              16 | GTN      | Gray Media, Inc.                                     | US       |                0.46 |                     0.03 |    -0.03 |      0.32 |                  62.22 |                        57.78 |         64.17 |         54.42 |          47.24 |        52.6  |           50.12 |             42.25 |         5.67 |
|              17 | GOOGL    | Alphabet Inc.                                        | US       |             3655.43 |                     0.08 |    -0.02 |     -0    |                  59.75 |                        57.62 |         45.29 |         43.26 |          57.34 |        56.23 |           76.52 |             71.38 |         4.74 |
|              18 | MTRX     | Matrix Service Company                               | US       |                0.29 |                     0.07 |     0    |     -0.02 |                  60.49 |                        56.51 |         46.94 |         47.96 |          55.84 |        64.13 |           71.49 |             61.03 |         5.82 |
|              19 | CII      | BlackRock Enhanced Large Cap Core Fund, Inc.         | US       |                0.87 |                     0.02 |    -0.01 |      0    |                  50.15 |                        56.32 |         53.08 |         52.17 |          55.19 |        48.82 |           49.54 |             82.33 |         2.71 |
|              20 | VOR      | Vor Biopharma Inc.                                   | US       |                1.18 |                     0.03 |    -0.03 |      0.27 |                  62.17 |                        55.67 |         59.98 |         62.38 |          48.35 |        38.53 |           34.84 |             54.59 |         8.63 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                  | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation    | US       |             4712.46 |             64.02 |         66.05 |         55.93 |          62.26 |        65.78 |           93.04 |             61.58 |             36.89 |         5.45 |             89.54 | short              |               12.43 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation    | US       |                1.88 |             59.6  |         57.97 |         60.69 |          58.51 |        65.94 |           59.01 |             49.81 |             84.19 |         8.33 |             85.47 | long               |               -6.82 |                   nan |                  nan |
|    nan | ATHM     | Autohome Inc.         | OTHER    |                2.26 |             41.3  |         49.93 |         46.95 |          35.65 |        33.01 |           28.42 |             26.09 |             37.89 |         6    |             78.55 | short              |              nan    |                   nan |                  nan |
|    nan | JKS      | JKS                   | US       |                0.76 |             39.12 |         46.27 |         28.4  |          32.19 |        46.06 |          nan    |            nan    |             47.22 |         7.15 |             58.41 | short              |                1.3  |                   nan |                  nan |
|    nan | FINV     | FinVolution Group     | OTHER    |                0.89 |             38.25 |         25.67 |         34.24 |          42.27 |        53.76 |           47.52 |             48.73 |             79.71 |         6.11 |             78.58 | long               |                2.69 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.   | OTHER    |                1.29 |             38.14 |         28.42 |         35.21 |          41.07 |        53.91 |           44.85 |             43.24 |             88.7  |         7.08 |             78.43 | long               |                3.79 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation     | OTHER    |                1.63 |             36.17 |         31.87 |         30.26 |          40.46 |        57.57 |           68.95 |             25.42 |             77.25 |         4.72 |             81.52 | long               |               -1.31 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.   | OTHER    |                0.89 |             32.35 |         29.97 |         21.45 |          34.74 |        44.08 |           59.91 |             19.83 |             37    |         8.98 |             77.55 | long               |               -7.8  |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.          | OTHER    |               10.4  |             26.45 |         28.85 |         22.71 |          24.84 |        28.07 |           29.19 |             38.93 |             30.07 |         6.76 |             76.61 | short              |               -0.33 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp. | OTHER    |                0.86 |             26.34 |         52.82 |         23.21 |          22.26 |        29.48 |           22.97 |             28.42 |             50    |         7.63 |             75.24 | short              |               -7.05 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
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
- Event watch (otherwise eligible): **10**
- Final eligible: **706**
- Eligible change vs previous stored run: **+9**

Top exclusion categories:
- liquidity: 232
- price: 167
- market_cap: 147
- data_confidence: 23
- price_history: 23
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AVGO | 473 | 8 | 7 | 8 | 2 | value,pullback,quality_value |
| AKER.OL | 11 | 2 |  | 2 | 1 | value,quality_value |
| PARR | 57 | 3 |  | 3 | 1 | value,quality_value |
| BION.SW | 73 | 1 |  | 1 | 1 | value,quality_value |
| MAGN | 482 | 10 | 21 | 10 | 1 | value,quality_value |
| MTRX | 498 | 6 | 18 | 5 | 1 | value,quality_value |
| IRS | 503 | 5 | 15 | 4 | 1 | value,quality_value |
| MOMO | 583 | 4 | 26 | 7 | 1 | value,quality_value |
| PBF | 1 |  |  |  | 1 | main |
| RNG | 2 |  |  |  | 1 | main |
| RMAX | 3 |  |  |  | 1 | main |
| HPE | 4 |  |  |  | 1 | main |
| DINO | 5 |  |  |  | 1 | main |
| ABCL | 6 |  |  |  | 1 | main |
| HRB | 7 |  |  |  | 1 | main |

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
| 1 | BION.SW | value+pullback | 72.91 | 77.55 | 43.79 | 95.50 |  | 96.85 | 75.11 |
| 2 | AVGO | value+pullback | 71.72 | 59.62 | 78.27 | 79.84 | 65.70 | 78.58 | 53.34 |
| 3 | IRS | value+pullback | 70.83 | 71.30 | 71.80 | 85.55 | 45.01 | 70.76 | 51.35 |
| 4 | MOMO | value+pullback | 69.97 | 75.52 | 71.01 | 63.82 | 57.67 | 71.09 | 45.65 |
| 5 | GSL | value+pullback | 68.07 | 69.62 | 70.66 | 73.91 | 36.99 | 73.67 | 59.06 |
| 6 | MTRX | value+pullback | 66.48 | 74.81 | 60.49 | 71.49 | 61.03 | 60.45 | 51.90 |
| 7 | VOLV-B.ST | value+pullback | 63.63 | 72.97 | 65.36 | 50.75 | 60.72 | 58.60 | 52.60 |
| 8 | MAGN | value+pullback | 62.89 | 70.22 | 47.38 | 60.00 | 73.14 | 68.31 | 52.80 |
| 9 | PBR-A | value+pullback | 61.77 | 72.64 | 65.72 | 51.81 | 58.93 | 49.42 | 52.37 |
| 10 | ALL-PH | value+pullback | 61.09 | 60.73 | 65.08 | 69.27 | 41.31 | 60.39 | 43.79 |
| 11 | YPF | value+pullback | 61.01 | 72.62 | 60.84 | 49.49 | 66.16 | 49.84 | 60.74 |
| 12 | BYD | value+pullback | 60.21 | 60.13 | 54.03 | 84.06 | 37.78 | 61.37 | 49.96 |
| 13 | BHF | value+pullback | 60.07 | 68.63 | 55.64 | 53.12 | 44.92 | 65.58 | 44.03 |
| 14 | MFA | value+pullback | 59.67 | 57.89 | 53.52 | 80.97 | 37.53 | 65.12 | 45.41 |
| 15 | WKC | value+pullback | 59.54 | 63.73 | 43.77 | 58.38 | 72.87 | 67.20 | 66.36 |
| 16 | AKER.OL | value | 58.62 | 67.72 | 30.95 | 98.84 | 82.87 | 75.96 | 83.67 |
| 17 | AF.PA | value+pullback | 58.07 | 67.98 | 78.48 | 39.08 |  | 35.96 | 48.15 |
| 18 | NOMD | value+pullback | 57.37 | 55.72 | 68.62 | 50.90 | 49.96 | 54.36 | 49.77 |
| 19 | ONIT | value+pullback | 56.94 | 72.94 | 58.20 | 54.29 | 43.43 | 40.12 | 44.82 |
| 20 | MSFT | value+pullback | 56.67 | 62.10 | 52.50 | 58.17 | 60.37 | 50.75 | 58.36 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 0/10 | 0/10 | 9/10 | 0/10 | 10/10 | 62.8 | 10 / 0 |
| Top 25 | 1/25 | 1/25 | 24/25 | 1/25 | 24/25 | 62.8 | 24 / 1 |
| Top 50 | 1/50 | 1/50 | 49/50 | 1/50 | 49/50 | 62.8 | 46 / 4 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=4, large_20_100b=2
Top-10 sparse-data names: PBF (missing quality,revisions; conf=62.8), RNG (missing quality,revisions; conf=61.9), RMAX (missing quality,revisions; conf=62.8), HPE (missing quality,revisions; conf=62.8), DINO (missing quality,revisions; conf=62.8), ABCL (missing quality,revisions; conf=60.0), HRB (missing quality,revisions; conf=61.9), MPC (missing quality,revisions; conf=62.8), ZD (missing quality,revisions; conf=62.8), GH (missing quality,revisions,valuation; conf=59.1)
