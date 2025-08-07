# API REST - Gestión de Ventas y Stock para Comercio de Electrónica

Proyecto integrador final del curso **"Desarrollo de APIs en Java con Spring Boot"** de TodoCode Academy.

##  Objetivo

Desarrollar una API REST robusta que permita gestionar el stock y registrar ventas de un comercio de artículos electrónicos.  
La aplicación debe servir de backend para futuras aplicaciones web y mobile, facilitando el trabajo de la dueña del comercio y sus empleados.

##  Tecnologías Utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Hibernate
- Lombok
- Maven
- Postman (para pruebas)
- JUnit & Mockito (tests)


##  Funcionalidades

-  ABM de productos (crear, listar, modificar, eliminar)
-  Registro de ventas con múltiples productos
-  Cálculo automático del total de cada venta
-  Gestión de clientes
-  Descuento automático por cliente recurrente
-  Validaciones de stock insuficiente
-  Reportes de ventas y stock
-  Manejo de errores y excepciones centralizado

## 📱 Escenario de uso

La API fue diseñada para ser consumida por:

- Una aplicación web (frontend a cargo de otro desarrollador)
- Una futura aplicación mobile

##  Estructura del Proyecto

src
├── controller
├── dto
├── entity
├── repository
├── service


##  Endpoints Principales
  Productos
- `POST /productos` → Crear producto  
- `GET /productos` → Listar productos
- `GET /productos/id` → Listar producto por su código
- `GET /productos/productos-venta/cod_venta` → Listar productos pertenecientes a una venta
- `GET /productos/menos-cinco-unidades` → Listar productos con stock de menos de 5 unidades
- `PUT /productos/id` → Modificar datos del producto
- `PATCH /productos/stock` → Agrega stock a un producto
  Cleintes

  Ventas
- `POST /ventas` → Registrar una venta  
- `GET /ventas` → Listar ventas  
- `GET /ventas`
- `GET /ventas`
- `GET /ventas`
- `GET /ventas`
- `GET /ventas`

## Estado actual del proyecto
-  En desarrollo / ✅ Completado (elegí uno y comentá brevemente si hay cosas por mejorar)

## Autor

Martín Díaz
Estudiante de Análisis de Sistemas | Backend Developer

LinkedIn | GitHub 

