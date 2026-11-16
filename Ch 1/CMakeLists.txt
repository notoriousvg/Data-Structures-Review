cmake_minimum_required(VERSION 3.10 FATAL_ERROR)

add_definitions(-std=c++17)

set(CXX_FLAGS "-Wall")
set(CMAKE_CXX_FLAGS, "${CXX_FLAGS}")

set(CMAKE_BUILD_TYPE Debug)

project(CH_1)

include_directories("includes")
# add include files here 
set(SOURCES main.cpp )
add_executable(CH_1 ${SOURCES})