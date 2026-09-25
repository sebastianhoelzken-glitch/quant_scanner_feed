# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-25

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

- **EUROPE:** 79.7/100
- **OTHER:** 69.6/100
- **US:** 80.5/100

## Main multi-horizon ranking

|   rank | symbol    | name               | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | CMBT.BR   | CMBT.BR            | EUROPE   |                4.78 |             81.55 |         69.69 |         80.37 |          84.53 |        82.73 |           96.37 |             78.65 |             62.96 |         3.69 |             73.14 | medium             |               -2.63 |                  1.08 |                 1.06 |
|      2 | FRO       | FRO                | US       |                9.38 |             79.58 |         79.76 |         79.4  |          80.49 |        76.3  |           91.48 |             81.14 |             49.99 |         5.37 |             73.14 | medium             |               -5.34 |                  0.04 |                 0.11 |
|      3 | HPE       | HPE                | US       |               74.08 |             79.41 |         86.46 |         81.49 |          77.33 |        67.24 |           73.46 |             82.48 |             41.03 |         6.9  |             72.34 | short              |               -1.95 |                 -0.08 |               nan    |
|      4 | MU        | MU                 | US       |             1072.18 |             78.29 |         76.65 |         66.25 |          81.37 |        79.94 |           95.13 |             82.75 |             62.65 |         8.1  |             73.14 | medium             |               -2.47 |                  1.87 |                 1.46 |
|      5 | VLO       | VLO                | US       |               96.85 |             77.8  |         74.32 |         80.46 |          80.74 |        75.14 |           87.05 |             81.5  |             50.82 |         3.51 |             69.68 | medium             |               -7.95 |                  0.1  |                 0.25 |
|      6 | AMC       | AMC                | US       |                2.28 |             77.73 |         78.52 |         82.44 |          76.93 |        76.03 |           86.28 |             79.3  |            nan    |         9.51 |             65.07 | swing              |                1.53 |                  3.77 |                 3.6  |
|      7 | DHT       | DHT                | US       |                3.07 |             77.03 |         77.17 |         76.88 |          77.72 |        75.43 |           88.05 |             83.82 |             52.71 |         4.44 |             73.14 | medium             |               -5.04 |                  0.13 |                -0.02 |
|      8 | REP.MC    | REP.MC             | EUROPE   |               32.93 |             76.97 |         83.12 |         79.81 |          74.13 |        70.25 |           61.36 |             79.05 |             68.35 |         3.7  |             73.14 | short              |                2.32 |                  1.55 |                 1.25 |
|      9 | SHELL.AS  | SHELL.AS           | EUROPE   |              239.91 |             76.91 |         80.68 |         74.7  |          73.25 |        79.11 |           93.42 |             80.23 |             63.51 |         2.39 |             73.14 | short              |                2.75 |                  2.57 |                 2.45 |
|     10 | KIN.BR    | KIN.BR             | EUROPE   |                1.36 |             76.88 |         79.58 |         79.91 |          74.18 |        64.88 |           90.04 |             64.38 |             16.81 |         3.63 |             69.89 | swing              |               -0.86 |                 -0.36 |                -0.28 |
|     11 | SSABBH.HE | SSABBH.HE          | EUROPE   |                9.41 |             76.49 |         66.95 |         73.15 |          79.84 |        82.28 |           72.41 |            nan    |             98.53 |         4.22 |             62.84 | long               |                1.31 |                nan    |               nan    |
|     12 | DELL      | DELL               | US       |              299.43 |             76.44 |         75.43 |         78.9  |          77.45 |        64.89 |           72.87 |             87.65 |             30.16 |         7.77 |             72.23 | swing              |               -7.18 |                 -1.16 |                -1.02 |
|     13 | BIRG.IR   | BIRG.IR            | EUROPE   |               18.96 |             75.77 |         77.17 |         73.86 |          75.04 |        76.51 |           96.82 |             67.69 |             55.26 |         2.14 |             73.14 | short              |                0.04 |                  1.81 |                 1.55 |
|     14 | OMV.VI    | OMV.VI             | EUROPE   |               23.6  |             75.66 |         78.04 |         78.65 |          73.29 |        69.85 |           62.91 |             85.03 |             65.12 |         1.82 |             72.34 | swing              |                4.44 |                  1.02 |                 0.54 |
|     15 | GH        | GH                 | US       |               20.8  |             75.16 |         68.28 |         78.43 |          79.12 |        71.89 |           63.26 |             89.07 |            nan    |         6.96 |             68.36 | medium             |              nan    |                nan    |               nan    |
|     16 | HSHP      | HSHP               | US       |                0.75 |             74.65 |         75.46 |         75.62 |          73.84 |        63.69 |           86.7  |            nan    |             19.17 |         4.76 |             62.84 | swing              |               -8.16 |                nan    |               nan    |
|     17 | MT.AS     | MT.AS              | EUROPE   |               47.92 |             74.39 |         64.41 |         74.78 |          77.75 |        73.99 |           70.95 |             83.54 |             68.12 |         5.02 |             73.14 | medium             |                1.79 |                  3.18 |               nan    |
|     18 | PBR-A     | PBR-A              | US       |              114.23 |             74.15 |         79.22 |         72.15 |          69.62 |        76.15 |           75.63 |             71.56 |             83.9  |         4.43 |             69.89 | short              |               -0.38 |                  0.13 |                -0.09 |
|     19 | NVDA      | NVIDIA Corporation | US       |             4764.53 |             74.13 |         79.58 |         73.96 |          72.47 |        74.3  |           83.7  |             80.61 |             61.17 |         6.44 |             90.13 | short              |                2.68 |                  1.62 |                 1.32 |
|     20 | NAT       | NAT                | US       |                1.43 |             73.95 |         76.9  |         73.58 |          74.32 |        68.52 |           88.03 |             69.09 |             32.59 |         4.81 |             73.14 | short              |               -6.61 |                 -0.83 |                -0.55 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name               | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS           | EUROPE   |              239.91 |                  58.53 |                    70.91 |                 74.87 |              65.93 |                87.59 |                   12.41 |           93.42 |             80.23 |     nan     |         nan |       nan |      nan    |         9.58 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | PBR-A    | PBR-A              | US       |              114.23 |                  68.56 |                    70.51 |                 71.27 |              69.46 |                71.86 |                   28.14 |           75.63 |             71.56 |     nan     |         nan |       nan |      nan    |         4.72 |          4.86 |        5.5  |                 nan |              nan |                   6 |                  0.32 |
|            2 | NVDA     | NVIDIA Corporation | US       |             4764.53 |                  60.87 |                    70.09 |                 71.79 |              65.55 |                75.9  |                   24.1  |           83.7  |             80.61 |       0.008 |         nan |       nan |       26.77 |        14.32 |         28.5  |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP       | BP                 | US       |              100.49 |                  58.05 |                    69.97 |                 73.88 |              65.66 |                83.42 |                   16.58 |           87.92 |             88.44 |     nan     |         nan |       nan |      nan    |         9.03 |         21.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL               | US       |              239.6  |                  64.3  |                    69.91 |                 71.56 |              68.39 |                77.71 |                   22.29 |           75.25 |             81.02 |     nan     |         nan |       nan |      nan    |         9.23 |         10.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR            | EUROPE   |                4.78 |                  55.44 |                    69.17 |                 73.74 |              63.26 |                85.98 |                   14.02 |           96.37 |             78.65 |     nan     |         nan |       nan |      nan    |         9.05 |          6.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                 | US       |                7.34 |                  61.38 |                    68.76 |                 71.54 |              65.53 |                73.25 |                   26.75 |           82.81 |             81.5  |     nan     |         nan |       nan |      nan    |         4.4  |          6.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR            | EUROPE   |               18.96 |                  56.21 |                    68.5  |                 72.52 |              62.68 |                85.76 |                   14.24 |           96.82 |             67.69 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                | US       |                9.38 |                  55.84 |                    68.1  |                 72.32 |              62.9  |                81    |                   19    |           91.48 |             81.14 |     nan     |         nan |       nan |      nan    |        10.48 |          7.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                | US       |                3.07 |                  55.86 |                    68.01 |                 72.02 |              63.36 |                82    |                   18    |           88.05 |             83.82 |     nan     |         nan |       nan |      nan    |        10.1  |          7.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA             | EUROPE   |              176.3  |                  62.62 |                    67.9  |                 69.28 |              67.32 |                75.65 |                   24.35 |           67.31 |             86.16 |     nan     |         nan |       nan |      nan    |         8.69 |         11.43 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR             | EUROPE   |               15.63 |                  63.16 |                    67.83 |                 69.34 |              64.53 |                77.23 |                   22.77 |           86.41 |             51.53 |     nan     |         nan |       nan |      nan    |         8.71 |          7.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS              | EUROPE   |               20.88 |                  63.01 |                    66.14 |                 66.88 |              65.01 |                73.71 |                   26.29 |           71.6  |             63.77 |     nan     |         nan |       nan |      nan    |         9.03 |         11.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR             | EUROPE   |               24.48 |                  55.81 |                    66.03 |                 69.5  |              60.18 |                80.93 |                   19.07 |           96.43 |             54.28 |     nan     |         nan |       nan |      nan    |        11.78 |         12.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR                | US       |              118    |                  68.63 |                    65.8  |                 65.32 |              64.64 |                61.54 |                   38.46 |           75.9  |             41.5  |     nan     |         nan |       nan |      nan    |         5.23 |          5.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | AVGO     | Broadcom Inc.      | US       |             1469.43 |                  60.81 |                    65.72 |                 65.2  |              60.47 |                74.47 |                   25.53 |           86.96 |             32.82 |       0.018 |         nan |       nan |       32.68 |        18.07 |         45.27 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | EQNR     | EQNR               | US       |               89.91 |                  56.22 |                    65.58 |                 68.69 |              62.48 |                74.85 |                   25.15 |           77.48 |             85.29 |     nan     |         nan |       nan |      nan    |        10.5  |         11.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | SAP.DE   | SAP SE             | EUROPE   |              213    |                  81.24 |                    65.57 |                 59.04 |              71.34 |                45.78 |                   54.22 |           34.78 |             46.09 |       0.043 |         nan |       nan |       17.98 |        22.05 |         28    |        1.63 |                 nan |              nan |                  12 |                  0.63 |
|          nan | ASRNL.AS | ASRNL.AS           | EUROPE   |               14.9  |                  57.41 |                    65.43 |                 67.8  |              62.13 |                79.23 |                   20.77 |           81.12 |             65.33 |     nan     |         nan |       nan |      nan    |        11.38 |         14.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBMO.AS  | SBMO.AS            | EUROPE   |                5.99 |                  56.63 |                    64.95 |                 67.81 |              61.17 |                74.23 |                   25.77 |           82.56 |             70.31 |     nan     |         nan |       nan |      nan    |         9.14 |          7.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name               | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS           | EUROPE   |              239.91 |                  58.53 |                    70.91 |                 74.87 |              65.93 |                87.59 |                   12.41 |           93.42 |             80.23 |     nan     |         nan |       nan |      nan    |         9.58 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                 | US       |              100.49 |                  58.05 |                    69.97 |                 73.88 |              65.66 |                83.42 |                   16.58 |           87.92 |             88.44 |     nan     |         nan |       nan |      nan    |         9.03 |         21.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR            | EUROPE   |                4.78 |                  55.44 |                    69.17 |                 73.74 |              63.26 |                85.98 |                   14.02 |           96.37 |             78.65 |     nan     |         nan |       nan |      nan    |         9.05 |          6.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR            | EUROPE   |               18.96 |                  56.21 |                    68.5  |                 72.52 |              62.68 |                85.76 |                   14.24 |           96.82 |             67.69 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                | US       |                9.38 |                  55.84 |                    68.1  |                 72.32 |              62.9  |                81    |                   19    |           91.48 |             81.14 |     nan     |         nan |       nan |      nan    |        10.48 |          7.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                | US       |                3.07 |                  55.86 |                    68.01 |                 72.02 |              63.36 |                82    |                   18    |           88.05 |             83.82 |     nan     |         nan |       nan |      nan    |        10.1  |          7.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA     | NVIDIA Corporation | US       |             4764.53 |                  60.87 |                    70.09 |                 71.79 |              65.55 |                75.9  |                   24.1  |           83.7  |             80.61 |       0.008 |         nan |       nan |       26.77 |        14.32 |         28.5  |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL     | SHEL               | US       |              239.6  |                  64.3  |                    69.91 |                 71.56 |              68.39 |                77.71 |                   22.29 |           75.25 |             81.02 |     nan     |         nan |       nan |      nan    |         9.23 |         10.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                 | US       |                7.34 |                  61.38 |                    68.76 |                 71.54 |              65.53 |                73.25 |                   26.75 |           82.81 |             81.5  |     nan     |         nan |       nan |      nan    |         4.4  |          6.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | PBR-A    | PBR-A              | US       |              114.23 |                  68.56 |                    70.51 |                 71.27 |              69.46 |                71.86 |                   28.14 |           75.63 |             71.56 |     nan     |         nan |       nan |      nan    |         4.72 |          4.86 |        5.5  |                 nan |              nan |                   6 |                  0.32 |
|          nan | A5G.IR   | A5G.IR             | EUROPE   |               24.48 |                  55.81 |                    66.03 |                 69.5  |              60.18 |                80.93 |                   19.07 |           96.43 |             54.28 |     nan     |         nan |       nan |      nan    |        11.78 |         12.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                 | US       |             1072.18 |                  47.76 |                    63.69 |                 69.38 |              56.69 |                77.93 |                   22.07 |           95.13 |             82.75 |     nan     |         nan |       nan |      nan    |         6.77 |         24.21 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR             | EUROPE   |               15.63 |                  63.16 |                    67.83 |                 69.34 |              64.53 |                77.23 |                   22.77 |           86.41 |             51.53 |     nan     |         nan |       nan |      nan    |         8.71 |          7.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA             | EUROPE   |              176.3  |                  62.62 |                    67.9  |                 69.28 |              67.32 |                75.65 |                   24.35 |           67.31 |             86.16 |     nan     |         nan |       nan |      nan    |         8.69 |         11.43 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                | US       |               96.85 |                  49.73 |                    64.16 |                 68.76 |              58.82 |                82.59 |                   17.41 |           87.05 |             81.5  |     nan     |         nan |       nan |      nan    |        10.06 |         15.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EQNR     | EQNR               | US       |               89.91 |                  56.22 |                    65.58 |                 68.69 |              62.48 |                74.85 |                   25.15 |           77.48 |             85.29 |     nan     |         nan |       nan |      nan    |        10.5  |         11.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                | US       |               14.53 |                  53.62 |                    64.68 |                 68.17 |              60.56 |                79.4  |                   20.6  |           82.54 |             76.62 |     nan     |         nan |       nan |      nan    |        10.21 |         22.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR             | EUROPE   |                1.67 |                  51.39 |                    63.7  |                 67.88 |              56.99 |                81.03 |                   18.97 |           97.94 |             54.12 |     nan     |         nan |       nan |      nan    |        10.42 |         10.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBMO.AS  | SBMO.AS            | EUROPE   |                5.99 |                  56.63 |                    64.95 |                 67.81 |              61.17 |                74.23 |                   25.77 |           82.56 |             70.31 |     nan     |         nan |       nan |      nan    |         9.14 |          7.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS           | EUROPE   |               14.9  |                  57.41 |                    65.43 |                 67.8  |              62.13 |                79.23 |                   20.77 |           81.12 |             65.33 |     nan     |         nan |       nan |      nan    |        11.38 |         14.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | FRO       | FRO       | US       |                9.38 |                     0.07 |    -0.05 |      0.24 |                  78.62 |                        82.14 |         79.76 |         79.4  |          80.49 |        76.3  |           91.48 |             81.14 |         5.37 |
|               2 | VLO       | VLO       | US       |               96.85 |                     0.07 |    -0.07 |      0.1  |                  80.29 |                        81.91 |         74.32 |         80.46 |          80.74 |        75.14 |           87.05 |             81.5  |         3.51 |
|               3 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.78 |                     0.09 |    -0.06 |      0.04 |                  70.26 |                        81.8  |         69.69 |         80.37 |          84.53 |        82.73 |           96.37 |             78.65 |         3.69 |
|               4 | DHT       | DHT       | US       |                3.07 |                     0.07 |    -0.05 |      0.18 |                  77.15 |                        80.34 |         77.17 |         76.88 |          77.72 |        75.43 |           88.05 |             83.82 |         4.44 |
|               5 | SMTC      | SMTC      | US       |               14.31 |                     0.06 |    -0.02 |      0.24 |                  75.79 |                        78.86 |         78.9  |         70.4  |          72.09 |        59.78 |           75.93 |             85.68 |         8.44 |
|               6 | DELL      | DELL      | US       |              299.43 |                     0.09 |    -0.09 |      0.16 |                  75.74 |                        78.53 |         75.43 |         78.9  |          77.45 |        64.89 |           72.87 |             87.65 |         7.77 |
|               7 | NAT       | NAT       | US       |                1.43 |                     0.07 |    -0.06 |      0.22 |                  78.15 |                        78.14 |         76.9  |         73.58 |          74.32 |        68.52 |           88.03 |             69.09 |         4.81 |
|               8 | BP        | BP        | US       |              100.49 |                     0.05 |    -0.02 |      0.04 |                  76.89 |                        77.99 |         71.22 |         67.91 |          68.53 |        73.47 |           87.92 |             88.44 |         4.44 |
|               9 | SHELL.AS  | SHELL.AS  | EUROPE   |              239.91 |                     0.02 |     0.02 |      0.07 |                  41.24 |                        77.24 |         80.68 |         74.7  |          73.25 |        79.11 |           93.42 |             80.23 |         2.39 |
|              10 | EQNR      | EQNR      | US       |               89.91 |                     0.06 |    -0.03 |      0.05 |                  77.6  |                        75.98 |         68.28 |         72.11 |          71.03 |        70.27 |           77.48 |             85.29 |         5.62 |
|              11 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.23 |                     0.03 |    -0.01 |      0.39 |                  57.55 |                        75.78 |         83.76 |         77.52 |          68.45 |        67.99 |           83.57 |             57.04 |         5.32 |
|              12 | GH        | GH        | US       |               20.8  |                     0.04 |    -0.04 |      0.03 |                  69.86 |                        75.71 |         68.28 |         78.43 |          79.12 |        71.89 |           63.26 |             89.07 |         6.96 |
|              13 | C5H.IR    | C5H.IR    | EUROPE   |                1.67 |                     0.05 |     0.02 |      0.06 |                  63.04 |                        75.21 |         76.1  |         67.35 |          71.59 |        74.81 |           97.94 |             54.12 |         2.61 |
|              14 | MT.AS     | MT.AS     | EUROPE   |               47.92 |                     0.06 |     0.01 |     -0.01 |                  66.73 |                        74.12 |         64.41 |         74.78 |          77.75 |        73.99 |           70.95 |             83.54 |         5.02 |
|              15 | ARGX.BR   | ARGX.BR   | EUROPE   |               52.83 |                     0.07 |    -0.02 |     -0.05 |                  69.78 |                        74.11 |         57.06 |         65.18 |          68.9  |        61.72 |           93.48 |             82.4  |         6.12 |
|              16 | NESTE.HE  | NESTE.HE  | EUROPE   |               26.59 |                     0.03 |    -0.01 |      0.11 |                  59.12 |                        74.07 |         78.98 |         74.01 |          69.3  |        60.95 |           62.63 |             87.9  |         4.84 |
|              17 | DAR       | DAR       | US       |                8.56 |                     0.09 |    -0.07 |     -0.01 |                  71.22 |                        73.73 |         53.83 |         64.06 |          73.39 |        77.45 |           89.68 |             87.22 |         4.7  |
|              18 | PBR-A     | PBR-A     | US       |              114.23 |                     0.03 |     0    |      0.19 |                  54.36 |                        73.63 |         79.22 |         72.15 |          69.62 |        76.15 |           75.63 |             71.56 |         4.43 |
|              19 | BE        | BE        | US       |               69    |                     0.05 |    -0.05 |      0.22 |                  82.56 |                        73.07 |         68.77 |         52.24 |          64.59 |        57.47 |           86.67 |             59.76 |         9.14 |
|              20 | FORTUM.HE | FORTUM.HE | EUROPE   |               21.27 |                     0.04 |    -0.03 |      0.14 |                  73.16 |                        72.81 |         77.02 |         65.16 |          58.45 |        52.81 |           68.12 |             64.69 |         4.6  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      6 | AMC      | AMC    | US       |                2.28 |             77.73 |         78.52 |         82.44 |          76.93 |        76.03 |           86.28 |             79.3  |            nan    |         9.51 |             65.07 | swing              |                1.53 |                  3.77 |                 3.6  |
|    109 | RBI.VI   | RBI.VI | EUROPE   |               21.47 |             65.15 |         73.81 |         69.42 |          60.88 |        47.63 |           10.42 |             71.8  |             65.68 |         4.38 |             71.77 | short              |                4.9  |                  3.68 |                 3.12 |
|    577 | ZH       | ZH     | US       |                0.28 |             41.59 |         69.56 |         50.3  |          32.87 |        24.6  |           18.06 |             26.16 |             24.02 |         7.31 |             73.14 | short              |                2.54 |                  3.55 |                 2.64 |
|    299 | BHF      | BHF    | US       |                2.7  |             54.95 |         62.36 |         36.95 |          47.54 |        64.89 |           66.77 |             46.18 |             95.48 |         4.02 |             69.55 | long               |               12.2  |                  3.28 |                 2.71 |
|     17 | MT.AS    | MT.AS  | EUROPE   |               47.92 |             74.39 |         64.41 |         74.78 |          77.75 |        73.99 |           70.95 |             83.54 |             68.12 |         5.02 |             73.14 | medium             |                1.79 |                  3.18 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    636 | SONY     | SONY    | US       |              118.07 |             36.26 |         37.04 |         45.06 |          35.47 |        30.32 |           23.02 |             43.99 |             29.4  |         5.14 |             69.5  | swing              |              nan    |                 -4.81 |                -4.49 |
|    498 | CNC      | CNC     | US       |               26.87 |             46.53 |         38.63 |         50.56 |          55.31 |        42.5  |           12.55 |             71.84 |             54.8  |         5.86 |             71.66 | medium             |              -12.69 |                 -4.16 |                -3.5  |
|    454 | TEVA     | TEVA    | US       |               41.21 |             49.29 |         66.93 |         54.53 |          44.05 |        35.41 |           18.21 |             24.57 |             40.26 |         4.75 |             72.34 | short              |               -5.72 |                 -4.09 |                -4.05 |
|    241 | HAFN     | HAFN    | US       |                4.2  |             57.51 |         64.97 |         56.57 |          55.34 |        58.45 |           74.27 |             14.02 |             49.7  |         5.68 |             69.68 | short              |               -8.46 |                 -3.85 |                -4.44 |
|    669 | PAH3.DE  | PAH3.DE | EUROPE   |                7.91 |             32.76 |         28.76 |         29.25 |          36.28 |        59.74 |          nan    |             23.28 |             94.47 |         5.12 |             70.3  | long               |              -12.58 |                 -3.74 |                -3.11 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.85

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
- Excluded by hard/data filters: **295**
- Event watch (otherwise eligible): **0**
- Final eligible: **705**
- Eligible change vs previous stored run: **-4**

Top exclusion categories:
- liquidity: 238
- price: 185
- market_cap: 166
- price_history: 19
- data_confidence: 12
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| CMBT.BR | 1 |  | 3 |  | 2 | main,pullback |
| FRO | 2 |  | 1 |  | 2 | main,pullback |
| VLO | 5 |  | 2 |  | 2 | main,pullback |
| DHT | 7 |  | 4 |  | 2 | main,pullback |
| SHELL.AS | 9 |  | 9 |  | 2 | main,pullback |
| PBR-A | 18 | 1 | 18 | 2 | 1 | value,quality_value |
| NVDA | 19 | 2 |  | 1 | 1 | value,quality_value |
| MSFT | 148 | 7 | 83 | 6 | 1 | value,quality_value |
| SAP.DE | 264 | 4 | 218 | 4 | 1 | value,quality_value |
| AVGO | 323 | 3 | 120 | 3 | 1 | value,quality_value |
| NOVN.SW | 490 | 8 |  | 9 | 1 | value,quality_value |
| ORCL | 586 | 6 |  | 8 | 1 | value,quality_value |
| NFLX | 639 | 5 |  | 5 | 1 | value,quality_value |
| HPE | 3 |  |  |  | 1 | main |
| MU | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **5** (HPE, MU, REP.MC, SHELL.AS, KIN.BR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (SMTC, SHELL.AS)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | PBR-A | value+pullback | 67.03 | 68.56 | 54.36 | 75.63 | 71.56 | 71.86 | 74.15 |
| 2 | AVGO | value+pullback | 66.35 | 60.81 | 67.55 | 86.96 | 32.82 | 74.47 | 54.01 |
| 3 | BP | pullback | 57.94 | 58.05 | 76.89 | 87.92 | 88.44 | 83.42 | 69.88 |
| 4 | VLO | pullback | 57.80 | 49.73 | 80.29 | 87.05 | 81.50 | 82.59 | 77.80 |
| 5 | FRO | pullback | 57.69 | 55.84 | 78.62 | 91.48 | 81.14 | 81.00 | 79.58 |
| 6 | DHT | pullback | 57.28 | 55.86 | 77.15 | 88.05 | 83.82 | 82.00 | 77.03 |
| 7 | CMBT.BR | pullback | 57.08 | 55.44 | 70.26 | 96.37 | 78.65 | 85.98 | 81.55 |
| 8 | SAP.DE | value+pullback | 56.83 | 81.24 | 53.89 | 34.78 | 46.09 | 45.78 | 56.62 |
| 9 | DAR | pullback | 56.66 | 51.61 | 71.22 | 89.68 | 87.22 | 83.39 | 68.72 |
| 10 | ARGX.BR | pullback | 55.89 | 35.43 | 69.78 | 93.48 | 82.40 | 80.92 | 63.45 |
| 11 | NAT | pullback | 54.95 | 49.54 | 78.15 | 88.03 | 69.09 | 76.52 | 73.95 |
| 12 | HSHP | pullback | 54.56 | 45.51 | 82.86 | 86.70 |  | 79.21 | 74.65 |
| 13 | EQNR | pullback | 54.52 | 56.22 | 77.60 | 77.48 | 85.29 | 74.85 | 70.65 |
| 14 | NETC.CO | pullback | 54.15 | 41.37 | 77.99 | 82.45 | 73.89 | 74.50 | 55.05 |
| 15 | NVDA | value | 54.06 | 60.87 | 45.81 | 83.70 | 80.61 | 75.90 | 74.13 |
| 16 | MSFT | value+pullback | 54.01 | 57.78 | 55.49 | 44.20 | 66.08 | 47.83 | 62.27 |
| 17 | BEN | pullback | 53.20 | 53.62 | 69.11 | 82.54 | 76.62 | 79.40 | 65.07 |
| 18 | SMTC | pullback | 52.63 | 36.96 | 75.79 | 75.93 | 85.68 | 68.61 | 71.25 |
| 19 | BIT | pullback | 52.49 | 47.76 | 81.19 |  |  | 98.46 | 31.44 |
| 20 | BE | pullback | 52.46 | 35.37 | 82.56 | 86.67 | 59.76 | 64.25 | 61.03 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 5 / 5 |
| Top 25 | 25/25 | 23/25 | 23/25 | 21/25 | 0/25 | 72.3 | 16 / 9 |
| Top 50 | 48/50 | 48/50 | 48/50 | 44/50 | 0/50 | 72.7 | 25 / 25 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=1, large_20_100b=3, mega_100b_plus=2
