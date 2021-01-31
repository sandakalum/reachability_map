How to visualize the map

1. Terminal 1 - roscore
2. Terminal 2 - rosrun rviz rviz (this needs to be inside the sourced terminal)
3. Terminal 3 - roslaunch ur5_moveit_config demo.launch
4. Terminal 4 - roslaunch planning_scene planning_scene_ros_api.launch 
5. Select the rviz cofguration file 
6. Go to the map location and open terminal
7. Terminal 5 - rosrun map_creator load_reachability_map ur5_r0.1_reachability_no_obstacles.h5
