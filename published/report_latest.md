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

- **EUROPE:** 79.3/100
- **OTHER:** 67.6/100
- **US:** 81.1/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO       | FRO       | US       |                9.38 |             83.95 |         83.31 |         84.59 |          84.85 |        82.18 |           90.8  |             79.67 |             62.15 |         5.42 |             73.14 | medium             |               -0.96 |                  0.92 |                 0.77 |
|      2 | HPE       | HPE       | US       |               74.08 |             83.94 |         89.91 |         86.55 |          81.32 |        72.44 |           71.67 |             81.12 |             52.23 |         6.91 |             72.34 | short              |                2.58 |                  0.83 |               nan    |
|      3 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.79 |             83.16 |         71.22 |         81.89 |          85.67 |        84.43 |           95.65 |             78.29 |             67.6  |         3.74 |             73.14 | medium             |               -1.03 |                  1.4  |                 1.31 |
|      4 | VLO       | VLO       | US       |               96.85 |             83.08 |         78.08 |         85.86 |          85.15 |        81.01 |           85.77 |             80.73 |             63.33 |         3.56 |             69.68 | swing              |               -2.67 |                  1.15 |                 1.04 |
|      5 | MU        | MU        | US       |             1072.18 |             82.84 |         80.16 |         71.26 |          85.56 |        85.51 |           95.18 |             81.22 |             73.03 |         8.12 |             73.14 | medium             |                2.07 |                  2.78 |                 2.15 |
|      6 | DHT       | DHT       | US       |                3.07 |             82.09 |         80.74 |         82.17 |          82.43 |        82    |           88.16 |             82.47 |             66.38 |         4.49 |             73.14 | medium             |                0.02 |                  1.14 |                 0.74 |
|      7 | AMC       | AMC       | US       |                2.28 |             81.43 |         82.27 |         87.75 |          80.59 |        79.65 |           85.13 |             79.28 |            nan    |         9.51 |             65.07 | swing              |                5.24 |                  4.51 |                 4.16 |
|      8 | PSX       | PSX       | US       |               89.7  |             80.9  |         75.2  |         85.06 |          83.04 |        78.77 |           79.07 |             85.6  |             63.63 |         3.78 |             73.14 | swing              |               -2.96 |                  1.17 |                 1.21 |
|      9 | P         | P         | US       |               35.68 |             80.81 |         92.77 |         87.86 |          73.76 |        59.68 |           69.59 |             90.88 |             13.25 |         8.13 |             72.68 | short              |                3.45 |                  3.24 |                 2.36 |
|     10 | DELL      | DELL      | US       |              299.43 |             80.24 |         78.98 |         83.9  |          81.49 |        69.92 |           72.73 |             86.41 |             38.37 |         7.8  |             72.23 | swing              |               -3.38 |                 -0.4  |                -0.45 |
|     11 | HSHP      | HSHP      | US       |                0.75 |             79.58 |         79.76 |         82.83 |          79.4  |        69.5  |           85.86 |            nan    |             27.5  |         4.81 |             62.84 | swing              |               -3.22 |                nan    |               nan    |
|     12 | NAT       | NAT       | US       |                1.43 |             78.89 |         80.64 |         79.06 |          78.71 |        73.88 |           86.95 |             69.64 |             42.63 |         4.85 |             73.14 | short              |               -1.68 |                  0.16 |                 0.19 |
|     13 | OKTA      | OKTA      | US       |               31.74 |             78.78 |         90.8  |         84.64 |          72.92 |        59.1  |           69.78 |             69.6  |             13.21 |         7.8  |             71.77 | short              |                0.25 |                  1.01 |                 0.98 |
|     14 | HALO      | HALO      | US       |               11.49 |             78.25 |         82.53 |         81.08 |          75.42 |        72.31 |           85.9  |             51.89 |             51.35 |         6.06 |             72.11 | short              |                2.14 |                nan    |               nan    |
|     15 | SHELL.AS  | SHELL.AS  | EUROPE   |              239.99 |             78.06 |         81.17 |         75.63 |          74.04 |        80.49 |           92.45 |             78.77 |             67.92 |         2.45 |             73.14 | short              |                3.91 |                  2.8  |                 2.62 |
|     16 | KIN.BR    | KIN.BR    | EUROPE   |                1.36 |             77.75 |         80.51 |         81.27 |          74.99 |        65.56 |           88.53 |             64.9  |             18.46 |         3.67 |             73.14 | swing              |                0    |                 -0.19 |                -0.15 |
|     17 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.42 |             77.56 |         68.08 |         74.8  |          80.31 |        82.28 |           69.57 |            nan    |             99.68 |         4.27 |             62.84 | long               |                2.38 |                nan    |               nan    |
|     18 | REP.MC    | REP.MC    | EUROPE   |               32.97 |             77.3  |         83.3  |         80.4  |          74.2  |        70.62 |           57.36 |             77.49 |             73.56 |         3.78 |             73.14 | short              |                2.64 |                  1.62 |                 1.3  |
|     19 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.94 |             76.85 |         78.42 |         75.22 |          75.93 |        77.77 |           96.2  |             66.31 |             58.45 |         2.2  |             73.14 | short              |                1.12 |                  2.03 |                 1.71 |
|     20 | WT        | WT        | US       |                3.19 |             76.44 |         74.77 |         81.31 |          78.11 |        68.1  |           73.51 |             83.36 |             35.18 |         5.92 |             73.14 | swing              |                2.49 |                  2.62 |                 2.32 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.01 |                  73.97 |                    74.47 |                 76.14 |              74.66 |                86.71 |                   13.29 |           84.64 |             57.93 |       0.872 |         nan |       nan |      nan    |       -78.14 |          2.09 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | BBWI     | Bath & Body Works, Inc.              | US       |                2.98 |                  82.54 |                    71.49 |                 67.67 |              72.28 |                52.6  |                   47.4  |           70.25 |             33.84 |       0.226 |         nan |       nan |        5.58 |         6.03 |          4.41 |        0.69 |                 nan |              nan |                  11 |                  0.58 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              114.23 |                  76.22 |                    71.35 |                 71.21 |              74.43 |                64.55 |                   35.45 |           61.33 |             79.31 |       0.14  |         nan |       nan |        1.79 |         4.72 |          4.8  |        5.5  |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              239.99 |                  59.88 |                    71.22 |                 74.85 |              66.56 |                86.52 |                   13.48 |           92.45 |             78.77 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | NVDA     | NVIDIA Corporation                   | US       |             4764.53 |                  60.87 |                    70.65 |                 72.61 |              65.73 |                77.24 |                   22.76 |           86.5  |             80.01 |       0.008 |         nan |       nan |       26.77 |        14.32 |         28.5  |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                                  | US       |                3.07 |                  60.45 |                    70.47 |                 73.84 |              66.44 |                81.51 |                   18.49 |           88.16 |             82.47 |     nan     |         nan |       nan |      nan    |        10.1  |          7.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              100.49 |                  59.41 |                    70.25 |                 73.82 |              66.28 |                82.31 |                   17.69 |           86.83 |             86.91 |     nan     |         nan |       nan |      nan    |         9.03 |         21.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              239.6  |                  66.12 |                    70.22 |                 71.39 |              69.27 |                76.11 |                   23.89 |           73.14 |             79.57 |     nan     |         nan |       nan |      nan    |         9.23 |         10.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.79 |                  56.91 |                    69.78 |                 74.08 |              64.18 |                85.42 |                   14.58 |           95.65 |             78.29 |     nan     |         nan |       nan |      nan    |         9.07 |          6.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.38 |                  68.48 |                    69.73 |                 71.67 |              68.63 |                68.62 |                   31.38 |           80.43 |             69.68 |       0.021 |         nan |       nan |        3.77 |         5.55 |          4.52 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.73 |                  74.83 |                    69.15 |                 69.38 |              70.59 |                68.62 |                   31.38 |           75.5  |             43.59 |       0.634 |         nan |       nan |        4.62 |      -127.59 |          2.2  |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | INVA     | Innoviva, Inc.                       | US       |                1.31 |                  64.71 |                    69.04 |                 71.46 |              66.43 |                82.33 |                   17.67 |           89.82 |             50.2  |       0.074 |         nan |       nan |        6.37 |         9.35 |          4.7  |        0.25 |                 nan |              nan |                  10 |                  0.53 |
|            8 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  72.47 |                    69.02 |                 69.14 |              69.81 |                62.43 |                   37.57 |           70.34 |             63.88 |       0.434 |         nan |       nan |        5.7  |         3.19 |          3.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM       | SM                                   | US       |                7.34 |                  62.66 |                    68.94 |                 71.38 |              66.07 |                72.06 |                   27.94 |           81.58 |             79.82 |     nan     |         nan |       nan |      nan    |         4.4  |          6.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.38 |                  57.88 |                    68.88 |                 72.71 |              64.06 |                80.1  |                   19.9  |           90.8  |             79.67 |     nan     |         nan |       nan |      nan    |        10.48 |          7.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1469.43 |                  60.81 |                    68.28 |                 68.88 |              62.35 |                78.42 |                   21.58 |           92.29 |             44.55 |       0.018 |         nan |       nan |       32.68 |        18.08 |         44.63 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.94 |                  56.06 |                    68.03 |                 71.96 |              62.28 |                84.89 |                   15.11 |           96.2  |             66.31 |     nan     |         nan |       nan |      nan    |        10.95 |         14.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.09 |                  68.99 |                    67.74 |                 66.81 |              69.15 |                69.76 |                   30.24 |           61.12 |            nan    |       0.24  |         nan |       nan |        1.54 |       nan    |          2.87 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              176.44 |                  65.3  |                    67.57 |                 68.01 |              67.92 |                71.66 |                   28.34 |           63.45 |             80.08 |     nan     |         nan |       nan |      nan    |         9.03 |         11.44 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | STNE     | StoneCo Ltd.                         | OTHER    |                1.86 |                  68.99 |                    67.51 |                 67.45 |              64.87 |                66.54 |                   33.46 |           86.35 |             32.21 |       0.647 |         nan |       nan |        1.6  |         4.04 |          3.43 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.01 |                  73.97 |                    74.47 |                 76.14 |              74.66 |                86.71 |                   13.29 |           84.64 |             57.93 |       0.872 |         nan |       nan |      nan    |       -78.14 |          2.09 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              239.99 |                  59.88 |                    71.22 |                 74.85 |              66.56 |                86.52 |                   13.48 |           92.45 |             78.77 |     nan     |         nan |       nan |      nan    |         9.59 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.79 |                  56.91 |                    69.78 |                 74.08 |              64.18 |                85.42 |                   14.58 |           95.65 |             78.29 |     nan     |         nan |       nan |      nan    |         9.07 |          6.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.07 |                  60.45 |                    70.47 |                 73.84 |              66.44 |                81.51 |                   18.49 |           88.16 |             82.47 |     nan     |         nan |       nan |      nan    |        10.1  |          7.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              100.49 |                  59.41 |                    70.25 |                 73.82 |              66.28 |                82.31 |                   17.69 |           86.83 |             86.91 |     nan     |         nan |       nan |      nan    |         9.03 |         21.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.38 |                  57.88 |                    68.88 |                 72.71 |              64.06 |                80.1  |                   19.9  |           90.8  |             79.67 |     nan     |         nan |       nan |      nan    |        10.48 |          7.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | NVDA     | NVIDIA Corporation                   | US       |             4764.53 |                  60.87 |                    70.65 |                 72.61 |              65.73 |                77.24 |                   22.76 |           86.5  |             80.01 |       0.008 |         nan |       nan |       26.77 |        14.32 |         28.5  |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.94 |                  56.06 |                    68.03 |                 71.96 |              62.28 |                84.89 |                   15.11 |           96.2  |             66.31 |     nan     |         nan |       nan |      nan    |        10.95 |         14.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.38 |                  68.48 |                    69.73 |                 71.67 |              68.63 |                68.62 |                   31.38 |           80.43 |             69.68 |       0.021 |         nan |       nan |        3.77 |         5.55 |          4.52 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | INVA     | Innoviva, Inc.                       | US       |                1.31 |                  64.71 |                    69.04 |                 71.46 |              66.43 |                82.33 |                   17.67 |           89.82 |             50.2  |       0.074 |         nan |       nan |        6.37 |         9.35 |          4.7  |        0.25 |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                                 | US       |              239.6  |                  66.12 |                    70.22 |                 71.39 |              69.27 |                76.11 |                   23.89 |           73.14 |             79.57 |     nan     |         nan |       nan |      nan    |         9.23 |         10.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.34 |                  62.66 |                    68.94 |                 71.38 |              66.07 |                72.06 |                   27.94 |           81.58 |             79.82 |     nan     |         nan |       nan |      nan    |         4.4  |          6.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              114.23 |                  76.22 |                    71.35 |                 71.21 |              74.43 |                64.55 |                   35.45 |           61.33 |             79.31 |       0.14  |         nan |       nan |        1.79 |         4.72 |          4.8  |        5.5  |                 nan |              nan |                  12 |                  0.63 |
|          nan | MU       | MU                                   | US       |             1072.18 |                  48.56 |                    63.92 |                 69.44 |              57.02 |                77.42 |                   22.58 |           95.18 |             81.22 |     nan     |         nan |       nan |      nan    |         6.77 |         24.21 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.73 |                  74.83 |                    69.15 |                 69.38 |              70.59 |                68.62 |                   31.38 |           75.5  |             43.59 |       0.634 |         nan |       nan |        4.62 |      -127.59 |          2.2  |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            8 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  72.47 |                    69.02 |                 69.14 |              69.81 |                62.43 |                   37.57 |           70.34 |             63.88 |       0.434 |         nan |       nan |        5.7  |         3.19 |          3.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               24.46 |                  55.09 |                    65.47 |                 68.99 |              59.58 |                80.57 |                   19.43 |           95.99 |             54.13 |     nan     |         nan |       nan |      nan    |        11.77 |         12.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1469.43 |                  60.81 |                    68.28 |                 68.88 |              62.35 |                78.42 |                   21.58 |           92.29 |             44.55 |       0.018 |         nan |       nan |       32.68 |        18.08 |         44.63 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.64 |                  63.21 |                    67.4  |                 68.74 |              64.39 |                76.24 |                   23.76 |           84.49 |             51.57 |     nan     |         nan |       nan |      nan    |         8.71 |          7.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR                               | EUROPE   |                1.67 |                  52.96 |                    64.49 |                 68.42 |              58.04 |                80.69 |                   19.31 |           97.63 |             53.88 |     nan     |         nan |       nan |      nan    |        10.42 |         10.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO      | VLO      | US       |               96.85 |                     0.07 |    -0.07 |      0.1  |                  80.29 |                        84.24 |         78.08 |         85.86 |          85.15 |        81.01 |           85.77 |             80.73 |         3.56 |
|               2 | FRO      | FRO      | US       |                9.38 |                     0.07 |    -0.05 |      0.24 |                  78.62 |                        84.2  |         83.31 |         84.59 |          84.85 |        82.18 |           90.8  |             79.67 |         5.42 |
|               3 | PSX      | PSX      | US       |               89.7  |                     0.07 |    -0.07 |      0.06 |                  82.98 |                        83.63 |         75.2  |         85.06 |          83.04 |        78.77 |           79.07 |             85.6  |         3.78 |
|               4 | DHT      | DHT      | US       |                3.07 |                     0.07 |    -0.05 |      0.18 |                  77.15 |                        82.66 |         80.74 |         82.17 |          82.43 |        82    |           88.16 |             82.47 |         4.49 |
|               5 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.79 |                     0.09 |    -0.06 |      0.04 |                  70.61 |                        82.41 |         71.22 |         81.89 |          85.67 |        84.43 |           95.65 |             78.29 |         3.74 |
|               6 | DELL     | DELL     | US       |              299.43 |                     0.09 |    -0.09 |      0.16 |                  75.74 |                        80.82 |         78.98 |         83.9  |          81.49 |        69.92 |           72.73 |             86.41 |         7.8  |
|               7 | NAT      | NAT      | US       |                1.43 |                     0.07 |    -0.06 |      0.22 |                  78.15 |                        79.88 |         80.64 |         79.06 |          78.71 |        73.88 |           86.95 |             69.64 |         4.85 |
|               8 | SMTC     | SMTC     | US       |               14.31 |                     0.06 |    -0.02 |      0.24 |                  75.79 |                        79.55 |         81.81 |         74.5  |          74.39 |        61.64 |           72.88 |             84.69 |         8.43 |
|               9 | BP       | BP       | US       |              100.49 |                     0.05 |    -0.02 |      0.04 |                  76.89 |                        79.26 |         74.64 |         72.77 |          72.42 |        78.79 |           86.83 |             86.91 |         4.47 |
|              10 | EQNR     | EQNR     | US       |               89.91 |                     0.06 |    -0.03 |      0.05 |                  77.6  |                        77.91 |         71.87 |         77.22 |          74.95 |        75.35 |           75.27 |             84.06 |         5.67 |
|              11 | SHELL.AS | SHELL.AS | EUROPE   |              239.99 |                     0.02 |     0.02 |      0.07 |                  42.53 |                        77.27 |         81.17 |         75.63 |          74.04 |        80.49 |           92.45 |             78.77 |         2.45 |
|              12 | CIRSA.MC | CIRSA.MC | EUROPE   |                3.23 |                     0.03 |    -0.01 |      0.38 |                  60.32 |                        76.38 |         84.35 |         79.12 |          69.57 |        69.05 |           81.5  |             59.05 |         5.36 |
|              13 | DAR      | DAR      | US       |                8.56 |                     0.09 |    -0.07 |     -0.01 |                  71.22 |                        76.02 |         57.1  |         69.01 |          77.88 |        83.9  |           89.59 |             86.06 |         4.75 |
|              14 | C5H.IR   | C5H.IR   | EUROPE   |                1.67 |                     0.05 |     0.02 |      0.06 |                  64.69 |                        75.58 |         76.54 |         68.61 |          72.68 |        76.38 |           97.63 |             53.88 |         2.66 |
|              15 | APA      | APA      | US       |               13.45 |                     0.08 |    -0.04 |      0.06 |                  67.6  |                        75.03 |         71.67 |         75.71 |          74.98 |        77.96 |           74.93 |             80.35 |         6.04 |
|              16 | BE       | BE       | US       |               69    |                     0.05 |    -0.05 |      0.22 |                  82.56 |                        75    |         72.53 |         57.59 |          68.29 |        60.56 |           85.54 |             61.66 |         9.15 |
|              17 | NTNX     | NTNX     | US       |               16.31 |                     0.02 |    -0.02 |      0.05 |                  55.35 |                        74.8  |         71.56 |         77.63 |          69.89 |        63.03 |           93.49 |             59.86 |         6.59 |
|              18 | NESTE.HE | NESTE.HE | EUROPE   |               26.59 |                     0.03 |    -0.01 |      0.11 |                  60.4  |                        73.76 |         79.47 |         74.72 |          69.27 |        60.69 |           60.17 |             86.2  |         4.9  |
|              19 | MT.AS    | MT.AS    | EUROPE   |               47.95 |                     0.06 |     0.01 |     -0.01 |                  66.82 |                        73.75 |         65.14 |         75.72 |          78.02 |        74.59 |           67.98 |             81.78 |         5.06 |
|              20 | SHEL     | SHEL     | US       |              239.6  |                     0.03 |    -0    |      0.05 |                  58.41 |                        73.74 |         76.84 |         74.77 |          71.16 |        76.5  |           73.14 |             79.57 |         2.96 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol    | name                     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | INDU-C.ST | AB Industrivärden (publ) | EUROPE   |               20.81 |             65.62 |         67.78 |         63.8  |          67.31 |        63.93 |           82.6  |             78.22 |             27.16 |         2.48 |             64.78 | short              |               10.47 |                  3.41 |                 2.6  |
|    nan | TLRY      | Tilray Brands, Inc.      | OTHER    |                0.5  |             28.17 |         29.46 |         22.34 |          26.89 |        34.3  |           44.15 |             31.73 |             32.86 |         8.93 |             78.44 | long               |                2.98 |                  0.13 |                 0.22 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      7 | AMC      | AMC        | US       |                2.28 |             81.43 |         82.27 |         87.75 |          80.59 |        79.65 |           85.13 |             79.28 |            nan    |         9.51 |             65.07 | swing              |                5.24 |                  4.51 |                 4.16 |
|    598 | ZH       | Zhihu Inc. | OTHER    |                0.28 |             43.71 |         68.48 |         50.88 |          36.54 |        31.21 |           31.3  |             25.2  |             33.07 |         6.35 |             82.17 | short              |                4.67 |                  3.97 |                 2.96 |
|    264 | VZLA     | VZLA       | OTHER    |                1.23 |             60.11 |         56.7  |         61.24 |          59.7  |        60.52 |           85.42 |            nan    |             29.63 |         8.37 |             61.82 | swing              |                2.6  |                  3.9  |               nan    |
|    141 | RBI.VI   | RBI.VI     | EUROPE   |               21.46 |             65.71 |         74.61 |         70.36 |          61.07 |        48.25 |            7.45 |             69.33 |             70.55 |         4.43 |             71.77 | short              |                5.47 |                  3.79 |                 3.2  |
|    217 | BMNR     | BMNR       | US       |               14.86 |             62.23 |         78.66 |         68.01 |          56.44 |        55    |           73.01 |             45.69 |             32.43 |         9.55 |             71.32 | short              |                0.46 |                  3.73 |                 3.47 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    641 | SONY     | SONY    | US       |              118.07 |             40.09 |         40.54 |         50.46 |          39.64 |        35.08 |           21.19 |             45.69 |             38.27 |         5.17 |             69.5  | swing              |              nan    |                 -4.05 |                -3.92 |
|    672 | PAH3.DE  | PAH3.DE | EUROPE   |                7.91 |             35.43 |         29.83 |         31.75 |          39.12 |        63.26 |          nan    |             27.58 |             97.53 |         5.16 |             70.3  | long               |               -9.91 |                 -3.21 |                -2.71 |
|    406 | TEVA     | TEVA    | US       |               41.21 |             54.69 |         70.9  |         60.73 |          48.65 |        39.99 |           13.72 |             30.25 |             50.33 |         4.79 |             72.34 | short              |               -0.32 |                 -3.01 |                -3.25 |
|    637 | PIRC.MI  | PIRC.MI | EUROPE   |                7.02 |             40.31 |         48.48 |         43.23 |          37.4  |        36.48 |           15.27 |             22.39 |             60.16 |         2.14 |             71.32 | short              |               -3.75 |                 -2.95 |                -2.82 |
|    322 | UMC      | UMC     | US       |               53.1  |             57.74 |         69.51 |         54.86 |          60.62 |        51.91 |           60.75 |             37.83 |             22.57 |         7.81 |             72.68 | short              |               -1.31 |                 -2.86 |                -3.12 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
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
- Excluded by hard/data filters: **291**
- Event watch (otherwise eligible): **2**
- Final eligible: **707**
- Eligible change vs previous stored run: **-2**

Top exclusion categories:
- liquidity: 238
- price: 183
- market_cap: 165
- price_history: 17
- data_confidence: 9
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| FRO | 1 |  | 2 |  | 2 | main,pullback |
| CMBT.BR | 3 |  | 5 |  | 2 | main,pullback |
| VLO | 4 |  | 1 |  | 2 | main,pullback |
| DHT | 6 |  | 4 |  | 2 | main,pullback |
| PSX | 8 |  | 3 |  | 2 | main,pullback |
| DELL | 10 |  | 6 |  | 2 | main,pullback |
| PBR-A | 38 | 3 | 25 | 5 | 1 | value,quality_value |
| NVDA | 63 | 4 |  | 2 | 1 | value,quality_value |
| PARR | 67 | 5 | 35 | 3 | 1 | value,quality_value |
| EMBC | 160 | 8 |  | 7 | 1 | value,quality_value |
| BION.SW | 204 | 1 | 107 | 1 | 1 | value,quality_value |
| NWL.MI | 294 | 6 | 78 | 6 | 1 | value,quality_value |
| AVGO | 375 | 9 | 97 | 8 | 1 | value,quality_value |
| INVA | 455 | 7 | 135 | 4 | 1 | value,quality_value |
| BBWI | 636 | 2 |  | 9 | 1 | value,quality_value |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **2** (HPE, MU)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (SMTC)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 73.18 | 73.97 | 60.62 | 84.64 | 57.93 | 86.71 | 62.73 |
| 2 | INVA | value+pullback | 69.92 | 64.71 | 62.20 | 89.82 | 50.20 | 82.33 | 52.77 |
| 3 | GSL | value+pullback | 69.56 | 67.43 | 80.11 | 75.67 | 30.47 | 74.53 | 60.26 |
| 4 | PARR | value+pullback | 69.42 | 68.48 | 64.48 | 80.43 | 69.68 | 68.62 | 71.24 |
| 5 | AVGO | value+pullback | 69.11 | 60.81 | 67.55 | 92.29 | 44.55 | 78.42 | 55.68 |
| 6 | NWL.MI | value+pullback | 68.80 | 74.83 | 67.79 | 75.50 | 43.59 | 68.62 | 58.83 |
| 7 | PBR-A | value+pullback | 66.50 | 76.22 | 54.36 | 61.33 | 79.31 | 64.55 | 73.83 |
| 8 | IRS | value+pullback | 66.05 | 67.40 | 79.95 | 63.58 | 40.40 | 61.33 | 45.89 |
| 9 | PBR | value+pullback | 64.60 | 66.52 | 64.62 | 61.33 | 69.01 | 61.93 | 70.38 |
| 10 | VOLV-B.ST | value+pullback | 64.07 | 65.15 | 70.31 | 59.09 | 63.06 | 58.88 | 53.98 |
| 11 | GAB | value+pullback | 63.73 | 56.28 | 73.90 | 54.18 | 77.99 | 62.24 | 50.29 |
| 12 | HMC | value+pullback | 63.22 | 55.22 | 55.76 | 75.65 | 81.02 | 66.30 | 66.74 |
| 13 | 0Q2N.IL | value+pullback | 63.17 | 68.99 | 57.39 | 61.12 |  | 69.76 | 59.92 |
| 14 | STNE | value+pullback | 62.75 | 68.99 | 50.30 | 86.35 | 32.21 | 66.54 | 39.65 |
| 15 | MAGN | value+pullback | 62.56 | 66.85 | 65.22 | 68.70 | 33.55 | 62.71 | 48.16 |
| 16 | WB | value+pullback | 62.52 | 71.47 | 65.03 | 73.42 | 17.46 | 60.30 | 37.92 |
| 17 | AVK | value+pullback | 62.21 | 58.66 | 74.17 | 62.24 | 49.49 | 58.89 | 47.34 |
| 18 | SAP.DE | value+pullback | 61.80 | 59.67 | 55.34 | 74.09 | 55.20 | 67.17 | 61.58 |
| 19 | BCE | value+pullback | 61.52 | 59.29 | 59.99 | 80.43 | 53.49 | 56.59 | 42.76 |
| 20 | CNC | value+pullback | 60.34 | 71.09 | 60.60 | 48.04 | 63.90 | 51.35 | 58.68 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 72.9 | 8 / 2 |
| Top 25 | 25/25 | 23/25 | 24/25 | 22/25 | 0/25 | 72.7 | 13 / 12 |
| Top 50 | 50/50 | 48/50 | 49/50 | 47/50 | 0/50 | 72.7 | 26 / 24 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=1, large_20_100b=4, mega_100b_plus=2
