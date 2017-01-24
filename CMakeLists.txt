cmake_minimum_required(VERSION 3.6)
project(myword2vec)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c main.c)
add_executable(word2vec ${SOURCE_FILES})