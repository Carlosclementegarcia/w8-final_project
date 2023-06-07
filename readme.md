Proyecto Company reports


![image](https://github.com/Carlosclementegarcia/w8-final_project/assets/129602687/4de56635-63d0-4e8b-8767-7cb1d3521732)


Descripción general:
Este proyecto resulta de la necesidad de parametrizar aspectos claves de una compañía de negocios dedicada a la venta de vehículos a escala.
La idea es controlar con 4 cuadros de mandos los parámetros claves de una empresa de una facturación en torno a 30 millones de € anuals y con datos de 2020, 2021 y 2022.
En términos generales, el proyecto se ha basado en realizar un proceso de limpieza y transformación del dato con Python y la creación de un dashboard o cuadro de mando con Power BI.

Desarrollo del proyecto:
Exploración de los datos y unificación de los mismos:

- Limpìeza de los datos en Python 
Los ficheros que he manejado se necuentran en formato .XLSX y por tanto los paso a formato .CSV, a fin de poder utilizarlos de forma conveniente, a partir de hay se han eliminado columnas con información no precisa para este proyecto, transformación y cohesión de datos en columnas y  paso a dato numérico, para realizar una predicción en una Regresión lineal.

- Machine learning en Python
Se crea un modelo predictivo basado en el fichero payments2, creado exprofeso para este motivo que va a trabajar en los campos month , year y amount, trabajando fundamentalmente en los años ya citados arriba. 
Es una predicción sencilla debida a la ausencia de otro tipo de datos, pero que nos arroja una cifra bastante coherente que nos sirve para fijar el presupuesto de 2023

- Relación de tablas en SQL
Relaciono entre sí las tablas de Sql, para poder acceder tanto a través de los ficheros CSV, los cuales paso a Excel, como a través de Sql, donde compruebo que funcionas las querys que le lanzo , con los datos convenientemente cargados. 

- Power BI
El paso clave para poder realizar un cuadro de mandos con unos kpi's bien definidos y que muestren al CEO de la empresa la situación en tiempo real de la compañia por toda la geografía mundial.


Por tanto, el primer reto de este proyecto ha sido realizar un proceso de exploración de los datos y por razones de tiempo, especificar con el cliente qué columnas o preguntas son más prioritarias para sus procesos y enfocar la homogeneización del dato a las mismas para poder tener datos consistentes de cara a posteriores análisis y el objetivo del proyecto.

Todo este proceso se ha llevado a cabo con Python en distintos Jupyter Notebooks (Arraigo_ETL1, Arraigo_ETL2 y Arraigo_ETL3).

Creación de Dashboard con Power BI:
Una vez contabamos con los datos limpios y consistentes y tras especificar con el cliente los principales KPIs y la información principal que deseaban visualizar se tomó la decisión de crear un cuadro de mando en Power BI, dado que permite un mejor enfoque de negocio.

Con ello, creamos una Dataframe específico a partir de los datos limpios, modificando el tipo de dato de algunas columnas para optimizar la posible visualización.

El resultado del cuadro de mando se puede ver en el siguiente video:

 prueba3.mp4 
Futuros pasos:
Dado que este proyecto se ha tenido que realizar en el plazo de dos semanas al tratarse del proyecto final de mi paso por el Bootcamp de Data en Ironhack, el objetivo del proyecto se ha centrado en intentar dar solución a los problemas prioritarios del cliente. Sin embargo, con el fin de poder dar una solución más efectiva, se plantean los siguientes retos:

Establecer y concretar la mejor forma de respuesta a las preguntas del cuestionario para tener un sistema de recopilación del dato sostenible a largo plazo.
Continuar con el proceso de limpieza y unificación de los datos históricos.
Creación de una Base de Datos consistente.
Alimentar el cuadro de mando con la nueva información y posibles futuros enfoques.
Como valor añadido, crear un modelo de predicción de la demanda para poder plantear escenarios de actuación en el futuro y mejorar la organización interna de recursos.
