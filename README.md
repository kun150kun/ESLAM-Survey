# Event-based SLAM: A Comprehensive Survey

[![arXiv](https://img.shields.io/badge/arXiv-2304.09793-brightgreen.svg)](https://arxiv.org/abs/2304.09793)
[![Survey](https://img.shields.io/badge/-survey-yellow.svg)](https://arxiv.org/pdf/2304.09793.pdf)
[![Github license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kun150kun/ESLAM-Survey/blob/main/LICENSE)

## Contents 
1. [Taxonomy](#Taxonomy)
2. [Methods](#Methods)
3. [Datasets](#Datasets)
4. [Citation](#Citation)
5. [Contact](#Contact)

## Taxonomy

## Methods
|Year|Publication|Title|Method|Type|Event Representation|Task|Code|
|---|---|---|---|---|---|---|---|
|2011|[IJCNN](https://ieeexplore.ieee.org/document/6033299)|Interacting maps for fast visual interpretation|Optimization|-|Event Frame|Ego-motion Estimation|-|
|2012|[ROBIO](https://ieeexplore.ieee.org/document/6491077)|Event-based particle filtering for robot self-localization|Filter|Feature|-|Ego-motion Estimation|-|


## Datasets
|Name|Publication|Motion|Devices|Resolution|Sensor|Dataset|
|---|---|---|---|---|---|---|
|ECDS|[IJRR](https://journals.sagepub.com/doi/pdf/10.1177/0278364917691115)|rotation, translation, 6DoF|Hand-held|240\*180|Event, IMU|[Dataset](https://rpg.ifi.uzh.ch/davis_data.html)|
|rpg|[ECCV](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yi_Zhou_Semi-Dense_3D_Reconstruction_ECCV_2018_paper.pdf)|6DoF|Hand-held|640\*480 |Stereo Event|[Dataset](https://rpg.ifi.uzh.ch/ECCV18_stereo_davis.html)|
|MVSEC|[RA-L](https://ieeexplore.ieee.org/document/8288670)|6DoF|Hexacoptor, Car, Hand-held, Motorcycle|346\*240 |Stereo Event, RGB, IMU, Lidar, GPS|[Dataset](https://daniilidis-group.github.io/mvsec)|
|UZH-FPV|[ICRA](https://ieeexplore.ieee.org/document/8793887)|6DoF|Drone|640\*480|Event, RGB, IMU|[Dataset](https://fpv.ifi.uzh.ch/)|
|DSEC|[RA-L](https://rpg.ifi.uzh.ch/docs/RAL21_DSEC.pdf)|6DoF|Car|640\*480|Stereo Event, RGB, Lidar, GPS|[Dataset](https://dsec.ifi.uzh.ch)|
|EDS|[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Hidalgo-Carrio_Event-Aided_Direct_Sparse_Odometry_CVPR_2022_paper.pdf)|6DoF|Hand-held|640\*480|Event, RGB, IMU|[Dataset](https://rpg.ifi.uzh.ch/eds.html#dataset)|
|VECtor|[RA-L](https://ieeexplore.ieee.org/document/9809788)|6DoF|Hand-held|640\*480|Stereo Event, RGB-D, IMU, Lidar|[Dataset](https://star-datasets.github.io/vector)|
|M2DGR|[ICRA](https://ieeexplore.ieee.org/document/9664374)|6DoF|Ground Robot|640\*480|Event, RGB, IMU, Lidar, GPS, Thermal|[Dataset](https://github.com/SJTU-ViSYS/M2DGR)|
|vicon|[IROS](https://ieeexplore.ieee.org/document/9981970)|6DoF|Quadrotor|346\*240,640\*480|Event, IMU|[Dataset](https://sites.google.com/connect.hku.hk/hku-arclab-evio/home)|
|ViViD|[RA-L](https://ieeexplore.ieee.org/document/9760091)|6DoF|Hand-held, Car|640\*480|Event, RGD-D, Thermal, Lidar, GPS|[Dataset](https://dsec.ifi.uzh.ch)|
|VISTA 2.0|[ICRA](https://dl.acm.org/doi/abs/10.1109/ICRA46639.2022.9812276)|6DoF|Synthetic|-|Event, RGD, Lidar|[Dataset](https://vista.csail.mit.edu/)|
|FusionPortable|[IROS](https://ieeexplore.ieee.org/document/9982119)|6DoF|Hand-held|346\*240|Stereo Event, RGD, IMU, Lidar, GPS|[Dataset](https://ram-lab.com/file/site/multi-sensor-dataset)|

## License
The survey and benchmark are only made available for academic research purpose.

## Citation
```
@article{huang2023eventbased,
  Author = {Kunping Huang and Sen Zhang and Jing Zhang and Dacheng Tao},
  Title = {Event-based Simultaneous Localization and Mapping: A Comprehensive Survey},
  Year = {2023},
  Journal = {arXiv:2304.09793}
}
```

## Contact

```
khua7609@uni.sydney.edu.au
```
