<h1 align="center">Reporte para Tractchun</h1> 
<div align="center"> <img src="https://github.com/user-attachments/assets/e8af7cc0-ee37-487c-b9b3-212233692f14" width="300px">

</div>

Dashboard Link : https://app.powerbi.com/groups/me/reports/d276dae2-35d0-457c-842f-cd06d30d393b/4e7455e767a0280340b2?experience=power-bi

## Situación Problematica


Este Dashboard fue diseñado para ayudar a la empresa Tractchun a monitorear y tomar decisiones sobre los agentes de IT que brindan soporte a los tickets relacionados con las tecnologías de oficina.

El principal inconveniente que enfrentaba la empresa era que la aplicación que utilizaban para gestionar los tickets no ofrecía opciones de visualización adecuadas, lo que dificultaba la toma de decisiones al no proporcionar información relevante. Además, su interfaz poco intuitiva complicaba aún más el proceso.

Para mejorar esta situación, se implementó un ranking de los agentes de IT según su desempeño en la resolución de tickets. Gracias a esta herramienta, la empresa pudo establecer un sistema de incentivos y premios, motivando a los empleados a resolver los tickets en el menor tiempo posible.

### Pasos seguidos

- Paso 1: Se cargaron los datos en Power BI Desktop; el conjunto de datos es un archivo .csv.

- Paso 2: Como se trata de una empresa ficticia, se definieron las posibles preguntas que podrían hacer los colegas y superiores. Con esta información, se podrá determinar la mejor forma de continuar con el proyecto.

- Paso 3: Luego se realizó la limpieza de datos y se estructuró el modelo de datos. En este se crearon la tabla de hechos, las tablas de dimensión y la dimensión de calendario (la cual nos va a servir para organizar y gestionar las fechas del modelo).

![Image](https://github.com/user-attachments/assets/10610b3f-fc5e-4f04-97bb-3aeb9cb8ff8a) 

- Paso 4: Con los datos ya cargados y en condiciones,se comenzaron a crear las medidas DAX (Data Analysis Expressiones, es el lenguaje de formulas que utilizamos en Power BI para crear medidas y cálculos personalizados) las cuales van a servir para hacer visualizaciones de calidad. Entre ellas podemos destacar las medidas utilizadas para la creación de los Ranking, medidas de totales, promedios y porcentajes.


![Image](https://github.com/user-attachments/assets/adbab39d-3500-44df-a350-446bd911a5dc) 

Esta fórmula cuenta el número total de tickets en la tabla f_Tickets, pero si la tabla no tiene registros, devuelve 0 en lugar de un valor vacío.

![Image](https://github.com/user-attachments/assets/77440808-638d-4863-9af2-81fb08a93de0) 

Esta fórmula calcula el porcentaje de tickets con problemas, dividiendo los tickets con problemas entre el total de tickets. Si el total de tickets es 0, devuelve 0 para evitar un error de división por cero.

![Image](https://github.com/user-attachments/assets/a8da40e0-a49e-40b1-b1b9-09dffe39f6bc)

Esta fórmula calcula el ranking de los agentes de TI en función del promedio de días que tienen los tickets abiertos. Los agentes que resuelven los tickets más rápidamente (menos días abiertos) tendrán un mejor ranking (número más bajo).



MOSTRANDO SEGMENTADOR POR TIPO DE TICKET::
![Image](https://github.com/user-attachments/assets/2575135d-65ae-42d5-a4a0-bc056c1d8551) 
EXPLICAR QUE HACE

- Paso 5: Se procedió con la creación de las visualizaciones, seleccionando el tipo de gráfico correcto según el tipo de dato a representar, asegurando asi una visualización clara y efectiva para facilitar el análisis y la toma de decisiones.

- Paso 6: Una vez creadas las visualizaciones, podemos darles el formato deseado, agregar segmentaciones, filtros y detalles que contribuyan a hacer el dashboard mas atractivo para los usuarios.

![Image](https://github.com/user-attachments/assets/0345729a-f92c-47f9-b5fd-5f846f33d848) Pantalla Inicio

![Image](https://github.com/user-attachments/assets/7a0942ae-15dc-4d20-ba8b-23556538bacd) Pantalla Rank

- Paso 7: Se incorporó un modo oscuro (Dark mode), para mejorar aún mas la experiencia del usuario.

![Image](https://github.com/user-attachments/assets/4a05fd77-563e-4e58-9e8d-cb25ebc8c802) Pantalla Dark 

- Paso 8: Finalmente se publicó el reporte en Power Bi Service se compartió con la organización. Además, se programaron reuniones para recibir retroalimentación de los usuarios y continuar mejorando este y futuros reportes.

![Image](https://github.com/user-attachments/assets/91ad2d3d-9169-4882-8675-9db50f9dc06b) Reporte Publicado

