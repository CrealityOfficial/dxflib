__files_group(${CMAKE_CURRENT_SOURCE_DIR} SRCS)
set(LIBS dxflib)

__add_real_target(writedimension exe SOURCE ${SRCS} LIB ${LIBS} DEF ${DEFS})