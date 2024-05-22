# CMakeList.txt : CMake project for dummy-raytracer, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (dummy-raytracer "dummy-raytracer.cpp" "dummy-raytracer.h" "vec3.h" "color.h" "ray.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET dummy-raytracer PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
