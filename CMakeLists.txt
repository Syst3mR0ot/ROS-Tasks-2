cmake_minimum_required(VERSION 3.1)

project(first_project)

set(CMAKE_CXX_STANDARD 17)

# here all .hpp or .h files
include_directories(include/)

#excute file
add_executable(first_project src/)

set_target_properties(first_project PROPERTIES LINKER_LANGUAGE CXX)

target_link_libraries(first_project)