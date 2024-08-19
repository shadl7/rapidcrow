cmake_minimum_required(VERSION 3.15)
project(rapidcrow CXX)

find_package(Boost REQUIRED)

add_executable(rapidcrow src/main.cpp)
target_link_libraries(rapidcrow boost::boost)
