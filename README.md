# Libft - Mi Primera Librería en C

## Descripción
Este proyecto consiste en la creación de una librería estática en C llamada `libft.a`. Es una recreación de diversas funciones estándar de la librería de C (`libc`), así como otras funciones de utilidad para la manipulación de memoria, cadenas de caracteres y listas enlazadas.

El objetivo de esta librería es ser utilizada en futuros proyectos de programación en C, proporcionando herramientas básicas y eficientes.

## Funciones Implementadas

Haz clic en cada función para ver su descripción detallada y mi explicación personal de cómo la implementé.

### Verificación de Caracteres
- [`ft_isalnum`](./docs/functions/ft_isalnum.md): Comprueba si el carácter es alfanumérico.
- [`ft_isalpha`](./docs/functions/ft_isalpha.md): Comprueba si el carácter es una letra.
- [`ft_isascii`](./docs/functions/ft_isascii.md): Comprueba si el carácter pertenece al código ASCII.
- [`ft_isdigit`](./docs/functions/ft_isdigit.md): Comprueba si el carácter es un dígito.
- [`ft_isprint`](./docs/functions/ft_isprint.md): Comprueba si el carácter es imprimible.

### Gestión de Memoria
- [`ft_bzero`](./docs/functions/ft_bzero.md): Escribe ceros en una porción de memoria.
- [`ft_calloc`](./docs/functions/ft_calloc.md): Reserva memoria y la inicializa en cero.
- [`ft_memchr`](./docs/functions/ft_memchr.md): Busca un carácter en un bloque de memoria.
- [`ft_memcmp`](./docs/functions/ft_memcmp.md): Compara dos bloques de memoria.
- [`ft_memcpy`](./docs/functions/ft_memcpy.md): Copia un bloque de memoria a otro.
- [`ft_memmove`](./docs/functions/ft_memmove.md): Copia un bloque de memoria manejando solapamientos.
- [`ft_memset`](./docs/functions/ft_memset.md): Llena un bloque de memoria con un valor específico.

### Manipulación de Cadenas (Strings)
- [`ft_atoi`](./docs/functions/ft_atoi.md): Convierte una cadena a un entero.
- [`ft_itoa`](./docs/functions/ft_itoa.md): Convierte un entero a una cadena.
- [`ft_split`](./docs/functions/ft_split.md): Divide una cadena usando un delimitador.
- [`ft_strchr`](./docs/functions/ft_strchr.md): Localiza la primera aparición de un carácter.
- [`ft_strdup`](./docs/functions/ft_strdup.md): Duplica una cadena reservando memoria.
- [`ft_striteri`](./docs/functions/ft_striteri.md): Aplica una función a cada carácter (con índice).
- [`ft_strjoin`](./docs/functions/ft_strjoin.md): Concatena dos cadenas en una nueva.
- [`ft_strlcat`](./docs/functions/ft_strlcat.md): Concatena cadenas de forma segura.
- [`ft_strlcpy`](./docs/functions/ft_strlcpy.md): Copia cadenas de forma segura.
- [`ft_strlen`](./docs/functions/ft_strlen.md): Calcula la longitud de una cadena.
- [`ft_strmapi`](./docs/functions/ft_strmapi.md): Crea una cadena aplicando una función a cada carácter.
- [`ft_strncmp`](./docs/functions/ft_strncmp.md): Compara dos cadenas hasta N caracteres.
- [`ft_strnstr`](./docs/functions/ft_strnstr.md): Localiza una subcadena con límite de longitud.
- [`ft_strrchr`](./docs/functions/ft_strrchr.md): Localiza la última aparición de un carácter.
- [`ft_strtrim`](./docs/functions/ft_strtrim.md): Elimina caracteres específicos del inicio y final.
- [`ft_substr`](./docs/functions/ft_substr.md): Crea una subcadena.
- [`ft_tolower`](./docs/functions/ft_tolower.md): Convierte a minúscula.
- [`ft_toupper`](./docs/functions/ft_toupper.md): Convierte a mayúscula.

### Salida de Datos
- [`ft_putchar_fd`](./docs/functions/ft_putchar_fd.md): Escribe un carácter en un descriptor.
- [`ft_putendl_fd`](./docs/functions/ft_putendl_fd.md): Escribe una cadena con salto de línea.
- [`ft_putnbr_fd`](./docs/functions/ft_putnbr_fd.md): Escribe un número entero.
- [`ft_putstr_fd`](./docs/functions/ft_putstr_fd.md): Escribe una cadena.

### Listas Enlazadas (Bonus)
- [`ft_lstadd_back`](./docs/functions/ft_lstadd_back.md): Añade un nodo al final.
- [`ft_lstadd_front`](./docs/functions/ft_lstadd_front.md): Añade un nodo al principio.
- [`ft_lstclear`](./docs/functions/ft_lstclear.md): Elimina y libera una lista completa.
- [`ft_lstdelone`](./docs/functions/ft_lstdelone.md): Libera la memoria de un solo nodo.
- [`ft_lstiter`](./docs/functions/ft_lstiter.md): Itera y aplica una función a cada contenido.
- [`ft_lstlast`](./docs/functions/ft_lstlast.md): Devuelve el último nodo.
- [`ft_lstmap`](./docs/functions/ft_lstmap.md): Crea una nueva lista mapeando la anterior.
- [`ft_lstnew`](./docs/functions/ft_lstnew.md): Crea un nuevo nodo.
- [`ft_lstsize`](./docs/functions/ft_lstsize.md): Cuenta el número de nodos.

---
Para más detalles sobre cómo usar y compilar la librería, consulta el archivo [user_doc.md](./user_doc.md).
