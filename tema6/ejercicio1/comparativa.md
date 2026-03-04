# Ejercicio: Formatos de Audio y Web Media

## 1. Comparativa de Formatos de Audio

A continuación, se presenta una tabla detallada con los formatos más utilizados en la industria actual, ordenados por su aplicación técnica.

| Formato | Siglas / Significado | Desarrollador | Tipo de Compresión | Peculiaridades |
| :--- | :--- | :--- | :--- | :--- |
| **WAV** | Waveform Audio File Format | Microsoft & IBM | Sin compresión (LPCM) | Estándar de la industria para edición profesional. Archivos muy pesados. |
| **MP3** | MPEG-1 Audio Layer III | Fraunhofer IIS | Con pérdida | El formato más universal. Revolucionó el consumo digital de música. |
| **AAC** | Advanced Audio Coding | Apple / Dolby / Otros | Con pérdida | Sucesor del MP3. Más eficiente y con mejor calidad a bitrates bajos. |
| **FLAC** | Free Lossless Audio Codec | Xiph.Org | Sin pérdida | Comprime el tamaño del archivo original al 50-60% sin perder calidad. |
| **ALAC** | Apple Lossless Audio Codec | Apple | Sin pérdida | Similar al FLAC, pero optimizado para el ecosistema Apple (iTunes/Music). |
| **OGG (Vorbis)** | Ogg Vorbis | Xiph.Org | Con pérdida | Formato libre de patentes. Muy usado en videojuegos y Spotify. |
| **OPUS** | Opus | IETF / Xiph.Org | Con pérdida | El formato más moderno. Ideal para streaming por su bajísima latencia. |

--- 

* **¿Cuál tiene mejor relación calidad/peso?**
    **OPUS**. Es el más eficiente actualmente, superando a AAC y MP3 incluso en bitrates extremadamente bajos (como 64 kbps), donde otros formatos empiezan a distorsionar.

* **¿Cuál usaríamos para una web de una emisora de radio?**
    **AAC+ (HE-AAC)** o **OPUS**. Ambos están diseñados para streaming constante, permitiendo una escucha fluida incluso con conexiones móviles limitadas.

* **¿Y para una web de venta de música?**
    Se deben ofrecer dos opciones: **FLAC** para los usuarios que buscan calidad de estudio (Audiófilos) y **AAC/MP3** (256-320 kbps) para descarga rápida y compatibilidad con dispositivos móviles.

---

## 2. Proceso de Optimización: De WAV a MP3

Para reducir el tamaño de un archivo `.wav` a `.mp3` afectando lo menos posible a la calidad hay que modificar los siguientes parámetros:

1.  **Bitrate Variable (VBR):** En lugar de un bitrate constante (CBR), se usa VBR. Esto permite que el codificador asigne más datos a partes complejas (como un solo de guitarra) y menos datos a partes simples (silencios), ahorrando peso total.
2.  **Frecuencia de Muestreo:** Mantener **44.1 kHz** (estándar CD) para evitar el "aliasing" o pérdida de brillo.
3.  **Filtrado:** Aplicar un filtro de corte en los 16-18 kHz. La mayoría de los adultos no perciben frecuencias superiores, y eliminar esa información reduce drásticamente el peso del archivo final.

---
