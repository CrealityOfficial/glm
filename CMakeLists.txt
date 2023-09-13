__add_include_interface(glm INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}
							INTERFACE_DEF GLM_FORCE_LEFT_HANDED
							)

if(CC_INSTALL_GLM)
	__install_directory_specif(${CMAKE_CURRENT_SOURCE_DIR}/ glm)
endif()