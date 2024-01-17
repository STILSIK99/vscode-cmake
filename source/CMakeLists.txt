cmake_minimum_required(VERSION 2.8...3.13)

set(CMAKE_CXX_COMPILER "g++.exe")
set(CMAKE_C_COMPILER "gcc.exe")

project(cmake_vscode_first VERSION 0.1.0 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(cmake_vscode_first main.cpp)

