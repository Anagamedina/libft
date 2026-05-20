# ft_lstlast

## Descripción
Devuelve el último nodo de la lista.

## Mi Implementación
Para encontrar el final de la lista, inicio un recorrido desde el nodo que recibo. El bucle continúa mientras el campo `next` del nodo actual no sea `NULL`. Cuando el bucle se detiene, sé que estoy en el último elemento y lo devuelvo. He incluido una comprobación inicial para devolver `NULL` si la lista que recibo ya está vacía.
