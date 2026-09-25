# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             16 |      160 |                   -0.0051 |                      0      |     0.5    |        -0.6626 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          65 |      10 |             16 |      160 |                   -0.0051 |                      0      |     0.5    |        -0.6626 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          70 |      10 |             16 |      160 |                   -0.0051 |                      0      |     0.5    |        -0.6626 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          75 |      10 |             16 |      149 |                   -0.0064 |                     -0.001  |     0.4899 |        -0.7755 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          80 |      10 |             15 |      133 |                   -0.0063 |                      0.0022 |     0.5113 |        -0.6968 |                    -0.0604 |                    0.027  |                         -0.1318 | False    |
| short     |             20 |          85 |      10 |             13 |       71 |                   -0.0153 |                      0.0057 |     0.5211 |        -1.1127 |                    -0.0519 |                    0.0478 |                         -0.2393 | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0004 |                      0.0077 |     0.6842 |        -0.015  |                    -0.0517 |                    0.1169 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.