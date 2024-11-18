# Sistema de Reservas y Catálogo de Zapatos TSP 👞

Este proyecto es un Sistema de Reservas y Catálogo de Zapatos desarrollado utilizando una arquitectura MEAN Stack (MongoDB, Express, Angular, Node.js). Forma parte de un ejercicio didáctico para implementar el modelo TSP (Team Software Process) y desarrollar un sistema robusto, escalable y eficiente.

## 🚀 Descripción

El sistema permite a los usuarios:

- Registrarse e iniciar sesión. 👤
- Buscar zapatos por características básicas y avanzadas. 🔍
- Visualizar productos con detalles como precios, disponibilidad y descripciones. 🛍️
- Realizar reservas y gestionar su carrito de compras. 🛒

## 📂 Estructura del Proyecto

```plaintext
├── backend/
│   ├── app.js               # Punto de entrada del servidor
│   ├── notificaciones.js    # Lógica de notificaciones
│   ├── reservas.js          # Rutas para manejo de reservas
│   ├── package.json         # Configuración y dependencias del backend
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   │   ├── components/ # Componentes Angular
│   │   │   ├── services/   # Servicios de Angular
│   │   │   └── models/     # Modelos de datos
│   ├── index.html          # Punto de entrada del frontend
│   ├── styles.css          # Estilos globales
│   └── main.ts             # Archivo principal de Angular
└── README.md               # Este archivo 📘
```

🛠️ Tecnologías

### Frontend:
- Angular (v15.0.0): Framework para el desarrollo del frontend.
- HTML5, CSS3, y TypeScript.

### Backend:
- Express.js: Framework para la creación de la API REST.
- Node.js: Entorno de ejecución para el backend.
- MongoDB: Base de datos NoSQL para almacenamiento de datos.

### Dependencias:
- CORS: Manejo de políticas de origen cruzado.
- Swagger-jsdoc y Swagger-UI-Express: Documentación de la API.
- Nodemon: Recarga automática del servidor en desarrollo.

🚀 Configuración y Ejecución

## 1️⃣ Clonar el Repositorio
```bash
git clone https://github.com/tu-usuario/sistema-reservas-catalogo-zapatos.git
cd sistema-reservas-catalogo-zapatos
```

## 2️⃣ Configuración del Backend

### Configurar variables de entorno:
- Crear un archivo .env con el siguiente contenido:

```bash
MONGO_URI=mongodb://localhost:27017/zapatos_tsp
PORT=3000
```


### Ejecutar el servidor:
```bash
Copiar código
npm run dev
```


## 3️⃣ Configuración del Frontend

Instalar dependencias:
```bash
Copiar código
cd frontend
npm install
```

### Ejecutar el servidor de desarrollo:
```bash
Copiar código
ng serve
```

### Acceder a la aplicación:
- Abrir en el navegador: http://localhost:4200


## 📑 Documentación de la API

La API está documentada utilizando Swagger. Una vez ejecutado el servidor backend, la documentación estará disponible en:

```bash
http://localhost:3000/api-docs
```

## Endpoints principales:
Autenticación: /api/auth
Zapatos: /api/zapatos
Reservas: /api/reservas
Notificaciones: /api/notificaciones


## 🌟 Características Destacadas

Modularidad: Cada funcionalidad se encuentra bien separada en el backend y frontend.
Validaciones: Validación en tiempo real en formularios utilizando Angular.
Optimización: Consultas optimizadas con MongoDB y Mongoose.
Experiencia de Usuario: Interfaz amigable y responsive.