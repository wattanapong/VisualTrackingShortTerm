   
# Visual Tracking Evaluation results

## in Short Term Tracking


| Model （arch+backbone+xcorr） | VOT16 (EAO/A/R)   | VOT18 (EAO/A/R)   | VOT19 (EAO/A/R)   | OTB2015 (AUC/Prec.) | VOT18-LT (F1) | Speed (fps)    | ref. |
|-------------------------------|-------------------|-------------------|-------------------|---------------------|---------------|----------------|------|
| siamrpn_alex_dwxcorr         | 0.393/0.618/0.238 | 0.352/0.576/0.290 | 0.260/0.573/0.547 | -                   | -             | 180            | [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md) |
| siamrpn_alex_dwxcorr_otb      | -                 | -                 | -                 | 0.666/0.876         | -             | 180            | [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md) |
| siamrpn_r50_l234_dwxcorr      | 0.464/0.642/0.196 | 0.415/0.601/0.234 | 0.287/0.595/0.467 | -                   | -             | 35             | [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md) |
| siamrpn_r50_l234_dwxcorr_otb  | -                 | -                 | -                 | 0.696/0.914         | -             | 35             | [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md) |
| siamrpn_mobilev2_l234_dwxcorr | 0.455/0.624/0.214 | 0.410/0.586/0.229 | 0.292/0.580/0.446 | -                   | -             | 75             | [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md) |
| siammask_r50_l3               | 0.455/0.634/0.219 | 0.423/0.615/0.248 | 0.283/0.597/0.461 | -                   | -             | 56             | [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md) |
| siamrpn_r50_l234_dwxcorr_lt   | -                 | -                 | -                 | -                   | 0.629         | 20             | [link<sub>1</sub>](https://github.com/STVIR/pysot/blob/master/MODEL_ZOO.md) |
| ATOM (CVPR2019)               |                   | 0.401/0.590/0.203 |                   |                     |               | 43<sup>2</sup> | [link<sub>2</sub>](https://github.com/visionml/pytracking)     |
| DiMP (ICCV2019)               |                   | 0.441/0.597/0.152 |                   |                     |               | 40             | [link<sub>2</sub>](https://github.com/visionml/pytracking)|
| siamban (CVPR2020)            |                   | 0.452/0.597/0.178 |                   |                     |               |       45       | [link<sub>3</sub>](https://github.com/hqucv/siamban)     |
| KYS (Arxiv2020)                |                   | 0.462/0.609/0.143 |                   |                     |               | 20<sup>3</sup> | [link<sub>2</sub>](https://github.com/visionml/pytracking)      |
|                               |                   |                   |                   |                     |               |                |      |


*** fps ***

null = GTX 1080Ti

fps<sup>2</sup> = GTX 1080

fps<sup>3</sup> = RTX 2080

