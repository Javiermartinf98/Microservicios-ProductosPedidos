# Microservicios-ProductosPedidos 🛒
En este proyecto se intenta desarrollar un micorservicio que interaccioné con el otro microservicio.
Compuesto por varios paquetes, los cuales se muestran a continuación:
- **com.curso.controller:** En este paquete unicamente contiene las rutas donde se lanzan las consultas: 
  > ***GET***: Muestra los datos.
  
  > ***POST***: Almacena los datos que se insertan.
 
- **com.curso.dao:** Este paquete tiene la conexion con la interface JPARepository.
- **com.curso.inicio:** Pquete que contiene la clase que ejecuta las consultas.
- **com.curso.model:** Paquete donde se ponen las clases.
- **com.curso.service** En este paquete se pone la interfaz que declara los metodos y la clase impl que implementa la interfaz y se desarrolla los metodos.
