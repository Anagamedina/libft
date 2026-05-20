# ft_lstadd_back

## Descripción
Añade el nodo `new` al final de la lista `lst`.

## Mi Implementación
Para añadir un elemento al final, primero compruebo si la lista está vacía. Si es así, el nuevo nodo se convierte directamente en el primer elemento. Si la lista ya contiene elementos, utilizo un puntero auxiliar para recorrerla hasta encontrar el último nodo (aquel cuyo puntero `next` es `NULL`). Una vez localizado, simplemente enlazo ese último nodo con el nuevo. Es una operación fundamental para mantener el orden cronológico de inserción en una lista.
