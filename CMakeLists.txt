# Example https://github.com/facebook/BGP/blob/main/CMakeLists.txt

# 1. Set the minimum required CMake version
cmake_minimum_required(VERSION 3.15)

# 2. Define your project name, version, and language
project(packsim 
        VERSION 1.0.0 
        LANGUAGES CXX)

# 3. Enforce modern C++ standards
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

# 5. Define your executable target
add_executable(packsim 
    main.cpp
)

