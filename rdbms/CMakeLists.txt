ADD_SUBDIRECTORY (util)
ADD_SUBDIRECTORY (types)
ADD_SUBDIRECTORY (app)

add_dependencies(types util)
add_dependencies(rdbms types)