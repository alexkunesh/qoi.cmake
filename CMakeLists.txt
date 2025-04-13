cmake_minimum_required(VERSION 3.20)
project(qoi)

add_library(qoi "dummy.c")
target_include_directories(qoi PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/qoi")
