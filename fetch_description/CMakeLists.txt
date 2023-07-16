cmake_minimum_required(VERSION 3.16.0)
project(fetch_description)

find_package(ament_cmake REQUIRED)

install(DIRECTORY meshes robots
  DESTINATION share/${PROJECT_NAME}/
)

ament_package()

