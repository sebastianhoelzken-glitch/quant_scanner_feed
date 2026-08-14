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

- **EUROPE:** 90.6/100
- **OTHER:** 75.2/100
- **US:** 88.8/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PBF       | PBF       | US       |                7.64 |             94.51 |         93.58 |         96.15 |          95.45 |        93.27 |             nan |               nan |             89.89 |         7.14 |             62.84 | swing              |                1.83 |                   nan |                  nan |
|      2 | HPE       | HPE       | US       |               68.7  |             86.89 |         85.36 |         94.68 |          88.43 |        73.63 |             nan |               nan |             56.94 |         6.89 |             62.84 | swing              |                1.65 |                   nan |                  nan |
|      3 | DINO      | DINO      | US       |               14.17 |             86.33 |         79.47 |         85.32 |          88.76 |        87.33 |             nan |               nan |             84.36 |         4.15 |             62.84 | medium             |                3.09 |                   nan |                  nan |
|      4 | SPHR      | SPHR      | US       |                5.49 |             86.15 |         91.79 |         87.06 |          85.23 |        72.65 |             nan |               nan |             57.29 |         5.64 |             60    | short              |              nan    |                   nan |                  nan |
|      5 | GH        | GH        | US       |               18.57 |             86.1  |         59.96 |         81.61 |          90.6  |        96.47 |             nan |               nan |            nan    |         6.92 |             59.09 | long               |              nan    |                   nan |                  nan |
|      6 | RMAX      | RMAX      | US       |                0.59 |             85.84 |         84.82 |         87.67 |          84.6  |        86.85 |             nan |               nan |             91.69 |         7.32 |             62.84 | swing              |               16.24 |                   nan |                  nan |
|      7 | ABCL      | ABCL      | US       |                2.92 |             85.8  |         90.83 |         95.57 |          80.77 |        64.69 |             nan |               nan |             47.75 |         9.05 |             60    | swing              |                1.97 |                   nan |                  nan |
|      8 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.72 |             85.43 |         79.2  |         82.27 |          88.59 |        95.99 |             nan |               nan |            100    |         3.53 |             60    | long               |                3.59 |                   nan |                  nan |
|      9 | HRB       | HRB       | US       |                5.86 |             85.32 |         89.13 |         91.58 |          78.33 |        81.5  |             nan |               nan |             92.24 |         7.14 |             61.93 | swing              |                2.04 |                   nan |                  nan |
|     10 | DELL      | DELL      | US       |              277.12 |             85.1  |         86.37 |         93.1  |          83.84 |        58.84 |             nan |               nan |             30.75 |         7.71 |             61.93 | swing              |                1.5  |                   nan |                  nan |
|     11 | RBI.VI    | RBI.VI    | EUROPE   |               20.29 |             85.06 |         72.82 |         84.63 |          88.18 |        85.48 |             nan |               nan |             80.2  |         3.82 |             62.84 | medium             |                7.01 |                   nan |                  nan |
|     12 | VLO       | VLO       | US       |               85.63 |             84.78 |         83.34 |         88.96 |          86.22 |        75.95 |             nan |               nan |             62.97 |         3.47 |             62.84 | swing              |                1.64 |                   nan |                  nan |
|     13 | GPN       | GPN       | US       |               21.76 |             84.32 |         84.83 |         86.91 |          74.02 |        83.8  |             nan |               nan |             94.98 |         5.76 |             62.84 | swing              |                2.2  |                   nan |                  nan |
|     14 | TXG       | TXG       | US       |                6.57 |             84.27 |         90.12 |         91.56 |          78.42 |        44.25 |             nan |               nan |              5.65 |         7.07 |             62.84 | swing              |                1.56 |                   nan |                  nan |
|     15 | QNST      | QNST      | US       |                1.03 |             84.09 |         90.73 |         89.38 |          78.8  |        72.55 |             nan |               nan |             67.63 |         7.91 |             62.84 | short              |                2.26 |                   nan |                  nan |
|     16 | CAKE      | CAKE      | US       |                4.83 |             82.87 |         88.95 |         90.03 |          76.78 |        53.16 |             nan |               nan |             26.46 |         5.78 |             62.84 | swing              |                1.45 |                   nan |                  nan |
|     17 | FSLY      | FSLY      | US       |                4.15 |             82.79 |         90    |         86.25 |          79.32 |        48.87 |             nan |               nan |             14.57 |         8.53 |             62.84 | short              |                2.04 |                   nan |                  nan |
|     18 | ANRO      | ANRO      | US       |                1.1  |             82.73 |         85.76 |         86.97 |          79.7  |        56.03 |             nan |               nan |             27.59 |         7.29 |             60    | swing              |              nan    |                   nan |                  nan |
|     19 | CRSR      | CRSR      | US       |                1.26 |             82.72 |         87.29 |         90.64 |          78.15 |        66.16 |             nan |               nan |             55.49 |         8.89 |             62.84 | swing              |                1.88 |                   nan |                  nan |
|     20 | REPL      | REPL      | US       |                1.23 |             82.17 |         97.63 |         88.3  |          76.04 |        53.65 |             nan |               nan |             23.34 |         9.91 |             60    | short              |                1.7  |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG              | EUROPE   |                3.1  |                  72.82 |                    75.46 |                 78.17 |              74.28 |                88.04 |                   11.96 |           92.79 |             60.01 |       0.847 |         nan |       nan |      nan    |       -80.42 |          2.15 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | 0QXR.IL  | Stellantis N.V.            | OTHER    |               14.8  |                  77.35 |                    73.8  |                 73.17 |              74.4  |                62.57 |                   37.43 |           72.01 |            nan    |       0.437 |         nan |       nan |        1.16 |       nan    |          0.74 |        3.71 |                 nan |              nan |                   9 |                  0.47 |
|          nan | ACA.PA   | ACA.PA                     | EUROPE   |               60.97 |                  68.72 |                    73.25 |                 74    |              72.95 |                89.85 |                   10.15 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.11 |          9.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | MOMO     | Hello Group Inc.           | OTHER    |                0.74 |                  77.26 |                    72.56 |                 71.67 |              74.77 |                74.91 |                   25.09 |           68.72 |             56.59 |       0.574 |         nan |       nan |       -5.14 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | NN.AS    | NN.AS                      | EUROPE   |               20.39 |                  65.01 |                    72.28 |                 73.49 |              71.8  |                98.95 |                    1.05 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.98 |         11.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                     | EUROPE   |               15.17 |                  64.63 |                    71.83 |                 73.03 |              71.35 |                98.23 |                    1.77 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.48 |          7.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BNP.PA   | BNP.PA                     | EUROPE   |              122.2  |                  68.74 |                    71.47 |                 71.92 |              71.28 |                81.45 |                   18.55 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.49 |          9.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                   | EUROPE   |              214.19 |                  68.3  |                    71.15 |                 71.63 |              70.96 |                81.6  |                   18.4  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.65 |          9.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | NWL.MI   | NewPrinces S.p.A.          | EUROPE   |                0.69 |                  70.16 |                    71.06 |                 73.06 |              71.19 |                83.28 |                   16.72 |           81.85 |             56.88 |       0.971 |         nan |       nan |        5.34 |      -121.21 |          2.13 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | CA.PA    | CA.PA                      | EUROPE   |               11.09 |                  66.27 |                    70.63 |                 71.36 |              70.34 |                86.62 |                   13.38 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.38 |         12.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                       | US       |              214.9  |                  68.46 |                    70.61 |                 70.97 |              70.47 |                78.49 |                   21.51 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.2  |          9.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                         | US       |               62    |                  62.36 |                    69.73 |                 70.96 |              69.24 |                96.75 |                    3.25 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        11.86 |         14.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PARR     | Par Pacific Holdings, Inc. | US       |                3.57 |                  66.79 |                    69.35 |                 71.62 |              67.85 |                69.58 |                   30.42 |           81.06 |             72.4  |       0.02  |         nan |       nan |        3.98 |         6.21 |          4.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | MTRX     | Matrix Service Company     | US       |                0.28 |                  74.81 |                    69.27 |                 69.88 |              70.92 |                60.38 |                   39.62 |           71.49 |             61.93 |       0.303 |         nan |       nan |      -46    |        16.78 |        nan    |        1.12 |                 nan |              nan |                  10 |                  0.53 |
|            7 | EMBC     | Embecta Corp.              | US       |                0.25 |                  77.07 |                    69.13 |                 67.73 |              71.04 |                59.61 |                   40.39 |           67.49 |             48.21 |       0.477 |         nan |       nan |        5.6  |         2.9  |          3.23 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | AKER.OL  | Aker ASA                   | EUROPE   |                9.72 |                  58.35 |                    69.07 |                 73.49 |              63.05 |                73.26 |                   26.74 |           97.88 |             78.53 |       0.114 |         nan |       nan |        5.28 |        54.7  |          3.77 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BMY      | BMY                        | US       |              114.54 |                  65.79 |                    69    |                 69.53 |              68.78 |                80.76 |                   19.24 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.86 |         14.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | XNET     | Xunlei Limited             | OTHER    |                0.28 |                  60.07 |                    68.86 |                 72.06 |              64.79 |                76.29 |                   23.71 |           87.5  |             78.06 |     nan     |         nan |       nan |        3.54 |       nan    |          0.37 |        2.58 |                 nan |              nan |                   6 |                  0.32 |
|          nan | HOPE     | HOPE                       | US       |                1.61 |                  63.89 |                    68.81 |                 69.63 |              68.48 |                86.86 |                   13.14 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.19 |         14.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ADAM     | ADAM                       | US       |                0.79 |                  66.55 |                    68.76 |                 69.12 |              68.61 |                76.83 |                   23.17 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.22 |          6.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG              | EUROPE   |                3.1  |                  72.82 |                    75.46 |                 78.17 |              74.28 |                88.04 |                   11.96 |           92.79 |             60.01 |       0.847 |         nan |       nan |      nan    |       -80.42 |          2.15 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | ACA.PA   | ACA.PA                     | EUROPE   |               60.97 |                  68.72 |                    73.25 |                 74    |              72.95 |                89.85 |                   10.15 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.11 |          9.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | AKER.OL  | Aker ASA                   | EUROPE   |                9.72 |                  58.35 |                    69.07 |                 73.49 |              63.05 |                73.26 |                   26.74 |           97.88 |             78.53 |       0.114 |         nan |       nan |        5.28 |        54.7  |          3.77 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|          nan | NN.AS    | NN.AS                      | EUROPE   |               20.39 |                  65.01 |                    72.28 |                 73.49 |              71.8  |                98.95 |                    1.05 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.98 |         11.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | 0QXR.IL  | Stellantis N.V.            | OTHER    |               14.8  |                  77.35 |                    73.8  |                 73.17 |              74.4  |                62.57 |                   37.43 |           72.01 |            nan    |       0.437 |         nan |       nan |        1.16 |       nan    |          0.74 |        3.71 |                 nan |              nan |                   9 |                  0.47 |
|            4 | NWL.MI   | NewPrinces S.p.A.          | EUROPE   |                0.69 |                  70.16 |                    71.06 |                 73.06 |              71.19 |                83.28 |                   16.72 |           81.85 |             56.88 |       0.971 |         nan |       nan |        5.34 |      -121.21 |          2.13 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | AGS.BR   | AGS.BR                     | EUROPE   |               15.17 |                  64.63 |                    71.83 |                 73.03 |              71.35 |                98.23 |                    1.77 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.48 |          7.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | XNET     | Xunlei Limited             | OTHER    |                0.28 |                  60.07 |                    68.86 |                 72.06 |              64.79 |                76.29 |                   23.71 |           87.5  |             78.06 |     nan     |         nan |       nan |        3.54 |       nan    |          0.37 |        2.58 |                 nan |              nan |                   6 |                  0.32 |
|          nan | BNP.PA   | BNP.PA                     | EUROPE   |              122.2  |                  68.74 |                    71.47 |                 71.92 |              71.28 |                81.45 |                   18.55 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.49 |          9.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | MOMO     | Hello Group Inc.           | OTHER    |                0.74 |                  77.26 |                    72.56 |                 71.67 |              74.77 |                74.91 |                   25.09 |           68.72 |             56.59 |       0.574 |         nan |       nan |       -5.14 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                   | EUROPE   |              214.19 |                  68.3  |                    71.15 |                 71.63 |              70.96 |                81.6  |                   18.4  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.65 |          9.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PARR     | Par Pacific Holdings, Inc. | US       |                3.57 |                  66.79 |                    69.35 |                 71.62 |              67.85 |                69.58 |                   30.42 |           81.06 |             72.4  |       0.02  |         nan |       nan |        3.98 |         6.21 |          4.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CA.PA    | CA.PA                      | EUROPE   |               11.09 |                  66.27 |                    70.63 |                 71.36 |              70.34 |                86.62 |                   13.38 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.38 |         12.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                       | US       |              214.9  |                  68.46 |                    70.61 |                 70.97 |              70.47 |                78.49 |                   21.51 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.2  |          9.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                         | US       |               62    |                  62.36 |                    69.73 |                 70.96 |              69.24 |                96.75 |                    3.25 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        11.86 |         14.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | 0P6O.IL  | Volkswagen AG              | OTHER    |               40.48 |                  64.8  |                    68.39 |                 69.91 |              66.3  |                72.27 |                   27.73 |           77.67 |            nan    |       0.427 |         nan |       nan |        7.45 |       nan    |          2.63 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|            6 | MTRX     | Matrix Service Company     | US       |                0.28 |                  74.81 |                    69.27 |                 69.88 |              70.92 |                60.38 |                   39.62 |           71.49 |             61.93 |       0.303 |         nan |       nan |      -46    |        16.78 |        nan    |        1.12 |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGN.AS   | AGN.AS                     | EUROPE   |               12.07 |                  62.01 |                    68.57 |                 69.66 |              68.13 |                92.62 |                    7.38 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.97 |         13.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | HOPE     | HOPE                       | US       |                1.61 |                  63.89 |                    68.81 |                 69.63 |              68.48 |                86.86 |                   13.14 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.19 |         14.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                        | US       |              114.54 |                  65.79 |                    69    |                 69.53 |              68.78 |                80.76 |                   19.24 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.86 |         14.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                              | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | INDU-C.ST | AB Industrivärden (publ)          | EUROPE   |               20.29 |                     0.08 |    -0.06 |     -0    |                  73.62 |                        69.87 |         45.07 |         59.36 |          68.01 |        66.69 |           86.84 |             78.53 |         2.49 |
|               2 | ALL       | The Allstate Corporation          | US       |               57.12 |                     0.05 |    -0.05 |      0.08 |                  85.22 |                        69.51 |         61.91 |         66.95 |          63.17 |        56.87 |           67.58 |             64.9  |         3.03 |
|               3 | INDU-A.ST | AB Industrivärden (publ)          | EUROPE   |               20.39 |                     0.08 |    -0.07 |     -0.01 |                  72.7  |                        69    |         41.29 |         57.9  |          67.16 |        64.8  |           86.84 |             78.53 |         2.67 |
|               4 | AMZN      | Amazon.com, Inc.                  | US       |             2480.28 |                     0.07 |    -0.03 |      0.06 |                  71.35 |                        68.91 |         62.74 |         58.63 |          63.74 |        62.2  |           80.87 |             71.08 |         5.8  |
|               5 | HRTG      | Heritage Insurance Holdings, Inc. | US       |                0.86 |                     0.06 |    -0.06 |      0.25 |                  86.84 |                        68.73 |         70.79 |         70.81 |          61.24 |        56.49 |           59.19 |             56.41 |         5.96 |
|               6 | CLW       | Clearwater Paper Corporation      | US       |                0.31 |                     0.06 |    -0.04 |      0.35 |                  80.37 |                        65.67 |         70.32 |         67.6  |          53.57 |        49.53 |           45.03 |             63.01 |         6.88 |
|               7 | WKC       | World Kinect Corporation          | US       |                1.65 |                     0.08 |    -0    |      0    |                  57.6  |                        65.45 |         58.24 |         69.3  |          69.2  |        63.87 |           56.82 |             71.98 |         4.97 |
|               8 | AVGO      | Broadcom Inc.                     | US       |             1724.03 |                     0.02 |    -0.01 |      0.12 |                  53.08 |                        65.43 |         62.66 |         56.36 |          62.34 |        61.99 |           81.98 |             64.9  |         6.21 |
|               9 | SLDE      | Slide Insurance Holdings, Inc.    | US       |                2.19 |                     0.02 |     0.01 |      0.05 |                  48.61 |                        65.42 |         66.27 |         66.88 |          66.25 |        63.29 |           75.7  |             63.66 |         5.82 |
|              10 | PKX       | POSCO Holdings Inc.               | OTHER    |               14.84 |                     0.03 |     0.01 |      0.11 |                  53.07 |                        65.2  |         60.84 |         42.94 |          55.19 |        65.53 |           82.35 |             68.99 |         6.18 |
|              11 | MSFT      | Microsoft Corporation             | US       |             3199.99 |                     0.02 |    -0.01 |      0.24 |                  49.75 |                        65.02 |         72.6  |         65.97 |          55.88 |        52.97 |           61.2  |             60.1  |         5.79 |
|              12 | DAC       | Danaos Corporation                | OTHER    |                2.22 |                     0.02 |    -0.02 |      0.08 |                  54.47 |                        64.72 |         66.21 |         63.18 |          66.77 |        64.64 |           75.67 |             55.44 |         3.36 |
|              13 | LLY       | Eli Lilly and Company             | US       |              934.65 |                     0.02 |     0.01 |      0.03 |                  44.14 |                        64.11 |         59.94 |         60.61 |          65.92 |        64.73 |           90.01 |             61.2  |         4.2  |
|              14 | DSX       | Diana Shipping Inc.               | OTHER    |                0.27 |                     0.03 |    -0.02 |      0.18 |                  60.85 |                        63.62 |         65.6  |         50.22 |          57.3  |        63.18 |           64.79 |             58.22 |         4.64 |
|              15 | HMC       | Honda Motor Co., Ltd.             | OTHER    |               35.11 |                     0.02 |     0.02 |      0.08 |                  44.39 |                        63.15 |         62.55 |         60.72 |          55.8  |        58.34 |           63.32 |             83.68 |         3.82 |
|              16 | LNC       | Lincoln National Corporation      | US       |                7.52 |                     0.04 |    -0.03 |      0.08 |                  68.13 |                        62.04 |         67.03 |         67.97 |          58.43 |        56.42 |           42.2  |             62.66 |         4.69 |
|              17 | MA        | Mastercard Incorporated           | US       |              430.82 |                     0.02 |    -0.02 |      0.03 |                  52.35 |                        61.23 |         58.34 |         58.76 |          53.53 |        50.3  |           71.4  |             64.74 |         3.26 |
|              18 | YPF       | YPF Sociedad Anónima              | OTHER    |               16.82 |                     0.06 |    -0    |      0.02 |                  69.41 |                        60.95 |         49.46 |         58.67 |          61.92 |        54.15 |           56.58 |             65.91 |         5.04 |
|              19 | ZEAL.CO   | Zealand Pharma A/S                | EUROPE   |                3.05 |                     0.02 |     0.01 |      0.13 |                  44.51 |                        58.92 |         60.54 |         46.27 |          47.97 |        57.33 |           70.63 |             52.36 |         7.87 |
|              20 | GOOGL     | Alphabet Inc.                     | US       |             3673.85 |                     0.08 |    -0.03 |     -0.02 |                  62.88 |                        58.74 |         44.6  |         43.56 |          58.86 |        57.94 |           81.95 |             70.8  |         4.9  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | PD       | PagerDuty, Inc.              | US       |                0.8  |             65.22 |         71.67 |         70.75 |          59.68 |        56.78 |           57.27 |             51.62 |             62.44 |         8.24 |             85.96 | short              |                0.09 |                   nan |                  nan |
|    nan | NVDA     | NVIDIA Corporation           | US       |             4732.85 |             64.53 |         69.24 |         58.96 |          63.51 |        65.56 |           92.49 |             61.81 |             31.21 |         5.62 |             89.54 | short              |               12.94 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.93 |             61.81 |         65.29 |         62.36 |          57.59 |        61.27 |           51.35 |             50.62 |             73.5  |         8.44 |             86.67 | short              |               -4.61 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.02 |             41.7  |         54.73 |         41.52 |          36.86 |        41.88 |           27.58 |             30    |             63.72 |         4.54 |             74.95 | short              |               -0.13 |                   nan |                  nan |
|    nan | ATHM     | Autohome Inc.                | OTHER    |                2.25 |             39.76 |         49.78 |         44.65 |          34.87 |        32.82 |           29.17 |             29.61 |             36.11 |         6.21 |             78.55 | short              |              nan    |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.93 |             38.14 |         28.15 |         34.06 |          42.23 |        53.64 |           50.26 |             48.62 |             78.24 |         6.3  |             78.58 | long               |                2.58 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.9  |             36.67 |         36.66 |         22.41 |          36.67 |        48.36 |           64.32 |             19.94 |             46.67 |         9.11 |             77.55 | long               |               -3.48 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.32 |             35.98 |         29.27 |         32.51 |          39.46 |        52.74 |           47.64 |             38.09 |             86.33 |         7.22 |             78.48 | long               |                1.63 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             35.82 |         30.58 |         29.05 |          41.05 |        57.7  |           73.25 |             26.2  |             71.96 |         4.93 |             81.52 | long               |               -1.66 |                   nan |                  nan |
|    nan | AT1.DE   | Aroundtown SA                | EUROPE   |                2.22 |             34.95 |         34.4  |         28.8  |          35.5  |        45    |           54    |             37.58 |             50.8  |         5.55 |             75.53 | long               |               -1.91 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             34.08 |         40.06 |         23.73 |          30.09 |        38.07 |           39.66 |             38.49 |             49.29 |         7.14 |             75.4  | short              |               -3.74 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.88 |             28.84 |         59.36 |         24.87 |          23.94 |        32.81 |           25.2  |             27.8  |             58    |         7.81 |             75.24 | short              |               -4.55 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.45 |             20.98 |         26.01 |         19.69 |          20.6  |        21.37 |           19.42 |             38.97 |             23.04 |         6.95 |             76.61 | short              |               -5.8  |                   nan |                  nan |

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
- Excluded by hard/data filters: **294**
- Event watch (otherwise eligible): **13**
- Final eligible: **693**
- Eligible change vs previous stored run: **-4**

Top exclusion categories:
- liquidity: 238
- price: 177
- market_cap: 153
- data_confidence: 23
- price_history: 19
- duplicate_listing: 4
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AKER.OL | 31 | 8 |  | 2 | 1 | value,quality_value |
| PARR | 49 | 5 |  | 7 | 1 | value,quality_value |
| BION.SW | 142 | 1 |  | 1 | 1 | value,quality_value |
| AVGO | 324 | 15 | 8 | 10 | 1 | pullback,quality_value |
| NWL.MI | 489 | 4 |  | 4 | 1 | value,quality_value |
| MTRX | 527 | 6 | 31 | 9 | 1 | value,quality_value |
| XNET | 539 | 9 |  | 5 | 1 | value,quality_value |
| MOMO | 596 | 3 | 33 | 6 | 1 | value,quality_value |
| 0QXR.IL | 680 | 2 |  | 3 | 1 | value,quality_value |
| PBF | 1 |  |  |  | 1 | main |
| HPE | 2 |  |  |  | 1 | main |
| DINO | 3 |  |  |  | 1 | main |
| SPHR | 4 |  |  |  | 1 | main |
| GH | 5 |  |  |  | 1 | main |
| RMAX | 6 |  |  |  | 1 | main |

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
| 1 | MOMO | value+pullback | 71.01 | 77.26 | 67.55 | 68.72 | 56.59 | 74.91 | 45.76 |
| 2 | PAH3.DE | value+pullback | 69.91 | 79.46 | 81.25 | 44.61 | 58.89 | 65.92 | 39.56 |
| 3 | INVA | value+pullback | 69.74 | 63.88 | 71.85 | 84.04 | 39.89 | 80.10 | 41.90 |
| 4 | 0P6O.IL | value+pullback | 69.71 | 64.80 | 76.65 | 77.67 |  | 72.27 | 39.48 |
| 5 | GSL | value+pullback | 67.20 | 65.70 | 72.25 | 75.31 | 37.58 | 71.87 | 54.85 |
| 6 | VOW3.DE | value+pullback | 66.65 | 73.08 | 76.83 | 63.95 | 38.64 | 60.27 | 37.89 |
| 7 | STNE | value+pullback | 66.27 | 72.21 | 62.26 | 79.40 | 37.82 | 66.73 | 40.92 |
| 8 | IRS | value+pullback | 66.17 | 60.69 | 70.14 | 81.69 | 44.17 | 68.81 | 48.37 |
| 9 | PBR-A | value+pullback | 65.24 | 75.29 | 74.26 | 55.82 | 58.94 | 49.12 | 54.18 |
| 10 | AVGO | value+pullback | 65.16 | 57.79 | 53.08 | 81.98 | 64.90 | 78.85 | 62.17 |
| 11 | MTRX | value+pullback | 63.98 | 74.81 | 50.17 | 71.49 | 61.93 | 60.38 | 50.83 |
| 12 | 1VOW3.MI | value+pullback | 62.61 | 63.86 | 71.16 | 63.95 | 38.68 | 60.99 | 39.04 |
| 13 | PKX | value+pullback | 62.34 | 55.54 | 53.07 | 82.35 | 68.99 | 65.81 | 58.01 |
| 14 | WKC | value+pullback | 61.57 | 59.34 | 57.60 | 56.82 | 71.98 | 68.26 | 66.53 |
| 15 | ALL-PH | value+pullback | 61.25 | 62.22 | 64.99 | 67.58 | 43.08 | 59.46 | 45.16 |
| 16 | VOW.DE | value+pullback | 61.25 | 61.60 | 71.16 | 63.95 | 34.35 | 59.75 | 35.66 |
| 17 | BHF | value+pullback | 60.54 | 69.00 | 59.95 | 50.45 | 44.36 | 64.23 | 45.10 |
| 18 | AF.PA | value+pullback | 60.45 | 64.23 | 77.61 | 50.19 | 61.87 | 40.32 | 52.84 |
| 19 | PBR | value+pullback | 60.23 | 64.53 | 66.62 | 55.82 | 59.92 | 49.23 | 54.65 |
| 20 | VOLV-B.ST | value+pullback | 59.70 | 55.63 | 63.66 | 60.91 | 60.26 | 59.66 | 53.00 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 0/10 | 0/10 | 9/10 | 0/10 | 10/10 | 61.9 | 10 / 0 |
| Top 25 | 0/25 | 0/25 | 24/25 | 0/25 | 25/25 | 62.8 | 24 / 1 |
| Top 50 | 2/50 | 2/50 | 49/50 | 2/50 | 48/50 | 62.8 | 43 / 7 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=1, mid_5_20b=6, large_20_100b=1, mega_100b_plus=1
Top-10 sparse-data names: PBF (missing quality,revisions; conf=62.8), HPE (missing quality,revisions; conf=62.8), DINO (missing quality,revisions; conf=62.8), SPHR (missing quality,revisions; conf=60.0), GH (missing quality,revisions,valuation; conf=59.1), RMAX (missing quality,revisions; conf=62.8), ABCL (missing quality,revisions; conf=60.0), SSABBH.HE (missing quality,revisions; conf=60.0), HRB (missing quality,revisions; conf=61.9), DELL (missing quality,revisions; conf=61.9)
