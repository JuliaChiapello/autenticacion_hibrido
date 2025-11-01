## 📖 Descripción del proyecto

Este proyecto es un **sistema de autenticación híbrido** para una tienda de comercio electrónico.  
Permite a los usuarios registrarse y autenticarse mediante:

- **Autenticación local:** Email + contraseña  
- **Autenticación social (OAuth 2.0):** Google (con posibilidad de agregar más)  

Incluye **JWT** para proteger rutas privadas y gestionar sesiones de manera segura.  

El frontend está construido con **React.js**, y el backend con **Node.js + Express**.

---

## 🚧 Estado del proyecto

| Funcionalidad                        | Estado       |
|-------------------------------------|------------|
| Registro y login local               | ✅ Completo |
| Hash de contraseñas con bcryptjs     | ✅ Completo |
| Login con Google OAuth 2.0           | ✅ Parcial  |
| Generación y validación de JWT       | ✅ Completo |
| Rutas privadas en frontend           | ✅ Completo |
| Logout y cierre de sesión            | 🚧 En desarrollo |
| Integración con más proveedores OAuth| 🚧 En desarrollo |

---

## 🔧 Funcionalidades

### Autenticación Local
- Registro de usuarios (nombre, email, contraseña)
- Contraseña hasheada con bcryptjs
- Login validando credenciales
- Generación de token JWT para sesiones seguras

### Autenticación Social (OAuth 2.0)
- Login con Google
- Creación automática de usuario si no existe en DB
- Redirección y callback desde el proveedor

### Gestión de Sesión
- Almacenamiento seguro de token en frontend (localStorage / cookies)
- Rutas privadas protegidas con JWT
- Logout funcional (elimina token del cliente)

### Bonus / Próximamente
- Añadir más proveedores sociales (Facebook, Instagram)
- Mejoras en la UI/UX

---

## 🚀 Tecnologías

**Frontend**
- React.js 18+
- React Router
- Axios / Fetch

**Backend**
- Node.js 18+
- Express.js
- Passport.js (local + OAuth 2.0)
- bcryptjs
- jsonwebtoken
- Base de datos relacional (PostgreSQL / MySQL)

**Herramientas**
- Git & GitHub
- Postman / Insomnia
- Visual Studio Code / IntelliJ IDEA

---

