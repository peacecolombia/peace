# PEACE: Plataforma de Estudios y Analisis sobre Colombia y sus Ecosistemicas

Este repositorio contiene todos los archivos relacionados con la pagina web de la iniciativa PEACE.
Para descargar este repositorio, debe tener [git](https://git-scm.com/) instalado en su computador, en la 
consola debe escribir el comando

```
git clone https://github.com/peacecolombia/peace.git
``` 

## Como contribuir a la página web?
Una vez tenga todos los archivos de la página web, puede hacer cambios localmente en su computador. La pagina se genera
utilizando el programa [jekyll](https://jekyllrb.com/). Con el comando `jekyll serve` puede generar localmente una 
versión de la página para verificar que los cambios se han hecho correctamente. Posteriormente puede hacer un [pull request](https://help.github.com/articles/about-pull-requests/).


## Estructura
Este repositorio tiene dos ramas (branches), `master` y `sources`. Todos los archivos con el código fuente estan 
guardados en `sources` y la página web compilada esta en `master`. Para hacer cambios a la página web, 
debe cambiarse a `sources` usando el comando `git branch sources`. Allí se hacen cambios y se genera la 
página con los comandos `git serve` o `git build`. Estos archivos se guardan automáticamente en la 
carpeta `_site`, la cual es ignorada en `sources` en el archivo `.gitignore`. 
Los cambios al código fuente pueden actualizarse en el repositorio con la secuencia:

```
git add .
git commit -m "Changes to source code"
git push origin sources
```

Ahora solo necesitamos actualizar `master` para que la página se actualize en el servidor. Para esto:

```
cd _site
git add .
git commit -m "Changes to website files"
git push origin master
```


## Contacto
En caso de preguntas o sugerencias, contactar a Veronika Ceballos <vceball@bgc-jena.mpg.de> o Carlos Sierra <csierra@bgc-jena.mpg.de>.

