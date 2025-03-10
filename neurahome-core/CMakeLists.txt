cmake_minimum_required(VERSION 3.30)
project(neurahome-core LANGUAGES C)

set(CMAKE_C_STANDARD 23)
set(CMAKE_C_STANDARD_REQUIRED True)

add_executable(neurahome-core src/main.c)

target_compile_features(neurahome-core PRIVATE c_std_23)
