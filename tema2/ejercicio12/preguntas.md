# Herencia
1. ¿Qué estilo toma el texto con inherit? ¿Por qué? \
    Toma el estilo heredado del helemento padre, que es el que tiene la clase "parent". El valor inherit activa la herencia incluso de propiedades que no se heredan.

2. ¿Cómo se comporta el texto con initial? ¿Qué significa este valor? \
    Se muestra con los estilos originales del componente p. Cuando se usa el valor initial se mostrarán los estilos.

3. ¿Qué sucede con unset? ¿Es diferente para propiedades heredables y no heredables? \
    En este caso hace que se herede el estilo del componente padre (div). El valor unset funciona diferente en función de si se hereda o no una propiedad:
    - Cuando se hereda una propiedad actúa como inherit (heredando del padre directo).
    - Cuando no se hereda una propiedad actúa como initial (cogiendo valores originales).

4. ¿Cómo actúa revert en comparación con los otros valores? \
    Revert restablece el valor de una propiedad aplicada a un elemento al estilo del padre que esté por encima, si éste no existe cogería los estilos del navegador y si éste no existe coge los estilos originales.
