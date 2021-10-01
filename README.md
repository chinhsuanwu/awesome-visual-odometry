# Awesome Visual Odometry [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Table of Contents

- [Papers](#papers)
- [Datasets](#datasets)
- [Tools](#tools)
- [Learning](#courses)

## Papers

#### System

- [Real-time simultaneous localisation and mapping with a single camera](https://ieeexplore.ieee.org/abstract/document/1238654), Davison, ICCV 2003
- [Visual Odometry](https://ieeexplore.ieee.org/abstract/document/1315094?casa_token=9MFPKQrYt0oAAAAA:se45fHIngWObVwjYS5y3Dhlo5WPb8b-K8an41ecJhDVwFhCqUzEObJXvZx95f9VO0qm3TVTrlTY), Nistér et al., CVPR 2004
- [MonoSLAM: Real-Time Single Camera SLAM](https://ieeexplore.ieee.org/abstract/document/4160954), Davison et al., TPAMI 2007 | [code](https://github.com/rrg-polito/mono-slam)
- [Parallel tracking and mapping for small AR workspaces](https://www.robots.ox.ac.uk/~gk/publications/KleinMurray2007ISMAR.pdf), Klein and Murray, ISMAR 2007 | [code](http://www.robots.ox.ac.uk/~gk/PTAM/)
- [Real-time stereo visual odometry for autonomous ground vehicles](https://ieeexplore.ieee.org/document/4651147), Howard, IROS 2008
- [StereoScan: Dense 3d reconstruction in real-time](https://ieeexplore.ieee.org/document/5940405), Geiger et al., IV 2011
- [DTAM: Dense tracking and mapping in real-time](https://ieeexplore.ieee.org/abstract/document/6126513), Newcombe et al., ICCV 2011
- [Real-Time Visual Odometry from Dense RGB-D Images](https://vision.cs.tum.edu/_media/spezial/bib/steinbruecker_sturm_cremers_iccv11.pdf), Steinbruecker et al., ICCV 2011 | [code](https://github.com/tum-vision/dvo_slam)
- [KinectFusion: Real-time dense surface mapping and tracking](https://ieeexplore.ieee.org/abstract/document/6162880), Newcombe et al., ISMAR 2011
- [Robust Odometry Estimation for RGB-D Cameras](https://vision.in.tum.de/_media/spezial/bib/kerl13icra.pdf), Kerl et al., ICRA 2013 | [code](https://github.com/tum-vision/dvo_slam)
- [SVO: Fast semi-direct monocular visual odometry](https://ieeexplore.ieee.org/document/6906584), Forster et al., ICRA 2014 | [code](https://github.com/uzh-rpg/rpg_svo)
- [LSD-SLAM: Large-Scale Direct Monocular SLAM](https://link.springer.com/chapter/10.1007/978-3-319-10605-2_54), Engel et al., ECCV 2014 | [code]((https://github.com/tum-vision/lsd_slam))
- [DynamicFusion: Reconstruction and tracking of non-rigid scenes in real-time](https://ieeexplore.ieee.org/document/7298631), Newcombe et al., CVPR 2015
- [ElasticFusion: Dense SLAM without a pose graph](http://roboticsproceedings.org/rss11/p01.pdf), Whelan et al., RSS 2015
- [ORB-SLAM: a Versatile and Accurate Monocular SLAM System](https://ieeexplore.ieee.org/document/7219438), Mur-Artal et al., T-RO 2015 | [code](https://github.com/raulmur/ORB_SLAM)
- [DeepVO: Towards End-to-End Visual Odometry with Deep Recurrent Convolutional Neural Networks](https://arxiv.org/abs/1709.08429), Wang et al., ICRA 2017
- [ORB-SLAM2: an Open-Source SLAM System for Monocular, Stereo and RGB-D Cameras](https://arxiv.org/abs/1610.06475), Mur-Artal et al., T-RO 2017 | [code](https://github.com/raulmur/ORB_SLAM2)
- [DSO: Direct Sparse Odometry](https://ieeexplore.ieee.org/iel7/34/4359286/07898369.pdf), Engel et al., TPAMI 2017 | [code](https://github.com/JakobEngel/dso_ros)
- [Unsupervised Learning of Monocular Depth Estimation and Visual Odometry with Deep Feature Reconstruction](https://openaccess.thecvf.com/content_cvpr_2018/html/Zhan_Unsupervised_Learning_of_CVPR_2018_paper.html), Zhan et al., CVPR 2018
- [CodeSLAM - Learning a Compact, Optimisable Representation for Dense Visual SLAM](https://arxiv.org/abs/1804.00874), Bloesch et al., CVPR 2018
- [Deep Virtual Stereo Odometry: Leveraging Deep Depth Prediction for Monocular Direct Sparse Odometry](https://openaccess.thecvf.com/content_ECCV_2018/html/Nan_Yang_Deep_Virtual_Stereo_ECCV_2018_paper.html), Yang et al., ECCV 2018
- [DynaSLAM: Tracking, Mapping and Inpainting in Dynamic Scenes](https://arxiv.org/abs/1806.05620), Bescos et al., RA-L 2018 | [code](https://github.com/BertaBescos/DynaSLAM)
- [OpenVSLAM: A Versatile Visual SLAM Framework](https://arxiv.org/abs/1910.01122), Sumikura et al., ACM MM 2019 | [code](https://github.com/xdspacelab/openvslam)
- [D3VO: Deep Depth, Deep Pose and Deep Uncertainty for Monocular Visual Odometry](https://arxiv.org/abs/2003.01060), Yang et al., CVPR 2020
- [Kimera: an Open-Source Library for Real-Time Metric-Semantic Localization and Mapping](https://github.com/MIT-SPARK/Kimera), Rosinol et al., ICRA 2020 | [code](https://arxiv.org/abs/1910.02490)
- [DXSLAM: A Robust and Efficient Visual SLAM System with Deep Features](https://arxiv.org/pdf/2008.05416), Li et al., IROS 2020 | [code](https://github.com/ivipsourcecode/dxslam)
- [ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial and Multi-Map SLAM](https://arxiv.org/abs/2007.11898), Campos et al., arXiv 2020 | [code](https://github.com/UZ-SLAMLab/ORB_SLAM3)
- [Generalizing to the Open World: Deep Visual Odometry with Online Adaptation](https://arxiv.org/abs/2103.15279), Li et al., CVPR 2021
- [Tight Integration of Feature-based Relocalization in Monocular Direct Visual Odometry](https://arxiv.org/abs/2102.01191), Gladkova et al., ICRA 2021
- [DROID-SLAM: Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras](https://arxiv.org/abs/2108.10869), Teed and Deng, arXiv 2021 | [code](https://github.com/princeton-vl/DROID-SLAM)

#### Feature

- [SIFT: Distinctive Image Features from Scale-Invariant Keypoints](https://link.springer.com/article/10.1023/B:VISI.0000029664.99615.94), Lowe, IJCV 2004
- [SURF: Speeded Up Robust Features](https://link.springer.com/chapter/10.1007/11744023_32), Bay et al., ECCV 2006
- [Faster and Better: A Machine Learning Approach to Corner Detection](https://ieeexplore.ieee.org/document/4674368), Rosten et al., TPAMI 2010.
- [ORB: An efficient alternative to SIFT or SURF](https://ieeexplore.ieee.org/document/6126544), Rublee et al., ICCV 2011
- [FLANN: Scalable Nearest Neighbor Algorithms for High Dimensional Data](https://ieeexplore.ieee.org/document/6809191), Muja and Lowe, TPAMI 2014
- [GMS: Grid-based Motion Statistics for Fast, Ultra-robust Feature Correspondence](https://ieeexplore.ieee.org/document/8099785), Bian et al., CVPR 2017
- [LF-Net: Learning Local Features from Images](https://arxiv.org/abs/1805.09662), Ono et al., NeurIPS 2017
- [SuperPoint: Self-Supervised Interest Point Detection and Description](https://arxiv.org/abs/1712.07629), DeTone et al., CVPR 2018 Workshop
- [R2D2: Repeatable and Reliable Detector and Descriptor](https://arxiv.org/abs/1906.06195), Revaud et al., NeurIPS 2019
- [D2-Net: A Trainable CNN for Joint Description and Detection of Local Features](https://arxiv.org/abs/1905.03561), Dusmanu et al., CVPR 2019
- [Deep Graphical Feature Learning for the Feature Matching Problem](https://openaccess.thecvf.com/content_ICCV_2019/html/Zhang_Deep_Graphical_Feature_Learning_for_the_Feature_Matching_Problem_ICCV_2019_paper.html), Zhang and Lee, ICCV 2019
- [SuperGlue: Learning Feature Matching with Graph Neural Networks](https://arxiv.org/abs/1911.11763), Sarlin et al., CVPR 2020
- [High-dimensional Convolutional Networks for Geometric Pattern Recognition](https://arxiv.org/abs/2005.08144), Choy et al., CVPR 2020
- [LoFTR: Detector-Free Local Feature Matching with Transformers](https://arxiv.org/abs/2104.00680), Sun et al., CVPR 2021
- [Co-Attention for Conditioned Image Matching](https://arxiv.org/abs/2007.08480), Wiles et al., CVPR 2021

#### Motion Estimation

- [In defense of the eight-point algorithm](https://ieeexplore.ieee.org/abstract/document/601246), Hartley, TPAMI 1997
- [An efficient solution to the five-point relative pose problem](https://ieeexplore.ieee.org/abstract/document/1288525?casa_token=SdQVAwGw1SsAAAAA:ehTyMRy_9qvpPNPduQaWiVWoO5SlEmfFtnXL222Ojg9icueDFUKXjVcr-DojSetVXSe4l76rduc), Nistér, TPAMI 2004
- [PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization](https://www.cv-foundation.org/openaccess/content_iccv_2015/html/Kendall_PoseNet_A_Convolutional_ICCV_2015_paper.html), Kendall et al., ICCV 2015
- [Deep Image Homography Estimation](https://arxiv.org/abs/1606.03798), DeTone et al., arXiv 2016
- [Unsupervised Learning of Depth and Ego-Motion from Video](https://people.eecs.berkeley.edu/~tinghuiz/projects/SfMLearner/cvpr17_sfm_final.pdf), Zhou et al., CVPR 2017
- [GeoNet: Unsupervised Learning of Dense Depth, Optical Flow and Camera Pose](https://openaccess.thecvf.com/content_cvpr_2018/html/Yin_GeoNet_Unsupervised_Learning_CVPR_2018_paper.html), Yin et al., CVPR 2018
- [Unsupervised Learning of Depth and Ego-Motion From Monocular Video Using 3D Geometric Constraints](https://openaccess.thecvf.com/content_cvpr_2018/html/Mahjourian_Unsupervised_Learning_of_CVPR_2018_paper.html), Mahjourian et al., CVPR 2018


#### Event Camera
- [Real-time 3D reconstruction and 6-DoF tracking with an event camera](https://link.springer.com/chapter/10.1007/978-3-319-46466-4_21), Kim et al., ECCV 2016
- [EVO: A Geometric Approach to Event-Based 6-DOF Parallel Tracking and Mapping in Real Time](https://ieeexplore.ieee.org/abstract/document/7797445), Rebecq et al., RA-L 2016
- [Simultaneous Optical Flow and Intensity Estimation From an Event Camera](https://openaccess.thecvf.com/content_cvpr_2016/html/Bardow_Simultaneous_Optical_Flow_CVPR_2016_paper.html), Bardow et al., CVPR 2016
- [Ultimate SLAM? Combining Events, Images, and IMU for Robust Visual SLAM in HDR and High-Speed Scenarios](https://arxiv.org/abs/1709.06310), Vidal, RA-L 2018
- [Combining Events and Frames using Recurrent Asynchronous Multimodal Networks for Monocular Depth Prediction](https://arxiv.org/abs/2102.09320), Gehrig et al., RA-L, 2021

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

## Tools

#### Graph Optimization

- [Ceres Solver](https://github.com/ceres-solver/ceres-solver), Agarwal et al., 2010
- [g2o](https://github.com/RainerKuemmerle/g2o), Kümmerle et al., ICRA 2011
- [GTSAM](https://collab.cc.gatech.edu/borg/gtsam?destination=node%2F299), Dellaert, 2012

#### Loop Closure Detection

- [DBoW](https://github.com/dorian3d/DBoW2), Galvez-López and Tardos, T-RO 2012

#### Visualization

- [Pangolin](https://github.com/stevenlovegrove/Pangolin), Lovegrove et al., 2010

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
- [Event-based Vision: A Survey](https://arxiv.org/abs/1904.08405), Gallego et al., arXiv 2019
- [A Survey on Deep Learning for Localization and Mapping: Towards the Age of Spatial Machine Intelligence](https://arxiv.org/abs/2006.12567), Chen et al., arXiv 2020.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)