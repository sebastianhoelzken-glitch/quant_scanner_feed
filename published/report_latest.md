# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-27

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

- **EUROPE:** 77.9/100
- **OTHER:** 72.8/100
- **US:** 82.2/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE       | HPE       | US       |               73.45 |             83.18 |         89.18 |         86.16 |          80.21 |        69.73 |           72.18 |             82.88 |             43.41 |         6.9  |             72.34 | short              |                1.83 |                  0.68 |               nan    |
|      2 | DELL      | DELL      | US       |              314.64 |             81.87 |         85.37 |         84.62 |          79.11 |        66.19 |           72.4  |             83.12 |             29.29 |         7.81 |             72.23 | short              |               -1.75 |                 -0.07 |                -0.21 |
|      3 | MU        | MU        | US       |             1074.59 |             81.43 |         80.03 |         72.48 |          84.82 |        82.82 |           95.16 |             83.37 |             63.98 |         8.09 |             73.14 | medium             |                0.66 |                  2.5  |                 1.93 |
|      4 | VLO       | VLO       | US       |               98.01 |             81.06 |         79.17 |         84.96 |          82.95 |        77.43 |           86.01 |             82.04 |             52.46 |         3.55 |             69.68 | swing              |               -4.68 |                  0.75 |                 0.74 |
|      5 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.88 |             81.02 |         74.36 |         80.59 |          82.95 |        81.45 |           96.23 |             70.63 |             61.52 |         3.65 |             73.14 | medium             |               -3.17 |                  0.97 |                 0.98 |
|      6 | AMC       | AMC       | US       |                2.31 |             80.68 |         81.47 |         85.46 |          79.9  |        79.38 |           86.9  |             79.1  |            nan    |         9.47 |             65.07 | swing              |                4.49 |                  4.36 |                 4.05 |
|      7 | FRO       | FRO       | US       |                9.34 |             79.76 |         79.22 |         80.81 |          80.31 |        77.27 |           91.51 |             66.03 |             52.47 |         5.03 |             73.14 | swing              |               -5.15 |                  0.08 |                 0.14 |
|      8 | SMTC      | SMTC      | US       |               14.96 |             79.1  |         84.66 |         81.94 |          76.26 |        61.96 |           74.07 |             85.44 |             12.37 |         8.43 |             73.14 | short              |                8.26 |                  0.79 |               nan    |
|      9 | REP.MC    | REP.MC    | EUROPE   |               32.76 |             78.56 |         84.19 |         81.54 |          75.59 |        71.36 |           61.47 |             84.21 |             68.82 |         3.8  |             73.14 | short              |                3.91 |                  1.87 |                 1.49 |
|     10 | PSX       | PSX       | US       |               90.15 |             78.09 |         74.92 |         83.74 |          80.81 |        75.36 |           79.36 |             87.07 |             53.49 |         3.8  |             73.14 | swing              |               -5.78 |                  0.6  |                 0.79 |
|     11 | ERO       | ERO       | US       |                3.47 |             77.91 |         71.32 |         77.66 |          79.26 |        78.17 |           83.89 |             70.26 |             66.79 |         7.72 |             73.14 | medium             |              nan    |                nan    |               nan    |
|     12 | DHT       | DHT       | US       |                3.09 |             77.61 |         77.37 |         78.47 |          77.85 |        77    |           88.91 |             70.54 |             55.3  |         4.45 |             73.14 | swing              |               -4.46 |                  0.24 |                 0.07 |
|     13 | KIN.BR    | KIN.BR    | EUROPE   |                1.35 |             77.43 |         80.21 |         80.74 |          74.65 |        65.33 |           89.47 |             65.54 |             18.01 |         3.7  |             73.14 | swing              |               -0.31 |                 -0.25 |                -0.19 |
|     14 | SHELL.AS  | SHELL.AS  | EUROPE   |              239.93 |             77.43 |         81.69 |         75.77 |          73.68 |        79.09 |           93.25 |             80.93 |             62.38 |         2.45 |             73.14 | short              |                3.28 |                  2.67 |                 2.53 |
|     15 | HALO      | HALO      | US       |               11.37 |             75.79 |         79.28 |         78.52 |          73.06 |        69.16 |           85.65 |             50.73 |             44.05 |         6.02 |             72.11 | short              |               -0.32 |                nan    |               nan    |
|     16 | OMV.VI    | OMV.VI    | EUROPE   |               23.35 |             75.39 |         76.46 |         79.22 |          74.31 |        70.96 |           64.62 |             87.47 |             64.76 |         1.94 |             72.34 | swing              |                4.17 |                  0.96 |                 0.5  |
|     17 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.22 |             75.26 |         57.77 |         70.96 |          79.57 |        82.59 |           72.73 |            nan    |             98.54 |         4.25 |             62.84 | long               |                0.08 |                nan    |               nan    |
|     18 | PBR-A     | PBR-A     | US       |              111.47 |             74.93 |         76.06 |         73.8  |          71.49 |        78.66 |           74.32 |             71.37 |             87.16 |         4.55 |             69.89 | long               |                0.4  |                  0.28 |                 0.02 |
|     19 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.12 |             74.28 |         74.71 |         75.84 |          73.86 |        73.36 |           70.41 |             75.67 |             71.9  |         5.42 |             73.14 | swing              |                3.15 |                  0.86 |               nan    |
|     20 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.96 |             74.27 |         77.3  |         72.64 |          73.08 |        75.47 |           96.96 |             57.55 |             55.34 |         2.18 |             73.14 | short              |               -1.46 |                  1.51 |                 1.32 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                    | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | VOLV-B.ST | AB Volvo (publ)         | EUROPE   |               58.57 |                  85.18 |                    71.51 |                 66.96 |              76.57 |                49.65 |                   50.35 |           46.92 |             63.02 |       0.036 |         nan |       nan |       15.57 |        13.06 |         18.47 |        0.95 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PBR-A     | PBR-A                   | US       |              111.47 |                  69.83 |                    70.87 |                 71.35 |              70.18 |                70.92 |                   29.08 |           74.32 |             71.37 |     nan     |         nan |       nan |      nan    |         4.61 |          4.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                | EUROPE   |              239.93 |                  57.21 |                    70.2  |                 74.34 |              65.05 |                87.62 |                   12.38 |           93.25 |             80.93 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA      | NVIDIA Corporation      | US       |             4777.92 |                  61.64 |                    70.15 |                 71.58 |              65.99 |                75.68 |                   24.32 |           81.99 |             79.93 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM        | SM                      | US       |                7.09 |                  63.39 |                    70.06 |                 72.62 |              67.08 |                73.54 |                   26.46 |           83.05 |             82.02 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL      | SHEL                    | US       |              240.17 |                  65.07 |                    69.94 |                 71.34 |              68.78 |                76.79 |                   23.21 |           73.5  |             81.12 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA    | TTE.PA                  | EUROPE   |              176.64 |                  64.74 |                    69.41 |                 70.64 |              68.96 |                76.17 |                   23.83 |           68.51 |             86.38 |     nan     |         nan |       nan |      nan    |         8.7  |         11.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | ATNI      | ATN International, Inc. | US       |                0.39 |                  84.9  |                    68.45 |                 64.2  |              76.34 |                55.96 |                   44.04 |           39.57 |             51.4  |       0.274 |         nan |       nan |        5.24 |        26.5  |          2.78 |        2.63 |                 nan |              nan |                  12 |                  0.63 |
|          nan | AGS.BR    | AGS.BR                  | EUROPE   |               15.57 |                  63.23 |                    68.24 |                 69.83 |              65.07 |                77.98 |                   22.02 |           85.69 |             55.04 |     nan     |         nan |       nan |      nan    |         8.67 |          7.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | STNE      | StoneCo Ltd.            | OTHER    |                1.89 |                  85.75 |                    68.18 |                 61.95 |              74.28 |                55.57 |                   44.43 |           44.86 |             25.39 |       0.635 |         nan |       nan |        1.61 |         4.12 |          3.54 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP        | BP                      | US       |               99.96 |                  55.16 |                    68.01 |                 72.17 |              63.56 |                82.75 |                   17.25 |           86.09 |             89.44 |     nan     |         nan |       nan |      nan    |         8.92 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR                 | EUROPE   |                4.88 |                  55.52 |                    67.94 |                 72.15 |              62.05 |                83.41 |                   16.59 |           96.23 |             70.63 |     nan     |         nan |       nan |      nan    |         9.24 |          6.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NOVO-B.CO | Novo Nordisk A/S        | EUROPE   |              149.52 |                  72.97 |                    67.62 |                 66.24 |              67.48 |                51.24 |                   48.76 |           68.57 |             57.19 |       0.034 |         nan |       nan |        7    |        11.58 |          9.63 |        4.39 |                 nan |              nan |                  11 |                  0.58 |
|          nan | PAA       | PAA                     | US       |               15.15 |                  54.79 |                    67.1  |                 70.88 |              62.67 |                84.58 |                   15.42 |           86.2  |             79.95 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | LLY       | Eli Lilly and Company   | US       |              927.79 |                  56.8  |                    67.04 |                 69.66 |              60.62 |                69.68 |                   30.32 |           91.52 |             71.77 |       0.01  |         nan |       nan |       26.4  |        25    |         39.69 |        1.17 |                 nan |              nan |                  12 |                  0.63 |
|            7 | AVGO      | Broadcom Inc.           | US       |             1480.63 |                  60.81 |                    66.75 |                 66.64 |              61.41 |                76.17 |                   23.83 |           87.89 |             39.2  |       0.018 |         nan |       nan |       32.9  |        18.2  |         45.58 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR   | BIRG.IR                 | EUROPE   |               18.96 |                  55.7  |                    66.64 |                 70.31 |              60.71 |                82.49 |                   17.51 |           96.96 |             57.55 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                     | US       |                9.34 |                  56.93 |                    66.49 |                 69.93 |              61.42 |                76.84 |                   23.16 |           91.51 |             66.03 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                     | US       |                3.09 |                  56.42 |                    66.47 |                 69.92 |              61.75 |                78.15 |                   21.85 |           88.91 |             70.54 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN       | BEN                     | US       |               14.75 |                  55.71 |                    66.32 |                 69.7  |              62.31 |                80.25 |                   19.75 |           83.82 |             77.58 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                  | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:----------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS              | EUROPE   |              239.93 |                  57.21 |                    70.2  |                 74.34 |              65.05 |                87.62 |                   12.38 |           93.25 |             80.93 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                    | US       |                7.09 |                  63.39 |                    70.06 |                 72.62 |              67.08 |                73.54 |                   26.46 |           83.05 |             82.02 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                    | US       |               99.96 |                  55.16 |                    68.01 |                 72.17 |              63.56 |                82.75 |                   17.25 |           86.09 |             89.44 |     nan     |         nan |       nan |      nan    |         8.92 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR               | EUROPE   |                4.88 |                  55.52 |                    67.94 |                 72.15 |              62.05 |                83.41 |                   16.59 |           96.23 |             70.63 |     nan     |         nan |       nan |      nan    |         9.24 |          6.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA     | NVIDIA Corporation    | US       |             4777.92 |                  61.64 |                    70.15 |                 71.58 |              65.99 |                75.68 |                   24.32 |           81.99 |             79.93 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PBR-A    | PBR-A                 | US       |              111.47 |                  69.83 |                    70.87 |                 71.35 |              70.18 |                70.92 |                   29.08 |           74.32 |             71.37 |     nan     |         nan |       nan |      nan    |         4.61 |          4.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                  | US       |              240.17 |                  65.07 |                    69.94 |                 71.34 |              68.78 |                76.79 |                   23.21 |           73.5  |             81.12 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                   | US       |               15.15 |                  54.79 |                    67.1  |                 70.88 |              62.67 |                84.58 |                   15.42 |           86.2  |             79.95 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                | EUROPE   |              176.64 |                  64.74 |                    69.41 |                 70.64 |              68.96 |                76.17 |                   23.83 |           68.51 |             86.38 |     nan     |         nan |       nan |      nan    |         8.7  |         11.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR               | EUROPE   |               18.96 |                  55.7  |                    66.64 |                 70.31 |              60.71 |                82.49 |                   17.51 |           96.96 |             57.55 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                   | US       |                9.34 |                  56.93 |                    66.49 |                 69.93 |              61.42 |                76.84 |                   23.16 |           91.51 |             66.03 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                   | US       |                3.09 |                  56.42 |                    66.47 |                 69.92 |              61.75 |                78.15 |                   21.85 |           88.91 |             70.54 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                | EUROPE   |               15.57 |                  63.23 |                    68.24 |                 69.83 |              65.07 |                77.98 |                   22.02 |           85.69 |             55.04 |     nan     |         nan |       nan |      nan    |         8.67 |          7.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                   | US       |               14.75 |                  55.71 |                    66.32 |                 69.7  |              62.31 |                80.25 |                   19.75 |           83.82 |             77.58 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | LLY      | Eli Lilly and Company | US       |              927.79 |                  56.8  |                    67.04 |                 69.66 |              60.62 |                69.68 |                   30.32 |           91.52 |             71.77 |       0.01  |         nan |       nan |       26.4  |        25    |         39.69 |        1.17 |                 nan |              nan |                  12 |                  0.63 |
|          nan | MU       | MU                    | US       |             1074.59 |                  47.98 |                    63.93 |                 69.62 |              56.96 |                78.17 |                   21.83 |           95.16 |             83.37 |     nan     |         nan |       nan |      nan    |         6.79 |         24.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                | EUROPE   |               24.5  |                  55.43 |                    66.01 |                 69.6  |              60.08 |                81.25 |                   18.75 |           96.57 |             55.51 |     nan     |         nan |       nan |      nan    |        11.79 |         12.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CTSH     | CTSH                  | US       |               22.7  |                  57.96 |                    65.47 |                 68.51 |              61.06 |                69.68 |                   30.32 |           87.23 |             67.81 |     nan     |         nan |       nan |      nan    |         9.05 |         12.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR                | EUROPE   |                1.65 |                  51.64 |                    64.11 |                 68.33 |              57.4  |                81.47 |                   18.53 |           98.19 |             55.47 |     nan     |         nan |       nan |      nan    |        10.34 |         10.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                   | US       |               98.01 |                  48.9  |                    63.5  |                 68.14 |              58.2  |                82.16 |                   17.84 |           86.01 |             82.04 |     nan     |         nan |       nan |      nan    |        10.18 |         16.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO       | US       |               98.01 |                     0.06 |    -0.06 |      0.12 |                  84.21 |                        84.62 |         79.17 |         84.96 |          82.95 |        77.43 |           86.01 |             82.04 |         3.55 |
|               2 | PSX       | PSX       | US       |               90.15 |                     0.07 |    -0.06 |      0.07 |                  81.77 |                        83.07 |         74.92 |         83.74 |          80.81 |        75.36 |           79.36 |             87.07 |         3.8  |
|               3 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.88 |                     0.07 |    -0.05 |      0.06 |                  75.94 |                        81.52 |         74.36 |         80.59 |          82.95 |        81.45 |           96.23 |             70.63 |         3.65 |
|               4 | FRO       | FRO       | US       |                9.34 |                     0.07 |    -0.07 |      0.16 |                  81.39 |                        80.82 |         79.22 |         80.81 |          80.31 |        77.27 |           91.51 |             66.03 |         5.03 |
|               5 | DHT       | DHT       | US       |                3.09 |                     0.06 |    -0.06 |      0.13 |                  83.92 |                        80.19 |         77.37 |         78.47 |          77.85 |        77    |           88.91 |             70.54 |         4.45 |
|               6 | DELL      | DELL      | US       |              314.64 |                     0.04 |    -0.01 |      0.19 |                  66.28 |                        79.57 |         85.37 |         84.62 |          79.11 |        66.19 |           72.4  |             83.12 |         7.81 |
|               7 | BP        | BP        | US       |               99.96 |                     0.06 |    -0.01 |      0.04 |                  70.65 |                        78.21 |         73.96 |         72.09 |          70.67 |        75.6  |           86.09 |             89.44 |         4.48 |
|               8 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.2  |                     0.04 |    -0.02 |      0.37 |                  68.63 |                        76.63 |         82.33 |         77.69 |          68.52 |        68.06 |           83.05 |             57.07 |         5.31 |
|               9 | C5H.IR    | C5H.IR    | EUROPE   |                1.65 |                     0.06 |     0.01 |      0.05 |                  66.53 |                        75.42 |         74.96 |         68.11 |          72.05 |        75.47 |           98.19 |             55.47 |         2.67 |
|              10 | EQNR      | EQNR      | US       |               87.93 |                     0.08 |    -0.04 |      0.02 |                  69.28 |                        75.26 |         63.88 |         73.81 |          72.64 |        72.57 |           75.36 |             85.97 |         5.62 |
|              11 | NESTE.HE  | NESTE.HE  | EUROPE   |               26.13 |                     0.05 |    -0.02 |      0.09 |                  74.77 |                        75.22 |         76.49 |         73.53 |          69.42 |        61.87 |           62.65 |             88.21 |         4.95 |
|              12 | NAT       | NAT       | US       |                1.44 |                     0.06 |    -0.06 |      0.19 |                  83.85 |                        75.12 |         76.69 |         73.4  |          71.63 |        67.82 |           88.1  |             43.88 |         4.61 |
|              13 | PBR-A     | PBR-A     | US       |              111.47 |                     0.05 |    -0.02 |      0.12 |                  74.65 |                        74.8  |         76.06 |         73.8  |          71.49 |        78.66 |           74.32 |             71.37 |         4.55 |
|              14 | TEAM      | TEAM      | US       |               41.78 |                     0.04 |    -0.02 |      0.01 |                  68.38 |                        74.61 |         68.12 |         83.66 |          66.93 |        47.9  |           43.22 |             92.49 |         9.48 |
|              15 | PAA       | PAA       | US       |               15.15 |                     0.06 |    -0.04 |     -0.04 |                  75.96 |                        74.57 |         55.69 |         67.89 |          72.71 |        73.88 |           86.2  |             79.95 |         2.05 |
|              16 | DAR       | DAR       | US       |                8.5  |                     0.09 |    -0.06 |     -0    |                  64.43 |                        74.51 |         56.96 |         68.07 |          75.72 |        80.5  |           89.6  |             85.9  |         4.73 |
|              17 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.12 |                     0.09 |    -0.09 |      0.11 |                  73.81 |                        74.42 |         74.71 |         75.84 |          73.86 |        73.36 |           70.41 |             75.67 |         5.42 |
|              18 | FORTUM.HE | FORTUM.HE | EUROPE   |               21.01 |                     0.05 |    -0.05 |      0.13 |                  83.13 |                        74.12 |         76.39 |         65.43 |          58.6  |        53.11 |           68.39 |             65.17 |         4.61 |
|              19 | ARGX.BR   | ARGX.BR   | EUROPE   |               52.56 |                     0.07 |    -0.03 |     -0.06 |                  68.06 |                        73.98 |         55.58 |         65.59 |          68.97 |        61.79 |           93.05 |             82.42 |         6.12 |
|              20 | SHEL      | SHEL      | US       |              240.17 |                     0.03 |     0.01 |      0.06 |                  52.79 |                        73.78 |         77.98 |         74.33 |          69.26 |        72.8  |           73.5  |             81.12 |         2.96 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    492 | CYH      | Community Health Systems, Inc. | US       |                0.36 |             49.32 |         53.6  |         39.23 |          45.05 |        60.44 |           53.44 |             28.12 |            100    |         8.15 |             82.05 | long               |                9.73 |                  4.77 |                 4.23 |
|    314 | HUT      | HUT                            | US       |               10.49 |             56.84 |         66.44 |         54.04 |          59.65 |        44.31 |           37.43 |             79.2  |             12.63 |         8.54 |             66.84 | short              |              nan    |                  4.63 |               nan    |
|    329 | ITRG     | ITRG                           | OTHER    |                0.49 |             56.2  |         47.73 |         56.19 |          56.21 |        63.18 |           56.54 |             61.88 |             83.1  |         8.17 |             68.32 | long               |                0.4  |                  4.53 |                 4.86 |
|      6 | AMC      | AMC                            | US       |                2.31 |             80.68 |         81.47 |         85.46 |          79.9  |        79.38 |           86.9  |             79.1  |            nan    |         9.47 |             65.07 | swing              |                4.49 |                  4.36 |                 4.05 |
|    553 | ZH       | ZH                             | US       |                0.28 |             45.15 |         72.4  |         54.41 |          35.89 |        26.66 |           17.54 |             25.55 |             24.86 |         7.26 |             73.14 | short              |                6.1  |                  4.26 |                 3.17 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    464 | TEVA     | TEVA    | US       |               40.18 |             50.95 |         65.57 |         56.19 |          45.7  |        37.9  |           17.91 |             25.37 |             41.93 |         4.8  |             72.34 | short              |               -4.06 |                 -3.76 |                -3.81 |
|    671 | PAH3.DE  | PAH3.DE | EUROPE   |                7.89 |             33.37 |         28.78 |         30.04 |          36.71 |        60.08 |          nan    |             23.66 |             94.2  |         5.13 |             70.3  | long               |              -11.98 |                 -3.62 |                -3.02 |
|    486 | CNC      | CNC     | US       |               26.85 |             49.64 |         42.05 |         54.19 |          57.89 |        45.09 |           12.21 |             73.01 |             56.84 |         5.9  |             71.66 | medium             |               -9.58 |                 -3.54 |                -3.04 |
|    216 | HAFN     | HAFN    | US       |                4.2  |             60.8  |         66.65 |         60.7  |          57.92 |        60.91 |           72.8  |             13.57 |             51.9  |         5.62 |             69.68 | short              |               -5.17 |                 -3.2  |                -3.95 |
|    632 | PIRC.MI  | PIRC.MI | EUROPE   |                7.03 |             39.24 |         49.49 |         42.37 |          36.1  |        35.34 |           18.11 |             17.28 |             55.93 |         2.11 |             71.32 | short              |               -4.83 |                 -3.17 |                -2.99 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
- `ret_63d_rank` vs `sector_score`: r=0.88
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
- Excluded by hard/data filters: **297**
- Event watch (otherwise eligible): **0**
- Final eligible: **703**
- Eligible change vs previous stored run: **-6**

Top exclusion categories:
- liquidity: 235
- price: 186
- market_cap: 166
- price_history: 21
- data_confidence: 15
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| DELL | 2 |  | 6 |  | 2 | main,pullback |
| VLO | 4 |  | 1 |  | 2 | main,pullback |
| CMBT.BR | 5 |  | 3 |  | 2 | main,pullback |
| FRO | 7 |  | 4 |  | 2 | main,pullback |
| PSX | 10 |  | 2 |  | 2 | main,pullback |
| NVDA | 40 | 2 | 26 | 1 | 1 | value,quality_value |
| LLY | 58 | 6 |  | 2 | 1 | value,quality_value |
| VOLV-B.ST | 374 | 1 | 216 | 3 | 1 | value,quality_value |
| AVGO | 400 | 7 | 146 | 4 | 1 | value,quality_value |
| ATNI | 470 | 3 | 313 | 7 | 1 | value,quality_value |
| NOVO-B.CO | 554 | 5 |  | 5 | 1 | value,quality_value |
| HOS | 572 | 8 |  | 6 | 1 | value,quality_value |
| STNE | 651 | 4 | 368 | 9 | 1 | value,quality_value |
| HPE | 1 |  |  |  | 1 | main |
| MU | 3 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **4** (MU, AMC, SMTC, REP.MC)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | AVGO | value+pullback | 67.68 | 60.81 | 68.41 | 87.89 | 39.20 | 76.17 | 53.35 |
| 2 | VOLV-B.ST | value+pullback | 66.20 | 85.18 | 69.50 | 46.92 | 63.02 | 49.65 | 54.78 |
| 3 | NVDA | value+pullback | 65.58 | 61.64 | 46.65 | 81.99 | 79.93 | 75.68 | 72.47 |
| 4 | ATNI | value+pullback | 62.03 | 84.90 | 57.18 | 39.57 | 51.40 | 55.96 | 50.65 |
| 5 | VLO | pullback | 58.59 | 48.90 | 84.21 | 86.01 | 82.04 | 82.16 | 81.06 |
| 6 | STNE | value+pullback | 58.12 | 85.75 | 48.05 | 44.86 | 25.39 | 55.57 | 36.81 |
| 7 | CMBT.BR | pullback | 57.16 | 55.52 | 75.94 | 96.23 | 70.63 | 83.41 | 81.02 |
| 8 | PSX | pullback | 57.05 | 51.18 | 81.77 | 79.36 | 87.07 | 79.96 | 78.09 |
| 9 | DHT | pullback | 57.00 | 56.42 | 83.92 | 88.91 | 70.54 | 78.15 | 77.61 |
| 10 | PAA | pullback | 56.83 | 54.79 | 75.96 | 86.20 | 79.95 | 84.58 | 70.30 |
| 11 | BP | pullback | 56.07 | 55.16 | 70.65 | 86.09 | 89.44 | 82.75 | 73.03 |
| 12 | FRO | pullback | 56.05 | 56.93 | 81.39 | 91.51 | 66.03 | 76.84 | 79.76 |
| 13 | ARGX.BR | pullback | 55.35 | 35.59 | 68.06 | 93.05 | 82.42 | 80.71 | 63.69 |
| 14 | DAR | pullback | 54.71 | 53.46 | 64.43 | 89.60 | 85.90 | 82.87 | 71.90 |
| 15 | SAP.DE | value+pullback | 54.61 | 70.37 | 48.48 | 42.49 | 52.77 | 48.65 | 57.38 |
| 16 | NETC.CO | pullback | 54.00 | 41.66 | 76.30 | 82.96 | 74.86 | 74.98 | 56.20 |
| 17 | C5H.IR | pullback | 53.20 | 51.64 | 66.53 | 98.19 | 55.47 | 81.47 | 73.50 |
| 18 | BEN | pullback | 53.17 | 55.71 | 67.18 | 83.82 | 77.58 | 80.25 | 69.73 |
| 19 | DNORD.CO | pullback | 52.95 | 43.57 | 80.23 | 81.35 | 63.70 | 71.57 | 66.86 |
| 20 | XOM | pullback | 52.35 | 56.67 | 73.96 | 70.01 | 83.84 | 74.85 | 66.48 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 6 / 4 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 73.1 | 14 / 11 |
| Top 50 | 48/50 | 49/50 | 49/50 | 46/50 | 0/50 | 72.7 | 28 / 22 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=2, large_20_100b=4, mega_100b_plus=2
