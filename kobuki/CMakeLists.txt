cmake_minimum_required(VERSION 3.5)
project(ir_kobuki)

find_package(ament_cmake REQUIRED)

install(DIRECTORY  launch config
        DESTINATION share/${PROJECT_NAME})

ament_package()
