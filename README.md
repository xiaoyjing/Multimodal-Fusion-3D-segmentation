# Multi-modal Fusion Neural Networks for 3D Semantic Segmentation: A Review

## **Multi-modal Fusion Neural Networks for 3D Semantic Segmentation: A Review**

This repo is used for recording, tracking, and benchmarking several recent multimodal 3D segmentation methods, as a supplement to our servey.
If you find any work missing or have any suggestions (papers, implementations and other resources), feel free to pull requests. We will add the missing papers to this repo ASAP.

🔥**Highlight!!**  
[1]. Our study covers the latest (2020-2024) progress in the field of deep learning for multimodal 3D point cloud segmentation. It goes beyond existing papers and covers the latest multimodal point cloud segmentation methods that have not been systematically summarized and widely discussed.  
[2]. We have perfected a comprehensive classification method, including symmetric and asymmetric methods, and on this basis, it is subdivided into 6 subcategories based on data, features, and results. Our paper’s classification is relatively objective and clear, and its coverage is relatively comprehensive. By combining these previously unexplored methods, we solved the significant gaps in the existing review papers.  
[3]. We comprehensively compare existing methods on current mainstream datasets and briefly analyze and discuss current multimodal 3D segmentation models. This enables readers to grasp the various methods in the context of their specific advantages and applications.  
[4]. Our paper includes a comprehensive discussion of the current challenges in the field and provides profound directions for future research.


### **Introduction**
In this survey, we present the first detailed survey on multimodal 3D segmentation.
<img width="635" alt="1746777205707" src="https://github.com/user-attachments/assets/b2f0e9ce-4ad7-47b8-8471-7633403a9e7d" />



### **Methods: A Survey**

#### Symmetric Fusion

##### data-data fusion

Year | Venue | Acronym | Paper Title | Code/Project
---- | ----- | ------- | ----------- | ------------
2020 | Neurocomputing | N/A | A spatially enhanced network with camera-lidar fusion for 3D semantic segmentation | N/A
2021 | IEEE Transactions on Intelligent Transportation Systems | N/A | Fast Road Detection by CNN-Based Camera–Lidar Fusion and Spherical Coordinate Transformation | N/A
2023 | IEEE Transactions on Multimedia | LIF-Seg | LIF-Seg: LiDAR and Camera Image Fusion for 3D LiDAR Semantic Segmentation | N/A
2023 | Signal, Image and Video Processing | N/A | U-Net-based RGB and LiDAR image fusion for road segmentation | N/A

##### feature-feature fusion

Year | Venue | Acronym | Paper Title | Code/Project
---- | ----- | ------- | ----------- | ------------
2020 | ECCV  |  EPNet  | EPNet: Enhancing Point Features with Image Semantics for 3D Object Detection | [code](https://github.com/happinesslz/EPNet)
2021 | | N/A | Learning from 2D: Contrastive Pixel-to-Point Knowledge Transfer for 3D Pretraining | N/A
2022 | ECCV | 2DPASS | 2DPASS: 2D Priors Assisted Semantic Segmentation on LiDAR Point Clouds | [code](https://github.com/yanx27/2DPASS)
2022 | IEEE TRANSACTIONS ON PATTERN ANALYSIS AND MACHINE INTELLIGENCE | EPNet++ | EPNet++: Cascade Bi-Directional Fusion for Multi-Modal 3D Object Detection | [code](https://github.com/happinesslz/epnetv2)
2023 | IEEE International Conference on Robotics and Automation | BEVFusion | BEVFusion: Multi-Task Multi-Sensor Fusion with Unified Bird's-Eye View Representation | [code](https://github.com/mit-han-lab/bevfusion)
2023 | CVPR | CMNEXT | Delivering Arbitrary-Modal Semantic Segmentation | [code](https://github.com/jamycheung/DELIVER)
2023 | CVPR | MSeg3D | Multi-modal 3D Semantic Segmentation for Autonomous Driving | ([code](https://github.com/jialeli1/lidarseg3d))
2023 | IEEE Transactions on Circuits and Systems for Video Technology | N/A | A Multi-Phase Camera-LiDAR Fusion Network for 3D Semantic Segmentation With Weak Supervision | N/A
2023 | IEEE TRANSACTIONS ON INTELLIGENT TRANSPORTATION SYSTEMS | CMX | CMX: Cross-Modal Fusion for RGB-X Semantic Segmentation With Transformers | ([code](https://github.com/huaaaliu/RGBX_Semantic_Segmentation))
2023 | EIECS | N/A | A Multi-Modal Fusion 3D Semantic Segmentation Method | N/A
2023 | IEEE ROBOTICS AND AUTOMATION LETTERS | CMDFusion | CMDFusion: Bidirectional Fusion Network With Cross-Modality Knowledge Distillation for LiDAR Semantic Segmentation | [code](https://github.com/Jun-CEN/CMDFusion)
2024 | ICRA | DefFusion | DefFusion: Deformable Multimodal Representation Fusion for 3D Semantic Segmentation | N/A
2024 | ISCAS | CLFusion | CLFusion:3D Semantic Segmentation Based on Camera and Lidar Fusion | N/A
2024 | ICML | GeminiFusion | GeminiFusion: Efficient Pixel-wise Multimodal Fusion for Vision Transformer | [code](https://github.com/JiaDingCN/GeminiFusion)
2024 | IEEE TRANSACTIONS ON PATTERN ANALYSIS AND MACHINE INTELLIGENCE | N/A | Uni-to-Multi Modal Knowledge Distillation for Bidirectional LiDAR-Camera Semantic Segmentation | N/A
2024 | N/A | vFusedSeg3D | vFusedSeg3D | N/A

##### result-result fusion

Year | Venue | Acronym | Paper Title | Code/Project
---- | ----- | ------- | ----------- | ------------
2020 | CVPR | xMUDA | xMUDA: Cross-Modal Unsupervised Domain Adaptation for 3D Semantic Segmentation | [code](https://github.com/valeoai/xmuda)
2021 | ICCV | PMF | Perception-Aware Multi-Sensor Fusion for 3D LiDAR Semantic Segmentation | [code](https://github.com/ICEORY/PMF)
2023 | IEEE Transactions on Circuits and Systems for Video Technology | N/A | A Multi-Phase Camera-LiDAR Fusion Network for 3D Semantic Segmentation With Weak Supervision | N/A
2023 | IEEE TRANSACTIONS ON INTELLIGENT VEHICLES | Multi-Phase Multi-Modal Fusion | Robust 3D Semantic Segmentation Based on Multi-Phase Multi-Modal Fusion for Intelligent Vehicles | N/A
2024 | IEEE Transactions on Pattern Analysis and Machine Intelligence | EPMF | EPMF: Efficient Perception-aware Multi-sensor Fusion for 3D Semantic Segmentation | N/A


#### Asymmetric Fusion

##### Data-feature fusion

Year | Venue | Acronym | Paper Title | Code/Project
---- | ----- | ------- | ----------- | ------------
2024 |  Applied Intelligence | DFAMNet | DFAMNet: dual fusion attention multi-modal network for semantic segmentation on LiDAR point clouds | [code](https://github.com/Pdsn5/DFAMNet)

##### Data-result fusion

Year | Venue | Acronym | Paper Title | Code/Project
---- | ----- | ------- | ----------- | ------------
2020 | IROS | N/A | LiDAR guided Small obstacle Segmentation | N/A
2022 | Sensors | N/A | Enhanced Perception for Autonomous Driving Using Semantic and Geometric Data Fusion | N/A

##### feature-result fusion

Year | Venue | Acronym | Paper Title | Code/Project
---- | ----- | ------- | ----------- | ------------
2023 | International Journal of Automotive Technology | N/A | IMPROVED 3D SEMANTIC SEGMENTATION MODEL BASED ONRGB IMAGE AND LIDAR POINT CLOUD FUSION FORAUTOMANTIC DRIVING | N/A


### **Datasets**

Dataset | Year | Samples (train/val/test) | Evaluation Metrics | Num classes | Characterization | Code/Project
------- | ---- | ------------------------ | ------------------ | ----------- | ---------------- | ------------
SemanticKITTI | 2019 | 19130/4071/20351 | mIoU | 19 | Collected by a Velodyne HDL-64E sensor(64 beams) and a front-view camera.  Sequence 00-10 are available for training and validation. | [code](https://www.semantic-kitti.org/tasks.html#semseg)
Waymo | 2019 | 23691/5976/2982 | mIoU | 23 | Collected by a mid-range lidar (top), four short-range lidars (front, side left, side right, and rear)) of 64 beams and 5 cameras(front, front-left, front-right, side-left, and sideright). | [code](https://waymo.com/open/challenges/2024/3d-semantic-segmentation/)
nuScenes | 2019 | 28130/6019/6008 | mIoU, fwIoU | 17 | 1,000 driving scenes with different weather and light conditions. sparser point cloud (35k points/frame) of 32 beams and RGB images captured by 6 cameras:front, front-left, front-right, back, back-left, and back-right. | [code](https://www.nuscenes.org/lidar-segmentation)
A2D2 | 2020 | 22408/2274/13264 | mIoU | 38 | Collected with six cameras and five Velodyne VLP-16 sensors. | [code](https://www.a2d2.audi/a2d2/en/dataset.html)
RELLIS-3D | 2020 | 7800/2413/3343 | mIoU | 14 | An off-road environment with images and point clouds with semantic-level 3D annotations. | [code](https://github.com/unmannedlab/RELLIS-3D)
DELIVER | 2023 | 3983/2005/1897 | mIoU | 25 | Based on the CARLA simulator to provide six mutually orthogonal views. Include four adverse conditions out of five conditions and each condition has five corner cases. | [code](https://github.com/jamycheung/DELIVER)


