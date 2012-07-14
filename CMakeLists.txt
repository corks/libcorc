cmake_minimum_required(VERSION 2.8.7)
project(libcorc C)

set(CMAKE_BUILD_TYPE Debug)

option(USE_DS  "EnableDS"  ON)
option(USE_NET "EnableNET" ON)
option(USE_OPT "EnableOPT" ON)

add_subdirectory(src)
