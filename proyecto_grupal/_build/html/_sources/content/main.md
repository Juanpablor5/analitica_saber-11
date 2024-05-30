# Resumen

En el siguiente trabajo para la materia de Big Data, se realizará un análisis de datos utilizando la base de datos pública de las pruebas Saber 11, obtenida del portal Datos Abiertos de Colombia. El objetivo principal es explorar las relaciones entre las diversas variables contenidas en esta base de datos y el puntaje global de las pruebas. Para ello, se llevó a cabo un proceso de ETL (Extracción, Transformación y Carga), donde los datos fueron subidos a AWS utilizando PostgreSQL, DBeaver y Prefect.

Además, se realizó una exploración y visualización exhaustiva de los datos utilizando Power BI, lo que permitió identificar patrones y tendencias a través de gráficos interactivos y paneles de control. Posteriormente, se realizó un ejercicio de regresión lineal multivariable para aplicar técnicas de machine learning, con el fin de inferir resultados de puntajes globales teniendo en cuenta las variables que se consideraron relevantes.

## Contenido

- [Introducción](introduccion.md)
- [Objetivos](objetivos.md)
- [Creación de la base de datos en AWS](bd_aws.md)
- [Exploración de datos](exploracion_datos.ipynb)
- [Proceso ETL de la base de datos](etl.md)
  - [Flujo del proceso ETL](etl/etl_analitica.ipynb)
  - [Análisis de flujo de trabajo con Prefect](etl/prefect.md)
- [Machine Learning, predicción del puntaje global](flujo_ml.ipynb)
- [Visualización de datos](visualizacion.md)
- [Conclusiones](conclusiones.md)
