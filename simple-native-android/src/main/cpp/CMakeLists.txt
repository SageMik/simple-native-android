cmake_minimum_required(VERSION 3.19)

project(simple_without_sqlite3_android)

include(FetchContent)

FetchContent_Declare(simple_native
    GIT_REPOSITORY https://github.com/SageMik/sqlite3_simple
    GIT_TAG Nv1.0.3
)
FetchContent_MakeAvailable(simple_native)
