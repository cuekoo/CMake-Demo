cmake_minimum_required(VERSION 3.0)

project(hw)

add_executable(main main.c)
target_link_libraries(main hw)
