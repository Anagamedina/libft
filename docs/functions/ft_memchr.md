# ft_memchr

## Descripción
Busca la primera aparición del byte `c` (interpretado como un `unsigned char`) en los primeros `n` bytes del área de memoria `s`.

## Mi Implementación
Recorrí el área de memoria byte a byte comparando cada uno con el valor buscado. En cuanto encuentro una coincidencia, devuelvo el puntero a esa posición exacta, realizando un cast a `void *`. Si termino de recorrer los `n` bytes sin éxito, devuelvo `NULL`. Es fundamental tratar los datos como `unsigned char` para asegurar una comparación de bytes pura.
