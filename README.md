# Java---CRUD-

MariaDB [(none)]> use escuela;
Database changed
MariaDB [escuela]> show tables;
+-------------------+
| Tables_in_escuela |
+-------------------+
| persona           |
+-------------------+
1 row in set (0.121 sec)

MariaDB [escuela]> describe persona;
+--------------------+--------------+------+-----+---------+----------------+
| Field              | Type         | Null | Key | Default | Extra          |
+--------------------+--------------+------+-----+---------+----------------+
| idPersona          | int(11)      | NO   | PRI | NULL    | auto_increment |
| clave              | varchar(10)  | NO   |     | NULL    |                |
| nombre             | varchar(50)  | NO   |     | NULL    |                |
| domicilio          | varchar(200) | NO   |     | NULL    |                |
| celular            | varchar(10)  | YES  |     | NULL    |                |
| correo_electronico | varchar(50)  | NO   |     | NULL    |                |
| fecha_nacimiento   | date         | YES  |     | NULL    |                |
| genero             | varchar(10)  | NO   |     | NULL    |                |
+--------------------+--------------+------+-----+---------+----------------+
8 rows in set (0.319 sec)
