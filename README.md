# Nuxt Minimal Starter

Requisitos: Versión node 20.11.1 
            Python 3.11
            MySQL

# FrontEnd

## 1. Instalar dependencias
```
npm install
```

## 2. Cambiar .env.example por .env y asignar variables

API_URL=https://ip_back:puerto_back

CLOUDINARY_NAME=nombre
CLOUDINARY_UPLOAD_PRESET=preset

## 3. Iniciar app
```
npm run dev
```

## La app se inicia en localhost:3000


# Backend

Backend de una aplicación web que permite comparar precios de productos entre Amazon, MediaMarkt y Fnac mediante scraping automatizado y gestión de usuarios. Desarrollado con **FastAPI**.

## 🚀 Tecnologías

- **Python 3.10+**
- **FastAPI** – API web rápida y moderna
- **MySQL** – Gestión de datos persistentes
- **Crawl4ai** – Scraping web
- **Docker & Docker Compose**
- **Uvicorn** – ASGI server
---


## Configuracion

Para ejecutar el en local, desde src ejecutar uvicorn app:app y configuran .env para fuera del servidor.

Para ejecutar en producción levnatar docker-compose up.


# Base de Datos

## 1. Conectate a tu servidor MySQL.

## 2. Ejecuta los siguientes comandos.
```
 create database BuyPilot;
 create user 'buypilot' identified by 'buypilot23';
 grant all privileges on BuyPilot.* to 'buypilot';
```
## 3. Importa el archivo de .sql
```
 mysql -u root -p BuyPilot < BuyPilot.sql
```



