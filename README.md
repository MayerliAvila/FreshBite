# 🥗 FreshBite

FreshBite es una aplicación web desarrollada para ayudar a los usuarios a administrar la despensa de alimentos de su hogar de forma inteligente. Permite registrar productos, controlar fechas de vencimiento, visualizar el inventario y recibir recomendaciones de recetas utilizando Inteligencia Artificial para reducir el desperdicio de alimentos.

---

# 📖 Descripción

El objetivo de FreshBite es facilitar el control del inventario de alimentos mediante una interfaz intuitiva y herramientas inteligentes.

Entre sus principales funcionalidades se encuentran:

- 📦 Registro de productos.
- 📅 Control de fechas de vencimiento.
- 📊 Visualización del inventario.
- ➖ Retiro de productos consumidos o vencidos
- 🤖 Recomendación de recetas mediante IA.
- 📉 Estadísticas del estado de los alimentos.

---

# 🏗 Arquitectura del proyecto

El proyecto está dividido en dos aplicaciones independientes:

```
FreshBite
│
├── Backend
│   ├── app
│   ├── models
│   ├── routes
│   ├── schemas
│   ├── database
│   ├── requirements.txt
│   └── .gitignore
│
├── Frontend
│   ├── src
│   ├── public
│   ├── package.json
│   ├── angular.json
│   └── .gitignore
│
└── README.md
```

---

# 🖥 Frontend

Desarrollado con:

- Angular
- TypeScript
- HTML5
- CSS3
- Bootstrap

Funciones principales

- Inicio de sesión
- Registro de usuarios
- Dashboard
- Inventario
- Agregar productos
- Retirar productos
- Perfil de usuario
- Gráficas del estado del inventario
- Consumo de API REST

---

# ⚙ Backend

Desarrollado con:

- Python
- FastAPI
- SQLAlchemy
- Pydantic
- JWT Authentication

Funciones principales

- API REST
- Autenticación de usuarios
- CRUD de productos
- CRUD de usuarios
- Gestión del inventario
- Control de fechas de vencimiento
- Integración con IA
- Integración con Open Food Facts

---

# 🗄 Base de datos

Motor utilizado

- PostgreSQL

Proveedor recomendado

- Supabase

---

# 🤖 Inteligencia Artificial

FreshBite integra un modelo de lenguaje para generar recetas utilizando los productos disponibles y aquellos próximos a vencer.

Además, una vez confirmada la receta, los ingredientes utilizados son descontados automáticamente del inventario.

---

# 🌐 API utilizada

- Grop

---

# 🚀 Tecnologías

## Frontend

- Angular
- TypeScript
- HTML5
- CSS3
- Bootstrap

## Backend

- Python
- FastAPI
- SQLAlchemy
- Pydantic
- JWT

## Base de datos

- PostgreSQL

## Hosting

Frontend

- Vercel

Backend

- Render

Base de datos

- Supabase

---

# 📥 Instalación

## 1. Clonar el repositorio

```bash
git clone https://github.com/usuario/FreshBite.git
```

---

## 2. Backend

Entrar a la carpeta

```bash
cd Backend
```

Crear entorno virtual

```bash
python -m venv venv
```

Activar entorno virtual

Windows

```bash
venv\Scripts\activate
```

Linux / Mac

```bash
source venv/bin/activate
```

Instalar dependencias

```bash
pip install -r requirements.txt
```

Ejecutar servidor

```bash
uvicorn app.main:app --reload
```

---

## 3. Frontend

Entrar a la carpeta

```bash
cd Frontend
```

Instalar dependencias

```bash
npm install
```

Ejecutar proyecto

```bash
ng serve
```

La aplicación estará disponible en

```
http://localhost:4200
```

---

# 📡 Endpoints principales

## Usuarios

- POST /usuarios
- POST /login
- GET /usuarios

## Productos

- GET /productos
- POST /productos
- PUT /productos/{id}
- DELETE /productos/{id}

  
# 👀 Vista previa

Puedes acceder a la aplicación desde el siguiente enlace:

### 🌐 Aplicación Web
**Frontend:** https://freshbite-frontend-kscf.vercel.app/

### 🔗 API REST
**Backend:** https://freshbite-backend.onrender.com/

### 📖 Documentación de la API (Swagger)
https://freshbite-backend.onrender.com/docs

---

## Capturas de pantalla

### 🏠 Página de inicio

<img width="1872" height="925" alt="image" src="https://github.com/user-attachments/assets/a4a6a4f8-de95-4de6-b222-2de127148e83" />

Usuario: prueba@gmail.com
Contraseña: 12345
### 📊 Dashboard

<img width="1918" height="928" alt="image" src="https://github.com/user-attachments/assets/3e24434e-6650-41e2-b46c-59bd5a7e02c6" />


# 👨‍💻 Autores

Proyecto desarrollado por

**Mayerli Quintero**

Politécnico Grancolombiano

Ingeniería de Software

---

# 📄 Licencia

Este proyecto fue desarrollado con fines académicos.
