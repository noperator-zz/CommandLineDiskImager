cmake_minimum_required(VERSION 3.0)

project(CommandLineDiskImager)

add_executable(CommandLineDiskImager main.cpp)

set_target_properties(CommandLineDiskImager PROPERTIES
    CMAKE_EXE_LINKER_FLAGS "-static"
    LINK_FLAGS "-static"
)
