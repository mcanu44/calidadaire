El archivo siata.sql.tar.gz contiene una bases de datos
de MySql, para instalarlo:

Mac:
$ brew install mysl

Linux/Ubuntu/Debian:
$ sudo apt-get update
$ sudo apt-get install mysql-server
$ sudo mysql_secure_installation

Despues se pude crear la base de datos ejecutando
estos comandos en la consola:
$ tar -zxf siata.sql.tar
$ mysql -u root -p siata < siata.sql