# Ejercicio Docker - Flask

## Objetivo

Levantar una API/servidor basico Flask en contenedor.

## Archivos clave

- `Dockerfile`
- `app.py`

## Comandos

```bash
cd 3-Docker/flask
docker build -t docker-flask .
docker run --rm -p 8080:8080 docker-flask
```

## Verificacion

Abrir `http://localhost:8080` y validar respuesta "Hello World".
