# 🧾 Sistema de Inventario y Gestión de Productos

Aplicación web **fullstack** desarrollada para la gestión de productos de un inventario. El sistema permite registrar, consultar, actualizar y eliminar productos, facilitando la administración de información como nombre, SKU, precios y cantidad disponible.

El proyecto está compuesto por un **backend desarrollado con Node.js y Express.js**, conectado a **MongoDB**, y un **frontend desarrollado con React.js y Tailwind CSS**.

---

## Objetivo

Desarrollar una aplicación web que permita gestionar de manera sencilla la información de los productos de un inventario mediante una interfaz gráfica y una API REST.

---

## Funcionalidades

- Registrar nuevos productos.
- Listar los productos registrados.
- Editar la información de un producto.
- Eliminar productos del inventario.
- Gestionar información como:
  - Nombre del producto.
  - SKU.
  - Precio de entrada.
  - Precio de salida.
  - Cantidad disponible.
- Interfaz web desarrollada con Tailwind CSS.
- Comunicación entre frontend y backend mediante una API REST.

---

## Tecnologías utilizadas

### Frontend

- **React.js** – Desarrollo de la interfaz de usuario.
- **Axios** – Comunicación con la API del backend.
- **Tailwind CSS** – Diseño y estilos de la aplicación.

### Backend

- **Node.js** – Entorno de ejecución.
- **Express.js** – Desarrollo del servidor y API REST.
- **MongoDB** – Base de datos para almacenar la información.
- **Mongoose** – Conexión y gestión de datos en MongoDB.

---

## Estructura del proyecto

```text
Sistema-Inventario/
│
├── backend/
│   ├── ...
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md

```

Instalación y ejecución
1. Clonar el repositorio
git clone <URL-DEL-REPOSITORIO>
cd <NOMBRE-DEL-PROYECTO>
2. Configurar el Backend

Ingresar a la carpeta del backend:

cd backend

Instalar las dependencias:

npm install

Verificar que MongoDB esté disponible y configurado para el proyecto.

Ejecutar el servidor:

node server.js

El backend estará disponible en:

http://localhost:5000

3. Configurar el Frontend

En otra terminal, ingresar a la carpeta del frontend:

cd frontend

Instalar las dependencias:

npm install

Ejecutar la aplicación:

npm start

El frontend estará disponible en:

http://localhost:3000

📡 API REST

La aplicación cuenta con los siguientes endpoints para la gestión de productos:

Método	Endpoint	Descripción
GET	/api/productos	Lista todos los productos.
POST	/api/productos	Registra un nuevo producto.
PUT	/api/productos/:id	Actualiza un producto existente.
DELETE	/api/productos/:id	Elimina un producto.

Consideraciones
Es necesario tener MongoDB disponible para ejecutar correctamente el sistema.
El backend debe estar ejecutándose para que el frontend pueda realizar las operaciones sobre los productos.
Las dependencias de frontend y backend deben instalarse mediante npm install.
Los estilos de la interfaz pueden modificarse utilizando Tailwind CSS.
El backend valida los campos requeridos para el registro de productos.
🎓 Información académica

Proyecto: Sistema de Inventario y Gestión de Productos

Tipo de proyecto: Proyecto académico

Asignatura: Gestión de Proyectos

Institución: Universidad Sergio Arboleda

## 👥 Autores

- Santiago Diaz Rueda
- Alan Osorio
- Ana Maria Amador
- Maria Fernanda Guevara
- Daniela López

