cmake_minimum_required(VERSION 3.19)
set(TARGET_NAME example)
set(CMAKE_INCLUDE_CURRENT_DIR ON)

project(${TARGET_NAME})

add_executable(${TARGET_NAME}
    main.cpp
)
