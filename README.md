# CCNY ORB SLAM3 

You can run with your RGBD/RGBD-IMU camera in real time

## Usage
### Note: you should complie the Thirdparty at first, then follow the below steps:
* `mkdir build`
* `cd build`
* `cmake ..`
* `make -j`
* `roslauch realsense2_camera rs_camera.launch`
* `roslauch CCNY_Roboticlab_ORBSLAM3.launch`
