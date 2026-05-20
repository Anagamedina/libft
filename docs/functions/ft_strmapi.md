# ft_strmapi

## Descripción
Crea una nueva cadena aplicando la función `f` a cada carácter de la cadena `s`, pasando su índice como primer argumento.

## Mi Implementación
A diferencia de `striteri`, esta función no modifica la cadena original. Primero reservo memoria para una nueva cadena del mismo tamaño que `s`. Luego, recorro `s` y guardo en la nueva cadena el resultado de aplicar `f` a cada carácter. Es ideal para crear versiones transformadas de un texto (por ejemplo, pasar a mayúsculas) manteniendo la original intacta.
