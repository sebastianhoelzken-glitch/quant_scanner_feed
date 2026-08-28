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

- **EUROPE:** 88.7/100
- **OTHER:** 78.1/100
- **US:** 84.3/100

## Main multi-horizon ranking

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO      | FRO      | US       |                8.49 |             76.82 |         74.93 |         77.3  |          77.46 |        76.34 |           84.33 |             82.83 |             60.04 |         5.26 |             69.68 | medium             |               12.11 |                  0.67 |                  nan |
|      2 | KIN.BR   | KIN.BR   | EUROPE   |                1.24 |             76.1  |         78.93 |         79.07 |          73.27 |        65.72 |           92.5  |             67.06 |             23.89 |         3.84 |             69.68 | swing              |               -1.24 |                 -0.14 |                  nan |
|      3 | OKTA     | OKTA     | US       |               25.08 |             75.37 |         82.73 |         78.35 |          72.39 |        49.11 |          nan    |             81.89 |             13.94 |         7.61 |             66.84 | short              |               12.66 |                  1.82 |                  nan |
|      4 | MPC      | MPC      | US       |               89.39 |             75.24 |         77.97 |         76.42 |          74.06 |        70.06 |           84.9  |             53.36 |             50.68 |         3.87 |             69.68 | short              |              nan    |                nan    |                  nan |
|      5 | DOCM.SW  | DOCM.SW  | EUROPE   |                0.6  |             74.12 |         78.59 |         78.63 |          69.66 |        57.68 |           52.72 |             78.42 |             43.67 |         7.2  |             66.84 | swing              |              nan    |                nan    |                  nan |
|      6 | AVAH     | AVAH     | US       |                2.51 |             73.84 |         82.77 |         76.9  |          70.79 |        67.42 |           92.96 |             55.65 |             35.47 |         7.41 |             68.66 | short              |               -5.34 |                 -0.97 |                  nan |
|      7 | SRAIL.SW | SRAIL.SW | EUROPE   |                3.23 |             73.69 |         83.65 |         76.68 |          70.71 |        63.3  |           80.29 |             78.55 |             29.97 |         5.47 |             69.68 | short              |               -0.21 |                  3.23 |                  nan |
|      8 | CRWD     | CRWD     | US       |              192.99 |             73.55 |         76.87 |         74.69 |          72.41 |        45.02 |          nan    |             90.22 |              1.4  |         7.38 |             66.84 | short              |               19.12 |                  3.92 |                  nan |
|      9 | WT       | WT       | US       |                3.19 |             73.41 |         80.42 |         75.96 |          70.86 |        61.83 |           73.2  |             80.44 |             27.87 |         5.32 |             69.68 | short              |               -4.02 |                 -0.54 |                  nan |
|     10 | NAT      | NAT      | US       |                1.24 |             72.58 |         59.98 |         74.82 |          76.01 |        70.34 |           79.26 |             87.58 |             42.18 |         4.62 |             68.89 | medium             |              nan    |                nan    |                  nan |
|     11 | CAKE     | CAKE     | US       |                4.81 |             72.2  |         70.36 |         76.55 |          74.04 |        64.35 |           86.81 |             67.12 |             19.75 |         5.75 |             67.18 | swing              |               -8    |                 -0.56 |                  nan |
|     12 | PAGP     | PAGP     | US       |                5.62 |             71.68 |         73.86 |         70.99 |          72.37 |        69.48 |           83.54 |             76.49 |             47.05 |         1.74 |             66.7  | short              |               -4.69 |                nan    |                  nan |
|     13 | DSX      | DSX      | US       |                0.3  |             71.59 |         76.09 |         62.15 |          67.1  |        79.95 |           90.33 |             44.2  |             92.11 |         5.5  |             67.86 | long               |                8.25 |                  2.07 |                  nan |
|     14 | RNG      | RNG      | US       |                5    |             71.52 |         77.3  |         78.84 |          65.74 |        50.54 |           22.32 |             84.65 |             53.79 |         7.2  |             67.75 | swing              |               -1.14 |                  0.24 |                  nan |
|     15 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.61 |             71    |         73.75 |         73.31 |          68.69 |        60.46 |           46.62 |             79.67 |             58.95 |         3.81 |             69.68 | short              |               15.26 |                  3.15 |                  nan |
|     16 | ABN.AS   | ABN.AS   | EUROPE   |               33.97 |             70.91 |         70.65 |         71.17 |          72.35 |        69.01 |           81.71 |             59.73 |             52.11 |         2.74 |             69.68 | medium             |                3.82 |                  0.08 |                  nan |
|     17 | BAYN.DE  | BAYN.DE  | EUROPE   |               47.81 |             70.5  |         55.26 |         70.53 |          75.24 |        70.47 |          nan    |             90.47 |             57.05 |         6.07 |             66.84 | medium             |               -3.42 |                 -0.04 |                  nan |
|     18 | NIQ      | NIQ      | US       |                4.89 |             70.42 |         81.45 |         80.41 |          60.43 |        48.77 |           37.38 |             94.41 |             38.52 |         9.04 |             68.2  | short              |               -4.15 |                 -0.8  |                  nan |
|     19 | AMC      | AMC      | US       |                2    |             70.3  |         48.32 |         69.53 |          71.07 |        71.46 |           84.72 |             60.88 |            nan    |         9.64 |             63.43 | long               |              nan    |                nan    |                  nan |
|     20 | ERO      | ERO      | US       |                3.5  |             70.27 |         77.5  |         66.31 |          67.23 |        73.32 |           83.5  |             48.38 |             69.35 |         7.6  |             69.68 | short              |               -6.46 |                 -1.71 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              215.49 |                  66.67 |                    74.5  |                 77.15 |              70.4  |                85.22 |                   14.78 |           95.11 |             70.59 |         nan |         nan |       nan |         nan |         9.85 |         10.09 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP       | US       |               93.68 |                  56.49 |                    67.59 |                 71.24 |              63.15 |                80.96 |                   19.04 |           87.27 |             79.09 |         nan |         nan |       nan |         nan |         9.51 |         20.17 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO      | US       |                8.49 |                  57.03 |                    67.4  |                 70.9  |              63.42 |                78.2  |                   21.8  |           84.33 |             82.83 |         nan |         nan |       nan |         nan |        10.14 |         10.88 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY      | US       |               14.99 |                  66.94 |                    67.29 |                 67.72 |              63.99 |                70.78 |                   29.22 |           89.61 |             30.52 |         nan |         nan |       nan |         nan |         7.41 |          5.57 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |               99.09 |                  69    |                    66.59 |                 66.06 |              65.9  |                63.92 |                   36.08 |           73.38 |             47.18 |         nan |         nan |       nan |         nan |         6.82 |          4.23 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS | EUROPE   |               14.59 |                  56.27 |                    66.58 |                 69.66 |              62.63 |                82.99 |                   17.01 |           84.48 |             71.79 |         nan |         nan |       nan |         nan |        11.25 |         14.09 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI   | EUROPE   |               21.82 |                  59.96 |                    66.11 |                 67.79 |              64.53 |                76.28 |                   23.72 |           71.66 |             76.35 |         nan |         nan |       nan |         nan |         8.85 |         14.03 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              165.22 |                  65.66 |                    66.04 |                 66.11 |              65.32 |                68.48 |                   31.52 |           70.85 |             57.21 |         nan |         nan |       nan |         nan |         8.89 |         10.9  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR      | US       |              103.05 |                  70.05 |                    65.54 |                 64.45 |              64.94 |                60.25 |                   39.75 |           73.62 |             36.59 |         nan |         nan |       nan |         nan |         4.65 |          4.68 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS   | EUROPE   |               11.92 |                  60.46 |                    65.47 |                 66.76 |              64.27 |                74.81 |                   25.19 |           69.71 |             72.69 |         nan |         nan |       nan |         nan |         8.75 |         12.35 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | COP      | COP      | US       |              135.14 |                  62.66 |                    65.42 |                 66.21 |              64.85 |                69.05 |                   30.95 |           66.83 |             72.99 |         nan |         nan |       nan |         nan |        13.68 |         17.24 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               17.7  |                  57.07 |                    65.31 |                 68.23 |              59.5  |                78.2  |                   21.8  |           97.29 |             43.3  |         nan |         nan |       nan |         nan |        10.27 |         13.9  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY      | US       |              117.37 |                  63    |                    65.26 |                 66.07 |              63.06 |                70    |                   30    |           78.3  |             50.98 |         nan |         nan |       nan |         nan |        10.15 |         14.67 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL     | US       |              215.94 |                  67.06 |                    65.23 |                 64.74 |              64.37 |                65.12 |                   34.88 |           72.97 |             43.69 |         nan |         nan |       nan |         nan |        10.31 |         10.06 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET       | US       |               63.32 |                  59.63 |                    65.16 |                 67.04 |              60.87 |                75.89 |                   24.11 |           89.67 |             42.73 |         nan |         nan |       nan |         nan |        12.18 |         14.6  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | REP.MC   | REP.MC   | EUROPE   |               28.9  |                  63.21 |                    65.16 |                 65.61 |              65.3  |                67.95 |                   32.05 |           62.52 |             75.62 |         nan |         nan |       nan |         nan |         7.36 |          8.64 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX      | CVX      | US       |              341.72 |                  61.97 |                    65.08 |                 65.92 |              64.38 |                70.19 |                   29.81 |           67.24 |             71.28 |         nan |         nan |       nan |         nan |        15.25 |         19.43 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE   | EUROPE   |               39.23 |                  68.39 |                    64.76 |                 63.61 |              65.18 |                58.06 |                   41.94 |          nan    |             54.83 |         nan |         nan |       nan |         nan |         2.88 |          7.5  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NAT      | NAT      | US       |                1.24 |                  52.01 |                    64.23 |                 68.12 |              60.33 |                78.45 |                   21.55 |           79.26 |             87.58 |         nan |         nan |       nan |         nan |        14.88 |         26.04 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               22.67 |                  58.11 |                    64.04 |                 66.29 |              58.48 |                74.4  |                   25.6  |           96.45 |             32.5  |         nan |         nan |       nan |         nan |        11.02 |         11.28 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              215.49 |                  66.67 |                    74.5  |                 77.15 |              70.4  |                85.22 |                   14.78 |           95.11 |             70.59 |         nan |         nan |       nan |         nan |         9.85 |         10.09 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP       | US       |               93.68 |                  56.49 |                    67.59 |                 71.24 |              63.15 |                80.96 |                   19.04 |           87.27 |             79.09 |         nan |         nan |       nan |         nan |         9.51 |         20.17 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO      | US       |                8.49 |                  57.03 |                    67.4  |                 70.9  |              63.42 |                78.2  |                   21.8  |           84.33 |             82.83 |         nan |         nan |       nan |         nan |        10.14 |         10.88 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS | EUROPE   |               14.59 |                  56.27 |                    66.58 |                 69.66 |              62.63 |                82.99 |                   17.01 |           84.48 |             71.79 |         nan |         nan |       nan |         nan |        11.25 |         14.09 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               17.7  |                  57.07 |                    65.31 |                 68.23 |              59.5  |                78.2  |                   21.8  |           97.29 |             43.3  |         nan |         nan |       nan |         nan |        10.27 |         13.9  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NAT      | NAT      | US       |                1.24 |                  52.01 |                    64.23 |                 68.12 |              60.33 |                78.45 |                   21.55 |           79.26 |             87.58 |         nan |         nan |       nan |         nan |        14.88 |         26.04 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI   | EUROPE   |               21.82 |                  59.96 |                    66.11 |                 67.79 |              64.53 |                76.28 |                   23.72 |           71.66 |             76.35 |         nan |         nan |       nan |         nan |         8.85 |         14.03 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY      | US       |               14.99 |                  66.94 |                    67.29 |                 67.72 |              63.99 |                70.78 |                   29.22 |           89.61 |             30.52 |         nan |         nan |       nan |         nan |         7.41 |          5.57 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | OXY      | OXY      | US       |               50.98 |                  52.26 |                    63.78 |                 67.61 |              59.04 |                77.36 |                   22.64 |           85.01 |             74.9  |         nan |         nan |       nan |         nan |        15.41 |         17.43 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET       | US       |               63.32 |                  59.63 |                    65.16 |                 67.04 |              60.87 |                75.89 |                   24.11 |           89.67 |             42.73 |         nan |         nan |       nan |         nan |        12.18 |         14.6  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAGP     | PAGP     | US       |                5.62 |                  49.33 |                    62.87 |                 66.97 |              58.06 |                82.73 |                   17.27 |           83.54 |             76.49 |         nan |         nan |       nan |         nan |        13.01 |         79.91 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS   | EUROPE   |               11.92 |                  60.46 |                    65.47 |                 66.76 |              64.27 |                74.81 |                   25.19 |           69.71 |             72.69 |         nan |         nan |       nan |         nan |         8.75 |         12.35 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               22.67 |                  58.11 |                    64.04 |                 66.29 |              58.48 |                74.4  |                   25.6  |           96.45 |             32.5  |         nan |         nan |       nan |         nan |        11.02 |         11.28 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | COP      | COP      | US       |              135.14 |                  62.66 |                    65.42 |                 66.21 |              64.85 |                69.05 |                   30.95 |           66.83 |             72.99 |         nan |         nan |       nan |         nan |        13.68 |         17.24 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              165.22 |                  65.66 |                    66.04 |                 66.11 |              65.32 |                68.48 |                   31.52 |           70.85 |             57.21 |         nan |         nan |       nan |         nan |         8.89 |         10.9  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY      | US       |              117.37 |                  63    |                    65.26 |                 66.07 |              63.06 |                70    |                   30    |           78.3  |             50.98 |         nan |         nan |       nan |         nan |        10.15 |         14.67 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |               99.09 |                  69    |                    66.59 |                 66.06 |              65.9  |                63.92 |                   36.08 |           73.38 |             47.18 |         nan |         nan |       nan |         nan |         6.82 |          4.23 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX      | CVX      | US       |              341.72 |                  61.97 |                    65.08 |                 65.92 |              64.38 |                70.19 |                   29.81 |           67.24 |             71.28 |         nan |         nan |       nan |         nan |        15.25 |         19.43 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CTSH     | CTSH     | US       |               24.89 |                  56.99 |                    63.19 |                 65.78 |              59.26 |                66.33 |                   33.67 |           83    |             62.89 |         nan |         nan |       nan |         nan |        10.14 |         13.74 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PR       | PR       | US       |               16.41 |                  54.09 |                    62.87 |                 65.71 |              59.48 |                73.85 |                   26.15 |           77.72 |             72.42 |         nan |         nan |       nan |         nan |        10.35 |         14.65 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name   | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AVAH     | AVAH   | US       |                2.51 |                     0.04 |     0.01 |      0.42 |                  55.64 |                        76.67 |         82.77 |         76.9  |          70.79 |        67.42 |           92.96 |             55.65 |         7.41 |
|               2 | NAT      | NAT    | US       |                1.24 |                     0.04 |    -0.03 |      0.04 |                  67.2  |                        76.48 |         59.98 |         74.82 |          76.01 |        70.34 |           79.26 |             87.58 |         4.62 |
|               3 | CAKE     | CAKE   | US       |                4.81 |                     0.04 |    -0.01 |      0.11 |                  67.58 |                        75.84 |         70.36 |         76.55 |          74.04 |        64.35 |           86.81 |             67.12 |         5.75 |
|               4 | TGB      | TGB    | US       |                2.9  |                     0.05 |    -0    |      0.36 |                  69.08 |                        74.3  |         78.23 |         69.55 |          66.47 |        63.63 |           56.93 |             89.56 |         7.69 |
|               5 | SSRM     | SSRM   | US       |                6.56 |                     0.05 |    -0.01 |      0.46 |                  70.81 |                        73.2  |         75.93 |         68.56 |          67.26 |        69.73 |           66.63 |             75.26 |         7.08 |
|               6 | ERO      | ERO    | US       |                3.5  |                     0.04 |    -0.01 |      0.44 |                  65.21 |                        72.49 |         77.5  |         66.31 |          67.23 |        73.32 |           83.5  |             48.38 |         7.6  |
|               7 | PR       | PR     | US       |               16.41 |                     0.05 |    -0.04 |      0.07 |                  80.02 |                        72.25 |         62.77 |         67.67 |          71.41 |        71.49 |           77.72 |             72.42 |         4.1  |
|               8 | KRX.IR   | KRX.IR | EUROPE   |               17.55 |                     0.02 |     0.01 |      0.27 |                  43.75 |                        71.85 |         78.71 |         66.48 |          62.97 |        62.05 |           97.93 |             42.33 |         5.14 |
|               9 | IAG      | IAG    | US       |               10.15 |                     0.07 |    -0.03 |      0.45 |                  68.35 |                        71.68 |         73.04 |         57.95 |          62.15 |        70.73 |           75.48 |             65.4  |         7.66 |
|              10 | VWS.CO   | VWS.CO | EUROPE   |               27.72 |                     0.02 |     0.02 |      0.21 |                  47.16 |                        71.64 |         77.69 |         63.54 |          63.82 |        60.43 |           89.44 |             52.19 |         5.55 |
|              11 | JHX      | JHX    | US       |               14.99 |                     0.04 |    -0.02 |      0.14 |                  64.48 |                        70.77 |         66.77 |         72.15 |          65.69 |        57.87 |           59.56 |             87.39 |         5.86 |
|              12 | REP.MC   | REP.MC | EUROPE   |               28.9  |                     0.05 |    -0.05 |      0.01 |                  85.15 |                        70.54 |         50.06 |         67.84 |          72.71 |        69.17 |           62.52 |             75.62 |         3.76 |
|              13 | MP       | MP     | US       |                8.63 |                     0.07 |    -0.07 |      0.36 |                  82.36 |                        70.24 |         65.81 |         46.17 |          45.73 |        43.17 |           57.73 |             89.55 |         8.76 |
|              14 | CVE      | CVE    | US       |               50.26 |                     0.04 |    -0.04 |      0.05 |                  74.12 |                        70.22 |         59.54 |         66.72 |          71.73 |        68.43 |           76.6  |             69.51 |         4.75 |
|              15 | TOST     | TOST   | US       |               17.53 |                     0.05 |    -0.04 |      0.09 |                  79.12 |                        69.57 |         58.32 |         66.47 |          58.41 |        51.78 |           67.37 |             73.25 |         6.77 |
|              16 | TIC      | TIC    | US       |                1.8  |                     0.09 |     0.01 |      0.31 |                  45.79 |                        69.45 |         73.8  |         62.17 |          55.4  |        54.93 |           56.09 |             96.43 |         7.88 |
|              17 | FSM      | FSM    | US       |                3.13 |                     0.04 |     0.02 |      0.45 |                  58.77 |                        69.34 |         76.92 |         57.97 |          57.04 |        69.37 |           77.64 |             43.58 |         7.11 |
|              18 | BAX      | BAX    | US       |               11.66 |                     0.08 |    -0.01 |     -0    |                  58.73 |                        69.19 |         53.87 |         69.1  |          67.39 |        65.04 |           76.12 |             70.72 |         5.96 |
|              19 | CRGY     | CRGY   | US       |                4.6  |                     0.04 |    -0.04 |      0.19 |                  70.47 |                        69.01 |         69.68 |         66.63 |          66.65 |        72.36 |           70.67 |             63.14 |         5.98 |
|              20 | APA      | APA    | US       |               12.86 |                     0.04 |    -0.02 |      0.14 |                  68.3  |                        68.86 |         69.15 |         67.38 |          70.1  |        68.87 |           73.46 |             62.31 |         5.52 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      8 | CRWD     | CRWD     | US       |              192.99 |             73.55 |         76.87 |         74.69 |          72.41 |        45.02 |          nan    |             90.22 |              1.4  |         7.38 |             66.84 | short              |               19.12 |                  3.92 |                  nan |
|      7 | SRAIL.SW | SRAIL.SW | EUROPE   |                3.23 |             73.69 |         83.65 |         76.68 |          70.71 |        63.3  |           80.29 |             78.55 |             29.97 |         5.47 |             69.68 | short              |               -0.21 |                  3.23 |                  nan |
|     15 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.61 |             71    |         73.75 |         73.31 |          68.69 |        60.46 |           46.62 |             79.67 |             58.95 |         3.81 |             69.68 | short              |               15.26 |                  3.15 |                  nan |
|    483 | META     | META     | US       |             1270.78 |             48.92 |         53.12 |         39.05 |          46.12 |        51.73 |           70.83 |             64.69 |             33.47 |         6.11 |             66.59 | short              |                5.75 |                  2.77 |                  nan |
|    545 | FVRR     | FVRR     | US       |                0.29 |             46.26 |         51.5  |         35.48 |          41.27 |        51.25 |           39.24 |             64.43 |             84.51 |         8.85 |             66.7  | short              |                8.46 |                  2.45 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    715 | DNUT     | DNUT   | US       |                0.52 |             29.91 |         51.72 |         31.56 |          28.26 |        26.54 |           21.94 |             38.55 |             21.7  |         6.92 |             69.68 | short              |              -13.54 |                 -4.39 |                  nan |
|    692 | VOR      | VOR    | US       |                1.16 |             35.56 |         39.68 |         46.81 |          31.44 |        21.01 |           17.54 |              3.47 |            nan    |         9.39 |             60.48 | swing              |              -19.3  |                 -4.16 |                  nan |
|    475 | HMC      | HMC    | US       |               35.68 |             49.17 |         48.6  |         52.57 |          43.75 |        49.74 |           26.66 |            nan    |             88.63 |         4.9  |             61.82 | swing              |              -14.94 |                 -4.09 |                  nan |
|    653 | IHS      | IHS    | US       |                2.44 |             39.24 |         44.03 |         37.8  |          38.56 |        39.93 |           39.74 |             28.64 |             42.05 |         1.91 |             62.3  | short              |              -19.36 |                 -4.08 |                  nan |
|    123 | PBF      | PBF    | US       |                7.29 |             62.33 |         50.31 |         63.73 |          63.27 |        61.38 |           51.75 |             26.51 |             79.56 |         7.26 |             69.23 | swing              |               -5.91 |                 -3.77 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_63d_rank` vs `sector_score`: r=0.98
- `relative_63d_rank` vs `sector_score`: r=0.95
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.86

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
- Excluded by hard/data filters: **271**
- Event watch (otherwise eligible): **0**
- Final eligible: **729**
- Eligible change vs previous stored run: **+15**

Top exclusion categories:
- liquidity: 217
- price: 163
- market_cap: 155
- data_confidence: 16
- price_history: 15
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AVAH | 6 |  | 1 |  | 2 | main,pullback |
| NAT | 10 |  | 2 |  | 2 | main,pullback |
| META | 483 | 1 |  | 1 | 1 | value,quality_value |
| LLY | 546 | 4 | 247 | 3 | 1 | value,quality_value |
| ORCL | 548 | 2 |  | 2 | 1 | value,quality_value |
| NOVO-B.CO | 680 | 3 | 376 | 4 | 1 | value,quality_value |
| FRO | 1 |  |  |  | 1 | main |
| KIN.BR | 2 |  |  |  | 1 | main |
| OKTA | 3 |  |  |  | 1 | main |
| MPC | 4 |  |  |  | 1 | main |
| DOCM.SW | 5 |  |  |  | 1 | main |
| SRAIL.SW | 7 |  |  |  | 1 | main |
| CRWD | 8 |  |  |  | 1 | main |
| WT | 9 |  |  |  | 1 | main |
| CAKE | 11 |  | 3 |  | 1 | pullback |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (FRO, KIN.BR, OKTA, MPC, DOCM.SW, SRAIL.SW, CRWD, WT)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (IAG)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BP | pullback | 57.41 | 56.49 | 80.88 | 87.27 | 79.09 | 80.96 | 60.12 |
| 2 | PR | pullback | 53.67 | 54.09 | 80.02 | 77.72 | 72.42 | 73.85 | 69.54 |
| 3 | OXY | pullback | 53.62 | 52.26 | 71.60 | 85.01 | 74.90 | 77.36 | 60.22 |
| 4 | SHELL.AS | pullback | 53.33 | 66.67 | 59.82 | 95.11 | 70.59 | 85.22 | 64.97 |
| 5 | NAT | pullback | 53.14 | 52.01 | 67.20 | 79.26 | 87.58 | 78.45 | 72.58 |
| 6 | DAR | pullback | 52.85 | 52.24 | 74.77 | 92.22 | 53.19 | 75.04 | 64.30 |
| 7 | GALD.SW | pullback | 52.78 | 31.45 | 70.40 | 78.68 | 76.56 | 78.60 | 52.65 |
| 8 | REP.MC | pullback | 51.82 | 63.21 | 85.15 | 62.52 | 75.62 | 67.95 | 68.50 |
| 9 | HQH | pullback | 51.41 | 57.52 | 83.78 |  |  | 89.84 | 65.11 |
| 10 | EOG | pullback | 51.41 | 57.79 | 84.13 | 81.16 | 46.14 | 67.94 | 55.57 |
| 11 | CAKE | pullback | 51.31 | 36.30 | 67.58 | 86.81 | 67.12 | 73.41 | 72.20 |
| 12 | CVE | pullback | 51.18 | 54.10 | 74.12 | 76.60 | 69.51 | 71.06 | 67.58 |
| 13 | FAST | pullback | 50.90 | 37.96 | 75.93 | 91.38 | 38.66 | 71.71 | 51.21 |
| 14 | SDZ.SW | pullback | 50.32 | 35.07 | 74.80 | 68.83 | 71.64 | 70.67 | 52.04 |
| 15 | MP | pullback | 50.22 | 41.33 | 82.36 | 57.73 | 89.55 | 60.10 | 45.95 |
| 16 | TALO | pullback | 50.16 | 52.60 | 80.57 | 68.24 | 67.89 | 64.98 | 64.69 |
| 17 | TOST | pullback | 49.94 | 39.64 | 79.12 | 67.37 | 73.25 | 63.65 | 58.37 |
| 18 | OMV.VI | pullback | 49.66 | 59.96 | 64.09 | 71.66 | 76.35 | 76.28 | 67.72 |
| 19 | HQL | pullback | 49.55 | 52.09 | 77.90 |  |  | 87.88 | 69.06 |
| 20 | MGY | pullback | 49.43 | 54.14 | 81.26 | 77.63 | 46.77 | 63.96 | 47.61 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 8/10 | 10/10 | 10/10 | 8/10 | 0/10 | 69.3 | 2 / 8 |
| Top 25 | 21/25 | 25/25 | 24/25 | 20/25 | 0/25 | 68.3 | 9 / 16 |
| Top 50 | 44/50 | 49/50 | 49/50 | 43/50 | 1/50 | 68.9 | 21 / 29 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=5, mid_5_20b=1, large_20_100b=2, mega_100b_plus=1
