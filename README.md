# 📘 Sistema Web de Gestión Personal  
**Proyecto en HTML, CSS y JavaScript**

Este proyecto es una aplicación web básica desarrollada con tecnologías frontend puras. Simula un sistema de gestión personal que incluye inicio de sesión, perfil de usuario, notas personales, galería de imágenes y control de sesiones. Su objetivo principal es reforzar buenas prácticas en el desarrollo frontend como la separación por responsabilidades, uso de `localStorage` y manipulación dinámica del DOM.

---

## 🧠 Funcionalidades Implementadas

- 🔐 **Login**: Inicio de sesión con almacenamiento de sesión mediante `localStorage`.
- 🔒 **Protección de Rutas**: Implementada con `middleware.js`; las páginas requieren autenticación para acceder.
- 👤 **Perfil de Usuario**: Visualización de datos del usuario autenticado.
- 📝 **Notas**: CRUD básico (crear, leer, actualizar, eliminar) para notas personales.
- 🖼️ **Galería de Imágenes**: Muestra imágenes representativas de los integrantes o elementos del sistema.
- 🎨 **Estilos**: Toda la interfaz está diseñada con un solo archivo CSS reutilizable y bien organizado.

---

## 🚀 Cómo Usarlo

1. Clona o descarga el proyecto en tu equipo.
2. Abre el archivo `login.html` en tu navegador.
3. Inicia sesión con las credenciales predefinidas (si están configuradas).
4. Al autenticarse, puedes acceder libremente a las siguientes páginas:
   - `inicio.html`
   - `profile.html`
   - `notes.html`
   - `gallery.html`
5. La sesión se mantiene activa mientras no cierres el navegador o uses la opción de logout (si existe).

---

## 🛠 Tecnologías Utilizadas

- HTML5  
- CSS3  
- JavaScript

---

## 📁 Estructura del Proyecto

```plaintext
/ ── index.html
│   └── login.html
│   └── inicio.html
│   └── profile.html
│   └── notes.html
│   └── gallery.html
│
├── js/
│   └── auth.js
│   └── middleware.js
│   └── notes.js
│   └── profile.js
│
├── css/
│   └── style.css
```

---

## 👥 Autores
Alex – Lógica de autenticación y protección de rutas

Cristian – Desarrollo general y manejo de sesión

Mariana – Diseño de interfaz y estilos CSS

Thomas – Módulo de notas y galería de imágenes

