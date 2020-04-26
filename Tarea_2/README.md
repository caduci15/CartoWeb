<p align ="center">
  <

# Bogotá y la inclusión social. 

## 1.	¿Cuál es el problema a tratar?

| Insumo       | Descripción          | Fuente  |
| -------------|:-------------:| -----:  |

<p align="center">
  <img src="modelo.png" alt="modelo" width="900"/> 
  <br>Figura 1. Fuente: Propia. <br/>
</p>

1.  Definición del problema 

Estudio de atención a población en situación de calle en Bogotá D.C. 

La población en situación de calle en Bogotá alcanza a ser de casi 7.000 habitantes (DANE, 2017), los cuales representan el 0,9% de la población total de la ciudad; sin embargo, a dcha población se le mantiene en un rezago político-social que no es pertinente ni idóneo pensando que la drogadicción, al igual que otras problemáticas sociales, desencadenan inexorablemente en problemas de salud pública. 

Es por eso, que este estudio, busca por un lado, mapear el último Censo de Habitantes de calle que realizó el DANE en Bogotá (2017) para dar cuenta de la distribución de dichsa población en la ciudad, además busca relacionar cada habitante con un centro u hogar de paso de los once (11) disponibles que tiene el distrito para su atención. Con esto, se busca además evidenciar que los centros existentes no son suficientes para atender dicha población. 

A continuación se listan los centros de atención disponibles para el habitante de calle y la población objeto de estudio según las cifras del censo. 


| CENTRO       | NOMBRE        | DIRECCIÓN     | TELÉFONO      | HORARIO ATENCIÓN |
| -------------|:-------------:|:-------------:|:-------------:|-------------:   |
| 1	           | EL CAMINO - COMUNIDAD DE VIDA	| KR 69 47 87	| 4105461 | LUNES A DOMINGO 24 HORAS |



| 2	           | HOGAR DE PASO DÍA - NOCHE 2 CARRERA 35 | KR 35 10 35	| 2016810	| LUNES A DOMINGO 24 HORAS |
| 3            | CENTRO DE ATENCION TRANSITORIA-CAT | KR 35 10 69 | 2478038 | LUNES A DOMINGO 24 HORAS |
| 4        	   | HOGAR DE PASO DIA - NOCHE 1 BAKATÁ | CL 10 17 15	| 2821859 | LUNES A DOMINGO 24 HORAS |
| 5	           | LA ACADEMIA - CENTRO DE FORMACION PARA EL ESTUDIO	| CL 12 16 73 | 2824921 | LUNES A DOMINGO 8:00 AM - 4:00 PM |
| 6	           | COMUNIDAD DE VIDA ALTA DEPENDENCIA FUNCIONAL	LA MESA VEREDA LA TRINITA	| 3808330 | LUNES A DOMINGO 24 HORAS |
| 7	           | COMUNIDAD DE VIDA RICAURTE | RICAURTE - VEREDA LLANO DEL POZO - HACIENDA YIRED | 3808330	| LUNES A DOMINGO 24 HORAS |
| 8	           | HOGAR DE PASO DÍA NOCHE CRA 13 | 	KR 13 18 36	| 3808330	| LUNES A DOMINGO 24 HORAS |
| 9	           | HOGAR DE PASO CALLE 18 | CL 18 13 47 | 3411186 | LUNES A DOMINGO 24 HORAS |
| 10           | HOGAR DE PASO 5 CASA AZUL - MUJERES DIVERSAS	| CL 24 19 A 35	| 3279797 | LUNES A VIERNES DIURNO 7:00 AM - 7:00 PM - NOCTURNO 7:00 PM - 7:00 AM - DOMINGOS Y FESTIVOS: 7:00 AM - 7:00 PM |
| 11           | HOGAR DE PASO 6 - CARRETEROS	| CL 18 14 36 | 3279797 | LUNES A VIERNES DIURNO 7:00 AM - 7:00 PM - NOCTURNO 7:00 PM - 7:00 AM - DOMINGOS Y FESTIVOS: 7:00 AM - 7:00 PM |

<p align="center">
  <img src="censo.png" alt="censo" width="500"/> 
  <br>Figura 1. Fuente: DANE - Censo Habitantes de Calle, 2017. <br/>
</p>


2.  Fuentes de datos
* Listado detallado de las fuentes de datos seleccionadas. Mínimo 3 conjuntos de datos **vectoriales**. Incluir información del proveedor de los datos, enlace para descarga, título y descripción del conjunto de datos, descripción de los  atributos principales a utilizar.

3. Procesamiento de datos

* Descripción detallada del procesamiento  realizado a los datos (algoritmos, herramientas utilizadas, modelos, etc)
* Idealmente incluir procesos que impliquen la utilización de las relaciones espaciales entre objetos, medidas, distancias y / o generación de geometrías.
* Cargar los datos en el servidor postgresql / postgis asignado para la clase.
* Listar las capas cargadas en el servidor postgresql / postgis (**Nota**: No olvide el prefijo asignado para la clase. Ejm: jc_departamentos )

4. Capa Simbología SLD

* Publicar una de las capas utilizando simbología basada en SLD
* Si utiliza QGIS para generar el SLD, favor mencionar brevemente el proceso realizado. 
* Incluir texto del SLD en el markdown del Readme.md (Ejemplo de clase https://github.com/dersteppenwolf/cartografia_web/tree/master/06_Simbologia) 
* Describir método utilizado para clasificar los datos.
* Describir el criterio para la selección de los colores a utilizar en la simbología
* Las reglas de la simbología deben incluir control de escala y etiquetado. 
* Adjuntar imagen con la leyenda de la capa.

5. Capa Simbología CSS

* Publicar una de las capas utilizando simbología basada en CSS
* Incluir texto del CSS en el markdown del Readme.md (Ejemplo de clase https://github.com/dersteppenwolf/cartografia_web/tree/master/06_Simbologia) 
* Describir método utilizado para clasificar los datos.
* Describir el criterio para la selección de los colores a utilizar en la simbología
* Las reglas de la simbología deben incluir control de escala y etiquetado. 
* Adjuntar imagen con la leyenda de la capa.


6. Capa Simbología YSLD

* Publicar una de las capas utilizando simbología basada en YSLD
* Incluir texto del YSLD en el markdown del Readme.md (Ejemplo de clase https://github.com/dersteppenwolf/cartografia_web/tree/master/06_Simbologia) 
* Describir método utilizado para clasificar los datos.
* Describir el criterio para la selección de los colores a utilizar en la simbología
* Las reglas de la simbología deben incluir control de escala y etiquetado. 
* Adjuntar imagen con la leyenda de la capa.


7. Grupo de capas

* Crear un **layer group** ( https://docs.geoserver.org/stable/en/user/data/webadmin/layergroups.html  ) que contenga las capas creadas en los puntos _4, 5 y 6_ y las adicionales que considere necesarias para darle contexto a la visualización (ejm. límites departamentales, límites municipales, límites internacionales, etc)
* Adjuntar el url de la previsualización _openlayers_ del conjunto de capas generada por Geoserver. Ejemplo: http://34.83.176.208:18080/geoserver/wms?service=WMS&version=1.1.0&request=GetMap&layers=tiger-ny&bbox=-74.047185%2C40.679648%2C-73.907005%2C40.882078&width=531&height=768&srs=EPSG%3A4326&format=application/openlayers 


8.  Conclusiones 

* Publicar un video en Loom ( https://www.loom.com/ ) de mínimo 5 minutos y máximo 8  donde describa brevemente lo siguiente:
* Problema planteado
* Procesamiento y análisis realizado a los datos
* Proceso de publicación de capas 
* Conclusiones del ejercicio desde el punto de vista temático según el problema definido. 
* Tutorial de loom https://support.loom.com/hc/en-us/articles/360006847737-Guide-to-Using-Loom-for-Education
* **Importante**  en el video debe quedar activa la cámara web durante todo el tiempo. Ejemplo: https://www.loom.com/share/9e89602fed3d40ff9cd3b79759ffce50
<img src="img/loom.png" width="600"/>

