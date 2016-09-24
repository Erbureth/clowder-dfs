cmake_minimum_required(VERSION 2.6)
project(clowder-dfs)

add_executable(clowder-dfs main.cpp)

install(TARGETS clowder-dfs RUNTIME DESTINATION bin)
