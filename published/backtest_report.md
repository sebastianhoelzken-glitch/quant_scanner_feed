# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              1 |        4 |                   -0.0602 |                     -0.0755 |          0 |        -2.9533 |                    -0.0602 |                   -0.0602 |                               0 | False    |
| short     |             20 |          65 |      10 |              1 |        3 |                   -0.0564 |                     -0.0797 |          0 |        -1.9929 |                    -0.0564 |                   -0.0564 |                               0 | False    |
| short     |             20 |          70 |      10 |              1 |        2 |                   -0.0399 |                     -0.0399 |          0 |        -1.0021 |                    -0.0399 |                   -0.0399 |                               0 | False    |
| short     |             20 |          75 |      10 |              1 |        2 |                   -0.0399 |                     -0.0399 |          0 |        -1.0021 |                    -0.0399 |                   -0.0399 |                               0 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.