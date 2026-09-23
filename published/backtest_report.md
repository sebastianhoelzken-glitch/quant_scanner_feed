# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             13 |      130 |                   -0.0058 |                      0      |     0.5    |        -0.6589 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          65 |      10 |             13 |      130 |                   -0.0058 |                      0      |     0.5    |        -0.6589 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          70 |      10 |             13 |      130 |                   -0.0058 |                      0      |     0.5    |        -0.6589 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          75 |      10 |             13 |      119 |                   -0.0074 |                      0.0001 |     0.5042 |        -0.7863 |                    -0.0519 |                    0.027  |                         -0.1015 | False    |
| short     |             20 |          80 |      10 |             12 |      112 |                   -0.0075 |                      0.0019 |     0.5089 |        -0.7537 |                    -0.0519 |                    0.0433 |                         -0.0844 | False    |
| short     |             20 |          85 |      10 |             11 |       65 |                   -0.029  |                     -0.001  |     0.4923 |        -2.0099 |                    -0.0519 |                    0.0048 |                         -0.2591 | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0004 |                      0.0077 |     0.6842 |        -0.015  |                    -0.0517 |                    0.1169 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.