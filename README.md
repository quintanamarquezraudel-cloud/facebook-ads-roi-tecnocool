📊 Análisis TecnoCool - Optimización de Campañas en Facebook Ads

🎯 Objetivo del Proyecto
El objetivo de este proyecto es analizar los datos históricos de campañas publicitarias de TecnoCool en Facebook Ads para identificar qué segmentos de audiencia (edad, género) generan mejor ROI.
El análisis busca optimizar el presupuesto publicitario y mejorar la efectividad de las campañas.

📁 Conjuntos de Datos Utilizados
El proyecto trabaja con un dataset principal:

tecnocool.csv → Información de campañas en Facebook Ads:

ID de anuncio y campaña

Fechas de inicio y fin

Segmentación (edad, género)

Métricas de desempeño (impresiones, clics, gasto, conversiones totales y aprobadas)

🔄 Etapas del Análisis
Carga y Exploración de Datos

Importación de librerías (pandas, numpy, matplotlib, seaborn).

Carga del dataset tecnocool.csv.

Exploración inicial de estructura y tipos de datos.

Identificación de Problemas de Calidad

Columnas de fechas en formato texto (object).

Filas con valores en cero en clicks y approved_conversion (se mantienen como NaN para evitar distorsión).

Valores nulos en total_conversion y approved_conversion.

Preprocesamiento de Datos

Detección de corrimiento de columnas a partir de la fila 761.

División del dataset en dos partes (tecnocool1 y tecnocool2).

Renombrado y ajuste de tipos de datos en tecnocool2.

Unión en un dataframe corregido (tecnocoolcorregido).

Análisis Estadístico y Visualización

Resumen estadístico de métricas clave: impresiones, clics, gasto, conversiones.

Histogramas y boxplots para identificar valores extremos.

Segmentación de Audiencias

Por Edad: 30–34, 35–39, 40–44, 45–49.

Por Género: Masculino (M), Femenino (F).

Insights Ejecutivos

Se detectó un corrimiento de columnas en parte del dataset, corregido en el preprocesamiento.

Los segmentos con mejor desempeño se concentran en edades 30–34 y 35–39, principalmente en género Masculino.

Se recomienda enfocar la inversión en estos segmentos y reforzar la calidad de datos para evitar sesgos.

🚀 Cómo Ejecutar el Proyecto
Opción 1: Google Colab (Recomendado)
Abrir el cuaderno en Google Colab.

Asegurarse de tener el archivo tecnocool.csv en la carpeta /datasets/.

Ejecutar las celdas en orden.

Opción 2: Entorno Local
Clonar este repositorio.

Instalar dependencias:

bash
pip install pandas numpy matplotlib seaborn
Colocar el dataset en /datasets/.

Ejecutar el notebook en Jupyter.

📋 Requisitos
pandas >= 1.3.0

numpy >= 1.20.0

matplotlib >= 3.0.0

seaborn >= 0.11.0
