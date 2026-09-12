# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              2 |       20 |                    0.0107 |                      0.0022 |     0.5    |         0.8933 |                     0.0022 |                    0.0192 |                               0 | False    |
| short     |             20 |          65 |      10 |              2 |       20 |                    0.0107 |                      0.0022 |     0.5    |         0.8933 |                     0.0022 |                    0.0192 |                               0 | False    |
| short     |             20 |          70 |      10 |              2 |       20 |                    0.0107 |                      0.0022 |     0.5    |         0.8933 |                     0.0022 |                    0.0192 |                               0 | False    |
| short     |             20 |          75 |      10 |              2 |       13 |                   -0.0014 |                     -0.01   |     0.3846 |        -0.0974 |                    -0.0137 |                    0.0022 |                               0 | False    |
| short     |             20 |          80 |      10 |              1 |        7 |                    0.01   |                     -0.01   |     0.4286 |         0.4474 |                     0.01   |                    0.01   |                               0 | False    |
| short     |             20 |          85 |      10 |              1 |        3 |                   -0.0312 |                     -0.0281 |     0      |        -2.5677 |                    -0.0312 |                   -0.0312 |                               0 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.