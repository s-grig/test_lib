cmake_minimum_required(VERSION 3.0)
project(test)

find_package(Tesseract CONFIG REQUIRED)

add_executable(main main.cpp)

target_link_libraries(main PRIVATE libtesseract)
