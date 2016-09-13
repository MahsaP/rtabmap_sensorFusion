cmake_minimum_required(VERSION 2.8.3)
project(rtabmap_sensorFusion)

find_package(catkin REQUIRED COMPONENTS std_msgs roscpp)

catkin_package()

install(DIRECTORY launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
