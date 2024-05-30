# Análisis de flujo de trabajo con Prefect

A continuación se muestra el mapa del flujo de trabajo que fue registrado en Prefect. Este mapa muestra las tareas que se ejecutaron en el proceso ETL de la base de datos de la prueba Saber 11, así como las dependencias entre ellas.

![Flujo de trabajo Prefect](../../assets/prefect.png)

Realizando el análisis del flujo, este se completó exitosamente en aproximadamente 35 segundos, con 9 tareas en total. Comienza con la conexión a la base de datos, seguido de la limpieza de datos y el cálculo de promedios, los cuales se cargan en tablas analíticas. Al final, se realiza una conexión adicional a la base de datos. La limpieza de datos y la carga de tablas destacan como los procesos más críticos en términos de tiempo, sugiriendo áreas para optimizaciones futuras. El análisis proporcionado por Prefect indica que estos pasos fueron los más demorados. En particular, se sugiere mejorar la eficiencia de la carga de datos mediante una estrategia de carga masiva en lugar de fila por fila.
