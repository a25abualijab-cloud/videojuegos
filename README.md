# videojuegos
# Videojuegos Abubakar Web

AEA5.2. Desenvolupament d’un CRUD en PHP (MySQLi) en servidor real

# Descripció
He fet aquest projecte amb l'ajuda del tutorial del Parzibyte que m'ha permet fer les 4 operacions bàsiques sobre una base de dades MySQL, després també vaig fer canvis dins de la carpeta del CSS important un bootstrap per donar-li un disseny guapo a la página web

- **Crear** nous registres
- **Llegir** i mostrar tots els registres
- **Actualitzar** registres existents
- **Eliminar** registres

# Estructura de la base de dades

CREATE TABLE videojuegos(
    id bigint unsigned not null primary key auto_increment,
    nombre varchar(255),
    descripcion varchar(255)
);
