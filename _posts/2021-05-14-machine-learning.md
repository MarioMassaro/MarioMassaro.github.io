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
 
Para esta guia en el tratamiento de imagenes utilizamos Roboflow, esta pagina facilita bastante todo el proceso y te ayuda hasta a descargar el formato de las imagenes en formato Yolov5, que esta de mas decir que nos facilita aun mas la creacion de nuestro modelo, por lo que queria darle un apartado especial a esta maravillosa pagina.

