cmake_minimum_required(VERSION 3.10)
project(include C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(include
        console.h
        const.h
        global.h
        keyboard.h
        keymap.h
        proc.h
        protect.h
        proto.h
        string.h
        tty.h
        type.h)
