cmake_minimum_required (VERSION 2.6)

set(CMAKE_CONFIGURATION_TYPES "Debug;Release") 
project (RaytracingInOneWeekend)

add_executable(RaytracingInOneWeekend main.cc camera.h hitable.h hitable_list.h ray.h material.h sphere.h vec3.h)
