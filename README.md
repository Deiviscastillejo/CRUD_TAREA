# CRUD_PHP
TALLER_CRUD - TAREAS - UNAC Tec

Nota: Para poner en funcionamiento, es importante que de manera local se cree la base de datos con los campos y sus tipos de datos correspondientes, y modificar los datos correspondiente en la clase conexion.php en la carpeta modelo

base de datos: 

create database tarea;


USE tarea;
CREATE TABLE tbl_tarea(
    id_tarea int NOT null AUTO_INCREMENT PRIMARY KEY,
    titulo varchar(50),
    descripcion varchar(200),
    fecha_creacion date,
    fecha_finalizacion date,
    completada varchar(20)
    
);

