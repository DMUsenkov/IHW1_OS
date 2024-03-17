cmake_minimum_required(VERSION 3.25)
project(OS_IHW1_master C)

set(CMAKE_C_STANDARD 11)

add_executable(OS_IHW1_master
        grade4/main.c
        grade5/grade5.c
        grade6/grade6.c
        grade7/grade7.c
        grade8/Handler.c
        grade8/TextWorker.c)
