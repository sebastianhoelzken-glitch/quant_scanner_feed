# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              9 |       90 |                    0.003  |                      0.0019 |     0.5111 |         0.3056 |                    -0.0428 |                    0.0366 |                         -0.0773 | False    |
| short     |             20 |          65 |      10 |              9 |       90 |                    0.003  |                      0.0019 |     0.5111 |         0.3056 |                    -0.0428 |                    0.0366 |                         -0.0773 | False    |
| short     |             20 |          70 |      10 |              9 |       90 |                    0.003  |                      0.0019 |     0.5111 |         0.3056 |                    -0.0428 |                    0.0366 |                         -0.0773 | False    |
| short     |             20 |          75 |      10 |              9 |       81 |                    0.0004 |                     -0.0001 |     0.4938 |         0.0404 |                    -0.0428 |                    0.0366 |                         -0.0773 | False    |
| short     |             20 |          80 |      10 |              8 |       72 |                    0.0021 |                      0.0037 |     0.5278 |         0.1811 |                    -0.0428 |                    0.0366 |                         -0.0598 | False    |
| short     |             20 |          85 |      10 |              7 |       42 |                   -0.0241 |                     -0.0005 |     0.5    |        -1.5145 |                    -0.0536 |                    0.0045 |                         -0.1274 | False    |
| short     |             20 |          90 |      10 |              3 |       18 |                   -0.007  |                      0.0077 |     0.6667 |        -0.234  |                    -0.0517 |                    0.0106 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.