add_library(stb STATIC stb_image.c stb_truetype.c)
target_include_directories(stb PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/stb)
target_compile_options(stb PUBLIC ${GRANITE_CXX_FLAGS})

