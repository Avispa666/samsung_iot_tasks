cmake_minimum_required(VERSION 3.6)
project(samsung_iot_tasks)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES bfs.cpp dfs.cpp)
add_executable(samsung_iot_tasks ${SOURCE_FILES})