# Proyecto_La_Cuponera_SV

## 👥 Integrantes del equipo

-Christian Carlos Alfaro Arabia AA202767  
-Luis Gustavo Hernández Rivas HR233189  
-Raquel Sugey Saenz Guevara SG142513  
-Laura Sofia Pineda Castro PC230111  
-Gerardo Alejandro Zelaya Arce ZA242754  

---

## 🚀 Instrucciones de instalación

Clonar el repositorio  
https://github.com/Gerard-01/Proyecto_La_Cuponera_SV.git

Instalar Docker

---

## ⚙️ Para Backend (abrir terminal en carpeta `La_Cuponera`)

### Paso 1: Ejecutar el siguiente comando

docker run --name CuponeraDB -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=0101 -e POSTGRES_DB=CuponeraDB -p 5432:5432 -d postgres

### Paso 2: Ejecutar comando para instalar dependencias

composer install

### Paso 3: Ejecutar migraciones y seeders

php artisan migrate  
php artisan migrate:fresh --seed

### Paso 4: Ejecutar comando para iniciar el servidor

php artisan serve

---

## 💻 Para Frontend (abrir terminal en carpeta `Cuponera_Front`)

### Paso 1: Ejecutar

docker compose up --build

### Paso 2: Abrir localhost

http://localhost:5173

---

## 🔑 Cuentas de prueba

Iniciar sesión con las siguientes credenciales para probar todas las funcionalidades de la aplicación:

### 👑 Administrador
**Correo:** admin@cuponera.sv  
**Contraseña:** admin123

### 👤 Usuario
**Correo:** cliente1@gmail.com  
**Contraseña:** user123

### 🏢 Empresa
**Correo:** maria@cafedelicia.sv  
**Contraseña:** business123

---
