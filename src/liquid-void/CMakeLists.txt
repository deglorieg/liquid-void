# List sources 

# Create a library called "liquid-void" with its own source 
add_library (liquid-void lvEngine.cpp lvEngine.h)

# Look for include files for library
# when other libraries or executables link to liquid-void
target_include_directories (liquid-void PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
