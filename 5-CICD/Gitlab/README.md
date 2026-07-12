# GitLab CI - Ejercicios

## Archivos

- `ejercicio.gitlab-ci.yml`: pipeline completo con lint, build, test y despliegue.
- `python.gitlab-ci.yml`: pipeline basico para proyecto Python.

## Objetivo

Practicar la estructura de stages/jobs y variables de entorno en GitLab CI.

## Uso recomendado

1. Copiar el contenido del archivo al `.gitlab-ci.yml` de un repositorio GitLab.
2. Configurar variables CI/CD necesarias.
3. Ejecutar pipeline desde GitLab.

## Nota

El pipeline de Python referencia `helloworld.py`; crea ese archivo o adapta el comando para evitar fallo del job.
