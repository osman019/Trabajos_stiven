# Documentacion de las 20 Consultas

# Consultas simples 

1.Has una consulta que muestre todos los datos de los  usuarios de la biblioteca.

SELECT * FROM Usuarios;

2.Realiza una consulta que muestre todas las categorias de libros disponibles en la biblioteca.

SELECT nombre_categoria FROM Categorias;

3.Crea una consulta que muestre el id del libro titulo, año de publicacion y el id de categoria ordenados por titulo de forma ascendente.

SELECT  id_libro, titulo, año_publicacion,id_categoria FROM Libros ORDER  BY titulo ASC;

4.has una consulta que muestre los libros en los cuales su fecha de publicacio es igual o mayor a 2000. 

SELECT titulo FROM Libros  WHERE año_publicacion >=  2000;

5.Se necesita saber el numero de telefono del  siguiente usuario "Osman" realiza una consulta para esto.

SELECT telefono FROM Usuarios WHERE nombre_usuario = 'Osman';
