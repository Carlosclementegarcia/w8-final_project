Proyecto Company Classic models reports


![image](https://github.com/Carlosclementegarcia/w8-final_project/assets/129602687/4de56635-63d0-4e8b-8767-7cb1d3521732)


Descripción general:
Este proyecto resulta de la necesidad de parametrizar aspectos claves de una compañía de negocios dedicada a la venta de vehículos a escala.
La idea es controlar con 4 cuadros de mandos los parámetros claves de una empresa de una facturación en torno a 30 millones de € anuals y con datos de 2020, 2021 y 2022.
En términos generales, el proyecto se ha basado en realizar un proceso de limpieza y transformación del dato con Python y la creación de un dashboard o cuadro de mando con Power BI.

Desarrollo del proyecto:
Exploración de los datos y unificación de los mismos:

- Limpìeza de los datos en Python 
Los ficheros que he manejado se necuentran en formato .XLSX y por tanto los paso a formato .CSV, a fin de poder utilizarlos de forma conveniente, a partir de hay se han eliminado columnas con información no precisa para este proyecto, transformación y cohesión de datos en columnas y  paso a dato numérico, para realizar una predicción en una Regresión lineal. Trabajo realizado en Visula Studio Code.

- Machine learning en Python
Se crea un modelo predictivo basado en el fichero payments2, creado exprofeso para este motivo que va a trabajar en los campos month , year y amount, trabajando fundamentalmente en los años ya citados arriba. 
Es una predicción sencilla debida a la ausencia de otro tipo de datos, pero que nos arroja una cifra bastante coherente que nos sirve para fijar el presupuesto de 2023.

![image](https://github.com/Carlosclementegarcia/w8-final_project/assets/129602687/b1231f23-7df7-4059-8fcd-ac70d662ddb7)



- Relación de tablas en SQL
Relaciono entre sí las tablas de Sql, para poder acceder tanto a través de los ficheros CSV, los cuales paso a Excel, como a través de Sql, donde compruebo que funcionas las querys que le lanzo , con los datos convenientemente cargados. Trabajo realizado en My Sql Workbench.

![image](https://github.com/Carlosclementegarcia/w8-final_project/assets/129602687/cc5eb759-c0ee-423d-88b2-097107bc8f8c)


- Power BI
El paso clave para poder realizar un cuadro de mandos con unos kpi's bien definidos y que muestren al CEO de la empresa la situación en tiempo real de la compañia por toda la geografía mundial.

![image](https://github.com/Carlosclementegarcia/w8-final_project/assets/129602687/fd3394fc-d5c4-442d-ac80-3e6adbef1381)


Diseño sobre el papel  4 Dashboards como cuadro de mandos de la empresa classic models. La primera pantalla referida a todo lo que se refiere a finanzas y a control de gasto, la segunda orientada a compras y a almacén, la tercera a RRHH y la cuarta y última a Ventas


![image](https://github.com/Carlosclementegarcia/w8-final_project/assets/129602687/3c3e6207-95b9-42af-8607-8e03d555ea32)


Desde estos dispositivos realizamos análisis de datos orientados a optimizar y armonizar el funcionamiento de la empresa y a dotarle de rápidas reacciones ante cualquier dificultad. Control de stock, seguimiento de cifra a vendedores, márgenes comerciales,  situación de los pagos de la compañía, etc.


![image](https://github.com/Carlosclementegarcia/w8-final_project/assets/129602687/b6ed7297-a98c-40ca-91b9-465a7f4a6b31)


Al tratarse de varios dataframes con alguna información sesgada o inexistente no se ha podido avanzar más en materia de machine learning o de alimentación actualizada de los datos, aunque el trabajo está orientado a poder amplificarse de manera sencilla y eficaz.


![image](https://github.com/Carlosclementegarcia/w8-final_project/assets/129602687/e36a8747-41f4-48d9-96be-1e306ffcff32)







