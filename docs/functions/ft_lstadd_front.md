# ft_lstadd_front

## Descripción
Añade el nodo `new` al principio de la lista `lst`.

## Mi Implementación
Esta operación es muy eficiente. En lugar de recorrer toda la lista, simplemente hago que el puntero `next` del nuevo nodo apunte a lo que actualmente es la cabeza de la lista. Después, actualizo el puntero de la cabeza para que apunte al nuevo nodo. Es la forma más rápida de insertar elementos en una lista enlazada.
