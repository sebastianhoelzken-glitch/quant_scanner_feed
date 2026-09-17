# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              7 |       70 |                    0.0102 |                      0.0054 |     0.5429 |         0.8976 |                    -0.0224 |                    0.0407 |                         -0.0406 | False    |
| short     |             20 |          65 |      10 |              7 |       70 |                    0.0102 |                      0.0054 |     0.5429 |         0.8976 |                    -0.0224 |                    0.0407 |                         -0.0406 | False    |
| short     |             20 |          70 |      10 |              7 |       70 |                    0.0102 |                      0.0054 |     0.5429 |         0.8976 |                    -0.0224 |                    0.0407 |                         -0.0406 | False    |
| short     |             20 |          75 |      10 |              7 |       60 |                    0.0065 |                      0.0019 |     0.5167 |         0.4975 |                    -0.0224 |                    0.0407 |                         -0.0406 | False    |
| short     |             20 |          80 |      10 |              6 |       52 |                    0.0105 |                      0.0063 |     0.5577 |         0.7084 |                    -0.0224 |                    0.0601 |                         -0.0224 | False    |
| short     |             20 |          85 |      10 |              5 |       36 |                   -0.0066 |                      0.0033 |     0.5278 |        -0.3761 |                    -0.0224 |                    0.0158 |                         -0.0224 | False    |
| short     |             20 |          90 |      10 |              3 |       15 |                    0.016  |                      0.0077 |     0.7333 |         0.6715 |                    -0.0517 |                    0.0329 |                          0      | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.