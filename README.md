# Awesome Visual Odometry [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Table of Contents

- [Learning](#courses)
- [Talks](#talks)
- [Papers](#papers)
- [Datasets](#datasets)
- [Projects](#projects)

## Learning

#### Courses

- [Multiple View Geometry](https://vision.in.tum.de/teaching/online/mvg), Cremers, 2014

#### Books
- [Multiple View Geometry in Computer Vision](https://www.robots.ox.ac.uk/~vgg/hzbook/), Hartley and Zisserman, 2004
- [Computer Vision: Algorithms and Applications](https://szeliski.org/Book/), Szeliski, 2010
#### Surveys

- [15 Years of Visual SLAM](http://wp.doc.ic.ac.uk/thefutureofslam/wp-content/uploads/sites/93/2015/12/slides_ajd.pdf), Davison, ICCV 2015 Workshop
- [Visual Odometry [Tutorial]](https://ieeexplore.ieee.org/abstract/document/6096039?casa_token=VV2yka6jC-EAAAAA:SVUZ6BWao5ZhKVQmqoJwqj-5hfDL5oq15StyyfFKV2--bXwuM0YX9_G6lZODuZE5HGPwATdTz1o), Scaramuzza and Fraundorfer, RAM 2011
- [Past, present, and future of simultaneous localization and mapping: Toward the robust-perception age](https://ieeexplore.ieee.org/abstract/document/7747236), Cadena et al., T-RO 2016

## Talks

- [Deep Visual SLAM Frontends: SuperPoint, SuperGlue, and SuperMaps](https://www.youtube.com/watch?v=u7Yo5EtOATQ), Malisiewicz, CVPR 2020

## Papers

#### System
- Classical
    - [Real-time simultaneous localisation and mapping with a single camera](https://ieeexplore.ieee.org/abstract/document/1238654), Davison, ICCV 2003
    - [Visual Odometry](https://ieeexplore.ieee.org/abstract/document/1315094?casa_token=9MFPKQrYt0oAAAAA:se45fHIngWObVwjYS5y3Dhlo5WPb8b-K8an41ecJhDVwFhCqUzEObJXvZx95f9VO0qm3TVTrlTY), Nistér et al., CVPR 2004
    - [MonoSLAM: Real-Time Single Camera SLAM](https://ieeexplore.ieee.org/abstract/document/4160954), Davison et al., TPAMI 2007
    - [Parallel tracking and mapping for small AR workspaces](https://www.robots.ox.ac.uk/~gk/publications/KleinMurray2007ISMAR.pdf), Klein and Murray, ISMAR 2007
    - [Real-time stereo visual odometry for autonomous ground vehicles](https://ieeexplore.ieee.org/document/4651147), Howard, IROS 2008
    - [StereoScan: Dense 3d reconstruction in real-time](https://ieeexplore.ieee.org/document/5940405), Geiger et al., IV 2011
    - [DTAM: Dense tracking and mapping in real-time](https://ieeexplore.ieee.org/abstract/document/6126513), Newcombe et al., ICCV 2011
    - [KinectFusion: Real-time dense surface mapping and tracking](https://ieeexplore.ieee.org/abstract/document/6162880), Newcombe et al., ISMAR 2011
    - [Dynamicfusion: Reconstruction and tracking of non-rigid scenes in real-time](https://ieeexplore.ieee.org/document/7298631), Newcombe et al., CVPR 2015
    - [ElasticFusion: Dense SLAM without a pose graph](http://roboticsproceedings.org/rss11/p01.pdf), Whelan et al. RSS 2015
    ---
- Learning-Based
    - [PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization](https://www.cv-foundation.org/openaccess/content_iccv_2015/html/Kendall_PoseNet_A_Convolutional_ICCV_2015_paper.html), Kendall et al., ICCV 2015
    - [Unsupervised Learning of Monocular Depth Estimation and Visual Odometry with Deep Feature Reconstruction](https://openaccess.thecvf.com/content_cvpr_2018/html/Zhan_Unsupervised_Learning_of_CVPR_2018_paper.html), Zhan et al., CVPR 2018
    - [CodeSLAM - Learning a Compact, Optimisable Representation for Dense Visual SLAM](https://arxiv.org/abs/1804.00874), Bloesch et al., CVPR 2018
    - [Deep Virtual Stereo Odometry: Leveraging Deep Depth Prediction for Monocular Direct Sparse Odometry](https://openaccess.thecvf.com/content_ECCV_2018/html/Nan_Yang_Deep_Virtual_Stereo_ECCV_2018_paper.html), Yang et al., ECCV 2018
    - [gradSLAM: Automagically differentiable SLAM](https://arxiv.org/abs/1910.10672), Murthy et al., ICRA 2020
    - [D3VO: Deep Depth, Deep Pose and Deep Uncertainty for Monocular Visual Odometry](https://arxiv.org/abs/2003.01060), Yang et al., CVPR 2020

#### Feature Detection
- Classical
    - [A combined corner and edge detector](http://www.bmva.org/bmvc/1988/avc-88-023.html), Harris and Stephens, AVC 1988
    - [SIFT: Distinctive Image Features from Scale-Invariant Keypoints](https://link.springer.com/article/10.1023/B:VISI.0000029664.99615.94), Lowe, IJCV 2004
    - [SURF: Speeded Up Robust Features](https://link.springer.com/chapter/10.1007/11744023_32), Bay et al., ECCV 2006
    - [ORB: An efficient alternative to SIFT or SURF](https://ieeexplore.ieee.org/document/6126544), Rublee et al., ICCV 2011
    ---
- Learning-Based
    - [LF-Net: Learning Local Features from Images](), Ono et al., NeurIPS 2017
    - [SuperPoint: Self-Supervised Interest Point Detection and Description](https://arxiv.org/abs/1712.07629), DeTone et al., CVPR 2018 Workshop
    - [R2D2: Repeatable and Reliable Detector and Descriptor](https://arxiv.org/abs/1906.06195), Revaud et al., NeurIPS 2019
    - [D2-Net: A Trainable CNN for Joint Description and Detection of Local Features](https://arxiv.org/abs/1905.03561), Dusmanu et al., CVPR 2019

#### Feature Matching
- Classical
    - [FLANN: Scalable Nearest Neighbor Algorithms for High Dimensional Data](https://ieeexplore.ieee.org/document/6809191), Muja and Lowe, TPAMI 2014
    - [GMS: Grid-based Motion Statistics for Fast, Ultra-robust Feature Correspondence](https://ieeexplore.ieee.org/document/8099785), Bian et al., CVPR 2017
    ---
- Learning-Based
    - [Deep Graphical Feature Learning for the Feature Matching Problem](https://openaccess.thecvf.com/content_ICCV_2019/html/Zhang_Deep_Graphical_Feature_Learning_for_the_Feature_Matching_Problem_ICCV_2019_paper.html), Zhang and Lee, ICCV 2019
    - [SuperGlue: Learning Feature Matching with Graph Neural Networks](https://arxiv.org/abs/1911.11763), Sarlin et al., CVPR 2020
#### Motion Estimation
- Classical
    - [In defense of the eight-point algorithm](https://ieeexplore.ieee.org/abstract/document/601246), Hartley, TPAMI 1997
    - [An efficient solution to the five-point relative pose problem](https://ieeexplore.ieee.org/abstract/document/1288525?casa_token=SdQVAwGw1SsAAAAA:ehTyMRy_9qvpPNPduQaWiVWoO5SlEmfFtnXL222Ojg9icueDFUKXjVcr-DojSetVXSe4l76rduc), Nistér, TPAMI 2004
    ---
- Learning-Based
    - [Deep Image Homography Estimation](https://arxiv.org/abs/1606.03798), DeTone et al., arXiv 2016
    - [Unsupervised Learning of Depth and Ego-Motion from Video](https://people.eecs.berkeley.edu/~tinghuiz/projects/SfMLearner/cvpr17_sfm_final.pdf), Zhou et al., CVPR 2017
    - [GeoNet: Unsupervised Learning of Dense Depth, Optical Flow and Camera Pose](https://openaccess.thecvf.com/content_cvpr_2018/html/Yin_GeoNet_Unsupervised_Learning_CVPR_2018_paper.html), Yin et al., CVPR 2018
    - [Unsupervised Learning of Depth and Ego-Motion From Monocular Video Using 3D Geometric Constraints](https://openaccess.thecvf.com/content_cvpr_2018/html/Mahjourian_Unsupervised_Learning_of_CVPR_2018_paper.html), Mahjourian et al., CVPR 2018
#### Loop Closure

- Classical
    - [Detecting Loop Closure with Scene Sequences](https://link.springer.com/article/10.1007/s11263-006-0020-1), Ho and Newman, IJCV 2007
    - [Bags of Binary Words for Fast Place Recognition in Image Sequences](https://ieeexplore.ieee.org/abstract/document/6202705/), Gálvez-López and Tardos, T-RO 2012
    ---
- Learning-Based
    - [Patch-NetVLAD: Multi-Scale Fusion of Locally-Global Descriptors for Place Recognition](https://arxiv.org/abs/2103.01486), Hausler et al., CVPR 2021
#### Bundle Adjustment

- Classical
    - [Bundle Adjustment — A Modern Synthesis](https://lear.inrialpes.fr/pubs/2000/TMHF00/Triggs-va99.pdf), Triggs et al., IWVA 1999
    ---
- Learning-Based
    - [BA-Net: Dense Bundle Adjustment Network](https://arxiv.org/abs/1806.04807), Tang and Tan, ICLR 2018

#### Event Camera
- [Real-time 3D reconstruction and 6-DoF tracking with an event camera](https://link.springer.com/chapter/10.1007/978-3-319-46466-4_21), Kim et al., ECCV 2016
- [EVO: A Geometric Approach to Event-Based 6-DOF Parallel Tracking and Mapping in Real Time](https://ieeexplore.ieee.org/abstract/document/7797445), Rebecq et al., RA-L 2016
- [Simultaneous Optical Flow and Intensity Estimation From an Event Camera](https://openaccess.thecvf.com/content_cvpr_2016/html/Bardow_Simultaneous_Optical_Flow_CVPR_2016_paper.html), Bardow et al., CVPR 2016
- [Ultimate SLAM? Combining Events, Images, and IMU for Robust Visual SLAM in HDR and High-Speed Scenarios](https://arxiv.org/abs/1709.06310), Vidal, RA-L 2018
- [Event-based Vision: A Survey](https://arxiv.org/abs/1904.08405), Gallego et al., arXiv 2019

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

#### Graph Optimization

- [Ceres Solver](https://github.com/ceres-solver/ceres-solver), Agarwal et al., 2010
- [g2o: A General Framework for Graph Optimization](https://github.com/RainerKuemmerle/g2o), Kümmerle et al., ICRA 2011
- [GTSAM: General smoothing and mapping library for Robotics and SFM](https://collab.cc.gatech.edu/borg/gtsam?destination=node%2F299), Dellaert, 2012

#### Visual Odometry

- [DVO: Dense Visual Odometry](https://github.com/tum-vision/dvo_slam), Steinbruecker et al. ICCV 2011
- [SVO: Fast semi-direct monocular visual odometry](https://github.com/uzh-rpg/rpg_svo), Forster et al., ICRA 2014
- [DSO: Direct Sparse Odometry](https://github.com/JakobEngel/dso_ros), Engel et al., TPAMI 2017
- [Kimera: an Open-Source Library for Real-Time Metric-Semantic Localization and Mapping](https://github.com/MIT-SPARK/Kimera), Rosinol et al., ICRA 2020

#### vSLAM

- [MonoSLAM: Real-Time Single Camera SLAM](https://github.com/rrg-polito/mono-slam), Davison et al., TPAMI 2007
- [PTAM: Parallel Tracking and Mapping](http://www.robots.ox.ac.uk/~gk/PTAM/), Klein and Murray, ISMAR 2007
- [LSD-SLAM: Large-Scale Direct Monocular SLAM](https://github.com/tum-vision/lsd_slam), Engel et al., ECCV 2014
- [ORB-SLAM: a Versatile and Accurate Monocular SLAM System](https://github.com/raulmur/ORB_SLAM), Mur-Artal et al., T-RO 2015
- [ORB-SLAM2: an Open-Source SLAM System for Monocular, Stereo and RGB-D Cameras](https://github.com/raulmur/ORB_SLAM2), Mur-Artal et al., T-RO 2017
- [OpenVSLAM: A Versatile Visual SLAM Framework](https://github.com/xdspacelab/openvslam), Sumikura et al., ACM MM 2019
- [ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial and Multi-Map SLAM](https://arxiv.org/abs/2007.11898), Campos et al., Arxiv 2020

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)