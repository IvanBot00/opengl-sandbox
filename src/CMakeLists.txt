
add_executable(main main.cpp ${PROJECT_SOURCE_DIR}/dep/glad/src/glad.c)

target_include_directories(
    main
    PRIVATE
    ${PROJECT_SOURCE_DIR}/dep/glad/include
)

target_link_libraries(
    main
    glfw
)