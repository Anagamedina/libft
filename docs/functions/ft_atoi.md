# ft_atoi

## Descripción
Convierte el inicio de la cadena de caracteres apuntada por `str` en un valor entero (`int`).

## Mi Implementación
Mi lógica para `ft_atoi` sigue tres pasos principales: 
1. Salto todos los espacios en blanco y caracteres de control iniciales (como tabulaciones o saltos de línea).
2. Compruebo si hay un signo `+` o `-` para determinar si el número final será positivo o negativo.
3. Recorro los dígitos numéricos y voy construyendo el entero multiplicando el resultado acumulado por 10 y sumando el valor del nuevo dígito. 
Es una función fundamental para procesar entradas de texto que representan datos numéricos.
