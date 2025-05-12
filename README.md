# 🧩 React Events App

[![React](https://img.shields.io/badge/React-18.2.0-blue.svg?logo=react)](https://reactjs.org/)
[![Context API](https://img.shields.io/badge/Context--API-State%20Management-blueviolet)](https://reactjs.org/docs/context.html)
[![Responsive](https://img.shields.io/badge/Responsive-Design-success.svg)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![MIT License](https://img.shields.io/badge/license-Test--Only-lightgrey.svg)]()

Aplicación frontend construida con **React** que permite a los usuarios **registrarse**, **iniciar sesión** y **gestionar eventos** de forma sencilla. Toda la lógica de autenticación y manejo de datos está estructurada con **Context API** para mantener una arquitectura limpia y escalable.

> ⚠️ **Este proyecto es solo para fines de prueba técnica. No está autorizado para uso en producción.**

---

## 🚀 Características

- 🔐 Registro y Login de usuarios
- 📅 Crear, consultar, filtrar y eliminar eventos
- 🧠 Autenticación global con Context API
- 📁 Arquitectura limpia por capas (`actions`, `components`, `pages`, etc.)
- 📱 UI completamente responsiva
- 🧼 Separación clara de lógica de negocio y presentación

---

## 📁 Estructura del Proyecto
```bash
src/
├── actions/ # Lógica de interacción con la API (crear, eliminar, filtrar eventos, login, etc.)
├── assets/ # Imágenes, fuentes y recursos estáticos
├── components/ # Componentes reutilizables de UI
├── config/ # Configuraciones generales del proyecto (URLs, constantes, etc.)
├── context/ # Contextos globales como AuthContext y EventContext
├── lib/ # Funciones auxiliares y utilidades generales
├── pages/ # Vistas principales como Login, Register, Dashboard, etc.
├── App.jsx # Componente raíz
├── main.jsx # Punto de entrada de la aplicación
├── index.css # Estilos globales
```

---

## 🔧 Tecnologías Usadas

- **React**
- **Context API**
- **Vite / Webpack**
- **Tailwind CSS / CSS Modules**
- **Axios / Fetch API**

---

## 🛠️ Instalación y Ejecución

1. Clona el repositorio:
```bash
   git clone https://github.com/Mendoza727/frontend-gestor-eventos.git
   cd frontend-gestor-eventos
```
Instala dependencias:

```bash
npm install
```
Ejecuta el proyecto:

```bash
npm run dev
```

📝 Licencia
Este proyecto fue desarrollado únicamente para propósitos de evaluación técnica.
🚫 No está permitido su uso en producción ni para fines comerciales.
