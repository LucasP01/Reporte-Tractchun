# Reporte para Tractchun  📊

<div align="center">  
  <a href="https://app.powerbi.com/groups/me/reports/d276dae2-35d0-457c-842f-cd06d30d393b/4e7455e767a0280340b2?experience=power-bi" target="_blank">
    <img src="https://github.com/user-attachments/assets/e8af7cc0-ee37-487c-b9b3-212233692f14" width="300px" alt="Reporte Power BI">
  </a>
  
  <br>  
  <sub><i style="color:gray;">🔗 Haz clic en la imagen para abrir el reporte</i></sub>
</div>

## Situación Problematica 🚀


Este Dashboard fue diseñado para ayudar a la empresa Tractchun a monitorear y tomar decisiones sobre los agentes de IT que brindan soporte a los tickets relacionados con las tecnologías de oficina.

El principal inconveniente que enfrentaba la empresa era que la aplicación que utilizaban para gestionar los tickets no ofrecía opciones de visualización adecuadas, lo que dificultaba la toma de decisiones al no proporcionar información relevante. Además, su interfaz poco intuitiva complicaba aún más el proceso.

Para mejorar esta situación, se implementó un ranking de los agentes de IT según su desempeño en la resolución de tickets. Gracias a esta herramienta, la empresa pudo establecer un sistema de incentivos y premios, motivando a los empleados a resolver los tickets en el menor tiempo posible.

## 📊 Fuentes de Datos  
El dashboard se construyó utilizando datos ficticios proporcionados por Javier Gomez en su curso de Power BI en Udemy.  

- **Origen de los datos:** El origen son los siguientes archivos en formato .xlsx: Agentes, FotosAgentes, Lista+Empleados, Puestos y Tickets (desde 2016 a 2020).
- **Frecuencia de actualización:** No hay mas actualizaciones del reporte.


## Paso a Paso 🚶🏻

- Paso 1: Se cargaron los datos en Power BI Desktop; el conjunto de datos es un archivo .csv.

- Paso 2: Como se trata de una empresa ficticia, se definieron las posibles preguntas que podrían hacer los colegas y superiores. Con esta información, se podrá determinar la mejor forma de continuar con el proyecto.

- Paso 3: Luego se realizó la limpieza de datos y se estructuró el modelo de datos. En este se crearon la tabla de hechos, las tablas de dimensión y la dimensión de calendario (la cual nos va a servir para organizar y gestionar las fechas del modelo).

<img src="https://drive.google.com/uc?export=view&id=1R3yiGTBqC5HPqdhdPk8bcG6ACxnoyImf" alt="Modelo de datos" width="800"> 

- Paso 4: Con los datos ya cargados y en condiciones,se comenzaron a crear las medidas DAX (Data Analysis Expressiones, es el lenguaje de formulas que utilizamos en Power BI para crear medidas y cálculos personalizados) las cuales van a servir para hacer visualizaciones de calidad. Entre ellas podemos destacar las medidas utilizadas para la creación de los Ranking, medidas de totales, promedios y porcentajes.

<img src="https://drive.google.com/uc?export=view&id=1CLssyZ-w5AMXOUwdVZlq4qIvfwokHB-R" alt="Total tickets">

Esta fórmula cuenta el número total de tickets en la tabla f_Tickets, pero si la tabla no tiene registros, devuelve 0 en lugar de un valor vacío.

<img src="https://drive.google.com/uc?export=view&id=1hhKgL-vll8-D-s6wW4FK9hA16U85-8Ph" alt="% Problemas">

Esta fórmula calcula el porcentaje de tickets con problemas, dividiendo los tickets con problemas entre el total de tickets. Si el total de tickets es 0, devuelve 0 para evitar un error de división por cero.

<img src="https://drive.google.com/uc?export=view&id=1x0IKFNgNT3SxWh7Se-nqJbo914PpWPdJ" alt="Rank días">

Esta fórmula calcula el ranking de los agentes de TI en función del promedio de días que tienen los tickets abiertos. Los agentes que resuelven los tickets más rápidamente (menos días abiertos) tendrán un mejor ranking (número más bajo).


- Paso 5: Se procedió con la creación de las visualizaciones, seleccionando el tipo de gráfico correcto según el tipo de dato a representar, asegurando asi una visualización clara y efectiva para facilitar el análisis y la toma de decisiones.

- Paso 6: Una vez creadas las visualizaciones, podemos darles el formato deseado, agregar segmentaciones, filtros y detalles que contribuyan a hacer el dashboard mas atractivo para los usuarios.

<img src="https://drive.google.com/uc?export=view&id=1UtP_jItr90sLlW5pWGbHuLHKtS2RHwru" alt="Pantalla principal" width="800">
<img src="https://drive.google.com/uc?export=view&id=1rj7_oIFsRUC-FQythNXIwu1YEhczx1-K" alt="Ranking agentes" width="800">

- Paso 7: Se incorporó un modo oscuro (Dark mode), para mejorar aún mas la experiencia del usuario.

<img src="https://drive.google.com/uc?export=view&id=188PEfSIfsEA3PljVxD22hmIg0ydCBnV2" alt="Modo Oscuro" width="800">

- Paso 8: Finalmente se publicó el reporte en Power Bi Service se compartió con la organización. Además, se programaron reuniones para recibir retroalimentación de los usuarios y continuar mejorando este y futuros reportes.

<img src="https://drive.google.com/uc?export=view&id=1v7XgdZvXvkAKO2M6acWn67IsizOhLHSh" alt="Reporte publicado" width = "400">

