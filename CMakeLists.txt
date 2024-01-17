cmake_minimum_required(VERSION 3.20)
project(Checking_list_function)


add_subdirectory(../Catch2 Catch2_build)
add_executable(Checking_list_function Checking_list_function.cpp)
target_link_libraries(Checking_list_function PRIVATE Catch2::Catch2)
