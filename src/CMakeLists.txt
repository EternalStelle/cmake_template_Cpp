cmake_minimum_required(VERSION 3.20.0)
# Project Name And Language Settings(C++ or C or C++ and C)
set(projectName MyApp)
project(${projectName} VERSION 0.1 LANGUAGES C CXX)
# Set C++ Version
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED true)
# Exeutable And Source Code
add_executable(${projectName} main.cpp)
