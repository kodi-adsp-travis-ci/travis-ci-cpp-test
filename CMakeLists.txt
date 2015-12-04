cmake_minimum_required(VERSION 2.7)
project(TravisCITest)

add_executable(TravisCITest main.cpp)

install(TARGETS TravisCITest DESTINATION bin)
