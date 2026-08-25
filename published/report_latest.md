# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-25

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

- **EUROPE:** 86.2/100
- **OTHER:** 72.4/100
- **US:** 83.2/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PSX      | PSX                        | US       |               82.65 |             82.14 |         80.99 |         86.41 |          83.28 |        78.09 |           78.59 |             86.47 |             64.31 |         3.4  |             69.68 | swing              |              nan    |                  1.43 |                  nan |
|      2 | DHT      | DHT                        | US       |                2.72 |             79.23 |         80.67 |         75.79 |          77.8  |        80.8  |           88.33 |             68.64 |             72.07 |         4.31 |             69.68 | long               |                0.33 |                  1.28 |                  nan |
|      3 | AVAH     | AVAH                       | US       |                2.56 |             79.16 |         86.1  |         83.07 |          75.24 |        72.86 |           94.55 |             52.54 |             43.07 |         7.43 |             68.66 | short              |                0.62 |                  2.72 |                  nan |
|      4 | SM       | SM                         | US       |                7.42 |             78.95 |         80.33 |         74.16 |          77.58 |        82.22 |           80.86 |             71.33 |             97.05 |         7.14 |             68.66 | long               |               -0.36 |                  1.59 |                  nan |
|      5 | MU       | MU                         | US       |              880.22 |             78.37 |         49.31 |         71.1  |          85.64 |        86.46 |           95.22 |             70.17 |             78.11 |         8.26 |             69.68 | long               |              nan    |                nan    |                  nan |
|      6 | JCAP     | JCAP                       | US       |                1.09 |             77.74 |         72.93 |         78.03 |          77.44 |        83.63 |           86.4  |             88.91 |             85.46 |         5.59 |             67.64 | long               |                1.11 |                nan    |                  nan |
|      7 | CRGY     | CRGY                       | US       |                3.92 |             77.34 |         84.26 |         74.79 |          75.32 |        79.36 |           70.4  |             84.34 |             96.79 |         6.24 |             67.05 | short              |               -1.43 |                  0.38 |                  nan |
|      8 | ERO      | ERO                        | US       |                3.44 |             77.33 |         87.8  |         75.36 |          73.65 |        79.31 |           82.81 |             49.86 |             81.06 |         7.67 |             69.68 | short              |               -1.62 |                nan    |                  nan |
|      9 | HPE      | HPE                        | US       |               59.43 |             76.45 |         58.31 |         79.91 |          81.27 |        73    |           68.06 |             81.24 |             61.01 |         6.89 |             67.86 | medium             |                2.12 |                  0.43 |                  nan |
|     10 | KIN.BR   | KIN.BR                     | EUROPE   |                1.23 |             76.39 |         79.97 |         80.49 |          72.81 |        64.69 |           89.64 |             66.5  |             22.17 |         4.2  |             69.68 | swing              |               -1.69 |                  0.77 |                  nan |
|     11 | PR       | PR                         | US       |               16.99 |             76.2  |         80.62 |         76.05 |          76.27 |        76.12 |           76.22 |             72.68 |             72.81 |         4.21 |             68.32 | short              |               -0.25 |                  1.37 |                  nan |
|     12 | SBLK     | SBLK                       | US       |                2.93 |             75.31 |         80.68 |         73.69 |          72.74 |        76.92 |           73.68 |             53.64 |             88.47 |         4.07 |             69.34 | short              |               -0.22 |                  0.28 |                  nan |
|     13 | CAKE     | CAKE                       | US       |                4.88 |             75.25 |         85.16 |         78.76 |          71.74 |        64.46 |           87.42 |             45.04 |             21.59 |         5.88 |             67.18 | short              |                0.04 |                nan    |                  nan |
|     14 | CART     | CART                       | US       |               10.26 |             75.2  |         82.79 |         78.85 |          71.55 |        69.38 |           70.16 |             76.51 |             65.3  |         5.76 |             67.64 | short              |                1.56 |                  1.19 |                  nan |
|     15 | FRO      | FRO                        | US       |                8.39 |             75    |         75.2  |         73.77 |          74.79 |        75.46 |           83.96 |             55.01 |             63.36 |         5.25 |             69.68 | long               |                1.26 |                nan    |                  nan |
|     16 | OVV      | OVV                        | US       |               15.61 |             74.85 |         75.87 |         73.24 |          74.74 |        74.95 |           64.29 |             79.45 |             84.46 |         3.99 |             69.34 | short              |               -0.59 |                  0.83 |                  nan |
|     17 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.73 |             74.82 |         79.73 |         75.94 |          73.7  |        69.12 |           81.59 |             76.92 |             38.13 |         5.09 |             85.57 | short              |                0.63 |                  0.3  |                  nan |
|     18 | PARR     | Par Pacific Holdings, Inc. | US       |                3.19 |             74.68 |         51.12 |         71.08 |          79.24 |        78.28 |           83.48 |             61.89 |             72.8  |         6.89 |             85.72 | medium             |               -0.46 |                  0.84 |                  nan |
|     19 | SSRM     | SSRM                       | US       |                6.86 |             74.47 |         84.41 |         75.41 |          70.4  |        73.52 |           66.48 |             57.23 |             83.56 |         7.07 |             66.14 | short              |               -0.36 |                  1.06 |                  nan |
|     20 | TGT      | TGT                        | US       |               66.05 |             74.44 |         80.86 |         78.41 |          70.47 |        62.75 |           65.75 |             61.62 |             41.18 |         3.28 |             67.64 | short              |              nan    |                nan    |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.27 |                  76.91 |                    74.03 |                 72.71 |              72.78 |                81.77 |                   18.23 |           87.17 |             26.92 |       0.807 |         nan |       nan |      nan    |       -84.38 |          2.26 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | STNE      | StoneCo Ltd.                         | OTHER    |                1.89 |                  75.73 |                    72.64 |                 72.74 |              71.57 |                69.24 |                   30.76 |           85.63 |             45.81 |       0.625 |         nan |       nan |        1.61 |         4.07 |          3.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.19 |                  72.81 |                    71.66 |                 73.05 |              70.78 |                67.57 |                   32.43 |           83.48 |             61.89 |       0.022 |         nan |       nan |        3.68 |         6.29 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | YALA      | Yalla Group Limited                  | OTHER    |                0.72 |                  71.14 |                    71.27 |                 73.07 |              70.09 |                79.47 |                   20.53 |           89.18 |             45.63 |     nan     |         nan |       nan |        0.07 |         5.77 |          7.29 |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|            5 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               63.68 |                  77.8  |                    70.23 |                 67.31 |              73.04 |                60.62 |                   39.38 |           56.18 |             61.09 |       0.034 |         nan |       nan |       16.36 |        13.94 |         19.69 |        1.43 |                 nan |              nan |                  12 |                  0.63 |
|          nan | ADAM      | ADAM                                 | US       |                0.76 |                  66.89 |                    70.14 |                 71.45 |              66.96 |                75.08 |                   24.92 |           88.65 |             52.82 |     nan     |         nan |       nan |      nan    |         7.9  |          5.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.65 |                  70.06 |                    69.4  |                 71.16 |              69.62 |                75.25 |                   24.75 |           79.57 |             56.34 |       1.031 |         nan |       nan |        5.15 |      -114.11 |          2.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              219.16 |                  68.29 |                    69.07 |                 69.77 |              65.34 |                71.89 |                   28.11 |           93.66 |             32.25 |     nan     |         nan |       nan |      nan    |        10.03 |         10.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                                  | US       |                2.72 |                  61.44 |                    68.98 |                 71.65 |              65.05 |                77.51 |                   22.49 |           88.33 |             68.64 |     nan     |         nan |       nan |      nan    |        10.49 |          6.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | WB        | Weibo Corporation                    | OTHER    |                1.47 |                  78.6  |                    67.81 |                 63.84 |              69.96 |                63.79 |                   36.21 |           64.25 |             18.91 |     nan     |         nan |       nan |        1.97 |         5.45 |          5.83 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SM        | SM                                   | US       |                7.42 |                  62.96 |                    67.63 |                 69.6  |              64.89 |                69.04 |                   30.96 |           80.86 |             71.33 |     nan     |         nan |       nan |      nan    |         4.88 |          6.59 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | INVA      | Innoviva, Inc.                       | US       |                1.3  |                  66.06 |                    67.48 |                 69.21 |              65.57 |                80.36 |                   19.64 |           88.46 |             35.42 |       0.073 |         nan |       nan |        6.51 |         9.52 |          4.89 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN       | BEN                                  | US       |               15.06 |                  57.08 |                    67.15 |                 70.44 |              62.8  |                80.39 |                   19.61 |           87.37 |             72.33 |     nan     |         nan |       nan |      nan    |        10.94 |         23.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | UNIT      | Uniti Group Inc.                     | US       |                2.05 |                  80.26 |                    66.91 |                 64.01 |              68.76 |                45.09 |                   54.91 |           67.37 |             28.56 |      -0.108 |         nan |       nan |        9.08 |       -13.87 |          2.61 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           10 | IHS       | IHS Holding Limited                  | OTHER    |                2.41 |                  72.38 |                    66.73 |                 66.31 |              71.12 |                59.4  |                   40.6  |           49.43 |             83.14 |      -0.116 |         nan |       nan |        7.46 |        15.13 |          5.17 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.38 |                  70.24 |                    66.61 |                 66.4  |              66.7  |                70.63 |                   29.37 |           76.3  |             34.13 |       0.08  |         nan |       nan |        3.84 |         5.04 |          4.28 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|           12 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |               98.29 |                  73.63 |                    65.76 |                 64.72 |              68.95 |                49.56 |                   50.44 |           54.53 |             70.11 |       0.16  |         nan |       nan |        1.74 |         6.82 |          4.34 |        4.31 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR   | BIRG.IR                              | EUROPE   |               18.13 |                  57.68 |                    65.66 |                 68.49 |              60.08 |                78.09 |                   21.91 |           96.33 |             44.93 |     nan     |         nan |       nan |      nan    |        10.52 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY       | BMY                                  | US       |              117.65 |                  62.27 |                    65.57 |                 66.75 |              62.92 |                71.38 |                   28.62 |           80.69 |             52.33 |     nan     |         nan |       nan |      nan    |        10.26 |         14.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET        | ET                                   | US       |               62.14 |                  62.33 |                    65.53 |                 66.66 |              62.16 |                73.3  |                   26.7  |           85.93 |             40.84 |     nan     |         nan |       nan |      nan    |        12.05 |         14.54 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                              | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:----------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            4 | YALA      | Yalla Group Limited               | OTHER    |                0.72 |                  71.14 |                    71.27 |                 73.07 |              70.09 |                79.47 |                   20.53 |           89.18 |             45.63 |     nan     |         nan |       nan |        0.07 |         5.77 |          7.29 |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|            3 | PARR      | Par Pacific Holdings, Inc.        | US       |                3.19 |                  72.81 |                    71.66 |                 73.05 |              70.78 |                67.57 |                   32.43 |           83.48 |             61.89 |       0.022 |         nan |       nan |        3.68 |         6.29 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | STNE      | StoneCo Ltd.                      | OTHER    |                1.89 |                  75.73 |                    72.64 |                 72.74 |              71.57 |                69.24 |                   30.76 |           85.63 |             45.81 |       0.625 |         nan |       nan |        1.61 |         4.07 |          3.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            1 | BION.SW   | BB Biotech AG                     | EUROPE   |                3.27 |                  76.91 |                    74.03 |                 72.71 |              72.78 |                81.77 |                   18.23 |           87.17 |             26.92 |       0.807 |         nan |       nan |      nan    |       -84.38 |          2.26 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | DHT       | DHT                               | US       |                2.72 |                  61.44 |                    68.98 |                 71.65 |              65.05 |                77.51 |                   22.49 |           88.33 |             68.64 |     nan     |         nan |       nan |      nan    |        10.49 |          6.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ADAM      | ADAM                              | US       |                0.76 |                  66.89 |                    70.14 |                 71.45 |              66.96 |                75.08 |                   24.92 |           88.65 |             52.82 |     nan     |         nan |       nan |      nan    |         7.9  |          5.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NWL.MI    | NewPrinces S.p.A.                 | EUROPE   |                0.65 |                  70.06 |                    69.4  |                 71.16 |              69.62 |                75.25 |                   24.75 |           79.57 |             56.34 |       1.031 |         nan |       nan |        5.15 |      -114.11 |          2.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BEN       | BEN                               | US       |               15.06 |                  57.08 |                    67.15 |                 70.44 |              62.8  |                80.39 |                   19.61 |           87.37 |             72.33 |     nan     |         nan |       nan |      nan    |        10.94 |         23.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                          | EUROPE   |              219.16 |                  68.29 |                    69.07 |                 69.77 |              65.34 |                71.89 |                   28.11 |           93.66 |             32.25 |     nan     |         nan |       nan |      nan    |        10.03 |         10.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM        | SM                                | US       |                7.42 |                  62.96 |                    67.63 |                 69.6  |              64.89 |                69.04 |                   30.96 |           80.86 |             71.33 |     nan     |         nan |       nan |      nan    |         4.88 |          6.59 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | INVA      | Innoviva, Inc.                    | US       |                1.3  |                  66.06 |                    67.48 |                 69.21 |              65.57 |                80.36 |                   19.64 |           88.46 |             35.42 |       0.073 |         nan |       nan |        6.51 |         9.52 |          4.89 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BIRG.IR   | BIRG.IR                           | EUROPE   |               18.13 |                  57.68 |                    65.66 |                 68.49 |              60.08 |                78.09 |                   21.91 |           96.33 |             44.93 |     nan     |         nan |       nan |      nan    |        10.52 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP       | KDP                               | US       |               37.87 |                  56.37 |                    65.16 |                 68.17 |              60.99 |                75.78 |                   24.22 |           85.17 |             67.59 |     nan     |         nan |       nan |      nan    |        12.83 |         32.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU        | MU                                | US       |              880.22 |                  50.55 |                    63.31 |                 68.12 |              56.66 |                73.61 |                   26.39 |           95.22 |             70.17 |     nan     |         nan |       nan |      nan    |         5.87 |         21.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PSX       | PSX                               | US       |               82.65 |                  51.07 |                    63.74 |                 67.63 |              59.85 |                80.18 |                   19.82 |           78.59 |             86.47 |     nan     |         nan |       nan |      nan    |        11.38 |        110.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | VOLV-B.ST | AB Volvo (publ)                   | EUROPE   |               63.68 |                  77.8  |                    70.23 |                 67.31 |              73.04 |                60.62 |                   39.38 |           56.18 |             61.09 |       0.034 |         nan |       nan |       16.36 |        13.94 |         19.69 |        1.43 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY       | BMY                               | US       |              117.65 |                  62.27 |                    65.57 |                 66.75 |              62.92 |                71.38 |                   28.62 |           80.69 |             52.33 |     nan     |         nan |       nan |      nan    |        10.26 |         14.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET        | ET                                | US       |               62.14 |                  62.33 |                    65.53 |                 66.66 |              62.16 |                73.3  |                   26.7  |           85.93 |             40.84 |     nan     |         nan |       nan |      nan    |        12.05 |         14.54 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY      | CRGY                              | US       |                3.92 |                  57.53 |                    64.31 |                 66.6  |              62.41 |                69.77 |                   30.23 |           70.4  |             84.34 |     nan     |         nan |       nan |      nan    |         6.45 |        173.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AOD       | Abrdn Total Dynamic Dividend Fund | OTHER    |                0.96 |                  51.84 |                    63.2  |                 66.51 |              59.8  |                80.22 |                   19.78 |           76.37 |             80.39 |     nan     |         nan |       nan |      nan    |       nan    |          4.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name    | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:--------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | JCAP     | JCAP    | US       |                1.09 |                     0.07 |    -0.05 |      0.09 |                  78.36 |                        81.38 |         72.93 |         78.03 |          77.44 |        83.63 |           86.4  |             88.91 |         5.59 |
|               2 | KRX.IR   | KRX.IR  | EUROPE   |               18.14 |                     0.03 |     0.01 |      0.33 |                  52.34 |                        78.59 |         82.6  |         73.22 |          68.51 |        65.35 |           95.47 |             68.94 |         5.28 |
|               3 | MU       | MU      | US       |              880.22 |                     0.1  |    -0.1  |      0.01 |                  72.05 |                        75.93 |         49.31 |         71.1  |          85.64 |        86.46 |           95.22 |             70.17 |         8.26 |
|               4 | SHOP     | SHOP    | US       |              164.99 |                     0.06 |     0.01 |      0.18 |                  68.53 |                        72.78 |         76.95 |         70.76 |          58.95 |        50.48 |           68.4  |             68.99 |         7.81 |
|               5 | AMRX     | AMRX    | US       |                5.3  |                     0.07 |    -0.03 |     -0.02 |                  72.23 |                        72.55 |         51.33 |         69.47 |          74.14 |        73.62 |           93.03 |             55.83 |         4.65 |
|               6 | JHX      | JHX     | US       |               15.01 |                     0.03 |    -0.01 |      0.13 |                  56.52 |                        72.53 |         74.48 |         79.22 |          70.05 |        62.68 |           57.42 |             86.42 |         6.08 |
|               7 | SNOW     | SNOW    | US       |               95.77 |                     0.04 |    -0.02 |      0.18 |                  70.05 |                        72.4  |         71.11 |         81.43 |          65.9  |        45.21 |           40.47 |             87.24 |         8.92 |
|               8 | QNST     | QNST    | US       |                1.01 |                     0.07 |     0.02 |      0.32 |                  57.39 |                        72.22 |         81.19 |         76.19 |          70.11 |        71.19 |           82.89 |             42.96 |         7.97 |
|               9 | PLTR     | PLTR    | US       |              361.83 |                     0.02 |     0.02 |      0.34 |                  45.07 |                        72.14 |         79.94 |         67.17 |          58.98 |        54.93 |           88.92 |             50.85 |         8.54 |
|              10 | MP       | MP      | US       |                8.75 |                     0.04 |    -0.02 |      0.33 |                  69.33 |                        72.11 |         74.29 |         51.48 |          49.31 |        46.21 |           58.6  |             85.66 |         8.78 |
|              11 | BILL     | BILL    | US       |                4.11 |                     0.06 |    -0.01 |      0.07 |                  68.92 |                        72.02 |         67.65 |         73.45 |          67.39 |        67.48 |           55.47 |             92.42 |         7.18 |
|              12 | BEN      | BEN     | US       |               15.06 |                     0.03 |     0.01 |      0.04 |                  53.02 |                        71.81 |         67.38 |         71.07 |          77.07 |        79.33 |           87.37 |             72.33 |         3.22 |
|              13 | NTNX     | NTNX    | US       |               15.43 |                     0.02 |     0.02 |      0.17 |                  43.82 |                        71.73 |         72.83 |         77.52 |          67.32 |        56.75 |           76.49 |             73.99 |         7.05 |
|              14 | AMG.AS   | AMG.AS  | EUROPE   |                1.13 |                     0.08 |    -0.08 |      0.18 |                  78.85 |                        71.22 |         62.81 |         47.84 |          58.13 |        65.69 |           77.03 |             83.86 |         6.45 |
|              15 | CVE      | CVE     | US       |               50.79 |                     0.02 |     0    |      0.15 |                  50.71 |                        70.63 |         74.54 |         70.75 |          74.83 |        73.32 |           76.18 |             70.12 |         4.86 |
|              16 | ADAM     | ADAM    | US       |                0.76 |                     0.04 |    -0.03 |      0.13 |                  66.67 |                        70.42 |         69.53 |         69.14 |          75.32 |        82.78 |           88.65 |             52.82 |         3.06 |
|              17 | U        | U       | US       |               17.39 |                     0.02 |     0.02 |      0.52 |                  44.71 |                        70.17 |         84.01 |         84.46 |          64.32 |        46.49 |           36.28 |             93.17 |         8.44 |
|              18 | DAR      | DAR     | US       |                8.42 |                     0.09 |    -0.08 |      0.03 |                  73.41 |                        69.9  |         56.25 |         62.22 |          74.49 |        80.03 |           91.81 |             62.77 |         4.01 |
|              19 | ARGX.BR  | ARGX.BR | EUROPE   |               54.07 |                     0.04 |     0.01 |      0.09 |                  59.66 |                        69.84 |         69.93 |         62.86 |          61.38 |        58.84 |           93.95 |             47.59 |         6    |
|              20 | AALB.AS  | AALB.AS | EUROPE   |                4.51 |                     0.06 |    -0.02 |      0.04 |                  75.87 |                        69.63 |         55.35 |         63.94 |          69.32 |        63.84 |           71.89 |             79.36 |         3.13 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | PD       | PagerDuty, Inc.                                      | US       |                0.81 |             62.82 |         71.27 |         69.1  |          56.55 |        51.71 |           52.32 |             49.12 |             57.4  |         8.5  |             86.86 | short              |                6.02 |                  0.09 |                  nan |
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4322.7  |             55.87 |         51.3  |         51.64 |          60.09 |        63.84 |           92.75 |             65.88 |             28.69 |         8.5  |             89.49 | long               |               -2.44 |                 -0.32 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.78 |             54.72 |         41.8  |         54.2  |          55.25 |        59.96 |           51.52 |             51.52 |             74.35 |         8.51 |             87.57 | long               |                3.37 |                  0.26 |                  nan |
|    nan | JOYY     | JOYY Inc.                                            | OTHER    |                3.17 |             52.47 |         50.18 |         59.47 |          54.76 |        47.39 |           49.12 |             46.15 |             28.56 |         8.5  |             82.25 | swing              |              nan    |                nan    |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.09 |             51.85 |         48.56 |         46.67 |          55.14 |        65.21 |           84.91 |             43.18 |             54.69 |         3.92 |             75.81 | long               |                3.61 |                  0.41 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1461.13 |             48.27 |         31.88 |         40.79 |          55.76 |        59.04 |           83.03 |             58.64 |             29.37 |         6.19 |             89.83 | long               |               -1.62 |                 -0.4  |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.                              | US       |                3.31 |             45.95 |         42.19 |         42.8  |          49.09 |        62.43 |           67.72 |             49.3  |             81.2  |         8.5  |             87.88 | long               |               -0.73 |                 -0.25 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.72 |             45.3  |         39.55 |         41.32 |          49.28 |        62.54 |           61.05 |             53.92 |             89.63 |         4.25 |             82.14 | long               |               -0.3  |                 -0.34 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.72 |             40.24 |         44.07 |         32.84 |          37.62 |        42.86 |           43.79 |             67.93 |             45    |         8.5  |             77.1  | short              |                1.02 |                 -0.84 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.88 |             37.58 |         29.47 |         34.4  |          40.76 |        52.13 |           45.33 |             44.05 |             79.75 |         8.5  |             78.58 | long               |                0.84 |                  0.07 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.15 |             35.7  |         26.67 |         32.13 |          39.28 |        54.24 |           44.19 |             34.21 |             96.67 |         8.5  |             78.48 | long               |               -0.73 |                 -0.21 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.83 |             32.3  |         30.08 |         20.54 |          34.52 |        46.54 |           63.24 |             17.69 |             43.85 |         9.03 |             78.45 | long               |               -1.73 |                 -1.43 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     42 | NWSA     | NWSA     | US       |               14.22 |             71.29 |         76.63 |         74.49 |          68.09 |        65.7  |           83.28 |             69.81 |             41.49 |         4.2  |             67.86 | short              |                8.87 |                  4.15 |                  nan |
|     76 | VG       | VG       | US       |               30.8  |             68.6  |         72.62 |         64.96 |          69.51 |        67.69 |           78.25 |             72.36 |             52.74 |         8.74 |             69.68 | short              |                3.12 |                  3.97 |                  nan |
|    411 | CAI      | CAI      | US       |                6.32 |             54.05 |         77.42 |         62.45 |          45.65 |        37.48 |           54.74 |             26.59 |              5.94 |         9.02 |             69.68 | short              |                0.45 |                  3.1  |                  nan |
|     81 | DSFIR.AS | DSFIR.AS | EUROPE   |               22.51 |             68.41 |         71.73 |         73.52 |          65.09 |        53.39 |           61.54 |             78.88 |             21.9  |         5.62 |             69.68 | swing              |                0.45 |                  3.06 |                  nan |
|    202 | HOOD     | HOOD     | US       |               79.75 |             62.17 |         66.34 |         66.15 |          58.19 |        49.29 |           62.94 |             66.22 |             14.23 |         8.76 |             68.2  | short              |               -1.34 |                  2.82 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol    | name              | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    284 | AKER.OL   | AKER.OL           | EUROPE   |                9.97 |             58.68 |         74.54 |         62.92 |          54.44 |        38.78 |           33.67 |             47.84 |             11.64 |         3.84 |             67.86 | short              |              -13.88 |                 -3.94 |                  nan |
|    579 | INDU-A.ST | INDU-A.ST         | EUROPE   |               20.85 |             45.7  |         45.72 |         45.69 |          47.4  |        41.33 |           37.61 |             47.87 |             25.69 |         1.84 |             65.8  | medium             |               -9.12 |                 -2.46 |                  nan |
|    671 | AF.PA     | Air France-KLM SA | EUROPE   |                3.05 |             37.1  |         31.01 |         34.2  |          40    |        49.33 |           43.35 |             32.32 |             74.38 |         6.48 |             76.7  | long               |               -7.71 |                 -2.23 |                  nan |
|    567 | FLR       | FLR               | US       |                5.87 |             46.82 |         46.65 |         51.98 |          46.99 |        43.91 |           18.99 |             67.22 |             53.99 |         5.94 |             68.66 | swing              |              nan    |                 -2.22 |                  nan |
|    501 | CERT      | CERT              | US       |                1.04 |             50.72 |         53.26 |         63.06 |          48.18 |        40.11 |           20.07 |             68.26 |             45.7  |         8.67 |             69.68 | swing              |               -7.88 |                 -2.13 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
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
- Excluded by hard/data filters: **284**
- Event watch (otherwise eligible): **12**
- Final eligible: **704**
- Eligible change vs previous stored run: **-4**

Top exclusion categories:
- liquidity: 233
- price: 163
- market_cap: 152
- price_history: 18
- data_confidence: 12
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MU | 5 |  | 3 |  | 2 | main,pullback |
| JCAP | 6 |  | 1 |  | 2 | main,pullback |
| PARR | 18 | 3 |  | 2 | 1 | value,quality_value |
| BION.SW | 114 | 1 |  | 4 | 1 | value,quality_value |
| IHS | 310 | 10 |  | 9 | 1 | value,quality_value |
| VOLV-B.ST | 407 | 5 | 183 | 7 | 1 | value,quality_value |
| YALA | 473 | 4 |  | 1 | 1 | value,quality_value |
| INVA | 564 | 8 | 214 | 6 | 1 | value,quality_value |
| NWL.MI | 625 | 6 | 189 | 5 | 1 | value,quality_value |
| STNE | 629 | 2 |  | 3 | 1 | value,quality_value |
| PSX | 1 |  |  |  | 1 | main |
| DHT | 2 |  |  |  | 1 | main |
| AVAH | 3 |  |  |  | 1 | main |
| SM | 4 |  |  |  | 1 | main |
| CRGY | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (PSX, DHT, AVAH, CRGY, ERO, HPE, KIN.BR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (MP)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 73.13 | 70.06 | 77.98 | 79.57 | 56.34 | 75.25 | 42.89 |
| 2 | INVA | value+pullback | 67.19 | 66.06 | 57.95 | 88.46 | 35.42 | 80.36 | 46.90 |
| 3 | VOLV-B.ST | value+pullback | 65.10 | 77.80 | 60.40 | 56.18 | 61.09 | 60.62 | 54.16 |
| 4 | UNIT | value+pullback | 63.58 | 80.26 | 70.09 | 67.37 | 28.56 | 45.09 | 43.23 |
| 5 | ETG | value+pullback | 62.83 | 55.53 | 49.92 | 68.55 | 80.64 | 76.72 | 61.65 |
| 6 | MFA | value+pullback | 60.28 | 57.72 | 61.68 | 77.94 | 33.64 | 62.44 | 42.74 |
| 7 | ALL-PH | value+pullback | 60.10 | 62.44 | 58.73 | 69.44 | 42.36 | 60.15 | 44.70 |
| 8 | AVK | value+pullback | 59.45 | 55.15 | 63.04 | 62.74 | 56.03 | 60.67 | 52.74 |
| 9 | TV | value+pullback | 57.96 | 67.97 | 63.25 | 42.79 | 30.40 | 61.51 | 39.14 |
| 10 | ACCO | value+pullback | 57.88 | 74.99 | 54.59 | 38.61 | 54.12 | 52.67 | 55.97 |
| 11 | MSFT | value+pullback | 57.85 | 58.21 | 53.82 | 63.55 | 67.28 | 53.36 | 60.62 |
| 12 | WKC | value+pullback | 57.72 | 61.83 | 33.83 | 64.35 | 75.40 | 67.58 | 68.79 |
| 13 | JCAP | pullback | 57.55 | 57.21 | 78.36 | 86.40 | 88.91 | 80.53 | 77.74 |
| 14 | ORCL | value+pullback | 56.83 | 69.90 | 58.67 | 50.26 | 59.89 | 38.31 | 41.96 |
| 15 | ONIT | value+pullback | 56.49 | 72.40 | 51.34 | 62.02 | 42.64 | 41.86 | 43.77 |
| 16 | PBR | value+pullback | 56.36 | 61.62 | 56.72 | 54.53 | 59.86 | 47.64 | 59.73 |
| 17 | KYN | value+pullback | 55.95 | 58.82 | 50.99 | 54.85 | 56.08 | 58.63 | 54.29 |
| 18 | AAPL | value+pullback | 55.66 | 60.17 | 46.70 | 66.74 | 49.24 | 55.01 | 51.44 |
| 19 | BION.SW | value | 55.19 | 76.91 | 35.86 | 87.17 | 26.92 | 81.77 | 66.29 |
| 20 | YALA | value | 55.18 | 71.14 | 41.93 | 89.18 | 45.63 | 79.47 | 51.65 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.2 | 3 / 7 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 68.7 | 8 / 17 |
| Top 50 | 50/50 | 50/50 | 49/50 | 49/50 | 0/50 | 68.7 | 16 / 34 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=1, large_20_100b=2, mega_100b_plus=1
