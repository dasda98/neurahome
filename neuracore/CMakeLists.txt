cmake_minimum_required(VERSION 3.30)
project(neuracore LANGUAGES C)

set(CMAKE_C_STANDARD 23)
set(CMAKE_C_STANDARD_REQUIRED True)

add_executable(neuracore src/main.c)

target_compile_features(neuracore PRIVATE c_std_23)
