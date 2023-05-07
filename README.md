# Pagina "Oficial" de TADP UTN FRBA

[![CircleCI](https://circleci.com/gh/tadp-utn-frba/tadp-utn-frba.github.io.svg?style=svg)](https://circleci.com/gh/tadp-utn-frba/tadp-utn-frba.github.io)

## Requisitos

* Jekyll
* Ruby 3+

## Como modificar la página?

Para poder modificar la página localmente se puede hacer mediante jekyll. Para instalar Jekyll referirse a este [link](http://jekyllrb.com/docs/installation/)

Una vez instalado jekyll se puede levantar una instancia local desde el directorio raiz ejecutando la siguiente línea.

```
bundle exec jekyll serve
```

De ahi se puede modificar el proyecto con cualquier editor o IDE de preferencia. jekyll tiene un watcher que ante el menor cambio en un
archivo se actualice estos cambios en la página que se esta sirviendo. En caso de modificar algo del _config.yml directamente habrá que
volver a levantar la instancia de nuevo.

Esta página tiene un blog, por lo que se puede agregar posts en caso de que se desee comunicar algo o publicar algo en la página.
Para este caso se necesita crear una entrada dentro de la carpeta _posts, una vez definido un archivo markdown (.md), simplemente
se puede usar notación markdown o html. La página actualmente tiene la infraestructura para formatear los posts y existe una sección
dedicada a estas entradas de blog, en /blog.

## Ya modifique algo de la página, solo pusheo?

No, lo mejor sería que se maneje todas las modificaciones de la página mediante Pull Requests, a menos que sea algo
realmente chico y no muy relevante

## No me animo o no tengo ganas de modificar la página pero quiero proponer un cambio. Qué Hago?

Se puede abrir un nuevo issue y de ahi alguien lo tome para hacer los cambios que se propongan.
