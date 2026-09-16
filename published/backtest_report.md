# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              7 |       70 |                    0.0021 |                      0.0041 |     0.5286 |         0.1907 |                    -0.0224 |                    0.0192 |                         -0.0239 | False    |
| short     |             20 |          65 |      10 |              7 |       70 |                    0.0021 |                      0.0041 |     0.5286 |         0.1907 |                    -0.0224 |                    0.0192 |                         -0.0239 | False    |
| short     |             20 |          70 |      10 |              7 |       70 |                    0.0021 |                      0.0041 |     0.5286 |         0.1907 |                    -0.0224 |                    0.0192 |                         -0.0239 | False    |
| short     |             20 |          75 |      10 |              7 |       59 |                   -0.0033 |                     -0.0039 |     0.4746 |        -0.2624 |                    -0.0224 |                    0.0158 |                         -0.0294 | False    |
| short     |             20 |          80 |      10 |              6 |       46 |                    0.001  |                      0.0063 |     0.5435 |         0.0641 |                    -0.0224 |                    0.0494 |                         -0.0237 | False    |
| short     |             20 |          85 |      10 |              4 |       33 |                    0.002  |                      0.0065 |     0.5758 |         0.0983 |                    -0.0224 |                    0.0158 |                         -0.0224 | False    |
| short     |             20 |          90 |      10 |              3 |       15 |                    0.016  |                      0.0077 |     0.7333 |         0.6715 |                    -0.0517 |                    0.0329 |                          0      | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.