# Video 5 El caracter (.)

**Cadena de Caracteres:** Es un carácter ASCII generalmente, seguido de otro carácter y de otro. No todos son visibles, el espacio por ejemplo. Cada carácter es un carácter.

**El caracter (.):** Encuentrame todo lo que sea un carácter.

**Punto + espacio (. ):** Encuentra todos los caracteres que tengan un espacio subsecuente. Puntos consecutivos (………….) Resalta el número de caracteres de acuerdo al número de puntos especificados.

# Video 6 Las clases predefinidas y construidas

**Dígitos: \d**
- Encuentra todos los dígitos de 0 a 9.
- \d es equivalente a poner [0-9].
- Si en vez de \d, usamos por ejemplo [0-2] nos encontrará solamente los dígitos de 0 a 2.
- Podemos usar “\D” para encontrar justo lo contrario, todo lo que no son dígitos.

**Palabras: \w**
- Encuentra todo lo que puede ser parte de una palabra, tanto letras (minúsculas o mayúsculas) como números.
- \w es equivalente a poner [a-zA-Z0-9_].
- Si en vez de \w, usamos por ejemplo [a-zA-Z] nos encontrará solamente las letras.
- Podemos usar “\W” para encontrar justo lo contrario, todos los caracteres que no son parte de palabras.

**Espacios: \s**
- Encuentra todos los espacios (los saltos de línea también son espacios).
- Podemos usar “\S” para encontrar justo lo contrario, todo lo que no son espacios.

# Video 7 Los delimitadores: +, *, ?

**Delimitadores:**

- (*) : Cero o más veces
- (?): Cero o una sola vez
- (+): una o más veces.
Aplican al carácter o sentencia que preceden

- [a-z]? : Esto es que puede estar una sola vez o no estar una letra minuscula de la (a) a la (z).
- \d*: Esto es que puede estar muchas veces o no estar un digito.
- \d+: Esto es que puede estar muchas veces o una sola vez un digito.

# Video Los contadores {1,4}

**Contadores:** Aplicando a un carácter que lo preceda se puede colocar entre llaves de esta forma, para indicarle que busque la cantidad deseada de caracteres.

{Cota inferiror, Cota superior}

Ejemplo:

\d{0,2}: Esto buscara 0, 1, 2 dígitos

\d{2,2}: Esto buscara 2 dígitos

\d{2}: Esto buscara 2 dígitos

\d{2,}: Esto buscara 2 o más dígitos.

\d{2,4}: Esto buscara 2, 3, 4 dígitos.

# Video 9 El caso de (?) como delimitador

**Delimitador ?:** Los matches los hace lo más pequeños posibles.Es decir, haz el match pero los divides en grupos pequeños.

*? Coincide con el elemento anterior cero o más veces, pero el menor número de veces que sea posible.

+? Coincide con el elemento anterior una o más veces, pero el menor número de veces que sea posible.

?? Coincide con el elemento anterior cero o una vez, pero el menor número de veces que sea posible

# Video 10 Not (^), su uso y sus peligros

Este caracter nos permite negar una clase o construir “anticlases”, vamos a llamarlo así, que es: toda la serie de caracteres que no queremos que entren en nuestro resultado de búsqueda.

Para esto definimos una clase, por ejemplo: [ 0-9 ], y la negamos [ ^0-9 ] para buscar todos los caracteres que coincidan con cualquier caracter que no sea 0,1,2,3,4,5,6,7,8 ó 9

# Video 11 Reto: Filtrando letras en números telefónicos utilizando negaciones

En el texto siguiente:

<p>555658
56-58-11
56.58.11
56.78-98
65 09 87
76y87r98</p>

Definir un patrón que haga match a todas las líneas excepto a la la última, la que tiene letras.

(\d{2,2}\W?){3}

# Video 12 Principio (^) y final de linea ($)

Estos dos caracteres indican en qué posición de la línea debe hacerse la búsqueda:

el ^ se utiliza para indicar el principio de línea

el $ se utiliza para indicar final de línea

^ ------------- $

# Video 13 Logs
<p>[LOG ENTRY] [ERROR] The system is unstable
[LOG ENTRY] [WARN] The system may be down
[LOG ENTRY] [WARN] Microsoft just bought Github
[LOG DATA] [LOG] Everything is OK
[LOG ENTRY] [LOG] [user:@beco] Logged in
[LOG ENTRY] [LOG] [user:@beco] Clicked here
[LOG DATA] [LOG] [user:@celismx] Did something
[LOG ENTRY] [LOG] [user:@beco] Rated the app
[LOG ENTRY] [LOG] [user:@beco] Logged out
[LOG LINE] [LOG] [user:@celismx] Logged in</p>
![image](https://user-images.githubusercontent.com/57947170/163825683-f9d6c4b4-7614-4c43-8f84-c31f6c0fb0f1.png)

# Video 14 Teléfonos
![image](https://user-images.githubusercontent.com/57947170/163827440-7ce64ae4-2aab-433b-b6b5-bdfa2ed87ab0.png)

#  Video 15 URLs
![image](https://user-images.githubusercontent.com/57947170/163828325-91eced89-e74e-4a91-bf62-c3dce20c6e16.png)

# Video 16 Mails

## Dominio
![image](https://user-images.githubusercontent.com/57947170/163829191-3966e6eb-51b3-4a26-938e-81396647e260.png)

## Mail completo
![image](https://user-images.githubusercontent.com/57947170/163830294-7041a62a-902f-4332-86d4-fbd75506546d.png)

# Video 17 Localizaciones

![image](https://user-images.githubusercontent.com/57947170/163832198-240e0e1b-e74b-4adc-923b-b6363d36b004.png)
![image](https://user-images.githubusercontent.com/57947170/163833986-aa86b41d-0d24-4a21-986d-0f65e6bc9a27.png)

# Video 19 Búsqueda y reemplazo

![image](https://user-images.githubusercontent.com/57947170/163838404-e19180a3-a714-4364-b5fe-b695a04b33b2.png)

# Video 20 Uso de REGEX para descomponer querys GET

![image](https://user-images.githubusercontent.com/57947170/166972698-a26947d7-60ed-49ef-86e5-09f7d4091f3d.png)
![image](https://user-images.githubusercontent.com/57947170/166972764-4385874d-cb1d-4252-a3e3-64bb5e351966.png)
Find: [\?&](\w+)=([^&\n]+)
Replace: \n - $1=$2





