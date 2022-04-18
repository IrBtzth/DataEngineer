# Video 5 El caracter (.)

**Cadena de Caracteres:** Es un carácter ASCII generalmente, seguido de otro carácter y de otro. No todos son visibles, el espacio por ejemplo. Cada carácter es un carácter.
**El caracter (.):** Encuentrame todo lo que sea un carácter
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
