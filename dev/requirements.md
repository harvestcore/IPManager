# Requisitos del sistema

En este documento se encuentran registrados todos los requisitos del sistema.



## Requisitos funcionales

- Se distinguirán los clientes por medio de un subdominio en la URL.

- El sistema tendrá un sistema de autenticación.

- La visualización de datos en el frontend deberá ser en forma de listados.

- El backend será una API capaz de funcionar sin la necesidad de un frontend.

- El sistema permitirá aprovisionar máquinas.

- El sistema desplegará servicios en Docker.

- En el sistema podrá haber distintos clientes.

- El sistema permitirá la administración de clientes.

- En cada cliente podrá haber diferentes usuarios.

- El sistema permitirá la administración de usuarios.

- Los usuarios podrán ser de tipo administrador o usuario común.

- Un usuario administrador podrá crear usuarios comunes.

  


## Requisitos no funcionales

- La autenticación del usuario será mediante JWT.

- El sistema contará con tests unitarios.
- El backend estará programado en Python.
- El frontend estará programado en Typescript.
- El frontend usará Angular como framework.
- El puesto centralizado estará compuesto por un backend y un frontend.
- El backend almacenará los datos en una base de datos no relacional (MongoDB).
- El despliegue de servicios se hará mediante contenedores Docker.
- El frontend tendrá una interfaz sencilla.
- El sistema funcionará para sistemas basados en GNU Linux.
- El sistema deberá ser escalable.
- La interfaz de usuario del sistema será mediante una aplicación web.



## Requisitos de información

- Se almacenarán las diferentes configuraciones de aprovisionamiento.
- El sistema almacenará los detalles de los sistemas que aprovisiona.
- El sistema almacenará configuraciones relacionadas con los despliegues (dockerfiles, docker-compose).
- El sistema almacenará para cada cliente un identificador único, un dominio y el nombre de la base de datos correspondiente a ese cliente.
- El sistema almacenará para todo cliente y usuario si ha sido eliminado, no borrando sus datos tras eliminarlo.
- El sistema almacenará para todo usuario registrado un identificador único, el tipo de usuario (admin o regular), el nombre y apellido del usuario, un email, un nombre de usuario y una contraseña almacenada en un formato seguro.
- El sistema almacenará para cada máquina un identificador único, un nombre de la máquina, una descripción de la máquina, su dirección IPv4 y un conjunto de identificadores de scripts asociados a esa máquina.
- El sistema almacenará para cada script de aprovisionamiento un identificador único, un nombre y el script en sí.
- El sistema almacenará para cada grupo de hosts un identificador único, un nombre y el conjunto de direcciones IP asociadas.
- El sistema almacenará para cada máquina un identificador único, un nombre, una descripción, un tipo de máquina, dirección IPv4 e IPv4, dirección MAC, máscara de red, dirección broadcast y dirección de red.

