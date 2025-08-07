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

##  Estado actual

Refactorización en curso:  
- [x] Separación de capas (controller, service, repository)  
- [x] Validaciones y manejo de excepciones  
- [x] DTOs implementados  
- [ ] Controlador de sesiones (pendiente)  
- [ ] Documentación Swagger (pendiente)  

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

(Esto podés completarlo vos o generarlo con Swagger)

- `POST /productos` → Crear producto  
- `GET /productos` → Listar productos  
- `POST /ventas` → Registrar una venta  
- `GET /ventas` → Listar ventas  
- etc.

