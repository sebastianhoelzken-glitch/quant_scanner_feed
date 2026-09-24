# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             15 |      150 |                   -0.0012 |                      0.0023 |     0.5133 |        -0.148  |                    -0.0519 |                    0.0361 |                         -0.1015 | False    |
| short     |             20 |          65 |      10 |             15 |      150 |                   -0.0012 |                      0.0023 |     0.5133 |        -0.148  |                    -0.0519 |                    0.0361 |                         -0.1015 | False    |
| short     |             20 |          70 |      10 |             15 |      150 |                   -0.0012 |                      0.0023 |     0.5133 |        -0.148  |                    -0.0519 |                    0.0361 |                         -0.1015 | False    |
| short     |             20 |          75 |      10 |             15 |      135 |                   -0.0021 |                      0.0001 |     0.5037 |        -0.2348 |                    -0.0519 |                    0.0361 |                         -0.1015 | False    |
| short     |             20 |          80 |      10 |             14 |      122 |                   -0.0031 |                      0.003  |     0.5164 |        -0.3237 |                    -0.0555 |                    0.0361 |                         -0.1421 | False    |
| short     |             20 |          85 |      10 |             12 |       65 |                   -0.023  |                      0.0001 |     0.5077 |        -1.6434 |                    -0.0519 |                    0.0273 |                         -0.2076 | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0004 |                      0.0077 |     0.6842 |        -0.015  |                    -0.0517 |                    0.1169 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.