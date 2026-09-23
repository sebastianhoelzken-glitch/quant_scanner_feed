# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             13 |      130 |                   -0.0076 |                     -0.0006 |     0.4923 |        -0.8833 |                    -0.0519 |                    0.027  |                         -0.1145 | False    |
| short     |             20 |          65 |      10 |             13 |      130 |                   -0.0076 |                     -0.0006 |     0.4923 |        -0.8833 |                    -0.0519 |                    0.027  |                         -0.1145 | False    |
| short     |             20 |          70 |      10 |             13 |      130 |                   -0.0076 |                     -0.0006 |     0.4923 |        -0.8833 |                    -0.0519 |                    0.027  |                         -0.1145 | False    |
| short     |             20 |          75 |      10 |             13 |      120 |                   -0.0095 |                     -0.0006 |     0.4917 |        -1.0234 |                    -0.0519 |                    0.027  |                         -0.1129 | False    |
| short     |             20 |          80 |      10 |             12 |      112 |                   -0.0096 |                     -0.0005 |     0.5    |        -0.9757 |                    -0.0519 |                    0.0433 |                         -0.096  | False    |
| short     |             20 |          85 |      10 |             11 |       64 |                   -0.0321 |                     -0.0025 |     0.4844 |        -2.2424 |                    -0.0519 |                   -0.0086 |                         -0.2847 | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0004 |                      0.0077 |     0.6842 |        -0.015  |                    -0.0517 |                    0.1169 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.