PROJECT (CMakemouse)

SET(SRC_LIST mouse.cpp)

MESSAGE(STATUS "This is BINARY dir " ${HELLO_BINARY_DIR})

MESSAGE(STATUS "This is SOURCE dir "${HELLO_SOURCE_DIR})

ADD_EXECUTABLE(CMouse ${SRC_LIST})
