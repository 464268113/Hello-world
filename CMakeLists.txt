cmake_minimum_required(VERSION 3.24)
project(Hello_world)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Hello_world
        hello_world.cpp)
