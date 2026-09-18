# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              8 |       80 |                    0.0095 |                      0      |     0.5    |         0.8846 |                    -0.0224 |                    0.0243 |                         -0.0406 | False    |
| short     |             20 |          65 |      10 |              8 |       80 |                    0.0095 |                      0      |     0.5    |         0.8846 |                    -0.0224 |                    0.0243 |                         -0.0406 | False    |
| short     |             20 |          70 |      10 |              8 |       80 |                    0.0095 |                      0      |     0.5    |         0.8846 |                    -0.0224 |                    0.0243 |                         -0.0406 | False    |
| short     |             20 |          75 |      10 |              8 |       71 |                    0.0055 |                     -0.001  |     0.4789 |         0.4745 |                    -0.0224 |                    0.0243 |                         -0.0406 | False    |
| short     |             20 |          80 |      10 |              7 |       61 |                    0.0069 |                      0.0001 |     0.5082 |         0.5294 |                    -0.0288 |                    0.0243 |                         -0.0288 | False    |
| short     |             20 |          85 |      10 |              6 |       39 |                   -0.008  |                      0.0001 |     0.5128 |        -0.4805 |                    -0.0241 |                    0.0158 |                         -0.0262 | False    |
| short     |             20 |          90 |      10 |              3 |       15 |                    0.016  |                      0.0077 |     0.7333 |         0.6715 |                    -0.0517 |                    0.0329 |                          0      | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.