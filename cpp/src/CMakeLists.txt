cmake_minimum_required(VERSION 3.16)
project(libnoise)

set(CMAKE_CXX_STANDARD 20)

add_library(libnoise white_noise.cpp white_noise.h)
#add_library(libnoise SHARED white_noise.cpp white_noise.h)