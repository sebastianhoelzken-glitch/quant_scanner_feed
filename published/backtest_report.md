# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |              5 |       50 |                   -0.0096 |                     -0.0237 |     0.38   |        -1.0507 |                    -0.0251 |                    0.0192 |                         -0.0718 | False    |
| short     |             20 |          65 |      10 |              5 |       50 |                   -0.0096 |                     -0.0237 |     0.38   |        -1.0507 |                    -0.0251 |                    0.0192 |                         -0.0718 | False    |
| short     |             20 |          70 |      10 |              5 |       50 |                   -0.0096 |                     -0.0237 |     0.38   |        -1.0507 |                    -0.0251 |                    0.0192 |                         -0.0718 | False    |
| short     |             20 |          75 |      10 |              5 |       42 |                   -0.0179 |                     -0.029  |     0.3095 |        -1.7954 |                    -0.0322 |                    0.0063 |                         -0.0785 | False    |
| short     |             20 |          80 |      10 |              4 |       30 |                   -0.0097 |                     -0.029  |     0.3667 |        -0.7547 |                    -0.0201 |                    0.0063 |                         -0.0523 | False    |
| short     |             20 |          85 |      10 |              3 |       16 |                   -0.0129 |                     -0.0335 |     0.375  |        -0.5866 |                    -0.0449 |                    0.0063 |                         -0.0877 | False    |
| short     |             20 |          90 |      10 |              1 |        3 |                   -0.0517 |                     -0.0536 |     0.3333 |        -1.0137 |                    -0.0517 |                   -0.0517 |                          0      | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.