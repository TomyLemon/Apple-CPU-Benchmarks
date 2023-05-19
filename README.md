# Apple-CPU-Benchmarks
This document documented some benchmark results on Apple CPUs.

## GeekBench5
| GB5    | Geekbench 5 Score | Geekbench 5 Power (watt)¹ | M1 Pro v.s. a14 score | M1 Pro v.s. a14 power | M2 Pro v.s. a15 score | M2 Pro v.s. a15 power |
|--------|-------------------|--------------------------|-----------------------|-----------------------|-----------------------|-----------------------|
| A14    | 1600              | 2.546                    |                       |                       |                       |                       |
| M1 Pro | 1780              | 3.244                    | 11.3%                 | 27.4%                 |                       |                       |
| A15    | 1750              | 2.842                    |                       |                       |                       |                       |
| M2     | 1890              | 3.767                    |                       |                       |                       |                       |
| M2 pro | 1960              | 4.133                    |                       |                       | 12.0%                 | 45.4%                 |

- ¹ See Notes 2.

## Spec2017
|Spec2017                                   |M1 pro          |M2 pro          |
|-------------------------------------------|----------------|----------------|
|500.perlbench_r                            |8.06            |9.44            |
|502.gcc_r                                  |12.60           |13.91           |
|505.mcf_r                                  |8.41            |9.37            |
|520.omnetpp_r                              |7.80            |9.73            |
|523.xalancbmk_r                            |9.44            |10.66           |
|525.x264_r                                 |20.00           |21.74           |
|531.deepsjeng_r                            |5.73            |6.80            |
|541.leela_r                                |5.77            |6.43            |
|548.exchange2_r                            |22.30           |24.27           |
|557.xz_r                                   |4.20            |4.67            |
|                                           |9.10            |10.32           |
|Instruction count                                      |                |
|500.perlbench_r                            |2949265681198   |2952625843135   |
|502.gcc_r                                  |1064910378634   |1067664368104   |
|505.mcf_r                                  |920746280386    |924407291949    |
|520.omnetpp_r                              |1050304739297   |1052704630840   |
|523.xalancbmk_r                            |1106288805745   |1106937686333   |
|525.x264_r                                 |1511133854481   |1512998176309   |
|531.deepsjeng_r                            |1753861421785   |1757013768957   |
|541.leela_r                                |2068151095948   |2072028906816   |
|548.exchange2_r                            |2132331121002   |2132678711720   |
|557.xz_r                                   |1833513691643   |1839142287235   |
|                                           |1533687948994.18|1536556867013.6 |
|Branch inst count                                     |                |
|500.perlbench_r                            |624662682256    |625256513748    |
|502.gcc_r                                  |256710738710    |257190709379    |
|505.mcf_r                                  |224623895012    |225267694175    |
|520.omnetpp_r                              |223164915457    |223590575917    |
|523.xalancbmk_r                            |322137567978    |322223831789    |
|525.x264_r                                 |106780269260    |107157785768    |
|531.deepsjeng_r                            |249205164866    |249751228482    |
|541.leela_r                                |332760649142    |333465480488    |
|548.exchange2_r                            |285007542905    |285073548147    |
|557.xz_r                                   |316209137574    |317206891598    |
|                                           |270098618541.075|270614170921.339|
|Branch miss                                 |                |
|500.perlbench_r                            |2662782515      |2679148468      |
|502.gcc_r                                  |2784039770      |2781534137      |
|505.mcf_r                                  |13112049964     |13080110376     |
|520.omnetpp_r                              |4662852139      |4642432136      |
|523.xalancbmk_r                            |633872390       |626607325       |
|525.x264_r                                 |1336374980      |1327940726      |
|531.deepsjeng_r                            |7060953322      |6848520890      |
|541.leela_r                                |22132321382     |22023452519     |
|548.exchange2_r                            |3877629344      |3853788231      |
|557.xz_r                                   |9980440792      |9946481962      |
|                                           |4330988062.19178|4303137107.16249|
|Branch inst(%)                                 |                |
|500.perlbench_r                            |21%             |21%             |
|502.gcc_r                                  |24%             |24%             |
|505.mcf_r                                  |24%             |24%             |
|520.omnetpp_r                              |21%             |21%             |
|523.xalancbmk_r                            |29%             |29%             |
|525.x264_r                                 |7%              |7%              |
|531.deepsjeng_r                            |14%             |14%             |
|541.leela_r                                |16%             |16%             |
|548.exchange2_r                            |13%             |13%             |
|557.xz_r                                   |17%             |17%             |
|                                           |18%             |18%             |
|Branch miss(%)                        	   |                |
|500.perlbench_r                            |0.43%           |0.43%           |
|502.gcc_r                                  |1.08%           |1.08%           |
|505.mcf_r                                  |5.84%           |5.81%           |
|520.omnetpp_r                              |2.09%           |2.08%           |
|523.xalancbmk_r                            |0.20%           |0.19%           |
|525.x264_r                                 |1.25%           |1.24%           |
|531.deepsjeng_r                            |2.83%           |2.74%           |
|541.leela_r                                |6.65%           |6.60%           |
|548.exchange2_r                            |1.36%           |1.35%           |
|557.xz_r                                   |3.16%           |3.14%           |
|                                           |1.60%           |1.59%           |
|Branch MPKI                                |                |                |
|500.perlbench_r                            |0.9             |0.9             |
|502.gcc_r                                  |2.6             |2.6             |
|505.mcf_r                                  |14.2            |14.1            |
|520.omnetpp_r                              |4.4             |4.4             |
|523.xalancbmk_r                            |0.6             |0.6             |
|525.x264_r                                 |0.9             |0.9             |
|531.deepsjeng_r                            |4.0             |3.9             |
|541.leela_r                                |10.7            |10.6            |
|548.exchange2_r                            |1.8             |1.8             |
|557.xz_r                                   |5.4             |5.4             |
|                                           |2.8             |2.8             |
- Compile using gcc12.2 -ofast -march=native Jemalloc 5.3.0

## Notes
1. PMU results are recored via https://gist.github.com/ibireme/173517c208c7dc333ba962c1f0d67d12.
2. CPU power(s) are recorded via https://github.com/junjie1475/ios_power_log.git.
3. Thread pining support via https://github.com/junjie1475/MacOS_CoreBinder.git.
