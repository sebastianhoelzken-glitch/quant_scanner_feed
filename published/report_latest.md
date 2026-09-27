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
- **OTHER:** 72.0/100
- **US:** 82.1/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE       | HPE       | US       |               73.45 |             81.82 |         88.01 |         84.58 |          79.06 |        68.58 |           72.02 |             82.98 |             42.87 |         6.9  |             72.34 | short              |                0.46 |                  0.4  |               nan    |
|      2 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.88 |             81.05 |         74.37 |         80.62 |          82.99 |        81.47 |           96.24 |             70.8  |             61.52 |         3.65 |             73.14 | medium             |               -3.14 |                  0.98 |                 0.99 |
|      3 | DELL      | DELL      | US       |              314.64 |             80.58 |         84.23 |         83.15 |          78.02 |        65.06 |           71.88 |             83.72 |             29.07 |         7.81 |             72.23 | short              |               -3.03 |                 -0.33 |                -0.4  |
|      4 | MU        | MU        | US       |             1074.59 |             80.28 |         78.9  |         70.94 |          83.68 |        81.66 |           95.09 |             83.49 |             63.16 |         8.09 |             73.14 | medium             |               -0.49 |                  2.27 |                 1.76 |
|      5 | VLO       | VLO       | US       |               98.01 |             79.86 |         77.99 |         83.33 |          81.73 |        76.16 |           85.77 |             82.03 |             51.64 |         3.55 |             69.68 | swing              |               -5.89 |                  0.51 |                 0.56 |
|      6 | AMC       | AMC       | US       |                2.31 |             79.44 |         80.28 |         83.8  |          78.61 |        77.92 |           86.61 |             79.1  |            nan    |         9.47 |             65.07 | swing              |                3.25 |                  4.11 |                 3.86 |
|      7 | REP.MC    | REP.MC    | EUROPE   |               32.76 |             78.61 |         84.21 |         81.57 |          75.65 |        71.42 |           61.6  |             84.33 |             68.82 |         3.8  |             73.14 | short              |                3.96 |                  1.88 |                 1.49 |
|      8 | FRO       | FRO       | US       |                9.34 |             78.56 |         78.03 |         79.19 |          79.09 |        76.01 |           91.25 |             66.08 |             51.68 |         5.03 |             73.14 | swing              |               -6.36 |                 -0.16 |                -0.04 |
|      9 | SMTC      | SMTC      | US       |               14.96 |             77.79 |         83.51 |         80.4  |          75.18 |        60.96 |           74.11 |             85.47 |             12.06 |         8.43 |             73.14 | short              |                6.95 |                  0.52 |               nan    |
|     10 | SHELL.AS  | SHELL.AS  | EUROPE   |              239.93 |             77.46 |         81.7  |         75.8  |          73.71 |        79.12 |           93.31 |             81.02 |             62.38 |         2.45 |             73.14 | short              |                3.31 |                  2.68 |                 2.53 |
|     11 | KIN.BR    | KIN.BR    | EUROPE   |                1.35 |             77.44 |         80.21 |         80.74 |          74.66 |        65.34 |           89.48 |             65.59 |             18.01 |         3.7  |             73.14 | swing              |               -0.31 |                 -0.25 |                -0.19 |
|     12 | PSX       | PSX       | US       |               90.15 |             76.85 |         73.74 |         82.15 |          79.6  |        74.1  |           79.08 |             87.19 |             52.67 |         3.8  |             73.14 | swing              |               -7.01 |                  0.36 |                 0.61 |
|     13 | ERO       | ERO       | US       |                3.47 |             76.39 |         70.12 |         76.01 |          77.96 |        76.78 |           83.27 |             70.32 |             66.01 |         7.72 |             73.14 | medium             |              nan    |                nan    |               nan    |
|     14 | DHT       | DHT       | US       |                3.09 |             76.35 |         76.16 |         76.82 |          76.54 |        75.61 |           88.3  |             70.56 |             54.51 |         4.45 |             73.14 | swing              |               -5.72 |                 -0.01 |                -0.12 |
|     15 | OMV.VI    | OMV.VI    | EUROPE   |               23.35 |             75.4  |         76.48 |         79.24 |          74.33 |        70.97 |           64.62 |             87.59 |             64.76 |         1.94 |             72.34 | swing              |                4.19 |                  0.97 |                 0.5  |
|     16 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.22 |             75.3  |         57.79 |         70.98 |          79.63 |        82.66 |           72.9  |            nan    |             98.54 |         4.25 |             62.84 | long               |                0.12 |                nan    |               nan    |
|     17 | HALO      | HALO      | US       |               11.37 |             74.41 |         78.11 |         76.91 |          71.92 |        68.06 |           85.74 |             50.63 |             43.37 |         6.02 |             72.11 | short              |               -1.7  |                nan    |               nan    |
|     18 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.12 |             74.29 |         74.71 |         75.84 |          73.86 |        73.37 |           70.42 |             75.74 |             71.9  |         5.42 |             73.14 | swing              |                3.15 |                  0.86 |               nan    |
|     19 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.96 |             74.27 |         77.3  |         72.64 |          73.08 |        75.47 |           96.99 |             57.53 |             55.34 |         2.18 |             73.14 | short              |               -1.46 |                  1.51 |                 1.32 |
|     20 | DFDS.CO   | DFDS.CO   | EUROPE   |                1.2  |             73.74 |         79.65 |         77.39 |          70.08 |        63.53 |           61.74 |             64.68 |             52.53 |         6.25 |             69.68 | short              |              nan    |                 -0.09 |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                            | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:--------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | VOLV-B.ST | AB Volvo (publ)                 | EUROPE   |               58.57 |                  89.18 |                    74.19 |                 69.4  |              79.63 |                51.48 |                   48.52 |           49.24 |             61.6  |       0.036 |         nan |       nan |       15.57 |        13.06 |         18.47 |        0.95 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PBR-A     | PBR-A                           | US       |              111.47 |                  69.83 |                    70.78 |                 71.23 |              70.14 |                70.73 |                   29.27 |           73.98 |             71.33 |     nan     |         nan |       nan |      nan    |         4.61 |          4.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                        | EUROPE   |              239.93 |                  57.21 |                    70.23 |                 74.38 |              65.07 |                87.68 |                   12.32 |           93.31 |             81.02 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA      | NVIDIA Corporation              | US       |             4777.92 |                  61.64 |                    70.22 |                 71.69 |              65.97 |                75.68 |                   24.32 |           82.61 |             79.68 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL      | SHEL                            | US       |              240.17 |                  65.07 |                    69.88 |                 71.26 |              68.77 |                76.66 |                   23.34 |           73.15 |             81.27 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NOVO-B.CO | Novo Nordisk A/S                | EUROPE   |              149.52 |                  76.92 |                    69.84 |                 67.96 |              70.56 |                52.84 |                   47.16 |           67.67 |             56.67 |       0.034 |         nan |       nan |        7    |        11.58 |          9.63 |        4.39 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SM        | SM                              | US       |                7.09 |                  62.84 |                    69.58 |                 72.16 |              66.64 |                73.21 |                   26.79 |           82.3  |             82.13 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA    | TTE.PA                          | EUROPE   |              176.64 |                  64.74 |                    69.47 |                 70.71 |              68.98 |                76.27 |                   23.73 |           68.69 |             86.44 |     nan     |         nan |       nan |      nan    |         8.7  |         11.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR    | AGS.BR                          | EUROPE   |               15.57 |                  63.23 |                    68.26 |                 69.85 |              65.08 |                78.02 |                   21.98 |           85.72 |             55.11 |     nan     |         nan |       nan |      nan    |         8.67 |          7.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                              | US       |               99.96 |                  55.16 |                    68.02 |                 72.18 |              63.56 |                82.76 |                   17.24 |           86.07 |             89.5  |     nan     |         nan |       nan |      nan    |         8.92 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR                         | EUROPE   |                4.88 |                  55.52 |                    67.97 |                 72.18 |              62.08 |                83.47 |                   16.53 |           96.24 |             70.8  |     nan     |         nan |       nan |      nan    |         9.24 |          6.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA       | PAA                             | US       |               15.15 |                  54.5  |                    66.91 |                 70.73 |              62.46 |                84.54 |                   15.46 |           86.04 |             80.07 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | HOS       | Hornbeck Offshore Services, Inc | US       |                2.35 |                  72.51 |                    66.75 |                 66.29 |              71.24 |                68.93 |                   31.07 |           53.55 |             66.21 |     nan     |         nan |       nan |        1.98 |        15.17 |         19.5  |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | BIRG.IR   | BIRG.IR                         | EUROPE   |               18.96 |                  55.7  |                    66.64 |                 70.32 |              60.71 |                82.5  |                   17.5  |           96.99 |             57.53 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | AVGO      | Broadcom Inc.                   | US       |             1480.63 |                  60.81 |                    66.38 |                 66.13 |              61.02 |                75.57 |                   24.43 |           87.89 |             36.41 |       0.018 |         nan |       nan |       32.9  |        18.2  |         45.58 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | NN.AS     | NN.AS                           | EUROPE   |               20.79 |                  62.65 |                    66.26 |                 67.16 |              64.95 |                74.38 |                   25.62 |           72.51 |             64.6  |     nan     |         nan |       nan |      nan    |         9    |         11.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                             | US       |                9.34 |                  56.59 |                    66.24 |                 69.7  |              61.16 |                76.73 |                   23.27 |           91.25 |             66.08 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                             | US       |                3.09 |                  56.21 |                    66.2  |                 69.63 |              61.54 |                77.85 |                   22.15 |           88.3  |             70.56 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR    | A5G.IR                          | EUROPE   |               24.5  |                  55.43 |                    66.03 |                 69.62 |              60.1  |                81.29 |                   18.71 |           96.58 |             55.61 |     nan     |         nan |       nan |      nan    |        11.79 |         12.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN       | BEN                             | US       |               14.75 |                  55.21 |                    65.8  |                 69.15 |              61.88 |                79.76 |                   20.24 |           82.78 |             77.67 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name               | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS  | SHELL.AS           | EUROPE   |              239.93 |                  57.21 |                    70.23 |                 74.38 |              65.07 |                87.68 |                   12.32 |           93.31 |             81.02 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR            | EUROPE   |                4.88 |                  55.52 |                    67.97 |                 72.18 |              62.08 |                83.47 |                   16.53 |           96.24 |             70.8  |     nan     |         nan |       nan |      nan    |         9.24 |          6.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                 | US       |               99.96 |                  55.16 |                    68.02 |                 72.18 |              63.56 |                82.76 |                   17.24 |           86.07 |             89.5  |     nan     |         nan |       nan |      nan    |         8.92 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM        | SM                 | US       |                7.09 |                  62.84 |                    69.58 |                 72.16 |              66.64 |                73.21 |                   26.79 |           82.3  |             82.13 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA      | NVIDIA Corporation | US       |             4777.92 |                  61.64 |                    70.22 |                 71.69 |              65.97 |                75.68 |                   24.32 |           82.61 |             79.68 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL      | SHEL               | US       |              240.17 |                  65.07 |                    69.88 |                 71.26 |              68.77 |                76.66 |                   23.34 |           73.15 |             81.27 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A     | PBR-A              | US       |              111.47 |                  69.83 |                    70.78 |                 71.23 |              70.14 |                70.73 |                   29.27 |           73.98 |             71.33 |     nan     |         nan |       nan |      nan    |         4.61 |          4.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA       | PAA                | US       |               15.15 |                  54.5  |                    66.91 |                 70.73 |              62.46 |                84.54 |                   15.46 |           86.04 |             80.07 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA    | TTE.PA             | EUROPE   |              176.64 |                  64.74 |                    69.47 |                 70.71 |              68.98 |                76.27 |                   23.73 |           68.69 |             86.44 |     nan     |         nan |       nan |      nan    |         8.7  |         11.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR            | EUROPE   |               18.96 |                  55.7  |                    66.64 |                 70.32 |              60.71 |                82.5  |                   17.5  |           96.99 |             57.53 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR    | AGS.BR             | EUROPE   |               15.57 |                  63.23 |                    68.26 |                 69.85 |              65.08 |                78.02 |                   21.98 |           85.72 |             55.11 |     nan     |         nan |       nan |      nan    |         8.67 |          7.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                | US       |                9.34 |                  56.59 |                    66.24 |                 69.7  |              61.16 |                76.73 |                   23.27 |           91.25 |             66.08 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                | US       |                3.09 |                  56.21 |                    66.2  |                 69.63 |              61.54 |                77.85 |                   22.15 |           88.3  |             70.56 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR    | A5G.IR             | EUROPE   |               24.5  |                  55.43 |                    66.03 |                 69.62 |              60.1  |                81.29 |                   18.71 |           96.58 |             55.61 |     nan     |         nan |       nan |      nan    |        11.79 |         12.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU        | MU                 | US       |             1074.59 |                  47.98 |                    63.93 |                 69.61 |              56.97 |                78.17 |                   21.83 |           95.09 |             83.49 |     nan     |         nan |       nan |      nan    |         6.79 |         24.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | VOLV-B.ST | AB Volvo (publ)    | EUROPE   |               58.57 |                  89.18 |                    74.19 |                 69.4  |              79.63 |                51.48 |                   48.52 |           49.24 |             61.6  |       0.036 |         nan |       nan |       15.57 |        13.06 |         18.47 |        0.95 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BEN       | BEN                | US       |               14.75 |                  55.21 |                    65.8  |                 69.15 |              61.88 |                79.76 |                   20.24 |           82.78 |             77.67 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR    | C5H.IR             | EUROPE   |                1.65 |                  51.64 |                    64.12 |                 68.35 |              57.41 |                81.51 |                   18.49 |           98.2  |             55.57 |     nan     |         nan |       nan |      nan    |        10.34 |         10.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CTSH      | CTSH               | US       |               22.7  |                  57.96 |                    65.33 |                 68.32 |              61.01 |                69.37 |                   30.63 |           86.59 |             67.86 |     nan     |         nan |       nan |      nan    |         9.05 |         12.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO       | VLO                | US       |               98.01 |                  48.9  |                    63.44 |                 68.06 |              58.18 |                82.04 |                   17.96 |           85.77 |             82.03 |     nan     |         nan |       nan |      nan    |        10.18 |         16.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO       | US       |               98.01 |                     0.06 |    -0.06 |      0.12 |                  84.21 |                        83.76 |         77.99 |         83.33 |          81.73 |        76.16 |           85.77 |             82.03 |         3.55 |
|               2 | PSX       | PSX       | US       |               90.15 |                     0.07 |    -0.06 |      0.07 |                  81.77 |                        82.23 |         73.74 |         82.15 |          79.6  |        74.1  |           79.08 |             87.19 |         3.8  |
|               3 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.88 |                     0.07 |    -0.05 |      0.06 |                  75.94 |                        81.57 |         74.37 |         80.62 |          82.99 |        81.47 |           96.24 |             70.8  |         3.65 |
|               4 | FRO       | FRO       | US       |                9.34 |                     0.07 |    -0.07 |      0.16 |                  81.39 |                        79.97 |         78.03 |         79.19 |          79.09 |        76.01 |           91.25 |             66.08 |         5.03 |
|               5 | DHT       | DHT       | US       |                3.09 |                     0.06 |    -0.06 |      0.13 |                  83.92 |                        79.24 |         76.16 |         76.82 |          76.54 |        75.61 |           88.3  |             70.56 |         4.45 |
|               6 | DELL      | DELL      | US       |              314.64 |                     0.04 |    -0.01 |      0.19 |                  66.28 |                        78.99 |         84.23 |         83.15 |          78.02 |        65.06 |           71.88 |             83.72 |         7.81 |
|               7 | BP        | BP        | US       |               99.96 |                     0.06 |    -0.01 |      0.04 |                  70.65 |                        77.65 |         72.82 |         70.54 |          69.55 |        74.5  |           86.07 |             89.5  |         4.48 |
|               8 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.2  |                     0.04 |    -0.02 |      0.37 |                  68.63 |                        76.62 |         82.32 |         77.67 |          68.51 |        68.07 |           83.1  |             57    |         5.31 |
|               9 | C5H.IR    | C5H.IR    | EUROPE   |                1.65 |                     0.06 |     0.01 |      0.05 |                  66.53 |                        75.45 |         74.98 |         68.15 |          72.08 |        75.49 |           98.2  |             55.57 |         2.67 |
|              10 | NESTE.HE  | NESTE.HE  | EUROPE   |               26.13 |                     0.05 |    -0.02 |      0.09 |                  74.77 |                        75.24 |         76.49 |         73.52 |          69.44 |        61.9  |           62.72 |             88.23 |         4.95 |
|              11 | EQNR      | EQNR      | US       |               87.93 |                     0.08 |    -0.04 |      0.02 |                  69.28 |                        74.46 |         62.72 |         72.22 |          71.47 |        71.38 |           75.25 |             86.02 |         5.62 |
|              12 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.12 |                     0.09 |    -0.09 |      0.11 |                  73.81 |                        74.44 |         74.71 |         75.84 |          73.86 |        73.37 |           70.42 |             75.74 |         5.42 |
|              13 | NAT       | NAT       | US       |                1.44 |                     0.06 |    -0.06 |      0.19 |                  83.85 |                        74.41 |         75.47 |         71.75 |          70.38 |        66.58 |           87.66 |             43.74 |         4.61 |
|              14 | FORTUM.HE | FORTUM.HE | EUROPE   |               21.01 |                     0.05 |    -0.05 |      0.13 |                  83.13 |                        74.14 |         76.39 |         65.43 |          58.62 |        53.16 |           68.55 |             65.08 |         4.61 |
|              15 | PBR-A     | PBR-A     | US       |              111.47 |                     0.05 |    -0.02 |      0.12 |                  74.65 |                        74.12 |         74.86 |         72.17 |          70.24 |        77.39 |           73.98 |             71.33 |         4.55 |
|              16 | ARGX.BR   | ARGX.BR   | EUROPE   |               52.56 |                     0.07 |    -0.03 |     -0.06 |                  68.06 |                        74.01 |         55.61 |         65.62 |          69    |        61.81 |           93.06 |             82.54 |         6.12 |
|              17 | TEAM      | TEAM      | US       |               41.78 |                     0.04 |    -0.02 |      0.01 |                  68.38 |                        73.96 |         67    |         82.17 |          65.97 |        47.08 |           43.6  |             92.65 |         9.48 |
|              18 | DAR       | DAR       | US       |                8.5  |                     0.09 |    -0.06 |     -0    |                  64.43 |                        73.79 |         55.85 |         66.55 |          74.65 |        79.46 |           89.72 |             86    |         4.73 |
|              19 | PAA       | PAA       | US       |               15.15 |                     0.06 |    -0.04 |     -0.04 |                  75.96 |                        73.77 |         54.52 |         66.32 |          71.56 |        72.74 |           86.04 |             80.07 |         2.05 |
|              20 | DNORD.CO  | DNORD.CO  | EUROPE   |                1.37 |                     0.07 |    -0.06 |      0.04 |                  80.23 |                        73.64 |         65.93 |         71.49 |          67.82 |        60.7  |           81.48 |             63.78 |         4.75 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    329 | ITRG     | ITRG   | US       |                0.49 |             55.41 |         47.21 |         55.39 |          55.43 |        61.81 |           57.35 |             61.93 |             78.02 |         8.17 |             68.32 | long               |               -0.39 |                  4.38 |                 4.74 |
|    326 | HUT      | HUT    | US       |               10.49 |             55.44 |         65.25 |         52.43 |          58.46 |        43.17 |           37.18 |             79.11 |             12.33 |         8.54 |             66.84 | short              |              nan    |                  4.35 |               nan    |
|      6 | AMC      | AMC    | US       |                2.31 |             79.44 |         80.28 |         83.8  |          78.61 |        77.92 |           86.61 |             79.1  |            nan    |         9.47 |             65.07 | swing              |                3.25 |                  4.11 |                 3.86 |
|    557 | ZH       | ZH     | US       |                0.28 |             43.94 |         71.29 |         52.94 |          34.95 |        25.87 |           17.87 |             25.72 |             24.86 |         7.26 |             73.14 | short              |                4.9  |                  4.02 |                 2.99 |
|    201 | GVR.IR   | GVR.IR | EUROPE   |                1.19 |             60.56 |         59.88 |         54.12 |          61.25 |        63.44 |           69.28 |             64.26 |             58.78 |         2.68 |             73.14 | long               |              nan    |                  3.59 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    474 | TEVA     | TEVA    | US       |               40.18 |             49.59 |         64.41 |         54.59 |          44.6  |        36.89 |           18.2  |             25.14 |             41.34 |         4.8  |             72.34 | short              |               -5.42 |                 -4.03 |                -4.01 |
|    489 | CNC      | CNC     | US       |               26.85 |             48.33 |         40.91 |         52.64 |          56.81 |        44.02 |           12.35 |             73.1  |             56.1  |         5.9  |             71.66 | medium             |              -10.89 |                 -3.8  |                -3.23 |
|    667 | PAH3.DE  | PAH3.DE | EUROPE   |                7.89 |             33.35 |         28.77 |         30.01 |          36.68 |        60.06 |          nan    |             23.55 |             94.2  |         5.13 |             70.3  | long               |              -12    |                 -3.63 |                -3.03 |
|    230 | HAFN     | HAFN    | US       |                4.2  |             59.37 |         65.47 |         59.09 |          56.7  |        59.65 |           72.4  |             13.58 |             51.31 |         5.62 |             69.68 | short              |               -6.6  |                 -3.48 |                -4.16 |
|    651 | 0JHU.IL  | 0JHU.IL | OTHER    |                8.25 |             35.9  |         22.44 |         30.37 |          41.43 |        72.68 |          nan    |            nan    |            100    |         5.15 |             60    | long               |               -1.71 |                 -3.37 |                -3.42 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `relative_63d_rank` vs `sector_score`: r=0.94
- `ret_63d_rank` vs `sector_score`: r=0.93
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
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
| CMBT.BR | 2 |  | 3 |  | 2 | main,pullback |
| DELL | 3 |  | 6 |  | 2 | main,pullback |
| VLO | 5 |  | 1 |  | 2 | main,pullback |
| FRO | 8 |  | 4 |  | 2 | main,pullback |
| NVDA | 29 | 2 | 24 | 1 | 1 | value,quality_value |
| RMT | 255 | 10 | 111 | 8 | 1 | value,quality_value |
| VOLV-B.ST | 341 | 1 | 208 | 2 | 1 | value,quality_value |
| NOVN.SW | 346 | 9 |  | 9 | 1 | value,quality_value |
| ALL | 351 | 8 |  | 4 | 1 | value,quality_value |
| AVGO | 400 | 5 | 149 | 6 | 1 | value,quality_value |
| NOVO-B.CO | 531 | 3 |  | 3 | 1 | value,quality_value |
| HOS | 546 | 4 |  | 5 | 1 | value,quality_value |
| TREE | 680 | 7 |  | 7 | 1 | value,quality_value |
| HPE | 1 |  |  |  | 1 | main |
| MU | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **5** (MU, AMC, REP.MC, SMTC, SHELL.AS)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | VOLV-B.ST | value+pullback | 67.97 | 89.18 | 69.50 | 49.24 | 61.60 | 51.48 | 55.02 |
| 2 | AVGO | value+pullback | 67.28 | 60.81 | 68.41 | 87.89 | 36.41 | 75.57 | 52.67 |
| 3 | NVDA | value+pullback | 65.65 | 61.64 | 46.65 | 82.61 | 79.68 | 75.68 | 72.60 |
| 4 | JPM | value+pullback | 61.34 | 55.85 | 74.79 | 46.09 | 70.18 | 59.78 | 52.94 |
| 5 | RMT | value+pullback | 59.31 | 55.28 | 48.65 | 54.91 | 91.28 | 65.97 | 58.13 |
| 6 | VLO | pullback | 58.53 | 48.90 | 84.21 | 85.77 | 82.03 | 82.04 | 79.86 |
| 7 | CMBT.BR | pullback | 57.19 | 55.52 | 75.94 | 96.24 | 70.80 | 83.47 | 81.05 |
| 8 | PSX | pullback | 57.00 | 51.18 | 81.77 | 79.08 | 87.19 | 79.87 | 76.85 |
| 9 | DHT | pullback | 56.85 | 56.21 | 83.92 | 88.30 | 70.56 | 77.85 | 76.35 |
| 10 | PAA | pullback | 56.81 | 54.50 | 75.96 | 86.04 | 80.07 | 84.54 | 68.94 |
| 11 | SAP.DE | value+pullback | 56.49 | 76.39 | 48.48 | 41.96 | 50.87 | 50.35 | 57.51 |
| 12 | BP | pullback | 56.08 | 55.16 | 70.65 | 86.07 | 89.50 | 82.76 | 71.68 |
| 13 | FRO | pullback | 55.99 | 56.59 | 81.39 | 91.25 | 66.08 | 76.73 | 78.56 |
| 14 | ARGX.BR | pullback | 55.38 | 35.59 | 68.06 | 93.06 | 82.54 | 80.75 | 63.72 |
| 15 | DAR | pullback | 54.76 | 53.06 | 64.43 | 89.72 | 86.00 | 82.96 | 70.60 |
| 16 | NETC.CO | pullback | 54.05 | 41.66 | 76.30 | 83.09 | 74.95 | 75.08 | 56.24 |
| 17 | C5H.IR | pullback | 53.22 | 51.64 | 66.53 | 98.20 | 55.57 | 81.51 | 73.53 |
| 18 | DNORD.CO | pullback | 52.99 | 43.57 | 80.23 | 81.48 | 63.78 | 71.66 | 66.88 |
| 19 | BEN | pullback | 52.93 | 55.21 | 67.18 | 82.78 | 77.67 | 79.76 | 68.14 |
| 20 | NOKIA.HE | value+pullback | 52.40 | 70.80 | 74.51 | 15.87 | 30.15 | 35.66 | 43.87 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 5 / 5 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 73.1 | 13 / 12 |
| Top 50 | 48/50 | 49/50 | 49/50 | 46/50 | 0/50 | 73.1 | 27 / 23 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=2, large_20_100b=3, mega_100b_plus=3
