# Porcentajes de trabajo realizado
- Diego Alvarez Cruz 100%
- Jhosep Mollapaza Morocco 100%
- Guadalupe Bedoya 100%
# backend-academic-management

## Crear entorno virtual:

python -m venv venv
source venv/bin/activate
## Instalar dependencias:

pip install -r requirements.txt
## Configurar variables de entorno:

Variables mínimas:

FLASK_APP=app.py
FLASK_ENV=development
DATABASE_URL=postgresql://<user>:<password>@<host>/<db_name>
SECRET_KEY=<una-clave-secreta>
## Iniciar el backend:

flask run
