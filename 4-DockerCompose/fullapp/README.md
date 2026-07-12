# Docker Compose - Full App (API + UI + MongoDB)

## Objetivo

Levantar una aplicacion completa con base de datos, backend Node.js y frontend React.

## Archivos clave

- `docker-compose.yml`
- `api/`
- `ui/`

## Variables de entorno

Antes de ejecutar, define un `.env` en esta carpeta con variables de puertos y credenciales (MongoDB, API y UI).

## Comandos

```bash
cd 4-DockerCompose/fullapp
docker compose up -d --build
```

## Verificacion

- UI en el puerto configurado por `REACT_LOCAL_PORT`.
- API en el puerto configurado por `NODE_LOCAL_PORT`.

## Nota

Existe un archivo de rutas llamado `turorial.routes.js` (nombre original del ejercicio).
