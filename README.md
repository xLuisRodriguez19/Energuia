 2022CS


TECNOLOGIAS NECESARIAS.
-MySQL (usuario 'root' y contraseña 'password')

-Python


PARA INSTALAR LA BD.

-Abrir MySQL Workbench, crear el schema con el nombre 'energuia', entonces abrir el archivo sql con el nombre energuia.sql 
en MySQL Workbench y ejecutarlo
	NOTA: para poder ingresar sesion en la pagina web, deberá registrar un Usuario en la base de datos 'energuia' 
		en la tabla 'usuario' con el tipo '3' (Administrador).

PAQUETERIAS A DESCARGAR.
- Flask https://flask.palletsprojects.com/en/2.1.x/installation/
- flask_mysqldb https://pypi.org/project/Flask-MySQLdb/
	NOTA: en linux, si dice que no se reconoce el modulo instale las siguientes dependencias.
		sudo apt-get install python3-dev default-libmysqlclient-dev build-essential
		

COMO ARRANCAR EL PROYECTO
- Windows:
	python ./main.py

-Linux:
	python3 ./main.py
