cmake_minimum_required(VERSION 3.10)

project(tutorial)

set(SOURCES main.cpp common.h)

add_executable(tutorial ${SOURCES})

install(TARGETS tutorial)
