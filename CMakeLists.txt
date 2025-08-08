cmake_minimum_required(VERSION 3.5)

project(gasm80 C)

set(CMAKE_C_STANDARD 11)

add_executable(${PROJECT_NAME} gasm80.c)

# Install the executable
install(TARGETS ${PROJECT_NAME}
    RUNTIME DESTINATION bin
)