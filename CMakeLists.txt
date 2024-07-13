cmake_minimum_required(VERSION 3.25)
project(hello)

set(CMAKE_CXX_STANDARD 17)

message("CMAKE_SYSTEM_PROCESSOR: ${CMAKE_SYSTEM_PROCESSOR}")

add_executable(hello main.cpp)
