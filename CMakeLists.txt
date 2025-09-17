cmake_minimum_required(VERSION 4.0)
project(hwclient)

set(CMAKE_CXX_STANDARD 17)

add_executable(hwclient main.cpp)

target_link_libraries(hwclient zmq)
