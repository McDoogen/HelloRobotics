add_executable(helloRos
helloRos.cpp
)

target_link_libraries(helloRos pico_stdlib)

pico_add_extra_outputs(helloRos)