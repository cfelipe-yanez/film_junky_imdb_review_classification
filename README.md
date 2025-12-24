# film_junky_imdb_review_classification
Este es el repositorio en el que se creará todo para el proyecto del sprint 17 del curso de Triple Ten 
# Film Junky IMDB Review Classification

## Descripción del proyecto
Film Junky Union, una comunidad para aficionados de películas clásicas, está desarrollando un sistema para filtrar y categorizar reseñas de películas. Este proyecto tiene como objetivo entrenar un modelo de clasificación que detecte automáticamente las críticas negativas de IMDB.

El modelo deberá alcanzar un valor F1 de al menos 0.85.

## Instrucciones del proyecto
1. Carga los datos desde `imdb_reviews.tsv`.
2. Realiza análisis exploratorio de datos y revisa el balance de clases.
3. Preprocesa los datos según sea necesario para el modelado.
4. Entrena al menos tres modelos diferentes (por ejemplo, regresión logística, árbol de decisión, boosting).
5. Evalúa los modelos con el conjunto de prueba.
6. Escribe reseñas de prueba y clasifícalas con los modelos entrenados.
7. Analiza y documenta las diferencias de rendimiento entre los modelos.
8. Presenta tus hallazgos y conclusiones.

**Nota:** BERT se puede utilizar localmente en muestras pequeñas, pero no es obligatorio.

## Descripción de los datos
- `imdb_reviews.tsv`: conjunto de datos de reseñas de IMDB.
- Columnas principales:
  - `review`: texto de la reseña
  - `pos`: objetivo (0 = negativo, 1 = positivo)
  - `ds_part`: indica si es parte del entrenamiento o prueba (`entrenamiento`/`prueba`)

## Dependencias
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib / seaborn (opcional para visualización)
- transformers (opcional, solo si se usa BERT)

## Objetivo
Construir un modelo que permita detectar automáticamente reseñas negativas con alta precisión y F1 ≥ 0.85.
