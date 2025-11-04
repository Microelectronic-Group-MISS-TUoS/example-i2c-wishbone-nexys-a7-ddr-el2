cmake_minimum_required(VERSION 3.17)

project(I2C_C-Lang C ASM)

set(SOURCE ${CMAKE_CURRENT_SOURCE_DIR}/src/I2C_C-Lang.c)
set(TARGET_NAME I2C.elf)

add_executable(${TARGET_NAME} ${SOURCE})

include(${CMAKE_CURRENT_SOURCE_DIR}/../common/Common.cmake)
