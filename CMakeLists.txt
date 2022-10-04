cmake_minimum_required(VERSION 3.21)
project(shortest_airline_route_master)

set(CMAKE_CXX_STANDARD 14)

include_directories(shortest-airline-route-master)

add_executable(shortest_airline_route_master
        shortest-airline-route-master/createAirlineXML/main.cpp
        shortest-airline-route-master/createAirportXML/main.cpp
        shortest-airline-route-master/createRouteXML/main.cpp
        shortest-airline-route-master/mergeXML/main.cpp
        shortest-airline-route-master/airline.h
        shortest-airline-route-master/airlinepath.cpp
        shortest-airline-route-master/airlinepath.h
        shortest-airline-route-master/main.cpp
        shortest-airline-route-master/route.h
        shortest-airline-route-master/vertex.h)
