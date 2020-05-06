# awesome-depth

A curated list of publication for depth estimation

## 0. Survey 
[1] Dijk et al, How do neural networks see depth in single images? [PDF](https://arxiv.org/pdf/1905.07005.pdf)

[2] Amlaan et al, Monocluar depth estimation: A survey, [PDF](https://arxiv.org/pdf/1901.09402.pdf)

[3] Zhao et al, Monocular Depth Estimation Based On Deep Learning: An Overview, [PDF](https://arxiv.org/pdf/2003.06620.pdf)

## 1. Monocular Depth (Fully Supervised)

[1] Eigen et al, Depth Map Prediction from a Single Image using a Multi-Scale Deep Network, NIPS 2014, [Web](https://cs.nyu.edu/~deigen/depth/)

[2] Eigen et al, Predicting Depth, Surface Normals and Semantic Labels with a Common Multi-Scale Convolutional Architecture, ICCV 2015, [Web](https://cs.nyu.edu/~deigen/dnl/)

[3] Laina et al, Deeper Depth Prediction with Fully Convolutional Residual Networks, 3DV 2016, [Code](https://github.com/iro-cp/FCRN-DepthPrediction)

[4] Chen et al, Single-Image Depth Perception in the Wild, NIPS 2016, [Web](http://www-personal.umich.edu/~wfchen/depth-in-the-wild/)

[5] Li et al, A Two-Streamed Network for Estimating Fine-Scaled Depth Maps from Single RGB Images, ICCV 2017, [PDF](http://arxiv.org/abs/1607.00730)

[6] Xu et al, Structured Attention Guided Convolutional Neural Fields for Monocular Depth Estimation, CVPR 2018, [PDF](https://arxiv.org/abs/1803.11029)

[7] Xu et al, PAD-Net: Multi-Tasks Guided Prediction-and-Distillation Network, CVPR 2018, [PDF](https://arxiv.org/abs/1805.04409)

[8] Qi et al, GeoNet: Geometric Neural Network for Joint Depth and Surface Normal Estimation, CVPR 2018, [PDF](https://xjqi.github.io/geonet.pdf)

[9] Fu et al, Deep Ordinal Regression Network for Monocular Depth Estimation, CVPR 2018, [PDF](https://arxiv.org/abs/1806.02446)

[10] Zhang et al, Joint Task-Recursive Learning for Semantic Segmentation and Depth Estimation, ECCV 2018, [PDF](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zhenyu_Zhang_Joint_Task-Recursive_Learning_ECCV_2018_paper.pdf)

[11] Jiao et al, Look Deeper into Depth: Monocular Depth Estimation with Semantic Booster and Attention-Driven Loss, ECCV 2018, [PDF](http://openaccess.thecvf.com/content_ECCV_2018/papers/Jianbo_Jiao_Look_Deeper_into_ECCV_2018_paper.pdf)

[12] Cheng et al, Depth Esimation via Affinity Learning with Convolutional Spatial Propagation Network, ECCV 2018, [PDF](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xinjing_Cheng_Depth_Estimation_via_ECCV_2018_paper.pdf), [Code](https://github.com/XinJCheng/CSPN)

[13] Lee et al, Monocular depth estimation using relative depth maps, CVPR 2019, [PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Lee_Monocular_Depth_Estimation_Using_Relative_Depth_Maps_CVPR_2019_paper.pdf),  [Code](https://github.com/jaehanlee-mcl/monocular-depth-estimation-using-relative-depth-maps)

[14] Lee et al, From Big to Small: Multi-Scale Local Planar Guidance for Monocular Depth Estimation, Arxiv, [PDF](https://arxiv.org/pdf/1907.10326.pdf), [Code](https://github.com/cogaplex-bts/bts)

[15] Zhang et al, Pattern-Affinitive Propagation across Depth, Surface Normal and Semantic Segmentation, CVPR 2019, [PDF](https://arxiv.org/pdf/1906.03525v1.pdf)

[16] Zhang et al, Exploiting temporal consistency for real-time video depth estimation, ICCV 2019, [PDF](https://arxiv.org/pdf/1908.03706.pdf), [Code](https://github.com/hkzhang91/ST-CLSTM)


## 2. Monocular Depth (Semi- / Un-Supervised)

### 2.1 Stereo Consistency

[1] Garg et al, Unsupervised CNN for Single View Depth Estimation: Geometry to the Rescue, ECCV 2016,  [Code](https://github.com/Ravi-Garg/Unsupervised_Depth_Estimation)

[2] Godard et al, Unsupervised Monocular Depth Estimation with Left-Right Consistency, CVPR 2017, [Web](http://visual.cs.ucl.ac.uk/pubs/monoDepth/)

[3] Kuznietsov et al, Semi-Supervised Deep Learning for Monocular Depth Map Prediction, CVPR 2017, [Code](https://github.com/Yevkuzn/semodepth)

[4] Luo et al, Single View Stereo Matching, CVPR 2018, [Code](https://github.com/lawy623/SVS)

[5] Godard et al, Digging Into Self-Supervised Monocular Depth Estimation, aXiv 2018, [PDF](https://arxiv.org/abs/1711.07933)

[6] Lai et al, Bridging Stereo Matching and Optical Flow via Spatio temporal, CVPR 2019, [PDF](https://arxiv.org/pdf/1905.09265.pdf), [Code](https://github.com/lelimite4444/)

[7] Tosi et al, Learning monocular depth estimation infusing traditional stereo knowledge, CVPR 2019, [PDF](https://arxiv.org/pdf/1904.04144.pdf) [Code](https://github.com/fabiotosi92/monoResMatch-Tensorflow)

[8] Garg et al, Learning Single Camera Depth Estimation using Dual-Pixels, ICCV 2019, [PDF](https://arxiv.org/pdf/1904.05822.pdf) [Code](https://github.com/google-research/google-research/tree/master/dual_pixels)

[9] Zhang et al, Du2Net: Learning Depth Estimation from Dual-Cameras and Dual-Pixels, arXiv 2020, [PDF](https://arxiv.org/pdf/2003.14299.pdf)


### 2.2 Multi View

[1] Zhou et al, Unsupervised Learning of Depth and Ego-Motion from Video, CVPR 2017, [Web](https://people.eecs.berkeley.edu/~tinghuiz/projects/SfMLearner/)

[2] Im et al, Robust Depth Estimation from Auto Bracketed Images, CVPR 2018, [PDF](https://arxiv.org/abs/1803.07702)

[3] Yin et al, GeoNet: Unsupervised Learning of Dense Depth, Optical Flow and Camera Pose, CVPR 2018,[Code](https://github.com/yzcjtr/GeoNet)

[4] Wang et al, Learning Depth from Monocular Videos using Direct Methods, CVPR 2018, [Code](https://github.com/MightyChaos/LKVOLearner)

[5] Yang et al, LEGO: Learning Edge with Geometry all at Once by Watching Videos, CVPR 2018, [Code](https://github.com/zhenheny/LEGO)

[6] Mahjourian et al, Unsupervised Learning of Depth and Ego-Motion from Monocular Video
Using 3D Geometric Constraints, CVPR 2018, [PDF](https://arxiv.org/abs/1802.05522)

[7] Zhan et al, Unsupervised Learning of Monocular Depth Estimation and Visual Odometry
with Deep Feature Reconstruction, CVPR 2018, [Web](https://github.com/Huangying-Zhan/Depth-VO-Feat)

[8] Ran et al, Competitive Collaboration: Joint Unsupervised Learning of Depth, Camera Motion, Optical Flow and Motion Segmentation, CVPR 2019, [PDF](https://arxiv.org/pdf/1805.09806.pdf), [Code](https://github.com/anuragranj/cc)

[9] Bian et al, Unsupervised Scale-consistent Depth and Ego-motion Learning from Monocular Video, NIPS 2019, [PDF](https://arxiv.org/pdf/1908.10553.pdf), [Code](https://github.com/JiawangBian/SC-SfMLearner-Release)
 
[10] Luo et al, Consistent Video Depth Estimation, SIGGRAPH 2020, [Web](https://roxanneluo.github.io/Consistent-Video-Depth-Estimation/)

[11] Teed et al, DEEPV2D: VIDEO TO DEPTH WITH DIFFERENTIABLE STRUCTURE FROM MOTION, ICLR 2020, [PDF](https://openreview.net/pdf?id=HJeO7RNKPr) [Code](https://github.com/princeton-vl/DeepV2D)

## 3. Depth Completion/Super-resolution

[1] Cheng et al, Learning Depth with Convolutional Spatial Propagation Network, arXiv 2018, [PDF](https://arxiv.org/pdf/1810.02695.pdf), [Code](https://github.com/XinJCheng/CSPN)

[2] Zhang et al, Deep Depth Completion of a Single RGB-D Image, CVPR 2018, [PDF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Deep_Depth_Completion_CVPR_2018_paper.pdf)

[3] Qiu et al, DeepLiDAR: Deep Surface Normal Guided Depth Prediction for Outdoor Scene from Sparse LiDAR Data and Single Color Image, CVPR 2019, [PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Qiu_DeepLiDAR_Deep_Surface_Normal_Guided_Depth_Prediction_for_Outdoor_Scene_CVPR_2019_paper.pdf), [Code](https://github.com/JiaxiongQ/DeepLiDAR)

[4] Chen et al, Learning Joint 2D-3D Representations for Depth Completion, ICCV 2019, [PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Learning_Joint_2D-3D_Representations_for_Depth_Completion_ICCV_2019_paper.pdf)

[5] Tang et al, Learning Guided Convolutional Network for Depth Completion, arXiv 2019, [PDF](https://arxiv.org/pdf/1908.01238.pdf),  [Code](https://github.com/kakaxi314/GuideNet)

## 4. Depth Fusion

[1] Marin et al, Reliable Fusion of ToF and Stereo Depth Driven by Confidence Measures, ECCV 2016, [PDF](https://lttm.dei.unipd.it//paper_data/eccv16/LCfusion-eccv16.pdf)

[2] Agresti et al, Deep Learning for Confidence Information in Stereo and ToF Data Fusion, ICCVW 2017, [Web](https://lttm.dei.unipd.it/paper_data/deepfusion/)


## 5. Depth Dataset

[1] Srinivasan et al, Aperture Supervision for Monocular Depth Estimation, CVPR 2018, [Code](https://github.com/google/aperture_supervision)

[2] Li et al, MegaDepth: Learning Single-View Depth Prediction from Internet Photos, CVPR 2018, [Web](http://www.cs.cornell.edu/projects/megadepth/)

[3] Monocular Relative Depth Perception with Web Stereo Data Supervision, CVPR 2018, [PDF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xian_Monocular_Relative_Depth_CVPR_2018_paper.pdf)

[4] Li et al, Learning the depths of moving people by watching frozen people, CVPR 2019, [Web](https://mannequin-depth.github.io/)

[5] Chen et al, Learning Single-Image Depth from Videos using Quality Assessment Networks, CVPR 2019, [PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Learning_Single-Image_Depth_From_Videos_Using_Quality_Assessment_Networks_CVPR_2019_paper.pdf)

[6] Li et al, Learning the Depths of Moving People by Watching Frozen People, CVPR 2019(oral), [PDF](https://arxiv.org/pdf/1904.11111.pdf)

[7] See [Link](https://scott89.github.io/depth-talk/#/6/1) for more conventional data sets.



## 6. 3D Photography 

[1] Zhou et al, Stereo Magnification: Learning view synthesis using multiplane images, SIGGRAPH 2018, [Web](https://people.eecs.berkeley.edu/~tinghuiz/projects/mpi/)

[2] Niklaus et al, 3D Ken Burns Effect from a Single Image, SIGGRAPH 2019, [PDF](https://arxiv.org/pdf/1909.05483.pdf) [Code](https://github.com/sniklaus/3d-ken-burns)

[3] Wiles et al, SynSin: End-to-end View Synthesis from a Single Image, CVPR 2020, [Web](http://www.robots.ox.ac.uk/~ow/synsin.html)

[4] Shih et al, 3D Photography using Context-aware Layered Depth Inpainting, CVPR 2020, [Web](https://shihmengli.github.io/3D-Photo-Inpainting/)

[5] Mildenhall et al, Representing Scenes as Neural Radiance Fields for View Synthesis, arXiv 2020, [Web](http://www.matthewtancik.com/nerf)

[6] Chen et al, Monocular Neural Image Based Rendering with Continuous View Control, ICCV 2019, [Web](https://ait.ethz.ch/projects/2019/cont-view-synth/)

[7] Chen et al, Learning Efficient Point Cloud Generation for Dense 3D Object Reconstruction, AAAI 2018, [PDF](https://arxiv.org/pdf/1706.07036.pdf)

## 7. RGB-D Application

## 8. Optical Flow & Scene Flow

[1] Dosovitskiy et al, FlowNet: Learning optical flow with convolutional networks, CVPR 2015, [PDF](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Dosovitskiy_FlowNet_Learning_Optical_ICCV_2015_paper.pdf)

[2] Yu et al, Back to basics: Unsupervised learning of optical flow via brightness constancy and motion smoothness, ECCV 2016 Workshop, [PDF](https://arxiv.org/pdf/1608.05842v1.pdf)

[3] Bailer et al, CNN-based Patch Matching for Optical Flow with Thresholded Hinge Embedding Loss, CVPR 2017, [PDF](http://arxiv.org/abs/1607.08064)

[4] Ranjan et al, Optical Flow Estimation using a Spatial Pyramid Network(SpyNet), CVPR 2017, [Code](https://github.com/anuragranj/spynet)

[5] Ilg et al, FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks, CVPR 2017, [Code](https://github.com/lmb-freiburg/flownet2)

[6] Sun et al, PWC-Net: CNNs for Optical Flow Using Pyramid, Warping, and Cost Volume, CVPR 2018, [Code](https://github.com/NVlabs/PWC-Net)

[7] Wang et al, Occlusion Aware Unsupervised Learning of Optical Flow, CVPR 2018, [PDF](http://arxiv.org/abs/1711.05890)

[6] Hui et al, LiteFlowNet: A Lightweight Convolutional Neural Network for Optical Flow Estimation, CVPR 2018, [PDF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hui_LiteFlowNet_A_Lightweight_CVPR_2018_paper.pdf)
