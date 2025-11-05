---
title: "A High-resolution Vehicle–pedestrian Trajectory Dataset"
description: "CrossTraj dataset for vehicle–pedestrian interaction modeling and safety analysis"
image: "/images/data1.png"
image: "/images/data2.png"
draft: false
---

High-granularity trajectory data of vehicles and pedestrians is essential for traffic simulation, behavior modeling, and intelligent transportation research. CrossTraj is a bi-season trajectory dataset captured at a midblock crosswalk in Milwaukee, WI, using synchronized panoramic roadside cameras covering 200 meters of roadway. Two one-hour recordings from winter and summer capture seasonal and traffic dynamics. The processing pipeline applies YOLOv9e for detection, DeepSORT for stable multi-object tracking, and monocular 3D estimation for depth, orientation, and dimensions. Detected objects are projected to a real-world ground plane via homography and unified across camera views through a stitching module. Kalman filtering and occlusion-aware smoothing reduce noise and fragmentation. The resulting dataset includes hundreds of continuous trajectories that reveal behaviors such as yielding, hesitation, and near-conflict interactions. Evaluations on identity continuity, alignment, and velocity confirm reliability. CrossTraj provides a benchmark for vehicle-pedestrian interaction studies, urban traffic modeling, and safety analysis, and is publicly available.

<p align="center">
  {{< image src="/images/data1.png" alt="data1" >}}
  {{< image src="/images/data2.png" alt="data1" >}}
</p>






