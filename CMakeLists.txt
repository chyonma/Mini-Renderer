cmake_minimum_required(VERSION 3.10)
project(TinyRenderer)

set(CMAKE_CXX_STANDARD 17)

# Add your source files here

add_executable(tinyrenderer main.cpp tgaimage.cpp tgaimage.h)