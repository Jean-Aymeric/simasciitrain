cmake_minimum_required(VERSION 3.30)
project(simasciitrain)

set(CMAKE_CXX_STANDARD 20)

add_executable(simasciitrain main.cpp
        TrainElement.h
        TypeWagon.h
        TypeWagon.cpp
        AbstractWagon.cpp
        AbstractWagon.h
        FreightWagon.h
        FreightWagon.cpp
        PassengerWagon.h
        PassengerWagon.cpp
        UtilityWagon.h
        UtilityWagon.cpp
        TypeLocomotive.h
        TypeLocomotive.cpp
        ElectricLocomotive.h
        ElectricLocomotive.h
        AbstractLocomotive.h
        AbstractLocomotive.cpp
        GasolineLocomotive.h
        GasolineLocomotive.cpp
        Wagons.h
        Wagons.cpp
        ITrain.h
        Train.h
        Train.cpp
)
