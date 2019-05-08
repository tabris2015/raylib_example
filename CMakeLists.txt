cmake_minimum_required(VERSION 2.8)

project(raylib_example)

set(CMAKE_CXX_STANDARD 11)

include_directories(include)

find_package(raylib 2.0 REQUIRED)

add_executable(teclas src/teclas.cpp)

target_link_libraries(teclas raylib m)