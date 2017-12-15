cmake_minimum_required(VERSION 2.8)

project(documents)
# declaring files in your project

set(SOURCE_FILES main.cpp)
set(HEADERs iModel.hpp)


add_executable(${PROJECT_NAME} ${SOURCE_FILES})
