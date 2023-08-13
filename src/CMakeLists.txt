
add_executable(${PROJECT_NAME} main.cpp)

find_package(SFML REQUIRED)

target_link_libraries(${PROJECT_NAME}
	${SFML_LIBRARIES}
)

target_include_directories(${PROJECT_NAME} PRIVATE 
	${SFML_INCLUDE_DIR}
)
