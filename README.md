# Proyecto: Movilidad urbana y productividad económica en ciudades de LATAM
Proyecto Bootcamp - TripleTen

## Objetivo

Identificar las ciudades potenciales para la inversión de la empresa American Development Bank en infraestructura de transporte para el aumento de la productividad y bienestar de la población por medio de la Movilidad Urbana y productividad económica del año 2024.

## Herramientas 

* JUPYTER NOTEBOOK. 
* PHYTON (PANDAS, NUMPY, SEABORN).
* POWER BI.

## Preguntas clave

1. ¿Qué ciudades presentan alta congestión y baja productividad económica?
2. ¿Cuáles muestran los mejores indicadores combinados (movilidad eficiente y economía fuerte)?
3. ¿Qué variables parecen tener una relación más fuerte con el desarrollo urbano?

## Metodología

* Limpieza de datos:
Visualización de los dataset y limpieza de datos (estandarización de nombre de columnas y nombre de países, tipo de datos adecuado).

* Procesamiento de datos:
Filtrado y unión de dataset para mostrar los datos del año 2024.

* Ánalisis de información
Visualización de la relación entre economía y tráfico, resumen ejecutivo. 

## Hallazgos y recomendaciones

#### Hallazgos iniciales:

Montevideo, Uruguay es la cuidad con mayor PIB per cápita y menor congestión. Posicionándose como caso ideal. La infraestructura que posee ayuda al desarrollo de la productividad económica.

La ciudad de México se presenta como un valor extremo, puesto que la congestión es muy alta, en comparación de otros países (~2,833 minutos). Esta ciudad requiere de atención prioritaria. Presenta un alto nivel de PIB pero también de tráfico. Es una oportunidad de inversión, el mejorar las vías podrían aumentar significativamente los ingresos del PIB.

Las ciudades de Buenos Aires y Sao Paulo serían las ciudades con un PIB alto y una congestión vial moderada, por lo que serían las segundas en tener prioridad.

Lima tienen un alto PIB, y una baja congestión por lo que se podría replicar casos de éxito de Montevideo, para bajar sus índices de tráfico.

Otra ciudad para mejora es Bogota, puesto que tiene un PIB alto, pero su tráfico es considero como moderado, por lo que se podrían tener mejorar para bajar el índice de congestión, y aumentar su PIB.

Para Salvador su tráfico es alto, en relativa al total de PIB que produce.

Brasil tiene un Outlier en la gráfica de boxplot, por lo que es importante analizar los datos de las ciudades de este país. Muestra una gran variabilidad con valores extremos. Su rango es aproximado entre los 100 a los 1700 minutos. Teniendo que la mayoría de las ciudades tienen congestión moderada.

Colombia, Argentina, Peru y Chile se establecen como datos están dentro de la media.

Pocos de los países tienen un PIB per Cápita entre los 10,000 y los 12000 dólares.

Algunas ciudades con PIB per cápita están entre los 15000 y los 18000 dólares.

Se aprecia un sesgo hacia la derecha.

#### Recomendaciones:

La infraestructura vial que tiene Montevideo es por medio de 4 carreteras centrales que conecta a sus diferentes ciudades externas al centro de la cuidad, la planeación territorial es estructurada y consistente para tener una movilidad exitosa, al igual que el tamaño de dicha cuidad no es grande, por lo que se puede tener un control territorial del crecimiento.

Para México, Lima y Bogotá recomendaría hacer la construcción de vialidades centrales que conecten las ciudades de gran impacto en el PIB. Ciudades con una población grande para mejorar la conectividad y el derrame económico.

Para Buenos Aires, Sao Paulo revisaría las políticas de transporte para adaptarlas en funcionalidad de la cuidad y del crecimiento de esta.

El Salvador es grande territorialmente, por lo que buscaría el transporte y la distribución de carreteras que mejor abarque la extensión territorial, Al igual que las políticas de transporte.

Brasil cuenta con patrones diferentes entre el PIB y la congestión, esto debido a los usos de suelo, infraestructura vial, condiciones territoriales como topografías, la especialización económica entre las ciudades.

Para la medición ROI se calcularía el valor económico del tiempo por medio de los índices del tráfico en los 10 kms y el PIB per cápita. Se observaría la diferencia entre el valor de PIB antes de la mejora y después de la mejora, al igual que el tiempo de retraso de congestión bajarla con al menos un 10% del actual. Se podría calcular de la siguiente forma: ROI = (Beneficio Económico Anual - Costo de Inversión) / Costo de Inversión x 100. Se estimaría conforme al número de personas que beneficia directamente la nueva infraestructura.


## Diccionario de datos
 
 #### *Movilidad urbana:*

   * Nombre del dataset: tomtom_traffic.csv

   * Descripción: Datos sobre congestión vehicular y condiciones de tráfico en ciudades del mundo. Se registra información sobre niveles de tráfico y congestión en tiempo real en distintas ciudades monitoreadas por TomTom, una empresa global de geolocalización. Cada registro corresponde a una actualización puntual del estado del tráfico en una ciudad.

   * Campos


<img width="923" height="313" alt="image" src="https://github.com/user-attachments/assets/eba54864-1044-4759-85c4-4a2da01e3fbb" />



#### *Economía urbana:* 

 * Nombre del dataset: oecd_city_economy.csv

 * Descripción: Contiene indicadores anuales sobre economía urbana, empleo, contaminación y población recopilados por la OECD (Organización para la Cooperación y el Desarrollo Económicos). Cada registro representa una ciudad en un año específico, lo que permite comparar niveles de productividad y desarrollo urbano entre países.
Indicadores económicos y ambientales por ciudad, recopilados por la OECD (Organización para la Cooperación y el Desarrollo Económico). 

 * Campos


<img width="1165" height="217" alt="image" src="https://github.com/user-attachments/assets/76529c47-d505-482e-adbc-329a69025309" />

