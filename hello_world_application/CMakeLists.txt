cmake_minimum_required(VERSION 3.4)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
project(hello_world)
add_executable(hello_world hello_world.cpp)
include_directories(/home/daniel/Merlin13-666/workspace/projects/lab03/formatter_ex_lib)
add_subdirectory(/home/daniel/Merlin13-666/workspace/projects/lab03/formatter_ex_lib formatter_ex)
target_link_libraries(hello_world formatter_ex)
