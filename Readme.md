# 🌀 Sistema CNSC - Backend (Django + DFR + PostgreSQL)

## ⭐ Estructura inicial

```bash
cnsc/
  backend/          # Proyecto Django (entorno virtual + configuración)
    .venv/          # Entorno virtual
    sistema_cnsc/   # Configuración principal de Django
    manage.py
  frontend/         # Next.js (pendiente)

## 🛠️ Stack tecnologico

- 🐍 Lenguaje: Python                    3.13.0
- 🎯 Framework backend: Django           5.2.5
- ⚡ API: Django REST Framework          3.16.1
- 🔑 Autenticacion: Simplejwt            5.5.1
- 🗄️ Base de datos: PostgreSQL
- 🧩 ORM: Django ORM

### ⚙️ Instalación y configuración

## 1. Clonar repositorio

git clone <URL_DEL_REPO>
cd cnsc/backend

## 2. Crear entorno virtual

.venv\Scripts\Activate    # Windows
source .venv/bin/activate # Linux/Mac

## 3. Activar entorno virtual

.venv\Scripts\Activate

## 4. Instalar dependencias

pip install -r requirements.txt

## 5. Migracion de bases de datos

python manage.py migrate

## 6. Crear super usuario

python manage.py createsuperuser

## 7. Levantar el servidor 

python manage.py runserver
# 👉 http://127.0.0.1:8000

En caso de presentar problemas con el puerto (8000 predeterminado), seleccionar puerto 8080

python manage.py runserver 8080
# 👉 http://127.0.0.1:8080

