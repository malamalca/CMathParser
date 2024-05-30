cmake_minimum_required(VERSION 3.14..3.29)

project (
  CMathParser
  VERSION 0.1.0
)

set(LIB_FILES
  CMathParser.cpp
  CMathParser.h
)

set(LIB CMathParser)
add_library(${LIB} STATIC ${LIB_FILES})

add_subdirectory(@TestApp)
