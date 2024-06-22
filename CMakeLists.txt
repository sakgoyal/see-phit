cmake_minimum_required(VERSION 3.6)
project(seephit)

set (CMAKE_CXX_STANDARD 20)
set (CMAKE_CXX_STANDARD_REQUIRED ON)
set (CMAKE_CXX_EXTENSIONS OFF)

add_library(seephit INTERFACE)
target_include_directories(seephit INTERFACE .)
