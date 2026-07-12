# Ejercicio Docker - Script Bash 2

## Objetivo

Practicar ejecucion de script y generacion de archivos en runtime del contenedor.

## Archivos clave

- `Dockerfile`
- `main.sh`

## Comandos

```bash
cd 3-Docker/script2
docker build -t docker-script2 .
docker run --rm docker-script2
```

## Nota de seguridad

Este ejercicio usa un ejemplo de credencial hardcodeada para fines docentes. No replicar este patron en produccion.
