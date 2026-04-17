# Gestión de Productos - Spring Boot
_Alejandra Farfán Duarte 02230131026_

Aplicación web CRUD para gestión de productos usando Spring Boot, Thymeleaf y patrón MVC.

## Tecnologías
- Java 17
- Spring Boot 4.0.5
- Thymeleaf
- Maven

## Estructura
    src/main/java/com/universidad/productosweb/
- **model/Producto.java** clase con atributos id, nombre, descripcion, precio
- **service/ProductoService.java** lógica CRUD con almacenamiento en memoria
- **controller/ProductoController.java** maneja las rutas con patrón PRG 


    src/main/resources/
- **templates/productos/** maneja las vistas lista.html y formulario.html

## Cómo ejecutar
1. Clonar el repositorio
2. Abrir en IntelliJ IDEA
3. En la terminal ejecutar: **./mvnw spring-boot:run**
4. Acceder a http://localhost:8080/productos para gestionar productos

## Funcionalidades
- Listar productos
- Crear nuevo producto
- Editar producto existente
- Eliminar producto

## capturas
1. listar producto
<img width="700" alt="listar producto" src="https://res.cloudinary.com/dindlmikf/image/upload/v1776396056/Captura_de_pantalla_2026-04-16_220633_znrsal.png">
2. crear producto
<img width="700" alt="Crear producto" src="https://res.cloudinary.com/dindlmikf/image/upload/v1776396056/Captura_de_pantalla_2026-04-16_221601_ybe7jr.png">
3. editar producto
<img width="700" alt="Editar producto" src="https://res.cloudinary.com/dindlmikf/image/upload/v1776396056/Captura_de_pantalla_2026-04-16_221658_q0b9qb.png">
4. eliminar producto
<img width="700" alt="Eliminar producto" src="https://res.cloudinary.com/dindlmikf/image/upload/v1776396056/Captura_de_pantalla_2026-04-16_221717_sui7ry.png">
- producto eliminado
<img width="700" alt="Producto eliminado" src="https://res.cloudinary.com/dindlmikf/image/upload/v1776396056/Captura_de_pantalla_2026-04-16_221732_iyfnrl.png">
