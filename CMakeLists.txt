cmake_minimum_required(VERSION 3.0.0)
project(example-wsl VERSION 0.1.0)

set(C_STANDART C99)
add_executable(example-wsl main.c)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
