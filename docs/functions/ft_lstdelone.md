# ft_lstdelone

## Descripción
Toma como parámetro un nodo y libera la memoria de su contenido utilizando la función `del` dada, y después libera el propio nodo. El puntero `next` no debe ser liberado.

## Mi Implementación
Esta función realiza una "cirugía" sobre un único nodo. Me aseguro de que el nodo exista y luego llamo a la función `del` para limpiar su contenido de forma segura. Finalmente, libero la memoria de la estructura del nodo. Es una función auxiliar clave que permite una gestión de memoria granular y segura dentro de la librería.
