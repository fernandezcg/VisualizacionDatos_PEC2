Visualización Datos PEC2
================


## Boxplot diagram

El box plot, o diagrama de caja es una técnica que resume la distribución de un conjunto de datos mostrando su mediana, cuartiles y valores atípicos.

Un diagrama de caja resume la distribución de una variable numérica en uno o más grupos, lo que lo convierte en una herramienta conveniente para comprender rápidamente las diferencias entre esos grupos.

__Funcionamiento__:
Un box plot muestra un recuadro que representa el rango intercuartílico (IQR) y una línea que indica la mediana.
También se extiende con líneas (o 'bigotes') para mostrar la variabilidad de los datos.

__Tipos de Datos__:
Datos **cuantitativos**, donde puedes tener múltiples categorías o grupos.

__Ejemplos de Aplicación__:
Son comúnmente utilizados para comparar la distribución de una variable entre diferentes grupos, como en el análisis de resultados académicos por género.

__Limitaciones__:
Pérdida de información importante, no muestra la distribución de los datos por completo, ya que los valores específicos se agrupan en cuartiles.
Una excelente **alternativa es el gráfico de violín**, que ilustra de manera eficaz la distribución de los datos de cada grupo.


__Tableau__: 
https://public.tableau.com/app/profile/c.sar.fern.ndez.garc.a/viz/PEC2_Boxplot/Dashboard1?publish=yes

__Flourish__: 
https://public.flourish.studio/story/2692175/

__Datos__: 

Conjunto de datos de ejercicios de miembros del gimnasio

https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset?resource=download

## Chord diagram

Los chord diagrams son una técnica visual utilizada para mostrar relaciones y conexiones entre diferentes elementos. Fueron popularizados en el análisis de redes y flujos, como en estudios de comercio internacional.

__Funcionamiento__:
En un diagrama de cuerdas, los elementos se representan en un círculo y las conexiones entre ellos se muestran como cuerdas que los unen, permitiendo visualizar las interacciones y flujos.

Este tipo de diagrama visualiza las interrelaciones entre entidades. Las conexiones entre entidades se utilizan para mostrar que comparten algo en común. Esto hace que los diagramas de acordes sean ideales para comparar las similitudes dentro de un conjunto de datos o entre diferentes grupos de datos.

Los nodos se disponen a lo largo de un círculo y las relaciones entre los puntos se conectan entre sí mediante el uso de arcos. Se asignan valores a cada conexión, que se representa proporcionalmente por el tamaño de cada arco. Se puede utilizar el color para agrupar los datos en diferentes categorías, lo que ayuda a realizar comparaciones y distinguir grupos.

__Tipos de Datos__:

Los chord diagrams son adecuados para datos cualitativos y cuantitativos, donde se desea mostrar relaciones entre categorías. Los datos deben ser en forma de pares o matrículas que indiquen conexiones.

__Ejemplos de Aplicación__:
Se utilizan a menudo para mostrar flujos de datos en redes sociales o relaciones comerciales entre países.

__Limitaciones__:
Pueden volverse confusos si hay demasiadas conexiones o elementos, lo que dificulta la interpretación.

__Flourish__:
https://public.flourish.studio/visualisation/20106448/

__R__:
https://fernandezcg.github.io/VisualizacionDatos_PEC2/Chord/PEC2_chord.html

__Datos__:
https://python-graph-gallery.com/chord-diagram-python-chord/
https://onlinelibrary.wiley.com/doi/abs/10.1111/imre.12327

## Cartogram diagram

Los cartogramas son representaciones gráficas en las que las áreas geográficas se distorsionan en función de una variable, como la población o el PIB.

__Funcionamiento__

En un cartograma, los tamaños de los países o regiones se ajustan para reflejar la magnitud de una variable, permitiendo así visualizar de manera efectiva cómo se distribuye ese dato en el espacio geográfico.

Tiene como objetivo corregir el sesgo que se puede observar en un mapa coroplético: cuando una variable se agrega por región, una región con muy pocos puntos de datos parecerá tan importante como una región con muchos puntos de datos. Por ejemplo, imagina que muestras el salario medio por región en tu mapa de coropletas. Una región con 3 habitantes y una superficie enorme tendrá más importancia en tu mapa que una pequeña con 3.000 habitantes, lo que induce un fuerte sesgo.

__Tipos de Datos__
Los cartogramas son adecuados para **datos cuantitativos, especialmente aquellos que tienen una dimensión geográfica**

__Ejemplos de Aplicación__:
Un ejemplo clásico es el uso de cartogramas en elecciones, donde el tamaño de los distritos electorales puede representarse según el número de votos.

__Limitaciones__
Pueden perder detalles geográficos y pueden ser difíciles de interpretar si no se entiende la lógica de la distorsión.

__Datawrapper__:
https://datawrapper.dwcdn.net/5Og4T/5/

__R__:
https://fernandezcg.github.io/VisualizacionDatos_PEC2/Cartogram/PEC2_cartograma.html

__Datos__:
El dataset World está disponible en el paquete tmap

## Recapitulación
En resumen, hemos explorado tres técnicas de visualización: los cartogramas, que permiten representar datos geográficos; los box plots, que resumen la distribución de datos numéricos; y los chord diagrams, que visualizan relaciones entre categorías.
