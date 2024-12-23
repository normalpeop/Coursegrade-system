cmake_minimum_required(VERSION 3.27)

project(testfile LANGUAGES CXX)

add_executable(testfile main.cpp)

target_compile_features(testfile PRIVATE cxx_std_20)
