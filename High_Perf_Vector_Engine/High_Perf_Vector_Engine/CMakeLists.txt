# CMakeList.txt : CMake project for High_Perf_Vector_Engine, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (High_Perf_Vector_Engine "High_Perf_Vector_Engine.cpp" "High_Perf_Vector_Engine.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET High_Perf_Vector_Engine PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
