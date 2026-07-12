# 4 - Docker Compose y Orquestacion

## Objetivo

Levantar aplicaciones multi-servicio de forma declarativa y entender relaciones entre servicios, redes y volumenes.

## Contenido

- Ejemplos basicos (`demo1`, `ejemplo`)
- Escenarios completos (`ejerciciofull`, `fullapp`)
- Administracion (`phpmyadmin`)
- Preparacion para Kubernetes (`kubernetes`)

## Ejecucion base

```bash
cd 4-DockerCompose/demo1
docker compose up
```

Si tu version usa comando legacy, sustituye por `docker-compose up`.

## Resultado de aprendizaje

- Definir servicios, dependencias y puertos.
- Persistir datos con volumenes.
- Comprender el paso de Compose a Kubernetes.
