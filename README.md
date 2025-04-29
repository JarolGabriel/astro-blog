# 🚀 Jarol Blog

[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-here/deploy-status)](https://jarol-blog.netlify.app)

Bienvenido a **Jarol Blog**, un proyecto de práctica creado con **Astro** +
**TypeScript**, donde los posts y los autores son gestionados mediante archivos
`.md` usando **Content Collections**.  
Actualmente está desplegado en: 👉
[jarol-blog.netlify.app](https://jarol-blog.netlify.app)

---

## 🌟 Funcionalidades principales

- 📚 **Listado de posts** escritos en Markdown.
- ✍️ **Páginas individuales** para cada autor mostrando:
  - Nombre
  - Avatar
  - Redes sociales (GitHub, LinkedIn, Twitter)
  - Biografía
  - Posts publicados
- ⚡ **Despliegue** en Netlify.
- 🛠️ **TypeScript** para mayor seguridad en el código.

---

## 🧱 Tecnologías utilizadas

- [Astro](https://astro.build/)
- [TypeScript](https://www.typescriptlang.org/)
- [Markdown](https://www.markdownguide.org/)
- [TailwindCSS](https://tailwindcss.com/) _(opcional si después lo agregas)_
- [Netlify](https://www.netlify.com/) para despliegue

---

## 🏗️ Estructura del proyecto

src/ ├── components/

# Componentes

Astro como AuthorCard, PostCard, etc. ├── layouts/

# Layout principal del sitio

├── pages/

# Páginas principales del blog

├── content/ │ ├── author/

# Archivos .md para cada autor

│ └── posts/ # Archivos .md para cada post └── styles/

# Archivos CSS globales

---

## 🚀 Instalación local

Si quieres correrlo en tu máquina:

```bash
# 1. Clona este repositorio
git clone https://github.com/tu-usuario/tu-repo.git

# 2. Entra al proyecto
cd tu-repo

# 3. Instala las dependencias
npm install

# 4. Corre el servidor de desarrollo
npm run dev
```

Luego entra a http://localhost:4321 para verlo en acción. 🎉

## Nuevas Características 🚀

Este proyecto ha sido actualizado recientemente con las siguientes mejoras:

- **RSS Feed**  
  Se ha implementado un RSS Feed utilizando las herramientas de Astro. Gracias a
  esto, los usuarios pueden suscribirse al blog y recibir notificaciones
  automáticas cuando se publique nuevo contenido.

- **Markdown-it**  
  Se integró la librería
  [`markdown-it`](https://github.com/markdown-it/markdown-it) para procesar
  contenido en formato Markdown de manera más flexible y personalizada,
  mejorando la forma en que se renderizan los artículos y publicaciones.

- **Sanitize-html**  
  Se añadió el paquete
  [`sanitize-html`](https://github.com/apostrophecms/sanitize-html) para limpiar
  y asegurar el contenido dinámico, protegiendo el sitio de posibles
  vulnerabilidades relacionadas con HTML malicioso.

---

> Estas mejoras tienen como objetivo ofrecer una mejor experiencia de lectura,
> mayor seguridad y facilitar la distribución de contenido.

🛤️ Futuras mejoras Conectar el blog a Astro DB para manejar posts y usuarios
dinámicamente.

Agregar un sistema de comentarios.

Mejorar la accesibilidad y el SEO.

Agregar paginación en los posts.

📜 Licencia Este proyecto está bajo la licencia MIT. ¡Eres libre de usarlo,
mejorarlo y compartirlo!

---

Creado con 💙 por Jarol

✅ **Listo para copiar y pegar** directo en tu `README.md`.  
✅ **Markdown estilizado** como lo verías en GitHub (títulos grandes, secciones
separadas, código resaltado, etc.).

---
