# ft_strnstr

## Descripción
Localiza la primera aparición de la subcadena `needle` en la cadena `haystack`, buscando como máximo `len` caracteres.

## Mi Implementación
Para esta búsqueda, primero manejo el caso donde `needle` está vacío (devuelvo `haystack`). Luego, recorro `haystack` buscando el primer carácter de `needle`. Cuando lo encuentro, inicio un bucle secundario para verificar si el resto de la subcadena coincide, teniendo siempre cuidado de no exceder el límite de búsqueda `len`.
