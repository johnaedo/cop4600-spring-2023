ALGORITHM: opt
FRAME SIZE: 5
PAGE FAULTS: 9
| *_1_*   | *_2_*   | *_3_*   | *_10_*   |   *_20_* |   *_30_* |   *_40_* |   1 |   2 |   1 |   2 |   30 |   40 |   10 |   1 |   2 |   *_3_* |   10 |   *_20_* |
|---------|---------|---------|----------|----------|----------|----------|-----|-----|-----|-----|------|------|------|-----|-----|---------|------|----------|
| 1       | 1       | 1       | 1        |        1 |        1 |        1 |   1 |   1 |   1 |   1 |    1 |    1 |    1 |   1 |   1 |       3 |    3 |       20 |
|         | 2       | 2       | 2        |        2 |        2 |        2 |   2 |   2 |   2 |   2 |    2 |    2 |    2 |   2 |   2 |       2 |    2 |        2 |
|         |         | 3       | 3        |        3 |        3 |       40 |  40 |  40 |  40 |  40 |   40 |   40 |   40 |  40 |  40 |      40 |   40 |       40 |
|         |         |         | 10       |       10 |       10 |       10 |  10 |  10 |  10 |  10 |   10 |   10 |   10 |  10 |  10 |      10 |   10 |       10 |
|         |         |         |          |       20 |       30 |       30 |  30 |  30 |  30 |  30 |   30 |   30 |   30 |  30 |  30 |      30 |   30 |       30 |
