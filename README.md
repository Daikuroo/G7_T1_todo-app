# G7_T1_todo-app
Desarrollo de la app "to do" incluida en el tutorial de Docker estudiando e implementando el S-SDLC

# Cómo ejecutar la aplicación

Este proyecto contiene una aplicación web de tareas con frontend y backend separados, listos para ejecutarse usando Docker.

---

## Requisitos

- Docker Desktop instalado y corriendo en tu máquina (Windows, macOS o Linux)
- Git instalado para clonar el repositorio

---

## Pasos para ejecutar la app localmente

### 1. Clonar este repositorio

[bash]
git clone https://github.com/Daikuroo/G7_T1_todo-app.git
cd G7_T1_todo-app/app

### 2. Levantar la app con Docker
Puedes usar dos comandos distintos:

[bash]
docker compose up --build
///
o alternativamente
///
docker compose -f 'compose.yml' up -d --build

### 3. Acceder con tu navegador
Abre tu navegador y visita http://localhost:80

### 4. Detener la app
Para ello puedes acceder directamente a Docker Desktop y terminar la app
o puedes usar el siguiente comando:

[bash]
docker compose down
///
Si has usado el primer comando en el apartado 2 es posible que sea necesario
Crtl^C para poder escribir el comando

# Más información
Para información más detalladas se puede acceder a /docs o a /security.
