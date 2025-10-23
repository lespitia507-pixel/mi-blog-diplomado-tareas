# Mi Proyecto de Inventario

Backend para un sistema de inventario hecho con Node.js y MongoDB.

## Lo que necesitas tener instalado

- Node.js
- MongoDB

## Cómo instalar

1. Clona el repo
```bash
git clone <url-del-repo>    
cd mi-blog-diplomado-tareas
```

2. Instala las dependencias
```bash
npm install
```

3. Crea un archivo `.env` y agrega:
```
PORT=3000
MONGO_URI=mongodb://localhost:27017/inventario_db
```

## Cómo correrlo
```bash
node app.js
```

Abre tu navegador en `http://localhost:3000`

## Estructura del proyecto
```
mi-blog-diplomado-tareas/
├── models/
│   ├── Usuario.js
│   ├── Producto.js
│   ├── Categoria.js
│   └── Movimiento.js
├── routes/
├── app.js
├── .env
└── README.md
```

## Modelos

**Usuario**: nombre, correo, contraseña, rol

**Producto**: nombre, descripción, precio, cantidad, categoría

**Categoría**: nombre, descripción

**Movimiento**: tipo (entrada/salida), producto, cantidad, usuario, motivo

## Tech Stack

Node.js | Express | MongoDB | Mongoose