cmake_minimum_required(VERSION 3.21)
project(Lab4 CUDA)

set(CMAKE_CUDA_STANDARD 11)

add_executable(Lab4 main.cu)

set_target_properties(Lab4 PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
