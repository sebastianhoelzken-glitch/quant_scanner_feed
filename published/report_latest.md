# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-13

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

- **EUROPE:** 90.7/100
- **OTHER:** 74.0/100
- **US:** 88.3/100

## Main multi-horizon ranking

|   rank | symbol    | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PBF       | PBF                        | US       |                7.64 |             92.68 |         92.33 |         93.85 |          93.03 |        89.85 |          nan    |               nan |             86.98 |         7.12 |             62.84 | swing              |               -1.25 |                   nan |                  nan |
|      2 | HPE       | HPE                        | US       |               68.67 |             85.24 |         84.12 |         92.48 |          86.36 |        70.9  |          nan    |               nan |             55.16 |         6.9  |             62.84 | swing              |              -11.72 |                   nan |                  nan |
|      3 | ZD        | ZD                         | US       |                1.66 |             84.06 |         74.4  |         84.41 |          85.5  |        83.71 |          nan    |               nan |             84.64 |         5.42 |             62.84 | medium             |              nan    |                   nan |                  nan |
|      4 | ABCL      | ABCL                       | US       |                2.92 |             83.83 |         89.54 |         93.38 |          78.12 |        60.68 |          nan    |               nan |             43.84 |         9.07 |             60    | swing              |               -7.74 |                   nan |                  nan |
|      5 | DELL      | DELL                       | US       |              277    |             83.6  |         85.07 |         91.21 |          82.13 |        57.19 |          nan    |               nan |             30.85 |         7.7  |             61.93 | swing              |              -14.28 |                   nan |                  nan |
|      6 | TWST      | TWST                       | US       |                6.81 |             83.31 |         89.31 |         90.54 |          77.31 |        45.26 |          nan    |               nan |             10.27 |         6.85 |             60    | swing              |              -15    |                   nan |                  nan |
|      7 | HRB       | HRB                        | US       |                5.86 |             83.28 |         87.8  |         89.51 |          76.12 |        78.76 |          nan    |               nan |             90.49 |         7.16 |             61.93 | swing              |                3.52 |                   nan |                  nan |
|      8 | DINO      | DINO                       | US       |               14.16 |             83.24 |         79.13 |         83.65 |          86.17 |        82.83 |          nan    |               nan |             79.11 |         4.14 |             62.84 | medium             |              nan    |                   nan |                  nan |
|      9 | VLO       | VLO                        | US       |               85.59 |             83.14 |         82.07 |         86.95 |          84.22 |        73.47 |          nan    |               nan |             61.49 |         3.49 |             62.84 | swing              |               -4.58 |                   nan |                  nan |
|     10 | TXG       | TXG                        | US       |                6.57 |             82.71 |         88.72 |         89.52 |          76.7  |        42.56 |          nan    |               nan |              5.67 |         7.08 |             62.84 | swing              |              -15.52 |                   nan |                  nan |
|     11 | GPN       | GPN                        | US       |               21.75 |             82.11 |         83.42 |         84.96 |          71.87 |        80.8  |          nan    |               nan |             92.64 |         5.79 |             62.84 | swing              |              nan    |                   nan |                  nan |
|     12 | SSABBH.HE | SSABBH.HE                  | EUROPE   |                9.69 |             81.84 |         76.08 |         78.48 |          85.19 |        92.85 |          nan    |               nan |             98.73 |         3.54 |             60    | long               |                6.39 |                   nan |                  nan |
|     13 | QNST      | QNST                       | US       |                1.03 |             81.83 |         89.5  |         87.09 |          76.57 |        69.53 |          nan    |               nan |             65.43 |         7.9  |             62.84 | short              |               -3.27 |                   nan |                  nan |
|     14 | CAKE      | CAKE                       | US       |                4.83 |             81.42 |         87.72 |         87.99 |          75.11 |        51.61 |          nan    |               nan |             26.74 |         5.79 |             62.84 | swing              |               -9.45 |                   nan |                  nan |
|     15 | LFST      | LFST                       | US       |                4.05 |             80.85 |         82.73 |         85.01 |          78.97 |        57.73 |          nan    |               nan |             33.96 |         4.89 |             62.84 | swing              |              -11.26 |                   nan |                  nan |
|     16 | CRSR      | CRSR                       | US       |                1.26 |             80.84 |         85.78 |         88.36 |          75.9  |        63.37 |          nan    |               nan |             53.75 |         8.89 |             62.84 | swing              |               -3.38 |                   nan |                  nan |
|     17 | PARR      | Par Pacific Holdings, Inc. | US       |                3.57 |             80.77 |         81.94 |         80.67 |          80.88 |        76.56 |           77.39 |                72 |             66.8  |         6.76 |             85.73 | short              |                6.23 |                   nan |                  nan |
|     18 | FSLY      | FSLY                       | US       |                4.15 |             80.75 |         88.51 |         84.05 |          77.44 |        46.86 |          nan    |               nan |             14.06 |         8.53 |             62.84 | short              |              -11.39 |                   nan |                  nan |
|     19 | REPL      | REPL                       | US       |                1.23 |             80.47 |         96.46 |         86.53 |          74.42 |        51.82 |          nan    |               nan |             23.06 |         9.91 |             60    | short              |              -14.69 |                   nan |                  nan |
|     20 | UMAC      | UMAC                       | US       |                1.18 |             80.36 |         81.18 |         82.09 |          79.54 |        63.93 |          nan    |               nan |             45.66 |         9.16 |             60    | swing              |               -8.58 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | SM       | SM Energy Company                                    | US       |                6.68 |                  83.54 |                    76.43 |                 75.11 |              76.27 |                60.98 |                   39.02 |           82.61 |             51.48 |       0.191 |         nan |       nan |        4.53 |         4.41 |          5.75 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|            2 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.74 |                  76.41 |                    72.39 |                 71.54 |              74.82 |                76.96 |                   23.04 |           66.72 |             59.53 |       0.574 |         nan |       nan |       -5.14 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | ACA.PA   | ACA.PA                                               | EUROPE   |               60.82 |                  67.58 |                    72.38 |                 73.18 |              72.06 |                89.99 |                   10.01 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.09 |          9.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BNP.PA   | BNP.PA                                               | EUROPE   |              123.19 |                  69.31 |                    71.98 |                 72.43 |              71.8  |                81.79 |                   18.21 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          9.72 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              213.26 |                  69.03 |                    71.81 |                 72.27 |              71.62 |                82    |                   18    |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.62 |          9.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | EMBC     | Embecta Corp.                                        | US       |                0.25 |                  74.87 |                    71.4  |                 70.54 |              72.4  |                62.53 |                   37.47 |           67.55 |            nan    |       0.477 |         nan |       nan |        5.53 |         2.9  |          3.48 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | NN.AS    | NN.AS                                                | EUROPE   |               20.35 |                  63.73 |                    71.27 |                 72.53 |              70.77 |                98.95 |                    1.05 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.97 |         11.54 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               15.14 |                  63.85 |                    71.08 |                 72.28 |              70.59 |                97.57 |                    2.43 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.47 |          7.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                 | US       |              215.3  |                  68.9  |                    71.07 |                 71.44 |              70.93 |                79.05 |                   20.95 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.2  |          9.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | YPF      | YPF Sociedad Anónima                                 | OTHER    |               16.81 |                  76.07 |                    70.8  |                 70.69 |              72.16 |                59.89 |                   40.11 |           70.22 |             66.12 |       0.06  |         nan |       nan |        1.68 |         8.61 |          1.27 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|            5 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  71.84 |                    70.01 |                 71.4  |              69.21 |                72.01 |                   27.99 |           85.95 |             45.22 |     nan     |         nan |       nan |        3.93 |       162.2  |          4.73 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            6 | TNK      | Teekay Tankers Ltd.                                  | OTHER    |                2.51 |                  68.98 |                    69.97 |                 71.34 |              70.99 |                78.37 |                   21.63 |           70.87 |             72.19 |       0.078 |         nan |       nan |        3.2  |         9.16 |          4.92 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | CA.PA    | CA.PA                                                | EUROPE   |               11.13 |                  65.38 |                    69.88 |                 70.63 |              69.58 |                86.37 |                   13.63 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.41 |         12.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                                                   | US       |               61.97 |                  62.03 |                    69.47 |                 70.71 |              68.97 |                96.75 |                    3.25 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        11.86 |         14.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ISP.MI   | ISP.MI                                               | EUROPE   |              120.32 |                  65.92 |                    69.44 |                 70.03 |              69.2  |                82.34 |                   17.66 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.56 |         12.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.57 |                  69.27 |                    69.26 |                 70.9  |              68.57 |                63.83 |                   36.17 |           77.39 |             72    |       0.02  |         nan |       nan |        3.81 |         6.21 |          4.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                                  | US       |              114.48 |                  66.11 |                    69.18 |                 69.69 |              68.98 |                80.44 |                   19.56 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.86 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BAC      | BAC                                                  | US       |              388.51 |                  64.32 |                    69.15 |                 69.95 |              68.82 |                86.82 |                   13.18 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        12.1  |         14.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A                                                | US       |               95.74 |                  69.43 |                    68.59 |                 68.45 |              68.65 |                65.52 |                   34.48 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         6.56 |          4.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR                                                  | US       |               99.94 |                  69.18 |                    67.99 |                 67.79 |              68.07 |                63.61 |                   36.39 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         4.49 |          4.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | SM       | SM Energy Company                                    | US       |                6.68 |                  83.54 |                    76.43 |                 75.11 |              76.27 |                60.98 |                   39.02 |           82.61 |             51.48 |       0.191 |         nan |       nan |        4.53 |         4.41 |          5.75 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|          nan | ACA.PA   | ACA.PA                                               | EUROPE   |               60.82 |                  67.58 |                    72.38 |                 73.18 |              72.06 |                89.99 |                   10.01 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.09 |          9.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                                                | EUROPE   |               20.35 |                  63.73 |                    71.27 |                 72.53 |              70.77 |                98.95 |                    1.05 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.97 |         11.54 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BNP.PA   | BNP.PA                                               | EUROPE   |              123.19 |                  69.31 |                    71.98 |                 72.43 |              71.8  |                81.79 |                   18.21 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          9.72 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               15.14 |                  63.85 |                    71.08 |                 72.28 |              70.59 |                97.57 |                    2.43 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.47 |          7.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              213.26 |                  69.03 |                    71.81 |                 72.27 |              71.62 |                82    |                   18    |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.62 |          9.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.74 |                  76.41 |                    72.39 |                 71.54 |              74.82 |                76.96 |                   23.04 |           66.72 |             59.53 |       0.574 |         nan |       nan |       -5.14 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                                                 | US       |              215.3  |                  68.9  |                    71.07 |                 71.44 |              70.93 |                79.05 |                   20.95 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.2  |          9.95 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  71.84 |                    70.01 |                 71.4  |              69.21 |                72.01 |                   27.99 |           85.95 |             45.22 |     nan     |         nan |       nan |        3.93 |       162.2  |          4.73 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            6 | TNK      | Teekay Tankers Ltd.                                  | OTHER    |                2.51 |                  68.98 |                    69.97 |                 71.34 |              70.99 |                78.37 |                   21.63 |           70.87 |             72.19 |       0.078 |         nan |       nan |        3.2  |         9.16 |          4.92 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            7 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.57 |                  69.27 |                    69.26 |                 70.9  |              68.57 |                63.83 |                   36.17 |           77.39 |             72    |       0.02  |         nan |       nan |        3.81 |         6.21 |          4.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ET       | ET                                                   | US       |               61.97 |                  62.03 |                    69.47 |                 70.71 |              68.97 |                96.75 |                    3.25 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        11.86 |         14.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | YPF      | YPF Sociedad Anónima                                 | OTHER    |               16.81 |                  76.07 |                    70.8  |                 70.69 |              72.16 |                59.89 |                   40.11 |           70.22 |             66.12 |       0.06  |         nan |       nan |        1.68 |         8.61 |          1.27 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|          nan | CA.PA    | CA.PA                                                | EUROPE   |               11.13 |                  65.38 |                    69.88 |                 70.63 |              69.58 |                86.37 |                   13.63 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.41 |         12.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | EMBC     | Embecta Corp.                                        | US       |                0.25 |                  74.87 |                    71.4  |                 70.54 |              72.4  |                62.53 |                   37.47 |           67.55 |            nan    |       0.477 |         nan |       nan |        5.53 |         2.9  |          3.48 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | PKX      | POSCO Holdings Inc.                                  | OTHER    |               14.84 |                  62.88 |                    66.85 |                 70.47 |              64.12 |                66.47 |                   33.53 |           87.54 |             68.8  |     nan     |         nan |       nan |        3.7  |         9.81 |         28.43 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | ISP.MI   | ISP.MI                                               | EUROPE   |              120.32 |                  65.92 |                    69.44 |                 70.03 |              69.2  |                82.34 |                   17.66 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.56 |         12.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BAC      | BAC                                                  | US       |              388.51 |                  64.32 |                    69.15 |                 69.95 |              68.82 |                86.82 |                   13.18 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        12.1  |         14.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                                  | US       |              114.48 |                  66.11 |                    69.18 |                 69.69 |              68.98 |                80.44 |                   19.56 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.86 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | IHS      | IHS Holding Limited                                  | OTHER    |                2.44 |                  69.75 |                    67.95 |                 68.86 |              70.52 |                66.42 |                   33.58 |           60    |             83.39 |      -0.111 |         nan |       nan |        7.1  |        15.11 |          5.1  |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | ALL      | The Allstate Corporation                             | US       |               57.1  |                     0.05 |    -0.05 |      0.08 |                  85.22 |                        70.96 |         62.17 |         67.3  |          63.98 |        57.52 |           73.79 |             65.12 |         3.03 |
|               2 | HRTG     | Heritage Insurance Holdings, Inc.                    | US       |                0.86 |                     0.06 |    -0.06 |      0.25 |                  86.84 |                        69.38 |         70.46 |         70.76 |          61.63 |        56.79 |           62.67 |             56.27 |         5.89 |
|               3 | HMC      | Honda Motor Co., Ltd.                                | OTHER    |               35.09 |                     0.02 |     0.02 |      0.08 |                  44.39 |                        66.29 |         65.18 |         64.34 |          60.57 |        65.61 |           73.25 |             82.62 |         3.81 |
|               4 | CLW      | Clearwater Paper Corporation                         | US       |                0.31 |                     0.06 |    -0.04 |      0.35 |                  80.37 |                        66.03 |         68.99 |         66.05 |          54.34 |        53.27 |           50.18 |             62.93 |         6.79 |
|               5 | YPF      | YPF Sociedad Anónima                                 | OTHER    |               16.81 |                     0.06 |    -0    |      0.02 |                  69.41 |                        65.94 |         51.45 |         63.13 |          70.93 |        71.34 |           70.22 |             66.12 |         5.75 |
|               6 | PKX      | POSCO Holdings Inc.                                  | OTHER    |               14.84 |                     0.03 |     0.01 |      0.11 |                  53.07 |                        65.18 |         58.79 |         40.37 |          54.92 |        67.41 |           87.54 |             68.8  |         6.15 |
|               7 | DSX      | Diana Shipping Inc.                                  | OTHER    |                0.27 |                     0.03 |    -0.02 |      0.18 |                  60.85 |                        64.91 |         66.08 |         51.9  |          59.87 |        66.96 |           67.7  |             61.32 |         4.57 |
|               8 | DAC      | Danaos Corporation                                   | OTHER    |                2.22 |                     0.02 |    -0.02 |      0.08 |                  54.47 |                        64.86 |         66.55 |         64.1  |          68.17 |        67.59 |           74.94 |             56.16 |         3.29 |
|               9 | SLDE     | Slide Insurance Holdings, Inc.                       | US       |                2.19 |                     0.02 |     0.01 |      0.05 |                  48.61 |                        64.56 |         65.6  |         65.27 |          65.06 |        62.89 |           80.9  |             55.28 |         5.79 |
|              10 | WKC      | World Kinect Corporation                             | US       |                1.65 |                     0.08 |    -0    |      0    |                  57.6  |                        64.19 |         59.44 |         71.27 |          68.26 |        60.4  |           46.49 |             70.79 |         4.94 |
|              11 | HTD      | John Hancock Tax-Advantaged Dividend Income Fund     | US       |                0.78 |                     0.02 |     0.01 |     -0.01 |                  48.6  |                        60.91 |         51.8  |         57.07 |          60.12 |        60.31 |           64.68 |             80.99 |         1.79 |
|              12 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                     0.05 |    -0    |     -0.03 |                  70.14 |                        57.86 |         44.22 |         46.73 |          55.43 |        64.99 |           85.95 |             45.22 |         4.13 |
|              13 | GSL      | Global Ship Lease, Inc.                              | OTHER    |                1.3  |                     0.07 |    -0.03 |     -0    |                  72.25 |                        57.45 |         49.75 |         51.53 |          61.36 |        67.8  |           73.1  |             41.53 |         3.71 |
|              14 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.74 |                     0.05 |    -0.01 |     -0.07 |                  67.55 |                        53.76 |         38.11 |         42.71 |          52.84 |        65.48 |           66.72 |             59.53 |         4.22 |
|              15 | SAFE     | Safehold Inc.                                        | US       |                0.95 |                     0.1  |    -0.03 |     -0.1  |                  55.36 |                        53.04 |         36.14 |         45.71 |          53.52 |        58.51 |           74.95 |             45.92 |         5.32 |
|              16 | NAVI     | Navient Corporation                                  | US       |                0.75 |                     0.03 |    -0.03 |      0.07 |                  60.78 |                        52.95 |         57.53 |         51.77 |          42.53 |        42.64 |           31.95 |             57.83 |         7.31 |
|              17 | MFA      | MFA Financial, Inc.                                  | US       |                0.81 |                     0.03 |     0.02 |     -0.04 |                  47.35 |                        52.85 |         46.07 |         43.11 |          53.35 |        62.61 |           82.67 |             41.2  |         3.64 |
|              18 | INVA     | Innoviva, Inc.                                       | US       |                1.3  |                     0.05 |    -0.02 |     -0.07 |                  71.85 |                        52.52 |         32.94 |         34.44 |          50.97 |        63.93 |           90.07 |             43.4  |         3.59 |
|              19 | ALL-PH   | The Allstate Corporation                             | US       |               24.91 |                     0.04 |    -0.01 |     -0.04 |                  64.99 |                        52.21 |         40.19 |         40.75 |          53.61 |        70.46 |           73.79 |             48.87 |         1.43 |
|              20 | SUZ      | Suzano S.A.                                          | OTHER    |                8.53 |                     0.06 |    -0.03 |     -0.03 |                  74.88 |                        49.39 |         33.17 |         33.83 |          45.2  |        58.56 |           70.51 |             47.64 |         3.17 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | KSS      | Kohl's Corporation           | US       |                1.93 |             66.43 |         67.72 |         65.49 |          63.04 |        67.36 |           74.57 |             52.72 |             57.86 |         8.39 |             86.67 | short              |                3.24 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.02 |             41.83 |         55.13 |         42.03 |          37.48 |        41.62 |           31.21 |             32.9  |             56.09 |         4.46 |             74.95 | short              |                1.14 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.9  |             40.15 |         37.79 |         24.72 |          42.51 |        58.67 |           79.73 |             21.61 |             60.89 |         9.08 |             77.55 | long               |                1.35 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             37.82 |         40.88 |         25.42 |          34.76 |        46.47 |           52.87 |             39.53 |             60.48 |         7.04 |             75.4  | long               |                3.91 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             37.48 |         31.75 |         31.66 |          43.2  |        59.73 |           72    |             29.63 |             75.22 |         4.89 |             81.52 | long               |               -1.06 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.88 |             33.39 |         59.79 |         26.53 |          27.59 |        39.2  |           32.88 |             30.6  |             69    |         7.73 |             75.24 | short              |                5.41 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.44 |             26.78 |         28.32 |         23.83 |          25.62 |        27.95 |           26.4  |             42.92 |             29.33 |         6.85 |             76.61 | short              |               -2.51 |                   nan |                  nan |

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
- `ret_63d_rank` vs `sector_score`: r=0.85

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
- Excluded by hard/data filters: **296**
- Event watch (otherwise eligible): **7**
- Final eligible: **697**
- Eligible change vs previous stored run: **+593**

Top exclusion categories:
- liquidity: 244
- price: 180
- market_cap: 156
- data_confidence: 26
- price_history: 22
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| YPF | 196 | 4 | 5 | 6 | 2 | value,pullback,quality_value |
| PKX | 399 | 10 | 6 | 8 | 2 | value,pullback,quality_value |
| PARR | 17 | 7 |  | 5 | 1 | value,quality_value |
| TNK | 84 | 6 |  | 4 | 1 | value,quality_value |
| SM | 150 | 1 |  | 1 | 1 | value,quality_value |
| EMBC | 349 | 3 |  | 7 | 1 | value,quality_value |
| IHS | 371 | 8 |  | 9 | 1 | value,quality_value |
| IRS | 500 | 5 | 12 | 3 | 1 | value,quality_value |
| MOMO | 548 | 2 | 14 | 2 | 1 | value,quality_value |
| PBF | 1 |  |  |  | 1 | main |
| HPE | 2 |  |  |  | 1 | main |
| ZD | 3 |  |  |  | 1 | main |
| ABCL | 4 |  |  |  | 1 | main |
| DELL | 5 |  |  |  | 1 | main |
| TWST | 6 |  |  |  | 1 | main |

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
| 1 | MOMO | value+pullback | 71.16 | 76.41 | 67.55 | 66.72 | 59.53 | 76.96 | 47.77 |
| 2 | IRS | value+pullback | 70.90 | 71.84 | 70.14 | 85.95 | 45.22 | 72.01 | 51.08 |
| 3 | INVA | value+pullback | 69.85 | 58.80 | 71.85 | 90.07 | 43.40 | 81.97 | 42.71 |
| 4 | YPF | value+pullback | 69.30 | 76.07 | 69.41 | 70.22 | 66.12 | 59.89 | 67.03 |
| 5 | GSL | value+pullback | 68.88 | 69.58 | 72.25 | 73.10 | 41.53 | 74.13 | 56.44 |
| 6 | SUZ | value+pullback | 67.68 | 65.46 | 74.88 | 70.51 | 47.64 | 69.91 | 39.52 |
| 7 | PKX | value+pullback | 65.44 | 62.88 | 53.07 | 87.54 | 68.80 | 66.47 | 56.85 |
| 8 | ALL-PH | value+pullback | 63.44 | 63.27 | 64.99 | 73.79 | 48.87 | 61.30 | 47.18 |
| 9 | BHF | value+pullback | 63.34 | 70.60 | 59.95 | 57.81 | 48.85 | 68.10 | 47.05 |
| 10 | DAC | value+pullback | 62.91 | 58.80 | 54.47 | 74.94 | 56.16 | 73.97 | 67.07 |
| 11 | CLW | value+pullback | 61.81 | 55.03 | 80.37 | 50.18 | 62.93 | 56.95 | 60.19 |
| 12 | HMC | value+pullback | 60.58 | 56.96 | 44.39 | 73.25 | 82.62 | 65.69 | 64.76 |
| 13 | MFA | value+pullback | 59.29 | 58.31 | 47.35 | 82.67 | 41.20 | 67.20 | 49.71 |
| 14 | WKC | value+pullback | 56.90 | 56.29 | 57.60 | 46.49 | 70.79 | 57.78 | 64.33 |
| 15 | MTRX | value+pullback | 56.43 | 68.70 | 50.17 | 46.24 | 62.20 | 50.62 | 46.66 |
| 16 | SM | value | 54.80 | 83.54 | 51.09 | 82.61 | 51.48 | 60.98 | 69.67 |
| 17 | TNK | value | 54.22 | 68.98 | 30.95 | 70.87 | 72.19 | 78.37 | 73.02 |
| 18 | PARR | value | 52.36 | 69.27 | 58.94 | 77.39 | 72.00 | 63.83 | 80.77 |
| 19 | GBLB.BR | pullback | 52.27 | 51.81 | 81.78 |  |  | 96.61 | 33.33 |
| 20 | IHS | value | 51.55 | 69.75 | 37.27 | 60.00 | 83.39 | 66.42 | 58.27 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 0/10 | 0/10 | 10/10 | 0/10 | 10/10 | 62.8 | 10 / 0 |
| Top 25 | 1/25 | 1/25 | 25/25 | 1/25 | 24/25 | 62.8 | 23 / 2 |
| Top 50 | 1/50 | 2/50 | 50/50 | 1/50 | 48/50 | 62.8 | 43 / 7 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=5, large_20_100b=2, mega_100b_plus=1
Top-10 sparse-data names: PBF (missing quality,revisions; conf=62.8), HPE (missing quality,revisions; conf=62.8), ZD (missing quality,revisions; conf=62.8), ABCL (missing quality,revisions; conf=60.0), DELL (missing quality,revisions; conf=61.9), TWST (missing quality,revisions; conf=60.0), HRB (missing quality,revisions; conf=61.9), DINO (missing quality,revisions; conf=62.8), VLO (missing quality,revisions; conf=62.8), TXG (missing quality,revisions; conf=62.8)
