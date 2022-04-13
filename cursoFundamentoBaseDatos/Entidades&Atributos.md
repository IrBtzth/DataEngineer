# Entidades y atributos
Una entidad es algo similar a un objeto (programación orientada a objetos) y representa algo en el mundo real, incluso algo abstracto. Tienen atributos que son las cosas que los hacen ser una entidad y por convención se ponen en plural.
Los atributos compuestos son aquellos que tienen atributos ellos mismos.

Los atributos llave son aquellos que identifican a la entidad y no pueden ser repetidos. Existen:

- Naturales: son inherentes al objeto como el número de serie
- Clave artificial: no es inherente al objeto y se asigna de manera arbitraria.

Entidades fuertes: son entidades que pueden sobrevivir por sí solas.
<p>Entidades débiles: no pueden existir sin una entidad fuerte y se representan con un cuadrado con doble línea.</p>

- Identidades débiles por identidad: no se diferencian entre sí más que por la clave de su identidad fuerte.
- Identidades débiles por existencia: se les asigna una clave propia.
![diagramaBaseDeDatos1](https://user-images.githubusercontent.com/57947170/162599578-0bfb3906-3634-4420-86fb-9252f1986501.png)

![diagramaBaseDeDatos](https://user-images.githubusercontent.com/57947170/162599292-61f6517e-ef6a-4dda-84db-4472bec0d8f9.png)

# Relaciones 
Las relaciones, representadas por un rombo, sirven para crear relaciones entre entidades. Por convención las relaciones son verbos que conectan entidades. Existen entidades multivaluadas o compuestas que tienen vida propia y se relacionan con otras entidades, por lo que se pueden normalizar (concepto que se explicará luego)

Cardinalidad

<p> Es una propiedad de las relaciones que indica la cantidad y correspondencia con la que puede estar relacionada una entidad y puede ser uno a uno, uno a varios, varios a uno y varios a varios.</p>

![jhdbcjsd](https://user-images.githubusercontent.com/57947170/163229030-b682df67-8dd0-4cea-bc21-396548a93414.png)

# Diagrama ER
![image](https://user-images.githubusercontent.com/57947170/163232685-a66e7751-1866-49cb-88bc-4b2102bd62ca.png)
# Diagrama Físico: tipos de datos y constraints
Tipos de dato:

- Texto: CHAR(n), VARCHAR(n), TEXT
- Números: INTEGER, BIGINT, SMALLINT, DECIMAL(n,s), NUMERIC(n,s)
- Fecha/hora: DATE, TIME, DATETIME, TIMESTAMP
- Lógicos: BOOLEAN
![image](https://user-images.githubusercontent.com/57947170/163232851-bba088a5-e2b5-4128-910b-a302bf1238e5.png)
