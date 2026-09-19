# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              9 |       90 |                    0.0027 |                      0.0019 |     0.5111 |         0.2706 |                    -0.0428 |                    0.0366 |                         -0.1008 | False    |
| short     |             20 |          65 |      10 |              9 |       90 |                    0.0027 |                      0.0019 |     0.5111 |         0.2706 |                    -0.0428 |                    0.0366 |                         -0.1008 | False    |
| short     |             20 |          70 |      10 |              9 |       90 |                    0.0027 |                      0.0019 |     0.5111 |         0.2706 |                    -0.0428 |                    0.0366 |                         -0.1008 | False    |
| short     |             20 |          75 |      10 |              9 |       80 |                   -0.0021 |                     -0.0006 |     0.4875 |        -0.1957 |                    -0.0428 |                    0.0366 |                         -0.1008 | False    |
| short     |             20 |          80 |      10 |              8 |       72 |                   -0.0015 |                      0.0019 |     0.5139 |        -0.1274 |                    -0.0428 |                    0.0366 |                         -0.0837 | False    |
| short     |             20 |          85 |      10 |              7 |       42 |                   -0.03   |                     -0.0025 |     0.4762 |        -1.937  |                    -0.0536 |                    0.0045 |                         -0.1496 | False    |
| short     |             20 |          90 |      10 |              3 |       17 |                   -0.0156 |                      0.0077 |     0.6471 |        -0.5181 |                    -0.0517 |                   -0.0079 |                         -0.0157 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.