add_library(common INTERFACE)
# target_compile_definitions(tutorials INTERFACE "-DTUTORIAL_SHARED_PATH=\"${TUTORIAL_SHARED_PATH}\"")
target_include_directories(common INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
