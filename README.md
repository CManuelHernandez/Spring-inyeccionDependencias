# Spring-inyeccionDependencias

Crear aplicación con dos clases de controlador. Controlador1.java y Controlador2.java
En Controlador1, en la URL /controlador1/addPersona, tipo GET, en los headers tiene que recibir, el nombre, población y edad.
Utilizando una clase de servicio, se creará un objeto Persona. La llamada devolverá el objeto Persona creado.
En otra clase, crear el Controlador2, en la URL /controlador2/getPersona tiene que devolver el objeto Persona recibido en el Controlador1, multiplicando la edad por dos.
