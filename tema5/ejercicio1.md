# Guía de Análisis de Sitios Web

### Autor: Javier Rodríguez López 

He escogido la [web de adidas](https://www.adidas.es/)

### Diseño y Composición
* **Imagen principal:** Nada mas entrar en la web se puede ver una imágen de tipo "hero section" que ocupa toda la pantalla con los productos mas vendidos.
* **Punto focal:** La atención se dirige inmediatamente al producto del centro de la imagen, que además tiene un tamaño ligeramente mayor que los demás.
* **Peso visual:** Usa tres imágenes grandes con espacios entre ellas y a la izquierda una tipografía gruesa con un botón para acceder a la sección.
* **Balance compositivo:** Está muy equilibrado y se podría decir que es casi simétrico.

### Gestión de Imágenes
* **Función de cada imagen:** Principalmente muestran los productos en detalle y desde un punto de vista que resulta muy atractivo.
* **Valor vs. Decorativa:** La mayoría aporta información real sobre el producto, por ejemplo las imágenes en 360º. Por otro lado hay algunas imágenes de secciones que si pueden ser mas decorativas
* **Texto alternativo:** Se usan atributos alt en todas las imágenes con una descripción bastante objetiva de lo que se muestra en la imagen.
* **Accesibilidad:** Usan elementos que son accesibles a simple vista, como por ejemplo botones con un alto contraste y tamaños de fuente adecuado.

### Rendimiento y SEO
* **Impacto en rendimiento:** Al tener imágenes grandes y de alta resolución se podría decir que el impacto es alto. Por lo que he podido ver en el inspector las imágenes (al menos en la portada) son en formato jpg, por lo que son pesadas.
* **Comparativa:** 
1. Una web con impacto **negativo** en carga: cnn.com
2. Una web con carga **ultra rápida**: wikipedia.org
* **Elementos SEO:** Las imágenes tienen nombres relevantes. Pero en principio parece una wed de rendimiento medio.

### Experiencia e Identidad
* **Identidad de marca:** Se refleja con las 3 bandas tipicas de la marca, mostrando productos que son muy típicos y mostrando deportistas en algunas imágenes o colecciones.
* **UX (User Experience):** Las imágenes de alta calidad hacen que se pueda ver la textura de la tela y los detalles de los productos. La navegación es muy intuitiva, se ven bien los botones y enlaces.

---

## Búsqueda de Referencias
Busca una web que cumpla con:
1. **Memoria semántica:** Amazon: Se centra en mostrar productos en cuadrículas y las características de ellos.
2. **Memoria episódica:** Unicef: Es un tipo de web que fomenta las imágenes de tipo "storytelling" para que se asocie la marca a una emoción o vivencia.

---

## Investigación Técnica
* **Core Web Vitals:** 
Son tres métricas de Google que miden la salud de una web:

1. LCP (Largest Contentful Paint): Tiempo de carga de la imagen más grande. (Objetivo: < 2.5s).
2. INP (Interaction to Next Paint): Qué tan rápido responde la web al hacer clic. (Objetivo: < 200ms).
3. CLS (Cumulative Layout Shift): Que los elementos no se "muevan" solos mientras carga la página. (Objetivo: < 0.1).
* **Aplicación:** Cómo implementar estas métricas en tu propia Web.

1. Comprimir todas las imágenes antes de subirlas (TinyPNG o similares).
2. Usar un sistema de caché para que los elementos no se recarguen cada vez.
3. Reservar espacio para las imágenes en el código (CSS) para evitar que el texto "salte" (mejorar el CLS).