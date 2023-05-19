# Apple-CPU-Benchmarks
This document documented some benchmark results on Apple CPUs.

# GeekBench5
| GB5    | Geekbench 5 Score | Geekbench 5 Power (watt)¹ | M1 Pro v.s. a14 score | M1 Pro v.s. a14 power | M2 Pro v.s. a15 score | M2 Pro v.s. a15 power |
|--------|-------------------|--------------------------|-----------------------|-----------------------|-----------------------|-----------------------|
| a14    | 1600              | 2.546                    |                       |                       |                       |                       |
| M1 Pro | 1780              | 3.244                    | 11.3%                 | 27.4%                 |                       |                       |
| a15    | 1750              | 2.842                    |                       |                       |                       |                       |
| M2     | 1890              | 3.767                    |                       |                       |                       |                       |
| M2 pro | 1960              | 4.133                    |                       |                       | 12.0%                 | 45.4%                 |

- ¹ See Notes 2.


# Notes
1. PMU results are recored via https://gist.github.com/ibireme/173517c208c7dc333ba962c1f0d67d12.
2. CPU power(s) are recorded via https://github.com/junjie1475/ios_power_log.git.
3. Thread pining support via https://github.com/junjie1475/MacOS_CoreBinder.git.
