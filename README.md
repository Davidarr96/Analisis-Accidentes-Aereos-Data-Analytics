   # PROYECTO Nº2  
([https://camo.githubusercontent.com/d4c225a859fc581be3b56ec513fc45eeb967df9ce0c26270e33aad71d446d812/68747470733a2f2f736c61636b2d696d67732e636f6d2f3f633d31266f313d726f2675726c3d687474707325334125324625324663646e2e706978616261792e636f6d25324670686f746f253246323031362532463039253246313525324631362532463133253246616972706c616e652d313637313936375f313238302e6a7067])


## DATA ANALITYCS-TEMÁTICA : ACCIDENTES AEREOS

## Introducción:

En esta ocación nos toca simular un Data Analitycs contratado por la empresa OACI (Organización de Aviación Civil Internacional, con el fin de reducir la tasa de mortalidad en accidentes aereos. 
 
 Para dicho objetivo, la empresa Henry nos brinda el siguiente [Dataset](https://github.com/Davidarr96/Proyecto_DataAnalitycs/blob/master/AccidentesAviones.csv) , con el fin de obtener la mayor información posible para realizar nuestra investigación. Además nos proporciona el siguiente [Repositorio](https://github.com/soyHenry/PI03-Analytics) con toda la información complementaria, donde podremos acceder a más información requerida para nuestro caso.
 
 ## EDA ( Análisis exploratortio de los datos)
 
 Para comenzar nuetro análisis, lo primero que se realizo fue cargar nuesto dataset en un notenook con todas las librerías y correspondencias necesarias para optimizar nuestro análisis. En este [Link](https://github.com/Davidarr96/Proyecto_DataAnalitycs/blob/master/EDA.ipynb) pueden encontrar cada paso que se fue realizando.
 
 Además de nuestro analisis exploratorio de datos, se decidió realizar las siguientes transformaciones :
 - Se reemplazo los valores '?' por Nan para saber cuantos valores nulo
 - Se normalizaron los títulos: 'fecha' : 'date', 
 'HORA declarada' : 'time',' Ruta' : 'location', 'OperadOR' : 'operator', 'PASAJEROS A BORDO' : 'passengers_aboard', 'cantidad de fallecidos' : 'total_fatalities'.
 - Se eliminaron los valores duplicados
 - Se eliminaron columnas como  'flight_no', 'cn_ln', 'registration' debido a la cantidad de valores nulos y falta de importancia dentro de nuestro analisis.
 - Entre otras transformaciones.

Una vez finalizado el analisis, se exporto este [Dataset](https://github.com/Davidarr96/Proyecto_DataAnalitycs/blob/master/AccidentesAereos.csv) a power bi para poder realizar los analisis correpondientes.

## ANALISIS:

Para una correcta interpretación de los datos, se decidío crear visualizaciones enfocados en la cantidad de muertes comparados a la cantidad de personas a bordo. Se logró identificar patrones y anomalías relacionadas con grandes sucesos de los últimos años, y en base a la mediana  se crearon KPI´s, donde en primera instancia se realiza una disminución progresiva de reduccion del 5% de la tasa de mortalidad total, hasta lograr el cometido 5% anual. Asímismo, se proyectó incrementar de forma correlativa la tasa de supervivencia, donde se ilustra un ejemplo de aumento en sobrevivientes de forma progresiva. Para poner en contexto, invito a que observen mi [Visualización](https://github.com/Davidarr96/Proyecto_DataAnalitycs/blob/master/Aviones.pbix) y puedan darme un feedback.





