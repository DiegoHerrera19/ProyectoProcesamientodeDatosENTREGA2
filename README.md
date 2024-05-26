# Proyecto de Análisis de Datos de Nueva York

## Integrantes
- Sofía Galindo
- Anamaria Leguizamón
- Diego Herrera

## Descripción
Este proyecto tiene como objetivo explorar y analizar dos conjuntos de datos proporcionados por el Departamento de Policía de Nueva York (NYPD) y el Departamento de Transporte de Nueva York (NYC DOT). El primer conjunto de datos contiene información sobre arrestos realizados por el NYPD hasta la fecha, mientras que el segundo conjunto de datos proporciona detalles sobre colisiones de vehículos motorizados ocurridas en la ciudad.

## Objetivos
- Realizar un análisis exploratorio de los datos para identificar patrones, tendencias y relaciones entre las diferentes variables.
- Visualizar los datos mediante gráficos y diagramas para facilitar la comprensión de los hallazgos.
- Identificar factores y características relevantes que influyen en la ocurrencia de arrestos y colisiones de vehículos.
- Realizar tareas de limpieza y transformación de datos según sea necesario para garantizar la calidad y consistencia de los conjuntos de datos.

## Normalización de Datos
Se llevó a cabo la normalización utilizando el método **StandardScaler** para evitar que alguna variable numérica tenga mayor peso al momento de construir el modelo. Este proceso asegura que todas las variables numéricas contribuyan de manera equitativa al análisis. No se realizó la normalización de variables categóricas debido al uso de la **Regresión Logística Multinomial**, la cual maneja de manera adecuada las variables categóricas sin necesidad de normalizarlas. Este enfoque garantiza que el modelo sea robusto y preciso, aprovechando las ventajas de la Regresión Logística Multinomial para el tratamiento de variables categóricas.

## Tecnologías Utilizadas
- Python
- PySpark
- Bibliotecas de Python: pandas, matplotlib, seaborn
