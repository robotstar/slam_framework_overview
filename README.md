# SLAM 框架汇总

## 视觉VO (Visual Odometry)

### 特征点法

#### PTAM

牛津大学 (Oxford)

2007

https://github.com/Oxford-PTAM/PTAM-GPL

https://github.com/ethz-asl/ethzasl_ptam

#### ORB_SLAM系列

西班牙萨拉戈萨大学

2015 2017

http://webdiis.unizar.es/~raulmur/orbslam/

https://github.com/raulmur/ORB_SLAM2

### 直接法

#### LSD_SLAM ( Large-Scale Direct SLAM)

德国慕尼黑工业大学 (TUM)

2014

https://github.com/tum-vision/lsd_slam

#### DSO (Direct Sparse Odometry) 

德国慕尼黑工业大学 (TUM)

2016至今

https://github.com/JakobEngel/dso

https://github.com/JakobEngel/dso_ros

### 半直接法

#### SVO (Semi-Direct Visual Odometry)

瑞士苏黎世大学(UZH)

2014

https://github.com/uzh-rpg/rpg_svo

## 视觉VIO (Visual Inertial Odometry)

### 松耦合

基于卡尔曼滤波方法融合相机位姿和IMU信息

#### SSF(Single Sensor Fusion) and MSF (Multi Sensor Fusion)

瑞士联邦理工大学(ETHZ)

2013

https://github.com/ethz-asl/ethzasl_sensor_fusion

https://github.com/ethz-asl/ethzasl_msf

### 紧耦合

基于滤波的方法: MSCKF, ROVIO

基于图优化的方法: OKVIS

#### OKVIS

瑞士联邦理工大学(ETHZ)

2013

https://github.com/ethz-asl/okvis

#### ROVIO

瑞士联邦理工大学(ETHZ)

2015

<https://github.com/ethz-asl/rovio>

#### VINS-Mono

香港科技大学(HKUST)

2017

https://github.com/HKUST-Aerial-Robotics/VINS-Mono

#### MSCKF

宾夕法尼亚大学(Penn)

2018

https://github.com/KumarRobotics/msckf_vio

## 激光VO (Lidar Odometry)

### LOAM

卡耐基梅隆大学(CMU)

2014

https://github.com/laboshinl/loam_velodyne

### laser_slam

瑞士联邦理工大学(ETHZ)

2016

https://github.com/ethz-asl/laser_slam

### Cartographer

谷歌

2016

https://github.com/googlecartographer/cartographer

https://github.com/googlecartographer/cartographer_ros

### LeGO-LOAM

美国史蒂文斯理工学院 (Stevens Institute of Technology)

2018

https://github.com/RobustFieldAutonomyLab/LeGO-LOAM

# SLAM出色研究小组/实验室网址

瑞士苏黎世大学自动系统实验室: http://www.asl.ethz.ch/

德国慕尼黑大学计算机视觉组: https://vision.in.tum.de/

瑞士苏黎世大学机器人和感知组: http://rpg.ifi.uzh.ch/ 

西班牙萨拉戈萨大学: https://i3a.unizar.es/es

香港科技大学空中机器人组: http://uav.ust.hk/

宾夕法尼亚大学GRASP实验室: https://www.kumarrobotics.org/ 

卡耐基梅隆大学机器人研究所: https://www.ri.cmu.edu/

英国帝国理工大学机器人视觉组: http://wp.doc.ic.ac.uk/robotvision/

英国帝国理工大学戴森机器人实验室: http://www.imperial.ac.uk/dyson-robotics-lab/

德国波恩大学自动智能实验室: http://www.ais.uni-bonn.de/

# Reference

http://www.slamcn.org