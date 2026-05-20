# ft_lstmap

## Descripción
Itera la lista `lst` y aplica la función `f` al contenido de cada nodo para crear una nueva lista. Si algo falla durante el proceso, libera la nueva lista completa.

## Mi Implementación
Esta es probablemente la función de listas más compleja. Mi enfoque fue crear una lista totalmente nueva basada en la original. Recorro la lista de origen, aplico la función `f` a cada contenido y uso el resultado para crear un nuevo nodo con `ft_lstnew`. Si la creación del nodo o la aplicación de la función fallan, utilizo `ft_lstclear` para borrar todo lo que había avanzado en la nueva lista, garantizando que no queden fugas de memoria (memory leaks).
