# MySql
##  Pasos para crear una bases de datos a través de código sql
 1. Dar clic en el en el botón sql para abrir el editor de código y crear la base de datos. Luego dar clic en el icono en forma de execute :zap: y verifica en la parte inferior que esta ha sido creada con el check :ballot_box_with_check: y en el SCHEMAS actualizar.
 
 ---La sentencia **CREATE DATABASE** se utiliza para crear una nueva BD.
 
 
 ```Sql:
 
 // listar BD creadas, crear BD y usar BD
 SHOW DATABASES;
 CREATE DATABASE IF NOT EXISTS supermecadodb;
 SHOW DATABASES;
 USE supermecadodb;
 
 ```
Luego dar clic en el icono en forma de execute :zap: y verifica en la parte inferior que esta ha sido creada con el check :ballot_box_with_check: y en el SCHEMAS actualizar.
 
 ---La sentencia **CREATE TABLE** define una tabla y los atributos de la misma.
 
```Sql:

SHOW TABLES;

//Listar las tablas de la BD, crear una tabla en la BD, definir los atributos de la tabla.

CREATE TABLE Person (
    personId INT AUTO_INCREMENT,
    name VARCHAR(20),
    PRIMARY KEY(personId)
);

SHOW TABLES;

DESCRIBE Persona;

INSERT INTO Person (name)
VALUES ('Jose'), ('Maria'), ('Daniela');

SELECT * FROM Person;
SELECT name FROM Person;
SELECT name, personId FROM Person;

```
---La sentencia **DROP** borra tablas.
 
 ```Sql:
DROP DATABASE supermecadodb;

```
Para eliminar  la base de datos utilizamos el comando DROP DATABASE, selecionamos el comado y ejecutamos :zap:. 
 
 
 
 

