set(LIB_NAME similar-numbers)
set(HEADERS PUBLIC ../include)

file(GLOB_RECURSE SOURCES *.c*)

add_library(${LIB_NAME} STATIC ${SOURCES})
target_include_directories(${LIB_NAME} ${HEADERS})
