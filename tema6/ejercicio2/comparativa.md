# Comparativa de Formatos de Vídeo

Esta tabla detalla los contenedores y formatos de vídeo más relevantes, su origen y su aplicación en la industria actual.

| Formato | Siglas / Significado | Desarrollador | Compresión | Uso principal | Peculiaridades |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **MP4** | MPEG-4 Part 14 | ISO/IEC | Con pérdida | Estándar universal (Web, Móviles, TV). | El formato más compatible del mundo. Soporta streaming e interactividad. |
| **WebM** | Web Media | Google | Con pérdida | Vídeo de alta calidad para HTML5. | Basado en el contenedor Matroska. Diseñado específicamente para la web y es libre de regalías. |
| **MOV** | QuickTime Movie | Apple | Con pérdida / Sin pérdida | Edición profesional y entorno Apple. | Permite separar pistas de audio, vídeo y texto en archivos independientes. |
| **AVI** | Audio Video Interleave | Microsoft | Con pérdida | Archivos antiguos de PC, almacenamiento local. | Muy compatible pero no permite streaming fluido. No soporta menús ni subtítulos modernos. |
| **WMV** | Windows Media Video | Microsoft | Con pérdida | Streaming antiguo y ecosistema Windows. | Optimizado para el reproductor Windows Media. Fue muy popular en la era pre-YouTube. |
| **OGG (Theora)** | Ogg Project | Xiph.Org | Con pérdida | Software libre y plataformas abiertas. | Formato totalmente gratuito y abierto. Menos eficiente que MP4 o WebM. |
| **Flash Video** | FLV / F4V | Adobe (antes Macromedia) | Con pérdida | Antiguo estándar de vídeo web (YouTube original). | Requiere el plugin Flash Player. Actualmente está obsoleto y no se recomienda su uso. |
| **Real Video** | RV | RealNetworks | Con pérdida | Streaming pionero en los años 90. | Fue el primer formato popular de streaming por Internet, pero hoy es una reliquia técnica. |

---

## Análisis de Compresión y Calidad

Es importante entender que la mayoría de estos formatos son **contenedores**. Esto significa que dentro de un `.mp4` o un `.mov` puede haber diferentes "motores" (códecs) encargados de la compresión:

1.  **Con pérdida (Lossy):** Casi todos los formatos web (MP4, WebM, OGG) eliminan información visual imperceptible para reducir el peso. Es la norma para el streaming.
2.  **Sin pérdida (Lossless):** Se usa principalmente en entornos de postproducción profesional (como ciertos perfiles de MOV o AVI) para no degradar la imagen al editarla repetidamente.
3.  **Sin compresión:** Prácticamente no se usa fuera del rodaje de cine de altísimo nivel debido a que un solo minuto de vídeo podría ocupar decenas de gigabytes.

### ¿Cuál elegir hoy en día?
* **Para Web:** Sin duda **MP4** por compatibilidad total, o **WebM** si buscas optimizar al máximo el rendimiento en navegadores modernos.
* **Para Edición:** **MOV** ya que mantiene una fidelidad de color excelente.
* **Para Archivo Histórico:** **AVI**, aunque está siendo reemplazado por **MKV** por su capacidad de guardar múltiples pistas de audio y subtítulos.