# ft_tolower

## Descripción
Convierte un carácter en mayúscula a su equivalente en minúscula, si el carácter es una letra mayúscula.

## Mi Implementación
Para esta función, compruebo si el valor ASCII del carácter se encuentra en el rango de las letras mayúsculas (de la 'A' a la 'Z'). Si es así, le sumo 32, que es la distancia constante en la tabla ASCII entre una mayúscula y su minúscula correspondiente. Si el carácter no es una mayúscula, lo devuelvo tal cual sin realizar ninguna modificación.
