# Análisis de Inmuebles en CDMX usando Pandas y Google Colab

Este repositorio contiene un ejercicio práctico de análisis y manipulación de datos de inmuebles en la Ciudad de México, utilizando la biblioteca Pandas en Python dentro de Google Colab.

## Descripción General

El archivo principal de este ejercicio es `inmuebles_cdmx.ipynb`, desarrollado y ejecutado en Google Colab. A lo largo del notebook se explora una base de datos pública de alquileres de inmuebles, abordando desde la carga y exploración inicial de los datos hasta la preparación para Machine Learning y la generación de reportes personalizados.

### Principales pasos realizados:

#### 1. Importación y exploración inicial de datos
- Carga del dataset desde un enlace público usando Pandas.
- Exploración básica: primeras y últimas filas, muestras aleatorias, dimensiones y nombres de columnas, tipos de datos y valores nulos.

#### 2. Análisis exploratorio
- Cálculo de promedios de alquiler por tipo de propiedad.
- Visualización de la distribución de valores y tipos de inmuebles.
- Filtrado de inmuebles residenciales y comerciales.
- Análisis del porcentaje de cada tipo de inmueble en la base de datos.

#### 3. Limpieza y filtrado
- Tratamiento de valores nulos y registros inconsistentes.
- Eliminación de filas con valores inválidos en las columnas clave.
- Aplicación de filtros para seleccionar propiedades con características específicas (número de habitaciones, valor de alquiler, superficie, etc.).

#### 4. Generación y guardado de archivos
- Exportación de subconjuntos de datos filtrados a archivos CSV, tanto en el entorno local como en Google Drive.

#### 5. Creación de nuevas columnas
- Cálculo de columnas numéricas como el gasto mensual y anual por inmueble.
- Generación de columnas categóricas descriptivas y de indicadores (“Tiene_suite”).

#### 6. Uso de Google Colab
- Todo el flujo de trabajo se realizó en Google Colab, aprovechando su integración con Google Drive para guardar archivos y su entorno interactivo para visualizaciones y análisis rápidos.

## Requisitos

- Python 3.x
- pandas (versión reciente)
- Google Colab (recomendado para reproducir el flujo de trabajo)
- Acceso a Google Drive (opcional, para guardar archivos generados)

## ¿Cómo usar este repositorio?

1. Abre el archivo `inmuebles_cdmx.ipynb` en Google Colab.
2. Ejecuta las celdas de código siguiendo el flujo del análisis.
3. Personaliza los filtros o visualizaciones de acuerdo con tus necesidades.
4. Los archivos de resultados pueden guardarse en tu Google Drive o descargarse localmente.

## Estructura del archivo principal

- Importación de librerías y datos
- Exploración y limpieza de datos
- Análisis exploratorio y visualización
- Creación de nuevas variables
- Exportación de resultados

## Licencia

Este proyecto es de uso educativo y está bajo la licencia MIT.

---
