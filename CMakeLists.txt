cmake_minimum_required (VERSION 2.6)
project (RaytracingInOneWeekend)


#add_library(SupportClasses )
#set_target_properties(SupportClasses PROPERTIES LINKER_LANGUAGE CXX)

add_executable(RaytracingInOneWeekend main.cc camera.h hitable.h hitable_list.h ray.h material.h sphere.h vec3.h)
#target_link_libraries(RaytracingInOneWeekend SupportClasses)