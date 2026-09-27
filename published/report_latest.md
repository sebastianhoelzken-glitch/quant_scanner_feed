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
- **OTHER:** 70.0/100
- **US:** 82.1/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE       | HPE       | US       |               73.45 |             82.72 |         88.79 |         85.63 |          79.81 |        69.31 |           72.16 |             82.92 |             43.06 |         6.9  |             72.34 | short              |                1.36 |                  0.58 |               nan    |
|      2 | DELL      | DELL      | US       |              314.64 |             81.5  |         85.03 |         84.21 |          78.8  |        65.8  |           72.19 |             83.66 |             29.04 |         7.81 |             72.23 | short              |               -2.11 |                 -0.14 |                -0.26 |
|      3 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.88 |             81.03 |         74.36 |         80.59 |          82.96 |        81.46 |           96.24 |             70.66 |             61.52 |         3.65 |             73.14 | medium             |               -3.16 |                  0.97 |                 0.98 |
|      4 | MU        | MU        | US       |             1074.59 |             81.02 |         79.67 |         71.98 |          84.42 |        82.37 |           95.14 |             83.4  |             63.42 |         8.09 |             73.14 | medium             |                0.25 |                  2.42 |                 1.87 |
|      5 | VLO       | VLO       | US       |               98.01 |             80.64 |         78.77 |         84.39 |          82.5  |        76.92 |           85.94 |             81.99 |             51.9  |         3.55 |             69.68 | swing              |               -5.11 |                  0.67 |                 0.67 |
|      6 | AMC       | AMC       | US       |                2.31 |             80.3  |         81.08 |         84.92 |          79.51 |        78.99 |           86.99 |             79.08 |            nan    |         9.47 |             65.07 | swing              |                4.11 |                  4.28 |                 3.99 |
|      7 | FRO       | FRO       | US       |                9.34 |             79.34 |         78.82 |         80.25 |          79.86 |        76.77 |           91.44 |             66.02 |             51.93 |         5.03 |             73.14 | swing              |               -5.58 |                 -0.01 |                 0.08 |
|      8 | SMTC      | SMTC      | US       |               14.96 |             78.68 |         84.29 |         81.44 |          75.91 |        61.64 |           74.2  |             85.41 |             12.15 |         8.43 |             73.14 | short              |                7.84 |                  0.7  |               nan    |
|      9 | REP.MC    | REP.MC    | EUROPE   |               32.76 |             78.6  |         84.21 |         81.56 |          75.64 |        71.41 |           61.6  |             84.25 |             68.82 |         3.8  |             73.14 | short              |                3.94 |                  1.88 |                 1.49 |
|     10 | PSX       | PSX       | US       |               90.15 |             77.62 |         74.53 |         83.21 |          80.38 |        74.86 |           79.24 |             87.17 |             52.93 |         3.8  |             73.14 | swing              |               -6.24 |                  0.51 |                 0.72 |
|     11 | SHELL.AS  | SHELL.AS  | EUROPE   |              239.93 |             77.45 |         81.7  |         75.79 |          73.7  |        79.12 |           93.31 |             80.96 |             62.38 |         2.45 |             73.14 | short              |                3.3  |                  2.68 |                 2.53 |
|     12 | KIN.BR    | KIN.BR    | EUROPE   |                1.35 |             77.43 |         80.21 |         80.73 |          74.65 |        65.33 |           89.48 |             65.53 |             18.01 |         3.7  |             73.14 | swing              |               -0.32 |                 -0.25 |                -0.2  |
|     13 | ERO       | ERO       | US       |                3.47 |             77.34 |         70.92 |         77.09 |          78.77 |        77.58 |           83.58 |             70.29 |             66.19 |         7.72 |             73.14 | medium             |              nan    |                nan    |               nan    |
|     14 | DHT       | DHT       | US       |                3.09 |             77.16 |         76.96 |         77.9  |          77.36 |        76.43 |           88.59 |             70.55 |             54.79 |         4.45 |             73.14 | swing              |               -4.91 |                  0.15 |                 0    |
|     15 | OMV.VI    | OMV.VI    | EUROPE   |               23.35 |             75.39 |         76.47 |         79.23 |          74.32 |        70.96 |           64.62 |             87.5  |             64.76 |         1.94 |             72.34 | swing              |                4.17 |                  0.97 |                 0.5  |
|     16 | HALO      | HALO      | US       |               11.37 |             75.33 |         78.89 |         77.98 |          72.68 |        68.76 |           85.7  |             50.71 |             43.68 |         6.02 |             72.11 | short              |               -0.78 |                nan    |               nan    |
|     17 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.22 |             75.31 |         57.79 |         70.98 |          79.63 |        82.67 |           72.9  |            nan    |             98.54 |         4.25 |             62.84 | long               |                0.13 |                nan    |               nan    |
|     18 | PBR-A     | PBR-A     | US       |              111.47 |             74.44 |         75.65 |         73.24 |          71.02 |        78.14 |           74.15 |             71.32 |             86.68 |         4.55 |             69.89 | long               |               -0.08 |                  0.19 |                -0.05 |
|     19 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.12 |             74.29 |         74.71 |         75.84 |          73.86 |        73.37 |           70.42 |             75.71 |             71.9  |         5.42 |             73.14 | swing              |                3.15 |                  0.86 |               nan    |
|     20 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.96 |             74.28 |         77.3  |         72.64 |          73.08 |        75.48 |           96.99 |             57.53 |             55.34 |         2.18 |             73.14 | short              |               -1.45 |                  1.51 |                 1.32 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                            | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:--------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | VOLV-B.ST | AB Volvo (publ)                 | EUROPE   |               58.57 |                  89.18 |                    74.28 |                 69.53 |              79.73 |                51.63 |                   48.37 |           49.24 |             62.32 |       0.036 |         nan |       nan |       15.57 |        13.06 |         18.47 |        0.95 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PBR-A     | PBR-A                           | US       |              111.47 |                  69.83 |                    70.82 |                 71.28 |              70.15 |                70.82 |                   29.18 |           74.15 |             71.32 |     nan     |         nan |       nan |      nan    |         4.61 |          4.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                        | EUROPE   |              239.93 |                  57.21 |                    70.22 |                 74.36 |              65.06 |                87.67 |                   12.33 |           93.31 |             80.96 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA      | NVIDIA Corporation              | US       |             4777.92 |                  61.64 |                    70.16 |                 71.58 |              66    |                75.64 |                   24.36 |           81.99 |             80.01 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL      | SHEL                            | US       |              240.17 |                  65.07 |                    69.92 |                 71.32 |              68.79 |                76.76 |                   23.24 |           73.38 |             81.21 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM        | SM                              | US       |                7.09 |                  62.79 |                    69.63 |                 72.24 |              66.62 |                73.36 |                   26.64 |           82.67 |             82.05 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA    | TTE.PA                          | EUROPE   |              176.64 |                  64.74 |                    69.46 |                 70.71 |              68.98 |                76.27 |                   23.73 |           68.69 |             86.42 |     nan     |         nan |       nan |      nan    |         8.7  |         11.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR    | AGS.BR                          | EUROPE   |               15.57 |                  63.23 |                    68.26 |                 69.85 |              65.08 |                78.01 |                   21.99 |           85.72 |             55.09 |     nan     |         nan |       nan |      nan    |         8.67 |          7.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                              | US       |               99.96 |                  55.16 |                    68.03 |                 72.2  |              63.57 |                82.79 |                   17.21 |           86.15 |             89.47 |     nan     |         nan |       nan |      nan    |         8.92 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR                         | EUROPE   |                4.88 |                  55.52 |                    67.95 |                 72.16 |              62.06 |                83.43 |                   16.57 |           96.24 |             70.66 |     nan     |         nan |       nan |      nan    |         9.24 |          6.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NOVO-B.CO | Novo Nordisk A/S                | EUROPE   |              149.52 |                  72.97 |                    67.56 |                 66.17 |              67.41 |                51.05 |                   48.95 |           68.57 |             56.87 |       0.034 |         nan |       nan |        7    |        11.58 |          9.63 |        4.39 |                 nan |              nan |                  11 |                  0.58 |
|            4 | ATNI      | ATN International, Inc.         | US       |                0.39 |                  85.72 |                    67.48 |                 62.86 |              75.75 |                49.3  |                   50.7  |           36.63 |             51.58 |       0.274 |         nan |       nan |        5.24 |        26.5  |          2.78 |        2.63 |                 nan |              nan |                  12 |                  0.63 |
|            5 | LLY       | Eli Lilly and Company           | US       |              927.79 |                  56.8  |                    66.98 |                 69.58 |              60.55 |                69.52 |                   30.48 |           91.52 |             71.42 |       0.01  |         nan |       nan |       26.4  |        25    |         39.69 |        1.17 |                 nan |              nan |                  12 |                  0.63 |
|            6 | HOS       | Hornbeck Offshore Services, Inc | US       |                2.35 |                  72.51 |                    66.9  |                 66.49 |              71.4  |                69.21 |                   30.79 |           53.55 |             67.28 |     nan     |         nan |       nan |        1.98 |        15.17 |         19.5  |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | PAA       | PAA                             | US       |               15.15 |                  54.42 |                    66.87 |                 70.69 |              62.4  |                84.54 |                   15.46 |           86.1  |             79.99 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                         | EUROPE   |               18.96 |                  55.7  |                    66.64 |                 70.32 |              60.71 |                82.5  |                   17.5  |           96.99 |             57.53 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | AVGO      | Broadcom Inc.                   | US       |             1480.63 |                  60.81 |                    66.63 |                 66.47 |              61.28 |                75.96 |                   24.04 |           87.89 |             38.3  |       0.018 |         nan |       nan |       32.9  |        18.2  |         45.58 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT       | DHT                             | US       |                3.09 |                  56.26 |                    66.3  |                 69.75 |              61.6  |                77.99 |                   22.01 |           88.59 |             70.55 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS     | NN.AS                           | EUROPE   |               20.79 |                  62.65 |                    66.25 |                 67.15 |              64.94 |                74.36 |                   25.64 |           72.51 |             64.53 |     nan     |         nan |       nan |      nan    |         9    |         11.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                             | US       |                9.34 |                  56.5  |                    66.22 |                 69.7  |              61.1  |                76.8  |                   23.2  |           91.44 |             66.02 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                  | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:----------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS  | SHELL.AS              | EUROPE   |              239.93 |                  57.21 |                    70.22 |                 74.36 |              65.06 |                87.67 |                   12.33 |           93.31 |             80.96 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM        | SM                    | US       |                7.09 |                  62.79 |                    69.63 |                 72.24 |              66.62 |                73.36 |                   26.64 |           82.67 |             82.05 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                    | US       |               99.96 |                  55.16 |                    68.03 |                 72.2  |              63.57 |                82.79 |                   17.21 |           86.15 |             89.47 |     nan     |         nan |       nan |      nan    |         8.92 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR               | EUROPE   |                4.88 |                  55.52 |                    67.95 |                 72.16 |              62.06 |                83.43 |                   16.57 |           96.24 |             70.66 |     nan     |         nan |       nan |      nan    |         9.24 |          6.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA      | NVIDIA Corporation    | US       |             4777.92 |                  61.64 |                    70.16 |                 71.58 |              66    |                75.64 |                   24.36 |           81.99 |             80.01 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL      | SHEL                  | US       |              240.17 |                  65.07 |                    69.92 |                 71.32 |              68.79 |                76.76 |                   23.24 |           73.38 |             81.21 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A     | PBR-A                 | US       |              111.47 |                  69.83 |                    70.82 |                 71.28 |              70.15 |                70.82 |                   29.18 |           74.15 |             71.32 |     nan     |         nan |       nan |      nan    |         4.61 |          4.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA    | TTE.PA                | EUROPE   |              176.64 |                  64.74 |                    69.46 |                 70.71 |              68.98 |                76.27 |                   23.73 |           68.69 |             86.42 |     nan     |         nan |       nan |      nan    |         8.7  |         11.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA       | PAA                   | US       |               15.15 |                  54.42 |                    66.87 |                 70.69 |              62.4  |                84.54 |                   15.46 |           86.1  |             79.99 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR               | EUROPE   |               18.96 |                  55.7  |                    66.64 |                 70.32 |              60.71 |                82.5  |                   17.5  |           96.99 |             57.53 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR    | AGS.BR                | EUROPE   |               15.57 |                  63.23 |                    68.26 |                 69.85 |              65.08 |                78.01 |                   21.99 |           85.72 |             55.09 |     nan     |         nan |       nan |      nan    |         8.67 |          7.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                   | US       |                3.09 |                  56.26 |                    66.3  |                 69.75 |              61.6  |                77.99 |                   22.01 |           88.59 |             70.55 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                   | US       |                9.34 |                  56.5  |                    66.22 |                 69.7  |              61.1  |                76.8  |                   23.2  |           91.44 |             66.02 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR    | A5G.IR                | EUROPE   |               24.5  |                  55.43 |                    66.02 |                 69.62 |              60.1  |                81.28 |                   18.72 |           96.58 |             55.59 |     nan     |         nan |       nan |      nan    |        11.79 |         12.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU        | MU                    | US       |             1074.59 |                  47.98 |                    63.93 |                 69.62 |              56.96 |                78.17 |                   21.83 |           95.14 |             83.4  |     nan     |         nan |       nan |      nan    |         6.79 |         24.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | LLY       | Eli Lilly and Company | US       |              927.79 |                  56.8  |                    66.98 |                 69.58 |              60.55 |                69.52 |                   30.48 |           91.52 |             71.42 |       0.01  |         nan |       nan |       26.4  |        25    |         39.69 |        1.17 |                 nan |              nan |                  12 |                  0.63 |
|            1 | VOLV-B.ST | AB Volvo (publ)       | EUROPE   |               58.57 |                  89.18 |                    74.28 |                 69.53 |              79.73 |                51.63 |                   48.37 |           49.24 |             62.32 |       0.036 |         nan |       nan |       15.57 |        13.06 |         18.47 |        0.95 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BEN       | BEN                   | US       |               14.75 |                  55.11 |                    65.87 |                 69.28 |              61.85 |                80.02 |                   19.98 |           83.33 |             77.61 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CTSH      | CTSH                  | US       |               22.7  |                  57.96 |                    65.42 |                 68.45 |              61.04 |                69.57 |                   30.43 |           87.02 |             67.81 |     nan     |         nan |       nan |      nan    |         9.05 |         12.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR    | C5H.IR                | EUROPE   |                1.65 |                  51.64 |                    64.12 |                 68.35 |              57.41 |                81.5  |                   18.5  |           98.2  |             55.55 |     nan     |         nan |       nan |      nan    |        10.34 |         10.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO       | US       |               98.01 |                     0.06 |    -0.06 |      0.12 |                  84.21 |                        84.31 |         78.77 |         84.39 |          82.5  |        76.92 |           85.94 |             81.99 |         3.55 |
|               2 | PSX       | PSX       | US       |               90.15 |                     0.07 |    -0.06 |      0.07 |                  81.77 |                        82.79 |         74.53 |         83.21 |          80.38 |        74.86 |           79.24 |             87.17 |         3.8  |
|               3 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.88 |                     0.07 |    -0.05 |      0.06 |                  75.94 |                        81.53 |         74.36 |         80.59 |          82.96 |        81.46 |           96.24 |             70.66 |         3.65 |
|               4 | FRO       | FRO       | US       |                9.34 |                     0.07 |    -0.07 |      0.16 |                  81.39 |                        80.52 |         78.82 |         80.25 |          79.86 |        76.77 |           91.44 |             66.02 |         5.03 |
|               5 | DHT       | DHT       | US       |                3.09 |                     0.06 |    -0.06 |      0.13 |                  83.92 |                        79.84 |         76.96 |         77.9  |          77.36 |        76.43 |           88.59 |             70.55 |         4.45 |
|               6 | DELL      | DELL      | US       |              314.64 |                     0.04 |    -0.01 |      0.19 |                  66.28 |                        79.44 |         85.03 |         84.21 |          78.8  |        65.8  |           72.19 |             83.66 |         7.81 |
|               7 | BP        | BP        | US       |               99.96 |                     0.06 |    -0.01 |      0.04 |                  70.65 |                        78.05 |         73.6  |         71.59 |          70.3  |        75.2  |           86.15 |             89.47 |         4.48 |
|               8 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.2  |                     0.04 |    -0.02 |      0.37 |                  68.63 |                        76.62 |         82.31 |         77.67 |          68.5  |        68.07 |           83.1  |             56.98 |         5.31 |
|               9 | C5H.IR    | C5H.IR    | EUROPE   |                1.65 |                     0.06 |     0.01 |      0.05 |                  66.53 |                        75.44 |         74.97 |         68.14 |          72.07 |        75.49 |           98.2  |             55.55 |         2.67 |
|              10 | NESTE.HE  | NESTE.HE  | EUROPE   |               26.13 |                     0.05 |    -0.02 |      0.09 |                  74.77 |                        75.25 |         76.5  |         73.54 |          69.45 |        61.91 |           62.72 |             88.25 |         4.95 |
|              11 | EQNR      | EQNR      | US       |               87.93 |                     0.08 |    -0.04 |      0.02 |                  69.28 |                        74.99 |         63.49 |         73.27 |          72.22 |        72.09 |           75.3  |             86    |         5.62 |
|              12 | NAT       | NAT       | US       |                1.44 |                     0.06 |    -0.06 |      0.19 |                  83.85 |                        74.87 |         76.28 |         72.83 |          71.17 |        67.31 |           87.9  |             43.83 |         4.61 |
|              13 | PBR-A     | PBR-A     | US       |              111.47 |                     0.05 |    -0.02 |      0.12 |                  74.65 |                        74.55 |         75.65 |         73.24 |          71.02 |        78.14 |           74.15 |             71.32 |         4.55 |
|              14 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.12 |                     0.09 |    -0.09 |      0.11 |                  73.81 |                        74.43 |         74.71 |         75.84 |          73.86 |        73.37 |           70.42 |             75.71 |         5.42 |
|              15 | TEAM      | TEAM      | US       |               41.78 |                     0.04 |    -0.02 |      0.01 |                  68.38 |                        74.39 |         67.75 |         83.16 |          66.6  |        47.58 |           43.36 |             92.56 |         9.48 |
|              16 | DAR       | DAR       | US       |                8.5  |                     0.09 |    -0.06 |     -0    |                  64.43 |                        74.31 |         56.61 |         67.58 |          75.38 |        80.15 |           89.83 |             85.94 |         4.73 |
|              17 | PAA       | PAA       | US       |               15.15 |                     0.06 |    -0.04 |     -0.04 |                  75.96 |                        74.29 |         55.3  |         67.36 |          72.3  |        73.45 |           86.1  |             79.99 |         2.05 |
|              18 | FORTUM.HE | FORTUM.HE | EUROPE   |               21.01 |                     0.05 |    -0.05 |      0.13 |                  83.13 |                        74.13 |         76.39 |         65.43 |          58.62 |        53.16 |           68.55 |             65.05 |         4.61 |
|              19 | ARGX.BR   | ARGX.BR   | EUROPE   |               52.56 |                     0.07 |    -0.03 |     -0.06 |                  68.06 |                        73.99 |         55.59 |         65.6  |          68.98 |        61.79 |           93.06 |             82.45 |         6.12 |
|              20 | DNORD.CO  | DNORD.CO  | EUROPE   |                1.37 |                     0.07 |    -0.06 |      0.04 |                  80.23 |                        73.64 |         65.94 |         71.49 |          67.82 |        60.7  |           81.48 |             63.76 |         4.75 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    493 | CYH      | Community Health Systems, Inc. | US       |                0.36 |             49    |         53.26 |         38.78 |          44.75 |        60.15 |           53.44 |             28.34 |            100    |         8.15 |             82.05 | long               |                9.41 |                  4.7  |                 4.18 |
|    323 | ITRG     | ITRG                           | US       |                0.49 |             56.3  |         47.98 |         56.43 |          56.17 |        62.51 |           57.41 |             61.85 |             78.23 |         8.17 |             68.32 | long               |                0.5  |                  4.55 |                 4.87 |
|    321 | HUT      | HUT                            | US       |               10.49 |             56.33 |         66.03 |         53.47 |          59.18 |        43.8  |           37.27 |             79.14 |             12.2  |         8.54 |             66.84 | short              |              nan    |                  4.52 |               nan    |
|      6 | AMC      | AMC                            | US       |                2.31 |             80.3  |         81.08 |         84.92 |          79.51 |        78.99 |           86.99 |             79.08 |            nan    |         9.47 |             65.07 | swing              |                4.11 |                  4.28 |                 3.99 |
|    557 | ZH       | ZH                             | US       |                0.28 |             44.76 |         72.03 |         53.93 |          35.58 |        26.41 |           17.68 |             25.58 |             24.86 |         7.26 |             73.14 | short              |                5.71 |                  4.18 |                 3.12 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    465 | TEVA     | TEVA    | US       |               40.18 |             50.51 |         65.2  |         55.67 |          45.34 |        37.53 |           18.03 |             25.34 |             41.52 |         4.8  |             72.34 | short              |               -4.5  |                 -3.85 |                -3.87 |
|    489 | CNC      | CNC     | US       |               26.85 |             49.18 |         41.68 |         53.68 |          57.51 |        44.67 |           12.26 |             73.05 |             56.34 |         5.9  |             71.66 | medium             |              -10.04 |                 -3.63 |                -3.11 |
|    671 | PAH3.DE  | PAH3.DE | EUROPE   |                7.89 |             33.38 |         28.79 |         30.05 |          36.71 |        60.09 |          nan    |             23.66 |             94.2  |         5.13 |             70.3  | long               |              -11.97 |                 -3.62 |                -3.02 |
|    221 | HAFN     | HAFN    | US       |                4.2  |             60.28 |         66.26 |         60.15 |          57.48 |        60.41 |           72.59 |             13.57 |             51.51 |         5.62 |             69.68 | short              |               -5.69 |                 -3.3  |                -4.03 |
|    651 | 0JHU.IL  | 0JHU.IL | OTHER    |                8.25 |             36.65 |         22.94 |         31.17 |          42.14 |        73.37 |          nan    |            nan    |            100    |         5.15 |             60    | long               |               -0.95 |                 -3.21 |                -3.31 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
- `ret_63d_rank` vs `sector_score`: r=0.90
- `relative_63d_rank` vs `sector_score`: r=0.87
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
| CMBT.BR | 3 |  | 3 |  | 2 | main,pullback |
| VLO | 5 |  | 1 |  | 2 | main,pullback |
| FRO | 7 |  | 4 |  | 2 | main,pullback |
| PSX | 10 |  | 2 |  | 2 | main,pullback |
| NVDA | 35 | 2 | 25 | 1 | 1 | value,quality_value |
| LLY | 62 | 5 |  | 2 | 1 | value,quality_value |
| VOLV-B.ST | 350 | 1 | 211 | 3 | 1 | value,quality_value |
| AVGO | 401 | 7 | 147 | 5 | 1 | value,quality_value |
| ATNI | 480 | 4 | 329 | 7 | 1 | value,quality_value |
| NOVO-B.CO | 554 | 3 |  | 6 | 1 | value,quality_value |
| HOS | 558 | 6 |  | 4 | 1 | value,quality_value |
| NFLX | 624 | 9 |  | 8 | 1 | value,quality_value |
| HPE | 1 |  |  |  | 1 | main |
| MU | 4 |  |  |  | 1 | main |

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
| 1 | VOLV-B.ST | value+pullback | 68.07 | 89.18 | 69.50 | 49.24 | 62.32 | 51.63 | 55.26 |
| 2 | AVGO | value+pullback | 67.55 | 60.81 | 68.41 | 87.89 | 38.30 | 75.96 | 53.18 |
| 3 | NVDA | value+pullback | 65.58 | 61.64 | 46.65 | 81.99 | 80.01 | 75.64 | 72.48 |
| 4 | ATNI | value+pullback | 60.52 | 85.72 | 57.18 | 36.63 | 51.58 | 49.30 | 49.74 |
| 5 | VLO | pullback | 58.56 | 48.90 | 84.21 | 85.94 | 81.99 | 82.11 | 80.64 |
| 6 | CMBT.BR | pullback | 57.17 | 55.52 | 75.94 | 96.24 | 70.66 | 83.43 | 81.03 |
| 7 | PSX | pullback | 57.03 | 51.18 | 81.77 | 79.24 | 87.17 | 79.93 | 77.62 |
| 8 | DHT | pullback | 56.92 | 56.26 | 83.92 | 88.59 | 70.55 | 77.99 | 77.16 |
| 9 | PAA | pullback | 56.81 | 54.42 | 75.96 | 86.10 | 79.99 | 84.54 | 69.83 |
| 10 | SAP.DE | value+pullback | 56.65 | 76.39 | 48.48 | 41.96 | 52.10 | 50.56 | 57.74 |
| 11 | BP | pullback | 56.09 | 55.16 | 70.65 | 86.15 | 89.47 | 82.79 | 72.59 |
| 12 | FRO | pullback | 56.02 | 56.50 | 81.39 | 91.44 | 66.02 | 76.80 | 79.34 |
| 13 | ARGX.BR | pullback | 55.36 | 35.59 | 68.06 | 93.06 | 82.45 | 80.72 | 63.69 |
| 14 | DAR | pullback | 54.78 | 52.95 | 64.43 | 89.83 | 85.94 | 83.00 | 71.48 |
| 15 | NETC.CO | pullback | 54.04 | 41.66 | 76.30 | 83.09 | 74.89 | 75.06 | 56.22 |
| 16 | C5H.IR | pullback | 53.22 | 51.64 | 66.53 | 98.20 | 55.55 | 81.50 | 73.52 |
| 17 | BEN | pullback | 53.06 | 55.11 | 67.18 | 83.33 | 77.61 | 80.02 | 69.14 |
| 18 | DNORD.CO | pullback | 52.99 | 43.57 | 80.23 | 81.48 | 63.76 | 71.66 | 66.88 |
| 19 | NOKIA.HE | value+pullback | 52.65 | 70.80 | 74.51 | 15.87 | 32.02 | 35.99 | 44.22 |
| 20 | XOM | pullback | 52.37 | 56.67 | 73.96 | 70.07 | 83.87 | 74.89 | 66.03 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 6 / 4 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 73.1 | 13 / 12 |
| Top 50 | 48/50 | 49/50 | 49/50 | 46/50 | 0/50 | 73.0 | 27 / 23 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=2, large_20_100b=4, mega_100b_plus=2
