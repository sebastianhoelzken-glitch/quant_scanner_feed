# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-16

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

- **EUROPE:** 77.8/100
- **OTHER:** 80.9/100
- **US:** 77.6/100

## Main multi-horizon ranking

|   rank | symbol   | name                             | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | KIN.BR   | Kinepolis Group NV               | EUROPE   |                1.31 |             84.09 |         86.86 |         86.6  |          81.59 |        75.98 |           93.79 |             76.69 |             43.82 |         3.78 |             84.75 | short              |                2.09 |                  1.12 |                 0.78 |
|      2 | AVAH     | Aveanna Healthcare Holdings Inc. | US       |                2.7  |             81.92 |         85.88 |         85.7  |          78.14 |        71.46 |           67.45 |             74.57 |             63.93 |         7.36 |             87.56 | short              |               -1.3  |                  1.9  |                 1.77 |
|      3 | DINO     | HF Sinclair Corporation          | US       |               17.28 |             80.7  |         82.44 |         85.79 |          78.96 |        71.66 |           61.73 |             78.3  |             70.98 |         5.37 |             85.41 | swing              |               -0.83 |                nan    |               nan    |
|      4 | FRO      | Frontline plc                    | OTHER    |                9.95 |             80.55 |         83.59 |         81.79 |          79.32 |        73.2  |           85.87 |             75.4  |             42.5  |         5.23 |             84.96 | short              |               -5.75 |                 -0.65 |                -1.45 |
|      5 | NAT      | Nordic American Tankers Limited  | OTHER    |                1.44 |             80.55 |         85.26 |         83    |          78.09 |        70.21 |           85.69 |             69.67 |             31.17 |         5.23 |             83.93 | short              |               -1.54 |                  0.97 |               nan    |
|      6 | MPC      | Marathon Petroleum Corporation   | US       |               99.9  |             79.88 |         82.37 |         84.71 |          77.38 |        68.26 |           63.71 |             77.84 |             55.48 |         4.75 |             86.94 | swing              |               -7.37 |                nan    |               nan    |
|      7 | CMBT.BR  | Cmb.Tech NV                      | EUROPE   |                4.93 |             79.58 |         82.18 |         81.79 |          77.38 |        69.36 |           71.66 |             78.59 |             47.7  |         4.14 |             83.78 | short              |               -3.75 |                  1.34 |                 0.15 |
|      8 | SM       | SM Energy Company                | US       |                8.5  |             79.36 |         82.01 |         79.72 |          77.02 |        79    |           83.33 |             60.02 |             80.78 |         6.68 |             87.98 | short              |               -6.02 |                 -0.24 |                -0.4  |
|      9 | HAFN     | Hafnia Limited                   | OTHER    |                4.1  |             78.76 |         81.86 |         81.53 |          75.99 |        74.13 |           70.87 |             74.87 |             72.9  |         4.09 |             83.9  | short              |                1.91 |                  1.93 |               nan    |
|     10 | VLO      | Valero Energy Corporation        | US       |               98.99 |             78.41 |         81.69 |         82.85 |          75.14 |        65.24 |           62    |             74.26 |             48.39 |         4.39 |             87.49 | swing              |               -7.49 |                 -1.31 |               nan    |
|     11 | DHT      | DHT Holdings, Inc.               | OTHER    |                3.09 |             77.89 |         82.81 |         79.44 |          76.33 |        71.9  |           80.69 |             77.64 |             46.58 |         5.13 |             84.79 | short              |               -7.7  |                  0.39 |                -0.25 |
|     12 | DK       | Delek US Holdings, Inc.          | US       |                4.14 |             77.37 |         85.91 |         82.61 |          72.14 |        61.23 |           39.98 |             75    |             65.48 |         7.31 |             83.57 | short              |               -6.89 |                 -0.87 |                -0.78 |
|     13 | GRK.HE   | GRK Infra Oyj                    | EUROPE   |                1.03 |             76.96 |         80.3  |         79.71 |          74.22 |        64.58 |           56.01 |             81.52 |             54.22 |         4.23 |             84.64 | short              |                6.96 |                  1.34 |               nan    |
|     14 | CHYM     | Chime Financial, Inc.            | US       |               11.02 |             76.94 |         81.05 |         82.72 |          72.84 |        63.27 |           55.6  |             78.62 |             49.37 |         7.9  |             87.8  | swing              |               10.25 |                  2.48 |                 1.98 |
|     15 | PSX      | Phillips 66                      | US       |               91.98 |             76.1  |         80.72 |         81.44 |          71.49 |        59.16 |           52.45 |             77.27 |             39.87 |         4.42 |             87.39 | swing              |              nan    |                nan    |               nan    |
|     16 | TALO     | Talos Energy Inc.                | US       |                2.65 |             75.9  |         82.91 |         78.5  |          73.3  |        71.32 |           61.07 |             74.04 |             77.37 |         6.02 |             82.5  | short              |               -3.69 |                nan    |               nan    |
|     17 | RBRK     | Rubrik, Inc.                     | US       |               18.46 |             75.79 |         82.48 |         82.07 |          69.5  |        53.29 |           53.71 |             81.18 |             17.11 |         8.42 |             85.93 | short              |                3.54 |                  3.89 |                 3.39 |
|     18 | VAR.OL   | Vår Energi ASA                   | EUROPE   |               12.63 |             75.71 |         79.03 |         76.83 |          74.58 |        71.86 |           85.94 |             62.71 |             46.91 |         4.35 |             86.39 | short              |                5.98 |                  1.71 |                 0.51 |
|     19 | EQNR     | Equinor ASA                      | OTHER    |               93.94 |             75.34 |         78.59 |         77.03 |          73.66 |        72.83 |           68.15 |             68.75 |             71.08 |         5.23 |             84.61 | short              |               -2.03 |                 -0.5  |                -0.91 |
|     20 | DELL     | DELL                             | US       |              299.23 |             74.98 |         81.64 |         76.68 |          73.28 |        60    |           71.24 |             80.34 |             23.12 |         7.97 |             70.16 | short              |               -7    |                  0.01 |                 0.09 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                               | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-----------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BBY       | Best Buy Co., Inc.                 | US       |               16.93 |                  91.6  |                    79.83 |                 75.78 |              82.94 |                59.37 |                   40.63 |           64.86 |             62.95 |       0.072 |         nan |       nan |        8.13 |        12.93 |         15.78 |        1.77 |                 nan |              nan |                  12 |                  0.63 |
|            2 | CRM       | Salesforce, Inc.                   | US       |              182.19 |                  83.9  |                    77.03 |                 74.29 |              77.63 |                58.88 |                   41.12 |           71.08 |             66.2  |       0.084 |         nan |       nan |       18.71 |        15.96 |         23.41 |        0.87 |                 nan |              nan |                  12 |                  0.63 |
|            3 | EOG       | EOG Resources, Inc.                | US       |               69.83 |                  76.71 |                    75.6  |                 74.25 |              75.1  |                80.36 |                   19.64 |           78.29 |             54.01 |       0.056 |         nan |       nan |        5.79 |        10.44 |         11.96 |        1.41 |                 nan |              nan |                  12 |                  0.63 |
|            4 | BMY       | Bristol-Myers Squibb Company       | US       |              112.73 |                  77.41 |                    75.02 |                 73.4  |              73.77 |                70.39 |                   29.61 |           79.85 |             53.64 |       0.062 |         nan |       nan |        8.67 |         9.72 |         14.13 |       17.72 |                 nan |              nan |                  12 |                  0.63 |
|            5 | NEM       | Newmont Corporation                | US       |              113.31 |                  74.64 |                    74.79 |                 75.38 |              72.33 |                76.46 |                   23.54 |           92.31 |             48.27 |       0.067 |         nan |       nan |        7.48 |        12.18 |         15.52 |        2.78 |                 nan |              nan |                  12 |                  0.63 |
|            6 | DTG.DE    | Daimler Truck Holding AG           | EUROPE   |               32.87 |                  79.34 |                    74.07 |                 72.62 |              77.44 |                73.87 |                   26.13 |           61.23 |             70.16 |       0.165 |         nan |       nan |       13.86 |         9.01 |         29.82 |        0.34 |                 nan |              nan |                  12 |                  0.63 |
|            7 | PFE       | Pfizer Inc.                        | US       |              135.97 |                  84.12 |                    73.79 |                 69.35 |              76.07 |                62.34 |                   37.66 |           62.91 |             42.78 |       0.08  |         nan |       nan |        8.24 |         9.51 |         36.73 |       12.68 |                 nan |              nan |                  11 |                  0.58 |
|            8 | VTRS      | Viatris Inc.                       | US       |               16.56 |                  90.79 |                    73.28 |                 68.01 |              78.59 |                46.69 |                   53.31 |           51.74 |             48.12 |       0.14  |         nan |       nan |        7.28 |         6.26 |        nan    |        1.05 |                 nan |              nan |                  11 |                  0.58 |
|            9 | HAFN      | Hafnia Limited                     | OTHER    |                4.1  |                  79.53 |                    73.07 |                 73.66 |              75.46 |                59.49 |                   40.51 |           70.87 |             74.87 |       0.077 |         nan |       nan |        7.44 |        12.99 |          7.18 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|           10 | BION.SW   | BB Biotech AG                      | EUROPE   |                3.03 |                  74.41 |                    72.49 |                 71.44 |              71.29 |                80.85 |                   19.15 |           84.35 |             31.58 |       0.865 |         nan |       nan |      nan    |       -78.75 |          2.11 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           11 | ADT       | ADT Inc.                           | US       |                4.49 |                  83.28 |                    72.47 |                 69.95 |              75.23 |                56.77 |                   43.23 |           65.54 |             50.52 |       0.231 |         nan |       nan |        4.8  |         7.21 |          9.86 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|          nan | PBR-A     | PBR-A                              | US       |              116.02 |                  70.24 |                    72.35 |                 73    |              72.43 |                73.26 |                   26.74 |           69.64 |             86.64 |     nan     |         nan |       nan |      nan    |         4.87 |          4.82 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | AMS.MC    | Amadeus IT Group, S.A.             | EUROPE   |               22.7  |                  82.87 |                    72.22 |                 68.82 |              74.18 |                57.36 |                   42.64 |           66.57 |             41.91 |       0.128 |         nan |       nan |       10.22 |        13.95 |         17.83 |        1.26 |                 nan |              nan |                  12 |                  0.63 |
|           13 | GEN       | Gen Digital Inc.                   | US       |               16.19 |                  81.2  |                    72.21 |                 70.06 |              73.84 |                51.97 |                   48.03 |           66.74 |             60.26 |       0.083 |         nan |       nan |       10.93 |         9.44 |         18.37 |        1.58 |                 nan |              nan |                  12 |                  0.63 |
|           14 | CARL-B.CO | Carlsberg A/S                      | EUROPE   |               15.3  |                  83.41 |                    72.08 |                 68.74 |              72.75 |                53.76 |                   46.24 |           74.49 |             30.15 |       0.068 |         nan |       nan |        9.11 |        12.44 |         17.94 |        3.59 |                 nan |              nan |                  11 |                  0.58 |
|           15 | TAL       | TAL Education Group                | OTHER    |                5.64 |                  67.96 |                    71.72 |                 73.94 |              69.16 |                80    |                   20    |           90.43 |             58.29 |       0.065 |         nan |       nan |        8.37 |        10.03 |          7.34 |        2.71 |                 nan |              nan |                  10 |                  0.53 |
|           16 | HPE       | Hewlett Packard Enterprise Company | US       |               64.23 |                  76.29 |                    71.44 |                 69.77 |              72.16 |                51.7  |                   48.3  |           63.22 |             79.18 |       0.064 |         nan |       nan |       12.82 |        12.15 |         28.51 |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|           17 | PPL       | PPL Corporation                    | US       |               21.65 |                  79.08 |                    71.4  |                 67.77 |              73.92 |                68.36 |                   31.64 |           59.63 |             46.82 |      -0.078 |         nan |       nan |       11.98 |        15.7  |         20.02 |        1.24 |                 nan |              nan |                  12 |                  0.63 |
|           18 | ARCO      | Arcos Dorados Holdings Inc.        | OTHER    |                1.42 |                  70.82 |                    71.37 |                 73.39 |              69.68 |                68.72 |                   31.28 |           86.96 |             63.13 |       0.079 |         nan |       nan |        5.82 |         9.05 |          6.43 |        0.54 |                 nan |              nan |                  12 |                  0.63 |
|           19 | VOE.VI    | Voestalpine AG                     | EUROPE   |                7.7  |                  82.81 |                    71.3  |                 69.41 |              74.1  |                52.42 |                   47.58 |           66.84 |             50.45 |       0.068 |         nan |       nan |        6.02 |         8.86 |         15.17 |        5.88 |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                               | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BBY      | Best Buy Co., Inc.                 | US       |               16.93 |                  91.6  |                    79.83 |                 75.78 |              82.94 |                59.37 |                   40.63 |           64.86 |             62.95 |       0.072 |         nan |       nan |        8.13 |        12.93 |         15.78 |        1.77 |                 nan |              nan |                  12 |                  0.63 |
|            5 | NEM      | Newmont Corporation                | US       |              113.31 |                  74.64 |                    74.79 |                 75.38 |              72.33 |                76.46 |                   23.54 |           92.31 |             48.27 |       0.067 |         nan |       nan |        7.48 |        12.18 |         15.52 |        2.78 |                 nan |              nan |                  12 |                  0.63 |
|            2 | CRM      | Salesforce, Inc.                   | US       |              182.19 |                  83.9  |                    77.03 |                 74.29 |              77.63 |                58.88 |                   41.12 |           71.08 |             66.2  |       0.084 |         nan |       nan |       18.71 |        15.96 |         23.41 |        0.87 |                 nan |              nan |                  12 |                  0.63 |
|            3 | EOG      | EOG Resources, Inc.                | US       |               69.83 |                  76.71 |                    75.6  |                 74.25 |              75.1  |                80.36 |                   19.64 |           78.29 |             54.01 |       0.056 |         nan |       nan |        5.79 |        10.44 |         11.96 |        1.41 |                 nan |              nan |                  12 |                  0.63 |
|           15 | TAL      | TAL Education Group                | OTHER    |                5.64 |                  67.96 |                    71.72 |                 73.94 |              69.16 |                80    |                   20    |           90.43 |             58.29 |       0.065 |         nan |       nan |        8.37 |        10.03 |          7.34 |        2.71 |                 nan |              nan |                  10 |                  0.53 |
|            9 | HAFN     | Hafnia Limited                     | OTHER    |                4.1  |                  79.53 |                    73.07 |                 73.66 |              75.46 |                59.49 |                   40.51 |           70.87 |             74.87 |       0.077 |         nan |       nan |        7.44 |        12.99 |          7.18 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|            4 | BMY      | Bristol-Myers Squibb Company       | US       |              112.73 |                  77.41 |                    75.02 |                 73.4  |              73.77 |                70.39 |                   29.61 |           79.85 |             53.64 |       0.062 |         nan |       nan |        8.67 |         9.72 |         14.13 |       17.72 |                 nan |              nan |                  12 |                  0.63 |
|           18 | ARCO     | Arcos Dorados Holdings Inc.        | OTHER    |                1.42 |                  70.82 |                    71.37 |                 73.39 |              69.68 |                68.72 |                   31.28 |           86.96 |             63.13 |       0.079 |         nan |       nan |        5.82 |         9.05 |          6.43 |        0.54 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PBR-A    | PBR-A                              | US       |              116.02 |                  70.24 |                    72.35 |                 73    |              72.43 |                73.26 |                   26.74 |           69.64 |             86.64 |     nan     |         nan |       nan |      nan    |         4.87 |          4.82 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                 | US       |              104.72 |                  57.96 |                    69.24 |                 72.96 |              65.09 |                81.81 |                   18.19 |           86.64 |             86.33 |     nan     |         nan |       nan |      nan    |         9.65 |         22.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | DTG.DE   | Daimler Truck Holding AG           | EUROPE   |               32.87 |                  79.34 |                    74.07 |                 72.62 |              77.44 |                73.87 |                   26.13 |           61.23 |             70.16 |       0.165 |         nan |       nan |       13.86 |         9.01 |         29.82 |        0.34 |                 nan |              nan |                  12 |                  0.63 |
|           21 | TALO     | Talos Energy Inc.                  | US       |                2.65 |                  75.12 |                    70.9  |                 71.49 |              75.07 |                75.42 |                   24.58 |           61.07 |             74.04 |       0.18  |         nan |       nan |        3.38 |        11.05 |        nan    |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           10 | BION.SW  | BB Biotech AG                      | EUROPE   |                3.03 |                  74.41 |                    72.49 |                 71.44 |              71.29 |                80.85 |                   19.15 |           84.35 |             31.58 |       0.865 |         nan |       nan |      nan    |       -78.75 |          2.11 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           22 | SM       | SM Energy Company                  | US       |                8.5  |                  69.54 |                    70.24 |                 70.63 |              67.48 |                63.36 |                   36.64 |           83.33 |             60.02 |       0.15  |         nan |       nan |        5.19 |         5.26 |          6.92 |        0.67 |                 nan |              nan |                  12 |                  0.63 |
|           13 | GEN      | Gen Digital Inc.                   | US       |               16.19 |                  81.2  |                    72.21 |                 70.06 |              73.84 |                51.97 |                   48.03 |           66.74 |             60.26 |       0.083 |         nan |       nan |       10.93 |         9.44 |         18.37 |        1.58 |                 nan |              nan |                  12 |                  0.63 |
|           37 | SHEL     | SHEL                               | US       |              244.9  |                  63.24 |                    68.48 |                 69.98 |              67.3  |                75.83 |                   24.17 |           71.87 |             81.17 |     nan     |         nan |       nan |      nan    |         9.57 |         10.67 |        1.63 |                 nan |              nan |                   6 |                  0.32 |
|           11 | ADT      | ADT Inc.                           | US       |                4.49 |                  83.28 |                    72.47 |                 69.95 |              75.23 |                56.77 |                   43.23 |           65.54 |             50.52 |       0.231 |         nan |       nan |        4.8  |         7.21 |          9.86 |      nan    |                 nan |              nan |                  11 |                  0.58 |
|           16 | HPE      | Hewlett Packard Enterprise Company | US       |               64.23 |                  76.29 |                    71.44 |                 69.77 |              72.16 |                51.7  |                   48.3  |           63.22 |             79.18 |       0.064 |         nan |       nan |       12.82 |        12.15 |         28.51 |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|           19 | VOE.VI   | Voestalpine AG                     | EUROPE   |                7.7  |                  82.81 |                    71.3  |                 69.41 |              74.1  |                52.42 |                   47.58 |           66.84 |             50.45 |       0.068 |         nan |       nan |        6.02 |         8.86 |         15.17 |        5.88 |                 nan |              nan |                  12 |                  0.63 |
|            7 | PFE      | Pfizer Inc.                        | US       |              135.97 |                  84.12 |                    73.79 |                 69.35 |              76.07 |                62.34 |                   37.66 |           62.91 |             42.78 |       0.08  |         nan |       nan |        8.24 |         9.51 |         36.73 |       12.68 |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                                | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AMC       | AMC                                 | US       |                1.97 |                     0.06 |    -0    |      0.05 |                  71.63 |                        76.36 |         63.28 |         71.13 |          73.62 |        71.7  |           80.29 |             93.26 |         9.72 |
|               2 | DELL      | DELL                                | US       |              299.23 |                     0.04 |     0.02 |      0.13 |                  57.47 |                        75.74 |         81.64 |         76.68 |          73.28 |        60    |           71.24 |             80.34 |         7.97 |
|               3 | BE        | Bloom Energy Corporation            | US       |               66.14 |                     0.06 |    -0.06 |      0.12 |                  83.78 |                        72.22 |         62.98 |         55.66 |          68.68 |        63.32 |           87.72 |             70.8  |         8.92 |
|               4 | SBLK      | Star Bulk Carriers Corp.            | OTHER    |                3.14 |                     0.04 |     0.01 |      0.07 |                  58.1  |                        72.19 |         76.15 |         72.42 |          73.99 |        73.56 |           81.52 |             60.62 |         4.46 |
|               5 | PBF       | PBF                                 | US       |                7.67 |                     0.05 |    -0.03 |     -0    |                  72.88 |                        72.18 |         63.84 |         75.97 |          73.21 |        64.63 |           51.1  |             86.96 |         7.87 |
|               6 | SB        | SB                                  | US       |                0.76 |                     0.06 |    -0.04 |      0.06 |                  77.53 |                        71.67 |         69.96 |         70.78 |          69.23 |        61.45 |           65.97 |             76.38 |         4.47 |
|               7 | CHEMM.CO  | ChemoMetec A/S                      | EUROPE   |                1.13 |                     0.06 |    -0.05 |      0.04 |                  83.9  |                        71.43 |         68.47 |         67.05 |          58.08 |        51.94 |           66.9  |             74.83 |         6.96 |
|               8 | SWON.SW   | SWON.SW                             | EUROPE   |                2.09 |                     0.05 |    -0.03 |      0.06 |                  74.07 |                        70.12 |         69.1  |         64.91 |          61.09 |        56.98 |           69.32 |             70.67 |         6.09 |
|               9 | TAL       | TAL Education Group                 | OTHER    |                5.64 |                     0.05 |    -0.01 |      0.01 |                  70.96 |                        69.5  |         64.05 |         59.95 |          59.79 |        67.72 |           90.43 |             58.29 |         6.23 |
|              10 | WT        | WisdomTree, Inc.                    | US       |                2.9  |                     0.12 |    -0.1  |     -0.04 |                  59.91 |                        69.3  |         49.55 |         66.61 |          70.42 |        61.07 |           82.89 |             69.56 |         6.12 |
|              11 | PLTR      | Palantir Technologies Inc.          | US       |              359.07 |                     0.07 |     0.01 |      0    |                  55.11 |                        69.16 |         65.5  |         66.64 |          60.75 |        58.93 |           90.06 |             63.76 |         8.06 |
|              12 | PNDORA.CO | Pandora A/S                         | EUROPE   |                8    |                     0.08 |    -0.02 |     -0.01 |                  61.07 |                        69.09 |         53.49 |         67.7  |          66.85 |        63.66 |           81.12 |             65.75 |         6.78 |
|              13 | DSFIR.AS  | DSFIR.AS                            | EUROPE   |               22.5  |                     0.04 |    -0.02 |      0.05 |                  69.04 |                        68.7  |         63.17 |         66.93 |          63.02 |        52.67 |           74.46 |             66.6  |         5.21 |
|              14 | NN.AS     | NN.AS                               | EUROPE   |               20.51 |                     0.02 |    -0.01 |      0.01 |                  49.58 |                        68.34 |         67.69 |         63.55 |          67.49 |        67.72 |           82.25 |             70.73 |         1.24 |
|              15 | HPE       | Hewlett Packard Enterprise Company  | US       |               64.23 |                     0.1  |    -0    |     -0.03 |                  43.75 |                        68.15 |         67.14 |         74.13 |          79.34 |        74.19 |           63.22 |             79.18 |         6.71 |
|              16 | AMV0.DE   | AMV0.DE                             | EUROPE   |                3.66 |                     0.05 |    -0.05 |      0.02 |                  82.85 |                        67.71 |         55.73 |         42.61 |          54.92 |        69.42 |           97.06 |             53.37 |         6.41 |
|              17 | HOOD      | Robinhood Markets, Inc.             | US       |               85.99 |                     0.11 |    -0.06 |      0.15 |                  51.18 |                        67.66 |         68.8  |         61.06 |          56.7  |        50.34 |           82.1  |             61.09 |         8.3  |
|              18 | UGP       | Ultrapar Participações S.A.         | OTHER    |                6.87 |                     0.02 |    -0    |      0.18 |                  47    |                        67.15 |         77.63 |         82.44 |          72.29 |        64.16 |           34.55 |             79.84 |         4.13 |
|              19 | UMC       | United Microelectronics Corporation | OTHER    |               46.93 |                     0.05 |    -0.01 |      0.11 |                  69.06 |                        67.12 |         64    |         58.79 |          71.37 |        66.95 |           72.61 |             68.26 |         7.57 |
|              20 | YEXT      | Yext, Inc.                          | US       |                0.55 |                     0.08 |     0    |      0.09 |                  57.84 |                        66.99 |         74.2  |         72.83 |          60.93 |        62.12 |           49.27 |             75.74 |         7.02 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | MU       | Micron Technology, Inc.      | US       |              907.15 |             64.24 |         42.08 |         55.69 |          74.5  |        72.78 |           85.27 |             61.56 |             51.38 |         8    |             88.87 | medium             |               -8.33 |                 -2.15 |               nan    |
|    nan | PAYX     | Paychex, Inc.                | US       |               36.47 |             54.92 |         55.32 |         59.67 |          54.51 |        53.71 |           64.78 |             38.22 |             44.32 |         5.06 |             85.23 | swing              |               -2.75 |                nan    |               nan    |
|    nan | KMX      | KMX                          | US       |                7.36 |             48.72 |         52.27 |         52.77 |          45.17 |        36.26 |           39.05 |             35.16 |             25.45 |         7.44 |             69.59 | swing              |              nan    |                 -2.03 |               nan    |
|    nan | BOL.PA   | Bolloré SE                   | EUROPE   |               10.41 |             44.76 |         49.75 |         44.4  |          45.12 |        41.32 |           35.87 |             55.99 |             32.3  |         8.5  |             81.83 | short              |                8.23 |                nan    |               nan    |
|    nan | EXO.AS   | Exor N.V.                    | EUROPE   |               23.35 |             42.16 |         56.13 |         47.32 |          37    |        31.97 |            8.19 |             59.91 |             44.67 |         3.01 |             75.12 | short              |               -9.34 |                nan    |               nan    |
|    nan | CAG      | Conagra Brands, Inc.         | US       |                6.22 |             39.69 |         36.89 |         39.82 |          39.55 |        48.15 |           42.46 |             34.49 |             73.35 |         5.54 |             88.05 | long               |              nan    |                 -2.05 |                -1.19 |
|    nan | COST     | Costco Wholesale Corporation | US       |              346.13 |             35.67 |         36.64 |         30.03 |          34.71 |        37.51 |           53.54 |             40.6  |             17.19 |         3.06 |             89.74 | long               |               -8.78 |                 -0.33 |                -0    |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     69 | SDGR     | Schrödinger, Inc.      | US       |                1.51 |             67.6  |         81.88 |         77.73 |          57.47 |        44.35 |           30.94 |             70.43 |             34.33 |         7.54 |             78.9  | short              |              nan    |                  4.26 |                 3.6  |
|     17 | RBRK     | Rubrik, Inc.           | US       |               18.46 |             75.79 |         82.48 |         82.07 |          69.5  |        53.29 |           53.71 |             81.18 |             17.11 |         8.42 |             85.93 | short              |                3.54 |                  3.89 |                 3.39 |
|     32 | GMAB     | Genmab A/S             | OTHER    |               18.18 |             72.94 |         77.48 |         76.36 |          69.52 |        67.58 |           86.47 |             66.78 |             38.28 |         4.49 |             84.8  | short              |              nan    |                  3.76 |                 2.87 |
|    307 | PST.MI   | Poste Italiane S.p.A.  | EUROPE   |               33.5  |             55.27 |         45.87 |         51.34 |          60.9  |        59.2  |           60.81 |             66.6  |             51.02 |         2.8  |             86.2  | medium             |              nan    |                  3.49 |                 3.13 |
|    201 | SONY     | Sony Group Corporation | OTHER    |              121.07 |             59.29 |         60.71 |         59.43 |          54.13 |        59.15 |           48.7  |             62.81 |             83.31 |         4.59 |             84.28 | short              |               12.31 |                  3.26 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    690 | HOS      | HOS                       | US       |                2.51 |             26.86 |         25.59 |         19.63 |          28.13 |        30.36 |           17.69 |              8.33 |             46.3  |         5.27 |             61.25 | long               |              -19.97 |                 -5.09 |               nan    |
|    654 | VZLA     | Vizsla Silver Corp.       | OTHER    |                1.16 |             34.85 |         43.65 |         36.71 |          32.99 |        30.63 |           33.95 |             41.66 |             15.38 |         8.42 |             66.82 | short              |              -17.79 |                 -4.43 |               nan    |
|    671 | UTG      | UTG                       | OTHER    |                2.87 |             32.07 |         25.96 |         25.3  |          38.18 |        47.25 |           51.29 |            nan    |             51.72 |         2.23 |             58.41 | long               |              -17.09 |                 -4.18 |                -3.13 |
|    489 | EGO      | Eldorado Gold Corporation | OTHER    |                9.08 |             47.42 |         47    |         50    |          47.84 |        44.68 |           44.75 |             44.13 |             28.21 |         8.43 |             84.5  | swing              |              -16.28 |                 -4.16 |                -3.01 |
|    604 | IHS      | IHS                       | US       |                2.48 |             39.71 |         59.24 |         41.48 |          37.94 |        37.71 |           41.04 |             32.26 |             32.5  |         2.09 |             66.93 | short              |              -18.64 |                 -4.05 |                -3.1  |

## Duplicate-security checks

- FRO.OL duplicates GL9.IR (security_id=ISIN:PLCTHQM00018)
- SHELL.AS duplicates GL9.IR (security_id=ISIN:PLCTHQM00018)
- IR5B.IR duplicates GL9.IR (security_id=ISIN:PLCTHQM00018)
- KRX.IR duplicates GL9.IR (security_id=ISIN:PLCTHQM00018)
- RPRX duplicates GL9.IR (security_id=ISIN:PLCTHQM00018)
- LYG duplicates LLOYL.XC (security_id=ISIN:GB00B3KSB568)
- UNA.AS duplicates GL9.IR (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.88

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
- Event watch (otherwise eligible): **7**
- Final eligible: **702**
- Eligible change vs previous stored run: **-14**

Top exclusion categories:
- liquidity: 232
- price: 180
- market_cap: 114
- price_history: 18
- data_confidence: 15
- duplicate_listing: 7
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| HAFN | 9 | 9 |  | 6 | 2 | main,value,quality_value |
| CRM | 25 | 2 |  | 3 | 1 | value,quality_value |
| BBY | 54 | 1 |  | 1 | 1 | value,quality_value |
| EOG | 101 | 3 |  | 4 | 1 | value,quality_value |
| NEM | 103 | 5 | 26 | 2 | 1 | value,quality_value |
| BMY | 140 | 4 | 57 | 7 | 1 | value,quality_value |
| TAL | 143 | 15 | 9 | 5 | 1 | pullback,quality_value |
| DTG.DE | 250 | 6 | 117 | 9 | 1 | value,quality_value |
| KIN.BR | 1 | 196 |  | 76 | 1 | main |
| AVAH | 2 | 36 |  | 27 | 1 | main |
| DINO | 3 | 113 |  | 92 | 1 | main |
| FRO | 4 | 163 |  | 77 | 1 | main |
| NAT | 5 | 188 |  | 84 | 1 | main |
| MPC | 6 | 26 |  | 19 | 1 | main |
| CMBT.BR | 7 | 230 |  | 131 | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (FRO, NAT, MPC, CMBT.BR, SM, HAFN, VLO)
- Adaptive in Value Top 10: **4** (BBY, EOG, VTRS, HAFN)
- Adaptive in Quality Value Top 10: **5** (BBY, EOG, HAFN, ARCO, TALO)
- Adaptive in Pullback Top 10: **1** (WT)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | ARCO | value+pullback | 75.32 | 70.82 | 83.88 | 86.96 | 63.13 | 68.72 | 51.24 |
| 2 | TAL | value+pullback | 73.52 | 67.96 | 70.96 | 90.43 | 58.29 | 80.00 | 62.00 |
| 3 | BMY | value+pullback | 72.04 | 77.41 | 69.57 | 79.85 | 53.64 | 70.39 | 62.12 |
| 4 | NEM | value+pullback | 72.00 | 74.64 | 62.56 | 92.31 | 48.27 | 76.46 | 64.31 |
| 5 | PPL | value+pullback | 71.33 | 79.08 | 81.23 | 59.63 | 46.82 | 68.36 | 37.75 |
| 6 | DTG.DE | value+pullback | 71.23 | 79.34 | 65.80 | 61.23 | 70.16 | 73.87 | 57.51 |
| 7 | GL9.IR | value+pullback | 70.50 | 68.57 | 75.33 | 71.38 | 65.47 | 69.22 | 55.77 |
| 8 | MS | value+pullback | 70.25 | 63.24 | 82.75 | 70.75 | 64.68 | 67.55 | 52.53 |
| 9 | SIKA.SW | value+pullback | 69.97 | 63.73 | 80.91 | 69.56 | 58.53 | 71.68 | 58.58 |
| 10 | BION.SW | value+pullback | 69.47 | 74.41 | 60.65 | 84.35 | 31.58 | 80.85 | 59.96 |
| 11 | GTX | value+pullback | 69.46 | 55.48 | 77.28 | 76.74 | 71.45 | 74.21 | 58.64 |
| 12 | AKZA.AS | value+pullback | 69.36 | 70.93 | 76.04 | 66.64 | 49.17 | 70.79 | 48.49 |
| 13 | PFE | value+pullback | 69.08 | 84.12 | 70.66 | 62.91 | 42.78 | 62.34 | 57.04 |
| 14 | AMS.MC | value+pullback | 69.08 | 82.87 | 74.30 | 66.57 | 41.91 | 57.36 | 49.29 |
| 15 | ADT | value+pullback | 68.95 | 83.28 | 70.92 | 65.54 | 50.52 | 56.77 | 52.73 |
| 16 | ZVRA | value+pullback | 68.68 | 67.54 | 78.41 | 76.16 | 37.81 | 68.07 | 52.48 |
| 17 | KODK | value+pullback | 68.53 | 60.63 | 66.82 | 59.46 | 94.73 | 76.21 | 62.97 |
| 18 | VOE.VI | value+pullback | 68.31 | 82.81 | 71.66 | 66.84 | 50.45 | 52.42 | 57.85 |
| 19 | VST | value+pullback | 68.23 | 86.01 | 82.89 | 50.00 | 42.39 | 49.85 | 37.15 |
| 20 | SBH | value+pullback | 67.99 | 78.97 | 74.50 | 65.29 | 42.14 | 58.34 | 55.27 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 85.2 | 3 / 7 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 85.0 | 8 / 17 |
| Top 50 | 50/50 | 50/50 | 49/50 | 49/50 | 0/50 | 85.0 | 17 / 33 |

Top-10 market-cap mix: small_1_5b=5, mid_5_20b=3, large_20_100b=2
