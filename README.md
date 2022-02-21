# crossairs-jpa-hibernate-console
Gestión de billetes en una agencia de viajes

## Requisitos

Se quiere implementar el sistema informático para la gestión de una agencia de viajes. Las especificaciones funcionales son las siguientes:

- Se tienen distintos destinos, entre las que se destacan [1.] París, [2.] Nueva York, [3.] Londres y [4.] Tokio. Estos destinos deben ser gestionables por la aplicación (CRUD).
- En la agencia se manejan vuelos, que tendrán los siguientes atributos: código, descripción, origen, destino, compañía aérea, fecha.
- Las compañías aéreas son otra entidad importante en nuestro modelo, por lo que también ser gestionará el alta, baja y modificación de las mismas.
- De cada vuelo existirá un número finito de billetes, que tendrán un identificador y un estado: [1.] libre, [2.] reservado, [3.] comprado y [4.] cancelado.
- Se tendrán registrados usuarios, que contarán con una clave alfanumérica que los identifique de manera inequívoca.
- Cada uno de los usuarios puede comprar los billetes que desee, y se debe llevar un registro del histórico los billetes que compra cada uno de los usuarios.

Se pide:

1. Diagrama UML de entidad - relación del modelo de dominio.
2. Diagrama UML de base de datos SQL y su correspondiente script de creación de tablas.
3. Diagrama UML de clases así como hacer una pequeña aplicación de consola que permita hacer las operaciones CRUD básicas sobre las entidades del modelo de dominio.
