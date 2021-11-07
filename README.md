# opencv_ros2
OpenCV Applications with ROS2

Environment
* Ubuntu 20.04
* ROS2 Foxy
* OpenCV 4.2.0
* Python 3.8.10
* vision_opencv - https://github.com/ros-perception/vision_opencv/tree/ros2

Applications
* face_detection

Camera
* usb_cam
* ros2 run astra_camera astra_camera_node (Orbbec Astra)
* /image /depth
* ros2 run image_tools showimage --ros-args --remap image:=/image -p reliability:=best_effort

Execution
* ros2 run opencv_ros2 face_detection
