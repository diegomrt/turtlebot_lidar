# turtlebot_lidar #

ROS Kinetic package for adding a 2D Lidar into the Gazebo simulation of a Turtlebot 2 robot. 

The simulated robot includes a Kobuki base, an Orbec Astra RGBD camera and a Hokuyo or RPLidar A2M8 Lidar

| Turtlebot 2 with Hokuyo Lidar   | Turtlebot 2 with RPLidar A2M8    |
| ------------------------------- | -------------------------------- |
| ![](./img/turtlebot_hokuyo.jpg) | ![](./img/turtlebot_rplidar.jpg)  |

## Turtlebot 2 with Hokuyo Lidar ## 

After installing, to launch the version with Hokuyo lidar, run:

```sh
roslaunch turtlebot_lidar turtlebot_hokuyo.launch  
```

## Turtlebot 2 with RPLidar A2M8 ## 

After installing, to launch the version with RPLidar A2, run:

```sh
roslaunch turtlebot_lidar turtlebot_rplidar.launch  
```



