# To compile this with cmake 
# 1. Go to path=<dump>
# 2. Create a build directory outside the source directory
# 3. Following are the steps to compile
#	a. mkdir build
#	b. cd build
#	c. cmake ../dump_util
#	d. make
# The final executable is in the build directory <elevator>
project(dump)

add_executable(dump dump.cxx)
