# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             13 |      130 |                   -0.0058 |                     -0.0038 |     0.4231 |        -0.7188 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          65 |      10 |             13 |      130 |                   -0.0058 |                     -0.0038 |     0.4231 |        -0.7188 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          70 |      10 |             13 |      130 |                   -0.0058 |                     -0.0038 |     0.4231 |        -0.7188 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          75 |      10 |             13 |      110 |                   -0.0057 |                     -0.0037 |     0.4364 |        -0.6095 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          80 |      10 |             12 |       86 |                   -0.005  |                      0.0019 |     0.5116 |        -0.4272 |                    -0.0519 |                    0.0449 |                         -0.0844 | False    |
| short     |             20 |          85 |      10 |              8 |       50 |                   -0.0355 |                     -0.0025 |     0.48   |        -2.1553 |                    -0.0519 |                   -0.0157 |                         -0.2393 | False    |
| short     |             20 |          90 |      10 |              3 |       18 |                   -0.007  |                      0.0077 |     0.6667 |        -0.234  |                    -0.0517 |                    0.0106 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.