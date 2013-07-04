project(Optional CXX)

add_library(${PROJECT_NAME} ${LIB_TYPE}
	optional.hpp
	test_optional.cpp
	test_type_traits.cpp
	)
	
install_target(${PROJECT_NAME})