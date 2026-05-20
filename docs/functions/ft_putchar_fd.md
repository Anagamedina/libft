# ft_putchar_fd

## Descripción
Escribe el carácter `c` en el descriptor de archivo dado.

## Mi Implementación
Mi implementación es una simple llamada a la función del sistema `write`. Paso la dirección del carácter y especifico que quiero escribir un solo byte en el descriptor de archivo proporcionado. Es la unidad básica de salida de mi librería y la base para funciones más complejas como la impresión de cadenas o números.
