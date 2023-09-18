cmake_minimum_required(VERSION 3.25)
project(FooString)

set(CMAKE_CXX_STANDARD 17)

add_executable(FooString main.cpp)

target_include_directories(
FooString
PUBLIC ${PROJECT_SOURCE_DIR}
)
