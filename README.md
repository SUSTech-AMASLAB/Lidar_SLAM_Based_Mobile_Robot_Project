# Lidar SLAM Based Mobile Robot Project

> @Brief：该仓库是AMASLAB 基于激光SLAM的移动机器人系统（Lidar SLAM Based Mobile Robot Project）项目文档。
>
> @Author：[Dong Li](https://github.com/DoongLi)
>
> @Date：2022-10-13
>
> @Github Link：[https://github.com/SUSTech-AMASLAB/Lidar_SLAM_Based_Mobile_Robot_Project](https://github.com/SUSTech-AMASLAB/Lidar_SLAM_Based_Mobile_Robot_Project)
>
> @Project Author：[Dong Li](https://github.com/DoongLi)

## Introduction

**Project**：Lidar SLAM Based Mobile Robot Project /基于激光SLAM的移动机器人系统

 **Requirements**：

- 1.基于相关硬件，分别用**2D 激光SLAM和3D激光的方案** 构建场景地图，并完成自主导航等功能；其中2D激光SLAM算法包括：Gmapping、Karto SLAM、Cartographer。
- 2.在本仓库上，撰写相关学习、调试、方案以及相关问题文档，并将能实现上述功能的可重复 系统框架 整合到仓库中。

**Device**：松灵TRACER-MINI移动底盘、EPIC-KBS9工控机、LDS-E300-E 2D激光雷达、C16-121B 3D激光雷达。

## Outline

#### 1.阅读实验室协作项目文档

**Requirements**：掌握项目完成流程和相关要求。

**Reference**：[https://github.com/SUSTech-AMASLAB/AMASLAB_Collaboration_Project_Doc](https://github.com/SUSTech-AMASLAB/AMASLAB_Collaboration_Project_Doc)

#### 2.基础内容学习

 **Requirements**：linux（Ubuntu）、Python、C++、ROS

**Reference**：[https://github.com/SUSTech-AMASLAB/Tutorial_for_Direction_Of_Robotics](https://github.com/SUSTech-AMASLAB/Tutorial_for_Direction_Of_Robotics)

#### 3.相关硬件调试

项目相关硬件如下：

- 1.EPIC-KBS9工控机：[https://github.com/SUSTech-AMASLAB/EPIC-KBS9](https://github.com/SUSTech-AMASLAB/EPIC-KBS9)
- 2.松灵TRACER-MINI移动底盘：https://github.com/SUSTech-AMASLAB/TRACER-MINI
- 3.C16-121B 3D激光雷达：https://github.com/SUSTech-AMASLAB/Lidar_C16-121B
- 4.Lidar LDS-E300-E激光雷达：[https://github.com/SUSTech-AMASLAB/Lidar_LDS-E300-E](https://github.com/SUSTech-AMASLAB/Lidar_LDS-E300-E)

#### 3.相关算法框架学习

- Gmapping：https://wiki.ros.org/slam_gmapping
- Karto SLAM：https://github.com/tu-darmstadt-ros-pkg/hector_slam
- Cartographer：https://github.com/cartographer-project/cartographer
- ROS Navigation：http://wiki.ros.org/navigation

#### 4.项目参考方案实现

Reference :

- 1.**cartographer**2D激光雷达SLAM算法实现 ：[https://github.com/cartographer-project/cartographer](https://github.com/cartographer-project/cartographer)
- 2.3D激光雷达SLAM实现：
  - LOAM：https://github.com/cuitaixiang/LOAM_NOTED

#### 5.整理相关项目资料

整理项目视频、图片、文档和工程代码 , **同时项目发布者和协同项目完成者制作项目主页** . 

## File Description

- **README.md**：项目总体文档，

  