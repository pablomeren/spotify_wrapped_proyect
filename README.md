# Spotify Wrapped Project (Análisis Completo con Python)

Análisis completo de mis hábitos de escucha a lo largo de los años en Spotify.

El objetivo del proyecto es recrear un Spotify Wrapped propio, tanto de todos los años combinados como un Wrapped específico del año 2025, con métricas, rankings y visualizaciones avanzadas.

Los datos originales proceden del paquete *Extended Streaming History* proporcionado por Spotify.

> **Nota:** Por motivos de privacidad, los archivos JSON originales NO están incluidos en este repositorio.

## Objetivo del proyecto

Crear una versión extendida y personalizada del Spotify Wrapped oficial, con:

* Mayor nivel de detalle.
* Más visualizaciones.
* Análisis reproducible en cualquier rango temporal.
* Wrapped global (todos los años) y Wrapped 2025.

## Contenido del proyecto

### Procesado del historial de reproducción

1. **Carga y concatenación** de todos los archivos JSON del *Extended Streaming History*.
2. **Conversión** de milisegundos a minutos escuchados.
3. **Limpieza básica del dataset:**
    * Eliminación de duplicados exactos.
    * Gestión de valores faltantes.

### ALL-TIME WRAPPED (todos los años)

Este análisis incluye:

* Top 10 canciones más escuchadas.
* Top 10 artistas más escuchados.
* Top 10 álbumes más escuchados.
* Evolución de minutos escuchados por año.
* Día con más minutos escuchados de cada año.
* Minutos escuchados por horas del día.

### WRAPPED 2025

Análisis específico del año 2025:

* **Rankings:**
    * Top 10 canciones de 2025.
    * Top 10 artistas de 2025.
    * Top 10 álbumes de 2025.
* **Gráficas incluidas:**
    * Minutos escuchados por mes.
    * Minutos escuchados por horas del día.
    * Día del año con mayor tiempo de escucha.

## Tecnologías utilizadas

* `Python 3`
* `pandas`
* `matplotlib`
* `json`
*  `glob`
* `Jupyter Notebook`

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE). Eres libre de usar, modificar y compartir el código, siempre que se respete la atribución del autor original.
