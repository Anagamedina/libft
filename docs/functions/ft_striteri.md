# ft_striteri

## Descripción
Aplica la función `f` a cada carácter de la cadena `s`, pasando su índice como primer argumento. Cada carácter se pasa por dirección a `f` para poder ser modificado si es necesario.

## Mi Implementación
Implementé esta función como un iterador simple. Utilizo un bucle para recorrer la cadena `s` y, en cada posición, llamo a la función `f` proporcionada, pasándole el índice actual y la dirección de memoria del carácter correspondiente (`&s[i]`). Esto permite realizar transformaciones complejas directamente sobre la cadena original.
