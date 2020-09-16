cmake_minimum_required(VERSION 3.10)

project(IconFontCpp)

add_library(${PROJECT_NAME} INTERFACE)
add_library(IconFontCpp::IconFontCpp ALIAS IconFontCpp)
target_include_directories(${PROJECT_NAME} INTERFACE ${PROJECT_SOURCE_DIR})