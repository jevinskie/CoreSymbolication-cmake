cmake_minimum_required(VERSION 3.22)

project(CoreSymbolication C)

add_library(CoreSymbolication INTERFACE)
target_include_directories(CoreSymbolication INTERFACE include)
target_link_libraries(CoreSymbolication INTERFACE ${CMAKE_OSX_SYSROOT}/System/Library/PrivateFrameworks/CoreSymbolication.framework)
