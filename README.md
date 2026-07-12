# Curso DevOps - Code Space Academy

Repositorio del temario práctico de DevOps impartido en **Code Space Academy**.

Este proyecto está organizado por bloques progresivos: desde fundamentos de Linux y Docker, hasta orquestación con Docker Compose/Kubernetes y automatización CI/CD con GitLab y Jenkins.

## Objetivos del repositorio

- Aprender contenedorización de aplicaciones con Docker.
- Entender orquestación multi-servicio con Docker Compose.
- Practicar despliegues declarativos en Kubernetes.
- Introducir pipelines de CI/CD para validar, empaquetar y desplegar software.

## Estructura del temario

### 1. Intro
Ruta: `1-Intro/`

Primer contacto con Docker mediante un Dockerfile mínimo basado en Alpine.

### 2. Linux
Ruta: `2-Linux/`

Ejercicios de shell scripting, creación de estructura de carpetas y manejo de permisos.

### 3. Docker
Ruta: `3-Docker/`

Bloque central con ejercicios de construcción de imágenes para distintos stacks:

- Alpine y Ubuntu (ejemplos base)
- Apache y Nginx
- Python/Flask
- Node.js/Express
- PHP/Apache
- Go
- C++
- React (Dockerfile estándar y multi-stage)
- Scripts Bash en contenedor

### 4. Docker Compose
Ruta: `4-DockerCompose/`

Prácticas de entornos multi-contenedor:

- Web + base de datos
- Full stack con API + UI + MongoDB
- Administración con PhpMyAdmin
- Manifiestos de Kubernetes para despliegue equivalente

### 5. CI/CD
Ruta: `5-CICD/`

Pipelines de automatización con:

- GitLab CI (`.gitlab-ci.yml`)
- Jenkins (`Jenkinsfile`)

## Requisitos previos

- Docker instalado
- Docker Compose instalado (o plugin `docker compose`)
- Git
- Recomendado: VS Code + extensión Docker

## Cómo usar el repositorio

1. Entra en la carpeta del ejercicio.
2. Revisa el `README.md` del ejercicio.
3. Ejecuta los comandos de build/run indicados.

Ejemplo:

```bash
cd 3-Docker/flask
docker build -t flask-app .
docker run --rm -p 8080:8080 flask-app
```

## Convenciones de este material

- Cada carpeta principal incluye un README de contexto.
- Cada ejercicio/caso práctico incluye su README con:
  - objetivo
  - archivos clave
  - comandos
  - resultado esperado

## Observaciones

Este repositorio tiene un enfoque formativo. Algunos ejercicios muestran patrones simplificados para enseñanza (por ejemplo, credenciales en texto plano o configuraciones legacy) para discutir buenas prácticas y evolución hacia entornos productivos.

## Licencia

Material de uso académico para el curso de DevOps en Code Space Academy.
