cmake_minimum_required(VERSION 2.8.3)
project(crom_sim_bringup)


find_package(catkin REQUIRED COMPONENTS
  crom_gazebo
  crom_moveit_config
)


catkin_package(
)


