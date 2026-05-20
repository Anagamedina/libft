# ft_lstclear

## Descripción
Elimina y libera el nodo dado y todos los siguientes, utilizando la función `del` para el contenido y `free` para el nodo. Al final, el puntero a la lista debe ser `NULL`.

## Mi Implementación
Para limpiar una lista completa, implementé un bucle que recorre cada nodo. En cada paso, guardo una referencia al siguiente nodo antes de eliminar el actual. Utilizo la función `del` proporcionada para liberar el contenido (ya que no sé qué tipo de datos contiene) y luego libero la estructura del nodo con `free`. Al terminar el proceso, pongo el puntero original a `NULL` para evitar errores de acceso a memoria liberada.
