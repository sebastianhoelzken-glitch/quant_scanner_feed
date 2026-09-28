# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             19 |      190 |                   -0.0077 |                     -0.0032 |     0.4737 |        -1.027  |                    -0.0519 |                    0.0534 |                         -0.1586 | False    |
| short     |             20 |          65 |      10 |             19 |      190 |                   -0.0077 |                     -0.0032 |     0.4737 |        -1.027  |                    -0.0519 |                    0.0534 |                         -0.1586 | False    |
| short     |             20 |          70 |      10 |             19 |      190 |                   -0.0077 |                     -0.0032 |     0.4737 |        -1.027  |                    -0.0519 |                    0.0534 |                         -0.1586 | False    |
| short     |             20 |          75 |      10 |             19 |      179 |                   -0.0091 |                     -0.0039 |     0.4693 |        -1.1555 |                    -0.0519 |                    0.0534 |                         -0.1609 | False    |
| short     |             20 |          80 |      10 |             18 |      147 |                   -0.0088 |                     -0.0025 |     0.4762 |        -0.9463 |                    -0.1309 |                    0.0534 |                         -0.3398 | False    |
| short     |             20 |          85 |      10 |             15 |       77 |                   -0.0186 |                     -0.0039 |     0.4805 |        -1.3748 |                    -0.1309 |                    0.045  |                         -0.2504 | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0012 |                      0.0077 |     0.6842 |        -0.0433 |                    -0.0517 |                    0.1015 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.