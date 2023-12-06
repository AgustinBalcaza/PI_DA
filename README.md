# PI_DA

Introducción
--------

Este proyecto tiene como objetivo realizar un análisis exhaustivo de datos relacionados con siniestros viales en la Ciudad Autónoma de Buenos Aires. Los datos fueron extraídos de BA Data, se sometió a un ETL, luego a un EDA y finalmente se graficó en un dashboard en Power BI

ETL - Extracción, Transformación y Carga
---------------

+ Se extrajeron los datos de la hoja **HECHOS** del dataset inicial de homicidios que nos proporcionaron
+ Se modificaron nombres de las columnas
+ Se modificaron los valores faltantes por **SD**
+ Se realizaron unas últimas transformaciones para modificar el tipo de dato de algunas columnas como fechas y horas
+ Se guardó el nuevo dataset limpio en un archivo Excel


Análisis Exploratorio de Datos (EDA)
-----------------------------------------

Se crearon visualizaciones y gráficos para analizar valores atípicos en los siniestros viales ocurridos en la Ciudad Autónoma de Buenos Aires. En el EDA se pudo observar que:

+ La mayoría de siniestros viales ocurren en la Comuna 1
+ Una gran parte de los siniestros viales ocurren durante la mañana
+ Gran parte de los siniestros viales ocurren en Diciembre
+ Hubo un descenso en el número de siniestros viales durante los años 2019, 2020 y 2021 probablemente debido a la Pandemia por COVID-19 y la cuarentena que realizó el país
+ La mayoría de las víctimas son de género masculino
+ Gran parte de los siniestros viales ocurren en avenidas
+ Las principales víctimas suelen ser motos y peatones


Dataset
---------

El dataset **homicidios.xlsx** fue extraído de BA Data. Los otros datasets están presentes en la carpeta **data/** y fueron creados mediante ETL


Autor
-------

+ **Agustín Balcaza**
