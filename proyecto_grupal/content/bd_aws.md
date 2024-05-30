# Creación de Base de Datos en AWS

Para la creación de la base de datos, desde una cuenta ya creada en AWS se crea una instancia PostgresSQL en RDS permitiendo el acceso publico y definiendo una `inbound rule` de tipo PostgreSQL para realizar la conexión desde la ip local.

Con el endpoint dado por aws, el puerto 5432 dado por defecto y las credenciales definidas de forma manual se realiza la conexión a la bases de datos creada llamada `analítica` definiendo las variables de entorno.

![](../assets/aws.png)
