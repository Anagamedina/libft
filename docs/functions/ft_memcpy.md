# ft_memcpy

## Descripción
Copia `n` bytes del área de memoria `src` al área de memoria `dst`. Las áreas no deben solaparse.

## Mi Implementación
Mi versión de `ft_memcpy` copia los bytes uno a uno de la fuente al destino utilizando punteros auxiliares de tipo `unsigned char`. Añadí una comprobación inicial para manejar el caso en que tanto el destino como la fuente sean `NULL`, en cuyo caso devuelvo `NULL`. Es una función de alto rendimiento diseñada para copias rápidas donde sabemos que no hay solapamiento.
