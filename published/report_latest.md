# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-19

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

- **EUROPE:** 78.5/100
- **OTHER:** 82.9/100
- **US:** 78.5/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | CMBT.BR   | CMBT.BR   | EUROPE   |                5.12 |             84.65 |         87.25 |         84.41 |          84.88 |        82.06 |           96.44 |             77.92 |             58.88 |         3.95 |             73.14 | short              |                8.48 |                  1.75 |                 1.59 |
|      2 | MPC       | MPC       | US       |              103.86 |             83.39 |         83.47 |         87.31 |          83.31 |        75.96 |           84.73 |             90.4  |             52.18 |         4.01 |             73.14 | swing              |              nan    |                nan    |               nan    |
|      3 | FRO       | FRO       | US       |                9.96 |             82.51 |         84.45 |         83.39 |          81.64 |        76.28 |           91.48 |             82.9  |             48.37 |         5.56 |             73.14 | short              |                3.14 |                 -0.29 |                -0.4  |
|      4 | DHT       | DHT       | US       |                3.27 |             80.19 |         83.93 |         81.31 |          79.07 |        75.4  |           88.69 |             83.51 |             50.64 |         4.7  |             73.14 | short              |                3.79 |                  0.66 |                 0.29 |
|      5 | DK        | DK        | US       |                4.16 |             79.46 |         86.16 |         83    |          75.93 |        64.34 |           56.61 |             93.35 |             48.94 |         7.3  |             73.14 | short              |                4.39 |                 -0.53 |                -0.62 |
|      6 | KIN.BR    | KIN.BR    | EUROPE   |                1.33 |             78.54 |         84.55 |         81.72 |          75.37 |        66.27 |           89.41 |             66.2  |             20.72 |         3.91 |             73.14 | short              |               -0.14 |                 -0.06 |                -0.42 |
|      7 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.42 |             78.19 |         76.22 |         73.39 |          80.17 |        81.9  |           71.03 |            nan    |             98.47 |         4.41 |             62.84 | long               |              nan    |                nan    |               nan    |
|      8 | SB        | SB        | US       |                0.91 |             78.17 |         86.05 |         80.54 |          75.81 |        69.35 |           70.53 |             83.82 |             54.25 |         4.33 |             72.34 | short              |                2.76 |                  1.44 |                 1.05 |
|      9 | DINO      | DINO      | US       |               17.93 |             77.81 |         80.99 |         83.74 |          74.63 |        63.52 |           49.63 |             88.01 |             59.82 |         4.43 |             73.14 | swing              |               -1.2  |                 -0.27 |                -0.56 |
|     10 | PBF       | PBF       | US       |                7.96 |             77.66 |         78.83 |         82.17 |          76.49 |        70.32 |           51.67 |             88.3  |             80.61 |         7.71 |             72.68 | swing              |                4.78 |                 -0.65 |                -1.11 |
|     11 | HPE       | HPE       | US       |               70.2  |             77.53 |         80.51 |         78.9  |          76.16 |        67.47 |           74.82 |             73.8  |             44.85 |         7.05 |             72.34 | short              |               -2.28 |                 -1.06 |                -1.19 |
|     12 | NAT       | NAT       | US       |                1.52 |             77.53 |         82.84 |         79.46 |          75.59 |        68.27 |           87.33 |             68.7  |             31.17 |         4.95 |             73.14 | short              |               -0.56 |                  0.03 |                 0.16 |
|     13 | REP.MC    | REP.MC    | EUROPE   |               31.6  |             77.25 |         79.36 |         81.17 |          75.14 |        70.9  |           60.58 |             80.86 |             69.06 |         3.92 |             73.14 | swing              |                8.03 |                  0.05 |                -0.33 |
|     14 | SHELL.AS  | SHELL.AS  | EUROPE   |              235.97 |             77.11 |         79.15 |         75.07 |          74.96 |        80.16 |           93.66 |             83.85 |             63.82 |         2.49 |             73.14 | long               |               13.05 |                 -0.47 |                -1.02 |
|     15 | OMV.VI    | OMV.VI    | EUROPE   |               23.5  |             76.94 |         78.21 |         80.85 |          75.68 |        70.33 |           63.19 |             86.42 |             63.5  |         1.92 |             72.34 | swing              |                6.38 |                  1.75 |                 1.34 |
|     16 | DELL      | DELL      | US       |              314.37 |             76.74 |         84.12 |         79.05 |          74.43 |        62.43 |           72.93 |             74.15 |             27.46 |         7.87 |             72.23 | short              |               -5.48 |                 -0.76 |                -1.2  |
|     17 | SM        | SM        | US       |                7.65 |             76.57 |         62.05 |         74.65 |          78.5  |        80.97 |           81.77 |             81.87 |             86.58 |         7.12 |             72.11 | long               |                4.94 |                 -1.55 |                -1.47 |
|     18 | PARR      | PARR      | US       |                3.68 |             76.1  |         78.08 |         78.92 |          74.12 |        69.89 |           56.67 |             82.78 |             75.6  |         6.96 |             69.89 | swing              |                1.83 |                 -0.74 |                -0.8  |
|     19 | AVAH      | AVAH      | US       |                2.6  |             76.07 |         74.51 |         80.06 |          77.63 |        70.77 |           92.7  |             71.23 |             34.47 |         7.75 |             72.11 | swing              |               -4.35 |                 -0.5  |                -0.4  |
|     20 | TKA.DE    | TKA.DE    | EUROPE   |                9.46 |             76    |         78.65 |         79.55 |          73.34 |        62.95 |          nan    |             61.05 |             48.6  |         7.24 |             70.3  | swing              |                6.78 |                  1.1  |                 0.53 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                    | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                | EUROPE   |              235.97 |                  62    |                    73.52 |                 77.2  |              68.99 |                88.69 |                   11.31 |           93.66 |             83.85 |     nan     |         nan |       nan |      nan    |         9.43 |         10.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                 | EUROPE   |                5.12 |                  58.17 |                    70.57 |                 74.77 |              65.02 |                85.26 |                   14.74 |           96.44 |             77.92 |     nan     |         nan |       nan |      nan    |         9.76 |          6.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | PBR-A    | PBR-A                   | US       |              112.15 |                  68.5  |                    70.03 |                 70.67 |              69.16 |                70.58 |                   29.42 |           74.18 |             71.4  |     nan     |         nan |       nan |      nan    |         4.68 |          4.79 |        5.42 |                 nan |              nan |                   6 |                  0.32 |
|          nan | SM       | SM                      | US       |                7.65 |                  61.95 |                    68.91 |                 71.54 |              65.91 |                72.92 |                   27.08 |           81.77 |             81.87 |     nan     |         nan |       nan |      nan    |         4.71 |          6.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                  | EUROPE   |              175.22 |                  65.78 |                    68.69 |                 69.4  |              68.52 |                73.37 |                   26.63 |           67.45 |             79.54 |     nan     |         nan |       nan |      nan    |         8.9  |         11.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                     | US       |              103.86 |                  55.05 |                    67.92 |                 72.01 |              63.67 |                83.31 |                   16.69 |           84.73 |             90.4  |     nan     |         nan |       nan |      nan    |         9.96 |         14.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                     | US       |              112.12 |                  62.09 |                    67.55 |                 69.27 |              65.18 |                75.68 |                   24.32 |           78.77 |             68.58 |     nan     |         nan |       nan |      nan    |         9.61 |         13.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                     | US       |                3.27 |                  54.83 |                    67.44 |                 71.63 |              62.54 |                81.69 |                   18.31 |           88.69 |             83.51 |     nan     |         nan |       nan |      nan    |        10.85 |          7.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | ATNI     | ATN International, Inc. | US       |                0.39 |                  74.39 |                    67.41 |                 65.83 |              71.83 |                70.75 |                   29.25 |           53.78 |             55.32 |       0.273 |         nan |       nan |        5.25 |        26.6  |          2.83 |        2.73 |                 nan |              nan |                  12 |                  0.63 |
|          nan | AGS.BR   | AGS.BR                  | EUROPE   |               15.93 |                  62.31 |                    67.28 |                 68.87 |              63.89 |                77.14 |                   22.86 |           86.21 |             51.42 |     nan     |         nan |       nan |      nan    |         8.83 |          7.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                     | US       |                9.96 |                  53.96 |                    67.23 |                 71.76 |              61.75 |                81.19 |                   18.81 |           91.48 |             82.9  |     nan     |         nan |       nan |      nan    |        11.23 |          8.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EOG      | EOG                     | US       |               65.85 |                  58.01 |                    66.62 |                 69.42 |              63.15 |                77.52 |                   22.48 |           82.17 |             74.29 |     nan     |         nan |       nan |      nan    |         9.74 |         11.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                   | EUROPE   |               20.87 |                  62.59 |                    66    |                 66.82 |              64.78 |                73.95 |                   26.05 |           71.85 |             64.01 |     nan     |         nan |       nan |      nan    |         9.03 |         11.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                 | EUROPE   |               19.08 |                  55.16 |                    65.79 |                 69.4  |              59.82 |                81.18 |                   18.82 |           96.61 |             55.01 |     nan     |         nan |       nan |      nan    |        11.05 |         14.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR                     | US       |              116.67 |                  69.02 |                    65.78 |                 65.16 |              64.88 |                60.76 |                   39.24 |           74.45 |             42.5  |     nan     |         nan |       nan |      nan    |         5.22 |          5.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN                     | US       |               46.54 |                  61.26 |                    65.47 |                 67.05 |              62.9  |                69.86 |                   30.14 |           78.72 |             62.19 |     nan     |         nan |       nan |      nan    |         9.07 |         10.59 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX      | CVX                     | US       |              357.71 |                  59.57 |                    65.2  |                 66.82 |              64.06 |                72.71 |                   27.29 |           67.97 |             80.78 |     nan     |         nan |       nan |      nan    |        15.45 |         20.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                  | EUROPE   |               24.42 |                  55.04 |                    65.14 |                 68.57 |              59.45 |                79.78 |                   20.22 |           94.55 |             54.63 |     nan     |         nan |       nan |      nan    |        11.75 |         12.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                      | US       |               63.36 |                  59.8  |                    64.96 |                 66.72 |              60.81 |                75.26 |                   24.74 |           88.86 |             42.05 |     nan     |         nan |       nan |      nan    |        12.08 |         14.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI                  | EUROPE   |               23.5  |                  57.78 |                    64.43 |                 66.07 |              63.81 |                75.4  |                   24.6  |           63.19 |             86.42 |     nan     |         nan |       nan |      nan    |         9.08 |         15.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              235.97 |                  62    |                    73.52 |                 77.2  |              68.99 |                88.69 |                   11.31 |           93.66 |             83.85 |         nan |         nan |       nan |         nan |         9.43 |         10.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR  | EUROPE   |                5.12 |                  58.17 |                    70.57 |                 74.77 |              65.02 |                85.26 |                   14.74 |           96.44 |             77.92 |         nan |         nan |       nan |         nan |         9.76 |          6.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC      | US       |              103.86 |                  55.05 |                    67.92 |                 72.01 |              63.67 |                83.31 |                   16.69 |           84.73 |             90.4  |         nan |         nan |       nan |         nan |         9.96 |         14.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO      | US       |                9.96 |                  53.96 |                    67.23 |                 71.76 |              61.75 |                81.19 |                   18.81 |           91.48 |             82.9  |         nan |         nan |       nan |         nan |        11.23 |          8.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT      | US       |                3.27 |                  54.83 |                    67.44 |                 71.63 |              62.54 |                81.69 |                   18.31 |           88.69 |             83.51 |         nan |         nan |       nan |         nan |        10.85 |          7.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM       | US       |                7.65 |                  61.95 |                    68.91 |                 71.54 |              65.91 |                72.92 |                   27.08 |           81.77 |             81.87 |         nan |         nan |       nan |         nan |         4.71 |          6.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | PBR-A    | PBR-A    | US       |              112.15 |                  68.5  |                    70.03 |                 70.67 |              69.16 |                70.58 |                   29.42 |           74.18 |             71.4  |         nan |         nan |       nan |         nan |         4.68 |          4.79 |        5.42 |                 nan |              nan |                   6 |                  0.32 |
|          nan | EOG      | EOG      | US       |               65.85 |                  58.01 |                    66.62 |                 69.42 |              63.15 |                77.52 |                   22.48 |           82.17 |             74.29 |         nan |         nan |       nan |         nan |         9.74 |         11.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               19.08 |                  55.16 |                    65.79 |                 69.4  |              59.82 |                81.18 |                   18.82 |           96.61 |             55.01 |         nan |         nan |       nan |         nan |        11.05 |         14.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              175.22 |                  65.78 |                    68.69 |                 69.4  |              68.52 |                73.37 |                   26.63 |           67.45 |             79.54 |         nan |         nan |       nan |         nan |         8.9  |         11.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY      | US       |              112.12 |                  62.09 |                    67.55 |                 69.27 |              65.18 |                75.68 |                   24.32 |           78.77 |             68.58 |         nan |         nan |       nan |         nan |         9.61 |         13.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA     | NVDA     | US       |             4671.57 |                  49.59 |                    64.16 |                 69.04 |              58.27 |                80.73 |                   19.27 |           90.23 |             80.38 |         nan |         nan |       nan |         nan |        14.17 |         27.71 |        0.47 |                 nan |              nan |                   6 |                  0.32 |
|          nan | AGS.BR   | AGS.BR   | EUROPE   |               15.93 |                  62.31 |                    67.28 |                 68.87 |              63.89 |                77.14 |                   22.86 |           86.21 |             51.42 |         nan |         nan |       nan |         nan |         8.83 |          7.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU       | US       |              998.56 |                  48.74 |                    63.43 |                 68.79 |              56.51 |                75.95 |                   24.05 |           95.37 |             77.5  |         nan |         nan |       nan |         nan |         6.49 |         22.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               24.42 |                  55.04 |                    65.14 |                 68.57 |              59.45 |                79.78 |                   20.22 |           94.55 |             54.63 |         nan |         nan |       nan |         nan |        11.75 |         12.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OXY      | OXY      | US       |               51.2  |                  52.1  |                    64.22 |                 68.27 |              59.47 |                77.7  |                   22.3  |           84.86 |             79.69 |         nan |         nan |       nan |         nan |        14.58 |         17.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | GL9.IR   | GL9.IR   | EUROPE   |                4.55 |                  44.13 |                    62.1  |                 68.09 |              54.29 |                83.97 |                   16.03 |           98.13 |             74.07 |         nan |         nan |       nan |         nan |        12.88 |         22.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP       | US       |               99.93 |                  55.52 |                    64.38 |                 67.49 |              59.76 |                74.8  |                   25.2  |           87.21 |             63.2  |         nan |         nan |       nan |         nan |         9.16 |         21.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR   | EUROPE   |                1.64 |                  53.9  |                    63.72 |                 67.2  |              57.31 |                77.87 |                   22.13 |           98.13 |             44.88 |         nan |         nan |       nan |         nan |        10.24 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY     | US       |                4.76 |                  55.01 |                    64.1  |                 67.09 |              61.74 |                71.93 |                   28.07 |           71.07 |             91.86 |         nan |         nan |       nan |         nan |         5.93 |        173.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AVAH      | AVAH      | US       |                2.6  |                     0.05 |    -0.03 |      0.05 |                  75.84 |                        80.63 |         74.51 |         80.06 |          77.63 |        70.77 |           92.7  |             71.23 |         7.75 |
|               2 | SHELL.AS  | SHELL.AS  | EUROPE   |              235.97 |                     0.03 |    -0    |      0.04 |                  56.82 |                        79.41 |         79.15 |         75.07 |          74.96 |        80.16 |           93.66 |             83.85 |         2.49 |
|               3 | BE        | BE        | US       |               68.1  |                     0.05 |    -0.04 |      0.31 |                  80.85 |                        77.83 |         72.59 |         56.15 |          68.27 |        60.1  |           86.27 |             81.04 |         9.15 |
|               4 | DELL      | DELL      | US       |              314.37 |                     0.03 |     0    |      0.31 |                  57.79 |                        76.43 |         84.12 |         79.05 |          74.43 |        62.43 |           72.93 |             74.15 |         7.87 |
|               5 | SRAIL.SW  | SRAIL.SW  | EUROPE   |                3.15 |                     0.05 |     0.01 |      0.22 |                  67.91 |                        75.46 |         82.92 |         72.03 |          65.77 |        60.45 |           78.85 |             53.65 |         5.59 |
|               6 | DAR       | DAR       | US       |                8.98 |                     0.03 |     0    |     -0.04 |                  57.06 |                        75.16 |         64.88 |         70.47 |          76.29 |        77.98 |           91.19 |             87.55 |         4.65 |
|               7 | NVDA      | NVDA      | US       |             4671.57 |                     0.03 |     0.02 |      0.03 |                  52.54 |                        74.75 |         73.53 |         63.68 |          66.67 |        66.78 |           90.23 |             80.38 |         5.07 |
|               8 | HPE       | HPE       | US       |               70.2  |                     0.02 |    -0.02 |      0.15 |                  54.04 |                        74.39 |         80.51 |         78.9  |          76.16 |        67.47 |           74.82 |             73.8  |         7.05 |
|               9 | TALO      | TALO      | US       |                2.47 |                     0.07 |    -0.04 |     -0.04 |                  71.35 |                        74.35 |         57.43 |         70.95 |          72.84 |        70.7  |           67.72 |             97.51 |         5.77 |
|              10 | PBR-A     | PBR-A     | US       |              112.15 |                     0.04 |    -0.02 |      0.14 |                  64.94 |                        74.16 |         77.76 |         71.31 |          69.7  |        76.24 |           74.18 |             71.4  |         4.69 |
|              11 | CRGY      | CRGY      | US       |                4.76 |                     0.1  |    -0.05 |      0.01 |                  60.8  |                        74.09 |         64.47 |         73.95 |          75.5  |        78.26 |           71.07 |             91.86 |         6.54 |
|              12 | SM        | SM        | US       |                7.65 |                     0.1  |    -0.03 |     -0.01 |                  48.76 |                        73.27 |         62.05 |         74.65 |          78.5  |        80.97 |           81.77 |             81.87 |         7.12 |
|              13 | APA       | APA       | US       |               13.68 |                     0.05 |     0    |      0.01 |                  69.04 |                        73.09 |         71.48 |         72.24 |          71.38 |        70.18 |           73.83 |             78.98 |         6.02 |
|              14 | VWS.CO    | VWS.CO    | EUROPE   |               27.06 |                     0.06 |    -0.04 |     -0.01 |                  82.59 |                        73.02 |         63.71 |         67.51 |          68.68 |        63.81 |           86.71 |             63.57 |         6.02 |
|              15 | C5H.IR    | C5H.IR    | EUROPE   |                1.64 |                     0.07 |    -0.01 |      0.07 |                  67.68 |                        72.94 |         72.86 |         65.79 |          68.95 |        74.21 |           98.13 |             44.88 |         2.75 |
|              16 | PR        | PR        | US       |               16.59 |                     0.06 |    -0.04 |     -0.04 |                  75.61 |                        72.93 |         55.71 |         67.77 |          71.56 |        72.49 |           79.07 |             79.28 |         4.59 |
|              17 | MT.AS     | MT.AS     | EUROPE   |               47.49 |                     0.07 |    -0.02 |      0.01 |                  69.99 |                        72.74 |         62.76 |         71.91 |          76.75 |        73.77 |           71.84 |             79.48 |         5.2  |
|              18 | GOLD      | GOLD      | US       |                1.15 |                     0.05 |    -0.03 |      0.02 |                  80.27 |                        72.69 |         65.18 |         56.16 |          66.44 |        72.75 |           91.34 |             65.25 |         7.41 |
|              19 | SYENS.BR  | SYENS.BR  | EUROPE   |                7.89 |                     0.06 |    -0.04 |     -0.03 |                  81.55 |                        72.66 |         55.15 |         71.19 |          67.61 |        57.43 |           68.2  |             74.61 |         5.42 |
|              20 | HLUN-B.CO | HLUN-B.CO | EUROPE   |                5.65 |                     0.05 |    -0.04 |      0.04 |                  78.11 |                        71.37 |         66.62 |         59.18 |          62.57 |        69.48 |           77.66 |             72.1  |         3.92 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    166 | 0QXR.IL  | 0QXR.IL | OTHER    |               25.94 |             60.56 |         60.73 |         56.61 |          60.39 |        73.09 |           88.89 |            nan    |             69.7  |         9.17 |             61.02 | long               |               18.3  |                  4.8  |                 4.56 |
|     28 | DOCM.SW  | DOCM.SW | EUROPE   |                0.58 |             73.7  |         80.25 |         77.4  |          70    |        58.37 |           48.93 |             69.86 |             47.35 |         7.48 |             70.3  | short              |                8.64 |                  3.72 |                 3.79 |
|     49 | PANW     | PANW    | US       |              258.86 |             70.06 |         74.19 |         72.91 |          67.21 |        48.48 |           50.7  |             87.65 |              5.86 |         7.57 |             73.14 | short              |                5.6  |                  3.71 |                 3.47 |
|     45 | RBRK     | RBRK    | US       |               19.12 |             70.7  |         84    |         77.98 |          63.42 |        45.97 |           53.54 |             81.57 |              1.57 |         8.67 |             72.23 | short              |               -5.63 |                  2.81 |                 2.73 |
|    611 | MGPI     | MGPI    | US       |                0.26 |             39.39 |         27.36 |         34.56 |          44.22 |        54.91 |           48.03 |             67.02 |             81.18 |         7.2  |             69.23 | long               |               -2.58 |                  2.53 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    657 | DEC      | DEC    | US       |                0.83 |             33.97 |         28.86 |         31.72 |          36.21 |        50.62 |           44.59 |              6.35 |             87.59 |         5.66 |             69.89 | long               |               -0.59 |                 -4.41 |                -3.33 |
|    679 | BBWI     | BBWI   | US       |                3.05 |             29.97 |         27.77 |         23.86 |          32.17 |        45.7  |           37.05 |             20.69 |             84.7  |         7.68 |             69.14 | long               |                1.08 |                 -4.16 |                -3.41 |
|    517 | APH      | APH    | US       |              166.45 |             45.83 |         45.31 |         38.43 |          46.35 |        49.1  |           78.73 |             26.76 |             17.59 |         6.13 |             73.14 | long               |               -9.35 |                 -3.85 |                -3.48 |
|    583 | BAC      | BAC    | US       |              351.37 |             42.09 |         29.85 |         39.81 |          44.38 |        46.35 |           47.88 |             21.86 |             56.1  |         2.77 |             72.8  | long               |               -4.73 |                 -3.75 |                -3.16 |
|    232 | HMY      | HMY    | US       |               10.84 |             57.38 |         43.44 |         52.72 |          62.03 |        68.08 |           82.5  |             26.98 |             73.3  |         8.15 |             73.14 | long               |                3.35 |                 -3.68 |               nan    |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.89
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.87

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
- Excluded by hard/data filters: **299**
- Event watch (otherwise eligible): **0**
- Final eligible: **701**
- Eligible change vs previous stored run: **+1**

Top exclusion categories:
- liquidity: 239
- price: 190
- market_cap: 168
- price_history: 21
- data_confidence: 16
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PBR-A | 27 | 1 | 10 | 1 | 2 | value,pullback,quality_value |
| NVDA | 85 | 3 | 7 | 2 | 2 | value,pullback,quality_value |
| HQL | 154 | 4 |  | 4 | 1 | value,quality_value |
| ALV.DE | 218 | 8 | 199 | 9 | 1 | value,quality_value |
| SU.PA | 265 | 9 | 75 | 7 | 1 | value,quality_value |
| ATNI | 299 | 2 | 194 | 3 | 1 | value,quality_value |
| SIE.DE | 461 | 7 |  | 6 | 1 | value,quality_value |
| AIR.PA | 482 | 10 | 224 | 10 | 1 | value,quality_value |
| UNIT | 593 | 6 | 349 | 8 | 1 | value,quality_value |
| MC.PA | 664 | 5 |  | 5 | 1 | value,quality_value |
| CMBT.BR | 1 |  |  |  | 1 | main |
| MPC | 2 |  |  |  | 1 | main |
| FRO | 3 |  |  |  | 1 | main |
| DHT | 4 |  |  |  | 1 | main |
| DK | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (CMBT.BR, MPC, FRO, DHT, KIN.BR, SSABBH.HE, SB, DINO, PBF)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (SHELL.AS)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | PBR-A | value+pullback | 69.17 | 68.50 | 64.94 | 74.18 | 71.40 | 70.58 | 73.78 |
| 2 | ATNI | value+pullback | 68.45 | 74.39 | 73.55 | 53.78 | 55.32 | 70.75 | 55.06 |
| 3 | UNIT | value+pullback | 57.33 | 62.11 | 74.52 | 60.45 | 28.54 | 40.72 | 41.16 |
| 4 | WBI | pullback | 55.93 | 39.75 | 77.30 | 95.82 | 68.53 | 76.91 | 55.83 |
| 5 | BE | pullback | 55.43 | 35.05 | 80.85 | 86.27 | 81.04 | 70.88 | 64.18 |
| 6 | KLAC | pullback | 55.43 | 36.58 | 71.50 | 95.97 | 78.62 | 76.49 | 54.24 |
| 7 | AVAH | pullback | 54.73 | 44.28 | 75.84 | 92.70 | 71.23 | 73.72 | 76.07 |
| 8 | GOLD | pullback | 54.65 | 46.64 | 80.27 | 91.34 | 65.25 | 71.78 | 65.81 |
| 9 | SHELL.AS | pullback | 54.38 | 62.00 | 56.82 | 93.66 | 83.85 | 88.69 | 77.11 |
| 10 | VWS.CO | pullback | 54.35 | 35.95 | 82.59 | 86.71 | 63.57 | 71.68 | 65.66 |
| 11 | GVR.IR | pullback | 54.29 | 53.32 | 64.55 | 91.47 | 75.75 | 84.30 | 62.83 |
| 12 | OXY | pullback | 54.16 | 52.10 | 71.70 | 84.86 | 79.69 | 77.70 | 62.18 |
| 13 | PR | pullback | 53.84 | 53.40 | 75.61 | 79.07 | 79.28 | 75.74 | 69.67 |
| 14 | BP | pullback | 53.81 | 55.52 | 77.78 | 87.21 | 63.20 | 74.80 | 61.73 |
| 15 | DAR | pullback | 53.57 | 50.28 | 57.06 | 91.19 | 87.55 | 84.36 | 73.38 |
| 16 | EOG | pullback | 53.45 | 58.01 | 72.78 | 82.17 | 74.29 | 77.52 | 61.86 |
| 17 | HLUN-B.CO | pullback | 53.20 | 56.42 | 78.11 | 77.66 | 72.10 | 74.08 | 64.59 |
| 18 | RDDT | pullback | 52.86 | 43.52 | 73.47 | 86.68 | 75.50 | 69.71 | 50.12 |
| 19 | HQL | value+pullback | 52.78 | 61.89 | 43.19 | 60.00 |  | 47.09 | 61.76 |
| 20 | TALO | pullback | 52.47 | 51.85 | 71.35 | 67.72 | 97.51 | 73.60 | 70.83 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 10/10 | 9/10 | 0/10 | 73.1 | 1 / 9 |
| Top 25 | 23/25 | 24/25 | 25/25 | 22/25 | 0/25 | 72.7 | 7 / 18 |
| Top 50 | 48/50 | 49/50 | 49/50 | 46/50 | 0/50 | 72.5 | 15 / 35 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=5, mega_100b_plus=1
