# TRABAJOP_IA
# COMMIT: Implementación de normalización de dataset + integración con Mistral AI
#
# Se desarrolló un notebook para realizar el preprocesamiento y análisis inteligente
# de un dataset de ventas mediante IA.
#
# ¿Qué se hizo?
# - Se cargó el archivo CSV permitiendo detectar automáticamente el encoding
#   (UTF-8 o Latin1) para evitar errores de lectura.
# - Se creó una copia de seguridad del dataset original.
# - Se normalizaron los datos:
#     * Conversión de ORDERDATE a formato datetime.
#     * Relleno de valores nulos numéricos usando la mediana.
#     * Limpieza y estandarización del dataset.
# - Se exportó el archivo limpio en formato UTF-8.
# - Se integró una consulta mediante API hacia Mistral AI para permitir preguntas
#   sobre el dataset usando lenguaje natural.
#
# ¿Por qué se utilizó Mistral Small?
# Se eligió el modelo "mistral-small-latest" porque ofrece un buen equilibrio entre:
# - Velocidad de respuesta.
# - Menor consumo de recursos y costos.
# - Buen rendimiento para análisis de datos y generación de respuestas.
# - Capacidad suficiente para interpretar contexto tabular y responder preguntas
#   sobre ventas sin requerir modelos más pesados.
#
# Resultado:
# El notebook permite limpiar datos automáticamente y posteriormente consultarlos
# mediante IA para obtener análisis descriptivos y responder preguntas del usuario.
