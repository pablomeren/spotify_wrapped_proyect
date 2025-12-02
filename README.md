# Spotify Wrapped Project (Análisis Completo con Python)
Análisis completo de mis hábitos de escucha a lo largo de los años en Spotify. El objetivo del proyecto es recrear un Spotify Wrapped propio, tanto de todos los años combinados como un Wrapped específico del año 2025, con métricas, rankings y visualizaciones avanzadas.
Los datos originales proceden del paquete Extended Streaming History proporcionado por Spotify.
*Por motivos de privacidad, los archivos JSON originales NO están incluidos en este repositorio.

OBJETIVO DEL PROYECTO
Crear una versión extendida y personalizada del Spotify Wrapped oficial, con más detalle, más visualizaciones y la posibilidad de analizar cualquier rango temporal, especialmente:
- Wrapped global (todos los años)
- Wrapped 2025 completo


CONTENIDO

Este proyecto incluye:

- Procesado del historial de reproducción

Carga y concatenación de todos los archivos JSON del "Extended Streaming History".
Conversión de milisegundos a minutos escuchados.
Limpieza básica de datos:
  Eliminación de duplicados exactos.
  Gestión de valores faltantes.
  Conversión correcta de fechas y creación de columnas derivadas (año, hora, día, fecha…).

- Análisis tipo Wrapped (todos los años combinados)

Top 10 canciones más escuchadas.
Top 10 artistas más escuchados.
Top 10 álbumes más escuchados.
Evolución de minutos escuchados por año.
Día con más minutos escuchados de cada año.
Horas del día donde más escucho música.

- Wrapped exclusivo de 2025

Top 10 canciones de 2025.
Top 10 artistas de 2025.
Top 10 álbumes de 2025.
Gráficas específicas del año:
  Minutos por mes.
  Minutos por hora del día.

- Tecnologías utilizadas

Python 
pandas 
matplotlib 
json
Jupyter Notebook
