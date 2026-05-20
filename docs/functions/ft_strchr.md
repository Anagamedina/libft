# ft_strchr

## Descripción
Localiza la primera aparición del carácter `c` (convertido a `char`) en la cadena de caracteres apuntada por `s`.

## Mi Implementación
Recorro la cadena `s` desde el principio buscando el carácter `c`. En el momento en que encuentro una coincidencia, devuelvo un puntero a esa posición exacta de la cadena. He tenido especial cuidado en manejar el caso donde `c` es el carácter nulo (`\0`), asegurándome de que la función también pueda localizar el final de la cadena.
