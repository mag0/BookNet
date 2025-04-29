# 📚 Biblioteca Digital Personal

## 🚀 Descripción
Una plataforma para gestionar y registrar libros, donde los usuarios pueden agregar títulos, organizarlos por categorías y llevar el seguimiento de su progreso de lectura.

## 🌟 Características
- Registro e inicio de sesión
- CRUD de libros (agregar, editar, eliminar, consultar)
- Registro del progreso de lectura
- Reseñas y calificaciones
- Filtros y búsqueda avanzada
- Integración con APIs externas (Google Books, Open Library)

## 🛠 Tecnologías usadas
- **Front-end:** React + Tailwind CSS
- **Back-end:** Node.js + Express.js
- **Base de datos:** MongoDB (Mongoose)
- **Autenticación:** JWT
- **Despliegue:** Vercel (front-end), Render (back-end), Atlas (DB)

## 🔧 Instalación y configuración

### 1. Clona el repositorio:
git clone https://github.com/tuusuario/biblioteca-digital.git
cd biblioteca-digital
## 🔧 Instalación y configuración

### 2. Instala dependencias:
cd frontend && npm install
cd ../backend && npm install

### 3. Configura las variables de entorno:
Crea un archivo `.env` en la carpeta `backend` con lo siguiente:
MONGO_URI=<tu_url_de_mongodb>
JWT_SECRET=<tu_secreto_jwt>
PORT=5000
### 4. Inicia el proyecto:
npm run dev

## 📋 Uso
1. Regístrate o inicia sesión con tu cuenta.
2. Agrega libros a tu biblioteca digital.
3. Marca el progreso de lectura y organiza los libros.
4. Filtra y busca por autor, categoría o estado de lectura.
5. Comparte reseñas y calificaciones con la comunidad.

## 👥 Autores
- Martín Andrés Guerreiro(https://github.com/mag0)
