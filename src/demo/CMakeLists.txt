# List source

# Add executable called "lvDemo" that is built from source
add_executable (lvDemo main.cpp)

# Link the executable to the liquid-void library, and use the public include directories? of the liquid-void library
target_link_libraries (lvDemo LINK_PUBLIC liquid-void)
