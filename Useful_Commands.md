# Useful Commands to Run ROS2 on Spot
- ***Command to run a docker container:*** `docker run -it --privileged --device=/dev/ttyUSB0 -e DISPLAY=$DISPLAY -e XAUTHORITY=/home/spot/.Xauthority -e QT_X11_NO_MITSHM=1 -v /tmp/.X11-unix:/tmp/.X11-unix -v /home/spot/.Xauthority:/home/spot/.Xauthority:ro --net=host --name humble_slam humble_spot-ros2:latest bash`
- ***Command to run Spot Driver***: `ros2 launch spot_driver spot_driver.launch.py config_file:=/home/spot/spot_auth.yaml launch_image_publishers:=False`
- ***Establish where the LiDAR is sitting***: `ros2 run tf2_ros static_transform_publisher --x 0 --y 0 --z 0.1 --yaw 0 --pitch 0 --roll 0 --frame-id front_rail --child-frame-id laser`

## Attributes needed to be able to run slam_toolbox 
- `ros2 run tf2_ros static_transform_publisher --x 0 --y 0 --z 0.1 --yaw 0 --pitch 0 --roll 0 --frame-id front_rail --child-frame-id laser`
- `ros2 run tf2_ros static_transform_publisher --x 0 --y 0 --z 0 --roll 0 --pitch 0 --yaw 0 --frame-id body --child-frame-id base_footprint`

## Attributes needed to run nav2_bringup
- `ros2 run tf2_ros static_transform_publisher --x 0 --y 0 --z 0 --roll 0 --pitch 0 --yaw 0 --frame-id body --child-frame-id base_link`
- 