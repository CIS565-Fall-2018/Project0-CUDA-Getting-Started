set(SOURCE_FILES
    "glslUtility.hpp"
    "glslUtility.cpp"
    "kernel.h"
    "kernel.cu"
    "main.hpp"
    "main.cpp"
    )

cuda_add_library(src
    ${SOURCE_FILES}
    OPTIONS -arch=sm_20
    )
