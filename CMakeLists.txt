cmake_minimum_required(VERSION 3.8)
project(Lab4)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Makefile
        myint.c
        myspin.c
        mysplit.c
        mystop.c
        README
        sdriver.pl
        trace01.txt
        trace02.txt
        trace03.txt
        trace04.txt
        trace05.txt
        trace06.txt
        trace07.txt
        trace08.txt
        trace09.txt
        trace10.txt
        trace11.txt
        trace12.txt
        trace13.txt
        trace14.txt
        trace15.txt
        trace16.txt
        tsh.c
        tshref
        tshref.out)

add_executable(Lab4 ${SOURCE_FILES})