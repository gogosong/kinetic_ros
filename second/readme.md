# USB CAM ROS

Kinetic

ls -ltr /dev/video*

cd catkin_ws/src

git clone https://github.com/bosch-ros-pkg/usb_cam

sudo apt-get install ros-indigo-camera-info-manager

source ~/catkin_ws/devel/setup.bash

rospack find usb_cam

sudo apt-get install ros-kinetic-image-view

roscore

roslaunch usb_cam usb_cam-test.launch

rosrun rqt_graph rqt_graph
