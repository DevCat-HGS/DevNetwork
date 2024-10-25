# 🌐 DevNetwork -- Mi Aplicación para Desarrolladores de Software

Bienvenido a **Mi Aplicación**, una plataforma diseñada para conectar desarrolladores, gestionar proyectos y fomentar la colaboración en la comunidad de software. 💻🤝

## 🚀 Descripción del Proyecto

Esta aplicación web permite a los usuarios:
- Buscar proyectos lanzados por grupos de trabajo.
- Comentar y puntuar proyectos.
- Crear y gestionar grupos de desarrollo.
- Subir y compartir sus proyectos con la comunidad.

## 🛠️ Tecnologías Utilizadas

- **Frontend:** HTML, CSS, JavaScript (React, Vue o Angular)
- **Backend:** Supabase (base de datos y autenticación)
- **Estilos:** SCSS
- **Gráficos:** SVG personalizados

## 👤 Creador

Este proyecto fue creado por **DevCat**. 🐱‍💻

## 📁 Estructura de Archivos

### Raíz del Proyecto
- **DevNetwork/**

### Carpeta Public
- **public/**
  - `index.html`              # Archivo principal HTML
  - `favicon.ico`             # Icono de la aplicación

### Carpeta Source
- **src/**
  - **assets/**
    - **images/**             # Imágenes utilizadas en la app
    - **svgs/**               # Archivos SVG personalizados
  - **components/**
    - `Header.js`            # Componente de cabecera
    - `Footer.js`            # Componente de pie de página
    - `UserProfile.js`       # Componente de perfil de usuario
    - `ProjectCard.js`       # Componente de tarjeta de proyecto
    - `GroupCard.js`         # Componente de tarjeta de grupo
    - `Chat.js`              # Componente de chat grupal
  - **pages/**
    - `Home.js`              # Página de inicio
    - `Login.js`             # Página de inicio de sesión
    - `Register.js`          # Página de registro
    - `CreateGroup.js`       # Página para crear un grupo
    - `Group.js`             # Página del grupo
    - `Project.js`           # Página del proyecto
  - **styles/**
    - `App.scss`             # Estilos generales
    - `Header.scss`          # Estilos de la cabecera
    - `Footer.scss`          # Estilos del pie de página
    - `UserProfile.scss`     # Estilos del perfil de usuario
    - `ProjectCard.scss`     # Estilos de la tarjeta de proyecto
    - `GroupCard.scss`       # Estilos de la tarjeta de grupo
  - **utils/**
    - `api.js`               # Funciones para llamadas a la API
    - `auth.js`              # Funciones de autenticación
    - `validations.js`       # Validaciones de formularios
  - `App.js`                  # Componente principal de la aplicación
  - `index.js`                # Punto de entrada de la aplicación
  - `routes.js`               # Definición de las rutas de navegación

### Carpeta de Pruebas
- **tests/**
  - `UserProfile.test.js`     # Pruebas del componente de perfil de usuario
  - `ProjectCard.test.js`     # Pruebas del componente de tarjeta de proyecto
  - `GroupCard.test.js`       # Pruebas del componente de tarjeta de grupo

### Archivos Raíz
- `.gitignore`                # Archivos y carpetas a ignorar por Git
- `package.json`              # Información del proyecto y dependencias
- `README.md`                 # Documentación básica del proyecto

## 📌 ¿Cómo Contribuir?

Si deseas contribuir al proyecto, no dudes en abrir un **issue** o enviar un **pull request**. ¡Todas las aportaciones son bienvenidas! 🙌

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

¡Gracias por visitar el repositorio de **DevNetwork**! 😊
