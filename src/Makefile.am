ACLOCAL_AMFLAGS = -I m4


# This is our dynamic library target. The 'lib_' prefix is a convention.
lib_LTLIBRARIES = libhello.la

# This is our executable target. The 'bin_' prefix is a convention.
bin_PROGRAMS = hello_world

# Define the source files for our dynamic library
libhello_la_SOURCES = hello_lib.cpp hello_lib.h

# Define the source files and dependencies for our executable
hello_world_SOURCES = main.cpp
hello_world_LDADD = libhello.la

# Include the header file when compiling the main program
hello_world_CXXFLAGS = -I.
