## SETUP
Make Colcon Workspace

    source /opt/ros/foxy/setup.bash
    mkdir ar_ws
    cd ar_ws
    colcon build --symlink-install

Run node 

    source install/setup.bash
    ros2 run joint_state_publisher_gui joint_state_publisher_gui
    ros2 launch krtmi rsp.launch.py

Run rviz2

    rviz2