# Tarea extra - segunda aplicación

Esta carpeta está preconfigurada para usar el PDF de lineamientos adjunto como documento de interés. El archivo está en `data/actividad2_lineamientos.pdf`.

- Base de datos: `pdf_embeddings_db`
- Colección exclusiva: `actividad2_vectors`
- Índice exclusivo: `actividad2_vector_index`
- Aplicación: `app.py`
- Casos de prueba: `casos_prueba.csv` y `casos_prueba.json`

Ejecuta desde esta carpeta: `python ingest.py data/actividad2_lineamientos.pdf`. Después confirma que el índice esté en estado `READY` y despliega esta carpeta como un segundo repositorio / segunda app de Streamlit. Configura sus propios secretos en los ajustes de esa segunda app.

Las respuestas esperadas de los casos son una referencia de evaluación basada en el contenido del PDF. Los fragmentos recuperados y scores reales deben completarse después de ejecutar la app; no se han simulado.
