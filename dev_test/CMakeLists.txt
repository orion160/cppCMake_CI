# CMakeList.txt : CMake project for Opengl_project, include source and define
# project specific logic here.
#
cmake_minimum_required(VERSION 3.16)

# Set c++ standard and ensure compiler compability
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add source to this project's executable.
add_executable(main main.cpp)
