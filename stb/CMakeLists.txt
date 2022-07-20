cmake_minimum_required(VERSION 3.0)
project(stb)

add_library(stb src/stb_image.h src/stb.cpp)
target_include_directories(stb PUBLIC src/)
