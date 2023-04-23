# Portifolio-project

python3 -m venv .venv && source .venv/bin/activate

python manage.py startapp blog

python manage.py startapp jobs

python manage.py migrate

pip install pillow

python manage.py makemigrations

python manage.py migrate