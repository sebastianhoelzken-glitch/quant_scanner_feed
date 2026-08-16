# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-16

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
- **OTHER:** 77.8/100
- **US:** 87.4/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PBF       | PBF       | US       |                7.36 |             93.12 |         87.49 |         92.95 |          95.13 |        93.28 |             nan |               nan |             90.14 |         7    |             62.84 | medium             |                0.42 |                   nan |                  nan |
|      2 | RMAX      | RMAX      | US       |                0.6  |             87.16 |         87.44 |         89.26 |          84.65 |        86.89 |             nan |               nan |             91.68 |         7.11 |             62.84 | swing              |                0.57 |                   nan |                  nan |
|      3 | RBI.VI    | RBI.VI    | EUROPE   |               20.65 |             86.83 |         76.93 |         86    |          88.54 |        87.66 |             nan |               nan |             84.07 |         3.61 |             62.84 | medium             |                4.5  |                   nan |                  nan |
|      4 | DINO      | DINO      | US       |               14.39 |             86.74 |         80.04 |         86.63 |          88.86 |        86.85 |             nan |               nan |             82.87 |         3.93 |             62.84 | medium             |                0.55 |                   nan |                  nan |
|      5 | HPE       | HPE       | US       |               67.18 |             86.29 |         84.21 |         92.06 |          88.37 |        74.31 |             nan |               nan |             58.58 |         6.72 |             62.84 | swing              |                0.18 |                   nan |                  nan |
|      6 | UMAC      | UMAC      | US       |                1.47 |             86.23 |         89.81 |         93.47 |          82.65 |        64.54 |             nan |               nan |             42.72 |         9.09 |             60    | swing              |                4.89 |                   nan |                  nan |
|      7 | HRB       | HRB       | US       |                5.91 |             86.11 |         89.47 |         92.8  |          79.19 |        82.74 |             nan |               nan |             93.39 |         6.94 |             61.93 | swing              |                0.24 |                   nan |                  nan |
|      8 | ABCL      | ABCL      | US       |                3.02 |             85.9  |         90.25 |         95.51 |          81.55 |        64.43 |             nan |               nan |             46.42 |         9.02 |             60    | swing              |                0.05 |                   nan |                  nan |
|      9 | ZD        | ZD        | US       |                1.64 |             85.39 |         67.36 |         83.63 |          87.47 |        87.16 |             nan |               nan |             88.69 |         5.27 |             62.84 | medium             |                0.63 |                   nan |                  nan |
|     10 | MPC       | MPC       | US       |               86.25 |             85.03 |         83.54 |         88.92 |          86.51 |        77.07 |             nan |               nan |             65.78 |         3.87 |             62.84 | swing              |                0.49 |                   nan |                  nan |
|     11 | GH        | GH        | US       |               18.23 |             84.28 |         47.36 |         78.92 |          89.64 |        95.51 |             nan |               nan |            nan    |         6.75 |             59.09 | long               |                0.08 |                   nan |                  nan |
|     12 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.73 |             84.19 |         79.03 |         81.01 |          87.36 |        95.49 |             nan |               nan |             99.75 |         3.29 |             60    | long               |                0.69 |                   nan |                  nan |
|     13 | DELL      | DELL      | US       |              274.03 |             83.83 |         83.46 |         91.62 |          84.19 |        60.35 |             nan |               nan |             33.61 |         7.66 |             61.93 | swing              |                0.03 |                   nan |                  nan |
|     14 | MAN       | MAN       | US       |                2.34 |             83.74 |         79.16 |         92.42 |          86.73 |        80.74 |             nan |               nan |             75.18 |         7.83 |             62.84 | swing              |              nan    |                   nan |                  nan |
|     15 | GPN       | GPN       | US       |               21.28 |             83.72 |         83.37 |         84.22 |          73.57 |        84.08 |             nan |               nan |             96.74 |         5.56 |             62.84 | swing              |                0.28 |                   nan |                  nan |
|     16 | CAKE      | CAKE      | US       |                4.88 |             83.49 |         89.44 |         90.38 |          77.55 |        53.97 |             nan |               nan |             27.89 |         5.62 |             62.84 | swing              |                0.06 |                   nan |                  nan |
|     17 | NWL       | NWL       | US       |                2.3  |             83.16 |         82.54 |         86.91 |          77.44 |        83.79 |             nan |               nan |             89.17 |         8.05 |             62.84 | swing              |                0.47 |                   nan |                  nan |
|     18 | TXG       | TXG       | US       |                6.31 |             83.12 |         87.61 |         89.51 |          78.63 |        44.82 |             nan |               nan |              6.8  |         6.94 |             62.84 | swing              |                0.09 |                   nan |                  nan |
|     19 | ANRO      | ANRO      | US       |                1.09 |             82.49 |         83.62 |         85.19 |          81.37 |        62.19 |             nan |               nan |             38.52 |         7.17 |             60    | swing              |                0.3  |                   nan |                  nan |
|     20 | OSCR      | OSCR      | US       |                8.74 |             82.47 |         82.23 |         86.92 |          82.7  |        65.17 |             nan |               nan |             45.89 |         8.23 |             62.84 | swing              |                0.34 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                           | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                  | EUROPE   |                3.11 |                  72.43 |                    75.85 |                 78.81 |              74.35 |                90.01 |                    9.99 |           94.89 |             59.92 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | IRWD     | Ironwood Pharmaceuticals, Inc. | US       |                0.62 |                  73.27 |                    75.54 |                 78.29 |              74.72 |                81.13 |                   18.87 |           88.44 |             73.63 |       0.171 |         nan |       nan |        4.32 |         2.93 |          5.46 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | STNE     | StoneCo Ltd.                   | OTHER    |                2.01 |                  77.27 |                    74.35 |                 74.06 |              73.38 |                75.52 |                   24.48 |           86.96 |             41.46 |       0.611 |         nan |       nan |        1.48 |         4.1  |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | MOMO     | Hello Group Inc.               | OTHER    |                0.73 |                  79.3  |                    73.6  |                 72.4  |              76.32 |                75.49 |                   24.51 |           67.79 |             56.33 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | ACA.PA   | ACA.PA                         | EUROPE   |               61.12 |                  68.46 |                    73.35 |                 74.16 |              73.02 |                91.26 |                    8.74 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.13 |         10    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                         | EUROPE   |               15.31 |                  65.51 |                    72.56 |                 73.73 |              72.09 |                98.41 |                    1.59 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          8.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PARR     | Par Pacific Holdings, Inc.     | US       |                3.48 |                  72.12 |                    71.87 |                 73.51 |              71.32 |                69.17 |                   30.83 |           81.06 |             69.45 |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | 0QXR.IL  | Stellantis N.V.                | OTHER    |               25.94 |                  71.36 |                    71.87 |                 72.25 |              71.29 |                70.98 |                   29.02 |           74.6  |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BNP.PA   | BNP.PA                         | EUROPE   |              122.86 |                  68.13 |                    71.51 |                 72.07 |              71.29 |                83.89 |                   16.11 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.54 |          9.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | 0Q2N.IL  | K+S Aktiengesellschaft         | OTHER    |                2.84 |                  70.07 |                    70.89 |                 70.76 |              71.21 |                75.78 |                   24.22 |           68.98 |            nan    |       0.261 |         nan |       nan |        1.54 |       nan    |          2.65 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHEL     | SHEL                           | US       |              215.86 |                  67.71 |                    70.62 |                 71.11 |              70.43 |                81.3  |                   18.7  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                       | EUROPE   |              215.21 |                  66.9  |                    70.56 |                 71.17 |              70.31 |                83.96 |                   16.04 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.72 |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PRU      | PRU                            | US       |               37.3  |                  67.24 |                    70.42 |                 70.95 |              70.21 |                82.06 |                   17.94 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.5  |         11.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                             | US       |               62.63 |                  62.98 |                    70.26 |                 71.48 |              69.78 |                96.96 |                    3.04 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        12.03 |         14.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ARCC     | ARCC                           | US       |               12.33 |                  64.44 |                    69.81 |                 70.71 |              69.45 |                89.51 |                   10.49 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.28 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ADAM     | ADAM                           | US       |                0.79 |                  66.74 |                    69.45 |                 69.9  |              69.27 |                79.37 |                   20.63 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.24 |          6.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | ACCO     | Acco Brands Corporation        | US       |                0.35 |                  71.56 |                    68.66 |                 68.87 |              68.96 |                67.95 |                   32.05 |           74.64 |             52.13 |       0.103 |         nan |       nan |        8.07 |         4.54 |          7    |        0.83 |                 nan |              nan |                  12 |                  0.63 |
|          nan | AGN.AS   | AGN.AS                         | EUROPE   |               12.16 |                  61.75 |                    68.6  |                 69.75 |              68.15 |                93.75 |                    6.25 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.05 |         13.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | 0P6O.IL  | Volkswagen AG                  | OTHER    |               40.88 |                  65.12 |                    68.52 |                 70.15 |              66.2  |                70.49 |                   29.51 |           79    |            nan    |       0.423 |         nan |       nan |        7.45 |       nan    |          2.66 |        0.68 |                 nan |              nan |                   9 |                  0.47 |
|           10 | AVGO     | Broadcom Inc.                  | US       |             1615.59 |                  59.62 |                    68.43 |                 69.29 |              63.75 |                79.37 |                   20.63 |           82.97 |             65.41 |       0.015 |         nan |       nan |       45.5  |        20.12 |         65.39 |        0.44 |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                            | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:--------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                   | EUROPE   |                3.11 |                  72.43 |                    75.85 |                 78.81 |              74.35 |                90.01 |                    9.99 |           94.89 |             59.92 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | IRWD     | Ironwood Pharmaceuticals, Inc.  | US       |                0.62 |                  73.27 |                    75.54 |                 78.29 |              74.72 |                81.13 |                   18.87 |           88.44 |             73.63 |       0.171 |         nan |       nan |        4.32 |         2.93 |          5.46 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ACA.PA   | ACA.PA                          | EUROPE   |               61.12 |                  68.46 |                    73.35 |                 74.16 |              73.02 |                91.26 |                    8.74 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.13 |         10    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | STNE     | StoneCo Ltd.                    | OTHER    |                2.01 |                  77.27 |                    74.35 |                 74.06 |              73.38 |                75.52 |                   24.48 |           86.96 |             41.46 |       0.611 |         nan |       nan |        1.48 |         4.1  |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR   | AGS.BR                          | EUROPE   |               15.31 |                  65.51 |                    72.56 |                 73.73 |              72.09 |                98.41 |                    1.59 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.56 |          8.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PARR     | Par Pacific Holdings, Inc.      | US       |                3.48 |                  72.12 |                    71.87 |                 73.51 |              71.32 |                69.17 |                   30.83 |           81.06 |             69.45 |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | MOMO     | Hello Group Inc.                | OTHER    |                0.73 |                  79.3  |                    73.6  |                 72.4  |              76.32 |                75.49 |                   24.51 |           67.79 |             56.33 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           14 | AKER.OL  | Aker ASA                        | EUROPE   |                9.76 |                  54.01 |                    67.11 |                 72.38 |              60.19 |                73.25 |                   26.75 |           99.59 |             81.26 |       0.113 |         nan |       nan |        5.32 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            6 | 0QXR.IL  | Stellantis N.V.                 | OTHER    |               25.94 |                  71.36 |                    71.87 |                 72.25 |              71.29 |                70.98 |                   29.02 |           74.6  |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BNP.PA   | BNP.PA                          | EUROPE   |              122.86 |                  68.13 |                    71.51 |                 72.07 |              71.29 |                83.89 |                   16.11 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.54 |          9.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                              | US       |               62.63 |                  62.98 |                    70.26 |                 71.48 |              69.78 |                96.96 |                    3.04 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        12.03 |         14.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                        | EUROPE   |              215.21 |                  66.9  |                    70.56 |                 71.17 |              70.31 |                83.96 |                   16.04 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         9.72 |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                            | US       |              215.86 |                  67.71 |                    70.62 |                 71.11 |              70.43 |                81.3  |                   18.7  |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PRU      | PRU                             | US       |               37.3  |                  67.24 |                    70.42 |                 70.95 |              70.21 |                82.06 |                   17.94 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.5  |         11.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | 0Q2N.IL  | K+S Aktiengesellschaft          | OTHER    |                2.84 |                  70.07 |                    70.89 |                 70.76 |              71.21 |                75.78 |                   24.22 |           68.98 |            nan    |       0.261 |         nan |       nan |        1.54 |       nan    |          2.65 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | ARCC     | ARCC                            | US       |               12.33 |                  64.44 |                    69.81 |                 70.71 |              69.45 |                89.51 |                   10.49 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |        10.28 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | SDF.DE   | K+S Aktiengesellschaft        N | EUROPE   |                2.58 |                  63.74 |                    67.95 |                 70.45 |              65.29 |                75.97 |                   24.03 |           87.12 |             57.29 |       0.132 |         nan |       nan |        1.83 |        13.75 |          2.44 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|            9 | 0P6O.IL  | Volkswagen AG                   | OTHER    |               40.88 |                  65.12 |                    68.52 |                 70.15 |              66.2  |                70.49 |                   29.51 |           79    |            nan    |       0.423 |         nan |       nan |        7.45 |       nan    |          2.66 |        0.68 |                 nan |              nan |                   9 |                  0.47 |
|           12 | NWL.MI   | NewPrinces S.p.A.               | EUROPE   |                0.68 |                  64.28 |                    67.57 |                 70.02 |              66.91 |                82.94 |                   17.06 |           80.41 |             56.99 |       0.974 |         nan |       nan |        5.34 |      -120.77 |          2.12 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | ADAM     | ADAM                            | US       |                0.79 |                  66.74 |                    69.45 |                 69.9  |              69.27 |                79.37 |                   20.63 |          nan    |            nan    |     nan     |         nan |       nan |      nan    |         8.24 |          6.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                            | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:--------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | INDU-C.ST | AB Industrivärden (publ)        | EUROPE   |               20.34 |                     0.08 |    -0.06 |     -0    |                  74.54 |                        70.56 |         46.5  |         60.05 |          68.71 |        68.07 |           85.85 |             81.26 |         2.41 |
|               2 | INDU-A.ST | AB Industrivärden (publ)        | EUROPE   |               20.42 |                     0.08 |    -0.06 |     -0.01 |                  73.26 |                        69.57 |         41.6  |         58.45 |          67.43 |        65.08 |           85.85 |             81.26 |         2.55 |
|               3 | IRWD      | Ironwood Pharmaceuticals, Inc.  | US       |                0.62 |                     0.02 |    -0    |      0.12 |                  52.87 |                        69.13 |         64.93 |         60.23 |          71.54 |        82.45 |           88.44 |             73.63 |         6.47 |
|               4 | AMZN      | Amazon.com, Inc.                | US       |             2448.02 |                     0.08 |    -0.04 |      0.06 |                  70.87 |                        67.35 |         59.38 |         57.77 |          62.97 |        61.34 |           80.86 |             72.37 |         5.62 |
|               5 | ALL       | The Allstate Corporation        | US       |               57.12 |                     0.05 |    -0.02 |      0.05 |                  73.72 |                        66.48 |         58.78 |         64.13 |          61.61 |        55.35 |           67.7  |             65.43 |         2.95 |
|               6 | MSFT      | Microsoft Corporation           | US       |             3178.69 |                     0.02 |    -0.01 |      0.26 |                  52.5  |                        66.44 |         72.79 |         66.28 |          56.13 |        52.35 |           60.78 |             66.73 |         5.67 |
|               7 | LLY       | Eli Lilly and Company           | US       |              909.38 |                     0.04 |    -0    |      0    |                  62.9  |                        64.38 |         51.82 |         58.19 |          63.53 |        61.96 |           79.35 |             66.57 |         4.18 |
|               8 | WKC       | World Kinect Corporation        | US       |                1.6  |                     0.1  |    -0.01 |     -0.01 |                  43.77 |                        63.3  |         52.92 |         68.24 |          69.82 |        64.61 |           56.82 |             74.97 |         4.83 |
|               9 | AVGO      | Broadcom Inc.                   | US       |             1615.59 |                     0.08 |    -0.08 |      0.06 |                  78.27 |                        62.87 |         47.23 |         49.44 |          60.08 |        61.57 |           82.97 |             65.41 |         6.07 |
|              10 | GOLD      | Gold.com, Inc.                  | US       |                1.1  |                     0.02 |     0.01 |      0.15 |                  42.92 |                        62.06 |         66.78 |         53.3  |          54.67 |        51.88 |           48.31 |             83.83 |         5.69 |
|              11 | CLW       | Clearwater Paper Corporation    | US       |                0.3  |                     0.08 |    -0.08 |      0.34 |                  78.34 |                        62    |         65    |         62.13 |          48.95 |        43.69 |           39.36 |             65.84 |         6.79 |
|              12 | LNC       | Lincoln National Corporation    | US       |                7.52 |                     0.03 |    -0.01 |      0.08 |                  60.68 |                        60.12 |         65.69 |         65.02 |          56.29 |        55.81 |           43.27 |             63.48 |         4.59 |
|              13 | GAIN      | Gladstone Investment Corporatio | US       |                0.56 |                     0.03 |    -0.02 |     -0.01 |                  61.9  |                        60.04 |         51.86 |         54.78 |          57.94 |        53.43 |           65.02 |             69.11 |         3.18 |
|              14 | ACCO      | Acco Brands Corporation         | US       |                0.35 |                     0.02 |    -0.02 |      0.06 |                  51.24 |                        59.9  |         58.17 |         58.93 |          60.77 |        68.44 |           74.64 |             52.13 |         5.38 |
|              15 | GSL       | Global Ship Lease Inc New       | OTHER    |                1.31 |                     0.05 |    -0.01 |      0.05 |                  70.66 |                        59.69 |         57.34 |         53.03 |          59.55 |        63.79 |           73.11 |             38.66 |         3.68 |
|              16 | V         | Visa Inc.                       | US       |              587.49 |                     0.02 |     0.01 |      0.02 |                  44.34 |                        59.12 |         56.55 |         57.83 |          53.97 |        49.12 |           68.88 |             65.15 |         2.84 |
|              17 | NESN.SW   | Nestlé S.A.                     | EUROPE   |              221.55 |                     0.06 |    -0    |     -0.05 |                  68.53 |                        58.75 |         44.44 |         46.55 |          54.67 |        54.42 |           77.6  |             64.51 |         2.73 |
|              18 | SDF.DE    | K+S Aktiengesellschaft        N | EUROPE   |                2.58 |                     0.03 |    -0    |      0    |                  54.92 |                        58.74 |         48.96 |         44.09 |          57.52 |        66.81 |           87.12 |             57.29 |         4.23 |
|              19 | GTN       | Gray Media, Inc.                | US       |                0.46 |                     0.03 |    -0.03 |      0.32 |                  62.22 |                        57.92 |         63.97 |         54.3  |          47.6  |        53.69 |           50.86 |             42.82 |         5.76 |
|              20 | CION      | CION Investment Corporation     | US       |                0.32 |                     0.02 |     0    |      0.23 |                  48.34 |                        57.77 |         69.31 |         52.8  |          43.63 |        47.34 |           34.78 |             59.41 |         6.22 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4712.46 |             64.22 |         67.14 |         57.22 |          62.84 |        65.59 |           94.57 |             60.71 |             30.53 |         5.43 |             89.53 | short              |                0.21 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.88 |             59.88 |         58.68 |         61.09 |          57.11 |        61.72 |           54.97 |             51.18 |             71.96 |         8.34 |             85.47 | long               |                0.28 |                   nan |                  nan |
|    nan | JOYY     | JOYY Inc.                    | OTHER    |                3.18 |             53.49 |         52.12 |         58.61 |          54.87 |        48.79 |           49.81 |             51.23 |             32.32 |         4.78 |             81.91 | swing              |                0.06 |                   nan |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.      | US       |                3.38 |             46.33 |         34.78 |         42.97 |          49.69 |        62.65 |           67.44 |             47.39 |             78.89 |         7.47 |             87.57 | long               |                0.31 |                   nan |                  nan |
|    nan | ATHM     | Autohome Inc.                | OTHER    |                2.26 |             43.17 |         51.26 |         48.65 |          37.7  |        34.95 |           32.89 |             30.42 |             35.2  |         6.03 |             78.55 | short              |                0.57 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.89 |             38.01 |         25.14 |         33.83 |          42.18 |        53.81 |           49.1  |             48.35 |             78.76 |         6.19 |             78.58 | long               |               -0.4  |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.29 |             37.83 |         27.9  |         34.78 |          40.88 |        53.72 |           46.72 |             42.26 |             86.54 |         7.19 |             78.43 | long               |               -0.34 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             36.98 |         32.17 |         31.17 |          41.78 |        59.33 |           71.99 |             26.33 |             77.84 |         4.73 |             81.52 | long               |               -0.27 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.76 |             35.63 |         39.75 |         24.54 |          31.51 |        40.23 |           44.83 |             38.36 |             49.64 |         7.05 |             75.4  | long               |                0.03 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.89 |             33.98 |         30.42 |         22.43 |          37.55 |        49.26 |           68.02 |             20.14 |             44.44 |         9.01 |             77.55 | long               |               -0.07 |                   nan |                  nan |
|    nan | AT1.DE   | Aroundtown SA                | EUROPE   |                2.21 |             33.48 |         31.88 |         27.69 |          35.07 |        44.88 |           54    |             37.93 |             51.43 |         5.45 |             75.53 | long               |               -2.41 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             26.24 |         52.53 |         22.78 |          22.08 |        29.69 |           24.32 |             27.06 |             50    |         7.7  |             75.24 | short              |               -0.14 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.4  |             20.88 |         27.64 |         21.21 |          20.55 |        20.21 |           15.41 |             40.25 |             20.79 |         6.86 |             75.64 | short              |               -2.07 |                   nan |                  nan |

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
- Excluded by hard/data filters: **281**
- Event watch (otherwise eligible): **13**
- Final eligible: **706**
- Eligible change vs previous stored run: **+2**

Top exclusion categories:
- liquidity: 225
- price: 169
- market_cap: 153
- price_history: 21
- data_confidence: 20
- duplicate_listing: 4
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| IRWD | 210 | 2 | 3 | 2 | 2 | value,pullback,quality_value |
| AVGO | 467 | 10 | 9 | 12 | 2 | value,pullback |
| PARR | 77 | 5 |  | 4 | 1 | value,quality_value |
| BION.SW | 165 | 1 |  | 1 | 1 | value,quality_value |
| 0Q2N.IL | 490 | 7 |  | 8 | 1 | value,quality_value |
| 0QXR.IL | 521 | 6 |  | 7 | 1 | value,quality_value |
| MOMO | 585 | 4 | 34 | 5 | 1 | value,quality_value |
| 0P6O.IL | 643 | 9 |  | 10 | 1 | value,quality_value |
| STNE | 656 | 3 |  | 3 | 1 | value,quality_value |
| PBF | 1 |  |  |  | 1 | main |
| RMAX | 2 |  |  |  | 1 | main |
| RBI.VI | 3 |  |  |  | 1 | main |
| DINO | 4 |  |  |  | 1 | main |
| HPE | 5 |  |  |  | 1 | main |
| UMAC | 6 |  |  |  | 1 | main |

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
| 1 | MOMO | value+pullback | 72.44 | 79.30 | 71.01 | 67.79 | 56.33 | 75.49 | 46.49 |
| 2 | AVGO | value+pullback | 72.31 | 59.62 | 78.27 | 82.97 | 65.41 | 79.37 | 54.76 |
| 3 | IRWD | value+pullback | 72.05 | 73.27 | 52.87 | 88.44 | 73.63 | 81.13 | 68.24 |
| 4 | 0P6O.IL | value+pullback | 68.22 | 65.12 | 70.96 | 79.00 |  | 70.49 | 42.42 |
| 5 | SDF.DE | value+pullback | 66.84 | 63.74 | 54.92 | 87.12 | 57.29 | 75.97 | 53.24 |
| 6 | VOW3.DE | value+pullback | 66.68 | 71.28 | 72.32 | 65.84 | 45.06 | 64.19 | 40.15 |
| 7 | IRS | value+pullback | 66.44 | 60.82 | 71.80 | 81.05 | 43.99 | 68.44 | 49.20 |
| 8 | 0Q2N.IL | value+pullback | 65.84 | 70.07 | 57.28 | 68.98 |  | 75.78 | 53.29 |
| 9 | ACCO | value+pullback | 64.28 | 71.56 | 51.24 | 74.64 | 52.13 | 67.95 | 59.85 |
| 10 | MTRX | value+pullback | 64.08 | 70.82 | 60.49 | 65.00 | 62.13 | 58.74 | 49.44 |
| 11 | PBR-A | value+pullback | 63.52 | 73.63 | 65.72 | 54.53 | 69.33 | 49.46 | 55.35 |
| 12 | GSL | value+pullback | 63.39 | 56.91 | 70.66 | 73.11 | 38.66 | 69.12 | 58.44 |
| 13 | ALL-PH | value+pullback | 61.18 | 62.26 | 65.08 | 67.70 | 42.82 | 58.96 | 43.36 |
| 14 | CNXC | value+pullback | 60.89 | 83.95 | 70.58 | 45.38 | 33.25 | 39.63 | 40.16 |
| 15 | 1VOW3.MI | value+pullback | 60.88 | 60.86 | 64.72 | 65.84 | 38.64 | 63.55 | 40.16 |
| 16 | BHF | value+pullback | 60.33 | 71.19 | 55.64 | 51.68 | 43.78 | 64.65 | 42.95 |
| 17 | BION.SW | value | 59.96 | 72.43 | 40.38 | 94.89 | 59.92 | 90.01 | 70.86 |
| 18 | VOW.DE | value+pullback | 59.93 | 60.94 | 63.50 | 65.84 | 34.41 | 62.30 | 37.14 |
| 19 | MFA | value+pullback | 59.56 | 58.61 | 53.52 | 78.94 | 38.75 | 64.43 | 45.65 |
| 20 | WKC | value+pullback | 58.86 | 60.34 | 43.77 | 56.82 | 74.97 | 68.96 | 66.43 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 0/10 | 0/10 | 10/10 | 0/10 | 10/10 | 62.8 | 10 / 0 |
| Top 25 | 0/25 | 0/25 | 24/25 | 0/25 | 25/25 | 62.8 | 24 / 1 |
| Top 50 | 1/50 | 1/50 | 49/50 | 1/50 | 49/50 | 62.8 | 42 / 8 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=3, large_20_100b=3
Top-10 sparse-data names: PBF (missing quality,revisions; conf=62.8), RMAX (missing quality,revisions; conf=62.8), RBI.VI (missing quality,revisions; conf=62.8), DINO (missing quality,revisions; conf=62.8), HPE (missing quality,revisions; conf=62.8), UMAC (missing quality,revisions; conf=60.0), HRB (missing quality,revisions; conf=61.9), ABCL (missing quality,revisions; conf=60.0), ZD (missing quality,revisions; conf=62.8), MPC (missing quality,revisions; conf=62.8)
