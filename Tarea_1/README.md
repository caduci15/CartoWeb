# Bogotá y la inclusión social. 

## 1.	¿Cuál es el problema a tratar?

Bogotá es la ciudad de Colombia que más población acoge en todo el país, por diferentes razones, entre ellas, la principal es que, al ser la capital es el lugar donde más confluyen dinámicas económicas y por ende si se realiza una discriminación de aporte de puntos al PIB por región, Bogotá lleva la delantera; se estima con cifras que el PIB total del país a 2018 ascendía a 985.931, de los cuales 252.511 provenían de la ciudad. *Medido en miles de pesos. 
Así mismo, al ser una ciudad con una dinámica voraz, necesita políticas eficientes para todos sus habitantes, de los cuales el 5,9% corresponde a población en situación de pobreza extrema; y el 12.4% se encuentra en índices de pobreza tasable pero no con índices de NBI apropiados. Esto, llevado a porcentajes, en suma, indica que el 18,3% de la población en Bogotá requiere atención social permanentemente. 

La Alcaldía, consciente de la situación de la población en mención ha puesto en marcha una serie de programas inclusivos que trabajan con población en situación de vulnerabilidad; sin embargo, para un ciudadano que recorra la cuidad a diario parecería no ser suficiente porque constantemente se evidencian las mismas situaciones; esto, se debe más a falta de socialización con los programas existentes y al conocimiento de cada uno, es decir a la masificación de la difusión de información. 

## 2.	¿Por qué los datos geográficos ayudan a resolverlo?

Pareciera casi un dogma que los estratos sociales menos favorecidos son los que más atención social requieren; por tanto, se debería realizar un análisis proporcional a la cantidad de infraestructura disponible para la atención de eventos por zona en función del estrato; además de la cercanía entre un punto de atención y el otro para determinar qué tan útil resulta esto y cuáles zonas quedan desatendidas por la lejanía de centros de atención. 

## 3.	Descripción de la solución propuesta.

La solución que se plantea es recopilar los datos disponibles en el repositorio del DPS, cruzarlos con los estratos socioeconómicos y validar cuáles localidades deben recibir atención de infraestructura, además de la concentración de sitios de atención por localidad. Posteriormente se plantea validar con una capa de uso del suelo cuáles podrían ser las potenciales ubicaciones sobre las cuales el DPS podría poner la mira para realizar adquisiciones inteligentes de predios en función del uso que le sirve a dichos centros. (Dotacional), esto para realizar un primer acercamiento sobre ubicaciones estratégicas de las zonas de atención. 

## 4.	Listado detallado de las fuentes de datos seleccionadas. Mínimo 3 conjuntos de datos. Incluir información del proveedor de los datos, enlace para descarga, título y descripción del conjunto de datos, descripción de los atributos principales a utilizar.

## 5.	Descripción detallada del procesamiento no trivial realizado a los datos (algoritmos, herramientas utilizadas, modelos, etc)
 


<img src="clip.png" alt="clip" width="100"/> 

<img src="seleccion.png" alt="seleccion" width="200"/> 
<img src="kernela.png" alt="kernela" width="200"/> 
<img src="kernelb.png" alt="kernelb" width="200"/>
<img src="kernelc.png" alt="kernelc" width="200"/> 
<img src="kerneld.png" alt="kerneld" width="200"/>  
<img src="kernele.png" alt="kernele" width="200"/> 

<img src="creciendoenfamilia.png" alt="creciendoenfamilia.png" width="400"/>

<img src="proteger.png" alt="proteger.png" width="400"/>

<img src="forjar.png" alt="forjar.png" width="400"/>

<img src="puntosamar.png" alt="puntosamar" width="400"/>

<img src="atencionsocialfocalizada.png" alt="atencionsocialfocalizada.png" width="400"/>

<img src="puntosatencionsocial.png" alt="puntosatencionsocial.png" width="400"/>

<img src="densidadbogota.png" alt="densidadbogota.png" width="400"/>

<img src="ea.png" alt="ea.png" width="400"/>








 
 
 
 
 

## 6.	Descripción detallada de la metodología utilizada para generar los mapas (atributos seleccionadas, métodos de clasificación, colores, etc)

Se realizó inicialmente una depuración de los estratos con un clip, en donde se seleccionaron los estratos 1 y 2 como foco de trabajo. 
Posteriormente se seleccionaron los centros de atención que realizan trabajo social sobre la población y se generó una densidad de tipo kernel para saber cuáles de esas poblaciones están desatendidas, y se realiza el mismo procedimiento con cada centro de atención. 
Después de tener identificados los clústeres de trabajo, se cruza la información con un overlap sobre las manzanas objeto de estudio. 
Finalmente se utiliza una capa que contiene todos los centros de atención y se realiza el mismo análisis de clúster para validar la misma variable en conjunto sobre la ciudad

## 7.	Descripción detallada del procedimiento técnico utilizado para generar los mapas (plugins, extensiones, procesos, transformaciones de datos, etc). Ejemplos de herramientas: Qgiscloud , leaflet, QGIS2Web , Github Pages, kepler.gl, flourish, etc.
Se utilizaron varias herramientas, utilicé en un principio QGIS2web para la publicación de los puntos de atención; utilicé además GitHub para la realización de cargue de datos y Colorbrewer para la asociación de la gama de colores idónea para la realización de las salidas gráficas.

https://stackoverflow.com/questions/14675913/changing-image-size-in-markdown/21972032#21972032

## 8.	Adicionar al repositorio github los archivos generados (ejm. html) en la subcarpeta Tarea_1/html/

## 9.	Urls de los mapas publicados en la web

## 10.	Conclusiones Ventajas / desventajas / dificultades encontradas durante el desarrollo del ejercicio
