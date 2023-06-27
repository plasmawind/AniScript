cmake_minimum_required(VERSION 3.5)

project(AniScript LANGUAGES C)

add_executable(AniScript main.c)

install(TARGETS AniScript
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
