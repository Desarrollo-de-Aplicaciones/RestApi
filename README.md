# RestApi
Abril Rivera-Carlos Gamboa-Starlin Chavarría.
9-02-2023, se instaló la maquina virtual, se instaló el sistema operativo y se instalo el node.js, se instaló el postgre sql.
10-02-2023, se instaló postman, se instaló el entorno de desarrollo que es el visual studio code, se instaló el framework express con comandos en visual studio code y ademas se instaló una dependencia de node.js que se llama nodemon que es para que el solo actualize el servidor y no estarlo actualizando cada que se haga un cambio.
12-02-2023, se crearon las carpetas propias del proyecto llamadas SCR/DBAPI, en dicha carpeta hay 3 archivos controller, queries, routes.
15-02-2023, se creo la DB con un esquema llamado APIDA, se crearon 3 tablas llamadas Cliente y Factura, en cadda tabla se introdujeron 10 registros, la tabla factura se relaciona con las otras dos tablas creadas.
--Script del Postgre--
CREATE TABLE Producto (
ID int PRIMARY KEY,
producto VARCHAR(255),
precio int,
descripcion VARCHAR(255));

INSERT INTO Producto (ID, producto, precio, descripcion)
VALUES (1, 'Espejo', 5000, 'Grande Dorado'), (2,'Guitarra', 80000, 'Electrica');

INSERT INTO Producto (ID, producto, precio, descripcion)
VALUES (3, 'Cuaderno', 2000, 'Encolochado'), (4,'Lapiz', 1000, 'De grafito');

INSERT INTO Producto (ID, producto, precio, descripcion)
VALUES (5, 'Alcancia', 4000, 'Rosada'), (6,'Parlantes', 10000, 'Stereo');

INSERT INTO Producto (ID, producto, precio, descripcion)
VALUES (7, 'Globo', 1500, 'Corazon'), (8,'Ropero', 15500, 'De madera');

INSERT INTO Producto (ID, producto, precio, descripcion)
VALUES (9, 'Retratera', 1800, 'Familiar'), (10,'Audifonos', 500, 'Sonic');
