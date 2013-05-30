DjERP
=====

Requerimientos
--------------
1. Python 2.7
2. Django 1.5.1
3. django-bootstrap-toolkit 2.12.0
4. South

Instalación
-----------
Estos pasos funcionan correctamente en Linux y Mac OS

1. Ingresamos al directorio del proyecto:
<tt>cd DjERP</tt>

1. Creamos nuestra BD:
<tt>python manage.py syncdb</tt>

1. Iniciamos nuestra aplicación:
<tt>python manage.py runserver</tt>

1. En tu navegador ingresa a la siguiente url:
<tt>http://127.0.0.1:8000/admin</tt>


Instalación con virtualenv
--------------------------
Estos pasos funcionan correctamente en Linux y Mac OS

1. Ingresamos al directorio del proyecto:
<tt>cd DjERP</tt>

1. Crear el ambiente virtual:
<tt>virtualenv env --no-site-packages</tt>

1. Activamos nuestro virtualenv:
<tt>source env/bin/activate</tt>

1. Instalamos los requerimientos:
<tt>pip install -r requirements.txt</tt>

1. Creamos nuestra BD:
<tt>python manage.py syncdb</tt>

1. Iniciamos nuestra aplicación:
<tt>python manage.py runserver</tt>

1. En tu navegador ingresa a la siguiente url:
<tt>http://127.0.0.1:8000/admin</tt>


