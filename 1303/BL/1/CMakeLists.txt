cmake_minimum_required(VERSION 2.8.3)
project(lab1)

find_package(catkin REQUIRED COMPONENTS roscpp)

catkin_package()

include_directories(include ${catkin_INCLUDE_DIRS})
add_executable(lab1 src/lab1.cpp)
target_link_libraries(lab1 ${catkin_LIBRARIES})
