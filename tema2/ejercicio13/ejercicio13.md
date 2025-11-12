# Herencia, especificidad y cascada

1. ¿Qué sucede si cambias el orden de las reglas CSS?\
Siempre que las reglas CSS tengan la misma especificidad se va a aplicar la última regla que aparezca en el archivo CSS, es decir, la que esté mas abajo.

2. ¿Cómo afecta la especificidad a los estilos aplicados en el párrafo #override?\
Los estilos definidos con un ID tienen más peso que los estilos aplicados mediante clases o elementos directos. Por eso se acaba mostrando los estilos de #override.

3. ¿Qué sucede si eliminas el !important de alguna regla?\
Lo que ocurre es que si tiene algun estilo que lo pueda sobrescribir lo hará y no se mostrará el estilo que quereemos que se muestre.

4. ¿Qué reglas son heredadas automáticamente y cuáles necesitas especificar explícitamente?\
Las propiedades relacionadas con texto y tipografía como color y font-family son heredadas automáticamente. En cambio, las propiedades de caja, posición y visualización como background-color, font-weight, margin, padding, width o height no se heredan por defecto, por lo que si se quieren modificar habrá que especificarlo.