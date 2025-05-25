cmake_minimum_required(VERSION 3.0)

project(psx-test LANGUAGES C)

add_executable(psx-test main.c)

install(TARGETS psx-test RUNTIME DESTINATION bin)
