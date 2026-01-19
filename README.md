# Tienda Online Minimalista para proyecto de Conquerblocks - Django

Proyecto desarrollado en Django como parte del módulo de backend.

## Descripción

Aplicación de e-commerce básica sin pasarela de pago real. Permite:

- Gestión de productos y categorías desde el panel de administración
- Listado público de productos
- Página de detalle de cada producto

## Tecnologías

- Python
- Django
- SQLite (desarrollo)

## Instalación en local

```bash
git clone <URL_DEL_REPOSITORIO>
cd tienda_online
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

## Acceso
- Panel de administración: `/admin`
```
