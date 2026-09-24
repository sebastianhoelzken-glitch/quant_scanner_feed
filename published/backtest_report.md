# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             14 |      140 |                   -0.0007 |                      0.0042 |     0.5214 |        -0.083  |                    -0.0519 |                    0.0361 |                         -0.1015 | False    |
| short     |             20 |          65 |      10 |             14 |      140 |                   -0.0007 |                      0.0042 |     0.5214 |        -0.083  |                    -0.0519 |                    0.0361 |                         -0.1015 | False    |
| short     |             20 |          70 |      10 |             14 |      140 |                   -0.0007 |                      0.0042 |     0.5214 |        -0.083  |                    -0.0519 |                    0.0361 |                         -0.1015 | False    |
| short     |             20 |          75 |      10 |             14 |      129 |                   -0.0026 |                      0.0022 |     0.5116 |        -0.2805 |                    -0.0519 |                    0.0361 |                         -0.1015 | False    |
| short     |             20 |          80 |      10 |             13 |      121 |                   -0.0027 |                      0.0037 |     0.5207 |        -0.277  |                    -0.0519 |                    0.0361 |                         -0.0916 | False    |
| short     |             20 |          85 |      10 |             12 |       65 |                   -0.023  |                      0.0001 |     0.5077 |        -1.6434 |                    -0.0519 |                    0.0273 |                         -0.2076 | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0004 |                      0.0077 |     0.6842 |        -0.015  |                    -0.0517 |                    0.1169 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.