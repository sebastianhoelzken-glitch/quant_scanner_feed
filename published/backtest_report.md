# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             12 |      120 |                   -0.0078 |                     -0.0074 |     0.4417 |        -0.9197 |                    -0.0519 |                    0.0251 |                         -0.1095 | False    |
| short     |             20 |          65 |      10 |             12 |      120 |                   -0.0078 |                     -0.0074 |     0.4417 |        -0.9197 |                    -0.0519 |                    0.0251 |                         -0.1095 | False    |
| short     |             20 |          70 |      10 |             12 |      120 |                   -0.0078 |                     -0.0074 |     0.4417 |        -0.9197 |                    -0.0519 |                    0.0251 |                         -0.1095 | False    |
| short     |             20 |          75 |      10 |             12 |      104 |                   -0.0087 |                     -0.0038 |     0.4519 |        -0.9071 |                    -0.0519 |                    0.0251 |                         -0.1015 | False    |
| short     |             20 |          80 |      10 |             11 |       84 |                   -0.0087 |                      0.0004 |     0.5119 |        -0.7502 |                    -0.0519 |                    0.0449 |                         -0.0844 | False    |
| short     |             20 |          85 |      10 |              8 |       48 |                   -0.0415 |                     -0.023  |     0.4583 |        -2.5316 |                    -0.0863 |                   -0.0187 |                         -0.3075 | False    |
| short     |             20 |          90 |      10 |              3 |       18 |                   -0.007  |                      0.0077 |     0.6667 |        -0.234  |                    -0.0517 |                    0.0106 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.