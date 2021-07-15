cmake_minimum_required(VERSION 3.5)

project(rapidxml)

add_library(${PROJECT_NAME}
        STATIC
        rapidxml.cpp
        )

target_include_directories(${PROJECT_NAME}
        PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}/include
        )