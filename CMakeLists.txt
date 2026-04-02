cmake_minimum_required(VERSION 3.10)
project(FormatterIncProject)

# устанавливаем стандарт C++
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# добавляем поддиректории(в порядке зависимостей)
add_subdirectory(formatter_lib)

add_subdirectory(formatter_ex)

add_subdirectory(hello_world)

add_subdirectory(solver_lib)

add_subdirectory(solver)
