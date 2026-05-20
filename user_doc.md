# Documentación de Usuario - Libft

Esta guía explica cómo compilar la librería y cómo integrarla en tus proyectos de C.

## Compilación

El proyecto incluye un `Makefile` con las reglas estándar para facilitar la compilación.

### Comandos disponibles:

- **Compilar la librería:**
  ```bash
  make
  ```
  Genera el archivo `libft.a` en la raíz del proyecto.

- **Compilar incluyendo las funciones de bonus (listas):**
  ```bash
  make bonus
  ```

- **Limpiar archivos objeto (.o):**
  ```bash
  make clean
  ```

- **Limpiar todo (objetos y librería .a):**
  ```bash
  make fclean
  ```

- **Recompilar desde cero:**
  ```bash
  make re
  ```

## Cómo usar la librería en tu proyecto

Para utilizar las funciones de `libft` en tu propio programa, sigue estos pasos:

1. **Incluir la cabecera:**
   Añade la siguiente línea al principio de tus archivos fuente `.c`:
   ```c
   #include "libft.h"
   ```

2. **Compilar tu programa enlazando la librería:**
   Al compilar tu proyecto, debes indicar la ruta del archivo `libft.a`. Por ejemplo:
   ```bash
   gcc main.c -L. -lft -o mi_programa
   ```
   *(Nota: `-L.` indica que busque librerías en el directorio actual, y `-lft` busca el archivo `libft.a`)*.

## Ejemplo de uso

Aquí tienes un ejemplo rápido usando `ft_strlen` y `ft_putstr_fd`:

```c
#include "libft.h"

int main(void)
{
    char *str = "Hola, mundo!";
    int len = ft_strlen(str);

    ft_putstr_fd("La longitud de '", 1);
    ft_putstr_fd(str, 1);
    ft_putstr_fd("' es: ", 1);
    ft_putnbr_fd(len, 1);
    ft_putchar_fd('\n', 1);
    return (0);
}
```
