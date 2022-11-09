cmake_minimum_required(VERSION 3.16)
project(stb)

add_library(stb SHARED src/stb_image.cpp)
target_include_directories(stb PUBLIC include)
