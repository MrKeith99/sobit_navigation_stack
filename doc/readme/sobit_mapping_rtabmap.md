# RTABMAP

## [rtabmap_ros](http://wiki.ros.org/rtabmap_ros)
- RTAB-Mapは、リアルタイム制約のあるRGB-D SLAMアプローチ

## [rtabmap_ros/Tutorials/Advanced Parameter Tuning](http://wiki.ros.org/rtabmap_ros/Tutorials/Advanced%20Parameter%20Tuning)
- このチュートリアルでは、パフォーマンスを向上させるためにどのパラメータを変更すればよいかを説明します

## [rtabmap_ros/Tutorials/HandHeldMapping](http://wiki.ros.org/rtabmap_ros/Tutorials/HandHeldMapping)
- このチュートリアルでは、rtabmap_rosを、Kinectのようなセンサーを使って、マッピングモードやローカリゼーションモードで、すぐに使えるようにする方法を紹介します。

## [rtabmap_ros/Tutorials/SetupOnYourRobot](http://wiki.ros.org/rtabmap_ros/Tutorials/SetupOnYourRobot)
- このチュートリアルでは、ロボットで使用可能な複数のRTAB-Map設定を紹介しています。

# Example
## SOBIT PRO
- [sobit_pro_rtabmap.launch](../../sobit_mapping/launch/sobit_pro/sobit_pro_rtabmap.launch)
- [rtabmap.launch.xml](../../sobit_mapping/launch/include/rtabmap.launch.xml)
    - SOBIT PROは、Azure_Kinect_ROS_Driverの「[slam_rtabmap.launch](https://github.com/microsoft/Azure_Kinect_ROS_Driver/blob/melodic/launch/slam_rtabmap.launch)」とrtabmap_rosの「[rtabmap.launch](https://github.com/introlab/rtabmap_ros/blob/master/launch/rtabmap.launch)」をモデルに作成

## SOBIT EDU / MINI
- [sobit_turtlebot_rtabmap.launch](../../sobit_mapping/launch/sobit_turtlebot/sobit_turtlebot_rtabmap.launch)
    - SOBIT EDU / MINIは，ROS WikiのSetupOnYourRobot「[2.1 Kinect + Odometry + 2D laser](http://wiki.ros.org/rtabmap_ros/Tutorials/SetupOnYourRobot#Kinect_.2B-_Odometry_.2B-_2D_laser)」をモデルに作成


---

- [Topに戻る](https://github.com/TeamSOBITS/sobit_navigation_stack)