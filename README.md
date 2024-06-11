# Uptask - Gestor de Proyectos

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,tailwind,express,nodejs,ts,mongodb&perline=13" />
  </a>
</p>


## Descripción

Aplicación Web para facilitar la gestión de proyectos individuales y en equipo. Cuenta con una agradable interfaz de usuario y funciones avanzadas para gestionar y clasificar tareas, anexar anotaciones y gestionar proyectos individual y colaborativamente. Fue creado con React, React Router, Tailwind CSS, Express.js y MongoDB

## Requisitos

- Node.js
- npm
- MongoDB (opcional)

## Configuración

### Instalación del frontend

Clonar el repositorio e instalar las dependencias con npm.

```bash
git clone git@github.com/hiahir357/uptask-frontend
cd uptask-frontend
npm install
```

En la raíz del proyecto, crea un archivo de variables de entorno `.env.local`. Deberá tener la url del backend una vez hayas instalado éste.

```
VITE_API_URL=backend-url
```

### Instalación del backend

Clonar el repositorio e instalar las dependencias con npm.

```bash
git clone git@github.com/hiahir357/uptask-backend
cd uptask-backend
npm install
```

En la raíz del proyecto, crea un archivo de variables de entorno `.env` con lo siguiente:

```
DATABASE_URL=url-base-de-datos-mongodb
FRONTEND_URL=frontend-url

SMTP_HOST=host
SMTP_PORT=puerto
SMTP_USER=usuario
SMTP_PASS=contraseña

JWT_SECRET=key
```
`DATABASE_URL` contiene la url de la base de datos MongoDB.

`FRONTEND_URL` contiene la url desde donde se sirve el cliente de uptask.

`SMTP_HOST`, `SMTP_PORT`, `SMTP_USER`, `SMTP_PASS` son variables que contienen información para permitir el envío de correos electrónicos, funcionalidad que se utiliza para verificar usuarios y recuperar contraseñas.

En `JWT_SECRET`, se le deberá asignar una cadena de caracteres aleatorios para garantizar la seguridad del sistema de login.

## Enlaces del Proyecto

- Frontend: [Uptask Frontend](https://github.com/hiahir357/uptask-frontend)
- Backend: [Uptask Frontend](https://github.com/hiahir357/uptask-backend)
