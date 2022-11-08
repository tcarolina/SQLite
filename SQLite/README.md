ESTRUCTURA DE DATOS

TALLER 
TRABAJO EN CLASE

1.UPDATE
RTA/:UPDATE se utiliza para modificar un subconjunto de los valores almacenados en cero o más filas de la tabla de la base de datos.
ej.update usuarios set clave='RealMadrid'; donde en la tabla de usuarios modifica la clave
 
2.ESTRUCTURA DE LA BASE DE DATOS .SCHEMA
RTA/:.schema es un comando sqlite que muestra la estructura de una tabla. Devolverá cómo la tabla consta de todas sus propiedades y sus tipos de datos y atributos.

3.DATE AND TIME FUNCTIONS
RTA/:-La función SQLite date() se usa para calcular la fecha y devolverla en el formato 'YYYY-MM-DD'.
-La función SQLite datetime() se utiliza para calcular un valor de fecha/hora y devolverlo en el formato 'YYYY-MM-DD HH:MM:SS'.

4.PRIMARY KEY CONSTRAINT
RTA/:-La clave principal de SQLite es un campo simple o una combinación de campos que se utiliza para definir un registro de forma única. Una tabla solo puede tener una clave principal.
-La clave principal generalmente se crea en el momento de crear la tabla. Definimos la clave principal mientras ejecutamos la instrucción CREATE TABLE.

![Image text](https://github.com/tcarolina/SQLite/blob/main/SQLite/Imagenes/Captura1.PNG)

5.NOT NULL CONSTRAINT
RTA/:-nos dice que los registros en este campo o columna no pueden ser nulos, por lo que se deben guardar algun registro.

6.UNIQUE CONSTRAINT
RTA/:Este atributo asignado a una columna significa que el campo es único y no se pueden escribir ni almacenar varios registros con los mismos datos.

7.DEFAULT CONSTRAINT
RTA/:Esta propiedad significa que el registro almacenado en esta columna tiene un valor predeterminado, por lo que si le agregamos datos, utilizará el valor especificado anteriormente.

8.CHECK CONSTRAINT
RTA/:-Las restricciones de SQLite CHECK le permiten definir expresiones para probar valores cada vez que se insertan o actualizan dentro de una columna.

-Si los valores no cumplen con los criterios definidos por la expresión, SQLite emitirá una violación de restricción y anulará la declaración. indica que los únicos datos que se pueden almacenar por medio de condiciones.

9.ALTER TABLE
RTA/:permite estas alteraciones de una tabla existente: se puede renombrar; se puede cambiar el nombre de una columna; se le puede agregar una columna; o se puede quitar una columna.

10.DELETE, DROP
RTA/:-DELETEle permite eliminar una fila, varias filas y todas las filas de una tabla.
- DROP TABLE se utiliza para eliminar una definición de tabla y todos los datos, índices, activadores, restricciones y especificaciones de permisos asociados para esa tabla.

11.BACKUP, RESTORE
RTA/:.backup proporciona el comando dot que le permite realizar una copia de seguridad de una base de datos de forma rápida y sencilla.
ej'.backup Store Store_backup.db


referencia:https://www.javatpoint.com/sqlite-date-and-time , 
           https://www.tutorialspoint.com/sqlite/index.htm 