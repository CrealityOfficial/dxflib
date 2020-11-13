cmake_minimum_required (VERSION 3.1)
list(APPEND CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake/")
include(ConfigureAllModules)    
set(CMAKE_CXX_STANDARD 11)

project(dxflib)

add_subdirectory(src)
add_subdirectory(main)
