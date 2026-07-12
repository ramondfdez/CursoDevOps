# 1 - Introduccion a Docker

## Objetivo

Entender la estructura minima de un Dockerfile y ejecutar una imagen simple basada en Alpine.

## Archivos

- `Dockerfile`

## Ejecucion

```bash
cd 1-Intro
docker build -t intro-alpine .
docker run --rm intro-alpine
```

## Resultado esperado

- Imagen construida correctamente.
- Ejecucion del contenedor sin errores.
