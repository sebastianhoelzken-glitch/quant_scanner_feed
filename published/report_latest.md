# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-24

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

- **EUROPE:** 79.5/100
- **OTHER:** 73.0/100
- **US:** 79.9/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC       | MPC       | US       |               99.04 |             80.92 |         74    |         83.04 |          83.48 |        78.79 |           84.82 |             90.55 |             63.29 |         4.37 |             73.14 | medium             |               -6.23 |                nan    |               nan    |
|      2 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.89 |             80.61 |         77.96 |         80.16 |          82.96 |        81.07 |           96.35 |             78.35 |             61.93 |         3.71 |             73.14 | medium             |               -3.57 |                  0.89 |                 0.92 |
|      3 | MU        | MU        | US       |             1057.46 |             79.26 |         77.58 |         70.43 |          82.76 |        80.95 |           94.8  |             83.51 |             64.43 |         8.24 |             73.14 | medium             |               -1.5  |                  2.07 |                 1.61 |
|      4 | HPE       | HPE       | US       |               72.28 |             79.21 |         87.52 |         80.93 |          77.5  |        67.98 |           73.25 |             83.01 |             44.55 |         7.01 |             72.34 | short              |               -2.14 |                 -0.12 |               nan    |
|      5 | DELL      | DELL      | US       |              305.37 |             78.32 |         80.67 |         79.43 |          77.2  |        64.57 |           72.27 |             87.79 |             30.17 |         7.85 |             72.23 | short              |               -5.3  |                 -0.78 |                -0.74 |
|      6 | VLO       | VLO       | US       |               94.53 |             78.14 |         72.99 |         80.32 |          80.88 |        75.95 |           86.33 |             82.43 |             54.42 |         3.71 |             69.68 | medium             |               -7.61 |                  0.17 |                 0.3  |
|      7 | FRO       | FRO       | US       |                9.25 |             77.95 |         78.55 |         77.35 |          79.73 |        76.48 |           90.97 |             81.86 |             51.76 |         5.58 |             73.14 | medium             |               -6.97 |                 -0.29 |                -0.13 |
|      8 | PSX       | PSX       | US       |               89.4  |             76.97 |         75.27 |         80.43 |          78.67 |        73.18 |           79.74 |             87.08 |             52.56 |         3.85 |             73.14 | swing              |               -6.89 |                  0.38 |                 0.62 |
|      9 | REP.MC    | REP.MC    | EUROPE   |               32.74 |             76.4  |         81.14 |         79.33 |          73.47 |        69.2  |           61.08 |             81.59 |             68.48 |         3.78 |             73.14 | short              |                1.75 |                  1.44 |                 1.16 |
|     10 | AMC       | AMC       | US       |                2.24 |             76.33 |         77.05 |         80.83 |          75.61 |        73.95 |           83    |             78.89 |            nan    |         9.53 |             65.07 | swing              |                0.14 |                  3.49 |                 3.39 |
|     11 | SHELL.AS  | SHELL.AS  | EUROPE   |              237.89 |             75.53 |         77.49 |         73.56 |          73.11 |        78.56 |           93.88 |             83.82 |             63.65 |         2.45 |             73.14 | long               |                1.38 |                  2.29 |                 2.24 |
|     12 | KIN.BR    | KIN.BR    | EUROPE   |                1.36 |             75.46 |         78.62 |         78    |          72.92 |        64.19 |           90.65 |             64.96 |             18.29 |         3.79 |             73.14 | short              |               -2.29 |                 -0.65 |                -0.49 |
|     13 | AMS.SW    | AMS.SW    | EUROPE   |                2.49 |             75.07 |         85.29 |         80.76 |          69.37 |        51.2  |           54.29 |             90.16 |              8.74 |         8.67 |             73.14 | short              |                3.99 |                  5.09 |               nan    |
|     14 | HSHP      | HSHP      | US       |                0.75 |             74.96 |         80.77 |         75.96 |          73.96 |        64.27 |           85.86 |            nan    |             22.3  |         4.84 |             62.84 | short              |               -7.85 |                nan    |               nan    |
|     15 | ABN.AS    | ABN.AS    | EUROPE   |               35.45 |             74.8  |         75.69 |         75.49 |          74.11 |        68.87 |           79.64 |             70.37 |             49.38 |         2.87 |             73.14 | short              |               -1.26 |                  1.15 |                 1.19 |
|     16 | DHT       | DHT       | US       |                3    |             74.74 |         73.73 |         72.6  |          76.05 |        75.75 |           87.42 |             84.55 |             55.65 |         4.77 |             73.14 | medium             |               -7.32 |                 -0.33 |                -0.36 |
|     17 | PBR-A     | PBR-A     | US       |              114.95 |             74.63 |         81.46 |         73.36 |          70    |        75.91 |           74.11 |             71.18 |             84.61 |         4.55 |             69.89 | short              |                0.11 |                  0.23 |                -0.02 |
|     18 | OKTA      | OKTA      | US       |               31.36 |             74.2  |         87.46 |         79.65 |          68.76 |        55.09 |           69.13 |             69.98 |             11.37 |         7.84 |             71.77 | short              |               -4.32 |                  0.09 |                 0.29 |
|     19 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.3  |             73.41 |         59.72 |         68.66 |          78.15 |        80.75 |           72.62 |            nan    |             98.5  |         4.32 |             62.84 | long               |               -1.77 |                nan    |               nan    |
|     20 | NAT       | NAT       | US       |                1.41 |             73.09 |         76.5  |         72.35 |          73.84 |        68.85 |           87.38 |             70.17 |             34.5  |         4.96 |             73.14 | short              |               -7.47 |                 -1    |                -0.68 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              237.89 |                  62.21 |                    73.69 |                 77.37 |              69.17 |                88.86 |                   11.14 |           93.88 |             83.82 |         nan |         nan |       nan |         nan |         9.5  |         10.58 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP       | US       |              100.09 |                  60.79 |                    71.32 |                 74.81 |              67.4  |                82.79 |                   17.21 |           87.81 |             87.26 |         nan |         nan |       nan |         nan |         9.11 |         20.6  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |              114.95 |                  69.89 |                    70.82 |                 71.26 |              70.17 |                70.74 |                   29.26 |           74.11 |             71.18 |         nan |         nan |       nan |         nan |         4.78 |          4.8  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL     | US       |              237.78 |                  65.71 |                    70.45 |                 71.82 |              69.32 |                76.99 |                   23.01 |           73.9  |             81.52 |         nan |         nan |       nan |         nan |         9.21 |         10.55 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              175.88 |                  66.26 |                    69.06 |                 69.74 |              68.84 |                73.64 |                   26.36 |           68.27 |             78.74 |         nan |         nan |       nan |         nan |         9    |         11.44 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR  | EUROPE   |                4.89 |                  54.47 |                    68.55 |                 73.23 |              62.5  |                85.84 |                   14.16 |           96.35 |             78.35 |         nan |         nan |       nan |         nan |         9.3  |          6.53 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM       | US       |                7.13 |                  61.18 |                    68.39 |                 71.1  |              65.37 |                72.66 |                   27.34 |           81.24 |             82.38 |         nan |         nan |       nan |         nan |         4.3  |          6.01 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT      | US       |                3    |                  56.75 |                    68.39 |                 72.26 |              63.94 |                81.26 |                   18.74 |           87.42 |             84.55 |         nan |         nan |       nan |         nan |         9.92 |          7.29 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO      | US       |                9.25 |                  56.12 |                    68.19 |                 72.36 |              63.09 |                80.57 |                   19.43 |           90.97 |             81.86 |         nan |         nan |       nan |         nan |        10.39 |          7.18 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               18.76 |                  55.08 |                    67.88 |                 72.06 |              61.9  |                85.7  |                   14.3  |           96.79 |             68.12 |         nan |         nan |       nan |         nan |        10.84 |         14.74 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR   | EUROPE   |               15.48 |                  62.58 |                    67.68 |                 69.33 |              64.18 |                77.56 |                   22.44 |           87.2  |             51.56 |         nan |         nan |       nan |         nan |         8.62 |          7.61 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS    | EUROPE   |               20.58 |                  62.77 |                    66.03 |                 66.81 |              64.83 |                73.76 |                   26.24 |           71.87 |             63.54 |         nan |         nan |       nan |         nan |         8.91 |         11.68 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY      | US       |              109.11 |                  62.56 |                    65.72 |                 66.77 |              63.63 |                71.33 |                   28.67 |           77.2  |             57.47 |         nan |         nan |       nan |         nan |         9.31 |         13.71 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR      | US       |              119    |                  69.03 |                    65.61 |                 64.92 |              64.72 |                60.52 |                   39.48 |           74.36 |             41.26 |         nan |         nan |       nan |         nan |         5.3  |          5.31 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               24.34 |                  54.92 |                    65.49 |                 69.08 |              59.5  |                80.75 |                   19.25 |           96.49 |             54.2  |         nan |         nan |       nan |         nan |        11.72 |         11.98 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | COP      | COP      | US       |              134.42 |                  60.23 |                    65.31 |                 66.92 |              63.85 |                71.02 |                   28.98 |           70.45 |             77.01 |         nan |         nan |       nan |         nan |        13.26 |         16.59 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX      | CVX      | US       |              352.14 |                  60.24 |                    65.22 |                 66.65 |              64.19 |                71.93 |                   28.07 |           67.79 |             78.7  |         nan |         nan |       nan |         nan |        15.14 |         19.91 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS | EUROPE   |               14.6  |                  56.22 |                    64.87 |                 67.46 |              61.29 |                79.43 |                   20.57 |           81.89 |             65.13 |         nan |         nan |       nan |         nan |        11.15 |         14.1  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | KEY      | KEY      | US       |               18.87 |                  58.09 |                    64.85 |                 67.09 |              61.26 |                74.95 |                   25.05 |           83.18 |             59.42 |         nan |         nan |       nan |         nan |         9.47 |         11.98 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | XOM      | XOM      | US       |              579.11 |                  58.06 |                    64.84 |                 66.88 |              62.91 |                73.77 |                   26.23 |           71.8  |             78.28 |         nan |         nan |       nan |         nan |        14.88 |         20.41 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              237.89 |                  62.21 |                    73.69 |                 77.37 |              69.17 |                88.86 |                   11.14 |           93.88 |             83.82 |         nan |         nan |       nan |         nan |         9.5  |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP       | US       |              100.09 |                  60.79 |                    71.32 |                 74.81 |              67.4  |                82.79 |                   17.21 |           87.81 |             87.26 |         nan |         nan |       nan |         nan |         9.11 |         20.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR  | EUROPE   |                4.89 |                  54.47 |                    68.55 |                 73.23 |              62.5  |                85.84 |                   14.16 |           96.35 |             78.35 |         nan |         nan |       nan |         nan |         9.3  |          6.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO      | US       |                9.25 |                  56.12 |                    68.19 |                 72.36 |              63.09 |                80.57 |                   19.43 |           90.97 |             81.86 |         nan |         nan |       nan |         nan |        10.39 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT      | US       |                3    |                  56.75 |                    68.39 |                 72.26 |              63.94 |                81.26 |                   18.74 |           87.42 |             84.55 |         nan |         nan |       nan |         nan |         9.92 |          7.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               18.76 |                  55.08 |                    67.88 |                 72.06 |              61.9  |                85.7  |                   14.3  |           96.79 |             68.12 |         nan |         nan |       nan |         nan |        10.84 |         14.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL     | US       |              237.78 |                  65.71 |                    70.45 |                 71.82 |              69.32 |                76.99 |                   23.01 |           73.9  |             81.52 |         nan |         nan |       nan |         nan |         9.21 |         10.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |              114.95 |                  69.89 |                    70.82 |                 71.26 |              70.17 |                70.74 |                   29.26 |           74.11 |             71.18 |         nan |         nan |       nan |         nan |         4.78 |          4.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM       | US       |                7.13 |                  61.18 |                    68.39 |                 71.1  |              65.37 |                72.66 |                   27.34 |           81.24 |             82.38 |         nan |         nan |       nan |         nan |         4.3  |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU       | US       |             1057.46 |                  49.43 |                    64.65 |                 70.13 |              57.93 |                77.73 |                   22.27 |           94.8  |             83.51 |         nan |         nan |       nan |         nan |         6.74 |         24.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              175.88 |                  66.26 |                    69.06 |                 69.74 |              68.84 |                73.64 |                   26.36 |           68.27 |             78.74 |         nan |         nan |       nan |         nan |         9    |         11.44 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC      | US       |               99.04 |                  49.79 |                    64.81 |                 69.6  |              59.79 |                82.7  |                   17.3  |           84.82 |             90.55 |         nan |         nan |       nan |         nan |         8.24 |         13.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR   | EUROPE   |               15.48 |                  62.58 |                    67.68 |                 69.33 |              64.18 |                77.56 |                   22.44 |           87.2  |             51.56 |         nan |         nan |       nan |         nan |         8.62 |          7.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               24.34 |                  54.92 |                    65.49 |                 69.08 |              59.5  |                80.75 |                   19.25 |           96.49 |             54.2  |         nan |         nan |       nan |         nan |        11.72 |         11.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | NVDA     | NVDA     | US       |             4756.66 |                  50.16 |                    64.28 |                 68.99 |              58.64 |                80.35 |                   19.65 |           89.08 |             80.62 |         nan |         nan |       nan |         nan |        14.38 |         28.91 |        0.49 |                 nan |              nan |                   6 |                  0.32 |
|          nan | VLO      | VLO      | US       |               94.53 |                  49.25 |                    63.79 |                 68.43 |              58.48 |                82.14 |                   17.86 |           86.33 |             82.43 |         nan |         nan |       nan |         nan |         9.88 |         15.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PSX      | PSX      | US       |               89.4  |                  50.62 |                    63.7  |                 67.78 |              59.56 |                80.05 |                   19.95 |           79.74 |             87.08 |         nan |         nan |       nan |         nan |        10.3  |         14.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EQNR     | EQNR     | US       |               88.83 |                  55.17 |                    64.57 |                 67.69 |              61.56 |                73.88 |                   26.12 |           75.84 |             85.46 |         nan |         nan |       nan |         nan |        10.44 |         11.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR   | EUROPE   |                1.67 |                  50.65 |                    63.31 |                 67.6  |              56.46 |                80.94 |                   19.06 |           98.14 |             54.23 |         nan |         nan |       nan |         nan |        10.44 |         10.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS | EUROPE   |               14.6  |                  56.22 |                    64.87 |                 67.46 |              61.29 |                79.43 |                   20.57 |           81.89 |             65.13 |         nan |         nan |       nan |         nan |        11.15 |         14.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | MPC       | MPC       | US       |               99.04 |                     0.09 |    -0.06 |      0.09 |                  69.68 |                        82.52 |         74    |         83.04 |          83.48 |        78.79 |           84.82 |             90.55 |         4.37 |
|               2 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.89 |                     0.07 |    -0.02 |      0.11 |                  70.16 |                        81.63 |         77.96 |         80.16 |          82.96 |        81.07 |           96.35 |             78.35 |         3.71 |
|               3 | FRO       | FRO       | US       |                9.25 |                     0.08 |    -0.05 |      0.17 |                  74.2  |                        80.88 |         78.55 |         77.35 |          79.73 |        76.48 |           90.97 |             81.86 |         5.58 |
|               4 | PSX       | PSX       | US       |               89.4  |                     0.06 |    -0.03 |      0.08 |                  73.84 |                        80.3  |         75.27 |         80.43 |          78.67 |        73.18 |           79.74 |             87.08 |         3.85 |
|               5 | VLO       | VLO       | US       |               94.53 |                     0.09 |    -0.07 |      0.1  |                  68.65 |                        80.09 |         72.99 |         80.32 |          80.88 |        75.95 |           86.33 |             82.43 |         3.71 |
|               6 | DELL      | DELL      | US       |              305.37 |                     0.07 |    -0.02 |      0.22 |                  71.27 |                        78.65 |         80.67 |         79.43 |          77.2  |        64.57 |           72.27 |             87.79 |         7.85 |
|               7 | DHT       | DHT       | US       |                3    |                     0.09 |    -0.08 |      0.11 |                  74.22 |                        78.16 |         73.73 |         72.6  |          76.05 |        75.75 |           87.42 |             84.55 |         4.77 |
|               8 | BP        | BP        | US       |              100.09 |                     0.05 |    -0.02 |      0.04 |                  75.07 |                        78.01 |         72.19 |         68.44 |          68.98 |        74.24 |           87.81 |             87.26 |         4.54 |
|               9 | SHELL.AS  | SHELL.AS  | EUROPE   |              237.89 |                     0.02 |    -0    |      0.06 |                  52.58 |                        77.98 |         77.49 |         73.56 |          73.11 |        78.56 |           93.88 |             83.82 |         2.45 |
|              10 | NAT       | NAT       | US       |                1.41 |                     0.08 |    -0.05 |      0.15 |                  71.11 |                        76.92 |         76.5  |         72.35 |          73.84 |        68.85 |           87.38 |             70.17 |         4.96 |
|              11 | SMTC      | SMTC      | US       |               13.8  |                     0.08 |     0.01 |      0.33 |                  49.35 |                        76.37 |         82.23 |         69.61 |          71.64 |        59.14 |           74.76 |             86.01 |         8.47 |
|              12 | EQNR      | EQNR      | US       |               88.83 |                     0.06 |    -0.03 |      0.04 |                  74.9  |                        75.22 |         67.31 |         71.99 |          71.03 |        70.23 |           75.84 |             85.46 |         5.72 |
|              13 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.76 |                     0.02 |    -0.02 |      0.05 |                  57.74 |                        74.76 |         73.05 |         70.16 |          73.13 |        75.09 |           96.79 |             68.12 |         2.23 |
|              14 | C5H.IR    | C5H.IR    | EUROPE   |                1.67 |                     0.05 |    -0    |      0.06 |                  67.99 |                        74.76 |         73.6  |         65.13 |          69.89 |        73.61 |           98.14 |             54.23 |         2.72 |
|              15 | MT.AS     | MT.AS     | EUROPE   |               47.69 |                     0.06 |    -0.02 |     -0.02 |                  72.8  |                        74.16 |         59.68 |         72.68 |          76.22 |        72.78 |           71.82 |             83.61 |         5.08 |
|              16 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.26 |                     0.02 |    -0.01 |      0.4  |                  49.44 |                        73.22 |         81.22 |         76.28 |          66.87 |        66.2  |           83.48 |             56.67 |         5.52 |
|              17 | DAR       | DAR       | US       |                8.46 |                     0.09 |    -0.06 |     -0.02 |                  65.59 |                        73    |         52.27 |         64.29 |          73.76 |        78    |           89.5  |             87.47 |         4.78 |
|              18 | PBR-A     | PBR-A     | US       |              114.95 |                     0.02 |     0.02 |      0.2  |                  42.76 |                        72.64 |         81.46 |         73.36 |          70    |        75.91 |           74.11 |             71.18 |         4.55 |
|              19 | FORTUM.HE | FORTUM.HE | EUROPE   |               21.44 |                     0.03 |     0.01 |      0.18 |                  56.46 |                        72.63 |         81.12 |         66.57 |          58.47 |        52.08 |           68.57 |             65.91 |         4.69 |
|              20 | SHEL      | SHEL      | US       |              237.78 |                     0.04 |    -0    |      0.03 |                  59.82 |                        72.51 |         73.05 |         69.7  |          67.34 |        71.01 |           73.9  |             81.52 |         3.03 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     13 | AMS.SW   | AMS.SW | EUROPE   |                2.49 |             75.07 |         85.29 |         80.76 |          69.37 |        51.2  |           54.29 |             90.16 |              8.74 |         8.67 |             73.14 | short              |                3.99 |                  5.09 |               nan    |
|    357 | ITRG     | ITRG   | US       |                0.49 |             52.33 |         51.62 |         52.23 |          52.44 |        60.47 |           58.52 |             61.84 |             77.53 |         8.26 |             68.32 | long               |               -3.46 |                  3.76 |                 4.28 |
|     10 | AMC      | AMC    | US       |                2.24 |             76.33 |         77.05 |         80.83 |          75.61 |        73.95 |           83    |             78.89 |            nan    |         9.53 |             65.07 | swing              |                0.14 |                  3.49 |                 3.39 |
|    114 | RBI.VI   | RBI.VI | EUROPE   |               21.1  |             63.52 |         68.84 |         67.67 |          59.37 |        46.12 |            9.97 |             72.02 |             65.14 |         4.42 |             71.77 | short              |                3.27 |                  3.36 |                 2.87 |
|    317 | SPM.MI   | SPM.MI | EUROPE   |                8.47 |             53.67 |         55.83 |         51.5  |          56.9  |        47.64 |          nan    |             59.43 |             26.54 |         4.04 |             70.3  | medium             |                5    |                  3.02 |                 2.88 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    472 | TEVA     | TEVA    | US       |               39.74 |             47.34 |         62.17 |         51.26 |          43.42 |        36.16 |           18.63 |             24.24 |             43.8  |         4.82 |             72.34 | short              |               -7.67 |                 -4.48 |                -4.35 |
|    473 | CNC      | CNC     | US       |               26.79 |             47.33 |         40.32 |         51.94 |          55.59 |        42.71 |           11.75 |             71.5  |             56.38 |         5.98 |             71.66 | medium             |              -11.9  |                 -4    |                -3.38 |
|    436 | CMPS     | CMPS    | US       |                1.66 |             48.96 |         43.34 |         54.57 |          55.6  |        39.65 |           42.48 |             49.56 |              5.66 |         7.91 |             69.27 | medium             |              -16.7  |                 -3.77 |                -3.81 |
|    307 | UMC      | UMC     | US       |               54.07 |             53.92 |         71.48 |         50.72 |          57.12 |        48.37 |           62.65 |             36.9  |             18.13 |         7.85 |             72.68 | short              |               -5.13 |                 -3.62 |                -3.69 |
|    669 | PAH3.DE  | PAH3.DE | EUROPE   |                8.01 |             33.51 |         33.33 |         27.53 |          33.69 |        57.12 |          nan    |             23.11 |             94.05 |         5.11 |             70.3  | long               |              -11.83 |                 -3.59 |                -3    |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `sector_score`: r=1.00
- `relative_63d_rank` vs `sector_score`: r=1.00
- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.88

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
- Excluded by hard/data filters: **288**
- Event watch (otherwise eligible): **0**
- Final eligible: **712**
- Eligible change vs previous stored run: **+3**

Top exclusion categories:
- liquidity: 238
- price: 181
- market_cap: 157
- price_history: 17
- data_confidence: 14
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 1 |  | 2 | main,pullback |
| CMBT.BR | 2 |  | 2 |  | 2 | main,pullback |
| DELL | 5 |  | 6 |  | 2 | main,pullback |
| VLO | 6 |  | 5 |  | 2 | main,pullback |
| FRO | 7 |  | 3 |  | 2 | main,pullback |
| PSX | 8 |  | 4 |  | 2 | main,pullback |
| NVDA | 54 | 1 |  | 1 | 1 | value,quality_value |
| LLY | 251 | 2 | 85 | 2 | 1 | value,quality_value |
| NOKIA.HE | 485 | 3 |  | 3 | 1 | value,quality_value |
| MU | 3 |  |  |  | 1 | main |
| HPE | 4 |  |  |  | 1 | main |
| REP.MC | 9 |  |  |  | 1 | main |
| AMC | 10 |  |  |  | 1 | main |
| SHELL.AS | 11 |  | 9 |  | 1 | pullback |
| DHT | 16 |  | 7 |  | 1 | pullback |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **4** (MU, HPE, REP.MC, AMC)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BP | pullback | 57.22 | 60.79 | 75.07 | 87.81 | 87.26 | 82.79 | 70.59 |
| 2 | CMBT.BR | pullback | 56.99 | 54.47 | 70.16 | 96.35 | 78.35 | 85.84 | 80.61 |
| 3 | FRO | pullback | 56.50 | 56.12 | 74.20 | 90.97 | 81.86 | 80.57 | 77.95 |
| 4 | DHT | pullback | 56.37 | 56.75 | 74.22 | 87.42 | 84.55 | 81.26 | 74.74 |
| 5 | MPC | pullback | 55.74 | 49.79 | 69.68 | 84.82 | 90.55 | 82.70 | 80.92 |
| 6 | DAR | pullback | 55.21 | 51.92 | 65.59 | 89.50 | 87.47 | 83.22 | 69.03 |
| 7 | PSX | pullback | 55.14 | 50.62 | 73.84 | 79.74 | 87.08 | 80.05 | 76.97 |
| 8 | VLO | pullback | 54.78 | 49.25 | 68.65 | 86.33 | 82.43 | 82.14 | 78.14 |
| 9 | V | pullback | 53.87 | 41.81 | 76.19 | 93.88 | 51.03 | 78.17 | 56.65 |
| 10 | RDDT | pullback | 53.46 | 43.36 | 75.63 | 86.26 | 76.35 | 69.90 | 50.16 |
| 11 | EQNR | pullback | 53.42 | 55.17 | 74.90 | 75.84 | 85.46 | 73.88 | 70.63 |
| 12 | SHELL.AS | pullback | 53.38 | 62.21 | 52.58 | 93.88 | 83.82 | 88.86 | 75.53 |
| 13 | C5H.IR | pullback | 53.33 | 50.65 | 67.99 | 98.14 | 54.23 | 80.94 | 71.75 |
| 14 | NAT | pullback | 53.15 | 50.29 | 71.11 | 87.38 | 70.17 | 76.25 | 73.09 |
| 15 | ARGX.BR | pullback | 53.00 | 35.38 | 57.31 | 94.58 | 82.31 | 81.28 | 62.32 |
| 16 | BIRG.IR | pullback | 52.91 | 55.08 | 57.74 | 96.79 | 68.12 | 85.70 | 73.09 |
| 17 | CVX | pullback | 52.01 | 60.24 | 78.34 | 67.79 | 78.70 | 71.93 | 62.96 |
| 18 | MT.AS | pullback | 51.84 | 51.37 | 72.80 | 71.82 | 83.61 | 72.54 | 72.73 |
| 19 | VWS.CO | pullback | 51.42 | 34.86 | 69.70 | 88.00 | 63.43 | 72.26 | 66.13 |
| 20 | DELL | pullback | 51.16 | 45.29 | 71.27 | 72.27 | 87.79 | 68.62 | 78.32 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 6 / 4 |
| Top 25 | 25/25 | 23/25 | 24/25 | 22/25 | 0/25 | 73.1 | 16 / 9 |
| Top 50 | 49/50 | 48/50 | 49/50 | 46/50 | 0/50 | 72.5 | 25 / 25 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=1, large_20_100b=5, mega_100b_plus=2
