# Accesibilidad a parques urbanos en el cantón de Heredia, Costa Rica

## Descripción general del tema

Las áreas verdes urbanas constituyen un elemento fundamental dentro de la planificación territorial de las ciudades contemporáneas. Espacios como parques, plazas y zonas recreativas contribuyen significativamente al bienestar físico y mental de la población, además de desempeñar funciones ecológicas relevantes dentro del paisaje urbano. Entre sus principales beneficios se encuentran la regulación microclimática, la mejora de la calidad del aire, la reducción del efecto de isla de calor y la provisión de espacios para la recreación y la interacción social.

En este contexto, el análisis de la *accesibilidad espacial* a parques urbanos se ha convertido en una herramienta importante dentro de los estudios geográficos y de planificación urbana. La accesibilidad puede entenderse como la facilidad con la cual las personas pueden llegar a un determinado servicio o infraestructura desde su lugar de residencia. En el caso de los parques urbanos, una adecuada distribución espacial permite que una mayor proporción de la población pueda acceder a estos espacios en distancias razonables.

El presente proyecto tiene como objetivo explorar la distribución espacial de los parques urbanos en el cantón de Heredia, Costa Rica, y analizar de manera preliminar su accesibilidad territorial mediante el uso de herramientas de **Sistemas de Información Geográfica (SIG)**. A partir de datos geoespaciales disponibles públicamente, se pretende identificar patrones espaciales en la localización de estos espacios recreativos y evaluar si existen zonas del cantón con menor disponibilidad de áreas verdes.

El análisis se desarrollará mediante el uso de datos geográficos vectoriales, principalmente en formatos como *Shapefile* y *GeoJSON*, los cuales permiten representar entidades espaciales como puntos, líneas y polígonos dentro de un sistema de coordenadas geográficas.

## Área de estudio

El área de estudio corresponde al cantón de Heredia, ubicado en la provincia del mismo nombre en Costa Rica. Este cantón forma parte de la Gran Área Metropolitana (GAM), una región caracterizada por un alto grado de urbanización y una importante concentración de población.

Heredia presenta una combinación de zonas urbanas consolidadas, áreas residenciales en expansión y algunos espacios verdes urbanos distribuidos en distintos distritos. Debido al crecimiento urbano experimentado en las últimas décadas, resulta pertinente analizar cómo se distribuyen espacialmente los parques urbanos dentro del cantón y si su localización responde a criterios de accesibilidad para la población.

![Cantón de Heredia](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/Costa_Rica_-_Heredia_-_Heredia.svg/500px-Costa_Rica_-_Heredia_-_Heredia.svg.png)

Fuente: Wikimedia Commons

## Datos geoespaciales utilizados

Para el desarrollo de este proyecto se utilizarán distintos conjuntos de datos geoespaciales provenientes de fuentes abiertas. Estos datos permiten representar espacialmente la ubicación de parques urbanos, así como los límites administrativos del cantón de Heredia.

Los principales conjuntos de datos utilizados incluyen:

- Localización de parques urbanos
- Límites administrativos del cantón de Heredia
- Red vial urbana
- Datos poblacionales agregados por distrito (cuando estén disponibles)

Los datos de parques urbanos pueden obtenerse a partir de la plataforma **OpenStreetMap**, un proyecto colaborativo que permite acceder a información geográfica abierta de todo el mundo.

https://www.openstreetmap.org

Asimismo, los límites administrativos y otros conjuntos de datos territoriales pueden obtenerse desde el **Sistema Nacional de Información Territorial de Costa Rica (SNIT)**:

https://www.snitcr.go.cr

Los formatos geográficos utilizados para este proyecto incluyen:

1. **Shapefile (.shp)**  
2. **GeoJSON (.geojson)**  
3. **GeoPackage (.gpkg)**  

Estos formatos permiten almacenar geometrías espaciales junto con atributos descriptivos que facilitan su análisis dentro de software SIG como QGIS.

## Variables principales de los datos

Los conjuntos de datos geoespaciales empleados contienen diversas variables o atributos asociados a cada entidad espacial. En el caso de los parques urbanos, algunos de los atributos más relevantes pueden incluir:

- Nombre del parque
- Tipo de área verde
- Ubicación geográfica (coordenadas)
- Distrito en el que se localiza
- Área aproximada del parque

En el caso de los límites administrativos, las variables pueden incluir información como:

- Nombre del cantón
- Nombre del distrito
- Código administrativo
- Área territorial

Estos atributos permiten realizar distintos tipos de análisis espaciales y estadísticos dentro de un entorno SIG.

## Problemas y preguntas de investigación

A partir de los datos geoespaciales disponibles, este proyecto busca explorar algunas preguntas relacionadas con la distribución territorial de los parques urbanos en el cantón de Heredia.

Entre las principales preguntas que se pretende abordar se encuentran:

- ¿Cómo se distribuyen espacialmente los parques urbanos dentro del cantón de Heredia?
- ¿Existen distritos con menor disponibilidad de áreas verdes urbanas?
- ¿Qué zonas del cantón presentan *menor accesibilidad* a parques urbanos?
- ¿La distribución de parques coincide con las zonas de mayor concentración poblacional?

Responder estas preguntas permitirá identificar posibles desigualdades territoriales en el acceso a espacios verdes dentro del cantón.

## Metodología general

El análisis se realizará mediante el uso de herramientas de **Sistemas de Información Geográfica (SIG)**, las cuales permiten integrar, visualizar y analizar información geoespacial proveniente de diferentes fuentes.

Las principales etapas del análisis incluyen:

- Recolección y descarga de datos geoespaciales
- Preparación y limpieza de los datos
- Visualización cartográfica de los parques urbanos
- Análisis de proximidad o distancia a parques
- Identificación de zonas con menor cobertura de áreas verdes

Este proceso permitirá generar mapas temáticos y análisis espaciales que faciliten la interpretación de la accesibilidad a parques urbanos dentro del cantón de Heredia.

## Importancia del estudio

El acceso equitativo a espacios verdes constituye un componente importante dentro del desarrollo urbano sostenible. La disponibilidad de parques urbanos influye directamente en la calidad de vida de la población, al proporcionar espacios para la recreación, el ejercicio físico y el contacto con la naturaleza.

Desde una perspectiva geográfica, los Sistemas de Información Geográfica permiten analizar de manera precisa la distribución espacial de estos espacios y evaluar su relación con variables demográficas y territoriales.

El desarrollo de este proyecto busca demostrar cómo los datos geoespaciales abiertos y las herramientas SIG pueden utilizarse para explorar problemáticas urbanas relacionadas con la planificación territorial y la accesibilidad a servicios urbanos.

## Referencias

OpenStreetMap. (2024). OpenStreetMap. https://www.openstreetmap.org

Sistema Nacional de Información Territorial (SNIT). (2024). Plataforma de datos geoespaciales de Costa Rica. https://www.snitcr.go.cr

Wikimedia Commons. (2024). Heredia in Costa Rica. https://commons.wikimedia.org