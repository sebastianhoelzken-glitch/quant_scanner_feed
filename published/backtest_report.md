# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              6 |       60 |                   -0.0104 |                     -0.0219 |     0.3667 |        -1.3141 |                    -0.0298 |                    0.0192 |                         -0.0866 | False    |
| short     |             20 |          65 |      10 |              6 |       60 |                   -0.0104 |                     -0.0219 |     0.3667 |        -1.3141 |                    -0.0298 |                    0.0192 |                         -0.0866 | False    |
| short     |             20 |          70 |      10 |              6 |       60 |                   -0.0104 |                     -0.0219 |     0.3667 |        -1.3141 |                    -0.0298 |                    0.0192 |                         -0.0866 | False    |
| short     |             20 |          75 |      10 |              6 |       50 |                   -0.015  |                     -0.0252 |     0.3    |        -1.7494 |                    -0.0298 |                    0.0081 |                         -0.0831 | False    |
| short     |             20 |          80 |      10 |              5 |       36 |                   -0.0111 |                     -0.0276 |     0.3333 |        -0.9811 |                    -0.0271 |                    0.0081 |                         -0.0759 | False    |
| short     |             20 |          85 |      10 |              3 |       16 |                   -0.0118 |                     -0.0335 |     0.375  |        -0.5376 |                    -0.0449 |                    0.0081 |                         -0.0877 | False    |
| short     |             20 |          90 |      10 |              1 |        3 |                   -0.0517 |                     -0.0536 |     0.3333 |        -1.0137 |                    -0.0517 |                   -0.0517 |                          0      | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.