# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             19 |      190 |                   -0.0166 |                     -0.0177 |     0.4421 |        -2.4215 |                    -0.0652 |                    0.027  |                         -0.2895 | False    |
| short     |             20 |          65 |      10 |             19 |      190 |                   -0.0166 |                     -0.0177 |     0.4421 |        -2.4215 |                    -0.0652 |                    0.027  |                         -0.2895 | False    |
| short     |             20 |          70 |      10 |             19 |      190 |                   -0.0166 |                     -0.0177 |     0.4421 |        -2.4215 |                    -0.0652 |                    0.027  |                         -0.2895 | False    |
| short     |             20 |          75 |      10 |             19 |      179 |                   -0.0193 |                     -0.0213 |     0.4302 |        -2.6808 |                    -0.0652 |                    0.027  |                         -0.3005 | False    |
| short     |             20 |          80 |      10 |             18 |      147 |                   -0.021  |                     -0.0238 |     0.4286 |        -2.5113 |                    -0.1309 |                    0.027  |                         -0.4489 | False    |
| short     |             20 |          85 |      10 |             15 |       78 |                   -0.0329 |                     -0.0421 |     0.4231 |        -2.7299 |                    -0.1309 |                    0.0071 |                         -0.4333 | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0012 |                      0.0077 |     0.6842 |        -0.0433 |                    -0.0517 |                    0.1015 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.