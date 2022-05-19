cmake_minimum_required(VERSION 3.21)
project(untitled_folder)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(untitled_folder
        DisciplinaDTO.h
        domain.cpp
        domain.h
        main.cpp
        repocontract.cpp
        repocontract.h
        repofile.cpp
        repofile.h
        repolab.h
        repository.cpp
        repository.h
        service.cpp
        service.h
        ui.cpp
        ui.h
        undo.h
        validator.cpp
        validator.h)
