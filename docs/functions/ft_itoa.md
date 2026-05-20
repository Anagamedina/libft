# ft_itoa

## Descripción
Convierte el número entero `n` en una cadena de caracteres terminada en nulo. Maneja correctamente números negativos.

## Mi Implementación
Para `ft_itoa`, primero manejo el caso especial del número 0. Luego, calculo la longitud necesaria para la cadena (incluyendo el signo negativo si existe) mediante una función auxiliar. Reservo la memoria exacta con `malloc` y voy rellenando la cadena de derecha a izquierda. Utilizo el operador módulo para extraer el último dígito y luego divido el número por 10 para pasar al siguiente. Al final, si el número original era negativo, añado el signo `-` en la primera posición y cierro la cadena con el carácter nulo.
