# 2d-semantic-grid-map-with-lidar-and-camera
This project use 2d lidar and depth camera in ROS system to generate 2d semantic map for robot navigation
![ros_tree](https://github.com/user-attachments/assets/7df88196-a4c5-483b-9333-31a8eb6f4fc1)

# Hardware
## 1. Jetson AGX Xavier 64GB 
![image](https://github.com/user-attachments/assets/b0c80d87-4345-4c07-89a7-d7b9ace9bfd1)
## 2. Orbbec Gemini2 depth camera
![image](https://github.com/user-attachments/assets/63abb136-2d9c-4648-906a-e0120b8fa41a)
## 3. Slamtech rplidar A3
![image](https://github.com/user-attachments/assets/349a6abb-21e1-42ef-996e-bfa600c2c8f8)

# pre-requsits
## 1. OpenCV with CUDA
[install OpenCV with CUDA using scripts](https://github.com/AastaNV/JEP/tree/master)
## 2. Orbbec_SDK_ROS2
[install Orbbec_SDK_ROS2](https://github.com/orbbec/OrbbecSDK_ROS2)
## 3. Slamtech lidar SDK ROS2
[install slamtech_lidar_SDK_ROS2](https://github.com/Slamtec/sllidar_ros2)
## 4. Micro-ROS agent
[install micro_ros_agent](https://github.com/micro-ROS/micro_ros_setup)
## 5. install Cartographer
Cartographer is an open-source project for mapping. You can use commandline to install it.
```
sudo apt-get install ros-<ros-distro>-cartographer
sudo apt-get install ros-<ros-distro>-cartographer-ros
```
## 6. install navigation2
Navigation2 is used for point-to-point navigation. You can use commandline to install it.
```
sudo apt install ros-<ros2-distro>-navigation2
sudo apt install ros-<ros2-distro>-nav2-bringup
```

