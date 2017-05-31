cmake_minimum_required(VERSION 3.7)
project(jisp)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES
        main.c
        mpc/mpc.c)
add_executable(jisp ${SOURCE_FILES})

target_link_libraries(jisp -ledit)
