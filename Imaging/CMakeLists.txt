# Define target name
set (TARGET_NAME Imaging)

# Define source files
file (GLOB CPP_FILES *.cpp *.c)
file (GLOB H_FILES *.h)
set (SOURCE_FILES ${CPP_FILES} ${H_FILES})
set (INCLUDE_DIRS_ONLY ../Noise ../RGBA)

# Setup target
setup_static_library ()