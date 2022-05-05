# Prácticas de Periodismo de Datos
## En este repositorio “adelarmm” dentro de la organización “PonteDatos” se encuentran las prácticas elaboradas a lo largo del curso en la asignatura Periodismo de Datos. 

### Índice de contenidos
En este repositorio se incluyen las prácticas de la asignatura de Periodismo de Datos impartida en el doble grado de Periodismo y Humanidades en la universidad Carlos III de Madrid. Contiene:

 
#### Práctica 1


> 1. [practica-1-libre.md](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-1-libre.md)
> 2. [practica-1-TRESCA.md](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-1-tresca.md)

Esta primera tarea consistió en aprender el manejo del lenguaje Markdown en los repositorios de Github, mediante la realización de dos comentarios: uno a libre elección (en mi caso se basó en informaciones estadísticas de el diario *El País* acerca del voto en las zonas rurales de Castilla y León, en un contexto de elecciones autonómicas) y otra pautada por el profesor, sobre el proyecto TRESCA y su estudio sobre el periodismo de datos. 


#### Práctica 2

> [practica-2.md](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-2.md)

En la segunda práctica tuvimos que escribir una noticia propia, a invención, basándonos en un gráfico o infografía de la temática que cada una eligiésemos. En mi caso, basé las informaciones en una infografía del Global Carbon Project, una organización científica que realiza estudios anuales sobre las distintas emisiones de contaminantes por la actividad humana. Yo elegí los datos de 2021 al ser los últimos y más recientes del estudio, pero igualmente los acompañé de una comparativa con la reducción de emisiones del año anterior, habiendo coincidido con los meses más duros de confinamiento y las predicciones del panel de expertos del IPCC para los próximos años. Todo el proyecto fue subido en formato Markdown usando la terminal, con los comandos nano y git add, commit y push, al repositorio de Github. 


#### Práctica 3

En este caso, el trabajo recopila notebooks de Python hechos en clase junto con el profesor para aprender el manejo de librerías especializadas en la visualización de datos, crear un folium que nos permita ver datos en un mapa, gráficos... Individualmente, hemos tenido que incluir en la entrega notas y explicaciones sobre los pasos que hemos ido haciendo durante la clase, a modo de apuntes, además de reflexionar acerca de qué nos faltaba por entender. Todos los archivos, de nuevo, fueron subidos al repositorio personal de Github a través de la terminal. Los archvios que comprende son: 


>  - [practica-3.md](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-3/Practica-3.md)
>  - [probando-con-R.html](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-3/probando-con-R.html)
>  - [probando-con-R.ipynb](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-3/probando-con-R.html)
>  - [api-pandas-folium.html](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-3/api-pandas-folium.html)
>  - [api-pandas-folium.ipynb](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-3/api-pandas-folium.ipynb)
>  - [python-api-covid19-pandas.html](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-3/python-api-covid19-pandas.html)
>  - [python-api-covid19-pandas.ipynb](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-3/python-api-covid19-pandas.ipynb)
>  - [esvsit.png](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-3/esvsit.png)
>  - [esvsit.csv](https://github.com/adelarmm/repositorio-adelariesco/blob/main/practica-3/esvsit.csv)


#### Práctica 4

La tarea que pone el broche final a la asignatura supone una continuación de la anterior. En este caso, se nos encomendó elaborar un Notebook que demostrase los conocimientos adquiridos en las clases sobre `pandas`y `matplotlib` con unos contenidos elegidos libremente, así como su forma de visualizarlos. Estos han sido sus archivos:

>  - [practica-4.md](https://github.com/Pontedatos/adelarmm/blob/main/practica-4.md)
>  - [practica-4.html](https://github.com/Pontedatos/adelarmm/blob/main/practica-4.html)
>  - [practica-4.ipynb](https://github.com/Pontedatos/adelarmm/blob/main/practica-4.ipynb)
>  - [practica-4.csv](https://github.com/Pontedatos/adelarmm/blob/main/practica-4.csv)


### Metodología 


#### Creación del repositorio en Pontedatos

Para esta entrega final se nos requería subir todos los archivos sin carpetas a un nuevo repositorio que crearíamos en la organización *Pontedatos*, propiedad del profesor. Para ello desde mi cuenta de Github, y con permiso aceptado del profesor para acceder a la organización, pude crear este repositorio con mi nombre de usuario. A partir de entonces todo mi trabajo se realizó desde la terminal.

#### Subida de archivos

Con todos los archivos que necesitaba subir descargados, el punto de partida fue clonar el repositorio nuevo en mi directorio local utilizando los comandos de la terminal. Con `cd` accedí al escritorio, el sitio en el que quise clonar "adelarmm". Una vez allí hice `git clone` junto a la dirección URL del repositorio en cuestión y así ya pude empezar a mover los archivos que deseaba desde mi ordenador hasta el repositorio Git. Después de listar con `ls` la carpeta en la que los tenía para ver si estaba todo correcto, comencé a moverlos a la carpeta del repositorio con el comando `mv`. Una vez hecho el traslado, listo en el repositorio y compruebo que está todo pasado. Ejecuté el comando `git add` para añadir, en efecto, los archivos. Con `git commit`comiteé los cambios y añadí un breve texto descriptivo del formato del conjunto de los archivos. Finalmente, con `git status` meto mis credenciales (usuario y token generado en el momento) y la subida ya está efectuada. 


#### Archivos README.md y resumen.md

Una vez con todos los archivos de las prácticas previas dentro de la carpeta, he procedido a editar el "README.md" que explica todos los archivos que guarda este repositorio y esta misma explicación metodológica sobre cómo subirlos, a través de `nano`, el editor de texto de la terminal. También he creado el archivo "resumen.md" donde debíamos especificar todo lo aprendido durante el curso.
