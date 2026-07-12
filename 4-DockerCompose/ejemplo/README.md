# Docker Compose - Ejemplo PHP + MySQL

## Objetivo

Conectar aplicacion web PHP con MySQL usando Compose y volumen persistente.

## Archivos clave

- `docker-compose.yml`
- `index.html`

## Comandos

```bash
cd 4-DockerCompose/ejemplo
docker compose up -d
```

## Verificacion

- Web: `http://localhost:8080`
- Base de datos activa en el servicio `db`.
