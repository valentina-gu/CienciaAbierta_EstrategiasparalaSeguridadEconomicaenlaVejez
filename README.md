---
title:"Readme: Estrategias para la seguridad económica en la vejez"

date: "31-07-2020"
output: html_document

---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Estrategias para la seguridad económica en la vejez

<br>

En Chile, la cobertura de las jubilaciones se estructura bajo un sistema de capitalización individual (Administradora de Fondos de Pensiones), creado durante la dictadura de Augusto Pinochet, que consiste en el ahorro de ingresos individuales administrado por instituciones financieras privadas en pos de generar utilidades. Sin embargo, las dificultades de empleo e ingresos se terminan por acarrear irremediablemente hasta la vejez y, por ende, estas no logran solucionar de raíz las desigualdades propias del sistema.

<br>

En virtud de ello, la presente investigación busca dar cuenta de las diferentes estrategias empleadas por individuos en edad de jubilación para alcanzar la seguridad económica -o, según el caso, las condiciones mínimas de supervivencia- acorde a su posición de género y de clase, en las comunas de Lo Barnechea y Pedro Aguirre Cerda. El objetivo de la investigación es identificar las diferencias entre las tendencias de utilización de estrategias económicas en la vejez según género y clase social en Santiago en 2018. Con este fin, la pregunta de investigación es la siguiente: ¿Cuáles son las diferencias en las tendencias de uso de estrategias económicas durante la vejez según género y clase social en Santiago, 2018?

<br>

Para su realización, se utilizó un cuestionario online (Google Form) de 43 preguntas dividido en un primer ítem de caracterización sociodemográfica y luego en cinco ítemes más, correspondientes a cada una de las dimensiones. La muestra seleccionada, y finalmente lograda, estuvo compuesta por personas desde los 60 (mujeres) y los 65 años (hombres), que residen en las comunas de Las Condes, en representación de la clase alta, y Pedro Aguirre Cerda, en representación de la clase baja. Esta muestra estuvo constituida por 60 personas, en donde 30 pertenecen a cada comuna y, dentro de cada comuna, 15 de los encuestados fueron hombres y otras 15, mujeres. 

<br>

## a. Índice del paper: Estrategias para la Seguridad Económica en la Vejez

<br>

- 1.Introducción

- 2.Antecedentes

     - 2.2.Redes Sociales
              
     - 2.3.Seguridad económica
              
     - 2.2.Género
              
- 3.Descripción general de la investigación

- 4.Metodología y reporte de terreno

- 5.Análisis descriptivos univariados de las variables

     - 5.1. Análisis descriptivos univariados de las variables
	
- 6.Testeo de hipótesis

     - 6.1. Hipótesis teórica 1: Estrategias según clase social.
Interpretaciones hipótesis teórica 1

     - 6.2 Hipótesis teórica 2: Estrategias según género. Interpretación hipótesis teórica 2

     - 6.3. Hipótesis teórica 3: Estrategias según clase social y género. Interpretación hipótesis teórica 3

- 7.Conclusiones

- Referencias

<br>
 
## b. ¿Por qué el proyecto es útil?

<br>

La pertinencia de esta investigación se sostiene en la necesidad de mostrar la existencia de variables estratificadoras que se acumulan a lo largo del trayecto de vida de los individuos y, con ello, poder contrarrestar la invisibilización de la situación de los adultos mayores en Chile, sobre todo teniendo en consideración las transformaciones demográficas que se están produciendo en el país, dentro de las cuales se destaca el creciente envejecimiento poblacional que, además, posee un carácter eminentemente femenino .  

<br>

El aporte específico que este trabajo realiza al campo de estudio radica en, por un lado, continuar los esfuerzos investigativos ya realizados en torno a las estrategias económicas en la vejez y, por otro, ofrecer un análisis más explícito del contraste que se produce entre clases en Chile, en la medida en que, mientras la mayoría de los trabajos revisado en los antecedentes realizan una mirada más general y se centran casi en su totalidad en los sectores más empobrecidos, esta investigación pone en contacto las estrategias empleadas tanto por un sector de la clase baja, como por uno de la clase alta, enriqueciendo la producción de conocimiento respecto al tema. 
<br>

## c. Organización de archivos en carpetas

<br>

-**input**:  información externa a la investigación.

  - bib: bibliografía
 	 
       -apa: formato APA para la bibliografía
       
       -referencias: referencias para el archivo paper
       
  - data: bases de datos
   
       -original
       
             - data: base de datos original (en formato excel)
       -proc
       
             - data2: base de datos  que se ocupara para el análisis (formato R). 
             
-**processing**:  preparación de datos

  - preparación_estrategias para la seguridad económica en la vejez: Limpieza base de datos
   
  - análisis_estrategias para la seguridad económica en la vejez: Pruebas de hipótesis (test de
    D de Cohen, Test de Welch y Test de Leven), gráficos y tablas.   
    
-**output**:  tablas, gráficos y otros elementos que fueron producidos mediante el manejo de datos. Para esta investigación esta carpeta es redundante, debido a que tablas y gráficos se encuentran en el archivo Rmd de análisis.Por  lo que a pesar de corresponder al protocolo, decidimos no ponerla. 

-**readme.doc** : archivo general de introducción

-**Estrategias_para_la_seguridad_economica_en_la_vejez** : el artículo/paper final.

-**proyecto_ciencia_abierta** : archivo r.project

<br>

## d. Contacto autoras de la investigación

<br>

El presente informe fue abordado, en primera instancia, por estudiantes de tercer año de sociología de la Universidad de Chile. Ahora bien, el tratamiento que se le dio, tal y como fue presentado, con miras hacia su accesibilidad y reproducibilidad, es atribuible al trabajo colaborativo de Josefina Carrasco, Isidora Didier, Valentina González, Karen Tapia y  Martina Silva; estudiantes de la carrera de sociología de la Universidad de Chile y actuales contribuidoras del conocimiento en la materia.

<br>

En caso de tener alguna duda o consulta, tanto sobre el tratamiento de los datos en R como de la información entregada en el informe, es posible contactarse con las autoras mediante correo electrónico, indicados a continuación.

<br>

Josefina Carrasco: josefina.carrasco@ug.uchile.cl
<br>
Isidora Didier: isidora.didier@ug.uchile.cl
<br>
Valentina González: vale5544@gmail.com
<br>
Karen Tapia: karentsepulveda@gmail.com
<br>
Martina Silva: martina.silva@ug.uchile.cl
<br>
