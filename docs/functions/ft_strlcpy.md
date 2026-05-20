# ft_strlcpy

## Descripción
Copia la cadena `src` en el buffer `dst`, limitando el tamaño de la copia a `size`. Garantiza la terminación en nulo.

## Mi Implementación
A diferencia de `strncpy`, mi implementación de `ft_strlcpy` se asegura de que la cadena de destino siempre termine en nulo (si `size > 0`). Copio hasta `size - 1` caracteres de la fuente y luego añado el `\0`. Devuelvo la longitud de la cadena que intenté copiar (`src`), lo que permite al usuario saber si el buffer de destino fue lo suficientemente grande.
