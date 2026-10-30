cmake_minimum_required(VERSION 3.8)
project(three_dof_arm)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY config launch rviz
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
