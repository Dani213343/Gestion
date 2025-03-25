# 📦 Backend - Sistema de Inventarios y Distribución de Cosméticos

## 📌 Descripción
Este proyecto consiste en el desarrollo del backend para un sistema de administración de inventarios y distribución de cosméticos. Permite gestionar productos, controlar el stock en tiempo real y registrar diferentes tipos de movimientos, como ventas, donaciones y roturas.

## 🚀 Características
- **Gestión de Inventarios:** CRUD de productos, control de stock en tiempo real.
- **Control de Movimientos:** Registro de ventas, roturas y donaciones.
- **Módulo de Pedidos y Distribución:** Gestión de pedidos de compra y venta.
- **Reportes y Análisis:** Generación de informes personalizados.
- **Gestión de Usuarios:** Control de roles y permisos.

## 🛠 Tecnologías Utilizadas
- **Node.js** - Entorno de ejecución para JavaScript.
- **Express.js** - Framework para la construcción de APIs.
- **MongoDB** (o MySQL) - Base de datos para almacenamiento de productos e inventario.
- **Mongoose** (para MongoDB) o Sequelize (para MySQL) - ORM para interactuar con la base de datos.
- **Postman / Thunder Client** - Para pruebas de API.

## 📂 Estructura del Proyecto
```
backend-inventario/
│── src/
│   ├── controllers/    # Lógica de negocio
│   ├── models/         # Modelos de datos
│   ├── routes/         # Rutas de la API
│   ├── config/         # Configuración del servidor y base de datos
│   ├── server.js       # Punto de entrada del servidor
│── package.json        # Dependencias del proyecto
│── .env                # Variables de entorno
```

## 🚀 Instalación y Configuración
### 1️⃣ Clonar el Repositorio
```bash
git clone https://github.com/tuusuario/backend-inventario.git
cd backend-inventario
```

### 2️⃣ Instalar Dependencias
```bash
npm install
```

### 3️⃣ Configurar Variables de Entorno
Crea un archivo `.env` en la raíz del proyecto y define las variables necesarias, como el puerto del servidor y la conexión a la base de datos:
```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/inventario
```

### 4️⃣ Ejecutar el Servidor
```bash
npm start
```
_El servidor se ejecutará en_ `http://localhost:5000`

## 📡 Endpoints de la API

### 🔹 **Productos**
- `GET /api/productos` → Obtener todos los productos.
- `POST /api/productos` → Agregar un nuevo producto.
- `PUT /api/productos/:id` → Actualizar un producto.
- `DELETE /api/productos/:id` → Eliminar un producto.

### 🔹 **Movimientos de Inventario**
- `POST /api/movimientos` → Registrar un movimiento (venta, rotura, donación).
- `GET /api/movimientos` → Obtener historial de movimientos.

### 🔹 **Usuarios y Roles**
- `POST /api/usuarios` → Crear un usuario.
- `POST /api/login` → Iniciar sesión.

## 🔍 Pruebas con Postman o Thunder Client
1. Inicia el servidor con `npm start`.
2. Abre Postman o Thunder Client.
3. Prueba los endpoints anteriores.

## 📜 Licencia
Este proyecto se distribuye bajo la licencia MIT.

---
👨‍💻 **Desarrollado por:** [Tu Nombre]


