# Explorando en busca de respuestas

[Esta es una continuación de la tarea ](https://github.com/microsoft/Data-Science-For-Beginners/blob/main/4-Data-Science-Lifecycle/14-Introduction/assignment.md)de la lección anterior , donde echamos un vistazo breve al conjunto de datos. Ahora echaremos un vistazo más profundo a los datos.

Nuevamente, la pregunta que el cliente quiere saber: ¿ Los pasajeros de los taxis amarillos en la ciudad de Nueva York dan más propina a los conductores en invierno o en verano?

Su equipo se encuentra en la etapa [de Análisis](https://github.com/microsoft/Data-Science-For-Beginners/blob/main/4-Data-Science-Lifecycle/15-analyzing/README.md)del ciclo de vida de la ciencia de datos, donde usted es responsable de realizar un análisis de datos exploratorio en el conjunto de datos. Se le ha proporcionado un cuaderno y un conjunto de datos que contiene 200 transacciones de taxi de enero y julio de 2019.

## Instrucciones
En este directorio hay un [cuaderno](https://github.com/microsoft/Data-Science-For-Beginners/blob/main/4-Data-Science-Lifecycle/15-analyzing/assignment.ipynb) y datos de la [Comisión de Taxis y Limusinas](https://docs.microsoft.com/en-us/azure/open-datasets/dataset-taxi-yellow?tabs=azureml-opendatasets). Consulte el [diccionario del conjunto de datos](https://www1.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf) y [la guía del usuario](https://www1.nyc.gov/assets/tlc/downloads/pdf/trip_record_user_guide.pdf) para obtener más información sobre los datos.

Utilice algunas de las técnicas de esta lección para hacer su propio EDA en el cuaderno (agregue celdas si lo desea) y responda las siguientes preguntas:

¿Qué otras influencias en los datos podrían afectar el monto de la propina?
¿Qué columnas probablemente no serán necesarias para responder las preguntas del cliente?
Con base en lo que se ha proporcionado hasta ahora, ¿parecen los datos proporcionar alguna evidencia de un comportamiento de inflexión estacional?


### Respuestas a preguntas
Con la información recopilada y el análisis exploratorio inicial, podemos abordar las preguntas planteadas:

1. Influencias en el monto de la propina:

* Respuesta: Varias variables podrían influir en el monto de la propina, como la duración del viaje, la ubicación de recogida/dejada, eventos especiales, condiciones climáticas, y la calidad del servicio. Sería útil explorar estas variables para comprender mejor las influencias en los hábitos de propina.

2. Columnas que probablemente no sean necesarias:

* Respuesta: Las columnas como VendorID, store_and_fwd_flag, RatecodeID, y improvement_surcharge podrían no ser directamente relevantes para entender los hábitos de propina estacional y podrían ser excluidas para simplificar el análisis, a menos que el cliente tenga un interés específico en ellas. También, dependiendo de la calidad y consistencia de los datos, algunas columnas podrían no ser útiles.

3. Evidencia de comportamiento de inflexión estacional:

* Respuesta: Basándonos en el análisis inicial, parece haber cierta variación en las propinas según la estación del año. Sin embargo, para confirmar un comportamiento de inflexión estacional, sería necesario realizar un análisis más detallado y posiblemente considerar la inclusión de otras variables como eventos especiales, condiciones climáticas y características específicas del viaje.

En resumen, para proporcionar respuestas más definitivas, se necesitaría un análisis más profundo y específico, explorando otras variables y considerando factores adicionales que podrían influir en el comportamiento de propina estacional. También sería útil colaborar con el cliente para afinar aún más las preguntas y asegurarse de que la investigación se alinee completamente con sus objetivos y expectativas.

## Rúbrica
Ejemplar | Adecuado | Necesita mejorar
--- | --- | -- |

#### Esta es la evidencia que corresponde a la <a href="https://github.com/microsoft/Data-Science-For-Beginners/blob/main/4-Data-Science-Lifecycle/15-analyzing/assignment.md">tarea</a> de la lección <a href="https://github.com/microsoft/Data-Science-For-Beginners/blob/main/4-Data-Science-Lifecycle/15-analyzing/README.md">Ciclo de vida: Ciclo de vida de la ciencia de datos: análisis<a href="https://github.com/microsoft/Data-Science-For-Beginners/tree/main"> DATA SCIENCE FOR BEGINNERS</a> de Microsoft.