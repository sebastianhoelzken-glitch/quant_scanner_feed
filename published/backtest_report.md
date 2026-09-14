# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              5 |       50 |                   -0.0064 |                     -0.0191 |     0.32   |        -0.974  |                    -0.0144 |                    0.0192 |                         -0.0502 | False    |
| short     |             20 |          65 |      10 |              5 |       50 |                   -0.0064 |                     -0.0191 |     0.32   |        -0.974  |                    -0.0144 |                    0.0192 |                         -0.0502 | False    |
| short     |             20 |          70 |      10 |              5 |       50 |                   -0.0064 |                     -0.0191 |     0.32   |        -0.974  |                    -0.0144 |                    0.0192 |                         -0.0502 | False    |
| short     |             20 |          75 |      10 |              5 |       41 |                   -0.0139 |                     -0.0224 |     0.2195 |        -2.0314 |                    -0.0201 |                   -0.0102 |                         -0.0557 | False    |
| short     |             20 |          80 |      10 |              4 |       28 |                   -0.009  |                     -0.0229 |     0.25   |        -0.9813 |                    -0.0147 |                   -0.0031 |                         -0.0328 | False    |
| short     |             20 |          85 |      10 |              3 |        9 |                   -0.0318 |                     -0.0335 |     0      |        -6.6715 |                    -0.0324 |                   -0.0306 |                         -0.0638 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.