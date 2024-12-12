cmake_minimum_required(VERSION 3.5)

project(lua-cmake)

add_library(lua STATIC
        onelua.c)
