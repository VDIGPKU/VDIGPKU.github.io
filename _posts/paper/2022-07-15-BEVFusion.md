---
title:  'BEVFusion: A Simple and Robust LiDAR-Camera Fusion Framework'  #  Paper title, covered by ''
teser: 2022bevfusion.png
type:   paper
pro_type: Autonomous Driving
layout: post  #  Do not change this
date:   2022-11-01 11:59:59 +0800  # paper pub data, only change year and month according to this format
author: Tingting Liang, Hongwei Xie, Kaicheng Yu, Zhongyu Xia, Zhiwei Lin, Yongtao Wang, Tao Tang, Bing Wang, Zhi Tang # authors information
venue:  NeurIPS 2022
year:   2022  # paper year, number
month:  November # paper month, full name
projectPage: None  # If has project page, link here, otherwise None
supplemental : https://proceedings.neurips.cc/paper_files/paper/2022/file/43d2b7fbee8431f7cef0d0afed51c691-Supplemental-Conference.pdf
data: None  # If has data, post data link here, otherwise None
code: https://github.com/VDIGPKU/BEVFusion  # If has data, post code link here, otherwise None
paperLink: https://proceedings.neurips.cc/paper_files/paper/2022/hash/43d2b7fbee8431f7cef0d0afed51c691-Abstract-Conference.html # post paper pdf link here
---

Fusing the camera and LiDAR information has become a de-facto standard for
3D object detection tasks. Current methods rely on point clouds from the LiDAR
sensor as queries to leverage the feature from the image space. However, people
discovered that this underlying assumption makes the current fusion framework
infeasible to produce any prediction when there is a LiDAR malfunction, regardless
of minor or major. This fundamentally limits the deployment capability to realistic
autonomous driving scenarios. In contrast, we propose a surprisingly simple
yet novel fusion framework, dubbed BEVFusion, whose camera stream does not
depend on the input of LiDAR data, thus addressing the downside of previous
methods. We empirically show that our framework surpasses the state-of-the-art
methods under the normal training settings. Under the robustness training settings
that simulate various LiDAR malfunctions, our framework significantly surpasses
the state-of-the-art methods by 15.7% to 28.9% mAP. To the best of our knowledge,
we are the first to handle realistic LiDAR malfunction and can be deployed to
realistic scenarios without any post-processing procedure. The code is available at
https://github.com/VDIGPKU/BEVFusion.
