# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             20 |      200 |                   -0.0072 |                     -0.0018 |     0.47   |        -0.9988 |                    -0.0519 |                    0.027  |                         -0.1542 | True     |
| short     |             20 |          65 |      10 |             20 |      200 |                   -0.0072 |                     -0.0018 |     0.47   |        -0.9988 |                    -0.0519 |                    0.027  |                         -0.1542 | True     |
| short     |             20 |          70 |      10 |             20 |      200 |                   -0.0072 |                     -0.0018 |     0.47   |        -0.9988 |                    -0.0519 |                    0.027  |                         -0.1542 | True     |
| short     |             20 |          75 |      10 |             20 |      189 |                   -0.0087 |                     -0.0025 |     0.4656 |        -1.1581 |                    -0.0519 |                    0.027  |                         -0.1564 | True     |
| short     |             20 |          80 |      10 |             19 |      163 |                   -0.0109 |                     -0.01   |     0.4601 |        -1.2815 |                    -0.074  |                    0.027  |                         -0.2582 | False    |
| short     |             20 |          85 |      10 |             17 |       83 |                   -0.0217 |                     -0.0213 |     0.4578 |        -1.7021 |                    -0.074  |                    0.045  |                         -0.2798 | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0012 |                      0.0077 |     0.6842 |        -0.0433 |                    -0.0517 |                    0.1015 |                         -0.0079 | False    |