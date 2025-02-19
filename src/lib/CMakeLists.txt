# Create a library called "http_rest_sensor_api_zynq"
add_library(http_rest_sensor_api_zynq_lib http_rest_sensor_api_zynq.cpp)

# Specify include directories for the library
target_include_directories(http_rest_sensor_api_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
