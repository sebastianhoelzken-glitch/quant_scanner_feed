# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              6 |       60 |                   -0.0007 |                      0.0054 |     0.5333 |        -0.0525 |                    -0.0224 |                    0.0192 |                         -0.0343 | False    |
| short     |             20 |          65 |      10 |              6 |       60 |                   -0.0007 |                      0.0054 |     0.5333 |        -0.0525 |                    -0.0224 |                    0.0192 |                         -0.0343 | False    |
| short     |             20 |          70 |      10 |              6 |       60 |                   -0.0007 |                      0.0054 |     0.5333 |        -0.0525 |                    -0.0224 |                    0.0192 |                         -0.0343 | False    |
| short     |             20 |          75 |      10 |              6 |       51 |                   -0.0038 |                      0.0001 |     0.5098 |        -0.266  |                    -0.0224 |                    0.0158 |                         -0.03   | False    |
| short     |             20 |          80 |      10 |              5 |       44 |                   -0.0017 |                      0.0063 |     0.5455 |        -0.1036 |                    -0.0224 |                    0.0158 |                         -0.0277 | False    |
| short     |             20 |          85 |      10 |              4 |       33 |                    0.0018 |                      0.0065 |     0.5758 |         0.088  |                    -0.0224 |                    0.0158 |                         -0.0224 | False    |
| short     |             20 |          90 |      10 |              3 |       15 |                    0.016  |                      0.0077 |     0.7333 |         0.6715 |                    -0.0517 |                    0.0329 |                          0      | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.