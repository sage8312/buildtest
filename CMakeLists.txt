cmake_minimum_required (VERSION 3.12)
project(build_test)

set(CMAKE_CXX_STANDARD 17)
set(CXX_STANDARD_REQUIRED YES)

set(SRC main.cpp)

add_executable(build_test ${SRC})
