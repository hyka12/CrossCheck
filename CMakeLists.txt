cmake_minimum_required(VERSION 3.13)
project(CrossCheck)

file(GLOB CPP_FILES "${CMAKE_CURRENT_SOURCE_DIR}/src/*.cpp")

set(CMAKE_CXX_STANDARD 20)
add_executable(CrossCheck ${CPP_FILES})
