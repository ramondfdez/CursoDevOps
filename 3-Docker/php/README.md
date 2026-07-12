# Ejercicio Docker - PHP con Apache

## Objetivo

Publicar una aplicacion PHP sencilla con Apache.

## Archivos clave

- `Dockerfile`
- `src/index.php`

## Comandos

```bash
cd 3-Docker/php
docker build -t docker-php .
docker run --rm -p 8080:80 docker-php
```

## Verificacion

Abrir `http://localhost:8080` y validar salida de PHP.
