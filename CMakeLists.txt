cmake_minimum_required(VERSION 3.26)
project(Homework5)

set(CMAKE_CXX_STANDARD 14)


include_directories(.)

add_executable(Homework5
        JonesFilters.c
        BmpProcessor.h
        PixelProcessor.h
        BmpProcessor.c)
target_link_libraries(Homework5 m)