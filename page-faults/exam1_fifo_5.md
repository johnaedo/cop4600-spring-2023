ALGORITHM: fifo
FRAME SIZE: 5
PAGE FAULTS: 14
| *_1_*   | *_2_*   | *_3_*   | *_10_*   |   *_20_* |   *_30_* |   *_40_* |   *_1_* |   *_2_* |   *_1_* |   *_2_* |   30 |   40 |   10 |   *_1_* |   *_2_* |   *_3_* |   10 |   20 |
|---------|---------|---------|----------|----------|----------|----------|---------|---------|---------|---------|------|------|------|---------|---------|---------|------|------|
| 1       | 1       | 1       | 1        |        1 |       30 |       30 |      30 |      30 |      30 |      30 |   30 |   30 |   30 |      30 |      30 |      30 |   30 |   30 |
|         | 2       | 2       | 2        |        2 |        2 |       40 |      40 |      40 |      40 |      40 |   40 |   40 |   40 |      40 |      40 |      40 |   40 |   40 |
|         |         | 3       | 3        |        3 |        3 |        3 |       1 |       2 |       1 |       2 |    2 |    2 |    2 |       1 |       2 |       3 |    3 |    3 |
|         |         |         | 10       |       10 |       10 |       10 |      10 |      10 |      10 |      10 |   10 |   10 |   10 |      10 |      10 |      10 |   10 |   10 |
|         |         |         |          |       20 |       20 |       20 |      20 |      20 |      20 |      20 |   20 |   20 |   20 |      20 |      20 |      20 |   20 |   20 |
