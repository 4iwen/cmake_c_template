set(SOURCE_FILES src/main.c)

add_executable(exec ${SOURCE_FILES})

target_link_libraries(exec PRIVATE lib)