<h1 align="center">Reporte para Tractchun</h1> 
<div align="center"> <img src="https://github.com/user-attachments/assets/e8af7cc0-ee37-487c-b9b3-212233692f14" width="300px">


### Dashboard Link : https://app.powerbi.com/groups/me/reports/d276dae2-35d0-457c-842f-cd06d30d393b/4e7455e767a0280340b2?experience=power-bi

## Situación Problematica


Este Dashboard fue diseñado para ayudar a la empresa Tractchun a monitorear y tomar decisiones sobre los agentes de IT que brindan soporte a los tickets relacionados con las tecnologías de oficina.

El principal inconveniente que enfrentaba la empresa era que la aplicación de tickets no ofrecía opciones de visualización adecuadas, lo que dificultaba la toma de decisiones al no proporcionar información relevante. Además, su interfaz poco intuitiva complicaba aún más el proceso.

Para mejorar esta situación, se implementó un ranking de los agentes de IT según su desempeño en la resolución de tickets. Gracias a esta herramienta, la empresa pudo establecer un sistema de incentivos y premios, motivando a los empleados a resolver los tickets en el menor tiempo posible.

### Pasos seguidos

- Paso 1: Se cargaron los datos en Power Bi Desktop; el conjunto de datos es un archivo .csv.

- Paso 2: Como se trata de una empresa ficticia, se definieron las posibles preguntas que podrían hacer los colegas y superiores. Con esta información, se podrá determinar la mejor forma de continuar con el proyecto.

- Paso 3: Luego se realizo la limpieza de datos y se estructuró el modelo de datos. En este se crearon la tabla de hechos, las tablas de dimensión y la dimensión de calendario (la cual nos va a servir para organizar y gestionar las fechas del modelo).

![Image](https://github.com/user-attachments/assets/10610b3f-fc5e-4f04-97bb-3aeb9cb8ff8a) 

- Paso 4: Con los datos ya cargados y en condiciones,se comenzaron a crear las medidas DAX (Data Analysis Expressiones, es el lenguaje de formulas que utilizamos en Power BI para crear medidas y cálculos personalizados) las cuales van a servir para hacer visualizaciones de calidad. Entre ellas podemos destacar las medidas utilizadas para la creación de los Ranking, medidas de totales, promedios y porcentajes.

EXPLICAR QUE HACEN ESTOS DAXXXXX

![Image](https://github.com/user-attachments/assets/adbab39d-3500-44df-a350-446bd911a5dc) DAX 1 TOTAL TICKETS

![Image](https://github.com/user-attachments/assets/77440808-638d-4863-9af2-81fb08a93de0) DAX 2 % PROBLEMA

![Image](https://github.com/user-attachments/assets/a8da40e0-a49e-40b1-b1b9-09dffe39f6bc) DAX 3 RANK DIAS

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




### [1] Total Number of Customers = 129880

   Number of satisfied Customers (Male) = 28159 (21.68 %)

   Number of satisfied Customers (Female) = 28269 (21.76 %)

   Number of neutral/unsatisfied customers (Male) = 35822 (27.58 %)

   Number of neutral/unsatisfied customers (Female) = 37630 (28.97 %)


           thus, higher number of customers are neutral/unsatisfied.
           
### [2] Average Ratings

    a) Baggage Handling - 3.63/5
    b) Check-in Service - 3.31/5
    c) Cleanliness - 3.29/5
    d) Ease of online booking - 2.88/5
    e) Food & Drink - 3.21/5
    f) In-flight Entertainment - 3.36/5
    g) In-flight service - 3.64/5
    h) In-flight Wifi service - 2.81/5
    i) Leg room service - 3.37/5
    j) On-board service - 3.38/5
    k) Online boarding - 3.33/5
    l) Seat comfort - 3.44/5
    m) Departure & arrival convenience - 3.22/5
  
  while calculating average rating, null values have been ignored as they were not relevant for some customers. 
  
  These ratings will change if different visual filters will be applied.  
  
  ### [3] Average Delay 
  
      a) Average delay in arrival(minutes) - 15.09
      b) Average delay in departure(minutes) - 14.71
Average delay will change if different visual filters will be applied.

 ### [4] Some other insights
 
 ### Class
 
 1.1) 47.87 % customers travelled by Business class.
 
 1.2) 44.89 % customers travelled by Economy class.
 
 1.3) 7.25 % customers travelled by Economy plus class.
 
         thus, maximum customers travelled by Business class.
 
 ### Age Group
 
 2.1)  21.69 % customers belong to '0-25' age group.
 
 2.2)  52.44 % customers belong to '25-50' age group.
 
 2.3)  25.57 % customers belong to '50-75' age group.
 
 2.4)  0.31 % customers belong to '75-100' age group.
 
         thus, maximum customers belong to '25-50' age group.
         
### Customer Type

3.1) 18.31 % customers have customer type 'First time'.

3.2) 81.69 % customers have customer type 'returning'.
       
       thus, more customers have customer type 'returning'.

### Type of travel

4.1) 69.06 % customers have travel type 'Business'.

4.2) 30.94 % customers have travel type 'Personal'.

        thus, more customers have travel type 'Business'.r

