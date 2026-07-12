# Ejercicio Docker - Node.js

## Objetivo

Ejecutar un servidor Node.js (Express) dentro de un contenedor.

## Archivos clave

- `Dockerfile`
- `package.json`
- `server.js`

## Comandos

```bash
cd 3-Docker/node
docker build -t docker-node .
docker run --rm -p 8080:8080 docker-node
```

## Verificacion

Abrir `http://localhost:8080` y comprobar respuesta del servidor.
