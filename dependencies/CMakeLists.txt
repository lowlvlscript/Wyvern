#set(LLVM_INCLUDE_EXAMPLES OFF)
#set(LLVM_BUILD_EXAMPLES OFF)
#set(LLVM_INCLUDE_BENCHMARKS OFF)
#set(LLVM_BUILD_BENCHMARKS OFF)
#set(LLVM_INCLUDE_TESTS OFF)
#set(LLVM_BUILD_TESTS OFF)
#set(LLVM_ENABLE_LIBXML2 OFF)
#set(LLVM_ENABLE_ZLIB OFF)
#set(LLVM_OPTIMIZED_TABLEGEN OFF)
#set(LLVM_TEMPORARILY_ALLOW_OLD_TOOLCHAIN ON)
#set(PACKAGE_VERSION "10.0.0")
#set(LLVM_BUILD_LLVM_C_DYLIB OFF)
#add_subdirectory(llvmp/llvm)

#get_filename_component(ABSOLUTE_LLVM_DIR
#        "dependencies/llvmp/llvm/cmake/modules" ABSOLUTE
#        BASE_DIR "${CMAKE_SOURCE_DIR}"
#        )

#set(LLVM_DIR "${ABSOLUTE_LLVM_DIR}")

#set(SIMDJSON_JUST_LIBRARY ON)
#set(SIMDJSON_ENABLE_THREADS ON)
#add_subdirectory(simdjson)
