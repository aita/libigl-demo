add_executable(Events main.cc)
target_link_libraries(Events
    igl
    igl_common
    igl_eigen
    igl_opengl
    igl_opengl_glfw
    common
)
