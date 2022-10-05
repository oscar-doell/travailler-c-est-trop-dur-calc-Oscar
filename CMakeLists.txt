cmake_minimum_required(VERSION 3.23)
project(Code_Beispiel_DOD C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(Code_Beispiel_DOD
        CAlculatOr.c
        CAlculatOr.h
        maiin.c)
