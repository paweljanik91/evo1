cmake_minimum_required(VERSION 2.6)
project(ev01)

add_executable(ev01 main.cpp)

install(TARGETS ev01 RUNTIME DESTINATION bin)
