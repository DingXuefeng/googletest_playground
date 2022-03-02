cmake_minimum_required(VERSION 3.21)
project(googltest_playground)

set(CMAKE_CXX_STANDARD 14)

add_subdirectory(src)

add_executable(googltest_playground
        main.cc)

target_link_libraries(googletest_playground A)

enable_testing()
add_subdirectory(test)