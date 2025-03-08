cmake_minimum_required(VERSION 3.26)
project(fuse-filesystem)

set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_EXPORT_COMPILE_COMMANDS True)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQURIED True)

set(FUSE_SOURCES 
    src/main.cpp
)

add_executable(${PROJECT_NAME}
    ${FUSE_SOURCES}
)

