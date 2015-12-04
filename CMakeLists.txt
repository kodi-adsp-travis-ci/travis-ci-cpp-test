cmake_minimum_required(VERSION 3.0)
project(Travis-CI-Test)

add_executable(travis-ci-test src/main.cpp)

enable_testing()
add_test(Travis-CI-Test travis-ci-test)