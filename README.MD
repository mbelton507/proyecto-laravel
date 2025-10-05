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
