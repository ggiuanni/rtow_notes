cmake_minimum_required(VERSION 3.0.0)
project(rtow)

add_executable(${PROJECT_NAME}
    src/main.cc)

target_include_directories(${PROJECT_NAME} PUBLIC include)