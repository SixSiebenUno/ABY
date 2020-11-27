
add_executable(secureml
    secureml.cpp
)
target_compile_options(secureml PRIVATE "-Wall" "-Wextra")
target_link_libraries(secureml ABY::aby ENCRYPTO_utils::encrypto_utils)
