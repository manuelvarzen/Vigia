---
layout: post
title: "San Isidro, Datos Abiertos para Gobernar"
date: 2018-05-31
categories:
  - Open Data 
  - Open Goverment 
  - Data
  - Goverment 
description: Otra historia de datos abiertos.
image: https://picsum.photos/2000/1200?image=1003
image-sm: https://picsum.photos/2000/1200?image=1003
---

<iframe width="100%" height="520" frameborder="0" src="https://manuelvarzen.carto.com/builder/40bb07aa-696a-40c9-bdab-3bfdad00d2b0/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Uno de los puntos críticos de trabajar con datos, estructurados o no, desde una perspectiva post-positivista; es la formulación de la pregunta que antecede a su exploración. Sin este requisito su gobierno se vuelve caótico y cuando se desea obtener información desde ellos esta es inexistente por que aquellos se encuentran dispersos y fragmentados además de incompletos y retrasados. 

Esta es una situación bastante común a cualquier institución, pública o privada. Sin embargo, existen organizaciones que avanzan y aprenden en el camino; y es justamente esa decisión las que les permite tener un liderazgo en el tema. Como sucede siempre, en la innovación social, hay quienes asumen el riesgo de ir primeros y otros, que quieren viajar, segundos y seguros. 

El caso de la Municipalidad de San Isidro es uno de un grupo pequeño de instituciones públicas que ha iniciado, desde hace algún tiempo atrás, una manera de adoptar el enfoque del gobierno abierto el mismo que guía el gobierno de sus datos abiertos. Así fue que hace un tiempo atrás, con la colaboración de una empresa, consiguieron implantar su [portal de datos abiertos](http://datosabiertos.msi.gob.pe/home). 

Así fue que nos animamos a explorar las posibilidades de sus datos publicados en su portal. Para empezar descargamos dos archivos, [1](http://datosabiertos.msi.gob.pe/dataviews/227114/consolidado-intervenciones-serenazgo-2016/) y [2](http://datosabiertos.msi.gob.pe/dataviews/94606/consolidado-intervenciones-serenazgo-2015/) en formato xlsx vinculados a seguridad ciudadana, los unimos y obtuvimos una versión consolidada. Retiramos las filas de datos que tuvieron al menos un dato incompleto. De quince mil registros solo quedaron cerca de mil quinientos aproximadamente. 

Ese fue un paso sencillo. El siguiente fue más complicado, más laborioso y estuvo divido en dos momentos: obtener la geo-localización de los nombres de las calles, es decir, encontrar los valores (numéricos) de latitud y longitud partiendo de información textual; y el segundo, cargar el polígono del distrito para visualizar sus límites. Como se observara logramos hacer ambas cosas. 

Acto seguido, formulamos una pregunta simple: ¿Cuál fue el medio de comunicación mediante el cual se notificaron los eventos vinculados a la seguridad ciudadana? Fue relativamente sencillo encontrar que el teléfono y la radio son los dispositivos más usados. Pero, ¿que es lo que más se informa a través de estos medios? Dos categorías, en primer lugar: "accidentes de tránsito" y "erradicación de mendigos". 

Finalmente, ¿Qué decisiones se pueden adoptar con esta información? Es un próximo nivel de análisis que nos conduce al concepto de la gestión basada en evidencia y que debería ser difundida entre los ciudadanos de una urbanización, ciudad o nación, con la intensión de mejorar las decisiones de los funcionarios públicos que impactan en la vida de millones de personas.