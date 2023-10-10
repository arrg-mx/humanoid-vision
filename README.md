# Perception and Vision for a Humanoid Robot

## Contenido

- [Desarrollo](#desarrollo)
- [Equipo](#equipo)
- [Referencias](#referencias)

## Desarrollo

- [ ] **TODO**

## Equipo

**Integrantes del proyecto:**

| Nombre | Observaciones |
| :----------| :----------- |
| Moreno Cedano Ruth Getzemaní | **responsable** |

## Referencias

### ¿Dónde empezar?

**Comunidad**

1. **Articulated Robotics** [@ArticulatedRobotics YT channel](https://www.youtube.com/@ArticulatedRobotics)
	- **How to use Cameras in ROS (Sim Camera and Pi Camera)** [YT video](https://www.youtube.com/watch?v=A3nw2M47K50)
	- **Can you chase a tennis ball with ROS?** [YT video](https://www.youtube.com/watch?v=gISSSbYUZag)
	- **How to get your robot to see in 3D! (Depth Cameras in ROS)** [YT video](https://www.youtube.com/watch?v=T9xZ22i9-Ys)
		- **Extra** - *realsense-ros* [Github repository](https://github.com/IntelRealSense/realsense-ros)
1. **Muhammad Luqman** [@robotisim YT channel](https://www.youtube.com/@robotisim) **Browse videos and playlists**
	- **ROS camera sensor and understanding its properties** [YT video](https://www.youtube.com/watch?v=mG0FHhhfmw8)
1. **robot design & simulation** [YT channel](https://www.youtube.com/@kabilankb2003)
   	- **How the robot will see in 3D | Depth camera interface with ros | REALSENSE depth camera D435i** [YT video](https://www.youtube.com/watch?v=_uvGxKpRnqo) 
1. [robot mania's YT channel](https://www.youtube.com/@robotmania8896)
	- **Object detection in Gazebo using Yolov5 and ROS2** [YT video](https://www.youtube.com/watch?v=594Gmkdo-_s)
	- [Google Drive](https://drive.google.com/drive/folders/1xC-gFmWQybQGagxtu8WxGqpFS-1Ek-V2) *3 files*
		- **Refs to:** *YOLOv5* [Github repository](https://github.com/ultralytics/yolov5)
1. [Kihwan Ryoo' YT channel](https://www.youtube.com/@kihwanryoo8369)
	1. *ROS Manipulation - Pick and Place demo* [YT video](https://www.youtube.com/watch?v=mtZAKtnwhGA)
	1. *ROS Manipulation - Hit the Ball demo* [YT video](https://www.youtube.com/watch?v=Sb9Ap8X50mk)
	1. **Source Code:** [Github repository](https://github.com/Kihwan-Ryoo/ros_manipulator_hit_the_ball) 


**Legacy/Opensource Projects, Applications and, Libraries**

1. **Georg No's** [Github profile](https://github.com/NovoG93)
   - *vision_msgs_rviz_plugins* [Github repositories](https://github.com/NovoG93/vision_msgs_rviz_plugins). This repo contains a RVIZ2 plugin to display [vision_msgs](https://github.com/ros-perception/vision_msgs/tree/ros2) for **ROS 2 humble**.
1. **ROS Perception** [Github Profile](https://github.com/ros-perception)
   - *vision_opencv* [Github repository](https://github.com/ros-perception/vision_opencv).
	> ros2 vision_opencv contains packages to interface ROS 2 with [OpenCV](http://opencv.org/) which is a library designed for computational efficiency and strong focus for real time computer vision applications. This repository contains:
	>	* `cv_bridge`: Bridge between ROS 2 image messages and OpenCV image representation
	> 	* `image_geometry`: Collection of methods for dealing with image and pixel geometry
	> 	* `opencv_tests`: Integration tests to use the capability of the packages with opencv
	> 	* `vision_opencv`: Meta-package to install both `cv_bridge` and `image_geometry`
   - *ROS Vision Messages* [Github repository](https://github.com/ros-perception/vision_msgs/tree/ros2). This package defines a set of messages to unify computer vision and object detection efforts in ROS.
   - *Browse repositories*
In order to use ROS 2 with OpenCV, please see the details within [cv_bridge](https://github.com/ros-perception/vision_opencv/tree/ros2/cv_bridge) package.
1. **Programming Humanoid Robot In Python** [Github repository](https://github.com/DAInamite/programming-humanoid-robot-in-python)
1. **sciurus17_ros** [GitHub repository](https://github.com/rt-net/sciurus17_ros)
1. **humanoid_base_footprint** [Github repository](https://github.com/ros-sports/humanoid_base_footprint) - ROS2 Humble
1. **iit-coman-ros-pkg** [Github repository](https://github.com/ADVRHumanoids/iit-coman-ros-pkg)
	- *Compliance control for stabilizing the humanoid on the changing slope based on terrain inclination estimation* [Research Gate Article](https://www.researchgate.net/publication/282589044_Compliance_control_for_stabilizing_the_humanoid_on_the_changing_slope_based_on_terrain_inclination_estimation) 
	[Fig. 1](https://www.researchgate.net/figure/The-compliant-humanoid-robot-COMAN_fig1_282589044)
1. ***(Opcional)*** *ROS2_Walking_Pattern_Generator* [Github repository](https://github.com/open-rdc/ROS2_Walking_Pattern_Generator). Walking Pattern Generator using ROS_2 for Humanoid Robots *(Under Construction...)*

**Nota:** Pueden usar la siguiente [plantilla](https://github.com/mrg-mex/mrg-plantilla-repositorio) como referencia de cómo empezar a estructurar su repositorio; así como una plantilla en Markdown para su reporte.
