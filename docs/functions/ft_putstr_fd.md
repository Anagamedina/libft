# ft_putstr_fd

## Descripción
Escribe la cadena `s` en el descriptor de archivo dado.

## Mi Implementación
Implementé esta función recorriendo la cadena con un bucle `while` hasta encontrar el carácter nulo terminador. En cada paso, utilizo la llamada al sistema `write` para enviar el carácter actual al descriptor de archivo especificado. He incluido una comprobación para asegurar que la cadena no sea `NULL` antes de intentar procesarla, evitando así posibles fallos de segmentación.
