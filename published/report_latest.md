# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-18

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

- **EUROPE:** 81.7/100
- **OTHER:** 82.1/100
- **US:** 81.1/100

## Main multi-horizon ranking

|   rank | symbol   | name                               | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | DELL     | Dell Technologies Inc.             | US       |              326.17 |             82.22 |         91.29 |         86.25 |          78.2  |        66.11 |           57.82 |             82.4  |             49.47 |         7.6  |             87.7  | short              |               -1.24 |                  0.26 |                -0.48 |
|      2 | AVAH     | Aveanna Healthcare Holdings Inc.   | US       |                2.66 |             80.42 |         81.67 |         84.76 |          79.17 |        73.25 |           69.5  |             73.96 |             66.25 |         7.25 |             87.56 | swing              |               -2.52 |                  0.22 |                 0.06 |
|      3 | HPE      | Hewlett Packard Enterprise Company | US       |               70.64 |             79.81 |         86.14 |         81.53 |          78.09 |        71.63 |           59.54 |             75.18 |             75.47 |         6.62 |             89.42 | short              |                5.68 |                 -0.66 |                -0.94 |
|      4 | FRO      | Frontline plc                      | OTHER    |               10.49 |             79.37 |         81.43 |         80.76 |          77.99 |        70.72 |           87.27 |             75.64 |             34.29 |         5.18 |             84.96 | short              |               -7.01 |                 -1    |                -0.9  |
|      5 | DINO     | HF Sinclair Corporation            | US       |               18.08 |             79    |         80.78 |         83.8  |          77.23 |        70.2  |           63    |             77.54 |             68.93 |         5.24 |             85.41 | swing              |               -2.6  |                 -0.08 |                -0.44 |
|      6 | KIN.BR   | Kinepolis Group NV                 | EUROPE   |                1.33 |             78.69 |         83.31 |         81.58 |          75.79 |        66.52 |           84.78 |             75.98 |             28.5  |         3.66 |             84.75 | short              |               -0.3  |                  0.06 |                -0.34 |
|      7 | GRK.HE   | GRK Infra Oyj                      | EUROPE   |                1.08 |             78.53 |         80.05 |         83.44 |          77    |        68.88 |           55.64 |             80.63 |             64.84 |         4.13 |             84.64 | swing              |                7.59 |                  1.42 |               nan    |
|      8 | NAT      | Nordic American Tankers Limited    | OTHER    |                1.5  |             78.08 |         82.86 |         80.45 |          75.72 |        66.75 |           86.07 |             70.07 |             22.79 |         5.13 |             83.93 | short              |               -4.02 |                  0.31 |                 0.39 |
|      9 | VLO      | Valero Energy Corporation          | US       |              103.56 |             77.3  |         80.69 |         81.2  |          73.91 |        64.52 |           63.25 |             73.93 |             48.89 |         4.32 |             87.49 | swing              |               -8.72 |                 -1.48 |               nan    |
|     10 | HAFN     | Hafnia Limited                     | OTHER    |                4.24 |             76.78 |         79.96 |         81.06 |          73.6  |        70.1  |           62.28 |             74.49 |             70.3  |         4.02 |             83.9  | swing              |               -0.75 |                 -0.14 |                -0.91 |
|     11 | DHT      | DHT Holdings, Inc.                 | OTHER    |                3.21 |             76.4  |         80.92 |         78.06 |          74.74 |        68.76 |           80.05 |             77.94 |             38.93 |         5.12 |             84.79 | short              |               -9.03 |                 -0.13 |                -0.33 |
|     12 | RBRK     | Rubrik, Inc.                       | US       |               19.35 |             76.33 |         87.86 |         83.91 |          68.75 |        52.64 |           48.39 |             80.44 |             22.1  |         8.37 |             85.93 | short              |               -0.08 |                  3.86 |                 3.34 |
|     13 | OERL.SW  | OC Oerlikon Corporation AG         | EUROPE   |                1.89 |             76.18 |         78.9  |         81.78 |          73.45 |        64.37 |           43.84 |             71.09 |             68.67 |         5.22 |             84.21 | swing              |                6.52 |                  2.65 |                 1.97 |
|     14 | CMBT.BR  | Cmb.Tech NV                        | EUROPE   |                5.11 |             76.17 |         80.79 |         77.59 |          74.75 |        66.01 |           69.28 |             80.05 |             44.39 |         4.06 |             83.78 | short              |              -10.51 |                  0.49 |                 0.73 |
|     15 | SB       | Safe Bulkers, Inc.                 | OTHER    |                0.89 |             75.41 |         83.44 |         78.53 |          72.29 |        64.89 |           60    |             72.68 |             51.3  |         4.89 |             83.97 | short              |               -3.96 |                  0.89 |               nan    |
|     16 | SMTC     | Semtech Corporation                | US       |               14.5  |             75.17 |         87.84 |         77.9  |          72.45 |        59.52 |           67.05 |             77.77 |             20.31 |         8.19 |             88.69 | short              |                3.99 |                  0.55 |               nan    |
|     17 | DK       | Delek US Holdings, Inc.            | US       |                4.35 |             75.08 |         86.26 |         80.18 |          69.97 |        59.4  |           42.16 |             74.04 |             60.95 |         7.21 |             83.57 | short              |              nan    |                 -1.4  |                -1.3  |
|     18 | PSX      | Phillips 66                        | US       |               95.85 |             75.07 |         79.75 |         79.95 |          70.39 |        58.12 |           54.91 |             76.32 |             37.44 |         4.36 |             87.35 | swing              |              nan    |                nan    |               nan    |
|     19 | ILMN     | Illumina, Inc.                     | US       |               32.28 |             74.71 |         85.52 |         78.73 |          70.68 |        60.85 |           68.1  |             53.81 |             31.38 |         6.05 |             89.21 | short              |                3.77 |                  2.2  |               nan    |
|     20 | PARR     | PARR                               | US       |                3.78 |             74.27 |         78.76 |         77.09 |          71.45 |        64.69 |           57.97 |             79.9  |             60.46 |         6.92 |             69.89 | short              |               -5.71 |                 -1.13 |                -0.95 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | SM       | SM Energy Company                          | US       |                7.67 |                  84.31 |                    78.93 |                 77.95 |              78.61 |                66.17 |                   33.83 |           84.38 |             59.96 |       0.167 |         nan |       nan |        4.87 |         4.71 |          6.77 |        0.64 |                 nan |              nan |                  12 |                  0.63 |
|            2 | SNDK     | Sandisk Corporation                        | US       |              206.09 |                  79.8  |                    77.73 |                 77.21 |              77.33 |                71.45 |                   28.55 |           80.27 |             70.07 |       0.033 |         nan |       nan |       18.37 |         6.1  |         20.62 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | SWON.SW  | SoftwareOne Holding AG                     | EUROPE   |                2.11 |                  83.91 |                    77.12 |                 75.79 |              78.83 |                63.56 |                   36.44 |           72.11 |             69.77 |       0.226 |         nan |       nan |       12.05 |        10.96 |         51.69 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|            4 | BBY      | Best Buy Co., Inc.                         | US       |               17.29 |                  86.89 |                    76.82 |                 73.34 |              78.85 |                55.74 |                   44.26 |           66    |             62.51 |       0.071 |         nan |       nan |        8.24 |        13.11 |         15.38 |        1.73 |                 nan |              nan |                  12 |                  0.63 |
|            5 | DHL.DE   | DHL AG                                     | EUROPE   |               62.58 |                  88.61 |                    75.69 |                 71.05 |              80.99 |                66.98 |                   33.02 |           53.73 |             51.26 |       0.087 |         nan |       nan |       10.35 |        14.84 |         17.19 |        2.57 |                 nan |              nan |                  12 |                  0.63 |
|            6 | CRM      | Salesforce, Inc.                           | US       |              174.25 |                  83.46 |                    75.61 |                 72.35 |              76.6  |                57.29 |                   42.71 |           67.6  |             61.97 |       0.089 |         nan |       nan |       17.9  |        15.17 |         22.93 |        0.84 |                 nan |              nan |                  12 |                  0.63 |
|            7 | NEM      | Newmont Corporation                        | US       |              114.27 |                  77.8  |                    75.22 |                 74.98 |              73.95 |                72.94 |                   27.06 |           87.28 |             48.04 |       0.067 |         nan |       nan |        7.49 |        12.2  |         15.36 |        2.78 |                 nan |              nan |                  12 |                  0.63 |
|            8 | UMI.BR   | Umicore SA                                 | EUROPE   |                5.33 |                  87.48 |                    74.64 |                 71.04 |              78.46 |                54    |                   46    |           59.81 |             57.46 |       0.1   |         nan |       nan |        5    |        12.27 |         11.02 |        2.62 |                 nan |              nan |                  12 |                  0.63 |
|            9 | BMY      | Bristol-Myers Squibb Company               | US       |              111.91 |                  73.09 |                    74.32 |                 73.43 |              72.39 |                77.4  |                   22.6  |           80.73 |             58.33 |       0.063 |         nan |       nan |        8.58 |         9.57 |         14    |       17.71 |                 nan |              nan |                  12 |                  0.63 |
|           10 | NWL.MI   | NewPrinces S.p.A.                          | EUROPE   |                0.77 |                  81.51 |                    73.52 |                 72.89 |              75.97 |                76.63 |                   23.37 |           77.9  |             34.93 |       0.61  |         nan |       nan |        4.41 |      -134.16 |          2.31 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           11 | OXY      | Occidental Petroleum Corporation           | US       |               51.67 |                  73.01 |                    73.42 |                 73.02 |              72.78 |                77.15 |                   22.85 |           76.44 |             63.25 |       0.064 |         nan |       nan |        5.74 |        14.69 |         17.49 |        1.19 |                 nan |              nan |                  12 |                  0.63 |
|           12 | PFE      | Pfizer Inc.                                | US       |              137.35 |                  81.59 |                    73.16 |                 69.1  |              74.95 |                65.99 |                   34.01 |           63.97 |             43.31 |       0.079 |         nan |       nan |        8.26 |         9.54 |         35.9  |       12.56 |                 nan |              nan |                  11 |                  0.58 |
|           13 | BION.SW  | BB Biotech AG                              | EUROPE   |                3.06 |                  76.12 |                    73.02 |                 71.52 |              72.52 |                80.4  |                   19.6  |           81.38 |             32.42 |       0.853 |         nan |       nan |      nan    |       -79.82 |          2.14 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | PBR-A    | PBR-A                                      | US       |              113.06 |                  68.84 |                    72.59 |                 73.84 |              71.71 |                75.53 |                   24.47 |           74.8  |             85.54 |     nan     |         nan |       nan |      nan    |         4.71 |          4.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | VZ       | Verizon Communications Inc.                | US       |              175.07 |                  85.63 |                    72.59 |                 67.46 |              75.9  |                52.67 |                   47.33 |           55.49 |             47.69 |       0.087 |         nan |       nan |        7.71 |         9.15 |         12.96 |        0.88 |                 nan |              nan |                  12 |                  0.63 |
|           15 | MDT      | Medtronic plc                              | OTHER    |              103.46 |                  74.86 |                    72.28 |                 70.13 |              70.37 |                68.87 |                   31.13 |           80    |             40.77 |       0.046 |         nan |       nan |       13.32 |        14.48 |         22.85 |        1.66 |                 nan |              nan |                  12 |                  0.63 |
|           16 | CTSH     | Cognizant Technology Solutions Corporation | US       |               24.3  |                  84.38 |                    71.9  |                 65.86 |              77.01 |                58.66 |                   41.34 |           42.14 |             57.03 |       0.079 |         nan |       nan |        7.16 |         9.79 |         13.28 |        0.9  |                 nan |              nan |                  12 |                  0.63 |
|           17 | FANG     | Diamondback Energy, Inc.                   | US       |               48.08 |                  74.49 |                    70.74 |                 68.83 |              71.39 |                61.75 |                   38.25 |           64.33 |             66.41 |       0.091 |         nan |       nan |        6.23 |        10.55 |         37.02 |       23.36 |                 nan |              nan |                  12 |                  0.63 |
|           18 | EPAM     | EPAM Systems, Inc.                         | US       |                5.27 |                  91.08 |                    70.65 |                 62.69 |              77.18 |                45.83 |                   54.17 |           39.2  |             33.55 |       0.108 |         nan |       nan |        7.17 |         8.33 |         15.89 |        0.63 |                 nan |              nan |                  11 |                  0.58 |
|           19 | AMS.MC   | Amadeus IT Group, S.A.                     | EUROPE   |               23.44 |                  80.81 |                    70.65 |                 67.46 |              72.12 |                54.36 |                   45.64 |           66.88 |             41.45 |       0.124 |         nan |       nan |       10.51 |        14.41 |         18.42 |        1.29 |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                  | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:--------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | SM       | SM Energy Company                     | US       |                7.67 |                  84.31 |                    78.93 |                 77.95 |              78.61 |                66.17 |                   33.83 |           84.38 |             59.96 |       0.167 |         nan |       nan |        4.87 |         4.71 |          6.77 |        0.64 |                 nan |              nan |                  12 |                  0.63 |
|            2 | SNDK     | Sandisk Corporation                   | US       |              206.09 |                  79.8  |                    77.73 |                 77.21 |              77.33 |                71.45 |                   28.55 |           80.27 |             70.07 |       0.033 |         nan |       nan |       18.37 |         6.1  |         20.62 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | SWON.SW  | SoftwareOne Holding AG                | EUROPE   |                2.11 |                  83.91 |                    77.12 |                 75.79 |              78.83 |                63.56 |                   36.44 |           72.11 |             69.77 |       0.226 |         nan |       nan |       12.05 |        10.96 |         51.69 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|            7 | NEM      | Newmont Corporation                   | US       |              114.27 |                  77.8  |                    75.22 |                 74.98 |              73.95 |                72.94 |                   27.06 |           87.28 |             48.04 |       0.067 |         nan |       nan |        7.49 |        12.2  |         15.36 |        2.78 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PBR-A    | PBR-A                                 | US       |              113.06 |                  68.84 |                    72.59 |                 73.84 |              71.71 |                75.53 |                   24.47 |           74.8  |             85.54 |     nan     |         nan |       nan |      nan    |         4.71 |          4.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | BMY      | Bristol-Myers Squibb Company          | US       |              111.91 |                  73.09 |                    74.32 |                 73.43 |              72.39 |                77.4  |                   22.6  |           80.73 |             58.33 |       0.063 |         nan |       nan |        8.58 |         9.57 |         14    |       17.71 |                 nan |              nan |                  12 |                  0.63 |
|            4 | BBY      | Best Buy Co., Inc.                    | US       |               17.29 |                  86.89 |                    76.82 |                 73.34 |              78.85 |                55.74 |                   44.26 |           66    |             62.51 |       0.071 |         nan |       nan |        8.24 |        13.11 |         15.38 |        1.73 |                 nan |              nan |                  12 |                  0.63 |
|           11 | OXY      | Occidental Petroleum Corporation      | US       |               51.67 |                  73.01 |                    73.42 |                 73.02 |              72.78 |                77.15 |                   22.85 |           76.44 |             63.25 |       0.064 |         nan |       nan |        5.74 |        14.69 |         17.49 |        1.19 |                 nan |              nan |                  12 |                  0.63 |
|           10 | NWL.MI   | NewPrinces S.p.A.                     | EUROPE   |                0.77 |                  81.51 |                    73.52 |                 72.89 |              75.97 |                76.63 |                   23.37 |           77.9  |             34.93 |       0.61  |         nan |       nan |        4.41 |      -134.16 |          2.31 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | CRM      | Salesforce, Inc.                      | US       |              174.25 |                  83.46 |                    75.61 |                 72.35 |              76.6  |                57.29 |                   42.71 |           67.6  |             61.97 |       0.089 |         nan |       nan |       17.9  |        15.17 |         22.93 |        0.84 |                 nan |              nan |                  12 |                  0.63 |
|           13 | BION.SW  | BB Biotech AG                         | EUROPE   |                3.06 |                  76.12 |                    73.02 |                 71.52 |              72.52 |                80.4  |                   19.6  |           81.38 |             32.42 |       0.853 |         nan |       nan |      nan    |       -79.82 |          2.14 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            5 | DHL.DE   | DHL AG                                | EUROPE   |               62.58 |                  88.61 |                    75.69 |                 71.05 |              80.99 |                66.98 |                   33.02 |           53.73 |             51.26 |       0.087 |         nan |       nan |       10.35 |        14.84 |         17.19 |        2.57 |                 nan |              nan |                  12 |                  0.63 |
|            8 | UMI.BR   | Umicore SA                            | EUROPE   |                5.33 |                  87.48 |                    74.64 |                 71.04 |              78.46 |                54    |                   46    |           59.81 |             57.46 |       0.1   |         nan |       nan |        5    |        12.27 |         11.02 |        2.62 |                 nan |              nan |                  12 |                  0.63 |
|           45 | UMC      | United Microelectronics Corporation   | OTHER    |               53.5  |                  62.33 |                    67.05 |                 70.63 |              64.93 |                73.97 |                   26.03 |           85.5  |             67.39 |       0.019 |         nan |       nan |       -0.2  |        27.87 |         21.65 |        1.17 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SPXX     | Nuveen S&P 500 Dynamic Overwrite Fund | US       |                0.29 |                  52.41 |                    66.33 |                 70.42 |              62.58 |                85.78 |                   14.22 |           79.44 |             94.02 |     nan     |         nan |       nan |      nan    |       nan    |          4.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           20 | HAFN     | Hafnia Limited                        | OTHER    |                4.24 |                  76.32 |                    70.34 |                 70.37 |              73.54 |                61.9  |                   38.1  |           62.28 |             74.49 |       0.075 |         nan |       nan |        7.61 |        13.32 |          7.48 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|           23 | TALO     | Talos Energy Inc.                     | US       |                2.5  |                  74.93 |                    69.8  |                 70.3  |              73.91 |                70.02 |                   29.98 |           60.16 |             73.59 |       0.192 |         nan |       nan |        3.2  |        10.34 |        nan    |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           15 | MDT      | Medtronic plc                         | OTHER    |              103.46 |                  74.86 |                    72.28 |                 70.13 |              70.37 |                68.87 |                   31.13 |           80    |             40.77 |       0.046 |         nan |       nan |       13.32 |        14.48 |         22.85 |        1.66 |                 nan |              nan |                  12 |                  0.63 |
|           12 | PFE      | Pfizer Inc.                           | US       |              137.35 |                  81.59 |                    73.16 |                 69.1  |              74.95 |                65.99 |                   34.01 |           63.97 |             43.31 |       0.079 |         nan |       nan |        8.26 |         9.54 |         35.9  |       12.56 |                 nan |              nan |                  11 |                  0.58 |
|           17 | FANG     | Diamondback Energy, Inc.              | US       |               48.08 |                  74.49 |                    70.74 |                 68.83 |              71.39 |                61.75 |                   38.25 |           64.33 |             66.41 |       0.091 |         nan |       nan |        6.23 |        10.55 |         37.02 |       23.36 |                 nan |              nan |                  12 |                  0.63 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                             | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:---------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | PBR-A     | PBR-A                            | US       |              113.06 |                     0.03 |    -0.01 |      0.17 |                  60.96 |                        76.27 |         78.66 |         72.82 |          70.47 |        74.19 |           74.8  |             85.54 |         4.64 |
|               2 | AVAH      | Aveanna Healthcare Holdings Inc. | US       |                2.66 |                     0.03 |     0.01 |      0.06 |                  52.12 |                        75.19 |         81.67 |         84.76 |          79.17 |        73.25 |           69.5  |             73.96 |         7.25 |
|               3 | NVDA      | NVIDIA Corporation               | US       |             4617.67 |                     0.05 |     0    |      0.01 |                  64.43 |                        71.93 |         68.82 |         64.47 |          66.29 |        65.75 |           81.3  |             77.34 |         5.73 |
|               4 | C5H.IR    | Cairn Homes plc                  | EUROPE   |                1.68 |                     0.05 |     0.01 |      0.09 |                  63.69 |                        71.5  |         74.06 |         64.8  |          65.6  |        67.83 |           82.22 |             56.49 |         2.76 |
|               5 | SWON.SW   | SoftwareOne Holding AG           | EUROPE   |                2.11 |                     0.04 |    -0.02 |      0.12 |                  67.69 |                        71.39 |         72.71 |         71.1  |          69.26 |        73.31 |           72.11 |             69.77 |         6.49 |
|               6 | TPRO.MI   | Technoprobe S.p.A.               | EUROPE   |               18.66 |                     0.06 |    -0.06 |      0.05 |                  86.72 |                        70.99 |         62.54 |         54.08 |          69    |        60.86 |           80.43 |             70.82 |         6.9  |
|               7 | CRM       | Salesforce, Inc.                 | US       |              174.25 |                     0.08 |     0    |      0.18 |                  55.03 |                        70.92 |         79.7  |         75.13 |          64.23 |        67.32 |           67.6  |             61.97 |         7.11 |
|               8 | VAR.OL    | Vår Energi ASA                   | EUROPE   |               12.17 |                     0.04 |    -0.01 |      0.06 |                  60.82 |                        70.43 |         70.77 |         69.31 |          69.57 |        68.4  |           82.67 |             62.62 |         4.31 |
|               9 | VWS.CO    | Vestas Wind Systems A/S          | EUROPE   |               27.43 |                     0.04 |    -0.03 |      0.01 |                  72.42 |                        69.7  |         64.55 |         69.2  |          67.32 |        59.62 |           65.92 |             73.66 |         6.15 |
|              10 | PR        | Permian Resources Corporation    | US       |               16.94 |                     0.05 |    -0.01 |      0.01 |                  69.81 |                        69.55 |         64.55 |         66.84 |          67.9  |        67.21 |           75.59 |             70.27 |         4.69 |
|              11 | SYENS.BR  | SYENS.BR                         | EUROPE   |                7.95 |                     0.05 |    -0.03 |     -0.02 |                  75.53 |                        69.33 |         49.57 |         64.34 |          63.67 |        54.8  |           78.58 |             67.42 |         5.37 |
|              12 | WT        | WisdomTree, Inc.                 | US       |                2.94 |                     0.11 |    -0.08 |     -0.02 |                  59.94 |                        68.94 |         52.6  |         66.86 |          69.8  |        59.86 |           80.74 |             69.11 |         6.03 |
|              13 | TTE.PA    | TTE.PA                           | EUROPE   |              174.16 |                     0.02 |    -0    |      0.02 |                  50.13 |                        68.44 |         67.56 |         59.99 |          63.24 |        66.36 |           78.5  |             76.3  |         2.83 |
|              14 | OSCR      | OSCR                             | US       |                8.61 |                     0.05 |    -0.02 |     -0.01 |                  75.66 |                        68.13 |         58.67 |         66.76 |          67.59 |        53.32 |           54.32 |             83.61 |         8.25 |
|              15 | SM        | SM Energy Company                | US       |                7.67 |                     0.1  |    -0.03 |      0.03 |                  49.36 |                        68.11 |         63.57 |         69.67 |          73.6  |        78.89 |           84.38 |             59.96 |         6.62 |
|              16 | SSL       | Sasol Limited                    | OTHER    |                7.9  |                     0.06 |    -0.03 |      0.17 |                  75.29 |                        68.04 |         74.3  |         67.25 |          63.51 |        64.4  |           52.55 |             60.59 |         4.81 |
|              17 | PNDORA.CO | Pandora A/S                      | EUROPE   |                8.02 |                     0.08 |     0    |      0.02 |                  54.82 |                        67.93 |         58.16 |         68.04 |          66.45 |        63.84 |           79.01 |             65.94 |         6.56 |
|              18 | CHYM      | Chime Financial, Inc.            | US       |               10.14 |                     0.11 |    -0.06 |     -0.07 |                  53.67 |                        67.69 |         50.85 |         76.05 |          71.34 |        61.45 |           49.19 |             78.54 |         7.86 |
|              19 | GEN       | Gen Digital Inc.                 | US       |               15.77 |                     0.04 |     0.01 |      0.1  |                  58.1  |                        67.63 |         74.84 |         73.16 |          66.29 |        67.56 |           62.92 |             59.43 |         5.57 |
|              20 | TALO      | Talos Energy Inc.                | US       |                2.5  |                     0.06 |    -0.02 |     -0    |                  71.51 |                        67.62 |         63.34 |         67.64 |          68.5  |        70.19 |           60.16 |             73.59 |         6.01 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | MU       | Micron Technology, Inc.      | US       |              962.51 |             68.92 |         64.57 |         61.1  |          75.03 |        73.28 |           84.16 |             63.14 |             53.78 |         7.99 |             88.87 | medium             |               -3.22 |                 -1.44 |                -1.44 |
|    nan | PAYX     | Paychex, Inc.                | US       |               36.16 |             57.22 |         46.76 |         58.11 |          56.32 |        58.55 |           65.75 |             37.11 |             61.41 |         4.86 |             89.15 | long               |               -6.9  |                nan    |               nan    |
|    nan | KMX      | CarMax, Inc.                 | US       |                7.22 |             49.63 |         46.13 |         58.62 |          52.51 |        46.74 |           45.48 |             39.16 |             42.36 |         7.15 |             87.56 | swing              |               -2.08 |                 -1.91 |               nan    |
|    nan | GVR.IR   | Glenveagh Properties PLC     | EUROPE   |                1.18 |             42.62 |         43.7  |         41.54 |          43.76 |        37.95 |           27.62 |             59.13 |             37.48 |         2.98 |             84.56 | medium             |              -21.47 |                 -4.17 |                -3.36 |
|    nan | COST     | Costco Wholesale Corporation | US       |              345.64 |             35.07 |         33.93 |         30.55 |          36.21 |        40.44 |           54.97 |             39.88 |             24.29 |         2.96 |             89.79 | long               |               -4.94 |                 -1.29 |                -0.87 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     12 | RBRK     | Rubrik, Inc.                           | US       |               19.35 |             76.33 |         87.86 |         83.91 |          68.75 |        52.64 |           48.39 |             80.44 |             22.1  |         8.37 |             85.93 | short              |               -0.08 |                  3.86 |                 3.34 |
|    241 | AVPT     | AvePoint, Inc.                         | US       |                2.49 |             57.6  |         64.82 |         61.68 |          53.51 |        50.98 |           59.37 |             44.47 |             40.26 |         7.03 |             87.41 | short              |                5.86 |                  3.74 |                 3.56 |
|     47 | TEVA     | Teva Pharmaceutical Industries Limited | OTHER    |               39.85 |             69.74 |         76.07 |         71.15 |          68.33 |        67.71 |           53.59 |             66.25 |             81.02 |         4.82 |             81.67 | short              |                5.7  |                  3.69 |                 2.66 |
|    226 | BRKR     | Bruker Corporation                     | US       |                8.38 |             58.02 |         71.27 |         60.15 |          55.89 |        49.43 |           43.16 |             34.48 |             46.94 |         7.28 |             88.35 | short              |                5.1  |                  3.68 |               nan    |
|     64 | ADPT     | Adaptive Biotechnologies Corporation   | US       |                3.97 |             67.74 |         73.51 |         73.13 |          62.36 |        49.99 |           45.97 |             45.67 |             28.23 |         7.87 |             80.64 | short              |              nan    |                  3.34 |                 2.7  |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    654 | DEC      | DEC    | US       |                0.84 |             34.56 |         32.12 |         32.74 |          36.38 |        48.47 |           48.45 |              8.67 |             76.54 |         5.6  |             69.89 | long               |              -12.71 |                 -4.63 |                -3.45 |
|    326 | HMY      | HMY    | US       |               10.88 |             54.02 |         46.3  |         49.87 |          58.18 |        63.31 |           81.54 |             26.99 |             61.07 |         8.19 |             68.7  | long               |               -4.01 |                 -4.4  |               nan    |
|    682 | BBWI     | BBWI   | US       |                3.02 |             28.89 |         27.51 |         20.4  |          30.28 |        43.69 |           44.68 |             15.52 |             73.1  |         7.74 |             69.14 | long               |               -9.23 |                 -4.4  |                -3.49 |
|    645 | AD       | AD     | US       |                2.78 |             34.96 |         52.93 |         34.55 |          35.33 |        34.58 |           47.4  |             42.17 |             10.89 |         3.46 |             68.07 | short              |              -20.7  |                 -4.07 |                -3.26 |
|    614 | IHS      | IHS    | US       |                2.49 |             39.08 |         58.34 |         39.9  |          37.62 |        38.25 |           44.7  |             33.06 |             27.59 |         1.2  |             66.93 | short              |              -19.64 |                 -4.01 |                -3.09 |

## Duplicate-security checks

- FRO.OL duplicates C5H.IR (security_id=ISIN:PLCTHQM00018)
- SHELL.AS duplicates C5H.IR (security_id=ISIN:PLCTHQM00018)
- KRX.IR duplicates C5H.IR (security_id=ISIN:PLCTHQM00018)
- LLOYL.XC duplicates LYG (security_id=ISIN:GB00B3KSB568)
- RPRX duplicates C5H.IR (security_id=ISIN:PLCTHQM00018)
- STG.CO duplicates VWS.CO (security_id=ISIN:SGXZ47063284)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.87

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
- Event watch (otherwise eligible): **5**
- Final eligible: **700**
- Eligible change vs previous stored run: **-6**

Top exclusion categories:
- liquidity: 233
- price: 180
- market_cap: 113
- price_history: 23
- data_confidence: 18
- duplicate_listing: 6
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| SWON.SW | 34 | 3 | 5 | 3 | 2 | value,pullback,quality_value |
| CRM | 37 | 6 | 7 | 9 | 2 | value,pullback,quality_value |
| AVAH | 2 | 38 | 2 | 21 | 2 | main,pullback |
| SM | 35 | 1 | 15 | 1 | 1 | value,quality_value |
| BBY | 36 | 4 |  | 6 | 1 | value,quality_value |
| SNDK | 85 | 2 | 30 | 2 | 1 | value,quality_value |
| BMY | 142 | 9 | 53 | 5 | 1 | value,quality_value |
| NEM | 143 | 7 | 54 | 4 | 1 | value,quality_value |
| NWL.MI | 173 | 10 |  | 8 | 1 | value,quality_value |
| DELL | 1 | 107 |  | 100 | 1 | main |
| HPE | 3 | 42 |  | 44 | 1 | main |
| FRO | 4 | 235 |  | 114 | 1 | main |
| DINO | 5 | 122 |  | 89 | 1 | main |
| KIN.BR | 6 | 319 |  | 198 | 1 | main |
| GRK.HE | 7 | 109 |  | 76 | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (DELL, HPE, FRO, DINO, KIN.BR, GRK.HE, NAT, VLO, HAFN)
- Adaptive in Value Top 10: **5** (SM, SNDK, BBY, DHL.DE, BMY)
- Adaptive in Quality Value Top 10: **4** (SM, SNDK, BMY, BBY)
- Adaptive in Pullback Top 10: **1** (TPRO.MI)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | SNDK | value+pullback | 73.73 | 79.80 | 65.80 | 80.27 | 70.07 | 71.45 | 65.88 |
| 2 | OXY | value+pullback | 73.27 | 73.01 | 72.57 | 76.44 | 63.25 | 77.15 | 57.05 |
| 3 | SWON.SW | value+pullback | 72.60 | 83.91 | 67.69 | 72.11 | 69.77 | 63.56 | 71.90 |
| 4 | NEM | value+pullback | 71.04 | 77.80 | 60.87 | 87.28 | 48.04 | 72.94 | 61.90 |
| 5 | TALO | value+pullback | 70.74 | 74.93 | 71.51 | 60.16 | 73.59 | 70.02 | 68.07 |
| 6 | BMY | value+pullback | 70.68 | 73.09 | 61.31 | 80.73 | 58.33 | 77.40 | 62.02 |
| 7 | FANG | value+pullback | 69.53 | 74.49 | 74.18 | 64.33 | 66.41 | 61.75 | 54.55 |
| 8 | SM | value+pullback | 69.52 | 84.31 | 49.36 | 84.38 | 59.96 | 66.17 | 71.64 |
| 9 | RSI | value+pullback | 69.29 | 61.97 | 76.61 | 74.16 | 55.24 | 74.50 | 50.45 |
| 10 | BION.SW | value+pullback | 68.87 | 76.12 | 58.02 | 81.38 | 32.42 | 80.40 | 58.92 |
| 11 | SO | value+pullback | 68.86 | 69.73 | 71.70 | 82.61 | 37.90 | 69.16 | 42.36 |
| 12 | DX | value+pullback | 68.81 | 61.25 | 73.76 | 69.13 | 72.35 | 71.93 | 50.27 |
| 13 | UMI.BR | value+pullback | 68.72 | 87.48 | 67.81 | 59.81 | 57.46 | 54.00 | 61.80 |
| 14 | GTX | value+pullback | 68.58 | 66.32 | 76.60 | 73.67 | 58.56 | 63.16 | 56.29 |
| 15 | VZ | value+pullback | 68.54 | 85.63 | 76.91 | 55.49 | 47.69 | 52.67 | 49.09 |
| 16 | PFE | value+pullback | 68.18 | 81.59 | 66.33 | 63.97 | 43.31 | 65.99 | 54.54 |
| 17 | TAL | value+pullback | 68.15 | 66.48 | 64.86 | 85.92 | 40.81 | 75.09 | 55.27 |
| 18 | PIRC.MI | value+pullback | 67.60 | 74.34 | 66.87 | 55.59 | 63.34 | 69.51 | 55.07 |
| 19 | TDS | value+pullback | 67.59 | 64.25 | 76.89 | 47.92 | 75.04 | 72.02 | 47.81 |
| 20 | VST | value+pullback | 67.50 | 86.01 | 77.00 | 49.28 | 41.77 | 54.41 | 40.16 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 85.2 | 1 / 9 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 84.7 | 4 / 21 |
| Top 50 | 50/50 | 50/50 | 50/50 | 50/50 | 0/50 | 84.9 | 9 / 41 |

Top-10 market-cap mix: small_1_5b=5, mid_5_20b=2, large_20_100b=1, mega_100b_plus=2
