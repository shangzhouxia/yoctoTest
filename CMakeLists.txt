project(YoctoTest C)
cmake_minimum_required(VERSION 2.6.3)

add_executable (YoctoTest main.c)

install(TARGETS YoctoTest DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)
