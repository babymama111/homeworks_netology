# Устанавливаем минимальную версию CMake
cmake_minimum_required(VERSION 3.0)

# Задаем имя проекта
project(MyProject)

# Добавляем исполняемый файл и исходный код для сборки
add_executable(6_3 main.cpp  classes/Figure/Figure.cpp classes/Triangle/Triangle.cpp classes/Quadrangle/Quadrangle.cpp classes/RightTriangle/RightTriangle.cpp classes/IsoscelesTriangle/IsoscelesTriangle.cpp classes/EquilateralTriangle/EquilateralTriangle.cpp classes/EquilateralQuadrangle/EquilateralQuadrangle.cpp classes/Square/Square.cpp classes/Parallelogram/Parallelogram.cpp  classes/Rhombus/Rhombus.cpp print_info_func/print_info_func.cpp)




