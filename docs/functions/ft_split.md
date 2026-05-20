# ft_split

## Descripción
Reserva memoria y devuelve un array de nuevas cadenas (terminadas en nulo) obtenidas al dividir la cadena `s` mediante el carácter delimitador `c`. El array debe terminar con un puntero `NULL`.

## Mi Implementación
Esta es una de las funciones más desafiantes de la librería. Mi enfoque se divide en:
1. Contar el número de palabras separadas por el delimitador para saber cuánta memoria reservar para el array de punteros.
2. Recorrer la cadena principal buscando los límites de cada subcadena.
3. Para cada palabra encontrada, reservar memoria dinámicamente y copiar el contenido.
4. Implementar una función de seguridad (`ft_free`) que, en caso de que falle alguna reserva de memoria a mitad del proceso, libere todo lo que se había reservado hasta ese momento para evitar memory leaks.
