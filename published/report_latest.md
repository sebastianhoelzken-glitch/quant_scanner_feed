# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-28

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

- **EUROPE:** 88.2/100
- **OTHER:** 82.1/100
- **US:** 82.9/100

## Main multi-horizon ranking

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | OKTA     | OKTA     | US       |               25.94 |             82.31 |         89.73 |         87.56 |          77.07 |        53.59 |          nan    |             84.81 |             12.8  |         7.89 |             66.84 | short              |               19.6  |                  3.21 |                  nan |
|      2 | CRWD     | CRWD     | US       |              200.27 |             81.64 |         86.04 |         85.86 |          77.43 |        49.84 |          nan    |             89.81 |              1.48 |         7.54 |             66.84 | short              |               27.21 |                  5.53 |                  nan |
|      3 | FRO      | FRO      | US       |                8.36 |             79.45 |         75.05 |         80    |          80.19 |        78.91 |           85.19 |             82.57 |             60.28 |         5.44 |             69.68 | medium             |               14.75 |                  1.19 |                  nan |
|      4 | AVAH     | AVAH     | US       |                2.59 |             78.6  |         86.05 |         83.1  |          74.11 |        69.89 |           92.86 |             57.12 |             34.9  |         7.49 |             68.66 | short              |               -0.58 |                 -0.02 |                  nan |
|      5 | MPC      | MPC      | US       |               87.6  |             78.08 |         79.32 |         79.56 |          76.84 |        72.79 |           86.02 |             54.16 |             50.52 |         4.11 |             69.68 | swing              |              nan    |                nan    |                  nan |
|      6 | WT       | WT       | US       |                3.26 |             77.89 |         84.45 |         82.09 |          73.68 |        64.13 |           74.11 |             79.55 |             26.53 |         5.53 |             69.68 | short              |                0.45 |                  0.36 |                  nan |
|      7 | HQL      | HQL      | US       |                0.56 |             77.26 |         76.48 |         79.48 |          78.04 |        73.66 |          nan    |            nan    |             67.89 |         2.09 |             55.57 | swing              |               10.99 |                  2.4  |                  nan |
|      8 | HPE      | HPE      | US       |               61.82 |             77.21 |         72.43 |         82.2  |          81.99 |        72.3  |           74.94 |             84.91 |             47.83 |         6.94 |             67.86 | swing              |               -1.99 |                  0.56 |                  nan |
|      9 | CAKE     | CAKE     | US       |                4.7  |             76.68 |         75.66 |         80.49 |          77.7  |        67.48 |           87.32 |             71.23 |             19.94 |         5.96 |             67.18 | swing              |               -3.52 |                  0.34 |                  nan |
|     10 | DELL     | DELL     | US       |              261.82 |             76    |         75.76 |         79.89 |          76.24 |        63.53 |           71.2  |             72.38 |             26    |         7.81 |             68.77 | swing              |               -0.45 |                  0.21 |                  nan |
|     11 | FROG     | FROG     | US       |               11.01 |             75.69 |         84    |         82.61 |          68.78 |        48.04 |           44.2  |             87.21 |              4.33 |         8.24 |             69.68 | short              |              nan    |                  2.05 |                  nan |
|     12 | KIN.BR   | KIN.BR   | EUROPE   |                1.22 |             75.69 |         77.94 |         78.54 |          73.44 |        65.45 |           91.77 |             67.9  |             22.37 |         4.23 |             69.68 | swing              |               -1.65 |                 -0.23 |                  nan |
|     13 | PAGP     | PAGP     | US       |                5.6  |             75.67 |         76.95 |         75.31 |          76.03 |        72.68 |           85.09 |             77.79 |             47.27 |         1.83 |             66.7  | short              |               -0.7  |                nan    |                  nan |
|     14 | RBRK     | RBRK     | US       |               18.9  |             75.27 |         88.91 |         85.11 |          65.42 |        47.88 |           54.17 |             91.42 |              1.53 |         8.39 |             68.77 | short              |                9.41 |                  1.39 |                  nan |
|     15 | SSRM     | SSRM     | US       |                6.83 |             75.14 |         85.22 |         78.01 |          72.02 |        72.26 |           66.57 |             77.11 |             70.5  |         7.15 |             68.32 | short              |               -2.14 |                  0.14 |                  nan |
|     16 | SRAIL.SW | SRAIL.SW | EUROPE   |                3.35 |             74.9  |         82.41 |         79.61 |          70.19 |        61.85 |           80.1  |             78.4  |             24.24 |         5.65 |             69.68 | short              |                1    |                  3.47 |                  nan |
|     17 | RNG      | RNG      | US       |                4.91 |             74.87 |         81.23 |         83    |          68.52 |        53.13 |           22.23 |             86.35 |             54.3  |         7.29 |             67.75 | swing              |                2.21 |                  0.91 |                  nan |
|     18 | PR       | PR       | US       |               16.66 |             74.69 |         71.1  |         75.05 |          75.66 |        74.33 |           79.32 |             73.93 |             61.34 |         4.29 |             68.32 | medium             |                4.91 |                 -0.36 |                  nan |
|     19 | ERO      | ERO      | US       |                3.56 |             74.23 |         87.61 |         72.43 |          70.63 |        76.04 |           84.64 |             48.86 |             68.58 |         7.67 |             69.68 | short              |               -2.49 |                 -0.92 |                  nan |
|     20 | NIQ      | NIQ      | US       |                4.83 |             74.05 |         84.95 |         84.71 |          63.4  |        50.7  |           35.94 |             95.78 |             38.74 |         9.08 |             68.2  | short              |               -0.51 |                 -0.07 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | FRO      | FRO      | US       |                8.36 |                  58.29 |                    68.23 |                 71.64 |              64.3  |                78.18 |                   21.82 |           85.19 |             82.57 |         nan |         nan |       nan |         nan |        10.04 |         10.15 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP       | US       |               93.56 |                  56.61 |                    68.2  |                 72.04 |              63.57 |                81.86 |                   18.14 |           88.68 |             80.77 |         nan |         nan |       nan |         nan |         9.55 |         20.26 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY      | US       |               14.91 |                  67.14 |                    67.46 |                 67.89 |              64.18 |                70.72 |                   29.28 |           89.61 |             31.1  |         nan |         nan |       nan |         nan |         7.42 |          5.57 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              213.37 |                  64.94 |                    67.22 |                 68.39 |              62.91 |                72.15 |                   27.85 |           94.39 |             31.6  |         nan |         nan |       nan |         nan |         9.77 |         10.02 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |               97.16 |                  68.85 |                    66.81 |                 66.43 |              65.89 |                64.32 |                   35.68 |           74.75 |             47.43 |         nan |         nan |       nan |         nan |         6.72 |          4.18 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR      | US       |              100.91 |                  69.83 |                    65.8  |                 64.89 |              64.95 |                60.81 |                   39.19 |           75    |             37.31 |         nan |         nan |       nan |         nan |         4.58 |          4.61 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET       | US       |               63.16 |                  59.38 |                    65.52 |                 67.61 |              60.94 |                76.92 |                   23.08 |           91.39 |             43.39 |         nan |         nan |       nan |         nan |        12.22 |         14.64 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               17.7  |                  57.01 |                    65.4  |                 68.38 |              59.56 |                78.38 |                   21.62 |           97.41 |             44.12 |         nan |         nan |       nan |         nan |        10.27 |         13.9  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL     | US       |              214.2  |                  65.95 |                    65.06 |                 64.9  |              63.8  |                65.93 |                   34.07 |           74.64 |             44.46 |         nan |         nan |       nan |         nan |        10.28 |         10.03 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | REP.MC   | REP.MC   | EUROPE   |               28.65 |                  62.09 |                    65.04 |                 65.83 |              64.86 |                68.83 |                   31.17 |           63.7  |             77.63 |         nan |         nan |       nan |         nan |         7.29 |          8.56 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS   | EUROPE   |               11.72 |                  59.61 |                    65.01 |                 66.39 |              63.82 |                74.78 |                   25.22 |           68.76 |             74.39 |         nan |         nan |       nan |         nan |         8.6  |         12.14 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI   | EUROPE   |               21.92 |                  57.96 |                    64.94 |                 66.86 |              63.3  |                76.15 |                   23.85 |           70.25 |             78.58 |         nan |         nan |       nan |         nan |         8.89 |         14.09 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | COP      | COP      | US       |              133.5  |                  60.56 |                    64.91 |                 66.24 |              63.74 |                70.33 |                   29.67 |           68.91 |             74.74 |         nan |         nan |       nan |         nan |        13.59 |         17.27 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX      | CVX      | US       |              336.23 |                  60.96 |                    64.9  |                 66.02 |              63.92 |                70.84 |                   29.16 |           68.13 |             72.84 |         nan |         nan |       nan |         nan |        15.09 |         19.23 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              164.11 |                  63.57 |                    64.79 |                 65.11 |              63.91 |                68.22 |                   31.78 |           69.95 |             58.56 |         nan |         nan |       nan |         nan |         8.84 |         10.84 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE   | EUROPE   |               38.15 |                  68.18 |                    64.64 |                 63.55 |              65.03 |                57.77 |                   42.23 |          nan    |             55.46 |         nan |         nan |       nan |         nan |         2.8  |          7.3  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY      | US       |              117.34 |                  61.38 |                    64.59 |                 65.72 |              62.03 |                70.42 |                   29.58 |           79.18 |             51.63 |         nan |         nan |       nan |         nan |        10.21 |         14.75 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS    | EUROPE   |               20.09 |                  63.44 |                    64.35 |                 64.54 |              62.86 |                69.72 |                   30.28 |           74.37 |             46.27 |         nan |         nan |       nan |         nan |         8.87 |         11.39 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAGP     | PAGP     | US       |                5.6  |                  50.56 |                    64.12 |                 68.26 |              59.26 |                83.76 |                   16.24 |           85.09 |             77.79 |         nan |         nan |       nan |         nan |        13.03 |         80.09 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | KEY      | KEY      | US       |               20.16 |                  62.21 |                    63.99 |                 64.77 |              61.03 |                68.66 |                   31.34 |           82.6  |             38.82 |         nan |         nan |       nan |         nan |        10.31 |         12.95 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | BP       | BP       | US       |               93.56 |                  56.61 |                    68.2  |                 72.04 |              63.57 |                81.86 |                   18.14 |           88.68 |             80.77 |         nan |         nan |       nan |         nan |         9.55 |         20.26 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO      | US       |                8.36 |                  58.29 |                    68.23 |                 71.64 |              64.3  |                78.18 |                   21.82 |           85.19 |             82.57 |         nan |         nan |       nan |         nan |        10.04 |         10.15 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              213.37 |                  64.94 |                    67.22 |                 68.39 |              62.91 |                72.15 |                   27.85 |           94.39 |             31.6  |         nan |         nan |       nan |         nan |         9.77 |         10.02 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               17.7  |                  57.01 |                    65.4  |                 68.38 |              59.56 |                78.38 |                   21.62 |           97.41 |             44.12 |         nan |         nan |       nan |         nan |        10.27 |         13.9  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAGP     | PAGP     | US       |                5.6  |                  50.56 |                    64.12 |                 68.26 |              59.26 |                83.76 |                   16.24 |           85.09 |             77.79 |         nan |         nan |       nan |         nan |        13.03 |         80.09 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY      | US       |               14.91 |                  67.14 |                    67.46 |                 67.89 |              64.18 |                70.72 |                   29.28 |           89.61 |             31.1  |         nan |         nan |       nan |         nan |         7.42 |          5.57 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | OXY      | OXY      | US       |               50.75 |                  50.84 |                    63.44 |                 67.63 |              58.3  |                78.06 |                   21.94 |           86.32 |             76.45 |         nan |         nan |       nan |         nan |        15.43 |         17.3  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET       | US       |               63.16 |                  59.38 |                    65.52 |                 67.61 |              60.94 |                76.92 |                   23.08 |           91.39 |             43.39 |         nan |         nan |       nan |         nan |        12.22 |         14.64 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI   | EUROPE   |               21.92 |                  57.96 |                    64.94 |                 66.86 |              63.3  |                76.15 |                   23.85 |           70.25 |             78.58 |         nan |         nan |       nan |         nan |         8.89 |         14.09 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP      | KDP      | US       |               37.22 |                  52.9  |                    63.11 |                 66.6  |              57.62 |                76.85 |                   23.15 |           90.89 |             56.98 |         nan |         nan |       nan |         nan |        12.58 |         32.53 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |               97.16 |                  68.85 |                    66.81 |                 66.43 |              65.89 |                64.32 |                   35.68 |           74.75 |             47.43 |         nan |         nan |       nan |         nan |         6.72 |          4.18 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS   | EUROPE   |               11.72 |                  59.61 |                    65.01 |                 66.39 |              63.82 |                74.78 |                   25.22 |           68.76 |             74.39 |         nan |         nan |       nan |         nan |         8.6  |         12.14 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PR       | PR       | US       |               16.66 |                  53.8  |                    63.26 |                 66.34 |              59.59 |                74.76 |                   25.24 |           79.32 |             73.93 |         nan |         nan |       nan |         nan |        10.56 |         14.95 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | COP      | COP      | US       |              133.5  |                  60.56 |                    64.91 |                 66.24 |              63.74 |                70.33 |                   29.67 |           68.91 |             74.74 |         nan |         nan |       nan |         nan |        13.59 |         17.27 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX      | CVX      | US       |              336.23 |                  60.96 |                    64.9  |                 66.02 |              63.92 |                70.84 |                   29.16 |           68.13 |             72.84 |         nan |         nan |       nan |         nan |        15.09 |         19.23 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               22.6  |                  56.73 |                    63.39 |                 65.87 |              57.6  |                74.63 |                   25.37 |           96.68 |             33.18 |         nan |         nan |       nan |         nan |        10.99 |         11.24 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | REP.MC   | REP.MC   | EUROPE   |               28.65 |                  62.09 |                    65.04 |                 65.83 |              64.86 |                68.83 |                   31.17 |           63.7  |             77.63 |         nan |         nan |       nan |         nan |         7.29 |          8.56 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY      | US       |              117.34 |                  61.38 |                    64.59 |                 65.72 |              62.03 |                70.42 |                   29.58 |           79.18 |             51.63 |         nan |         nan |       nan |         nan |        10.21 |         14.75 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT      | US       |                2.68 |                  57.09 |                    63.16 |                 65.55 |              58.36 |                70.38 |                   29.62 |           89.73 |             45.82 |         nan |         nan |       nan |         nan |        10.29 |          6.58 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN      | US       |               15.18 |                  54.61 |                    62.55 |                 65.25 |              58.14 |                73.78 |                   26.22 |           85.19 |             55.4  |         nan |         nan |       nan |         nan |        11    |         23.85 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | FRO      | FRO      | US       |                8.36 |                     0.02 |     0    |      0.12 |                  45.26 |                        76.21 |         75.05 |         80    |          80.19 |        78.91 |           85.19 |             82.57 |         5.44 |
|               2 | NTAP     | NTAP     | US       |               32.1  |                     0.08 |    -0.01 |      0.1  |                  59.02 |                        75.75 |         65.09 |         77.24 |          77.36 |        68.08 |           87.16 |             72.27 |         6.33 |
|               3 | PR       | PR       | US       |               16.66 |                     0.03 |    -0.03 |      0.1  |                  63.11 |                        73.95 |         71.1  |         75.05 |          75.66 |        74.33 |           79.32 |             73.93 |         4.29 |
|               4 | BP       | BP       | US       |               93.56 |                     0.06 |    -0.06 |     -0.03 |                  84.57 |                        72.78 |         50.09 |         60.49 |          71.01 |        74.76 |           88.68 |             80.77 |         4.18 |
|               5 | SYENS.BR | SYENS.BR | EUROPE   |                8.13 |                     0.03 |     0.01 |      0.05 |                  55.78 |                        72.77 |         65.79 |         73.09 |          67.18 |        58.78 |           72.58 |             88.95 |         5.35 |
|               6 | JHX      | JHX      | US       |               14.83 |                     0.04 |    -0.01 |      0.12 |                  65.4  |                        72.73 |         69.32 |         75.25 |          68.28 |        60.69 |           59.78 |             88.89 |         6.06 |
|               7 | APA      | APA      | US       |               12.74 |                     0.05 |    -0.05 |      0.17 |                  78.02 |                        71.83 |         71.53 |         71.63 |          73.42 |        71.19 |           73.76 |             63.71 |         5.72 |
|               8 | CVE      | CVE      | US       |               50.18 |                     0.04 |    -0.02 |      0.05 |                  66.63 |                        71.7  |         63.7  |         71.01 |          74.98 |        71.08 |           77.79 |             70.97 |         4.93 |
|               9 | TALO     | TALO     | US       |                2.4  |                     0.06 |    -0.06 |      0.15 |                  86.07 |                        71.65 |         68.82 |         69.34 |          71.17 |        68.13 |           69.1  |             68.32 |         5.62 |
|              10 | REP.MC   | REP.MC   | EUROPE   |               28.65 |                     0.06 |    -0.06 |     -0    |                  84.41 |                        71.43 |         48.68 |         68.77 |          74.02 |        69.86 |           63.7  |             77.63 |         3.94 |
|              11 | TOST     | TOST     | US       |               17.44 |                     0.05 |    -0    |      0.07 |                  68.16 |                        70.6  |         62.68 |         70.58 |          61.75 |        55.16 |           69.21 |             74.97 |         7.03 |
|              12 | OXY      | OXY      | US       |               50.75 |                     0.04 |    -0.04 |      0.06 |                  71.57 |                        70.37 |         60.93 |         61.81 |          68.54 |        69.85 |           86.32 |             76.45 |         4.8  |
|              13 | BAX      | BAX      | US       |               11.5  |                     0.09 |    -0.02 |     -0.03 |                  57.34 |                        70.28 |         52.55 |         71.42 |          69.85 |        67.48 |           76.72 |             70.86 |         6.23 |
|              14 | CRGY     | CRGY     | US       |                4.61 |                     0.03 |    -0.01 |      0.23 |                  58.22 |                        70.25 |         75.23 |         72.03 |          71.19 |        75.2  |           71.79 |             63.64 |         6.21 |
|              15 | OMV.VI   | OMV.VI   | EUROPE   |               21.92 |                     0.03 |    -0.03 |      0.06 |                  63.84 |                        70.17 |         60.52 |         69.51 |          71.71 |        68.43 |           70.25 |             78.58 |         2.05 |
|              16 | COP      | COP      | US       |              133.5  |                     0.04 |    -0.04 |      0.1  |                  73.04 |                        70.01 |         67.38 |         68.13 |          66.46 |        64.32 |           68.91 |             74.74 |         4.02 |
|              17 | DSX      | DSX      | US       |                0.29 |                     0.02 |     0.02 |      0.17 |                  44.77 |                        69.59 |         76.19 |         60.66 |          67.98 |        81.63 |           90.29 |             44.8  |         5.77 |
|              18 | WDAY     | WDAY     | US       |               41.02 |                     0.06 |    -0.02 |      0.22 |                  71.8  |                        69.39 |         70.25 |         70.6  |          60.64 |        57.46 |           72.33 |             59.07 |         8.56 |
|              19 | DHT      | DHT      | US       |                2.68 |                     0.03 |    -0.02 |      0.11 |                  63.23 |                        69.25 |         69.89 |         66.94 |          68.93 |        74.74 |           89.73 |             45.82 |         4.56 |
|              20 | GPN      | GPN      | US       |               21.06 |                     0.02 |     0    |      0.07 |                  48.98 |                        68.72 |         69.15 |         75.79 |          67.78 |        68.4  |           52.85 |             86.09 |         5.84 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name               | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | ORCL     | Oracle Corporation | US       |              375.52 |             44.01 |          63.6 |         40.57 |          42.31 |        45.71 |           59.87 |             54.35 |             31.39 |         8.92 |             89.54 | short              |                2.11 |                  0.37 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      2 | CRWD     | CRWD     | US       |              200.27 |             81.64 |         86.04 |         85.86 |          77.43 |        49.84 |          nan    |             89.81 |              1.48 |         7.54 |             66.84 | short              |               27.21 |                  5.53 |                  nan |
|    440 | META     | META     | US       |             1248.3  |             52.56 |         56.42 |         43.27 |          49.51 |        55.62 |           73.16 |             66.26 |             35.37 |         6.31 |             66.59 | short              |                9.39 |                  3.5  |                  nan |
|     16 | SRAIL.SW | SRAIL.SW | EUROPE   |                3.35 |             74.9  |         82.41 |         79.61 |          70.19 |        61.85 |           80.1  |             78.4  |             24.24 |         5.65 |             69.68 | short              |                1    |                  3.47 |                  nan |
|    600 | TLRY     | TLRY     | US       |                0.54 |             44    |         51.94 |         38.3  |          40    |        48    |           38.1  |             67.36 |             64.92 |         8.28 |             69.68 | short              |               16.58 |                  3.23 |                  nan |
|    122 | KURA     | KURA     | US       |                1.01 |             65.38 |         85.49 |         72.78 |          57.99 |        44.42 |           50.39 |             64.6  |              3.99 |         7.37 |             66.84 | short              |                1.29 |                  3.22 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    526 | HMC      | HMC    | US       |               34.88 |             48.88 |         45.44 |         54.04 |          46.14 |        51.61 |           25.54 |            nan    |             88.52 |         5.12 |             61.82 | swing              |              -15.23 |                 -4.15 |                  nan |
|    640 | IHS      | IHS    | US       |                2.42 |             42.05 |         51.82 |         41.75 |          41.33 |        42.35 |           39.23 |             29.26 |             43.02 |         1.99 |             62.3  | short              |              -16.55 |                 -3.52 |                  nan |
|    717 | BBWI     | BBWI   | US       |                3.23 |             30.63 |         29.87 |         25.07 |          31.4  |        46.12 |           35.74 |              7.33 |             87.38 |         7.86 |             64.5  | long               |              nan    |                 -3.47 |                  nan |
|    550 | ENI.MI   | ENI.MI | EUROPE   |               65.44 |             47.39 |         33.39 |         41.08 |          53.69 |        56.46 |           61.96 |             28.02 |             57.37 |         3.57 |             67.86 | long               |              -13.17 |                 -3.33 |                  nan |
|    128 | PBF      | PBF    | US       |                6.98 |             65.25 |         47.17 |         65.88 |          66.32 |        64.61 |           52.74 |             27.48 |             81.02 |         7.36 |             69.23 | medium             |               -2.99 |                 -3.18 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
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
- Excluded by hard/data filters: **275**
- Event watch (otherwise eligible): **1**
- Final eligible: **724**
- Eligible change vs previous stored run: **+10**

Top exclusion categories:
- liquidity: 222
- price: 167
- market_cap: 156
- data_confidence: 17
- price_history: 17
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| FRO | 3 |  | 1 |  | 2 | main,pullback |
| V | 82 | 2 |  | 1 | 1 | value,quality_value |
| NVDA | 185 | 5 |  | 3 | 1 | value,quality_value |
| ASML.AS | 196 | 10 | 36 | 7 | 1 | value,quality_value |
| SAP.DE | 372 | 4 |  | 4 | 1 | value,quality_value |
| SU.PA | 414 | 7 | 146 | 9 | 1 | value,quality_value |
| LLY | 481 | 9 | 184 | 8 | 1 | value,quality_value |
| NFLX | 516 | 1 | 137 | 2 | 1 | value,quality_value |
| NOVN.SW | 534 | 6 | 245 | 6 | 1 | value,quality_value |
| MC.PA | 695 | 3 | 339 | 5 | 1 | value,quality_value |
| OKTA | 1 |  |  |  | 1 | main |
| CRWD | 2 |  |  |  | 1 | main |
| AVAH | 4 |  |  |  | 1 | main |
| MPC | 5 |  |  |  | 1 | main |
| WT | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (OKTA, CRWD, AVAH, MPC, WT, CAKE, DELL)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BP | pullback | 58.89 | 56.61 | 84.57 | 88.68 | 80.77 | 81.86 | 65.75 |
| 2 | NOVN.SW | value+pullback | 55.16 | 57.48 | 58.56 | 54.85 | 46.46 | 52.00 | 48.41 |
| 3 | OXY | pullback | 54.10 | 50.84 | 71.57 | 86.32 | 76.45 | 78.06 | 65.17 |
| 4 | MC.PA | value+pullback | 53.94 | 65.23 | 51.92 | 41.47 | 54.43 | 48.62 | 35.20 |
| 5 | REP.MC | pullback | 52.19 | 62.09 | 84.41 | 63.70 | 77.63 | 68.83 | 69.32 |
| 6 | EOG | pullback | 52.14 | 57.25 | 85.04 | 82.59 | 47.64 | 68.66 | 60.92 |
| 7 | GALD.SW | pullback | 51.92 | 31.67 | 66.45 | 77.99 | 78.71 | 78.67 | 53.70 |
| 8 | TALO | pullback | 51.75 | 51.85 | 86.07 | 69.10 | 68.32 | 65.20 | 69.08 |
| 9 | SDZ.SW | pullback | 51.68 | 34.86 | 81.23 | 66.92 | 73.45 | 69.96 | 55.04 |
| 10 | MGY | pullback | 51.36 | 54.26 | 86.67 | 79.59 | 47.77 | 64.88 | 54.56 |
| 11 | TTE.PA | pullback | 50.82 | 63.57 | 83.30 | 69.95 | 58.56 | 68.22 | 55.08 |
| 12 | ABBN.SW | pullback | 50.79 | 35.59 | 68.44 | 73.21 | 76.30 | 75.35 | 50.65 |
| 13 | TCOM | pullback | 50.27 | 55.93 | 81.11 | 60.40 | 82.19 | 63.58 | 49.22 |
| 14 | COP | pullback | 50.14 | 60.56 | 73.04 | 68.91 | 74.74 | 70.33 | 66.92 |
| 15 | APA | pullback | 50.11 | 53.02 | 78.02 | 73.76 | 63.71 | 65.85 | 71.58 |
| 16 | PR | pullback | 50.02 | 53.80 | 63.11 | 79.32 | 73.93 | 74.76 | 74.69 |
| 17 | NTAP | pullback | 49.88 | 37.55 | 59.02 | 87.16 | 72.27 | 74.10 | 72.66 |
| 18 | TK | pullback | 49.85 | 40.37 | 73.20 | 79.97 |  | 72.76 | 61.90 |
| 19 | DOW | pullback | 49.79 | 53.45 | 79.31 | 48.90 | 97.39 | 64.44 | 53.69 |
| 20 | CVE | pullback | 49.78 | 53.40 | 66.63 | 77.79 | 70.97 | 71.77 | 71.04 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 7/10 | 9/10 | 10/10 | 7/10 | 1/10 | 68.3 | 3 / 7 |
| Top 25 | 21/25 | 22/25 | 25/25 | 20/25 | 2/25 | 68.3 | 8 / 17 |
| Top 50 | 45/50 | 47/50 | 50/50 | 44/50 | 2/50 | 68.8 | 15 / 35 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=1, large_20_100b=3, mega_100b_plus=2
Top-10 sparse-data names: HQL (missing quality,revisions; conf=55.6)
