cmake_minimum_required(VERSION 3.5)
project(recersi)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    jsoncpp/json-forwards.h
    jsoncpp/json.h
    jsoncpp.cpp
        main.cpp)

add_executable(recersi ${SOURCE_FILES})