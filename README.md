# 🧾 Sistema de Inventario y Gestión de Productos

Este proyecto es una aplicación web fullstack que permite registrar, editar, listar y eliminar productos en un inventario. Está construido con **Node.js**, **Express**, **MongoDB** en el backend y **React.js** en el frontend.

## 🚀 Funcionalidades

- Crear productos con nombre, SKU, precio de entrada y salida, y cantidad.
- Editar información de productos existentes.
- Eliminar productos del inventario.
- Listar todos los productos registrados.
- Interfaz amigable con Tailwind CSS.

## 🛠️ Tecnologías utilizadas

### Frontend
- React.js
- Axios
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB (vía Mongoose)

### Ejecutar el Servidor
```bash
node server.js
```
_El servidor se ejecutará en_ `http://localhost:5000`

### Ejecutar el Inventario
```bash
npm start
```
_El inventario se ejecutará en_ `http://localhost:3000`


## 📡 API Endpoints

GET /api/productos – Lista todos los productos.

POST /api/productos – Crea un nuevo producto.

PUT /api/productos/:id – Actualiza un producto existente.

DELETE /api/productos/:id – Elimina un producto.

## 📌 Notas
Asegúrate de que MongoDB esté corriendo en tu máquina.

Puedes modificar los estilos usando Tailwind CSS en el frontend.

El backend valida que todos los campos requeridos estén presentes.

🧑‍💻 Autor Danii

