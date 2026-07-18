cmake_minimum_required(VERSION 3.16)

project(EmbeddedTelemetrySim)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_executable(
    telemetry
    src/main.cpp
    src/Device.cpp
    src/Telemetry.cpp
    src/Logger.cpp
)