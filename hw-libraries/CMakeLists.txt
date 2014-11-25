cmake_minimum_required(VERSION 3.0)

project(hw)

add_library(hw SHARED hw.c)
install(TARGETS hw DESTINATION lib)
install(FILES hw.h DESTINATION include/hw)
