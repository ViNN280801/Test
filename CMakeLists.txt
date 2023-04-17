cmake_minimum_required(VERSION 3.26 FATAL_ERROR)

project(rtrim
        LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "-Wall -Wpedantic -Wextra")

add_executable(main trim.cpp main.cpp)
