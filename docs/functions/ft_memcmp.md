# ft_memcmp

## Descripción
Compara los primeros `n` bytes de dos áreas de memoria `s1` y `s2`.

## Mi Implementación
Implementé esta comparación recorriendo ambas áreas simultáneamente. En el momento en que encuentro dos bytes diferentes, devuelvo la diferencia entre ellos (s1 - s2). Si llego al final de los `n` bytes sin encontrar diferencias, devuelvo 0. Al igual que en otras funciones `mem`, utilizo punteros a `unsigned char` para garantizar que la comparación sea consistente byte a byte.
