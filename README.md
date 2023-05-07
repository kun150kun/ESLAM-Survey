# Event-based SLAM: A Comprehensive Survey

[![arXiv](https://img.shields.io/badge/arXiv-2304.09793-brightgreen.svg)](https://arxiv.org/abs/2304.09793)
[![Survey](https://img.shields.io/badge/-survey-yellow.svg)](https://arxiv.org/pdf/2304.09793.pdf)
[![Github license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kun150kun/ESLAM-Survey/blob/main/LICENSE)

More content and details can be found in our Survey Paper: [Event-based Simultaneous Localization and Mapping: A Comprehensive Survey](https://arxiv.org/pdf/2304.09793.pdf)

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
|2011|[IJCNN](https://ieeexplore.ieee.org/document/6033299)|Interacting maps for fast visual interpretation|Optimization|-|Event frame|Ego-motion estimation|-|
|2012|[ROBIO](https://ieeexplore.ieee.org/document/6491077)|Event-based particle filtering for robot self-localization|Filter|Feature|-|Ego-motion estimation|-|
|2013|[ICVS](https://dl.acm.org/doi/10.1007/978-3-642-39402-7_14)|Simultaneous localization and mapping for event-based vision systems|Filter|Feature|-|Mapping|-|
|2014|[BMVC](http://www.bmva.org/bmvc/2014/papers/paper066/index.html)|Simultaneous mosaicing and tracking with an event camera|Filter|Direct|-|Ego-motion estimation|-|
|2014|[ICRA](https://ieeexplore.ieee.org/document/6906931)|Low-latency event-based visual odometry|Filter|Direct|Event packet|Ego-motion estimation|-|
|2014|[ICRA](https://ieeexplore.ieee.org/document/6906882)|Event-based 3D SLAM with a depth-augmented dynamic vision sensor|Filter|Feature|-|Visual odometry|-|
|2014|[IROS](https://ieeexplore.ieee.org/document/6942940)|Event-based, 6-DOF pose tracking for high-speed maneuvers|Optimization|Feature|Event packet|Ego-motion estimation|-|
|2015|[ArXiv](https://arxiv.org/pdf/1510.01972.pdf)|Event-based camera pose tracking using a generative event model|Filter|Direct|-|Ego-motion estimation|-|
|2015|[RSS](https://www.roboticsproceedings.org/rss11/p36.pdf)|Continuous-time trajectory estimation for event-based vision sensors|Optimization|Feature|Event packet|Ego-motion estimation|-|
|2016|[ECCV](https://link.springer.com/chapter/10.1007/978-3-319-46466-4_21)|Real-time 3D reconstruction and 6-DoF tracking with an event camera|Filter|Direct|-|Visual odometry|-|
|2016|[ICRA](https://ieeexplore.ieee.org/document/7487657)|Fast localization and tracking using event sensors|Optimization|Feature|Event frame|Ego-motion estimation|-|
|2016|[IROS](https://ieeexplore.ieee.org/document/7758089)|Low-latency visual odometry using event-based feature tracks|Optimization|Feature|Local point set|Visual odometry|-|
|2016|[RA-L](https://ieeexplore.ieee.org/document/7797445)|EVO: a geometric approach to event-based 6-DOF parallel tracking and mapping in real time|Optimization|Direct|Edge Map|Visual odometry|[Code](https://github.com/uzh-rpg/rpg_dvs_evo_open)|
|2017|[BMVC](https://rpg.ifi.uzh.ch/docs/BMVC17_Rebecq.pdf)|Real-time visual-inertial odometry for event cameras using keyframe-based nonlinear optimization|Optimization|Feature|Motion-compensated event frame|Visual inertial odometry|-|
|2017|[CVPR](https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhu_Event-Based_Visual_Inertial_CVPR_2017_paper.pdf)|Event-based visual inertial odometry|Filter|Feature|Motion-compensated event packet|Visual inertial odometry|[Code](https://github.com/daniilidis-group/event_feature_tracking)|
|2017|[ICCP](https://ieeexplore.ieee.org/document/7951488)|Real-time panoramic tracking for event cameras|Optimization|Feature|Event packet|Visual odometry|-|
|2017|[RA-L](https://ieeexplore.ieee.org/document/7805257)|Accurate angular velocity estimation with an event camera|Optimization|Motion-compensation|Motion-compensated event frame|Ego-motion estimation|-|
|2017|[R-AL](https://ieeexplore.ieee.org/document/8258997)|Ultimate SLAM? combining events, images, and IMU for robust visual SLAM in HDR and high-speed scenarios|Optimization|Feature|Motion-compensated event frame|Visual inertial odometry|[Code](https://github.com/uzh-rpg/rpg_ultimate_slam_open)|
|2017|[TPAMI](https://ieeexplore.ieee.org/document/8094962)|Event-based, 6-DOF camera tracking from photometric depth maps|Filter|Direct|-|Ego-motion estimation|-|
|2018|[CVPR](https://ieeexplore.ieee.org/document/8578505)|A unifying contrast maximization framework for event cameras, with applications to motion, depth, and optical flow estimation|Optimization|Motion-compensation|Motion-compensated event frame|Ego-motion estimation|-|
|2018|[T-RO](https://ieeexplore.ieee.org/document/8432102)|Continuous-time visual-inertial odometry for event cameras|Optimization|Feature|Event packet|Visual inertial odometry|-|
|2019|[CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Unsupervised_Event-Based_Learning_of_Optical_Flow_Depth_and_Egomotion_CVPR_2019_paper.pdf)|Unsupervised event-based learning of optical flow, depth, and egomotion|Optimization|Deep learning|Voxel grid|Visual odometry|-|
|2019|[ICRA](https://ieeexplore.ieee.org/document/8794255)|Event-based, direct camera tracking from a photometric 3D map using nonlinear optimization|Optimization|Direct|Brightness incremental image|Ego-motion estimation|-|
|2019|[ROBIO](https://ieeexplore.ieee.org/document/8961878)|Neuromorphic Visual Odometry System For Intelligent Vehicle Application With Bio-inspired Vision Sensor|Optimization|Feature|Motion-compensated event frame|Visual odometry|-|
|2020|[BMVC](https://www.bmvc2020-conference.com/assets/papers/0366.pdf)|High-speed event-based camera tracking|Filter|Feature|-|Ego-motion estimation|-|
|2020|[CVPR](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Globally_Optimal_Contrast_Maximisation_for_Event-Based_Motion_Estimation_CVPR_2020_paper.pdf)|Globally Optimal Contrast Maximisation for Event-Based Motion Estimation|Optimization|Motion-compensation|Motion-compensated event frame|Ego-motion estimation|-|
|2020|[EBCCSP](https://ieeexplore.ieee.org/document/9291346)|Embedded Event-based Visual Odometry|Optimization|Feature|Event packet|Ego-motion estimation|-|
|2020|[ECCV](https://link.springer.com/chapter/10.1007/978-3-030-58558-7_10)|Entropy Minimisation Framework for Event-Based Vision Model Estimation|Optimization|Motion-compensation|Motion-compensated event packet|Ego-motion estimation|[Code](https://github.com/ImperialCollegeLondon/EventEMin)|
|2020|[ECCV](https://link.springer.com/chapter/10.1007/978-3-030-58574-7_4)|Globally-Optimal Event Camera Motion Estimation|Optimization|Motion-compensation|Motion-compensated event frame|Ego-motion estimation|-|
|2020|[ICRA](https://ieeexplore.ieee.org/document/9197133)|Event-Based Angular Velocity Regression with Spiking Networks|Optimization|Deep learning|-|Ego-motion estimation|[Code](https://github.com/uzh-rpg/snn_angular_velocity)|
|2020|[IROS](https://ieeexplore.ieee.org/document/9341224)|Unsupervised learning of dense optical flow, depth and egomotion with event-based sensors|Optimization|Deep learning|Event frame and time surface|Visual odometry|-|
|2020|[IROS](https://ieeexplore.ieee.org/document/9341208)|IDOL: A Framework for IMU-DVS Odometry using Lines|Optimization|Feature|Event packet|Visual odometry|-|
|2020|[TCI](https://ieeexplore.ieee.org/document/8950341)|Robust Motion Compensation for Event Cameras With Smooth Constraint|Optimization|Motion-compensation|Motion-compensated event frame|Ego-motion estimation|-|
|2021|[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Spatiotemporal_Registration_for_Event-Based_Visual_Odometry_CVPR_2021_paper.pdf)|Spatiotemporal Registration for Event-based Visual Odometry|Optimization|Feature|Event packet|Ego-motion estimation|-|
|2021|[ECMR](https://ieeexplore.ieee.org/document/9568811)|Feature-based Event Stereo Visual Odometry|Optimization|Feature|Time surface|Stereo visual odometry|-|
|2021|[ICCV](https://openaccess.thecvf.com/content/ICCV2021/papers/Gu_The_Spatio-Temporal_Poisson_Point_Process_A_Simple_Model_for_the_ICCV_2021_paper.pdf)|The Spatio-Temporal Poisson Point Process: A Simple Model for the Alignment of Event Camera Data|Optimization|Motion-compensation|Motion-compensated event frame|Ego-motion estimation|[Code](https://github.com/pbideau/Event-ST-PPP)|
|2021|[R-AL](https://ieeexplore.ieee.org/document/9454404)|Real-Time Rotational Motion Estimation With Contrast Maximization Over Globally Aligned Events|Optimization|Motion-compensation|Motion-compensated event frame|Ego-motion estimation|-|
|2021|[Sensors](https://www.mdpi.com/1424-8220/22/15/5687)|Visual Odometry with an Event Camera Using Continuous Ray Warping and Volumetric Contrast Maximization|Optimization|Motion-compensation|Event packet|Visual odometry|-|
|2021|[T-RO](https://ieeexplore.ieee.org/document/9386209)|Event-Based Stereo Visual Odometry|Optimization|Direct|Time surface|Stereo visual odometry|[Code](https://github.com/HKUST-Aerial-Robotics/ESVO)|
|2022|[ArXiv](https://arxiv.org/pdf/2209.12160.pdf)|PL-EVIO: Robust Monocular Event-based Visual Inertial Odometry with Point and Line Features|Optimization|Feature|Motion-compensated time surface|Visual inertial odometry|-|
|2022|[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Hidalgo-Carrio_Event-Aided_Direct_Sparse_Odometry_CVPR_2022_paper.pdf)|Event-aided Direct Sparse Odometry|Optimization|Direct|Brightness incremental image|Visual odometry|[Code](https://github.com/uzh-rpg/slam-orogen-eds)|
|2022|[ICRA](https://ieeexplore.ieee.org/document/9811805)|DEVO: Depth-Event Camera Visual Odometry in Challenging Conditions|Optimization|Direct|Time surface|Visual odometry|-|
|2022|[ICRA](https://ieeexplore.ieee.org/document/9811943)|Asynchronous Optimisation for Event-based Visual Odometry|Optimization|Feature|-|Visual odometry|-|
|2022|[IROS](https://ieeexplore.ieee.org/document/9981970)|Monocular Event Visual Inertial Odometry based on Event-corner using Sliding Windows Graph-based Optimization|Optimization|Feature|Time surface|Visual inertial odometry|-|
|2022|[IROS](https://ieeexplore.ieee.org/document/9981249/)|A Tightly-Coupled Event-Inertial Odometry using Exponential Decay and Linear Preintegrated Measurements|Filter|Feature|Time surface|Visual inertial odometry|-|
|2022|[R-AL](https://ieeexplore.ieee.org/document/9810191)|Event-Based Line SLAM in Real-Time|Filter|Feature|-|Visual odometry|-|
|2022|[R-AL](https://ieeexplore.ieee.org/document/9813406)|Exploring Event Camera-Based Odometry for Planetary Robots|Filter|Feature|Brightness incremental image|Visual inertial odometry|[Code](https://uzh-rpg.github.io/eklt-vio)|
|2022|[TPAMI](https://ieeexplore.ieee.org/document/9329204)|Globally-Optimal Contrast Maximisation for Event Cameras|Optimization|Motion-compensation|Motion-compensated event frame|Ego-motion estimation|-|
|2022|[TPAMI](https://ieeexplore.ieee.org/document/9625712)|Robust Event-Based Vision Model Estimation by Dispersion Minimisation|Optimization|Motion-compensation|Motion-compensated event packet|Ego-motion estimation|[Code](https://github.com/ImperialCollegeLondon/EventEMin)|
|2023|[Sensors](https://www.mdpi.com/1424-8220/23/4/1998)|ESVIO: Event-Based Stereo Visual-Inertial Odometry|Optimization|Direct|Time surface|Stereo visual inertial odometry|-|

## Datasets
|Name|Publication|Motion|Devices|Resolution|Sensor|Dataset|
|---|---|---|---|---|---|---|
|ECDS|[IJRR](https://journals.sagepub.com/doi/pdf/10.1177/0278364917691115)|rotation, translation, 6DoF|Hand-held|240\*180|Event, IMU|[Dataset](https://rpg.ifi.uzh.ch/davis_data.html)|
|rpg|[ECCV](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yi_Zhou_Semi-Dense_3D_Reconstruction_ECCV_2018_paper.pdf)|6DoF|Hand-held|240\*180|Stereo Event|[Dataset](https://rpg.ifi.uzh.ch/ECCV18_stereo_davis.html)|
|MVSEC|[RA-L](https://ieeexplore.ieee.org/document/8288670)|6DoF|Hexacoptor, Car, Hand-held, Motorcycle|346\*240|Stereo Event, Stereo Frame, IMU, Lidar, GPS|[Dataset](https://daniilidis-group.github.io/mvsec)|
|UZH-FPV|[ICRA](https://ieeexplore.ieee.org/document/8793887)|6DoF|Drone|640\*480|Event, Frame, IMU|[Dataset](https://fpv.ifi.uzh.ch/)|
|DSEC|[RA-L](https://rpg.ifi.uzh.ch/docs/RAL21_DSEC.pdf)|6DoF|Car|640\*480|Stereo Event, Stereo Frame, Lidar, GPS|[Dataset](https://dsec.ifi.uzh.ch)|
|TUM-VIE|[IROS](https://ieeexplore.ieee.org/document/9636728)|6DoF|Hand-held|1280\*720|Stereo Event, Stereo Frame, IMU|[Dataset](https://cvg.cit.tum.de/data/datasets/visual-inertial-event-dataset)|
|EDS|[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Hidalgo-Carrio_Event-Aided_Direct_Sparse_Odometry_CVPR_2022_paper.pdf)|6DoF|Hand-held|640\*480|Event, Frame, IMU|[Dataset](https://rpg.ifi.uzh.ch/eds.html#dataset)|
|VECtor|[RA-L](https://ieeexplore.ieee.org/document/9809788)|6DoF|Hand-held|640\*480|Stereo Event, Stereo Frame, RGB-D, IMU, Lidar|[Dataset](https://star-datasets.github.io/vector)|
|M2DGR|[ICRA](https://ieeexplore.ieee.org/document/9664374)|6DoF|Ground Robot|640\*480|Event, Frame, IMU, Lidar, GPS, Thermal|[Dataset](https://github.com/SJTU-ViSYS/M2DGR)|
|vicon|[IROS](https://ieeexplore.ieee.org/document/9981970)|6DoF|Quadrotor|346\*240, 640\*480|Event, IMU|[Dataset](https://sites.google.com/connect.hku.hk/hku-arclab-evio/home)|
|ViViD++|[RA-L](https://ieeexplore.ieee.org/document/9760091)|6DoF|Hand-held, Car|240\*180, 640\*480|Event, Frame, RGB-D, Thermal, Lidar, GPS|[Dataset](https://visibilitydataset.github.io)|
|VISTA 2.0|[ICRA](https://dl.acm.org/doi/abs/10.1109/ICRA46639.2022.9812276)|6DoF|Synthetic|-|Event, RGD, Lidar|[Dataset](https://vista.csail.mit.edu/)|
|FusionPortable|[IROS](https://ieeexplore.ieee.org/document/9982119)|6DoF|Hand-held, Quadruped Robot|346\*240|Stereo Event, Stereo Frame, IMU, Lidar, GPS|[Dataset](https://ram-lab.com/file/site/multi-sensor-dataset)|

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
