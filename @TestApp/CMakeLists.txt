set(APP TestApp)

set(FILES
  Entry.cpp
)

add_executable(${APP} ${FILES})

target_link_libraries(${APP} PUBLIC
  CMathParser
  m
)
