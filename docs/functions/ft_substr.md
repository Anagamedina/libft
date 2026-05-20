# ft_substr

## Descripción
Reserva memoria y devuelve una subcadena de la cadena `s`. La subcadena empieza en el índice `start` y tiene una longitud máxima de `len`.

## Mi Implementación
En esta función, lo más importante fue gestionar correctamente los límites. Compruebo si `start` está fuera de la cadena original y ajusto `len` si la subcadena solicitada es más larga que lo que queda de la cadena original. Tras calcular el tamaño real necesario, reservo memoria y copio los caracteres correspondientes.
