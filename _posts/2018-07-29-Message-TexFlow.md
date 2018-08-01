---
layout: post
title: "28-7-2018: Visualizando el mensaje presidencial"
date: 2018-07-29
summary: An approach to the analysis of discourse
description: 
image: /Vigia/img/
image-sm: /Vigia/img/
categories:
  - Politics  
  - Discourse
  - TextMining 
  - Data Visualization
---
### El vaso medio lleno 
Ante una crisis, un mensaje, pero no solo de sustantivos sino de verbos que llaman a la acción a todos los ciudadanos, a los cotidianos de siempre, que lejos de pertenecer a entidades estatales burocraticas de tamñamos increibles (macro o micro), quieren descansar de aquellas y aquellos (representantes políticos) que han aportado (y que aportan) muy poco al país. Así es que deberiamos considerar un análisis más exhuastivo del mensaje empleando algunas de las técnicas de visualización de datos no estructurados.  

<blockquote class="twitter-tweet" data-lang="en"><p lang="es" dir="ltr">Los desafíos que tenemos por delante son enormes. Hemos dado los primeros pasos y ahora nos disponemos a impulsar, con mayor decisión, los cambios que requiere el país. Te necesito a ti y a los 32 millones de peruanos para emprender este gran reto, porque <a href="https://twitter.com/hashtag/LoQueNosUne?src=hash&amp;ref_src=twsrc%5Etfw">#LoQueNosUne</a> es el Perú.</p>&mdash; Martín Vizcarra (@MartinVizcarraC) <a href="https://twitter.com/MartinVizcarraC/status/1023268274300178433?ref_src=twsrc%5Etfw">July 28, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

--- 
### Flujo de las palabras más relevantes en el discurso del presidente Martín Vizcarra 
Según el análisis que nos facilita el aplicativo Voyant-Tools, en el mensaje presidencial existieron 5 palabras que destacaron por su frecuencia de uso. Estas fueron: |país|millones|nacional|corrupción|sistema|. 

<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->
<iframe style='width: 720px; height: 400px;' src='//voyant-tools.org/tool/StreamGraph/?lang=es&stopList=keywords-13c83ff4cbc0e57ddb8ae730fa9fc270&bins=10&docId=a5cca7ef7b39ab705cfa26e6cb1f92d6&corpus=2f4cd0a4eb79d33ea30e80d4c5761d49'></iframe>

Como observamos en la imagen la palabra país se mantuvo como un flujo continuo a lo largo de los segmento del mensaje constituyendo un eje sobre la cual descansaron otras dos palabras: nacional y sistema. 

Estas tres referencias constituyeron un argumento que ha eludido las referencias a la palabra Estado justamente para mantener una conexión con todos los ciudadanos. 

Haberse referido al Estado, en estos momentos, donde el descredito de varias de sus instituciones es generalizado, hubiera sido, muy probablemente, contraproducente para el efecto que se obtuvo. 

Este diseño no fue gratuito. Definitivamente fue pensando con cuidado y lo que observamos en la visualización de este texto es justamente aquel diseño del mensaje, identificando la palabra eje sobre la cual se construyo toda la argumentación. 

Otro punto a descatar es la referencia a la palabra millones, que en este contexto, esta referido al prespuesto que se requiere para hacer todas las obras que fueron anunciadas el 28 de julio. 

Como se observa es posible identificar como aparece en magnitud para luego desvanecerse por complejo con lo que estamos frente a la concepción de que el dinero, aunque bastante necesario, no es suficiente. 

--- 
### Transición de las palabras en el texto del mensaje presidencial. 
Una forma dinámica de identificar el flujo de aquellas palabras es a través de esta otra visualización basada en el Arco de Texto. Nos facilita la identificación de las palabras vecinas que acompañan a cada una de las anteriores y de esta forma veremos como se construye la secuencia de los mensajes que tienen un llamado a la acción por parte de los ciudadanos. 

<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->
<iframe style='width: 720px; height: 400px;' src='//voyant-tools.org/tool/TextualArc/?lang=es&stopList=keywords-13c83ff4cbc0e57ddb8ae730fa9fc270&corpus=2f4cd0a4eb79d33ea30e80d4c5761d49'></iframe>
