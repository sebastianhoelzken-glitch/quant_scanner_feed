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
- **OTHER:** 73.2/100
- **US:** 83.2/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PSX      | PSX                        | US       |               82.65 |             82.12 |         80.99 |         86.42 |          83.26 |        78.02 |           78.45 |             86.54 |             64.19 |         3.4  |             69.68 | swing              |              nan    |                  1.42 |                  nan |
|      2 | DHT      | DHT                        | US       |                2.72 |             79.25 |         80.69 |         75.81 |          77.81 |        80.8  |           88.37 |             68.69 |             71.96 |         4.31 |             69.68 | long               |                0.35 |                  1.28 |                  nan |
|      3 | AVAH     | AVAH                       | US       |                2.56 |             79.13 |         86.1  |         83.07 |          75.2  |        72.77 |           94.39 |             52.62 |             42.94 |         7.43 |             68.66 | short              |                0.6  |                  2.71 |                  nan |
|      4 | SM       | SM                         | US       |                7.42 |             78.9  |         80.31 |         74.14 |          77.49 |        82.07 |           80.47 |             71.38 |             97.09 |         7.14 |             68.66 | long               |               -0.42 |                  1.58 |                  nan |
|      5 | MU       | MU                         | US       |              880.22 |             78.37 |         49.34 |         71.1  |          85.64 |        86.44 |           95.33 |             70.15 |             77.89 |         8.26 |             69.68 | long               |              nan    |                nan    |                  nan |
|      6 | JCAP     | JCAP                       | US       |                1.09 |             77.66 |         72.93 |         78    |          77.32 |        83.39 |           86    |             88.99 |             85.1  |         5.59 |             67.64 | long               |                1.04 |                nan    |                  nan |
|      7 | CRGY     | CRGY                       | US       |                3.92 |             77.27 |         84.26 |         74.79 |          75.27 |        79.27 |           70.24 |             84.32 |             96.65 |         6.24 |             67.05 | short              |               -1.5  |                  0.36 |                  nan |
|      8 | ERO      | ERO                        | US       |                3.44 |             77.27 |         87.79 |         75.33 |          73.59 |        79.21 |           82.75 |             49.8  |             80.8  |         7.67 |             69.68 | short              |               -1.69 |                nan    |                  nan |
|      9 | TGB      | TGB                        | US       |                2.93 |             76.96 |         88.91 |         80.88 |          73.04 |        68.39 |           55.78 |             87.9  |             59.32 |         7.7  |             69.23 | short              |                3.98 |                  1.61 |                  nan |
|     10 | HPE      | HPE                        | US       |               59.43 |             76.46 |         58.35 |         79.93 |          81.29 |        72.99 |           68.2  |             81.3  |             60.71 |         6.89 |             67.86 | medium             |                2.13 |                  0.43 |                  nan |
|     11 | PR       | PR                         | US       |               16.99 |             76.11 |         80.59 |         76.03 |          76.19 |        75.98 |           75.87 |             72.74 |             72.8  |         4.21 |             68.32 | short              |               -0.34 |                  1.35 |                  nan |
|     12 | KIN.BR   | KIN.BR                     | EUROPE   |                1.23 |             75.72 |         79.26 |         79.54 |          72.17 |        64.15 |           89.81 |             66.47 |             22.04 |         4.2  |             69.68 | swing              |               -2.36 |                  0.64 |                  nan |
|     13 | SBLK     | SBLK                       | US       |                2.93 |             75.22 |         80.66 |         73.65 |          72.66 |        76.8  |           73.53 |             53.58 |             88.24 |         4.07 |             69.34 | short              |               -0.3  |                  0.27 |                  nan |
|     14 | CAKE     | CAKE                       | US       |                4.88 |             75.2  |         85.14 |         78.73 |          71.67 |        64.36 |           87.25 |             44.97 |             21.52 |         5.88 |             67.18 | short              |               -0.02 |                nan    |                  nan |
|     15 | CART     | CART                       | US       |               10.26 |             75.08 |         82.73 |         78.8  |          71.36 |        69.08 |           69.41 |             76.57 |             65.31 |         5.76 |             67.64 | short              |                1.44 |                  1.16 |                  nan |
|     16 | FRO      | FRO                        | US       |                8.39 |             74.97 |         75.19 |         73.74 |          74.75 |        75.42 |           83.89 |             54.95 |             63.35 |         5.25 |             69.68 | long               |                1.23 |                nan    |                  nan |
|     17 | OVV      | OVV                        | US       |               15.61 |             74.82 |         75.9  |         73.27 |          74.74 |        74.91 |           64.28 |             79.51 |             84.22 |         3.99 |             69.34 | short              |               -0.61 |                  0.82 |                  nan |
|     18 | PARR     | Par Pacific Holdings, Inc. | US       |                3.19 |             74.68 |         51.12 |         71.09 |          79.24 |        78.28 |           83.48 |             61.82 |             72.8  |         6.89 |             85.72 | medium             |               -0.46 |                  0.84 |                  nan |
|     19 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.73 |             74.47 |         79.46 |         75.54 |          73.41 |        68.86 |           81.59 |             76.88 |             38.13 |         5.1  |             85.57 | short              |                0.28 |                  0.23 |                  nan |
|     20 | SSRM     | SSRM                       | US       |                6.86 |             74.4  |         84.41 |         75.39 |          70.34 |        73.4  |           66.42 |             57.18 |             83.22 |         7.07 |             66.14 | short              |               -0.42 |                  1.04 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.27 |                  78.34 |                    75.21 |                 73.85 |              73.9  |                82.25 |                   17.75 |           88.91 |             26.88 |       0.807 |         nan |       nan |      nan    |       -84.38 |          2.26 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | STNE      | StoneCo Ltd.                         | OTHER    |                1.89 |                  75.73 |                    72.61 |                 72.69 |              71.53 |                69.17 |                   30.83 |           85.63 |             45.55 |       0.626 |         nan |       nan |        1.61 |         4.07 |          3.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               63.79 |                  84.11 |                    72.58 |                 68.69 |              76.86 |                56.61 |                   43.39 |           52.72 |             61.12 |       0.034 |         nan |       nan |       16.36 |        13.94 |         19.69 |        1.43 |                 nan |              nan |                  12 |                  0.63 |
|            4 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.19 |                  72.81 |                    71.66 |                 73.04 |              70.77 |                67.56 |                   32.44 |           83.48 |             61.82 |       0.022 |         nan |       nan |        3.68 |         6.29 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.38 |                  79.95 |                    71.4  |                 70.06 |              73.29 |                68.57 |                   31.43 |           74.89 |             33.82 |       0.08  |         nan |       nan |        3.84 |         5.04 |          4.28 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            6 | YALA      | Yalla Group Limited                  | OTHER    |                0.72 |                  71.14 |                    71.25 |                 73.04 |              70.07 |                79.43 |                   20.57 |           89.18 |             45.48 |     nan     |         nan |       nan |        0.07 |         5.77 |          7.29 |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|          nan | ADAM      | ADAM                                 | US       |                0.76 |                  66.1  |                    69.66 |                 71.06 |              66.39 |                75.02 |                   24.98 |           88.49 |             52.9  |     nan     |         nan |       nan |      nan    |         7.9  |          5.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.65 |                  70.06 |                    69.39 |                 71.14 |              69.61 |                75.22 |                   24.78 |           79.57 |             56.22 |       1.031 |         nan |       nan |        5.15 |      -114.11 |          2.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | DHT       | DHT                                  | US       |                2.72 |                  61.36 |                    68.95 |                 71.64 |              65    |                77.55 |                   22.45 |           88.37 |             68.69 |     nan     |         nan |       nan |      nan    |        10.49 |          6.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | WB        | Weibo Corporation                    | OTHER    |                1.47 |                  78.6  |                    67.76 |                 63.77 |              69.91 |                63.7  |                   36.3  |           64.25 |             18.56 |     nan     |         nan |       nan |        1.97 |         5.45 |          5.83 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SM        | SM                                   | US       |                7.42 |                  63.08 |                    67.61 |                 69.54 |              64.95 |                68.86 |                   31.14 |           80.47 |             71.38 |     nan     |         nan |       nan |      nan    |         4.88 |          6.59 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              219.16 |                  65.72 |                    67.56 |                 68.58 |              63.46 |                71.84 |                   28.16 |           93.62 |             32.14 |     nan     |         nan |       nan |      nan    |        10.03 |         10.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | INVA      | Innoviva, Inc.                       | US       |                1.3  |                  66.06 |                    67.46 |                 69.17 |              65.54 |                80.33 |                   19.67 |           88.46 |             35.21 |       0.073 |         nan |       nan |        6.51 |         9.52 |          4.89 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|           10 | DAC       | Danaos Corporation                   | OTHER    |                2.35 |                  64.59 |                    67.44 |                 69.58 |              66.42 |                79.29 |                   20.71 |           80.65 |             56.39 |       0.002 |         nan |       nan |        4.03 |         6.14 |          5.07 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BEN       | BEN                                  | US       |               15.06 |                  57.05 |                    67.2  |                 70.52 |              62.8  |                80.53 |                   19.47 |           87.67 |             72.31 |     nan     |         nan |       nan |      nan    |        10.94 |         23.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | IHS       | IHS Holding Limited                  | OTHER    |                2.41 |                  73.2  |                    67.18 |                 66.67 |              71.71 |                59.4  |                   40.6  |           49.43 |             83.1  |      -0.116 |         nan |       nan |        7.46 |        15.13 |          5.17 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           12 | UNIT      | Uniti Group Inc.                     | US       |                2.05 |                  80.26 |                    66.87 |                 63.96 |              68.72 |                45.01 |                   54.99 |           67.37 |             28.28 |      -0.108 |         nan |       nan |        9.08 |       -13.87 |          2.61 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           13 | ACCO      | ACCO Brands Corporation              | US       |                0.33 |                  81.06 |                    65.96 |                 61.58 |              72.99 |                51.31 |                   48.69 |           37.28 |             53.91 |       0.106 |         nan |       nan |        7.98 |         4.35 |          6.87 |        0.81 |                 nan |              nan |                  12 |                  0.63 |
|           14 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |               98.29 |                  73.63 |                    65.77 |                 64.74 |              68.96 |                49.58 |                   50.42 |           54.53 |             70.24 |       0.16  |         nan |       nan |        1.74 |         6.82 |          4.34 |        4.31 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY       | BMY                                  | US       |              117.65 |                  62.27 |                    65.56 |                 66.73 |              62.9  |                71.35 |                   28.65 |           80.67 |             52.27 |     nan     |         nan |       nan |      nan    |        10.26 |         14.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                              | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:----------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                     | EUROPE   |                3.27 |                  78.34 |                    75.21 |                 73.85 |              73.9  |                82.25 |                   17.75 |           88.91 |             26.88 |       0.807 |         nan |       nan |      nan    |       -84.38 |          2.26 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            6 | YALA      | Yalla Group Limited               | OTHER    |                0.72 |                  71.14 |                    71.25 |                 73.04 |              70.07 |                79.43 |                   20.57 |           89.18 |             45.48 |     nan     |         nan |       nan |        0.07 |         5.77 |          7.29 |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|            4 | PARR      | Par Pacific Holdings, Inc.        | US       |                3.19 |                  72.81 |                    71.66 |                 73.04 |              70.77 |                67.56 |                   32.44 |           83.48 |             61.82 |       0.022 |         nan |       nan |        3.68 |         6.29 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | STNE      | StoneCo Ltd.                      | OTHER    |                1.89 |                  75.73 |                    72.61 |                 72.69 |              71.53 |                69.17 |                   30.83 |           85.63 |             45.55 |       0.626 |         nan |       nan |        1.61 |         4.07 |          3.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT       | DHT                               | US       |                2.72 |                  61.36 |                    68.95 |                 71.64 |              65    |                77.55 |                   22.45 |           88.37 |             68.69 |     nan     |         nan |       nan |      nan    |        10.49 |          6.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | NWL.MI    | NewPrinces S.p.A.                 | EUROPE   |                0.65 |                  70.06 |                    69.39 |                 71.14 |              69.61 |                75.22 |                   24.78 |           79.57 |             56.22 |       1.031 |         nan |       nan |        5.15 |      -114.11 |          2.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | ADAM      | ADAM                              | US       |                0.76 |                  66.1  |                    69.66 |                 71.06 |              66.39 |                75.02 |                   24.98 |           88.49 |             52.9  |     nan     |         nan |       nan |      nan    |         7.9  |          5.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN       | BEN                               | US       |               15.06 |                  57.05 |                    67.2  |                 70.52 |              62.8  |                80.53 |                   19.47 |           87.67 |             72.31 |     nan     |         nan |       nan |      nan    |        10.94 |         23.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | GSL       | Global Ship Lease, Inc.           | OTHER    |                1.38 |                  79.95 |                    71.4  |                 70.06 |              73.29 |                68.57 |                   31.43 |           74.89 |             33.82 |       0.08  |         nan |       nan |        3.84 |         5.04 |          4.28 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|           10 | DAC       | Danaos Corporation                | OTHER    |                2.35 |                  64.59 |                    67.44 |                 69.58 |              66.42 |                79.29 |                   20.71 |           80.65 |             56.39 |       0.002 |         nan |       nan |        4.03 |         6.14 |          5.07 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM        | SM                                | US       |                7.42 |                  63.08 |                    67.61 |                 69.54 |              64.95 |                68.86 |                   31.14 |           80.47 |             71.38 |     nan     |         nan |       nan |      nan    |         4.88 |          6.59 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | INVA      | Innoviva, Inc.                    | US       |                1.3  |                  66.06 |                    67.46 |                 69.17 |              65.54 |                80.33 |                   19.67 |           88.46 |             35.21 |       0.073 |         nan |       nan |        6.51 |         9.52 |          4.89 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|            3 | VOLV-B.ST | AB Volvo (publ)                   | EUROPE   |               63.79 |                  84.11 |                    72.58 |                 68.69 |              76.86 |                56.61 |                   43.39 |           52.72 |             61.12 |       0.034 |         nan |       nan |       16.36 |        13.94 |         19.69 |        1.43 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS  | SHELL.AS                          | EUROPE   |              219.16 |                  65.72 |                    67.56 |                 68.58 |              63.46 |                71.84 |                   28.16 |           93.62 |             32.14 |     nan     |         nan |       nan |      nan    |        10.03 |         10.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                           | EUROPE   |               18.13 |                  57.32 |                    65.43 |                 68.3  |              59.8  |                78.04 |                   21.96 |           96.27 |             44.86 |     nan     |         nan |       nan |      nan    |        10.52 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU        | MU                                | US       |              880.22 |                  50.55 |                    63.33 |                 68.15 |              56.67 |                73.66 |                   26.34 |           95.33 |             70.15 |     nan     |         nan |       nan |      nan    |         5.87 |         21.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP       | KDP                               | US       |               37.87 |                  56.37 |                    65.13 |                 68.12 |              60.97 |                75.71 |                   24.29 |           85.06 |             67.55 |     nan     |         nan |       nan |      nan    |        12.83 |         32.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PSX       | PSX                               | US       |               82.65 |                  51.07 |                    63.72 |                 67.6  |              59.85 |                80.13 |                   19.87 |           78.45 |             86.54 |     nan     |         nan |       nan |      nan    |        11.38 |        110.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AOD       | Abrdn Total Dynamic Dividend Fund | OTHER    |                0.96 |                  51.84 |                    63.38 |                 66.74 |              59.95 |                80.59 |                   19.41 |           76.61 |             81.16 |     nan     |         nan |       nan |      nan    |       nan    |          4.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY       | BMY                               | US       |              117.65 |                  62.27 |                    65.56 |                 66.73 |              62.9  |                71.35 |                   28.65 |           80.67 |             52.27 |     nan     |         nan |       nan |      nan    |        10.26 |         14.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name    | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:--------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | JCAP     | JCAP    | US       |                1.09 |                     0.07 |    -0.05 |      0.09 |                  78.36 |                        81.3  |         72.93 |         78    |          77.32 |        83.39 |           86    |             88.99 |         5.59 |
|               2 | KRX.IR   | KRX.IR  | EUROPE   |               18.14 |                     0.03 |     0.01 |      0.33 |                  52.34 |                        78.25 |         81.9  |         72.29 |          67.87 |        64.79 |           95.57 |             68.9  |         5.28 |
|               3 | MU       | MU      | US       |              880.22 |                     0.1  |    -0.1  |      0.01 |                  72.05 |                        75.94 |         49.34 |         71.1  |          85.64 |        86.44 |           95.33 |             70.15 |         8.26 |
|               4 | SHOP     | SHOP    | US       |              164.99 |                     0.06 |     0.01 |      0.18 |                  68.53 |                        72.76 |         76.95 |         70.75 |          58.92 |        50.43 |           68.28 |             68.96 |         7.81 |
|               5 | JHX      | JHX     | US       |               15.01 |                     0.03 |    -0.01 |      0.13 |                  56.52 |                        72.52 |         74.49 |         79.23 |          70.01 |        62.58 |           57.27 |             86.49 |         6.08 |
|               6 | AMRX     | AMRX    | US       |                5.3  |                     0.07 |    -0.03 |     -0.02 |                  72.23 |                        72.49 |         51.34 |         69.44 |          74.07 |        73.52 |           92.85 |             55.77 |         4.65 |
|               7 | SNOW     | SNOW    | US       |               95.77 |                     0.04 |    -0.02 |      0.18 |                  70.05 |                        72.4  |         71.12 |         81.43 |          65.9  |        45.2  |           40.45 |             87.24 |         8.92 |
|               8 | QNST     | QNST    | US       |                1.01 |                     0.07 |     0.02 |      0.32 |                  57.39 |                        72.17 |         81.16 |         76.16 |          70.05 |        71.12 |           82.74 |             42.89 |         7.97 |
|               9 | PLTR     | PLTR    | US       |              361.83 |                     0.02 |     0.02 |      0.34 |                  45.07 |                        72.12 |         79.93 |         67.16 |          58.96 |        54.92 |           88.9  |             50.78 |         8.54 |
|              10 | MP       | MP      | US       |                8.75 |                     0.04 |    -0.02 |      0.33 |                  69.33 |                        72.02 |         74.25 |         51.44 |          49.22 |        46.05 |           58.25 |             85.65 |         8.78 |
|              11 | BILL     | BILL    | US       |                4.11 |                     0.06 |    -0.01 |      0.07 |                  68.92 |                        71.91 |         67.64 |         73.42 |          67.28 |        67.3  |           54.93 |             92.49 |         7.18 |
|              12 | BEN      | BEN     | US       |               15.06 |                     0.03 |     0.01 |      0.04 |                  53.02 |                        71.89 |         67.46 |         71.12 |          77.15 |        79.45 |           87.67 |             72.31 |         3.22 |
|              13 | NTNX     | NTNX    | US       |               15.43 |                     0.02 |     0.02 |      0.17 |                  43.82 |                        71.72 |         72.82 |         77.51 |          67.29 |        56.72 |           76.45 |             73.97 |         7.05 |
|              14 | AMG.AS   | AMG.AS  | EUROPE   |                1.13 |                     0.08 |    -0.08 |      0.18 |                  78.85 |                        70.95 |         62.15 |         46.9  |          57.51 |        65.13 |           77.39 |             83.84 |         6.45 |
|              15 | CVE      | CVE     | US       |               50.79 |                     0.02 |     0    |      0.15 |                  50.71 |                        70.64 |         74.56 |         70.77 |          74.82 |        73.24 |           76.14 |             70.17 |         4.86 |
|              16 | ADAM     | ADAM    | US       |                0.76 |                     0.04 |    -0.03 |      0.13 |                  66.67 |                        70.42 |         69.57 |         69.17 |          75.3  |        82.71 |           88.49 |             52.9  |         3.06 |
|              17 | U        | U       | US       |               17.39 |                     0.02 |     0.02 |      0.52 |                  44.71 |                        70.1  |         83.98 |         84.44 |          64.23 |        46.33 |           35.93 |             93.25 |         8.44 |
|              18 | DAR      | DAR     | US       |                8.42 |                     0.09 |    -0.08 |      0.03 |                  73.41 |                        69.89 |         56.27 |         62.23 |          74.49 |        80.02 |           91.78 |             62.73 |         4.01 |
|              19 | ARGX.BR  | ARGX.BR | EUROPE   |               54.07 |                     0.04 |     0.01 |      0.09 |                  59.66 |                        69.52 |         69.23 |         61.91 |          60.76 |        58.32 |           94.11 |             47.53 |         6    |
|              20 | AALB.AS  | AALB.AS | EUROPE   |                4.51 |                     0.06 |    -0.02 |      0.04 |                  75.87 |                        69.3  |         54.77 |         63.05 |          68.79 |        63.4  |           72.39 |             79.42 |         3.13 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | PD       | PagerDuty, Inc.                                      | US       |                0.81 |             62.79 |         71.29 |         69.08 |          56.51 |        51.69 |           52.32 |             48.93 |             57.4  |         8.5  |             86.86 | short              |                5.99 |                  0.08 |                  nan |
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4322.7  |             55.9  |         51.33 |         51.68 |          60.12 |        63.85 |           92.75 |             66.02 |             28.69 |         8.5  |             89.49 | long               |               -2.41 |                 -0.31 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.78 |             54.7  |         41.82 |         54.18 |          55.22 |        59.95 |           51.52 |             51.44 |             74.35 |         8.52 |             87.57 | long               |                3.35 |                  0.26 |                  nan |
|    nan | JOYY     | JOYY Inc.                                            | OTHER    |                3.17 |             52.13 |         49.85 |         59    |          54.4  |        47.09 |           49.12 |             45.93 |             28.56 |         8.5  |             82.25 | swing              |              nan    |                nan    |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.09 |             51.86 |         48.57 |         46.67 |          55.14 |        65.21 |           84.91 |             43.15 |             54.69 |         3.91 |             75.81 | long               |                3.61 |                  0.41 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1461.13 |             48.23 |         31.86 |         40.75 |          55.72 |        59.02 |           83.03 |             58.46 |             29.37 |         6.2  |             89.83 | long               |               -1.66 |                 -0.41 |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.                              | US       |                3.31 |             45.91 |         42.17 |         42.76 |          49.05 |        62.4  |           67.72 |             49.09 |             81.2  |         8.5  |             87.88 | long               |               -0.77 |                 -0.26 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.72 |             44.94 |         39.28 |         40.9  |          48.97 |        62.27 |           61.05 |             53.73 |             89.63 |         4.25 |             82.14 | long               |               -0.67 |                 -0.41 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.72 |             40.21 |         44.05 |         32.8  |          37.57 |        42.84 |           43.79 |             67.76 |             45    |         8.5  |             77.1  | short              |                0.98 |                 -0.85 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.88 |             37.7  |         29.58 |         34.5  |          40.9  |        52.27 |           46.25 |             43.71 |             78.73 |         8.5  |             78.58 | long               |                0.96 |                  0.09 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.15 |             36.23 |         26.93 |         32.44 |          40.02 |        55.42 |           47.26 |             33.88 |             96.36 |         8.5  |             78.48 | long               |               -0.2  |                 -0.11 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.83 |             32.29 |         30.09 |         20.5  |          34.48 |        46.53 |           63.24 |             17.55 |             43.85 |         9.04 |             78.45 | long               |               -1.74 |                 -1.43 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     43 | NWSA     | NWSA     | US       |               14.22 |             71.26 |         76.59 |         74.43 |          68.09 |        65.71 |           83.56 |             69.86 |             41.27 |         4.2  |             67.86 | short              |                8.84 |                  4.14 |                  nan |
|     76 | VG       | VG       | US       |               30.8  |             68.52 |         72.62 |         64.95 |          69.46 |        67.59 |           78.13 |             72.33 |             52.53 |         8.74 |             69.68 | short              |                3.05 |                  3.95 |                  nan |
|    405 | CAI      | CAI      | US       |                6.32 |             54.01 |         77.41 |         62.42 |          45.6  |        37.41 |           54.61 |             26.55 |              5.9  |         9.02 |             69.68 | short              |                0.41 |                  3.09 |                  nan |
|     88 | DSFIR.AS | DSFIR.AS | EUROPE   |               22.51 |             67.81 |         71.07 |         72.61 |          64.55 |        52.95 |           62.04 |             78.86 |             21.65 |         5.62 |             69.68 | swing              |               -0.15 |                  2.94 |                  nan |
|    193 | HOOD     | HOOD     | US       |               79.75 |             62.18 |         66.35 |         66.17 |          58.19 |        49.27 |           62.9  |             66.26 |             14.18 |         8.76 |             68.2  | short              |               -1.33 |                  2.83 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    299 | AKER.OL   | AKER.OL   | EUROPE   |                9.96 |             57.91 |         73.79 |         61.94 |          53.88 |        38.33 |           34.03 |             47.77 |             11.5  |         3.84 |             67.86 | short              |              -14.65 |                 -4.09 |                  nan |
|    586 | INDU-A.ST | INDU-A.ST | EUROPE   |               20.89 |             44.96 |         45.09 |         44.82 |          46.89 |        40.98 |           38.28 |             47.77 |             25.47 |         1.84 |             67.86 | medium             |               -9.87 |                 -2.61 |                  nan |
|    105 | SSABBH.HE | SSABBH.HE | EUROPE   |                9    |             66.44 |         47.65 |         57.32 |          75.56 |        80.94 |           73.22 |            nan    |             98.56 |         4.02 |             62.84 | long               |                0.37 |                 -2.27 |                  nan |
|    564 | FLR       | FLR       | US       |                5.87 |             46.79 |         46.68 |         51.97 |          46.91 |        43.75 |           18.75 |             67.18 |             53.72 |         5.94 |             68.66 | swing              |              nan    |                 -2.23 |                  nan |
|    660 | AVOL.SW   | AVOL.SW   | EUROPE   |                7.11 |             38.6  |         29.83 |         34.55 |          42.66 |        47.51 |           54.41 |             42.14 |             41.73 |         3.61 |             69.68 | long               |               -9.52 |                 -2.22 |                  nan |

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
- market_cap: 150
- price_history: 18
- data_confidence: 12
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MU | 5 |  | 3 |  | 2 | main,pullback |
| JCAP | 6 |  | 1 |  | 2 | main,pullback |
| PARR | 18 | 4 |  | 3 | 1 | value,quality_value |
| DAC | 37 | 10 |  | 7 | 1 | value,quality_value |
| GSL | 92 | 5 |  | 6 | 1 | value,quality_value |
| BION.SW | 94 | 1 |  | 1 | 1 | value,quality_value |
| VOLV-B.ST | 394 | 3 | 190 | 9 | 1 | value,quality_value |
| YALA | 469 | 6 |  | 2 | 1 | value,quality_value |
| INVA | 559 | 9 | 212 | 8 | 1 | value,quality_value |
| NWL.MI | 619 | 7 | 186 | 5 | 1 | value,quality_value |
| STNE | 624 | 2 |  | 4 | 1 | value,quality_value |
| PSX | 1 |  |  |  | 1 | main |
| DHT | 2 |  |  |  | 1 | main |
| AVAH | 3 |  |  |  | 1 | main |
| SM | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (PSX, DHT, AVAH, CRGY, ERO, TGB, HPE)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (MP)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 73.12 | 70.06 | 77.98 | 79.57 | 56.22 | 75.22 | 42.88 |
| 2 | INVA | value+pullback | 67.16 | 66.06 | 57.95 | 88.46 | 35.21 | 80.33 | 46.88 |
| 3 | VOLV-B.ST | value+pullback | 65.67 | 84.11 | 60.40 | 52.72 | 61.12 | 56.61 | 54.25 |
| 4 | UNIT | value+pullback | 63.54 | 80.26 | 70.09 | 67.37 | 28.28 | 45.01 | 43.20 |
| 5 | ETG | value+pullback | 62.99 | 55.53 | 49.92 | 68.77 | 81.42 | 76.99 | 61.79 |
| 6 | MFA | value+pullback | 60.20 | 57.72 | 61.68 | 77.94 | 33.22 | 62.27 | 42.70 |
| 7 | ALL-PH | value+pullback | 59.88 | 62.25 | 58.73 | 69.35 | 41.91 | 59.65 | 44.61 |
| 8 | ACCO | value+pullback | 59.21 | 81.06 | 54.59 | 37.28 | 53.91 | 51.31 | 56.01 |
| 9 | TV | value+pullback | 57.94 | 67.97 | 63.25 | 42.79 | 30.22 | 61.48 | 38.84 |
| 10 | MSFT | value+pullback | 57.86 | 58.21 | 53.82 | 63.55 | 67.37 | 53.37 | 60.65 |
| 11 | WKC | value+pullback | 57.73 | 61.83 | 33.83 | 64.35 | 75.48 | 67.59 | 68.80 |
| 12 | JCAP | pullback | 57.46 | 57.11 | 78.36 | 86.00 | 88.99 | 80.35 | 77.66 |
| 13 | ORCL | value+pullback | 56.81 | 69.90 | 58.67 | 50.26 | 59.81 | 38.29 | 41.94 |
| 14 | PBR | value+pullback | 56.33 | 61.62 | 56.72 | 54.53 | 59.67 | 47.60 | 59.46 |
| 15 | ONIT | value+pullback | 56.22 | 72.18 | 51.34 | 62.04 | 42.32 | 40.96 | 43.71 |
| 16 | KYN | value+pullback | 56.13 | 58.82 | 50.99 | 55.53 | 56.22 | 58.91 | 54.44 |
| 17 | BION.SW | value | 55.98 | 78.34 | 35.86 | 88.91 | 26.88 | 82.25 | 67.63 |
| 18 | AAPL | value+pullback | 55.62 | 60.17 | 46.70 | 66.74 | 48.92 | 54.94 | 51.39 |
| 19 | YALA | value | 55.15 | 71.14 | 41.93 | 89.18 | 45.48 | 79.43 | 51.64 |
| 20 | LNC | value+pullback | 54.27 | 57.02 | 58.98 | 44.64 | 63.82 | 46.73 | 57.18 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 68.9 | 3 / 7 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 68.7 | 7 / 18 |
| Top 50 | 50/50 | 50/50 | 49/50 | 49/50 | 0/50 | 68.7 | 16 / 34 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=1, large_20_100b=2, mega_100b_plus=1
