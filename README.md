# Sentencias Sql

Las **sentencias SQL** son un términos que se utiliza en este lenguaje de dominio para referise a los comandos SQL. Existen dos tipos de sentencias en SQL que permiten la definición y manipulación de datos. 

Las sentencias **DML** se utilizan para la minipulación de datos permitiendo al usuario realizar consultas, modificaciones, inserciones y eliminación de datos. Dentro de la sentencias **DML** es posible añadir y eliminar filas  o modificar datos existentes a traves de las sentencias  ***Select, Insert, Delete y Update***.

|  Sentencias DML | Descripción           |
|---------|-------------------------------|
|  SELEC  | Recupera los datos            |
|  INSERT | Añada nuevas filas            |
|  DELETE | Elimina filas                 |
|  UPDATE | Modifica los datos existentes |

Las sentencias **DDL** se ocupan de la creaión de objetos  y las sentecia maás utilizadas ***Create Table, Drop Table, Alter Table*** para  aañadir, modificar o eliminar una tabla.

|  Sentencias DDL | Descripción                                 |
|-----------------|-----------------------------------------------------|
|  CREATE TABLE   | Añade una nueva tabla                         |
|  DROP TABLE     | Elimina tabla                                 |
|  ALTER TABLE    | Modifica la estructura de una tabla existente |
|  CREATE VIEW    | Añade una nueva vista a la base de datos      |
|  DROP VIEW      |Construye un índice para una columna           |
|  CREATE INDEX   | Suprime el índice para una columna            |
|  DROP INDEX     | Define un alias para un nombre de tabla       |
|  DROP SYNOYM    | Suprime un alias para un nombre de tabl       |






En SQL exinten otras sentencia para el control de acceso y transacciones relacionadas con los privilegios de usuario como son las denominadas **DCL**.

Otra categoría de sentencias son las **PLSQL** de tipo programático que incluyen los comandos ***Declare, Open, Fetch y Close*** .


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
 
 
 
 

