# COVIDMAPS


1	Título

COVIMAPS

2	Resumen

2.1	Español

COVIMAPS será una aplicación basada en servidores y contenedores, que ofrecerá a sus usuarios información de interés con respecto al SARS-Covid-19, dependiendo de su localización. 


2.2	Inglés

COVIMAPS will be an application based on servers and containers, which will offer its users information of interest regarding the SARS-Covid-19 depending on their location.

3	Palabras clave

3.1	Español

-	SARS-Covid-19
-	Coronavirus
-	Pandemia
-	Mapa
-	Estadísticas 
-	Probabilidad de infección

3.2	Inglés

- SARS-Covid-19
- Coronavirus
- Pandemic
- Map
- Stadistics
- Infection’s probability





4	Problema

En el año 2020 las actividades de la vida cotidiana se vieron interrumpidas debido a la pandemia ocasionada por el brote del virus Sars-Covid-19. Las personas de todo el mundo fueron obligadas al distanciamiento social. Muchas personas permanecen con miedo pues, en ciertas etapas es sumamente complejo saber quién es portador del virus.

5	Justificación

Con el proyecto se busca brindar información a la ciudadanía en relación a la probabilidad que tiene de contagiarse dependiendo de la zona en la que habite, para esto, utilizaremos los datos abiertos proporcionados por el gobierno, que evidencian los casos confirmados y los casos en estudio de cada barrio de la ciudad. 

6	Fundamentación del proyecto

6.1	Objetivo General

Desarrollar una aplicación que permita establecer una probabilidad de contagio con base en los casos confirmados y en estudio, que están cerca de una localización en cuestión.

6.2	Objetivos Específico

- Desarrollo de los servidores y contenedores necesarios para el cumplimiento de los objetivos siguientes, según el criterio y parámetros del docente. 

- Implementar una funcionalidad de registro para que los usuarios puedan acceder a la aplicación. 

- Desarrollar una ventana de login para que se pueda acceder previamente realizado el registro. 

- Desarrollar e implementar una base de datos que contenga la tabla de registro, la tabla de probabilidades y la tabla del mapa interactivo. 
 
- Implementar una vista de mapa de la ciudad de Medellín en donde se graficaran los casos que han sido confirmados y, los que están en estudio.

- Implementar un sistema de estadísticas que funcionará para cada usuario de manera individual, dependiendo de su localización y de los casos confirmados en dicha zona. 

- Unir todos los componentes en una única solución tecnológica. 


6.3	Metodología

Se optará por el trabajo remoto. El desarrollo de la solución tecnológica se basará en un servidor web centralizado y, en un repositorio en github  se tendrá el código de la aplicación que corresponderá al desarrollo de la aplicación móvil.

6.4	Herramientas

FRONTEND: Para el desarrollo de todo lo que sería el frontend de la aplicación se usaran lenguajes de programación como HTML5, CSS3 Y JS, pero, si este tipo de lenguajes son para desarrollo WEB, ¿cómo se realizaría el proceso para que sea una aplicación movil? Apache Cordova nos permite tener un entorno de desarrollo de aplicaciones móviles bajo estos tres lenguajes mencionados anteriormente y, no se tendrá que lidiar los lenguajes nativos de cada sistema operativos, sin embargo, si tiene un par de ajustes a considerar, por tanto, la primera versión sería desarrollada como si fuese para un sistema ANDROID. 

BACKEND: Javascript nos servirá también para desarrollar backend para cosas especificas dentro de la aplicación, sin embargo, el mayor componente de backend será un servidor WEB con base de datos SQL nos permitirá tener las tablas que contienen la información de los contagiados y el porcentaje de riesgo según la zona del usuario. Se implementará la geolocalización (GPS) cuando se ingrese a la pestaña de "Mapa" y, la información allí mostrada (Casos confirmados de contagio por zona, porcentaje de riesgo, etc) se obtendrán de la base de datos contenida en el servidor WEB. Inicialmente implementaremos seguridad básica dentro del servidor, es decir, seguridad por el puerto 80 para que se puedan realizar peticiones a ese servidor. 
