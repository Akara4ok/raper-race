cmake_minimum_required(VERSION 3.22)

project(RaperRace)

find_package(SFML 2.5 COMPONENTS graphics REQUIRED)

add_executable(raperrace src/main.cpp)

target_link_libraries(raperrace sfml-graphics)