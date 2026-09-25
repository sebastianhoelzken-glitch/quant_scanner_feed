# Point-in-Time Backtest

This backtest uses only daily score snapshots that were actually stored at the time.
It therefore avoids reconstructing old fundamentals from today's revised database.

Assumed round-trip costs: **20.0 bps**.

| horizon   |   holding_days |   threshold |   top_n |   signal_dates |   trades |   mean_net_forward_return |   median_net_forward_return |   hit_rate |   t_stat_naive |   worst_signal_date_return |   best_signal_date_return |   max_drawdown_nonoverlap_proxy | mature   |
|:----------|---------------:|------------:|--------:|---------------:|---------:|--------------------------:|----------------------------:|-----------:|---------------:|---------------------------:|--------------------------:|--------------------------------:|:---------|
| short     |             20 |          60 |      10 |             16 |      160 |                   -0.0099 |                     -0.0012 |     0.475  |        -1.2766 |                    -0.0628 |                    0.027  |                         -0.1676 | False    |
| short     |             20 |          65 |      10 |             16 |      160 |                   -0.0099 |                     -0.0012 |     0.475  |        -1.2766 |                    -0.0628 |                    0.027  |                         -0.1676 | False    |
| short     |             20 |          70 |      10 |             16 |      160 |                   -0.0099 |                     -0.0012 |     0.475  |        -1.2766 |                    -0.0628 |                    0.027  |                         -0.1676 | False    |
| short     |             20 |          75 |      10 |             16 |      149 |                   -0.0115 |                     -0.0012 |     0.4631 |        -1.3978 |                    -0.0628 |                    0.027  |                         -0.161  | False    |
| short     |             20 |          80 |      10 |             15 |      133 |                   -0.012  |                     -0.0012 |     0.4812 |        -1.33   |                    -0.0628 |                    0.027  |                         -0.2002 | False    |
| short     |             20 |          85 |      10 |             13 |       65 |                   -0.0324 |                     -0.0247 |     0.4615 |        -2.4066 |                    -0.076  |                    0.0154 |                         -0.321  | False    |
| short     |             20 |          90 |      10 |              4 |       19 |                   -0.0004 |                      0.0077 |     0.6842 |        -0.015  |                    -0.0517 |                    0.1169 |                         -0.0079 | False    |

No configuration has at least 20 independent signal dates yet; treat all numbers as preliminary.