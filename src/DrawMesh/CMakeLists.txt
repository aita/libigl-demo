add_executable(DrawMesh main.cc)
target_link_libraries(DrawMesh
    igl
    igl_common
    igl_eigen
    igl_opengl
    igl_opengl_glfw
)
