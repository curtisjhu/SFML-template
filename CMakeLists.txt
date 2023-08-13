cmake_minimum_required(VERSION 3.13)
project(traffic-simulations)
set(CMAKE_CXX_STANDARD 17)

set(CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake")

include(cmake/CPM.cmake)
include(cmake/SFML.cmake)

add_subdirectory(src)
