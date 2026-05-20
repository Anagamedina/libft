# ft_strdup

## Descripción
Crea una copia de la cadena `s1` reservando memoria dinámicamente con `malloc`.

## Mi Implementación
Para duplicar una cadena, primero utilizo `ft_strlen` para conocer su tamaño exacto. Luego, reservo memoria suficiente para todos los caracteres más el terminador nulo. Finalmente, copio el contenido de la cadena original a la nueva zona de memoria y devuelvo el puntero. Es esencial para cuando necesitamos manipular una copia de una cadena sin alterar la original.
