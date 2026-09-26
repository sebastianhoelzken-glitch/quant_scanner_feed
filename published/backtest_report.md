# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             16 |      160 |                   -0.0055 |                     -0.0018 |     0.4875 |        -0.6442 |                    -0.0519 |                    0.0534 |                         -0.1386 | False    |
| short     |             20 |          65 |      10 |             16 |      160 |                   -0.0055 |                     -0.0018 |     0.4875 |        -0.6442 |                    -0.0519 |                    0.0534 |                         -0.1386 | False    |
| short     |             20 |          70 |      10 |             16 |      160 |                   -0.0055 |                     -0.0018 |     0.4875 |        -0.6442 |                    -0.0519 |                    0.0534 |                         -0.1386 | False    |
| short     |             20 |          75 |      10 |             16 |      153 |                   -0.0073 |                     -0.0025 |     0.4771 |        -0.8203 |                    -0.0519 |                    0.0534 |                         -0.1386 | False    |
| short     |             20 |          80 |      10 |             15 |      142 |                   -0.0065 |                     -0.0025 |     0.4859 |        -0.6865 |                    -0.0519 |                    0.0534 |                         -0.1223 | False    |
| short     |             20 |          85 |      10 |             14 |       76 |                   -0.0172 |                     -0.0025 |     0.4868 |        -1.2567 |                    -0.079  |                    0.045  |                         -0.2344 | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0012 |                      0.0077 |     0.6842 |        -0.0433 |                    -0.0517 |                    0.1015 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.