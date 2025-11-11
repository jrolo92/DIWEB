# Especificidad

1. ¿Qué color se aplica finalmente al encabezado h1? Explica cuál fue la regla ganadora y por qué: \
Finalmente se acaba aplicando los estilos en línea debido a que esa forma de aplicar estilos prevalece sobre las hojas de estilo externas. Solo los estilos marcados con !important serían mas prioritarios que los estilos en línea, pero no es el caso.

2. ¿Cuál es el color del párrafo con el ID parrafo? ¿Qué regla prevalece?  \
El párrafo con el id="parrafo" aparece del color que le hemos dado en la hoja de estilos externa (aguamarina). Aquí prevalece la ley de la especificidad, según la cual tendrá prioridad el estilo del ID sobre el del elemento p.

3. ¿Qué color tiene el párrafo con la clase texto dentro del div contenedor? Explica por qué se aplica ese color en particular: \
Este párrafo tiene el color asignado en la hoja de estilos externa en el apartado de clase "texto", que en mi caso es azul. Se aplica este color debido a que lo hemos marcado como !important y ésto tiene mas preferencia que el estilo del elemento p.

