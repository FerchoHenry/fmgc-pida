# <h1 align=center> **PROYECTO INDIVIDUAL Nº2 - HENRY DATA ANALYST** </h1>

# <h1 align=center>**`DATA ANALYST (Pida)`**</h1> 

<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/portada_pida.jpg"  height=500>
</p>

### Tabla de Contenido:

1. [Descripción](https://github.com/FerchoHenry/fmgc-pida/blob/main/README.md#descripci%C3%B3n)
2. [Estructura del proyecto](https://github.com/FerchoHenry/fmgc-pida/blob/main/README.md#estructura-del-proyecto)
3. [Consigna](https://github.com/FerchoHenry/fmgc-pida/blob/main/README.md#consigna-del-proyecto)
4. [Datasets](https://github.com/FerchoHenry/fmgc-pida/blob/main/README.md#datasets)
5. [EDA](https://github.com/FerchoHenry/fmgc-pida/blob/main/README.md#eda-exploratory-data-analysis)
6. [Analisis](https://github.com/FerchoHenry/fmgc-pida/blob/main/README.md#analisis)
7. [Dashboard](https://github.com/FerchoHenry/fmgc-pida/blob/main/README.md#dashboard)
8. [Kpis](https://github.com/FerchoHenry/fmgc-pida/blob/main/README.md#kpis)


## **Descripción:**

Una empresa prestadora de servicios de telecomunicaciones nos encarga la realización de un análisis completo que permita reconocer el comportamiento del sector de telecomunicaciones a nivel nacional. Debemos considerar que la principal actividad de la empresa es brindar acceso a internet, pero también es importante tener en cuenta el comportamiento asociado al resto de los servicios de comunicación, con el fin de orientar a la empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.

## Estructura del proyecto:

<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/estructuraproyecto2.png"  height=250>
</p>

## Consigna del proyecto

Debemos realizar un análisis exploratorio de los datos en un notebook donde estaran los pasos documentados con claridad, con las conclusiones correspondientes en cada gráfico empleado y análisis de lo que vamos observando, utilizaremos celdas **`Markdown`** para tal fin. La prolijidad del notebook será un aspecto que consideraremos. Deberemos tener en cuenta varios aspectos indispensables ,como son : búsqueda de valores faltantes, valores atípicos/extremos u outliers y registros duplicados. Asimismo, la utilización de gráficos coherentes según la tipología de variable que corresponda resulta esencial.

Ademas deberemos realizar un **`Dashboard`** que debera ser funcional y coherente con el storytelling. El dasbhoard debera incluir filtros, permitiendo explorar detalladamente los datos con la selección de cada uno de ellos. Es decir, será indispensable que sea interactivo. También, se espera que el diseño que implementen facilite la interpretación de la información y su análisis, siendo importante, para ello, la claridad en la presentación de los datos, aspectos inherentes a la esteticidad, elección coherente de los gráficos según las variables a visualizar, entre otros ítems.

Otro factor a realizar sera un **`Analisis`** del cual no se considerará solamente la producción de gráficos con datos -dashboard-, sino también los análisis y conclusiones que puedan extraer a partir de ellos.

Todo esto teniendo en cuenta los puntos detallados en la [rúbrica de evaluación](https://docs.google.com/spreadsheets/d/e/2PACX-1vTy9Ome3iLIl40SZ2jciZLiwARr9MVXfo_Mud3vVCin9P4zroAw_oxVQVch6m4TKivmUjFrYJKMJJhS/pubhtml)


## Datasets

- [Datasets principales](https://indicadores.enacom.gob.ar/datos-abiertos) 
- [Diccionario de datos](https://docs.google.com/document/d/1BYW0vT_DNIjjKM9v4hNg5KmqjRNOc7OBB1jCXc80gnI/edit#heading=h.hjukififf3ol)

### Dataset Complementario:
* Para el analisis de ingresos vs moneda dolar se extrajo informacion de tipo de cambio segun año (a mitad de primer trimestre) desde pagina oficial del BCRA

fuente:     
https://www.bcra.gob.ar/PublicacionesEstadisticas/Planilla_cierre_de_cotizaciones.asp

* Además se separó la hoja Acc de velocidades generando un nuevo archivo con la info agrupadas segun caegorias de velocidades.

## EDA (Exploratory Data Analysis) 

Se realizó un análisis exploratorio de los datos en un notebook, donde figuran los pasos documentados con conclusiones correspondientes en cada gráfico empleado y análisis de lo que se fue  observando, utilizando celdas Markdown para tal fin. 
Para cada Dataframe generado se realizo : búsqueda de valores faltantes, valores atípicos/extremos u outliers y registros duplicados
El mismo se puede visualizar desde [EDA](https://github.com/FerchoHenry/fmgc-pida/blob/main/notebooks/EDA.ipynb)

## Analisis

### Evolucion conectividad:
<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/evalucion_conectividad.png"  height=500>
</p>

### Del grafico podemos observar que la conectividad sobre los hogares y sobre los habitantes ambas crecieron en los ultimos años.

### Evolucion Accesos a tecnologia:
<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/evolucion_acc_tecnologia.png"  height=500>
</p>

#### Del siguiente grafico se puede llegar a las siguientes deducciones:  
*   La tecnologia CABLEMODEM es la que al primer trimestre del 2024 presenta mayor numero de accesos, la misma presenta un movimiento lateral desde el 2022  
*   La tecnologia ADSL era la de mayor numero de accesos en el 2014 , luego del 216 presenta una baja logaritmica
*   Fibra Optica es la tecnologia con mayor tasa de creciemiento desde el 2021 se pudiera sugerir que dentro de unos años podria superar al CABLEMODEM  
*   La tecnologia Wireless presenta un comportamiento lateral con tendencia levemente positiva


### Evolucion velocidades:
<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/evolucion_velocidades.png"  height=500>
</p>

#### Se puede observar que la curva de velocidad avanza de manera lineal hasta el 2017 para luego desde ahi tomar un comportamiento exponencial, esto comparado con las curvas de tecnologias aplicadas por año se explica en el predominio de tecnologias como fibra optica las cuales tienen mayor ancho de banda

### Analisis Geografico y velocidades:

<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/Geografico.png"  height=500>
</p>

### Del siguiente Dashboard se puede ver por un lado informacion en el mapa segun el radio de la burbuja que provincia cuenta con mayor numero de conexiones y cuales no (cualitativamente) ademas en las provincias del mapa donde no figura una burbuja o es pequeña nos da informacion donde podria haber un nicho de mercado por evaluar. Ademas en el grafico de torta podemos evaluar por cada provincia el porcentaje de implementacion de cada tecnologia por provincia. Por ultimo tambien se puede evaluar el rango de velocidades de cada provincia, si bien esta el top 6 de provincias selecionando las provincias en el segmentador de la izquierda se puede indentificar a cada una

### Ingresos y comparacion en USd:
<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/ingresos_usd.png"  height=500>
</p>

#### Si bien el grafico de ingresos muestra un fuerte ascenso en el ultimo periodo su contraste en moneda dolar indica que la misma disminuyó.

## Dashboard  

Se realizo en PowerBI con la idea de poder realizar un storytelling. El mismo incluye filtros, permitiendo explorar detalladamente los datos con la selección de cada uno de ellos.Se priorizó que el diseño facilite la interpretación de la información y su análisis.
El mismo se puede encontrar en : [Dashboard](https://github.com/FerchoHenry/fmgc-pida/blob/main/reports/Pida-fmgc.pbix)
  
## KPIs 
 
Se representan 3 KPIs:

1_ El KPI propuesto es:
- *Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia*.
La fórmula es la siguiente:

 $`KPI = ((Nuevo acceso - Acceso actual) / Acceso actual) * 100`$
 
Donde:

- "Nuevo acceso" se refiere al número de hogares con acceso a Internet después del próximo trimestre.
- "Acceso actual" se refiere al número de hogares con acceso a Internet en el trimestre actual.

Esta fórmula te ayudará a calcular el KPI para medir el aumento en el acceso a Internet por cada 100 hogares en cada provincia.

**Ejemplo de uso:**

KPI = ((510 - 500) / 500) * 100 = 2%

Esto indicaría un aumento del 2% en el acceso a Internet en esa provincia para el próximo trimestre.


 

