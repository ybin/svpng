cmake_minimum_required(VERSION 3.13)
project(svpng C)

set(CMAKE_C_STANDARD 11)

include_directories(${CMAKE_CURRENT_LIST_DIR})

add_executable(svpng example.c)
