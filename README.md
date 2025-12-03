# Movilidad laboral en Europa: análisis del commuting y las nuevas formas de empleo

Este proyecto analiza la movilidad laboral en Europa utilizando datos oficiales y herramientas de visualización interactivas. El objetivo es transformar datos dispersos en información útil para comprender patrones de desplazamiento al trabajo, dinámicas territoriales y nuevas formas de empleo en el espacio europeo.
Toda la infomarción del análisis y la memoria del proyecto se encuentra en el html generado a partir del archivo "Movilidad laboral en Europa.Rmd"

## Objetivos del proyecto

* Integrar y limpiar datos procedentes de distintas fuentes europeas.
* Analizar patrones de commuting y movilidad laboral.
* Explorar diferencias entre regiones, países y grupos demográficos.
* Crear un dashboard interactivo que permita consultar la información de manera clara y flexible.
* Facilitar la toma de decisiones basada en datos para investigación, docencia o planificación territorial.

## Tecnologías y librerías utilizadas

### Análisis y manipulación de datos

* tidyverse
* openxlsx
* haven
* stringr
* lubridate

### Visualización y dashboard

* flexdashboard
* plotly
* ggplot2
* leaflet
* geojsonio
* htmlwidgets

## Resultados principales

El proyecto incluye un dashboard desde el que es posible:

* Comparar indicadores de movilidad laboral por país o región.
* Analizar la evolución temporal del commuting.
* Visualizar mapas interactivos con distintas capas geográficas.
* Explorar gráficos dinámicos filtrables.

Enlace al servidor shiny ULPGC en la que se aloja en cuadro de mandos: http://10.22.143.222:3838/sample-apps/a2637/MiDashboard.Rmd
Se accede desde la red de la universidad o usando una VPN. Luego de que carge la página, esperar unos segundos a que se muestre completamente la primera página "Vista General".


## Cómo usar el proyecto

1. Clonar el repositorio:
   git clone [https://github.com/tu_usuario/tu_repositorio.git](https://github.com/tu_usuario/tu_repositorio.git)
2. Abrir el proyecto en RStudio.
3. Instalar las librerías necesarias.
4. Ejecutar los scripts del directorio /scripts.
5. Renderizar el dashboard.

## Licencia

Este proyecto se distribuye bajo una licencia libre. Puede modificarse y reutilizarse citando la fuente original.

## Autoría

Proyecto desarrollado en el marco del estudio sobre movilidad laboral en Europa para la asignatura de Análisis Exploratorio de Datos y Visualización del segundo curso del grado en Ciencia e Ingeniería de Datos de la Universidad de Las Palmas de Gran Canaria.

Por Lucas Mendoza Rodríguez.
