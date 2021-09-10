# kuka_kr6

$ sudo apt install ros-melodic-industrial-core

Using Moveit! together with Gazebo Simulator
Bring the robot model into gazebo and load the ros_control controllers: 
$ roslaunch kuka_kr6_gazebo kr6r900sixx_gazebo.launch

Launch moveit! and ensure that it is configured to run alongside Gazebo: 
$ roslaunch kuka_kr6r900sixx_moveit_config moveit_planning_execution_rsi.launch sim:=true
