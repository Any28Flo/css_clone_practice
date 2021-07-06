#  HTML y CSS

## Introducción

A todo el mundo le gusta la música, ¿verdad? Lo más probable es que, si lo haces haya oído hablar de ** Spotify **.

Crearemos una versión simplificada de la página de inicio de Spotify:


![Spotify image](https://i.imgur.com/xVD0bm6.jpg)


<br>

Ya se proporcionan todos los recursos e imágenes necesarios. También puede resultarle útil recurrir a la **[full-length PDF version of the website](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/spotify-prototype.pdf)** como referencia.

## Requisitos

- Haz fork de  este repositorio
- Clona este repositorio

## Envío

Al finalizar, ejecute los siguientes comandos:

```shell
$ git add .
$ git commit -m "done"
$ git push origin master
```

Cree Pull Request para que sus maestros puedan verificar el trabajo.

## Instrucciones

Se le proporcionan algunos recursos: en la carpeta `images`, encontrará las imágenes necesarias y el texto está listo para usted en el archivo` index.html`. Escriba su código HTML y CSS en los archivos `index.html` y` styles / style.css`, respectivamente. Recuerde seguir las mejores prácticas.

La página está dividida en 4 secciones, ¡y la hemos cortado generosamente en pedazos!


In general, website designs don't just come out the wild, so you will most likely be having mockups/sketches that you will have to integrate. It is a good practice to help you out before coding to cut the website into pieces in order to help you out _**structuring**_ your HTML.
:muscle: :muscle: :muscle:

<br>

![](https://res.cloudinary.com/ihwebdeb/image/upload/v1571085836/Ironhack/spotify-prototype_1x_ahk8ep.jpg)

Let's do this!


### Iteración 1: barra de navegación

- La barra de navegación debe ser `position: fixed`.
- Alinee el logo a la izquierda y el `ul` con los enlaces a la derecha, ya sea usando` float` o `flex`.

### Iteración 2: Fondo de imagen grande con texto

- Consulte[esta guia](https://css-tricks.com/centering-css-complete-guide/) sobre cómo centrar las cosas.

### Iteración 3: Qué hay en la sección de Spotify

- Parece que los `div`s ocupan aproximadamente un tercio del contenedor cada uno. ¿Cómo puedes representar esto en código?

### Iteración 4: La sección verde

- Parece que tenemos 2 secciones principales, un elemento contenedor con el texto que fluye de arriba a abajo y la imagen del reproductor de Spotify a la derecha.
- Coloque el logotipo de Spotify absolutamente de acuerdo con el _green_ `div`.

¡Happy Coding! :corazón:
