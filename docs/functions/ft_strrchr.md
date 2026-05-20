# ft_strrchr

## Descripción
Localiza la última aparición del carácter `c` (convertido a `char`) en la cadena de caracteres apuntada por `s`.

## Mi Implementación
Para encontrar la última aparición, primero calculo la longitud de la cadena para empezar a buscar desde el final hacia atrás. Voy retrocediendo hasta encontrar el carácter `c` o hasta llegar al principio de la cadena. Al igual que en `strchr`, manejo correctamente la búsqueda del carácter nulo.
