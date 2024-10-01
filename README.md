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

cambiar imagen:
<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/estructuraproyecto.png"  height=500>
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

evolucion conectividad
<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/evalucion_conectividad.png"  height=500>
</p>

evolucion Accesos a tecnologia:
<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/evolucion_acc_tecnologia.png"  height=500>
</p>

evolucion velocidades
<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/evolucion_velocidades.png"  height=500>
</p>

Ingresos y comparacion en USd:
<p align="center">
<img src="https://github.com/FerchoHenry/fmgc-pida/blob/main/imagenes/ingresos_usd.png"  height=500>
</p>

## Dashboard  
Debe ser funcional y coherente con el storytelling. El dasbhoard tiene que incluir filtros, permitiendo explorar detalladamente los datos con la selección de cada uno de ellos. Es decir, es indispensable que sea interactivo. También, se espera que el diseño que implementen facilite la interpretación de la información y su análisis, siendo importante, para ello, la claridad en la presentación de los datos, aspectos inherentes a la esteticidad, elección coherente de los gráficos según las variables a visualizar, entre otros ítems.
  
## KPIs  
Debes graficar y medir el KPI propuesto a continuación, representándolo adecuadamente en el dashboard. A su vez, tambíen tienes que proponer, medir y graficar dos KPIs que consideres relevantes para la temática. 
El KPI propuesto es:
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


 

