# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES )
set(COMPONENT_PRIV_REQUIRES )


idf_component_register(
	SRCS
	"main.c"
	"metaballs.c"
	"plasma.c"
	"rotozoom.c"
	INCLUDE_DIRS
	"."

)
set(COMPONENT_ADD_INCLUDEDIRS "")

#register_component()
