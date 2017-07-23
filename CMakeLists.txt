project(egl)
cmake_minimum_required(VERSION 3.5)

include_directories(SYSTEM
    include
)

aux_source_directory(./ SRC)
add_library(${PROJECT_NAME} SHARED ${SRC})
