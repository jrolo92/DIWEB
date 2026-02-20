# Proyecto: CUERO & ALMA

Este proyecto implementa una plataforma de e-commerce de marroquinería utilizando una arquitectura de estilos moderna, modular y escalable basada en **SASS**.

## 1. Integrantes del Grupo
* **Jaime Gómez Mesa**
* **Yoël Gómez Benítez**
* **Javier Rodríguez López**

---

## 2. Estructura del Proyecto

```text
/
├── css/                # Archivos CSS compilados
│   └── main.css        # Archivo CSS principal compilado
├── docs/               # Documentación adicional
├── images/             # Activos visuales (logos, productos)
├── scss/               # Código fuente de estilos
│   ├── base/           # Configuraciones globales (_colores, _tipografia)
│   ├── components/     # Elementos reutilizables (_buttons, _cards, _forms)
│   ├── layout/         # Estructuras fijas (_header, _footer, _grid)
│   ├── _carrito.scss   # Estilos específicos de la página de carrito
│   ├── _catalogo.scss  # Estilos específicos de la página de catálogo
│   ├── _index.scss     # Estilos específicos de la home
│   └── main.scss       # Archivo maestro de importación
├── carrito.html        # Vista del carrito
├── catalogo.html       # Vista del catálogo de productos
├── index.html          # Vista principal
└── README.md           # Documentación del proyecto
```

## 3. Qué se ha refactorizado respecto al CSS original
Hemos generado este proyecto directamente usando SASS, lo cual nos ha permitido el uso de variables y de código dividido en módulos que se usa en distintas partes del proyecto
gracias a los partials, los cuales se compilan en conjunto en un archivo css principal.


## 4. Qué ventajas aporta SASS al proyecto
El uso de Sass ha dotado al proyecto de herramientas de desarrollo profesional:

- Escalabilidad: Gracias a la estructura de carpetas, el proyecto puede crecer con nuevos productos y secciones sin que el código de estilos se vuelva dificil de manejar.

- Mantenibilidad Global: Cambiar la paleta de colores de toda la web se hace desde un solo archivo (_colores.scss), eliminando el riesgo de dejar elementos sin actualizar.

- Reutilización de Código: Al separar los botones y componentes, evitamos duplicar reglas CSS, lo que resulta en un archivo final más ligero y optimizado.

- Flujo de Trabajo Eficiente: El uso de archivos parciales (_) permite una navegación rápida por el proyecto y una mejor organización mental de la interfaz.


## 5. Mejoras
- En el carrusel poner título de sección de tendencias.
