﻿add_executable(${CMAKE_PROJECT_NAME} main.cpp)
target_link_libraries(${CMAKE_PROJECT_NAME}
        Qt${QT_VERSION_MAJOR}::Core
        UILibrary
        )
install(TARGETS ${CMAKE_PROJECT_NAME} DESTINATION bin)
