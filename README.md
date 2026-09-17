# ResCanchas Frontend

Frontend web del proyecto ResCanchas, desarrollado con Angular para ofrecer una interfaz moderna y funcional para la gestión de reservas y administración de canchas deportivas.

## Descripción general

Este repositorio contiene la interfaz de usuario del sistema. Su objetivo es permitir a los usuarios:

- iniciar sesión en la plataforma
- registrar encargados
- acceder al panel principal del sistema
- navegar entre módulos de gestión y administración
- consumir la API REST del backend del proyecto

El frontend y el backend forman parte del mismo proyecto, trabajando de forma complementaria para brindar una experiencia completa de reservas deportivas.

## Repositorio relacionado

- Backend: https://github.com/TomasCGH/Backend_ResCanchas

## Stack tecnológico

- Angular 19
- TypeScript
- RxJS
- Angular Router
- HTML5 / CSS3

## Funcionalidades principales

- login de usuario
- registro de encargado
- interfaz de dashboard
- rutas protegidas por guard de autenticación
- consumo de servicios REST para la lógica del negocio

## Requisitos previos

Antes de ejecutar el proyecto asegúrate de tener instalado:

- Node.js 18 o superior
- npm
- Angular CLI (opcional, pero recomendado)

## Instalación

Clona el repositorio e instala las dependencias:

```bash
npm install
```

## Ejecución en desarrollo

```bash
npm start
```

O también:

```bash
ng serve
```

Luego abre tu navegador en:

```text
http://localhost:4200/
```

## Compilación para producción

```bash
ng build
```

Los archivos compilados se generarán en la carpeta `dist/` del proyecto.

## Estructura del proyecto

```text
Frontend_ResCanchas/
├── src/
│   ├── app/
│   │   ├── dashboard/
│   │   ├── guards/
│   │   ├── login/
│   │   ├── registrar-encargado/
│   │   ├── servicios/
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   ├── app.routes.ts
│   │   └── ...
│   ├── assets/
│   ├── index.html
│   ├── main.ts
│   └── styles.css
├── angular.json
├── package.json
├── tsconfig.json
├── .gitignore
├── README.md
└── ...
```

## Rutas principales

La aplicación define rutas como:

- `/login`
- `/dashboard`
- `/registrar`

Estas rutas están gestionadas mediante Angular Router y protegidas según la lógica de acceso definida en el guard de registro.

## Estado del proyecto

El frontend se encuentra en desarrollo activo como parte del sistema ResCanchas, integrándose directamente con el backend para ofrecer una solución completa de gestión deportiva.

## Licencia

Actualmente no se ha definido una licencia pública para este repositorio.

---

Proyecto frontend del sistema ResCanchas.
