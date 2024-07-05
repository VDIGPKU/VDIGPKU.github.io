---
title:  'DrivingGaussian: Composite Gaussian Splatting for Surrounding Dynamic Autonomous Driving Scenes'  #  Paper title, covered by ''
teser: 2023drivinggaussian.png
type:   paper
pro_type: 3D Reconstruction
layout: post  #  Do not change this
date:   2023-12-01 11:59:59 +0800  # paper pub data, only change year and month according to this format
author: Xiaoyu Zhou, Zhiwei Lin, Xiaojun Shan, Yongtao Wang, Deqing Sun, Ming-Hsuan Yang # authors information
venue:  ICML 2024
year:   2024  # paper year, number
month:  March # paper month, full name
projectPage: https://pkuvdig.github.io/DrivingGaussian/  # If has project page, link here, otherwise None
supplemental : https://openaccess.thecvf.com/content/CVPR2024/html/Zhou_DrivingGaussian_Composite_Gaussian_Splatting_for_Surrounding_Dynamic_Autonomous_Driving_Scenes_CVPR_2024_paper.html
data: None  # If has data, post data link here, otherwise None
code: https://github.com/VDIGPKU/DrivingGaussian  # If has data, post code link here, otherwise None
paperLink: https://openaccess.thecvf.com/content/CVPR2024/html/Zhou_DrivingGaussian_Composite_Gaussian_Splatting_for_Surrounding_Dynamic_Autonomous_Driving_Scenes_CVPR_2024_paper.html # post paper pdf link here
---

We present DrivingGaussian, an efficient and effective framework for surrounding dynamic autonomous driving scenes. For complex scenes with moving objects, we first sequentially and progressively model the static background of the entire scene with incremental static 3D Gaussians. We then leverage a composite dynamic Gaussian graph to handle multiple moving objects, individually reconstructing each object and restoring their accurate positions and occlusion relationships within the scene. We further use a LiDAR prior for Gaussian Splatting to reconstruct scenes with greater details and maintain panoramic consistency. DrivingGaussian outperforms existing methods in dynamic driving scene reconstruction and enables photorealistic surround-view synthesis with high-fidelity and multi-camera consistency.