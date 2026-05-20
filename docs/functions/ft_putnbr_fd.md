# ft_putnbr_fd

## Descripción
Escribe el número entero `n` en el descriptor de archivo dado.

## Mi Implementación
Esta función utiliza recursividad para desglosar el número. Primero manejo el caso crítico de `INT_MIN` (-2147483648), ya que no se puede convertir directamente a positivo sin desbordamiento. Para los demás números negativos, imprimo el signo `-` y trabajo con el valor absoluto. La recursividad me permite imprimir los dígitos en el orden correcto: divido el número por 10 hasta llegar al primer dígito, y luego, al deshacer la recursión, voy imprimiendo el resto de los dígitos usando el operador módulo y sumando `'0'` para obtener el valor ASCII.
