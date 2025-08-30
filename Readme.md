# Home About Project

Este proyecto es una aplicación web construida con Django.

## Estructura del proyecto

- `django_base/`: Configuración principal de Django (settings, urls, wsgi, asgi).
- `pages/`: Aplicación principal con vistas, modelos y administración.
- `templates/`: Archivos HTML para las vistas (`home.html`, `about.html`, `_base.html`).
- `db.sqlite3`: Base de datos SQLite.
- `manage.py`: Script de gestión de Django.
- `requirements.txt`: Dependencias del proyecto.

## Instalación y ejecución

1. Instala las dependencias:
	```bash
	pip install -r requirements.txt
	```
2. Ejecuta las migraciones:
	```bash
	python manage.py migrate
	```
3. Inicia el servidor de desarrollo:
	```bash
	python manage.py runserver
	```
4. Accede a la aplicación en [http://localhost:8000](http://localhost:8000)

## Estructura de URLs

- `/`: Página principal (home)
- `/about/`: Página "about"

## Autor

GerardoGG42
