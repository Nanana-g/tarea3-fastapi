# FastAPI Simple API

Una API básica construida con FastAPI, con versionamiento Git y containerización Docker.

## Requisitos

- Python 3.11
- Docker
- Git

## Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/tu_usuario/fastapi_api.git
Instalar dependencias:

pip install -r requirements.txt

Uso
Para ejecutar localmente:


uvicorn main:app --reload
Para ejecutar con Docker:


docker build -t mi-api .
docker run -p 8000:8000 mi-api
Estructura de Branches
main: Producción
staging: Pre-producción
develop: Desarrollo
features/*: Nuevas funcionalidades
API Endpoints
GET /: Retorna un mensaje de bienvenida