cmake_minimum_required(VERSION 3.15)

set(CMAKE_C_STANDARD 17)
set(CMAKE_C_STANDARD_REQUIRED True)

add_compile_options(-W -Wall -Wextra -Wpedantic -Werror)

project(LearningCMake LANGUAGES C)

add_executable(toto src/a.c)
