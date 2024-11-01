cmake_minimum_required(VERSION 3.25)

project(myProject)

include(CTest)
enable_testing()

add_executable(${PROJECT_NAME} WIN32 main.cpp)

set_property(TARGET myProject PROPERTY CXX_STANDARD 17)