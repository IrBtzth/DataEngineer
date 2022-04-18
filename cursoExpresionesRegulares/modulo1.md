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



