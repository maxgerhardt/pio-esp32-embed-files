# Warning! This code was automatically generated for projects
# without default 'CMakeLists.txt' file.

set(COMPONENT_SRCS "main.c")
set(COMPONENT_ADD_INCLUDEDIRS ".")
register_component()

#set(app_sources
#	"main.c"
#)
#idf_component_register(SRCS ${app_sources})

target_add_binary_data(${COMPONENT_TARGET} "cert.pem" TEXT)
