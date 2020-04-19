# LTMU
- High-Performance Long-Term Tracking with Meta-Updater(**CVPR2020 Oral**).
<div align="center">
  <img src="https://github.com/Daikenan/LTMU/blob/master/framework.png" width="500px" />
</div>
## Introduction 
Our Meta-updater can be easily embedded into other online-update algorithms(Dimp, ATOM, ECO, RT-MDNet...) to make their online-update more accurately in long-term tracking task. [More info](https://zhuanlan.zhihu.com/p/130322874).
### Dimp
| LaSOT            | Success Score    | Precision Score |
|:-----------   |:----------------:|:----------------:|
| Dimp50       | 0.568            |      -       |
| Dimp50+MU(k=1)       | 0.594            |      -       |

| TLP            | Success Score    | Precision Score |
|:-----------   |:----------------:|:----------------:|
| Dimp50       | 0.514            |      0.522       |
| Dimp50+MU(k=1)       | 0.564            |      0.575       |

| VOT2019 LT            | F    | TP | TR |
|:-----------   |:----------------:|:----------------:|:----------------:|
| Dimp50       | 0.5727            |    0.6225         |0.5302|
| Dimp50+MU(k=1)       | 0.6415            |     0.6871        |    0.6006|

| VOT2018 LT            | F    | TP | TR |
|:-----------   |:----------------:|:----------------:|:----------------:|
| Dimp50       | 0.5869            |    0.6356         |0.5452|
| Dimp50+MU(k=1)       | 0.6493            |     0.6978        |    0.6072|

### RT-MDNet
| LaSOT            | Success Score    | Precision Score |
|:-----------   |:----------------:|:----------------:|
| RT-MDNet       | 0.325            |  0.319           |
| RT-MDNet+MU(k=2)       | 0.366            |  0.353           |
### ATOM
Coming soon
### ECO
Coming soon
### MDNet
Coming soon
## Paper link
- [Google Drive](https://drive.google.com/open?id=14CGBaVl8sNIYRi0tQ5E_wsjpHiINu9Jk)
- [Baidu Yun](https://pan.baidu.com/s/1jhPOdYoNRVD30Mr5okkv2g)   提取码：kexg
## Citation
Please cite the above publication if you use the code or compare with the ASRCF tracker in your work. Bibtex entry:
```
@inproceedings{Dai_2020_CVPR,
author = {Kenan Dai, Yunhua Zhang, Dong Wang, Jianhua Li, Huchuan Lu, Xiaoyun Yang},
title = {{High-Performance Long-Term Tracking with Meta-Updater},
booktitle = {CVPR},
year = {2020}
}
``` 
