<div align="center">
  <h1>📚 Biblio-TK</h1>
  <p><strong>Sistema Integral de Gestión Bibliotecaria Moderna</strong></p>

  <p>
    <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
    <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
    <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
  </p>
</div>

---

## 📖 Sobre el Proyecto

Bienvenido a la organización oficial de **Biblio-TK**. Desarrollamos una plataforma completa y escalable diseñada para modernizar y automatizar la administración de bibliotecas educativas y públicas. 

Nuestro sistema permite gestionar de forma eficiente el catálogo de libros, controlar el flujo de préstamos y devoluciones en tiempo real, administrar membresías de usuarios y generar reportes estadísticos para la toma de decisiones.

### ✨ Características Principales
* **Catálogo Digital Avanzado:** Búsqueda rápida por título, autor, ISBN, categoría y disponibilidad.
* **Gestión de Préstamos y Reservas:** Control automatizado de fechas de entrega, renovaciones y cálculo de multas por retraso.
* **Panel Administrativo:** Gestión de inventario, alta/baja de ejemplares y control de usuarios y roles (Administradores, Bibliotecarios, Lectores).
* **Arquitectura Desacoplada y Contenerizada:** Despliegue rápido, seguro y reproducible mediante contenedores.

---

## 🗂️ Ecosistema de Repositorios

Nuestra arquitectura está dividida en **4 repositorios principales** para mantener una clara separación de responsabilidades:

| Repositorio | Tecnologías | Descripción |
| :--- | :--- | :--- |
| 🛠️ [**`backend`**](https://github.com/Biblio-TK/bibliotk-backend) | **NestJS**, TypeScript, REST API / OpenAPI | API central encargada de la lógica de negocio, autenticación/autorización, validaciones y comunicación con la base de datos. |
| 💻 [**`frontend`**](https://github.com/Biblio-TK/bibliotk-frontend) | **Angular**, TypeScript, RxJS | Aplicación web SPA (Single Page Application) que provee la interfaz de usuario tanto para el panel administrativo como para el catálogo público. |
| 🐳 [**`infra`**](https://github.com/Biblio-TK/bibliotk-infra) | **Docker**, **PostgreSQL**, **Nginx** | Configuración de infraestructura, archivos `docker-compose`, inicialización y persistencia de base de datos, y configuración de Nginx como *reverse proxy*. |
| 📄 [**`docs`**](https://github.com/Biblio-TK/bibliotk-docs) | **Markdown**, Diagramas, OpenAPI | Documentación técnica del proyecto: arquitectura de software, modelo entidad-relación (MER), guías de estilo, estándares de Git y manuales de usuario. |


---

## 🚀 Inicio Rápido (Entorno de Desarrollo)

Para levantar el ecosistema completo en un entorno local, dirígete al repositorio **`infra`** y sigue las instrucciones detalladas allí. A grandes rasgos, el flujo consiste en:

1. Clonar los repositorios necesarios o el orquestador en `infra`.
2. Configurar las variables de entorno basándote en los archivos `.env.example`.
3. Levantar los contenedores con Docker Compose:
   ```bash
   docker compose up -d --build
   ```

---

## 👥 Nuestro Equipo

Este proyecto es desarrollado y mantenido con dedicación por:

| Integrante | Rol Principal | GitHub |
| :--- | :--- | :--- |
| **Jose Enrique Guereca Muñoz** | Backend & Arquitectura | [@EGuereca](https://github.com/EGuereca) |
| **Jesus Manuel De la Rosa Guillen** | Frontend & UI/UX | [@LGSUSDLR](https://github.com/LGSUSDLR) |
| **Iker Jesus Flores Luna** | DevOps, Infraestructura & DB | [@IKER1208](https://github.com/IKER1208) |
| **Jesus Emilio Olvera Cortinas** | Backend & Documentación | [@KoeEmilio](https://github.com/KoeEmilio) |
| **David Jonatan Castañeda Valenzuela** | Frontend & QA Testing | [@Deivid777](https://github.com/Deivid777) |

---

## 🛠️ Estándares y Flujo de Trabajo

* **Control de Versiones:** Utilizamos *Git Flow* / *Trunk-Based Development* con ramas protegidas (`main` y `develop`).
* **Commits:** Seguimos la especificación de [Conventional Commits](https://www.conventionalcommits.org/es/) para mantener un historial limpio y semántico.
* **Revisiones de Código:** Todo cambio requiere un *Pull Request* (PR) aprobado y superar los *checks* de integración continua antes de fusionarse.

---
<div align="center">
  <sub>Desarrollado con ❤️ por el equipo de <strong>Biblio-TK</strong> © 2026</sub>
</div>