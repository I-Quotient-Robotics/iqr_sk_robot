cmake_minimum_required(VERSION 3.0.2)
project(iqr_sk_description)

## Compile as C++11, supported in ROS Kinetic and newer
# add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
  bunker_description
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES iqr_sk_description
#  CATKIN_DEPENDS bunker_description
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)