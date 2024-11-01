cmake_minimum_required(VERSION 3.25)

project(myProject)

include(CTest)
enable_testing()

include_directories(${CMAKE_SOURCE_DIR}/include)

link_directories(${CMAKE_SOURCE_DIR}/lib)

add_executable(myProject main.cpp)

set_property(TARGET myProject PROPERTY CXX_STANDARD 17)