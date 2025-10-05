# Login en Laravel — Laboratorio #2

Este proyecto implementa un sistema básico de **autenticación (login y registro)** en Laravel, utilizando Laravel Breeze.  
Incluye configuración de entorno, migraciones, respaldo de base de datos y documentación completa del proceso.

---

## 1. Objetivo
Implementar un sistema de autenticación en Laravel y documentar el proceso de instalación, configuración y funcionamiento del login.

---

## 2. Requisitos previos
- PHP 8.0 o superior  
- Composer  
- Node.js y npm  
- MySQL / MariaDB  
- Servidor local (XAMPP o Laragon)  
- Editor de código (Visual Studio Code)

---

## 3. Instalación y configuración
```bash
git clone <repo>
cd proyecto
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm run dev
php artisan serve

4. Estructura MVC en Laravel

Modelos (app/Models): representan las tablas de la base de datos.
Controladores (app/Http/Controllers): manejan la lógica entre vistas y modelos.
Vistas (resources/views): muestran la interfaz al usuario.
Rutas (routes/web.php): definen las URL del sistema y qué controladores las manejan.

5. Base de datos
Configuración del archivo .env:
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=root
DB_PASSWORD=

6.Dificultades y soluciones
Dificultad 1: Problemas con la versión de PHP y la compatibilidad con
Laravel.
Solución: Se actualizó la versión de PHP a la recomendada en la documentación
oficial de Laravel, logrando que el proyecto se instalara correctamente

Dificultad 2: Laravel no reconocía la versión de PHP instalada, a pesar de
que esta se encontraba en el sistema.
Solución: Se verificaron las variables de entorno en el sistema operativo y se
configuró correctamente la ruta de PHP en el PATH, asegurando que el servidor
de Laravel pudiera detectar la versión instalada.

7.  resultado final 
[![Captura-de-pantalla-2025-10-05-015117.png](https://i.postimg.cc/6TJf4Xhj/Captura-de-pantalla-2025-10-05-015117.png)](https://postimg.cc/Pvyw009Y)


**Proyecto:** LoginLaravel  
**Alumno:** Marcial Belton
**Correo:** Beltongarrido16@hotmail.com
**Curso:** Ingenieria Web
**Instructor:** Ing. Irina Fong  
**Fecha de ejecución del laboratorio:** 



