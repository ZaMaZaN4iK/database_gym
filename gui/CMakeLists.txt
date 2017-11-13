cmake_minimum_required(VERSION 3.9)
project(gym)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_BUILD_TYPE Debug)

find_package(Qt5Widgets)

set(SOURCE_FILES main.cpp)
add_executable(gym ${SOURCE_FILES})