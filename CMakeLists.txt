cmake_minimum_required(VERSION 3.30)

set(PROJECT_NAME "cmdfx-showcase-0.1.0")
project(${PROJECT_NAME})

find_package(cmdfx REQUIRED)
add_executable(${PROJECT_NAME} main.c)
target_link_libraries(${PROJECT_NAME} PRIVATE cmdfx::cmdfx)