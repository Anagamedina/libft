# ft_strlcat

## Descripción
Concatena la cadena `src` al final de `dst`, limitando el tamaño total del buffer de destino a `dstsize`. Garantiza la terminación en nulo si hay espacio.

## Mi Implementación
Esta es una versión segura de concatenación. Primero determino cuánto espacio está ya ocupado en `dst`. Luego, empiezo a añadir caracteres de `src` siempre que el tamaño total no exceda `dstsize - 1`. Al final, aseguro la terminación en nulo. La función devuelve la longitud total que la cadena habría intentado crear, lo cual es útil para detectar si hubo truncamiento.
