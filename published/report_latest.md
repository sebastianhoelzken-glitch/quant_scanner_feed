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
- **OTHER:** 77.9/100
- **US:** 87.3/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PBF       | PBF       | US       |                7.36 |             92.62 |         86.87 |         92.53 |          94.91 |        92.71 |             nan |               nan |             89.19 |         6.97 |             62.84 | medium             |               -0.06 |                   nan |                  nan |
|      2 | RNG       | RNG       | US       |                4.65 |             88.8  |         91.59 |         91.33 |          86.26 |        78.87 |             nan |               nan |             70.21 |         7.02 |             61.93 | short              |              nan    |                   nan |                  nan |
|      3 | RMAX      | RMAX      | US       |                0.6  |             86.88 |         87.2  |         89.44 |          84.63 |        86.56 |             nan |               nan |             91.02 |         7.06 |             62.84 | swing              |               17.29 |                   nan |                  nan |
|      4 | DINO      | DINO      | US       |               14.39 |             86.36 |         79.79 |         86.68 |          88.74 |        86.04 |             nan |               nan |             81.35 |         3.93 |             62.84 | medium             |                3.12 |                   nan |                  nan |
|      5 | HPE       | HPE       | US       |               67.18 |             86.2  |         84.26 |         92.06 |          88.14 |        73.58 |             nan |               nan |             57.26 |         6.71 |             62.84 | swing              |                0.96 |                   nan |                  nan |
|      6 | ABCL      | ABCL      | US       |                3.02 |             85.97 |         90.31 |         95.52 |          81.64 |        64.43 |             nan |               nan |             46.28 |         9    |             60    | swing              |                2.14 |                   nan |                  nan |
|      7 | HRB       | HRB       | US       |                5.91 |             85.91 |         89.48 |         92.92 |          79.22 |        82.35 |             nan |               nan |             92.55 |         6.92 |             61.93 | swing              |                2.63 |                   nan |                  nan |
|      8 | ZD        | ZD        | US       |                1.64 |             85.06 |         66.95 |         83.51 |          87.42 |        86.62 |             nan |               nan |             87.55 |         5.18 |             62.84 | medium             |                1    |                   nan |                  nan |
|      9 | MPC       | MPC       | US       |               86.25 |             85.02 |         83.5  |         89.07 |          86.54 |        76.82 |             nan |               nan |             65.29 |         3.85 |             62.84 | swing              |              nan    |                   nan |                  nan |
|     10 | RBI.VI    | RBI.VI    | EUROPE   |               20.65 |             84.6  |         75.77 |         84.83 |          87.21 |        84.38 |             nan |               nan |             78.54 |         3.61 |             62.84 | medium             |                6.56 |                   nan |                  nan |
|     11 | GH        | GH        | US       |               18.23 |             84.4  |         47.14 |         78.99 |          89.81 |        95.67 |             nan |               nan |            nan    |         6.71 |             59.09 | long               |              nan    |                   nan |                  nan |
|     12 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.73 |             84.19 |         78.43 |         80.97 |          87.4  |        95.63 |             nan |               nan |            100    |         3.3  |             60    | long               |                2.35 |                   nan |                  nan |
|     13 | UMAC      | UMAC      | OTHER    |                1.47 |             84.16 |         89.39 |         91.88 |          78.92 |        55.63 |             nan |               nan |             28.57 |         9.08 |             60    | swing              |                3.79 |                   nan |                  nan |
|     14 | DELL      | DELL      | US       |              274.03 |             83.64 |         83.48 |         91.57 |          83.8  |        59.22 |             nan |               nan |             31.65 |         7.6  |             61.93 | swing              |                0.04 |                   nan |                  nan |
|     15 | GPN       | GPN       | US       |               21.28 |             83.51 |         83.2  |         84.33 |          73.56 |        83.83 |             nan |               nan |             96.18 |         5.51 |             62.84 | swing              |                1.4  |                   nan |                  nan |
|     16 | CAKE      | CAKE      | US       |                4.88 |             83.4  |         89.39 |         90.37 |          77.42 |        53.24 |             nan |               nan |             26.44 |         5.54 |             62.84 | swing              |                1.99 |                   nan |                  nan |
|     17 | TXG       | TXG       | US       |                6.31 |             83.05 |         87.48 |         89.58 |          78.62 |        44.81 |             nan |               nan |              6.79 |         6.91 |             62.84 | swing              |                0.33 |                   nan |                  nan |
|     18 | NWL       | NWL       | US       |                2.3  |             82.84 |         82.47 |         86.99 |          77.37 |        83.2  |             nan |               nan |             88.07 |         8.05 |             62.84 | swing              |                2.89 |                   nan |                  nan |
|     19 | OPRT      | OPRT      | US       |                0.31 |             82.34 |         78.1  |         86.1  |          78.58 |        87.79 |             nan |               nan |             98.52 |         7.96 |             62.84 | long               |                3.24 |                   nan |                  nan |
|     20 | OSCR      | OSCR      | US       |                8.74 |             82.3  |         82    |         86.96 |          82.59 |        64.66 |             nan |               nan |             44.97 |         8.23 |             62.84 | swing              |                8.13 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG              | EUROPE   |                3.12 |                  73.05 |                    76.28 |                 79.22 |              74.8  |                90.14 |                    9.86 |           95.41 |             59.84 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | ACA.PA   | ACA.PA                     | EUROPE   |               61.12 |                  68.44 |                    73.3  |                 74.11 |              72.97 |                91.13 |                    8.87 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.13 |         10    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | MOMO     | Hello Group Inc.           | OTHER    |                0.73 |                  77.26 |                    72.55 |                 71.66 |              74.77 |                75.01 |                   24.99 |           68.72 |             56.4  |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | NN.AS    | NN.AS                      | EUROPE   |               20.48 |                  64.78 |                    72.1  |                 73.32 |              71.61 |                98.94 |                    1.06 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.03 |         11.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | 0QXR.IL  | Stellantis N.V.            | OTHER    |               25.94 |                  73.68 |                    71.93 |                 71.73 |              72.03 |                65.45 |                   34.55 |           71.97 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.71 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BNP.PA   | BNP.PA                     | EUROPE   |              122.86 |                  68.41 |                    71.67 |                 72.21 |              71.45 |                83.62 |                   16.38 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.54 |          9.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                     | EUROPE   |               15.31 |                  64.24 |                    71.55 |                 72.76 |              71.06 |                98.32 |                    1.68 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          8.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | NWL.MI   | NewPrinces S.p.A.          | EUROPE   |                0.68 |                  70.16 |                    71.09 |                 73.1  |              71.23 |                83.4  |                   16.6  |           81.85 |             57.04 |       0.974 |         nan |       nan |        5.32 |      -120.77 |          2.12 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | PARR     | Par Pacific Holdings, Inc. | US       |                3.48 |                  69.04 |                    70.59 |                 72.67 |              69.51 |                69.76 |                   30.24 |           81.06 |             72.5  |       0.02  |         nan |       nan |        3.98 |         6.07 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ET       | ET                         | US       |               62.63 |                  63.32 |                    70.56 |                 71.76 |              70.07 |                97.07 |                    2.93 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        12.03 |         14.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                       | US       |              215.92 |                  67.71 |                    70.51 |                 70.97 |              70.32 |                80.76 |                   19.24 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CA.PA    | CA.PA                      | EUROPE   |               11.18 |                  65.62 |                    70.48 |                 71.29 |              70.16 |                88.29 |                   11.71 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.44 |         12.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                   | EUROPE   |              215.27 |                  66.48 |                    70.17 |                 70.78 |              69.92 |                83.67 |                   16.33 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.7  |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TRIN     | TRIN                       | US       |                1.41 |                  65.14 |                    69.69 |                 70.45 |              69.39 |                86.38 |                   13.62 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.61 |         10.43 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ARCC     | ARCC                       | US       |               12.33 |                  64.15 |                    69.56 |                 70.46 |              69.2  |                89.39 |                   10.61 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.28 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OBDC     | OBDC                       | US       |                5.03 |                  66.1  |                    69.37 |                 69.92 |              69.15 |                81.39 |                   18.61 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.02 |         20.93 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | MTRX     | Matrix Service Company     | US       |                0.29 |                  74.81 |                    69.29 |                 69.89 |              70.94 |                60.55 |                   39.45 |           71.49 |             61.82 |       0.297 |         nan |       nan |      -46    |        17.14 |        nan    |        1.12 |                 nan |              nan |                  10 |                  0.53 |
|            7 | 0P6O.IL  | Volkswagen AG              | OTHER    |               40.88 |                  65.77 |                    69.29 |                 70.61 |              67.51 |                74.43 |                   25.57 |           77.03 |            nan    |       0.423 |         nan |       nan |        7.45 |       nan    |          2.66 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|          nan | ADAM     | ADAM                       | US       |                0.79 |                  65.93 |                    68.78 |                 69.26 |              68.59 |                79.24 |                   20.76 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.24 |          6.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                        | US       |              112.67 |                  64.71 |                    68.54 |                 69.18 |              68.29 |                82.61 |                   17.39 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.74 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG              | EUROPE   |                3.12 |                  73.05 |                    76.28 |                 79.22 |              74.8  |                90.14 |                    9.86 |           95.41 |             59.84 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | ACA.PA   | ACA.PA                     | EUROPE   |               61.12 |                  68.44 |                    73.3  |                 74.11 |              72.97 |                91.13 |                    8.87 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.13 |         10    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                      | EUROPE   |               20.48 |                  64.78 |                    72.1  |                 73.32 |              71.61 |                98.94 |                    1.06 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.03 |         11.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | NWL.MI   | NewPrinces S.p.A.          | EUROPE   |                0.68 |                  70.16 |                    71.09 |                 73.1  |              71.23 |                83.4  |                   16.6  |           81.85 |             57.04 |       0.974 |         nan |       nan |        5.32 |      -120.77 |          2.12 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | AGS.BR   | AGS.BR                     | EUROPE   |               15.31 |                  64.24 |                    71.55 |                 72.76 |              71.06 |                98.32 |                    1.68 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          8.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PARR     | Par Pacific Holdings, Inc. | US       |                3.48 |                  69.04 |                    70.59 |                 72.67 |              69.51 |                69.76 |                   30.24 |           81.06 |             72.5  |       0.02  |         nan |       nan |        3.98 |         6.07 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BNP.PA   | BNP.PA                     | EUROPE   |              122.86 |                  68.41 |                    71.67 |                 72.21 |              71.45 |                83.62 |                   16.38 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.54 |          9.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | AKER.OL  | Aker ASA                   | EUROPE   |                9.75 |                  54.11 |                    66.78 |                 71.84 |              60.09 |                73.08 |                   26.92 |           98.28 |             79.73 |       0.113 |         nan |       nan |        5.32 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|          nan | ET       | ET                         | US       |               62.63 |                  63.32 |                    70.56 |                 71.76 |              70.07 |                97.07 |                    2.93 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        12.03 |         14.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | 0QXR.IL  | Stellantis N.V.            | OTHER    |               25.94 |                  73.68 |                    71.93 |                 71.73 |              72.03 |                65.45 |                   34.55 |           71.97 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.71 |                 nan |              nan |                   9 |                  0.47 |
|            2 | MOMO     | Hello Group Inc.           | OTHER    |                0.73 |                  77.26 |                    72.55 |                 71.66 |              74.77 |                75.01 |                   24.99 |           68.72 |             56.4  |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | CA.PA    | CA.PA                      | EUROPE   |               11.18 |                  65.62 |                    70.48 |                 71.29 |              70.16 |                88.29 |                   11.71 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.44 |         12.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                       | US       |              215.92 |                  67.71 |                    70.51 |                 70.97 |              70.32 |                80.76 |                   19.24 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                   | EUROPE   |              215.27 |                  66.48 |                    70.17 |                 70.78 |              69.92 |                83.67 |                   16.33 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.7  |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | 0P6O.IL  | Volkswagen AG              | OTHER    |               40.88 |                  65.77 |                    69.29 |                 70.61 |              67.51 |                74.43 |                   25.57 |           77.03 |            nan    |       0.423 |         nan |       nan |        7.45 |       nan    |          2.66 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|          nan | ARCC     | ARCC                       | US       |               12.33 |                  64.15 |                    69.56 |                 70.46 |              69.2  |                89.39 |                   10.61 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.28 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TRIN     | TRIN                       | US       |                1.41 |                  65.14 |                    69.69 |                 70.45 |              69.39 |                86.38 |                   13.62 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.61 |         10.43 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OBDC     | OBDC                       | US       |                5.03 |                  66.1  |                    69.37 |                 69.92 |              69.15 |                81.39 |                   18.61 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.02 |         20.93 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | MTRX     | Matrix Service Company     | US       |                0.29 |                  74.81 |                    69.29 |                 69.89 |              70.94 |                60.55 |                   39.45 |           71.49 |             61.82 |       0.297 |         nan |       nan |      -46    |        17.14 |        nan    |        1.12 |                 nan |              nan |                  10 |                  0.53 |
|           16 | PKX      | POSCO Holdings Inc.        | OTHER    |               15.32 |                  61.22 |                    65.94 |                 69.55 |              63.27 |                68.16 |                   31.84 |           85.55 |             69.26 |     nan     |         nan |       nan |        3.7  |        10.16 |         29.3  |        0.89 |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                                             | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:-------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | INDU-C.ST | AB Industrivärden (publ)                         | EUROPE   |               20.37 |                     0.08 |    -0.06 |     -0    |                  74.54 |                        69.62 |         46.1  |         59.39 |          67.94 |        67.16 |           83.96 |             79.73 |         2.41 |
|               2 | INDU-A.ST | AB Industrivärden (publ)                         | EUROPE   |               20.46 |                     0.08 |    -0.06 |     -0.01 |                  73.26 |                        68.64 |         41.45 |         57.8  |          66.59 |        64.03 |           83.96 |             79.73 |         2.56 |
|               3 | BION.SW   | BB Biotech AG                                    | EUROPE   |                3.12 |                     0.02 |     0.02 |      0.07 |                  43.79 |                        67.89 |         66.54 |         65.64 |          74.02 |        81.3  |           95.41 |             59.84 |         2.21 |
|               4 | ALL       | The Allstate Corporation                         | US       |               57.12 |                     0.05 |    -0.02 |      0.05 |                  73.72 |                        66.36 |         58.42 |         64.11 |          61.58 |        55.45 |           68.74 |             63.33 |         3    |
|               5 | AMZN      | Amazon.com, Inc.                                 | US       |             2448.02 |                     0.08 |    -0.04 |      0.06 |                  70.87 |                        65.93 |         58.67 |         56.68 |          62.4  |        62.62 |           81.99 |             63.76 |         5.63 |
|               6 | LLY       | Eli Lilly and Company                            | US       |              909.38 |                     0.04 |    -0    |      0    |                  64.17 |                        65.06 |         50.72 |         56.72 |          63.81 |        63.7  |           89.44 |             61.25 |         4.13 |
|               7 | MSFT      | Microsoft Corporation                            | US       |             3178.69 |                     0.02 |    -0.01 |      0.26 |                  52.5  |                        63.81 |         70.52 |         63.15 |          53.78 |        51.69 |           58.17 |             60.25 |         5.64 |
|               8 | CLW       | Clearwater Paper Corporation                     | US       |                0.3  |                     0.08 |    -0.08 |      0.34 |                  78.34 |                        63.67 |         67.42 |         65.66 |          52.18 |        47.56 |           43.5  |             63.37 |         6.77 |
|               9 | WKC       | World Kinect Corporation                         | US       |                1.6  |                     0.1  |    -0.01 |     -0.01 |                  43.77 |                        62.27 |         52.11 |         66.93 |          68.8  |        63.81 |           56.82 |             72.52 |         4.86 |
|              10 | GOLD      | Gold.com, Inc.                                   | US       |                1.1  |                     0.02 |     0.01 |      0.15 |                  42.92 |                        62.12 |         66.89 |         53.59 |          54.87 |        51.98 |           48.33 |             83.78 |         5.66 |
|              11 | AVGO      | Broadcom Inc.                                    | US       |             1615.59 |                     0.08 |    -0.08 |      0.06 |                  78.27 |                        61.4  |         45.75 |         47.79 |          58.89 |        60.94 |           79.84 |             65.27 |         6.08 |
|              12 | LNC       | Lincoln National Corporation                     | US       |                7.52 |                     0.03 |    -0.01 |      0.08 |                  60.68 |                        60.5  |         65.87 |         65.5  |          56.75 |        56.02 |           44.98 |             63.1  |         4.55 |
|              13 | GSL       | Global Ship Lease Inc New                        | OTHER    |                1.31 |                     0.05 |    -0.01 |      0.05 |                  70.66 |                        59.68 |         56.88 |         52.78 |          60.58 |        66.54 |           75.31 |             37.2  |         3.68 |
|              14 | YPF       | YPF Sociedad Anónima                             | OTHER    |               16.96 |                     0.05 |     0.02 |      0.01 |                  60.84 |                        59.33 |         49.62 |         59.24 |          65.74 |        64.01 |           53.32 |             66.12 |         4.83 |
|              15 | CION      | CION Investment Corporation                      | US       |                0.32 |                     0.03 |    -0.01 |      0.22 |                  60.04 |                        58.72 |         67.76 |         52.06 |          43.19 |        46.72 |           34.95 |             58.96 |         6.19 |
|              16 | GTN       | Gray Media, Inc.                                 | US       |                0.46 |                     0.03 |    -0.03 |      0.32 |                  62.22 |                        58.34 |         64.37 |         54.79 |          47.86 |        53.34 |           52.25 |             42.49 |         5.72 |
|              17 | V         | Visa Inc.                                        | US       |              587.49 |                     0.02 |     0.01 |      0.02 |                  44.34 |                        58.21 |         55.92 |         57.2  |          53.37 |        48.88 |           69.31 |             60.64 |         2.87 |
|              18 | GOOGL     | Alphabet Inc.                                    | US       |             3655.43 |                     0.08 |    -0.02 |     -0    |                  59.75 |                        57.57 |         45.32 |         43.43 |          57.44 |        56.36 |           76.52 |             70.94 |         4.76 |
|              19 | HTD       | John Hancock Tax-Advantaged Dividend Income Fund | US       |                0.78 |                     0.02 |     0.01 |     -0    |                  43.93 |                        57.44 |         52.11 |         55.01 |          56.75 |        56.51 |           57.28 |             79.24 |         1.87 |
|              20 | NESN.SW   | Nestlé S.A.                                      | EUROPE   |              221.91 |                     0.06 |    -0    |     -0.05 |                  68.03 |                        57.2  |         43.43 |         46    |          53.68 |        53.39 |           71.89 |             64.1  |         2.76 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4712.46 |             64.26 |         65.95 |         56.11 |          62.56 |        66.03 |           93.48 |             62    |             36.89 |         5.44 |             89.54 | long               |               12.67 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.88 |             60.58 |         58.9  |         62.03 |          59.14 |        65.59 |           58.69 |             50.82 |             79.87 |         8.33 |             85.47 | long               |               -5.84 |                   nan |                  nan |
|    nan | ATHM     | Autohome Inc.                | OTHER    |                2.26 |             41.12 |         49.61 |         46.7  |          35.54 |        32.62 |           29.17 |             26.53 |             36.11 |         6    |             78.55 | short              |              nan    |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.89 |             38.04 |         25.36 |         33.88 |          42.2  |        53.84 |           49.1  |             48.32 |             78.76 |         6.17 |             78.58 | long               |                2.48 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.29 |             37.9  |         28.21 |         34.86 |          40.94 |        53.78 |           46.72 |             42.44 |             86.54 |         7.18 |             78.43 | long               |                3.55 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             36.67 |         31.96 |         30.45 |          41.38 |        58.91 |           73.25 |             26.26 |             76.43 |         4.73 |             81.52 | long               |               -0.81 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.76 |             33.3  |         39.07 |         23.85 |          29.69 |        36.92 |           38.42 |             38.6  |             47.04 |         7.02 |             75.4  | short              |               -4.52 |                   nan |                  nan |
|    nan | AT1.DE   | Aroundtown SA                | EUROPE   |                2.21 |             33.28 |         31.85 |         27.29 |          34.72 |        44.57 |           54    |             37.41 |             51.43 |         5.44 |             75.53 | long               |               -3.58 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.89 |             33.04 |         29.98 |         21.73 |          36.09 |        46.63 |           64.09 |             20.3  |             40.86 |         9    |             77.55 | long               |               -7.11 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             25.6  |         52.39 |         22.68 |          21.53 |        28.52 |           21.62 |             28.13 |             49.43 |         7.69 |             75.24 | short              |               -7.8  |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.4  |             20.49 |         27.27 |         20.45 |          20.32 |        20.53 |           16.55 |             39.36 |             22.78 |         6.81 |             76.61 | short              |               -6.29 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- VTYL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)

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
- Excluded by hard/data filters: **283**
- Event watch (otherwise eligible): **11**
- Final eligible: **706**
- Eligible change vs previous stored run: **+9**

Top exclusion categories:
- liquidity: 230
- price: 166
- market_cap: 155
- data_confidence: 20
- price_history: 20
- duplicate_listing: 4
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| BION.SW | 169 | 1 | 3 | 1 | 2 | value,pullback,quality_value |
| PARR | 86 | 5 |  | 3 | 1 | value,quality_value |
| MTRX | 513 | 6 | 22 | 8 | 1 | value,quality_value |
| NWL.MI | 529 | 4 |  | 2 | 1 | value,quality_value |
| 0QXR.IL | 559 | 3 |  | 5 | 1 | value,quality_value |
| IRS | 562 | 9 | 28 | 10 | 1 | value,quality_value |
| MOMO | 597 | 2 | 33 | 6 | 1 | value,quality_value |
| 0P6O.IL | 661 | 7 |  | 7 | 1 | value,quality_value |
| PBF | 1 |  |  |  | 1 | main |
| RNG | 2 |  |  |  | 1 | main |
| RMAX | 3 |  |  |  | 1 | main |
| DINO | 4 |  |  |  | 1 | main |
| HPE | 5 |  |  |  | 1 | main |
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
| 1 | MOMO | value+pullback | 71.88 | 77.26 | 71.01 | 68.72 | 56.40 | 75.01 | 45.83 |
| 2 | AVGO | value+pullback | 71.65 | 59.62 | 78.27 | 79.84 | 65.27 | 78.46 | 53.34 |
| 3 | BION.SW | value+pullback | 71.18 | 73.05 | 43.79 | 95.41 | 59.84 | 90.14 | 70.28 |
| 4 | IRS | value+pullback | 69.39 | 69.62 | 71.80 | 81.69 | 44.63 | 69.19 | 48.89 |
| 5 | 0P6O.IL | value+pullback | 68.91 | 65.77 | 70.96 | 77.03 |  | 74.43 | 40.62 |
| 6 | MTRX | value+pullback | 66.58 | 74.81 | 60.49 | 71.49 | 61.82 | 60.55 | 51.80 |
| 7 | GSL | value+pullback | 66.36 | 64.29 | 70.66 | 75.31 | 37.20 | 71.95 | 58.73 |
| 8 | VOW3.DE | value+pullback | 66.19 | 72.40 | 72.32 | 65.24 | 38.50 | 63.78 | 39.04 |
| 9 | PAH3.DE | value+pullback | 63.24 | 55.61 | 84.72 | 42.63 | 58.91 | 65.46 | 38.25 |
| 10 | MAGN | value+pullback | 62.84 | 70.22 | 47.38 | 60.00 | 72.76 | 68.25 | 52.82 |
| 11 | 1VOW3.MI | value+pullback | 62.09 | 62.27 | 67.82 | 65.24 | 37.87 | 64.41 | 39.27 |
| 12 | ALL-PH | value+pullback | 61.49 | 62.31 | 65.08 | 68.74 | 42.03 | 60.08 | 43.60 |
| 13 | PBR-A | value+pullback | 60.88 | 67.68 | 65.72 | 55.82 | 59.15 | 49.30 | 52.54 |
| 14 | BHF | value+pullback | 60.65 | 70.78 | 55.64 | 52.87 | 44.94 | 65.39 | 43.72 |
| 15 | YPF | value+pullback | 60.50 | 69.87 | 60.84 | 53.32 | 66.12 | 48.57 | 61.62 |
| 16 | VOW.DE | value+pullback | 60.15 | 61.27 | 63.50 | 65.24 | 34.52 | 63.30 | 37.17 |
| 17 | MFA | value+pullback | 59.63 | 57.89 | 53.52 | 80.97 | 37.40 | 64.97 | 45.31 |
| 18 | BYD | value+pullback | 59.13 | 60.40 | 54.03 | 78.88 | 38.13 | 59.29 | 49.71 |
| 19 | WKC | value+pullback | 58.52 | 60.34 | 43.77 | 56.82 | 72.52 | 68.49 | 65.37 |
| 20 | AF.PA | value+pullback | 57.99 | 58.63 | 78.48 | 46.76 | 62.27 | 37.70 | 51.66 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 0/10 | 0/10 | 10/10 | 0/10 | 10/10 | 62.8 | 10 / 0 |
| Top 25 | 0/25 | 0/25 | 24/25 | 0/25 | 25/25 | 62.8 | 24 / 1 |
| Top 50 | 1/50 | 1/50 | 49/50 | 1/50 | 49/50 | 62.8 | 45 / 5 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=3, large_20_100b=3
Top-10 sparse-data names: PBF (missing quality,revisions; conf=62.8), RNG (missing quality,revisions; conf=61.9), RMAX (missing quality,revisions; conf=62.8), DINO (missing quality,revisions; conf=62.8), HPE (missing quality,revisions; conf=62.8), ABCL (missing quality,revisions; conf=60.0), HRB (missing quality,revisions; conf=61.9), ZD (missing quality,revisions; conf=62.8), MPC (missing quality,revisions; conf=62.8), RBI.VI (missing quality,revisions; conf=62.8)
