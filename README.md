# New York Air Quality

- Se reliza un ETL en el que que puede notar que no existen valores faltantes, se analizan la cantidad de filas y columnas, dejando ver que es u dataset prolijo y son mucho por normalizar. 
Se cambia el tipo de dato de la variable 'Start_Date' de object a Datetime para una mejor utilización de datos posterior en etapa de visualización con Power BI.

- En el EDA se visualiza gráficamnete que no existen valores nulos

## TERMINOLOGÍA UTILIZADA: 
términos geográficos:

UHF42: Se refiere a los barrios de la ciudad de Nueva York según la clasificación del United Hospital Fund (UHF). Hay 42 barrios en total, cada uno con características demográficas y geográficas similares.

UHF34: Similar a UHF42, pero con 34 barrios. Estos barrios también se utilizan para la recopilación y análisis de datos de salud y demografía en Nueva York2.

Borough: En el contexto de Nueva York, un borough es una de las cinco divisiones administrativas principales de la ciudad: Manhattan, Brooklyn, Queens, el Bronx y Staten Island. Cada borough es coextensivo con un condado del estado de Nueva York3.

CD: Puede referirse a distritos censales o distritos electorales, que son divisiones geográficas utilizadas para la administración y la representación política.

Citywide: Significa ciudadanía o metropolitana. Se refiere a todo el área de la ciudad, en lugar de una subdivisión específica.

BORRADOR ACERCA DE POSIBLES OBJETIVOS DEL ANÁLISIS:

- Análisis de tendencias temporales:

Objetivo: Determinar cómo ha cambiado la calidad del aire en diferentes períodos (mensuales, anuales, estacionales) en Nueva York.

Ejemplo: ¿Ha mejorado la calidad del aire en verano durante los últimos cinco años?

- Análisis geoespacial:

Objetivo: Comparar la calidad del aire entre diferentes barrios, distritos o áreas de Nueva York.

Ejemplo: ¿Qué áreas de Nueva York tienen la peor calidad del aire y por qué?

- Análisis de correlación:

Objetivo: Identificar correlaciones entre diferentes variables del dataset, como la relación entre la densidad de emisiones y la categoría de calidad del aire.

Ejemplo: ¿Existe una correlación entre el aumento de emisiones y la disminución de la calidad del aire en ciertas zonas?

- Detección de anomalías:

Objetivo: Identificar valores atípicos o anomalías en los datos que podrían indicar eventos inusuales de contaminación.

Ejemplo: ¿Hubo algún evento anómalo de contaminación en un día específico que sobresalga en los datos?

- Evaluación de políticas ambientales:

Objetivo: Evaluar el impacto de diferentes políticas ambientales en la calidad del aire.

Ejemplo: ¿Qué impacto han tenido las políticas de reducción de emisiones en la calidad del aire en los últimos diez años?

- Predicción de la calidad del aire:

Objetivo: Utilizar modelos predictivos para predecir la calidad del aire en el futuro.

Ejemplo: ¿Podemos predecir la calidad del aire para el próximo año utilizando datos históricos y modelos de regresión?

#### Ejemplo de enfoque
Supongamos que decides realizar un análisis de tendencias temporales:

Carga y limpieza de datos:

Asegúrate de que tus datos estén limpios y en el formato correcto.

Análisis exploratorio de datos:

Realiza gráficos de series temporales para visualizar las tendencias de calidad del aire a lo largo del tiempo.

Estadísticas descriptivas:

Calcula estadísticas como la media, mediana, y desviación estándar de las mediciones de calidad del aire.

Visualizaciones:

Usa gráficos de línea para mostrar cómo la calidad del aire ha cambiado en diferentes períodos.

Interpretación y conclusiones:

Interpreta los resultados y saca conclusiones basadas en tus hallazgos. ¿Hubo una mejora notable? ¿Hay patrones estacionales?