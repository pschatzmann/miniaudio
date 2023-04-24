cmake_minimum_required (VERSION 3.8)

project ("miniaudio" LANGUAGES CXX)

add_library(project INTERFACE)
target_include_directories(project INTERFACE .)
