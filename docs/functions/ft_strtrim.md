# ft_strtrim

## Descripción
Elimina todos los caracteres del conjunto `set` del principio y del final de la cadena `s1`.

## Mi Implementación
Mi estrategia fue identificar primero los límites de la nueva cadena. Recorro `s1` desde el inicio para saltar los caracteres que están en `set`, y luego hago lo mismo desde el final hacia atrás. Una vez que tengo los índices de inicio y fin, utilizo mi función `ft_substr` para extraer y devolver la parte limpia de la cadena.
