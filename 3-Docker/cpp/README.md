# Ejercicio Docker - C++

## Objetivo

Compilar y ejecutar una aplicacion C++ dentro de Docker.

## Archivos clave

- `Dockerfile`
- `source1.cpp`

## Comandos

```bash
cd 3-Docker/cpp
docker build -t docker-cpp .
docker run --rm docker-cpp
```

## Verificacion

Comprobar salida del programa C++ en consola.
