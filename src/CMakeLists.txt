add_executable(live live.c)

add_executable(car car.c)

add_executable(planet planet.c)
target_link_libraries(planet m)
