cmake_minimum_required(VERSION 2.8)
project(PROJECT)

## ECE650 Specific configuration start here
## Project specific configurations go here

# enable c++11 support
set (CMAKE_CXX_FLAGS "-std=c++11 -Wall ${CMAKE_CXX_FLAGS}")

# create the main executable
## add additional .cpp files if needed
#add_executable(graph graph.cpp)
add_executable(main graph.cpp main.cpp)
