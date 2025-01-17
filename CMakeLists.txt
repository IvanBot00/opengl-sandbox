CMAKE_MINIMUM_REQUIRED(VERSION 3.11)

project(opengl-sandbox)

include(FetchContent)

FetchContent_Declare( 
    GLFW
    GIT_REPOSITORY git@github.com:glfw/glfw.git
)

FetchContent_MakeAvailable(glfw)

add_subdirectory(src)
