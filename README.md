# CRUD de Productos en PHP y MySQL

Este proyecto es una aplicación básica CRUD (Crear, Leer, Actualizar y Eliminar) para gestionar productos, desarrollada con **PHP**, **MySQL**, **HTML** y **XAMPP**.

Permite:
- Listar productos
- Crear nuevos productos
- Editar productos existentes
- Eliminar productos
- Conexión segura a MySQL mediante PDO


## 📌 Tecnologías utilizadas

- PHP 8
- MySQL / MariaDB
- PDO (PHP Data Objects)
- HTML5
- Servidor local XAMPP


## 🗄 Base de datos

La base de datos se llama **inventario** y contiene la tabla **productos**:

CREATE DATABASE IF NOT EXISTS inventario;
USE inventario;

CREATE TABLE productos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100) NOT NULL,
    precio DECIMAL(10,2) NOT NULL,
    creado_en TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

INSERT INTO productos (nombre, precio) VALUES
('Teclado', 120000),
('Mouse', 45000),
('Pantalla 24"', 780000);

# que aprendi hoy?

aprendi a conectar php a github






