cmake_minimum_required(VERSION 3.29)
project(Tienda_2_0)

set(CMAKE_CXX_STANDARD 20)

add_executable(Tienda_2_0 main.cpp
        Persona.cpp
        Persona.h
        Cliente.cpp
        Cliente.h
        Empleado.cpp
        Empleado.h
        Producto.cpp
        Producto.h
        Venta.cpp
        Venta.h
        Turno.cpp
        Turno.h
        Factura.cpp
        Factura.h
        Reporte.cpp
        Reporte.h
        Tienda.cpp
        Tienda.h)
