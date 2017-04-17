cmake_minimum_required (VERSION 2.6)
project(chatt)

set(CMAKE_CXX_FLAGS "-std=c++14 -Wall -Wextra -pedantic")

link_libraries(-pthread)

add_subdirectory(src)
