cmake_minimum_required(VERSION 3.0)
project(TravisCITest)

add_executable(TravisCITest main.cpp)

install(TARGETS TravisCITest DESTINATION bin)
