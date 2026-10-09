# Análisis de Rendimiento y ROI de Campañas en Facebook Ads

🎯 Objetivo del Proyecto: TecnoCool es una tienda tecnológica que invierte en campañas de Facebook Ads segmentadas por edad, género e intereses, pero no sabe qué combinación de audiencia le da mejor retorno. Como analista de datos, se me pidió analizar los datos históricos de campañas para identificar qué segmentos generan mejor ROI y así optimizar el presupuesto publicitario.

📁 Conjuntos de datos utilizados:
- tecnocool.csv → Contiene información de campañas publicitarias segmentadas por edad, género e intereses, incluyendo métricas de clics, conversiones e inversión.

🔄 Etapas del Análisis

### 1. Carga y exploración inicial de datos
- Importación de librerías necesarias (pandas, seaborn, matplotlib)
- Carga del dataset y revisión de las primeras filas (.head())
- Exploración de tipos de datos y estadísticas descriptivas (.info() y .describe())
  
### 2. Limpieza y preprocesamiento de datos
- Corrección de columnas desalineadas en el dataset
- Unificación de tipos de dato
- Conversión de fechas y categorías
- Verificación de duplicados y valores nulos/negativos
