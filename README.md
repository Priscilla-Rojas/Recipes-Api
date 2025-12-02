# 🍜 Food Recipes – Backend (API)

![Node.js](https://img.shields.io/badge/Node.js-16-green)
![Express](https://img.shields.io/badge/Express-4.17-lightgrey)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14-blue)
![Sequelize](https://img.shields.io/badge/Sequelize-6-blue)
![Testing](https://img.shields.io/badge/Mocha%2FChai%2FSupertest-Testing-red)

API REST del proyecto **Food Recipes**, utilizada por el frontend para explorar, buscar y crear recetas.  
Integra datos locales desde PostgreSQL y datos externos desde Spoonacular.
---
## 🚀 Características principales

- Endpoints REST para recetas (listado, detalle, creación, etc.)
- Integración con **Spoonacular API**
- Base de datos PostgreSQL
- Modelos con **Sequelize**
- Middleware de manejo de errores
- Tests automatizados con Mocha, Chai y Supertest
---
## 📦 Instalación

```bash
git clone https://github.com/Priscilla-Rojas/Recipes-API.git
cd Recipes-API
npm install
```
---
## 🔐 Variables de entorno
Crear archivo `.env` en la raíz del proyecto:
* B_USER=tu_usuario
* DB_PASSWORD=tu_contraseña
* DB_HOST=localhost
* DB_NAME=food
* DB_PORT=5432
* API_KEY1=tu_api_key_spoonacular
---
## ▶️ Ejecutar servidor

```bash
npm start
```
Servidor disponible en:
`http://localhost:3001/`
---
## 📂 Estructura del proyecto
```
api/
├── controllers/     # Lógica de negocio
├── routes/          # Endpoints REST
├── models/          # Modelos Sequelize
├── tests/           # Tests automatizados
└── index.js         # Servidor principal
```
## 🧪 Testing
Este proyecto incluye tests de backend usando:
* Mocha
* Chai
* Supertest-session

Ejecutar los tests:
```Bash
npm test
``` 
Los tests cubren:
* Inicialización de la base de datos
* Datos de ejemplo
* Test de integración del endpoint `GET /recipes` (respuesta 200)
## 🔄 Flujo general

DB ↔ Sequelize ↔ Express API ↔ Frontend

## 👩‍💻 Mi rol y responsabilidades

* Modelado de base de datos relacional
* Implementación de endpoints
* Integración con API externa
* Manejo de errores
* Testing
* Arquitectura interna (routes, controllers, models)

