---
title: "Proyecto de Reconocimiento de Objetos, imagenes y videos"
excerpt_separator: "<!--more-->"
categories:
  - Post Formats
tags:
  - Post Formats
  - readability
  - standard
---

# Modelo de deteccion de objetos a tiempo real

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/ia.jpeg" alt="">
</figure> 

<!--more-->

### Para este proyecto cree una guia personal de como utilizar el modelo Pre-Entrenado de YoloV5
Me vino la necesidad de crear mi propia guia cuando intente hacer mi proyecto y necesite utilizar multiples videos,blogs y recursos para lograr entender su uso, con esta guia podras aprender a utilizar YoloV5, donde te enseño:

    -Extraccion de imagenes (desde el coco dataset y google images)
    -Renombre de imagenes extraidas
    -Division de carpetas (Train, Test, Validation)
    -Tratamiento de imagenes personalizadas para su uso en el modelo (creacion de labels)
    -Utilizacion del modelo y guardado del modelo entrenado para uso futuro
 
#### para explicar todo este contenido se creo una carpeta orgnaizada por partes que deberas seguir para hacer tu propio proyecto de deteccion de objetos 

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/machine-1.JPG" alt="">
</figure> 

Dentro de la carpeta instrucciones podremos encontrar todos los pasos detallados para este proyecto.

#### respecto a la extraccion de imagenes

tenemos dos formas, extrayendolas de google imagenes con un codigo que ya tengo creado y explicado que se conecta a la api de google, o descargamos desde la api del coco dataset 

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/machine-2.JPG" alt="">
</figure> 

Es muy facil de usar y buscar el contenido exacto que necesitas.

#### tratamiento  y division nunca han podido ser mas faciles gracias a roboflow

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/machine-3.JPG" alt="">
</figure> 

esta pagina es una completa salvavidas en cuanto a preprocesado de imagenes, facilita mucho los procesos de encuadrado de imagenes y te ayuda hasta a descargar el formato de las imagenes en formato Yolov5, que esta de mas decir que nos facilita aun mas la creacion de nuestro modelo.

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/machine-4.JPG" alt="">
</figure> 

#### por ultima para utilizar el modelo les dejo creado un google colab con todo el codigo necesario para su uso

desde como cargar sus datos a como ver los resultados del modelo.

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/machine-5.JPG" alt="">
</figure> 

por ultimo me gustaria que buscaran las reglas basicas de como encuadrar las imagenes, ya que si este proceso se hace erroneamente por almenos un poco, el modelo sufrira en precision y no sera tan util como deberia.


Muchas gracias por leer este articulo y aqui les dejo el enlace a la guia de mi GitHub para que la puedan probar por ustedes mismos:

  - https://github.com/MarioMassaro/Object-Deteccion-With-Yolo
