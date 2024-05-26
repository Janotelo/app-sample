cmake_minimum_required(VERSION 3.10)

project(app_sample)

add_executable(${PROJECT_NAME} main.c)

INSTALL (TARGETS ${PROJECT_NAME} DESTINATION /usr/bin)