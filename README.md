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
  <tt>cd DjERP</tt>
2. Crear el ambiente virtual:
  <tt>virtualenv env --no-site-packages</tt>
3. Activamos nuestro virtualenv:
  <tt>source env/bin/activate</tt>
4. Instalamos los requerimientos:
  <tt>pip install -r requirements.txt</tt>
5. Creamos nuestra BD en este caso SQLite3:
  <tt>python manage.py syncdb</tt>
6. Iniciamos nuestra aplicación:
  <tt>python manage.py runserver</tt>
7. En tu navegador ingresa a la siguiente url:
  <tt>http://127.0.0.1:8000/admin</tt>


