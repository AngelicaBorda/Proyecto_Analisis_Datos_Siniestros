# **Proyecto_Analisis_Datos_Siniestros**
Proyecto de Análisis de Datos, en el que analizo siniestros en la Ciudad Autónoma de Buenos Aires.

## **Rol a Desarrollar**

El Observatorio de Movilidad y Seguridad Vial (OMSV), centro de estudios que se encuentra bajo la órbita de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, me solicita la elaboración de un proyecto de anális de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales. Para ello, me disponibilizan un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021. Este dataset se encuentra en formato xlsx y contiene dos hojas llamadas: hechos y víctimas. 


## **EDA**

El dataset brindado es un archivo excel, compuesto por la hoja 0 con datos sobre los hechos, hoja 1 un diccionario sobre hechos, hoja 2 con datos sobre las víctimas y hoja 3 con un diccionario sobre victimas. 
Mi primer paso es realizar un análisis exploratorio de datos, veo los valores nulos, duplicados y valores faltantes. Por lo que decido eliminar algunas filas y columnas. Luego busque outliers, pero teniendo en cuenta la temática que analizamos, no detecte ninguno.


## **Análisis de Datos**

En el dataset contamos con la información de los accidentes fatales, ocurridos en la Ciudad Autónoma de Buenos Aires en los años 2016, 2017, 2018, 2019, 2020 y 2021.

| Año | Muertes |
| ------ | ------ |
| 2016 | 146 |
| 2017 | 140 |
| 2018 | 149 |
| 2019 |104 |
| 2020 | 81 |
| 2021 | 97 |
| Total | 717 |

#### Descenso de accidentes fatales en los Años 2019 y 2020.

Analizada la información, se desprende que en los años 2019 y 2020 hubo una significatuva disminución de los accidentes de tránsito con víctimas fatales. Se pudo corroborar que en el año 2019 esa baja se debió al Plan de Seguridad Vial Porteño, en las que se tomo ciertas medidas como campañas de educación y controles viales, que dieron por resultado alrededor de un 30% de reducción de fallecimientos. Por otro lado se pudo observar, que en el 2020 se volvió a reducir notoriamente el número de víctimas, pero en esta oportunidad se debió al confinamiento obligatorio en la ciudad.

Link Plan de Seguridad Vial Porteño [Link](https://www.lanacion.com.ar/sociedad/entre-2018-2019-bajaron-30-muertes-accidentes-nid2376375/)

### **Víctimas**

En cuanto al rango de edad de las víctimas, se oberva que el 46 % son adultos (entre 30 a 59 años) y que los siguen jóvenes con un 30 % (19 a 29 años) y ancianos con un 20.5% (60 en adelante).

Respecto del sexo, el 76.2 es masculino, mientras que el 23.8% femenino.

Rol de la Víctima: podemos obervar que el 42.9 % son motociclistas, seguido de 38.6 % de peatones.

Podemos concluir que la mayoría de víctimas fatales son hombres, adultos y jóvenes, los cuales en su mayoría son motociclistas y peatones.

### **Lugar del accidente**

La mayor cantidad de accidentes se producen en avenidas con el 61.6 %. Las comunas con mas accidentes fatales son las Comuna 1, 4 y 9.

### **Horario**

La franja horaria en que más accidentes ocurren es de noche  y madrugada con el 46.3 %.

## 'KPIs'

- *Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior*

De acuerdo al último censo nacional elaborado por el Instituto Nacional de Estadística y Censos en 2022, la Ciudad Autónoma de Buenos Aires
cuenta con 3.121.707 habitantes [Link](https://www.argentina.gob.ar/caba/)) 

Las víctimas fatales en accidentes de tránsito en el segundo semestre de 2021 fueron 42, por lo que la tasa de homicidios en siniestros viales en el segundo semestre del año 2021 fue del 1.34, lo que implica que para cumplir con el KPI propuesto en el segundo semestre del 2022, habría que reducir en 4.2 a las víctimas fatales.





