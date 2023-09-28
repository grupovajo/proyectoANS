# CLUSTERING DE UNIDADES PRODUCTIVAS AGRÍCOLAS

<img src="https://raw.githubusercontent.com/grupovajo/proyectoANS/master/recursos/MIAD.png" align="right"
     alt="MIAD" width="84" height="35">
<img src="https://raw.githubusercontent.com/grupovajo/proyectoANS/master/recursos/Uniandes.png" align="left"
     alt="MIAD" width="84" height="35">
     
Repositorio grupo 8 del proyecto ANS de la maestría en inteligencia analitica de datos Uniandes


## Descripción

Este proyecto tiene como objetivo principal la generación de clusters de unidades productivas agrícolas (UPA) para la focalización de subsidios e inversiones que se planeen realizar para potenciar el agro colombiano. Este algoritmo de aprendizaje no supervisado de generación de clusters fue desarrollado en lenguaje Python con librerias de Scikit-Learn y SciPy donde usamos algoritmos de clusters o agrupamiento.

 Este proyecto surge para suplir la necesidad de focalización y priorización de inversiones que se realizarán para potenciar el campo colombiano, con el objetivo de agrupar aquellos con mayor potencial de suplir las necesidades regionales y de exportaciones a otros paises.

- A continuación se podrá consultar la siguiente información:

  - [Prerrequisitos](#prerrequisitos)
  - [Ejemplo](#ejemplo)
  - [Resultados](#resultados)
  - [Contribuciones](#contribuciones)
  - [Contacto](#contacto)
 
## Prerrequisitos
Se debe tener instalado Scikit-Learn y SciPy, se recomienda tener Anaconda 3 o de lo contrario las librerias de Pandas, Numpy, Matplotlib y Seaborn.

## Ejemplo
Como ejemplo se presenta el proceso de clustering para la soya, la cual es el producto más demandado en el mundo y especialmente en los paises de Asia.

<img src="https://raw.githubusercontent.com/grupovajo/proyectoANS/master/recursos/TablaProductosAgricolas.png" align="center"
     alt="MIAD" width="553" height="266">

Es así como para la soya se encuentra el piloto de clustering para focalización de esfuerzos para potenciar el campo colombiano.



## Resultados
Los resultados a detalle se pueden encontrar en el notebook, sin embargo es importante resaltar y mostrar los siguientes resultados de la clusterización.

<img src="https://raw.githubusercontent.com/grupovajo/proyectoANS/master/recursos/ResultadosClustersMapa.png" align="center"
     alt="MIAD" width="393" height="349">

En el mapa se observa como en total obtenemos 5 clusters que estan distribuidos por algunas zonas que estan divididas coherentemente en diferentes suelos que se encuentran en el país.

<img src="https://raw.githubusercontent.com/grupovajo/proyectoANS/master/recursos/MapaFertilidadCO.png" align="center"
     alt="MIAD" width="227" height="335">

Siendo esto un indicio que el cálculo del potencial que se propone logra dividir estos clusters de una manera que recoja la variabilidad y nos de una mejor perspectiva para el cultivo de la soya y las posibles zonas que se deberian prestar especial atención.

Por último si vemos las siguientes gráficas, se puede observar que los resultados estan bien distribuidos (que no siempre sera el caso para cualquier producto agrícola) y que tenemos una gran cantidad de datos que podrian considerarse extremos, sin embargo esto no es necesariamente malo para el ejercicio.

<img src="https://raw.githubusercontent.com/grupovajo/proyectoANS/master/recursos/ResultadosClustersBox.png" align="left"
     alt="MIAD" width="523" height="238">
<img src="https://raw.githubusercontent.com/grupovajo/proyectoANS/master/recursos/ResultadosClustersHist.png" align="right"
     alt="MIAD" width="523" height="203">

## Contribuciones
Grupo 8: 
Valentina Farkas Sánchez
Oscar Andrés Patiño Patarroyo
Andrés Sierra Urrego
John Edinson Rodríguez Fajardo


## Contacto

Para más información escriba al correo: o.patinop@uniandes.edu.co, v.farkas@uniandes.edu.co, a.sierrau@uniandes.edu.co, je.rodriguezf1@uniandes.edu.co





