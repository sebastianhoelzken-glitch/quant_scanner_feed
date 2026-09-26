# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             16 |      160 |                   -0.0168 |                     -0.0148 |     0.4438 |        -2.158  |                    -0.0652 |                    0.027  |                         -0.2548 | False    |
| short     |             20 |          65 |      10 |             16 |      160 |                   -0.0168 |                     -0.0148 |     0.4438 |        -2.158  |                    -0.0652 |                    0.027  |                         -0.2548 | False    |
| short     |             20 |          70 |      10 |             16 |      160 |                   -0.0168 |                     -0.0148 |     0.4438 |        -2.158  |                    -0.0652 |                    0.027  |                         -0.2548 | False    |
| short     |             20 |          75 |      10 |             16 |      153 |                   -0.0191 |                     -0.0211 |     0.4314 |        -2.3713 |                    -0.0652 |                    0.027  |                         -0.2548 | False    |
| short     |             20 |          80 |      10 |             15 |      142 |                   -0.0192 |                     -0.0212 |     0.4366 |        -2.2449 |                    -0.0652 |                    0.027  |                         -0.2436 | False    |
| short     |             20 |          85 |      10 |             14 |       77 |                   -0.0316 |                     -0.042  |     0.4286 |        -2.605  |                    -0.079  |                    0.0071 |                         -0.3479 | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0012 |                      0.0077 |     0.6842 |        -0.0433 |                    -0.0517 |                    0.1015 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.