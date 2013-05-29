DjERP
=====

Requerimientos
--------------
1. Python 1.7
2. Virtualenv

Instalación
-----------
Estos pasos funcionan correctamente en Linux y Mac OS

1. Ingresamos al directorio del proyecto:
  cd DjERP
2. Crear el ambiente virtual:
  virtualenv env --no-site-packages
3. Activamos nuestro virtualenv:
  source env/bin/activate
4. Instalamos los requerimientos:
  pip install -r requirements.txt
5. Creamos nuestra BD en este caso SQLite3:
  python manage.py syncdb
6. Iniciamos nuestra aplicación:
  python manage.py runserver
7. En tu navegador ingresa a la siguiente url:
  http://127.0.0.1:8000/admin
