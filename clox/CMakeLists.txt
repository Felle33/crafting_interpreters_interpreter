cmake_minimum_required(VERSION 3.22.1)
project(clox)

# Include directories
include_directories(${PROJECT_SOURCE_DIR}/include)

set(SOURCES
    src/main.c
    src/chunk.c
    src/memory.c
)

# Add the executable
add_executable(${PROJECT_NAME} ${SOURCES})