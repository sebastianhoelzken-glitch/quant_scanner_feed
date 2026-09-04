# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-04

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

- **EUROPE:** 87.5/100
- **OTHER:** 82.7/100
- **US:** 83.1/100

## Main multi-horizon ranking

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | SNOW     | SNOW     | US       |              106.65 |             78.85 |         84.08 |         84.79 |          73.61 |        45.49 |          nan    |             97.54 |              1.37 |         7.71 |             66.84 | swing              |               23.7  |                  2.53 |                 2.19 |
|      2 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.68 |             77.7  |         79.87 |         74.4  |          77.06 |        78.34 |           96.23 |             56.24 |             64.14 |         3.69 |             69.68 | short              |               -3.6  |                 -0.76 |               nan    |
|      3 | KIN.BR   | KIN.BR   | EUROPE   |                1.29 |             76    |         81.41 |         79.33 |          72.67 |        64.38 |           90.68 |             66.09 |             21    |         3.73 |             69.68 | short              |               -2.55 |                  0.92 |                 0.67 |
|      4 | DELL     | DELL     | US       |              288    |             75.87 |         83.8  |         76.77 |          74.97 |        64.12 |           74.01 |             77.8  |             32.23 |         7.4  |             68.77 | short              |               -3.24 |                  1.6  |                 1.99 |
|      5 | DSX      | DSX      | US       |                0.32 |             75.22 |         81.47 |         66.92 |          69.79 |        80.65 |           90.44 |             45.21 |             91.48 |         5.8  |             67.86 | short              |                1.48 |                  1.48 |                 0.65 |
|      6 | CRGY     | CRGY     | US       |                4.74 |             75.09 |         81.25 |         73.11 |          73.36 |        76.81 |           72.08 |             89.59 |             86.85 |         5.99 |             69.23 | short              |               -4.62 |                  0.42 |               nan    |
|      7 | DK       | DK       | US       |                3.83 |             75.01 |         82.17 |         78.59 |          71.43 |        58.46 |           56.01 |             86.13 |             32.89 |         6.93 |             69.68 | short              |               -3.01 |                 -0.53 |                -0.41 |
|      8 | AVAH     | AVAH     | US       |                2.57 |             74.72 |         82.91 |         78.25 |          71.18 |        67.87 |           93.91 |             54.31 |             35.84 |         7.36 |             68.66 | short              |               -1.68 |                 -0.7  |                -0.33 |
|      9 | HALO     | HALO     | US       |               10.85 |             74.28 |         81.99 |         77.3  |          71.26 |        69.08 |           87.64 |             56.39 |             48.87 |         5.41 |             68.66 | short              |              nan    |                nan    |               nan    |
|     10 | OKTA     | OKTA     | US       |               25.72 |             73.12 |         78.39 |         76.54 |          69.7  |        55.75 |           68.1  |             75.03 |             13.07 |         7.44 |             68.66 | short              |               -5.11 |                 -1.16 |                -1.61 |
|     11 | PR       | PR       | US       |               17.16 |             72.99 |         80.31 |         72.94 |          72.93 |        73.04 |           80.55 |             75.21 |             63.07 |         4.08 |             68.32 | short              |               -3.51 |                 -0.29 |                -0.41 |
|     12 | ABN.AS   | ABN.AS   | EUROPE   |               34.94 |             72.98 |         74.64 |         73.87 |          72.09 |        67.6  |           78.77 |             59.59 |             50.53 |         2.53 |             69.68 | short              |               -2.61 |                  0.01 |                 0.22 |
|     13 | GTLB     | GTLB     | US       |                7.09 |             72.62 |         86.94 |         81.18 |          64.06 |        48.64 |           60.18 |             92.94 |              7.85 |         8.3  |             69.68 | short              |               -3.97 |                  1.94 |                 1.71 |
|     14 | RSKD     | RSKD     | US       |                0.79 |             72.14 |         86.36 |         80    |          64.28 |        50.34 |           40.76 |             94.64 |             32.03 |         5.65 |             69.68 | short              |               -1.77 |                  2.06 |                 2.29 |
|     15 | C5H.IR   | C5H.IR   | EUROPE   |                1.76 |             71.72 |         74.9  |         71.34 |          70.14 |        72.09 |           91.7  |             64.42 |             54.31 |         2.04 |             69.68 | short              |              nan    |                nan    |               nan    |
|     16 | A5G.IR   | A5G.IR   | EUROPE   |               23.79 |             71.66 |         71.72 |         66.82 |          71.61 |        71.99 |           96.26 |             53.91 |             48.26 |         1.97 |             69.68 | long               |                0.23 |                  1.64 |                 1.43 |
|     17 | SHELL.AS | SHELL.AS | EUROPE   |              220.22 |             71.22 |         72.82 |         63.94 |          69.62 |        74.78 |           93.28 |             72.42 |             61.22 |         2.27 |             69.68 | long               |               -3.28 |                  0.99 |                 0.74 |
|     18 | WT       | WT       | US       |                3.25 |             71.19 |         71.68 |         74.53 |          70.7  |        61.7  |           74.01 |             76.83 |             26.62 |         5.4  |             69.68 | swing              |                0.65 |                nan    |               nan    |
|     19 | PBF      | PBF      | US       |                7.71 |             71    |         79.26 |         73.99 |          68.01 |        64.83 |           51.98 |             51.35 |             79.3  |         7.29 |             69.23 | short              |               -4.49 |                  0.5  |                 1.59 |
|     20 | MT.AS    | MT.AS    | EUROPE   |               49.51 |             70.77 |         68.95 |         69.63 |          74.14 |        71.91 |           72.38 |             81.75 |             65.06 |         4.86 |             69.68 | medium             |              nan    |                nan    |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              220.22 |                  67.33 |                    74.79 |                 77.27 |              71.07 |                85.25 |                   14.75 |           93.28 |             72.42 |         nan |         nan |       nan |         nan |        10.02 |         10.27 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR   | EUROPE   |               15.85 |                  63.32 |                    69.05 |                 70.87 |              65.6  |                79.72 |                   20.28 |           87.75 |             56.55 |         nan |         nan |       nan |         nan |         8.9  |          7.85 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              172.63 |                  65.72 |                    68.16 |                 68.72 |              67.9  |                72.84 |                   27.16 |           68.04 |             74.74 |         nan |         nan |       nan |         nan |         9.24 |         11.32 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY      | US       |               14.85 |                  67.81 |                    67.69 |                 67.97 |              64.47 |                70.83 |                   29.17 |           89.95 |             28.98 |         nan |         nan |       nan |         nan |         7.34 |          5.49 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS    | EUROPE   |               20.69 |                  63.75 |                    67.57 |                 68.46 |              66.63 |                75.95 |                   24.05 |           71.15 |             70.63 |         nan |         nan |       nan |         nan |         8.93 |         11.74 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |              109.8  |                  69.48 |                    67.1  |                 66.63 |              66.22 |                64.18 |                   35.82 |           75.12 |             46.39 |         nan |         nan |       nan |         nan |         7.55 |          4.75 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN      | US       |               46.32 |                  62.58 |                    67.01 |                 68.61 |              64.54 |                71.97 |                   28.03 |           79.46 |             65.27 |         nan |         nan |       nan |         nan |         8.99 |         10.65 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR  | EUROPE   |                4.68 |                  57.52 |                    66.85 |                 70.19 |              61.21 |                78.71 |                   21.29 |           96.23 |             56.24 |         nan |         nan |       nan |         nan |         8.94 |          6.32 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP      | KDP      | US       |               38.62 |                  55.15 |                    66.78 |                 70.57 |              61.86 |                82.1  |                   17.9  |           89.5  |             73.73 |         nan |         nan |       nan |         nan |        12.97 |         32.88 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR      | US       |              114.09 |                  69.2  |                    66    |                 65.35 |              65.02 |                61.9  |                   38.1  |           75.38 |             40.55 |         nan |         nan |       nan |         nan |         5.14 |          5.27 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ALLY     | ALLY     | US       |               11.45 |                  62.08 |                    65.9  |                 67.14 |              63.99 |                71.64 |                   28.36 |           75.49 |             63.92 |         nan |         nan |       nan |         nan |         6.78 |         10.26 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               23.79 |                  55.48 |                    65.85 |                 69.33 |              59.99 |                81.4  |                   18.6  |           96.26 |             53.91 |         nan |         nan |       nan |         nan |        11.53 |         11.83 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET       | US       |               63.72 |                  60.66 |                    65.81 |                 67.58 |              61.61 |                76.14 |                   23.86 |           90.03 |             42.36 |         nan |         nan |       nan |         nan |        12.25 |         14.68 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR   | EUROPE   |                1.76 |                  53.1  |                    65.01 |                 68.84 |              59.5  |                82.35 |                   17.65 |           91.7  |             64.42 |         nan |         nan |       nan |         nan |        10.84 |         13.33 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI   | EUROPE   |               22.46 |                  58.9  |                    65    |                 66.59 |              63.84 |                75.22 |                   24.78 |           67.88 |             78.89 |         nan |         nan |       nan |         nan |         9.02 |         14.43 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY     | US       |                4.74 |                  56.19 |                    64.84 |                 67.66 |              62.52 |                72.79 |                   27.21 |           72.08 |             89.59 |         nan |         nan |       nan |         nan |         6.4  |        174.5  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               18.74 |                  56.23 |                    64.64 |                 67.59 |              58.85 |                78.09 |                   21.91 |           96.46 |             43.01 |         nan |         nan |       nan |         nan |        10.88 |         14.72 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY      | US       |              120.06 |                  61.28 |                    64.64 |                 65.79 |              62    |                71.16 |                   28.84 |           79.71 |             50.74 |         nan |         nan |       nan |         nan |        10.38 |         14.9  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | XOM      | XOM      | US       |              575.72 |                  58.2  |                    64.53 |                 66.38 |              62.8  |                73.73 |                   26.27 |           70.79 |             76.23 |         nan |         nan |       nan |         nan |        15.04 |         20.9  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE   | EUROPE   |               38.65 |                  68.27 |                    64.5  |                 63.32 |              64.93 |                57.49 |                   42.51 |          nan    |             54.31 |         nan |         nan |       nan |         nan |         2.84 |          7.39 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name     | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS | EUROPE   |              220.22 |                  67.33 |                    74.79 |                 77.27 |              71.07 |                85.25 |                   14.75 |           93.28 |             72.42 |         nan |         nan |       nan |         nan |        10.02 |         10.27 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR   | EUROPE   |               15.85 |                  63.32 |                    69.05 |                 70.87 |              65.6  |                79.72 |                   20.28 |           87.75 |             56.55 |         nan |         nan |       nan |         nan |         8.9  |          7.85 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP      | KDP      | US       |               38.62 |                  55.15 |                    66.78 |                 70.57 |              61.86 |                82.1  |                   17.9  |           89.5  |             73.73 |         nan |         nan |       nan |         nan |        12.97 |         32.88 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR  | EUROPE   |                4.68 |                  57.52 |                    66.85 |                 70.19 |              61.21 |                78.71 |                   21.29 |           96.23 |             56.24 |         nan |         nan |       nan |         nan |         8.94 |          6.32 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR   | EUROPE   |               23.79 |                  55.48 |                    65.85 |                 69.33 |              59.99 |                81.4  |                   18.6  |           96.26 |             53.91 |         nan |         nan |       nan |         nan |        11.53 |         11.83 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR   | EUROPE   |                1.76 |                  53.1  |                    65.01 |                 68.84 |              59.5  |                82.35 |                   17.65 |           91.7  |             64.42 |         nan |         nan |       nan |         nan |        10.84 |         13.33 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA   | EUROPE   |              172.63 |                  65.72 |                    68.16 |                 68.72 |              67.9  |                72.84 |                   27.16 |           68.04 |             74.74 |         nan |         nan |       nan |         nan |         9.24 |         11.32 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | GOLD     | GOLD     | US       |                1.04 |                  52.38 |                    64.4  |                 68.62 |              59.36 |                75.73 |                   24.27 |           86.67 |             80.17 |         nan |         nan |       nan |         nan |        11.12 |         13.51 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN      | US       |               46.32 |                  62.58 |                    67.01 |                 68.61 |              64.54 |                71.97 |                   28.03 |           79.46 |             65.27 |         nan |         nan |       nan |         nan |         8.99 |         10.65 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS    | EUROPE   |               20.69 |                  63.75 |                    67.57 |                 68.46 |              66.63 |                75.95 |                   24.05 |           71.15 |             70.63 |         nan |         nan |       nan |         nan |         8.93 |         11.74 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | GL9.IR   | GL9.IR   | EUROPE   |                5.37 |                  41.42 |                    61.71 |                 68.14 |              53.67 |                89.51 |                   10.49 |           97.9  |             77.34 |         nan |         nan |       nan |         nan |        15.25 |         26.43 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY      | US       |               14.85 |                  67.81 |                    67.69 |                 67.97 |              64.47 |                70.83 |                   29.17 |           89.95 |             28.98 |         nan |         nan |       nan |         nan |         7.34 |          5.49 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY     | US       |                4.74 |                  56.19 |                    64.84 |                 67.66 |              62.52 |                72.79 |                   27.21 |           72.08 |             89.59 |         nan |         nan |       nan |         nan |         6.4  |        174.5  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR  | EUROPE   |               18.74 |                  56.23 |                    64.64 |                 67.59 |              58.85 |                78.09 |                   21.91 |           96.46 |             43.01 |         nan |         nan |       nan |         nan |        10.88 |         14.72 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET       | US       |               63.72 |                  60.66 |                    65.81 |                 67.58 |              61.61 |                76.14 |                   23.86 |           90.03 |             42.36 |         nan |         nan |       nan |         nan |        12.25 |         14.68 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ALLY     | ALLY     | US       |               11.45 |                  62.08 |                    65.9  |                 67.14 |              63.99 |                71.64 |                   28.36 |           75.49 |             63.92 |         nan |         nan |       nan |         nan |         6.78 |         10.26 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CTSH     | CTSH     | US       |               25.13 |                  58.01 |                    64.26 |                 66.91 |              60.15 |                67.23 |                   32.77 |           85.19 |             62.86 |         nan |         nan |       nan |         nan |        10.23 |         13.61 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PR       | PR       | US       |               17.16 |                  53.16 |                    63.44 |                 66.77 |              59.51 |                76.19 |                   23.81 |           80.55 |             75.21 |         nan |         nan |       nan |         nan |        10.66 |         15.32 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A    | US       |              109.8  |                  69.48 |                    67.1  |                 66.63 |              66.22 |                64.18 |                   35.82 |           75.12 |             46.39 |         nan |         nan |       nan |         nan |         7.55 |          4.75 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI   | EUROPE   |               22.46 |                  58.9  |                    65    |                 66.59 |              63.84 |                75.22 |                   24.78 |           67.88 |             78.89 |         nan |         nan |       nan |         nan |         9.02 |         14.43 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | DFDS.CO  | DFDS.CO  | EUROPE   |                1.11 |                     0.04 |    -0    |      0.18 |                  62.39 |                        73.11 |         76.68 |         66.34 |          69.06 |        65.18 |           63.02 |             85.4  |         5.84 |
|               2 | AMC      | AMC      | US       |                1.96 |                     0.06 |    -0.06 |     -0.01 |                  86.69 |                        72.87 |         47.36 |         67.89 |          69.25 |        70.35 |           83.97 |             60.89 |         9.59 |
|               3 | CCC      | CCC      | US       |                3.67 |                     0.05 |    -0.05 |      0.11 |                  85.92 |                        72.06 |         62.23 |         64.96 |          60.32 |        64.37 |           87.38 |             61.44 |         7.96 |
|               4 | WT       | WT       | US       |                3.25 |                     0.02 |    -0.02 |      0.14 |                  54.24 |                        71.73 |         71.68 |         74.53 |          70.7  |        61.7  |           74.01 |             76.83 |         5.4  |
|               5 | OKTA     | OKTA     | US       |               25.72 |                     0.02 |    -0.02 |      0.19 |                  50.99 |                        71.72 |         78.39 |         76.54 |          69.7  |        55.75 |           68.1  |             75.03 |         7.44 |
|               6 | ANF      | ANF      | US       |                5.5  |                     0.02 |     0    |      0.32 |                  46.38 |                        70.95 |         81.04 |         72.51 |          67.36 |        68.08 |           87.79 |             39.39 |         8.42 |
|               7 | TECK     | TECK     | US       |               29.14 |                     0.04 |    -0.02 |      0.04 |                  67.59 |                        70.43 |         63.39 |         59.98 |          69.51 |        68.05 |           88.06 |             73.22 |         5.67 |
|               8 | GL9.IR   | GL9.IR   | EUROPE   |                5.37 |                     0.07 |    -0.01 |     -0.06 |                  66.51 |                        70.36 |         42.84 |         58.41 |          73.24 |        69.43 |           97.9  |             77.34 |         2.08 |
|               9 | DASH     | DASH     | US       |               83.03 |                     0.06 |    -0.04 |      0.05 |                  79.67 |                        70.33 |         60.45 |         65.71 |          57.83 |        51.39 |           71.13 |             75.34 |         6.92 |
|              10 | TBI      | TBI      | US       |                0.26 |                     0.09 |    -0.07 |     -0.03 |                  72.07 |                        70.32 |         48.74 |         74.36 |          73.01 |        61.95 |           48.32 |             84.44 |         8.64 |
|              11 | PAGP     | PAGP     | US       |                5.57 |                     0.03 |    -0.01 |      0.09 |                  57.61 |                        70.11 |         70.7  |         63.49 |          66.94 |        68    |           85.25 |             60.45 |         1.55 |
|              12 | METSO.HE | METSO.HE | EUROPE   |               14.52 |                     0.05 |    -0.05 |      0.04 |                  78.9  |                        69.7  |         62.96 |         55.91 |          59.23 |        56.91 |           79.91 |             69.37 |         4.54 |
|              13 | WPM      | WPM      | US       |               61.4  |                     0.04 |    -0    |      0.26 |                  61.21 |                        69.59 |         75.47 |         57.15 |          53.36 |        55.18 |           87.08 |             35.06 |         6.91 |
|              14 | ITRG     | ITRG     | OTHER    |                0.51 |                     0.03 |    -0.02 |      0.19 |                  60.52 |                        68.96 |         68.27 |         54.46 |          55.21 |        62.61 |           69.23 |             79.37 |         8.21 |
|              15 | RAND.AS  | RAND.AS  | EUROPE   |                6.79 |                     0.04 |    -0.03 |      0.03 |                  73    |                        68.67 |         55.45 |         68.68 |          64.05 |        60.19 |           79.75 |             49.54 |         6.55 |
|              16 | CMG      | CMG      | US       |               41.04 |                     0.02 |     0.01 |      0.12 |                  47.87 |                        68.53 |         70.03 |         59.75 |          53.45 |        55.21 |           89.99 |             55.63 |         6.36 |
|              17 | NTG.CO   | NTG.CO   | EUROPE   |                0.79 |                     0.05 |    -0.02 |      0.07 |                  72.29 |                        68.42 |         64.3  |         67.3  |          66.9  |        62.42 |           85.38 |             45.64 |         4.96 |
|              18 | PAYX     | PAYX     | US       |               38.4  |                     0.02 |    -0.01 |      0.04 |                  51.57 |                        67.92 |         60.99 |         67.31 |          62.27 |        58.64 |           85.12 |             63.34 |         4.79 |
|              19 | DSFIR.AS | DSFIR.AS | EUROPE   |               23.06 |                     0.02 |     0    |      0    |                  47.43 |                        67.89 |         61.82 |         73.47 |          65.89 |        52.54 |           62.21 |             77.29 |         5.33 |
|              20 | PLTR     | PLTR     | US       |              378.61 |                     0.02 |    -0.02 |      0.17 |                  55.39 |                        67.67 |         68.57 |         60.66 |          54.4  |        52.71 |           90.64 |             46.3  |         8.48 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    148 | MAU.PA   | MAU.PA | EUROPE   |                1.63 |             61.38 |         65.8  |         41.49 |          56.96 |        67.79 |           74.57 |             51.55 |             71.11 |         5.07 |             69.68 | long               |                3.87 |                  2.87 |                 2.5  |
|    129 | ENI.MI   | ENI.MI | EUROPE   |               68.75 |             62.03 |         62.86 |         55.83 |          62.73 |        61.33 |           56.98 |             74.07 |             59.44 |         3.34 |             67.86 | short              |                6.08 |                  2.85 |                 3.16 |
|    442 | STLA     | STLA   | US       |               17.85 |             49.45 |         51.1  |         35.9  |          47.8  |        64.16 |           63.09 |             64.4  |             95.65 |         7.42 |             65.41 | long               |               14.09 |                  2.75 |                 1.64 |
|    601 | TLRY     | TLRY   | US       |                0.54 |             41.98 |         45.98 |         34.56 |          37.97 |        46.51 |           38.4  |             66.71 |             67.28 |         8.14 |             66.43 | long               |               12.1  |                  2.6  |                 1.97 |
|      1 | SNOW     | SNOW   | US       |              106.65 |             78.85 |         84.08 |         84.79 |          73.61 |        45.49 |          nan    |             97.54 |              1.37 |         7.71 |             66.84 | swing              |               23.7  |                  2.53 |                 2.19 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    488 | FNKO     | FNKO   | US       |                0.28 |             47.51 |         47.06 |         47.96 |          52.29 |        44.25 |           29.86 |             64.67 |             39.42 |         7.65 |             68.66 | medium             |               -8.61 |                 -5.26 |                -4.04 |
|    634 | CXM      | CXM    | US       |                1.26 |             39.44 |         31.8  |         41.05 |          38.3  |        40.57 |           34.2  |             36.9  |             53.73 |         6.64 |             69.23 | swing              |              -22.57 |                 -5.01 |               nan    |
|    664 | SIE.DE   | SIE.DE | EUROPE   |              211.14 |             35.87 |         36.13 |         35.62 |          36.71 |        27.38 |          nan    |             23.25 |             14.3  |         3.18 |             63.59 | medium             |              -18.6  |                 -4.54 |                -3.44 |
|    705 | AVGO     | AVGO   | US       |             1466.7  |             28.18 |         24.26 |         24.39 |          34.22 |        31.98 |          nan    |             28.66 |             24.45 |         5.78 |             62.41 | medium             |              -22.06 |                 -4.4  |                -3.08 |
|    710 | MC.PA    | MC.PA  | EUROPE   |              212.49 |             24.07 |         22.49 |         19.41 |          25.65 |        29.46 |           38.77 |             14.55 |             21.28 |         4.22 |             66.43 | long               |              -11.68 |                 -4.27 |                -3.28 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `ret_63d_rank` vs `sector_score`: r=0.99
- `relative_63d_rank` vs `sector_score`: r=0.98
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
- Excluded by hard/data filters: **287**
- Event watch (otherwise eligible): **0**
- Final eligible: **713**
- Eligible change vs previous stored run: **+0**

Top exclusion categories:
- liquidity: 232
- price: 188
- market_cap: 166
- data_confidence: 13
- price_history: 13
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| OKTA | 10 |  | 5 |  | 2 | main,pullback |
| MA | 244 | 1 | 64 | 1 | 1 | value,quality_value |
| AAPL | 338 | 2 |  | 2 | 1 | value,quality_value |
| SNOW | 1 |  |  |  | 1 | main |
| CMBT.BR | 2 |  |  |  | 1 | main |
| KIN.BR | 3 |  |  |  | 1 | main |
| DELL | 4 |  |  |  | 1 | main |
| DSX | 5 |  |  |  | 1 | main |
| CRGY | 6 |  |  |  | 1 | main |
| DK | 7 |  |  |  | 1 | main |
| AVAH | 8 |  |  |  | 1 | main |
| HALO | 9 |  |  |  | 1 | main |
| WT | 18 |  | 4 |  | 1 | pullback |
| ANF | 26 |  | 6 |  | 1 | pullback |
| AMC | 36 |  | 2 |  | 1 | pullback |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (CMBT.BR, KIN.BR, DELL, DSX, CRGY, HALO, OKTA)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (OKTA)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | GL9.IR | pullback | 56.95 | 41.42 | 66.51 | 97.90 | 77.34 | 89.51 | 63.92 |
| 2 | CCC | pullback | 54.23 | 47.17 | 85.92 | 87.38 | 61.44 | 67.49 | 63.30 |
| 3 | FAST | pullback | 53.88 | 38.34 | 76.67 | 90.77 | 56.41 | 77.28 | 51.62 |
| 4 | METSO.HE | pullback | 53.27 | 37.31 | 78.90 | 79.91 | 69.37 | 73.09 | 58.07 |
| 5 | AMC | pullback | 52.83 |  | 86.69 | 83.97 | 60.89 | 62.36 | 68.57 |
| 6 | TECK | pullback | 52.66 | 47.20 | 67.59 | 88.06 | 73.22 | 76.16 | 65.72 |
| 7 | A | pullback | 52.57 | 40.02 | 84.02 | 73.59 | 66.03 | 69.60 | 57.99 |
| 8 | GOLD | pullback | 52.25 | 52.38 | 64.32 | 86.67 | 80.17 | 75.73 | 56.16 |
| 9 | BEN | pullback | 51.96 | 56.17 | 73.58 | 87.25 | 54.20 | 75.26 | 61.07 |
| 10 | DASH | pullback | 51.30 | 39.08 | 79.67 | 71.13 | 75.34 | 65.90 | 59.14 |
| 11 | AFRM | pullback | 51.28 | 51.03 | 80.56 | 84.81 | 55.51 | 64.35 | 55.20 |
| 12 | FTNT | pullback | 50.00 | 35.43 | 73.47 | 74.25 | 65.38 | 69.79 | 54.43 |
| 13 | MU | pullback | 49.33 | 49.36 | 63.70 | 96.25 | 52.33 | 68.68 | 67.35 |
| 14 | BSY | pullback | 49.28 | 37.11 | 86.06 | 72.25 | 51.07 | 59.09 | 43.24 |
| 15 | PAGP | pullback | 49.00 | 50.50 | 57.61 | 85.25 | 60.45 | 78.82 | 67.47 |
| 16 | NTG.CO | pullback | 48.92 | 40.25 | 72.29 | 85.38 | 45.64 | 67.36 | 65.60 |
| 17 | SSABBH.HE | pullback | 48.66 | 50.75 | 74.73 | 71.91 |  | 70.95 | 65.21 |
| 18 | AALB.AS | pullback | 48.58 | 47.80 | 75.01 | 71.89 | 54.75 | 67.84 | 57.90 |
| 19 | FLS.CO | pullback | 48.57 | 38.59 | 79.12 | 87.86 | 29.07 | 63.52 | 52.85 |
| 20 | ADAM | pullback | 48.11 | 53.57 | 71.20 | 90.66 | 28.70 | 69.19 | 59.12 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 10/10 | 10/10 | 9/10 | 0/10 | 68.7 | 3 / 7 |
| Top 25 | 23/25 | 25/25 | 25/25 | 23/25 | 0/25 | 69.2 | 5 / 20 |
| Top 50 | 47/50 | 49/50 | 48/50 | 46/50 | 1/50 | 68.9 | 13 / 37 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=5, mid_5_20b=1, large_20_100b=1, mega_100b_plus=2
