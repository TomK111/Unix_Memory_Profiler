cmake_minimum_required(VERSION 3.19)
project(Linux_Heap_Memory_Manager C)

set(CMAKE_C_STANDARD 11)

include_directories(.)
include_directories(gluethread)

add_executable(Linux_Heap_Memory_Manager
        gluethread/glthread.c
        gluethread/glthread.h
        css.h
        mm.c
        mm.h
        testapp.c
        uapi_mm.h gluethread/glthread.c gluethread/glthread.h)
