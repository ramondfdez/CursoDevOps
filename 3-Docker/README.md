# 3 - Docker Fundamentals

## Objetivo

Construir imagenes Docker para distintos lenguajes y servicios, comparando enfoques simples, runtime web y multi-stage builds.

## Ejercicios en esta carpeta

### Dockerfiles en raiz

- `Demo1.Dockerfile`
- `Demo1b.Dockerfile`
- `Ejercicio3.Dockerfile`
- `Ejercicio4.Dockerfile`
- `Ejercicio4b.Dockerfile`

Ejemplo de ejecucion por archivo:

```bash
cd 3-Docker
docker build -f Demo1.Dockerfile -t demo1 .
docker run --rm demo1

docker build -f Demo1b.Dockerfile -t demo1b .
docker run --rm demo1b

docker build -f Ejercicio3.Dockerfile -t ejercicio3 .
docker run --rm ejercicio3

docker build -f Ejercicio4.Dockerfile -t ejercicio4 .
docker run --rm ejercicio4

docker build -f Ejercicio4b.Dockerfile -t ejercicio4b .
docker run --rm ejercicio4b
```

### Carpetas de ejercicios

- `apachevol/`
- `cpp/`
- `demo1/`
- `flask/`
- `go/`
- `node/`
- `php/`
- `python/`
- `react/`
- `script/`
- `script2/`
- `serverapache/`
- `web/`

## Comandos utiles

Ejemplo con Dockerfile nombrado:

```bash
cd 3-Docker
docker build -f Demo1.Dockerfile -t demo1 .
docker run --rm demo1
```

Ejemplo por carpeta:

```bash
cd 3-Docker/flask
docker build -t flask-app .
docker run --rm -p 8080:8080 flask-app
```

## Resultado de aprendizaje

- Diferenciar imagen base, capas y comando de arranque.
- Exponer puertos y ejecutar servicios web.
- Entender ventajas de multi-stage para reducir imagen final.
