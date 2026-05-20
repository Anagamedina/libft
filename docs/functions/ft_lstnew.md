# ft_lstnew

## Descripción
Crea un nuevo nodo utilizando `malloc`. El miembro `content` se inicializa con el valor del parámetro y el miembro `next` se pone a `NULL`.

## Mi Implementación
Es el constructor básico de mis nodos de lista. Reservo memoria para la estructura `t_list` y, si la asignación es exitosa, inicializo sus campos. El contenido puede ser cualquier tipo de dato (por eso es `void *`), y el puntero al siguiente nodo se establece en `NULL` por defecto para indicar que, de momento, es un nodo aislado.
