cmake_minimum_required(VERSION 3.23)
project(Server)

set(CMAKE_CXX_STANDARD 14)

include_directories(scr)

add_subdirectory(scr)
add_subdirectory(tst)
add_subdirectory(lib/googletest)
