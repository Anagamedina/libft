# ft_memmove

## Descripción
Copia `len` bytes del área de memoria `src` al área de memoria `dst`, manejando correctamente el posible solapamiento entre las áreas.

## Mi Implementación
Esta función fue un reto interesante. Para evitar que los datos se corrompan por solapamiento, decidí comparar las direcciones de memoria. Si el destino está después de la fuente (`src < dst`), realizo la copia de atrás hacia adelante. De lo contrario, copio de forma normal de adelante hacia atrás. Esta lógica garantiza que los datos de origen no se sobrescriban antes de ser copiados al destino.
