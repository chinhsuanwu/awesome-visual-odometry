# Awesome Visual Odometry [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Table of Contents

- [Learning](#courses)
- [Talks](#talks)
- [Papers](#papers)
- [Datasets](#datasets)
- [Projects](#projects)

## Learning

#### Courses

- [Multiple View Geometry](https://vision.in.tum.de/teaching/online/mvg), Daniel Cremers, 2014

#### Surveys

- [15 Years of Visual SLAM](http://wp.doc.ic.ac.uk/thefutureofslam/wp-content/uploads/sites/93/2015/12/slides_ajd.pdf), Andrew Davison, ICCV 2015 Workshop
- [Visual Odometry [Tutorial]](https://ieeexplore.ieee.org/abstract/document/6096039?casa_token=VV2yka6jC-EAAAAA:SVUZ6BWao5ZhKVQmqoJwqj-5hfDL5oq15StyyfFKV2--bXwuM0YX9_G6lZODuZE5HGPwATdTz1o), Scaramuzza and Fraundorfer, RAM 2011
- [Past, present, and future of simultaneous localization and mapping: Toward the robust-perception age](https://ieeexplore.ieee.org/abstract/document/7747236), Cadena et al., T-RO 2016

## Talks

- [Deep Visual SLAM Frontends: SuperPoint, SuperGlue, and SuperMaps](https://www.youtube.com/watch?v=u7Yo5EtOATQ), Malisiewicz, CVPR 2020

## Papers

- [Real-time simultaneous localisation and mapping with a single camera](https://ieeexplore.ieee.org/abstract/document/1238654), Davison, ICCV 2003
- [Visual Odometry](https://ieeexplore.ieee.org/abstract/document/1315094?casa_token=9MFPKQrYt0oAAAAA:se45fHIngWObVwjYS5y3Dhlo5WPb8b-K8an41ecJhDVwFhCqUzEObJXvZx95f9VO0qm3TVTrlTY), Nistér et al., CVPR 2004
- [MonoSLAM: Real-Time Single Camera SLAM](https://ieeexplore.ieee.org/abstract/document/4160954), Davison et al., TPAMI 2007
- [Parallel tracking and mapping for small AR workspaces](https://www.robots.ox.ac.uk/~gk/publications/KleinMurray2007ISMAR.pdf), Klein and Murray, ISMAR 2007
- [DTAM: Dense tracking and mapping in real-time](https://ieeexplore.ieee.org/abstract/document/6126513), Newcombe et al., ICCV 2011
- [KinectFusion: Real-time dense surface mapping and tracking](https://ieeexplore.ieee.org/abstract/document/6162880), Newcombe et al., ISMAR 2011
- [Dynamicfusion: Reconstruction and tracking of non-rigid scenes in real-time](https://ieeexplore.ieee.org/document/7298631), Newcombe et al., CVPR 2015
- [ElasticFusion: Dense SLAM without a pose graph](http://roboticsproceedings.org/rss11/p01.pdf), Whelan et al. RSS 2015
- [Real-time 3D reconstruction and 6-DoF tracking with an event camera](https://link.springer.com/chapter/10.1007/978-3-319-46466-4_21), Kim et al., ECCV 2016

## Datasets

|dataset|year|environment| carrier | camera |
|:-:|:-:|:-:|:-:|:-:|
|[TUM RGB-D](http://vision.in.tum.de/data/datasets/rgbd-dataset/download) | 2012 | indoor | handheld/robot | RGB-D
|[KITTI](http://www.cvlibs.net/datasets/kitti)| 2013 | outdoor | car | stereo
| [Malaga](https://www.mrpt.org/MalagaUrbanDataset) | 2014 | outdoor | car | stereo
| [ICL-NUIM](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html) | 2014 | indoor | handheld | RGB-D
| [Oxford RobotCar](https://robotcar-dataset.robots.ox.ac.uk/) | 2016 | outdoor | car | stereo
| [EuRoC MAV](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets) | 2016 | indoor | MAV | stereo
| [TUM MonoVO](https://vision.in.tum.de/data/datasets/mono-dataset) | 2016 | in/outdoor | handheld | monocular
| [TUM VI](https://vision.in.tum.de/data/datasets/visual-inertial-dataset) | 2018 | in/outdoor | handhled | stereo

## Projects

#### Tracking

- [PTAM: Parallel Tracking and Mapping](http://www.robots.ox.ac.uk/~gk/PTAM/), Klein and Murray, ISMAR 2007

#### Graph Optimization

- [Ceres Solver](https://github.com/ceres-solver/ceres-solver), Agarwal et al., 2010
- [g2o: A General Framework for Graph Optimization](https://github.com/RainerKuemmerle/g2o), Kümmerle et al., ICRA 2011
- [GTSAM: General smoothing and mapping library for Robotics and SFM](https://collab.cc.gatech.edu/borg/gtsam?destination=node%2F299), Dellaert, 2012

#### Visual Odometry

- [DVO: Dense Visual Odometry](https://github.com/tum-vision/dvo_slam), Steinbruecker et al. ICCV 2011
- [SVO: Fast semi-direct monocular visual odometry](https://github.com/uzh-rpg/rpg_svo), Forster et al., ICRA 2014
- [DSO: Direct Sparse Odometry](https://github.com/JakobEngel/dso_ros), Engel et al., 2016

#### vSLAM

- [LSD-SLAM: Large-Scale Direct Monocular SLAM](https://github.com/tum-vision/lsd_slam), Engel et al., ECCV 2014
- [ORB-SLAM: a Versatile and Accurate Monocular SLAM System](https://github.com/raulmur/ORB_SLAM), Mur-Artal et al., T-RO 2015
- [ORB-SLAM2: an Open-Source SLAM System for Monocular, Stereo and RGB-D Cameras](https://github.com/raulmur/ORB_SLAM2), Mur-Artal et al., T-RO 2017
- [OpenVSLAM: A Versatile Visual SLAM Framework](https://github.com/xdspacelab/openvslam), Sumikura et al., ACM MM 2019
- [Kimera: an Open-Source Library for Real-Time Metric-Semantic Localization and Mapping](https://github.com/MIT-SPARK/Kimera), Rosinol et al., ICRA 2020
- [ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial and Multi-Map SLAM](https://arxiv.org/abs/2007.11898), Campos et al., Arxiv 2020

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)