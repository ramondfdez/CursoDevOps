# Docker Compose - Ejercicio Full

## Objetivo

Orquestar un escenario con interfaz web, backend administrativo y MongoDB.

## Archivo clave

- `docker-compose.yml`

## Comandos

```bash
cd 4-DockerCompose/ejerciciofull
docker compose up -d
```

## Verificacion

- UI: `http://localhost`
- Herramienta admin: `http://localhost:8081`

## Observacion

Revisar el mapeo de puertos de MongoDB en `docker-compose.yml` antes de usar acceso externo al puerto 27017.
