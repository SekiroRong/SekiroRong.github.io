---
layout: post
title: MODE
subtitle: 3D Moving Object Detection with Event LiDAR Points
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/kvt.png
share-img: /assets/img/path.jpg
tags: [project]
comments: true
---

# MODE:3D Moving Object Detection with Event LiDAR Points
This is the official implementation of:

[MODE:3D Moving Object Detection with Event LiDAR Points](http://arxiv.org/abs/available_soon) 
[Github Linke](https://github.com/SekiroRong/MODE)

## Visualization

![output.gif](/assets/img/MODE.gif)

## Main results

### KITTI 3D MOT(dynamic objects)

|  BEV          |   Car    |  Car    |    Car |  Cyclist| Cyclist|Cyclist |Pedestrian|Pedestrian|Pedestrian|
|---------------|----------|---------|--------|---------|--------|--------|---------|---------|---------|
|  Difficulty   | easy     | moderate|   hard | easy    |moderate|   hard | easy    |moderate |   hard     |
|  SECOND       | 98.96    |  91.86  |  89.31 |  92.67  |  88.17 |  85.92 |  76.28  |  73.91  |  69.23  |
|  PointPillars | 96.49    |  92.90  |  92.27 |  90.88  |  84.04 |  82.17 |  77.24  |  75.57  |  72.73  |
|  Part-A2      | 96.06    |  93.51  |  91.06 |  91.13  |  86.04 |  85.21 |  74.75  |  71.84  |  67.42  |



## Citation
Please consider citing our work as follows if it is helpful.
```
@inproceedings{available soon,
  title={{MODE: 3D Moving Object Detection with Event LiDAR Points}},
  author={Yihang Li*, Yu Rong*, Fu Zhang},
  booktitle={available soon},
  year={2023}
}
```

## Acknowledgments
This project is based on the following codebases.  

* [MMDetection3D](https://github.com/open-mmlab/mmdetection3d)
