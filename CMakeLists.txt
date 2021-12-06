cmake_minimum_required(VERSION 3.17)
project(TIPL-cpp-examples VERSION 1.0.0 LANGUAGES CXX)

include(CTest)

find_package(TIPL REQUIRED)
add_subdirectory(load_nii)
add_subdirectory(spatial_normalization)
add_subdirectory(linear_reg)
