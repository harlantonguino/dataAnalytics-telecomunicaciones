# DataAnalyst_InternetFijo Argentina

![HENRY](https://info.expeditors.com/hs-fs/hubfs/AdobeStock_335784628.jpeg?width=2750&name=AdobeStock_335784628.jpeg))



### Proyecto Data Analyst
Realizar un análisis completo que permita reconocer el comportamiento del sector de servicios de telecomunicaciones especificamente internet fijo a 
nivel nacional

##### El proyecto se desarrolla en python, dashboard power bi

### Archivos disponibles:

[>>> link to datasets originales::](https://drive.google.com/drive/folders/1oIR4AlBRNpNQrzngluD6oYgWxXpObQan?usp=drive_link)

### datasets
##### datasets luego de ETL y hacer un merge entre los datasets originales. Seran usados para realizar el EDA
- dfNacion.csv
- dfProvincia.csv
- df.Localidad.csv

### notebooks
##### ETL
- PI2_DA_ETL.ipynb

##### EDA 
- PI2_DA_EDA.ipynb

##### API Request 
- PI2_DA_APIREquest.ipynb

### API Request

Se realiza un request de los datasets disponibilizados en la API datos abiertos de enacom.com.ar. Finalmente se decide usar los archivos csv descargados
de forma manual debido a que la API no es estable

### ETL

Es realizado un proceso de extraccion, transformacion y carga de los datos. Se intenta reunir toda la iformacion de interes en pocos datasets. 
Finalmente se dispone de un nuevo archivo csv discriminado por Nacion, Provincia y Localidad

### EDA

Con la informacion disponible se realiza un analisis exploratorio de los datos con el objetivo de identificar tendencias que nos permitan extraer 
informacion valiosa de los datos suministrados y finalmente generar conocimiento como base para la toma de desiciones de forma acertada

Analisis exploratorio de datos sobre internet fijo en Argentina con informacion disponible entre Q1 2014 hasta Q3 2022 en varios datasets 
obtenidos de enacom.com.ar

Al 2022 Q3 los accesos de internet fijo en el pais alcanzaron 11 millones y presentaron un incremento del 10.0% respecto al mismo trimestre 
del año anterior. Los ingresos ascienden a 67.055.929(miles de pesos) en el tercer trimestre del 2022 con un incremento del 55.9% en relacion 
al mismo trimestre del año anterior. En cuanto a la penetracion del servicio se presentan 76.64 accesos por cada 100 hogares en el tercer trimestre
2022 incrementando 8.6% los accesos respecto al tercer trimestre 2021. Para el 2022 Q3 la velocidad media de bajada esta en 62.46mbps arriba 
28.9% en relacion al 2021 Q3. Los accesos por fibra optica en el 2022 tercer trimestre llegan a 2.871.541 un aumento del 83.4% respecto al mismo trimestre 
del año anterior.

### grafica1. ingresos, accesos, velocidad nacion
![Captura de pantalla 2023-07-15 235311](https://github.com/harlantonguino/DataAnalyst_InternetFijo/assets/9009541/5882cb79-bca4-43ab-b4cb-05892c6ba10d)

### tabla1. variacion porcentual año anterior
![Captura de pantalla 2023-07-15 234917](https://github.com/harlantonguino/DataAnalyst_InternetFijo/assets/9009541/fbe7db15-3725-429e-b995-78bdcfc83dd5)

Se observa un fuerte cambio en la tendencia de los accesos por fibra en el año 2018 lo que repercute en el drastico aumento en los acceos con velocidades
mayores a 30mbps. Se puede deducir una migracion de tecnologia 

### grafica2. accesos internet fijo por tecnologia
![Captura de pantalla 2023-07-15 235758](https://github.com/harlantonguino/DataAnalyst_InternetFijo/assets/9009541/9c1e8dfd-4dce-4387-acd5-c6f68b4be946)

### grafica3. accesos internet fijo por velocidad
![Captura de pantalla 2023-07-15 235833](https://github.com/harlantonguino/DataAnalyst_InternetFijo/assets/9009541/a3343c28-2f6d-411b-9390-bfabed24b7dd)

Se presenta la relacion porcentual de los accesos tanto por las diferentes tecnologias como las diferentes velocidades en diferentes años. Se identifica que en el 2022 
predominan los acceso por cable modem sobre la demas tecnologias con un 54.4% en relacion a los accesos por fibra que representan un 25.9% del total 
de accesos. De la misma manera en cuanto a la velocidad media se puede identificar un dominio de las velocidades mayores a 30mbps con 63.1% respecto 
al total de los accesos. Cabe resaltar la disminucion gradual de los accesos por tecnologia ADLS en el trasncurso de los años, la migracion hacia fibra 
optica y la tendencia de los accesos mayores a 30mbs pasando de 0.2% en 2014 a 63.1% en 2022 con relacion a los accesos totales por tecnologia. 

### grafica4. relacion accesos por tecnlogias, accesos por velocidades
![Captura de pantalla 2023-07-16 000703](https://github.com/harlantonguino/DataAnalyst_InternetFijo/assets/9009541/fcbe8a0f-4999-4f0e-85fd-74997824a210)

### tabla2. relacion porcentual accesos por tecnlogias, accesos por velocidades
![Captura de pantalla 2023-07-16 002515](https://github.com/harlantonguino/DataAnalyst_InternetFijo/assets/9009541/9734e657-a727-419b-89e9-693a7291658e)


### DashBoard

Visualizacion de los datos desarrollados en power bi. Se crea un tablero interactivo con los datos relevantes del objeto de estudio que permite
presentar de forma acertada la informacion 

### Autor
Harlan Tonguino
[>>> link to Linkedin:](https://www.linkedin.com/in/harlan-tonguino-37048a174)
