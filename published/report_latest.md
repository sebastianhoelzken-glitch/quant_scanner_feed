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

- **EUROPE:** 91.0/100
- **OTHER:** 80.7/100
- **US:** 86.5/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE       | HPE       | US       |               67.18 |             79.81 |         80.78 |         83.51 |          78.84 |        70.49 |           75.34 |             70.78 |             47.5  |         6.69 |             65.68 | swing              |               -6.3  |                   nan |                  nan |
|      2 | MPC       | MPC       | US       |               86.25 |             78.66 |         79.46 |         79.55 |          77.86 |        74.48 |           86.36 |             58.56 |             54.76 |         3.84 |             67.5  | swing              |               -5.88 |                   nan |                  nan |
|      3 | FSLY      | FSLY      | US       |                4.12 |             77.99 |         86    |         83.09 |          72.89 |        53.15 |           44.75 |             99.02 |             13.27 |         8.38 |             67.5  | short              |               -2.85 |                   nan |                  nan |
|      4 | CLMT      | CLMT      | US       |                3.62 |             77.45 |         82.5  |         82.16 |          72.73 |        53.2  |           52.62 |             93.15 |              5.57 |         4.4  |             66.59 | short              |               -2.08 |                   nan |                  nan |
|      5 | BAX       | BAX       | US       |               11.94 |             77.33 |         77.92 |         84.76 |          76.73 |        71.76 |           76.72 |             99.02 |             54.11 |         5.78 |             66.02 | swing              |                4.11 |                   nan |                  nan |
|      6 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.73 |             76.73 |         74.31 |         74.25 |          79.16 |        82.45 |           75.01 |            nan    |             98.29 |         3.27 |             62.84 | long               |               -6.76 |                   nan |                  nan |
|      7 | AMCX      | AMCX      | US       |                0.44 |             76.62 |         82.58 |         82.18 |          71.06 |        63.37 |           24.87 |             88.51 |             93    |         6.61 |             67.05 | short              |                7.15 |                   nan |                  nan |
|      8 | NET       | NET       | US       |               97.16 |             76.01 |         81.24 |         81.67 |          70.78 |        53.01 |           59.47 |             93.77 |              1.59 |         6.71 |             67.5  | swing              |                1.18 |                   nan |                  nan |
|      9 | GENI      | GENI      | US       |                2.01 |             76.01 |         85.53 |         81.17 |          70.84 |        69.13 |           65.94 |             99.02 |             71.3  |         9.3  |             67.5  | short              |                0.96 |                   nan |                  nan |
|     10 | NTAP      | NTAP      | US       |               35.11 |             75.72 |         78.02 |         79.64 |          73.41 |        66.53 |           89.59 |             50.37 |             25.72 |         6.12 |             65.45 | swing              |               -4.72 |                   nan |                  nan |
|     11 | HALO      | HALO      | US       |                9.68 |             75.63 |         77.37 |         76.82 |          72.8  |        74.44 |           88.22 |             66.26 |             56.67 |         5.3  |             66.48 | short              |                0.32 |                   nan |                  nan |
|     12 | PBF       | PBF       | US       |                7.36 |             75.55 |         79.52 |         78    |          73.11 |        69.09 |           52.77 |             53.91 |             83.81 |         6.95 |             67.05 | short              |              -17.14 |                   nan |                  nan |
|     13 | ZETA      | ZETA      | US       |                6.26 |             75.4  |         86.62 |         82.63 |          68.18 |        53.88 |           52.74 |             82.76 |             22.64 |         7.54 |             67.05 | short              |               -5.02 |                   nan |                  nan |
|     14 | CRDO      | CRDO      | US       |               41.88 |             75.4  |         75.68 |         75.12 |          76.04 |        67.44 |           93.64 |             65.65 |             15.56 |         8.88 |             67.5  | medium             |                0.05 |                   nan |                  nan |
|     15 | U         | U         | US       |               17.59 |             75.28 |         83.27 |         85.8  |          67.28 |        51.25 |           48.93 |             99.02 |             20.81 |         8.24 |             67.5  | swing              |                0.42 |                   nan |                  nan |
|     16 | RMAX      | RMAX      | US       |                0.6  |             75.27 |         81.8  |         81.87 |          68.75 |        58.56 |           24.34 |             91.69 |             79.66 |         7.04 |             67.05 | swing              |              -11.32 |                   nan |                  nan |
|     17 | JCAP      | JCAP      | US       |                1.19 |             74.94 |         82.13 |         77.58 |          69.69 |        72.3  |           70.22 |             83.62 |             71.85 |         5.3  |             66.48 | short              |               -3.17 |                   nan |                  nan |
|     18 | DELL      | DELL      | US       |              274.03 |             74.86 |         77.6  |         78.77 |          72.12 |        61.53 |           71.34 |             52.81 |             28.48 |         7.62 |             66.59 | swing              |               -8.93 |                   nan |                  nan |
|     19 | NWL       | NWL       | US       |                2.3  |             74.74 |         79.62 |         82.88 |          69.85 |        63.34 |           38.94 |             96.58 |             76.01 |         8.03 |             66.02 | swing              |               -7.96 |                   nan |                  nan |
|     20 | HQL       | HQL       | US       |                0.55 |             74.62 |         72.52 |         73.3  |          76.12 |        75.94 |          nan    |            nan    |             73.72 |         1.79 |             55.57 | medium             |               13.11 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS             | EUROPE   |              215.21 |                  68.15 |                    72.01 |                 73.52 |              68.25 |                78.32 |                   21.68 |           93.91 |             50.86 |     nan     |         nan |       nan |      nan    |         9.72 |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A                | US       |               95.07 |                  68.96 |                    71.25 |                 72.13 |              70.08 |                74.56 |                   25.44 |           76.37 |            nan    |     nan     |         nan |       nan |      nan    |         6.53 |          4.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAH3.DE  | PAH3.DE              | EUROPE   |                8.46 |                  63.89 |                    68.84 |                 70.37 |              68.28 |                78.28 |                   21.72 |          nan    |             81.91 |     nan     |         nan |       nan |      nan    |         1.87 |         89.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | DSX      | DSX                  | US       |                0.27 |                  57.08 |                    68.79 |                 74.29 |              65.15 |                84.4  |                   15.6  |           90.59 |             88.61 |     nan     |         nan |       nan |      nan    |         4.13 |          5.06 |      nan    |                 nan |              nan |                   6 |                  0.32 |
|          nan | JD       | JD                   | US       |               33.91 |                  63.32 |                    67.59 |                 69.05 |              67.07 |                74.38 |                   25.62 |          nan    |             80.93 |     nan     |         nan |       nan |      nan    |         6.88 |         19.5  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                  | US       |              112.67 |                  64.5  |                    67.3  |                 68.29 |              64.93 |                72.71 |                   27.29 |           81.03 |             54.03 |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE               | EUROPE   |               37.62 |                  68.14 |                    66.53 |                 65.99 |              66.72 |                63.81 |                   36.19 |          nan    |             61.74 |     nan     |         nan |       nan |      nan    |         2.76 |          7.2  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR              | EUROPE   |               17.82 |                  60.33 |                    66.19 |                 68.38 |              60.92 |                76.35 |                   23.65 |           96.68 |             37.41 |     nan     |         nan |       nan |      nan    |        10.34 |         14    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE              | EUROPE   |               36.96 |                  68.87 |                    66.04 |                 65.17 |              66.36 |                60.58 |                   39.42 |          nan    |             58.68 |     nan     |         nan |       nan |      nan    |         3.13 |          7.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ALL      | ALL                  | US       |               57.12 |                  57.62 |                    65.87 |                 67.29 |              61.13 |                74.41 |                   25.59 |           83.28 |             62.52 |     nan     |         nan |       nan |      nan    |         9.48 |          5.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | META     | Meta Platforms, Inc. | US       |             1298.44 |                  71.12 |                    65.67 |                 62.77 |              63.48 |                53    |                   47    |           74.86 |             27.33 |       0.014 |         nan |       nan |       13.9  |        16.91 |         22.22 |        0.88 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL     | SHEL                 | US       |              215.86 |                  67.8  |                    65.62 |                 65.12 |              64.36 |                65.08 |                   34.92 |           76.42 |             38.26 |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                  | US       |               14.87 |                  57.67 |                    65.6  |                 68.26 |              61.47 |                76.72 |                   23.28 |           86.39 |             61.37 |     nan     |         nan |       nan |      nan    |        10.72 |         23.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | AVGO     | Broadcom Inc.        | US       |             1615.59 |                  59.62 |                    65.3  |                 64.71 |              61.89 |                74.75 |                   25.25 |           73.6  |             55.1  |       0.015 |         nan |       nan |       45.5  |        20.12 |         65.39 |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                  | US       |                7.93 |                  58.56 |                    65.24 |                 67.74 |              61.24 |                72.31 |                   27.69 |           85.78 |             60.64 |     nan     |         nan |       nan |      nan    |        10.43 |         10.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | SAP.DE   | SAP SE               | EUROPE   |              207.92 |                  81.4  |                    65.23 |                 58.43 |              70.63 |                47.12 |                   52.88 |           37.68 |             35.43 |       0.044 |         nan |       nan |       17.58 |        21.52 |         26.97 |        1.8  |                 nan |              nan |                  12 |                  0.63 |
|          nan | PRU      | PRU                  | US       |               37.3  |                  65.73 |                    64.18 |                 63.74 |              63.43 |                64.6  |                   35.4  |           71.05 |             44.74 |     nan     |         nan |       nan |      nan    |         8.5  |         11.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                  | US       |                2.72 |                  59.76 |                    64.14 |                 65.97 |              59.81 |                69.91 |                   30.09 |           89.15 |             42.05 |     nan     |         nan |       nan |      nan    |        10.46 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBLK     | SBLK                 | US       |                2.8  |                  60.33 |                    64.12 |                 65.46 |              61.65 |                69.55 |                   30.45 |           77.34 |             56.97 |     nan     |         nan |       nan |      nan    |         8.16 |         11.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | ONIT     | Onity Group Inc.     | US       |                0.28 |                  79.61 |                    63.41 |                 59.42 |              69.33 |                44.44 |                   55.56 |           43.64 |             40.11 |      -5.517 |         nan |       nan |       17.76 |         4.76 |          2.48 |        0.62 |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name          | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:--------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | DSX      | DSX           | US       |                0.27 |                  57.08 |                    68.79 |                 74.29 |              65.15 |                84.4  |                   15.6  |           90.59 |             88.61 |     nan     |         nan |       nan |       nan   |         4.13 |          5.06 |      nan    |                 nan |              nan |                   6 |                  0.32 |
|          nan | SHELL.AS | SHELL.AS      | EUROPE   |              215.21 |                  68.15 |                    72.01 |                 73.52 |              68.25 |                78.32 |                   21.68 |           93.91 |             50.86 |     nan     |         nan |       nan |       nan   |         9.72 |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A         | US       |               95.07 |                  68.96 |                    71.25 |                 72.13 |              70.08 |                74.56 |                   25.44 |           76.37 |            nan    |     nan     |         nan |       nan |       nan   |         6.53 |          4.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAH3.DE  | PAH3.DE       | EUROPE   |                8.46 |                  63.89 |                    68.84 |                 70.37 |              68.28 |                78.28 |                   21.72 |          nan    |             81.91 |     nan     |         nan |       nan |       nan   |         1.87 |         89.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | JD       | JD            | US       |               33.91 |                  63.32 |                    67.59 |                 69.05 |              67.07 |                74.38 |                   25.62 |          nan    |             80.93 |     nan     |         nan |       nan |       nan   |         6.88 |         19.5  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR       | EUROPE   |               17.82 |                  60.33 |                    66.19 |                 68.38 |              60.92 |                76.35 |                   23.65 |           96.68 |             37.41 |     nan     |         nan |       nan |       nan   |        10.34 |         14    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY           | US       |              112.67 |                  64.5  |                    67.3  |                 68.29 |              64.93 |                72.71 |                   27.29 |           81.03 |             54.03 |     nan     |         nan |       nan |       nan   |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN           | US       |               14.87 |                  57.67 |                    65.6  |                 68.26 |              61.47 |                76.72 |                   23.28 |           86.39 |             61.37 |     nan     |         nan |       nan |       nan   |        10.72 |         23.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO           | US       |                7.93 |                  58.56 |                    65.24 |                 67.74 |              61.24 |                72.31 |                   27.69 |           85.78 |             60.64 |     nan     |         nan |       nan |       nan   |        10.43 |         10.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ALL      | ALL           | US       |               57.12 |                  57.62 |                    65.87 |                 67.29 |              61.13 |                74.41 |                   25.59 |           83.28 |             62.52 |     nan     |         nan |       nan |       nan   |         9.48 |          5.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | GL9.IR   | GL9.IR        | EUROPE   |                5.61 |                  44.81 |                    60.99 |                 66.26 |              53.39 |                83.85 |                   16.15 |           97.85 |             60.39 |     nan     |         nan |       nan |       nan   |        15.94 |         27.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE        | EUROPE   |               37.62 |                  68.14 |                    66.53 |                 65.99 |              66.72 |                63.81 |                   36.19 |          nan    |             61.74 |     nan     |         nan |       nan |       nan   |         2.76 |          7.2  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT           | US       |                2.72 |                  59.76 |                    64.14 |                 65.97 |              59.81 |                69.91 |                   30.09 |           89.15 |             42.05 |     nan     |         nan |       nan |       nan   |        10.46 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OXY      | OXY           | US       |               50.41 |                  54.31 |                    62.58 |                 65.52 |              57.93 |                72.54 |                   27.46 |           86.17 |             57.7  |     nan     |         nan |       nan |       nan   |        14.83 |         17.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBLK     | SBLK          | US       |                2.8  |                  60.33 |                    64.12 |                 65.46 |              61.65 |                69.55 |                   30.45 |           77.34 |             56.97 |     nan     |         nan |       nan |       nan   |         8.16 |         11.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE       | EUROPE   |               36.96 |                  68.87 |                    66.04 |                 65.17 |              66.36 |                60.58 |                   39.42 |          nan    |             58.68 |     nan     |         nan |       nan |       nan   |         3.13 |          7.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL          | US       |              215.86 |                  67.8  |                    65.62 |                 65.12 |              64.36 |                65.08 |                   34.92 |           76.42 |             38.26 |     nan     |         nan |       nan |       nan   |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | AVGO     | Broadcom Inc. | US       |             1615.59 |                  59.62 |                    65.3  |                 64.71 |              61.89 |                74.75 |                   25.25 |           73.6  |             55.1  |       0.015 |         nan |       nan |        45.5 |        20.12 |         65.39 |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|          nan | MPC      | MPC           | US       |               86.25 |                  50.98 |                    61.04 |                 64.45 |              55.92 |                74.23 |                   25.77 |           86.36 |             58.56 |     nan     |         nan |       nan |       nan   |        11.04 |         12.33 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PR       | PR            | US       |               15.56 |                  59.24 |                    62.96 |                 64.39 |              59.91 |                68.25 |                   31.75 |           80.12 |             49.76 |     nan     |         nan |       nan |       nan   |         9.94 |         13.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.94 |                     0.06 |    -0.03 |      0.18 |                  78.19 |                        84.3  |         77.92 |         84.76 |          76.73 |        71.76 |           76.72 |             99.02 |         5.78 |
|               2 | HALO     | HALO     | US       |                9.68 |                     0.04 |    -0.04 |      0.27 |                  76.17 |                        77.69 |         77.37 |         76.82 |          72.8  |        74.44 |           88.22 |             66.26 |         5.3  |
|               3 | TIC      | TIC      | US       |                1.86 |                     0.07 |    -0.02 |      0.44 |                  70.44 |                        75.68 |         78.13 |         64.05 |          58.1  |        58.3  |           57.73 |             96.7  |         7.63 |
|               4 | CCC      | CCC      | US       |                3.55 |                     0.02 |     0.01 |      0.15 |                  47.72 |                        74.75 |         74.6  |         76.71 |          70.33 |        70.37 |           87.88 |             77.75 |         7.75 |
|               5 | AMRX     | AMRX     | US       |                5.46 |                     0.05 |     0    |      0.02 |                  67.42 |                        73.97 |         60.22 |         71.43 |          74.21 |        72.79 |           93.83 |             62.47 |         4.36 |
|               6 | SNOW     | SNOW     | US       |               98.51 |                     0.03 |    -0    |      0.22 |                  53.69 |                        73.2  |         74.48 |         83.49 |          68.12 |        48.21 |           45.5  |             95.35 |         8.83 |
|               7 | PLTR     | PLTR     | US       |              361.39 |                     0.03 |     0.01 |      0.31 |                  50.53 |                        72.44 |         78.86 |         65.34 |          57.45 |        54.46 |           90.58 |             48.78 |         8.29 |
|               8 | CLOV     | CLOV     | US       |                2.11 |                     0.04 |    -0.03 |     -0    |                  71.14 |                        71.78 |         49.87 |         72.56 |          72.94 |        56.12 |           55.09 |             92.05 |         8.45 |
|               9 | GH       | GH       | US       |               18.23 |                     0.07 |    -0.07 |      0.01 |                  82.98 |                        71.67 |         50.03 |         72.85 |          75.25 |        71.94 |           64.86 |             65.53 |         6.72 |
|              10 | OKTA     | OKTA     | US       |               22.14 |                     0.05 |    -0.01 |     -0.01 |                  68.58 |                        71.54 |         54.99 |         74.34 |          70.97 |        59.28 |           69.43 |             67.97 |         7.44 |
|              11 | ALL      | ALL      | US       |               57.12 |                     0.05 |    -0.02 |      0.05 |                  73.72 |                        71.49 |         60.98 |         68.79 |          71.2  |        74.11 |           83.28 |             62.52 |         3.61 |
|              12 | AXTI     | AXTI     | US       |                4.63 |                     0.08 |    -0.08 |      0.78 |                  79.23 |                        71.42 |         72.4  |         58.49 |          67.46 |        53.5  |           55.55 |             81.54 |         9.76 |
|              13 | TGB      | TGB      | OTHER    |                2.64 |                     0.05 |     0    |      0.23 |                  68.72 |                        70.67 |         78.56 |         65.07 |          62.9  |        58.88 |           44.16 |             81.66 |         7.52 |
|              14 | WKC      | WKC      | US       |                1.6  |                     0.1  |    -0.01 |     -0.01 |                  43.77 |                        70.57 |         55.02 |         75.34 |          75.76 |        66.58 |           57.42 |             99.02 |         3.01 |
|              15 | ELF      | ELF      | US       |                4.66 |                     0.07 |    -0.07 |      0.24 |                  81.45 |                        70.53 |         66.2  |         70.19 |          56.89 |        50.5  |           61.83 |             72.37 |         8.22 |
|              16 | QNST     | QNST     | US       |                1.02 |                     0.07 |    -0.03 |      0.22 |                  70.17 |                        70.24 |         75.02 |         73.08 |          67.79 |        68.67 |           86.25 |             33.01 |         7.78 |
|              17 | PENN     | PENN     | US       |                2.18 |                     0.11 |    -0.07 |     -0.09 |                  53.82 |                        70.15 |         37.53 |         67.06 |          73.14 |        68.66 |           77.07 |             87.53 |         6.53 |
|              18 | METSB.HE | METSB.HE | EUROPE   |                1.09 |                     0.06 |     0.01 |      0.23 |                  63.05 |                        70.03 |         77.04 |         62.52 |          54.7  |        53.65 |           50.1  |             80.2  |         4.29 |
|              19 | EXLS     | EXLS     | US       |                4.56 |                     0.03 |    -0    |      0.24 |                  57.5  |                        69.39 |         72.22 |         63.53 |          58.4  |        63.2  |           84.41 |             51.83 |         6.96 |
|              20 | AVTR     | AVTR     | US       |                7.98 |                     0.05 |     0.01 |      0.23 |                  66.28 |                        69.36 |         77.72 |         79.87 |          61.8  |        48.35 |           23.14 |             99.02 |         7.53 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation      | US       |             4712.46 |             62.62 |         64.6  |         53.97 |          60.64 |        67.36 |           90.68 |             46.42 |             50.71 |         5.56 |             89.53 | long               |               -1.38 |                   nan |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc. | US       |                3.38 |             35.84 |         29    |         34.26 |          37.43 |        48.48 |           38.21 |             29.52 |             83.08 |         7.48 |             87.87 | long               |              -10.18 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.     | OTHER    |                1.29 |             32.48 |         24.63 |         30    |          34.96 |        48.89 |           32.79 |             27.22 |             97.14 |         7.29 |             78.43 | long               |               -5.68 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

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
- Excluded by hard/data filters: **277**
- Event watch (otherwise eligible): **3**
- Final eligible: **720**
- Eligible change vs previous stored run: **+16**

Top exclusion categories:
- liquidity: 223
- price: 169
- market_cap: 152
- price_history: 20
- data_confidence: 17
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| BAX | 5 |  | 1 |  | 2 | main,pullback |
| DSX | 22 | 1 |  | 1 | 1 | value,quality_value |
| SLDE | 108 | 8 |  | 3 | 1 | value,quality_value |
| AVGO | 447 | 3 | 127 | 2 | 1 | value,quality_value |
| PBR | 449 | 6 | 236 | 5 | 1 | value,quality_value |
| SAP.DE | 460 | 4 |  | 10 | 1 | value,quality_value |
| NFLX | 516 | 7 |  | 6 | 1 | value,quality_value |
| NOVN.SW | 606 | 10 | 227 | 7 | 1 | value,quality_value |
| ONIT | 629 | 5 | 287 | 8 | 1 | value,quality_value |
| META | 660 | 2 | 273 | 4 | 1 | value,quality_value |
| HPE | 1 |  |  |  | 1 | main |
| MPC | 2 |  |  |  | 1 | main |
| FSLY | 3 |  |  |  | 1 | main |
| CLMT | 4 |  |  |  | 1 | main |
| SSABBH.HE | 6 |  |  |  | 1 | main |

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
| 1 | AVGO | value+pullback | 68.95 | 59.62 | 78.27 | 73.60 | 55.10 | 74.75 | 51.66 |
| 2 | NOVN.SW | value+pullback | 63.85 | 62.01 | 75.29 | 69.35 | 39.72 | 60.24 | 43.99 |
| 3 | PBR | value+pullback | 60.57 | 67.87 | 57.68 | 76.62 | 25.77 | 58.60 | 51.50 |
| 4 | META | value+pullback | 58.98 | 71.12 | 52.31 | 74.86 | 27.33 | 53.00 | 39.79 |
| 5 | WB | value+pullback | 58.70 | 84.23 | 76.91 | 26.97 | 21.18 | 40.18 | 27.95 |
| 6 | ALL-PH | value+pullback | 58.68 | 69.73 | 65.08 | 54.27 | 32.96 | 50.27 | 39.27 |
| 7 | ONIT | value+pullback | 57.88 | 79.61 | 58.20 | 43.64 | 40.11 | 44.44 | 42.37 |
| 8 | BAX | pullback | 56.67 | 47.46 | 78.19 | 76.72 | 99.02 | 78.55 | 77.33 |
| 9 | DSX | value | 56.46 | 57.08 | 47.95 | 90.59 | 88.61 | 84.40 | 74.32 |
| 10 | MC.PA | value+pullback | 55.51 | 56.66 | 80.52 | 32.65 | 48.28 | 43.29 | 33.38 |
| 11 | GL9.IR | pullback | 53.91 | 44.81 | 65.70 | 97.85 | 60.39 | 83.85 | 64.09 |
| 12 | HALO | pullback | 53.85 | 47.65 | 76.17 | 88.22 | 66.26 | 74.73 | 75.63 |
| 13 | MSFT | value+pullback | 53.30 | 58.21 | 52.50 | 50.00 | 56.27 | 47.94 | 58.09 |
| 14 | CYH | value+pullback | 53.29 | 76.56 | 62.59 | 27.72 | 22.31 | 41.45 | 39.44 |
| 15 | AMRX | pullback | 52.81 | 42.26 | 67.42 | 93.83 | 62.47 | 78.19 | 72.11 |
| 16 | PAH3.DE | pullback | 52.53 | 63.89 | 84.72 |  | 81.91 | 78.28 | 47.57 |
| 17 | ALL | pullback | 52.06 | 57.62 | 73.72 | 83.28 | 62.52 | 74.41 | 70.00 |
| 18 | BEN | pullback | 51.70 | 57.67 | 69.06 | 86.39 | 61.37 | 76.72 | 66.18 |
| 19 | GALD.SW | pullback | 51.62 | 31.50 | 78.72 | 79.60 | 55.38 | 72.33 | 51.81 |
| 20 | DIE.BR | pullback | 51.54 | 42.83 | 83.71 | 74.72 | 56.60 | 68.73 | 48.54 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 10/10 | 9/10 | 0/10 | 66.8 | 10 / 0 |
| Top 25 | 23/25 | 23/25 | 25/25 | 22/25 | 1/25 | 66.6 | 23 / 2 |
| Top 50 | 47/50 | 45/50 | 49/50 | 43/50 | 2/50 | 66.5 | 42 / 8 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=2, large_20_100b=4
