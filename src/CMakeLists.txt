add_executable(SDL3_Init)
target_sources(SDL3_Init PRIVATE main.cpp)
target_link_libraries(SDL3_Init PRIVATE vendor)