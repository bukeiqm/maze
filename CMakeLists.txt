cmake_minimum_required(VERSION 3.10)
project(Maze)

set(CMAKE_CXX_STANDARD 17)

find_package(SFML COMPONENTS graphics window system REQUIRED)

add_executable(maze src/main.cpp)

target_link_libraries(maze sfml-graphics sfml-window sfml-system)
