# ft_strncmp

## Descripción
Compara los primeros `n` caracteres de las cadenas `s1` y `s2`.

## Mi Implementación
Implementé la comparación carácter a carácter utilizando punteros a `unsigned char` para asegurar que la resta de valores ASCII sea correcta. El bucle se detiene si encuentro una diferencia, si llego al límite `n` o si alguna de las cadenas termina. Devuelvo la diferencia entre los primeros caracteres distintos que encuentre, o 0 si son idénticas hasta el punto `n`.
