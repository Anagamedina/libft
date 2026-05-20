# ft_calloc

## Descripción
Reserva memoria para un array de `count` elementos de `size` bytes cada uno y la inicializa a cero.

## Mi Implementación
Para `ft_calloc`, primero calculé el tamaño total necesario multiplicando `count` por `size`. Luego, utilicé `malloc` para reservar esa memoria. Si la reserva tiene éxito, uso mi propia función `ft_bzero` para asegurarme de que toda la memoria reservada esté limpia (llena de ceros) antes de devolver el puntero. Es una alternativa segura a `malloc` cuando necesitamos que los datos empiecen en un estado conocido.
