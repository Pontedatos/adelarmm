# EXAMEN FINAL TEÓRICO
## Estas son las respuestas del examen teórico final de Periodismo de Datos, elaborado por Adela Riesco Miranda


### BLOQUE C

- ¿Cómo creamos un directorio? Si quisiéramos crear dos directorios, ¿podríamos hacerlo de una sola vez? Razona tu respuesta

Un directorio es una carpeta; un “contenedor virtual” donde podemos agrupar archivos informáticos almacenados en él u otros subdirectorios o subcarpetas. Con la terminal, podemos crear un directorio en nuestro ordenador con el comando `mkdir`, que aprendimos en clase. Solamente tendríamos que escribir `mkdir nombredelacarpeta` estando ya ubicados en el directorio actual en el que queramos ubicar ese directorio. 

Si quisiésemos crear dos directorios a la vez (dos directorios independientes e iguales en jerarquía) solo tendríamos que utilizar ese mismo comando `mkdir carpeta1 carpeta2`, separando con un espacio el nombre de cada carpeta. Si, por el contrario, quisiésemos crear uno dentro de otro anidados, el comando que usaremos será: 
`mkdir -p nombredirectorio//{subdirectorio1,subdirectorio2}`

- ¿Cómo vemos los archivos y directorios ocultos al listar un directorio?
Para listar los archivos y directorios ocultos tenemos que usar el comando `ls` con el parámetro `-a` o `-la`. 


- ¿En qué se diferencian las rutas absolutas de las relativas? Pon ejemplos de ambas.
La ruta absoluta de un archivo es aquella en la que indico toda la ruta de este, incluyendo el directorio raíz. Por ejemplo, si quiero abrir una carpeta llamada **Adela** guardada en mi escritorio, su ruta relativa hasta ella será `cd /mnt/c/Users/Adela\Riesco\Miranda/Desktop/Adela`.

La ruta relativa es aquella en la que partimos desde donde estamos situados en ese momento, sin incluir el directorio raíz, porque ya no me encuentro ahí. Me explico: si quisiese ir a la misma carpeta, pero antes he hecho `cd /mnt/c/Users/Adela\Riesco\Miranda/Desktop` y he dado a Enter, me encuentro en Desktop. Y por lo tanto, la ruta que tengo que especificar para acceder a **Adela** desde ahí ya solo sería `cd Adela`. 



- ¿Qué función tiene la almohadilla en Markdown y en un programa de la shell? Razona tu respuesta.
En Markdown, el carácter de almohadilla se utiliza para crear encabezados o títulos, y podemos generar distintos niveles de encabezados agregando más o menos almohadillas. Es precisamente lo que estoy haciendo en este documento, donde **EXAMEN TEÓRICO** sería el título de nivel 1 y **BLOQUE C** un título a nivel 3, al que le preceden 3 almohadillas separadas por un espacio. 

En los archivos de la shell, por el contrario, incluir una almohadilla al comienzo de una línea sirve para incluir comentarios, es decir, texto que no queremos que sea interpretado por el propio Shell. Estas son útiles para documental los pasos que se dan al trabajar en un proceso. 


- ¿Qué es una API? Pon algún ejemplo.
API son unas siglas que responden al nombre de **Access Programming Interface** o interfaz de programación de acceso. Se trata de una especie de “código” que nos permite comunicarnos con la web. Como responde la definición de “interfaz”, las API’s cumplen con la función de intermediar entre la web y nosotros, es el lenguaje que “nos traduce” la web. HTTP es un ejemplo de API. 


- ¿Qué es Markdown?
Markdown es una sintaxis simple o lenguaje de marcas para la edición de textos en aplicaciones informáticas. Se utiliza en editores de texto simple como `nano`, el utilizado para la creación de este examen, o Github, la nube a la que se subirá este documento. Genera documentos en formato `.md`. 


- ¿Que significa TSV?
Significa **Tab Separated Values**, es decir, un tipo de datos *SV, separados por espacios del Tabulador. Fue el tipo de datos *SV más utilizado como herramienta de trabajo con Excel hasta que CSV, **Coma Separated Values** lo sustituyese como el formato más usado. Excel es la aplicación que se utiliza para visualizar y trabajar con este tipo de datos. 





### PREGUNTAS OBLIGATORIAS

- ¿Quién es Philip Meyer?

Philip Meyer fue un periodista estadounidense cuyo trabajo se considera un antecedente del periodismo de datos como tal. Comienza a finales de los años 50 su labor en The Miami Herald, y ya en esos primeros años publica una investigación hecha con cierto análisis estadístico propio del periodismo de datos, al descubrir que un alto porcentaje de la financiación para campañas electorales en su país provenía de las empresas aseguradoras que tan altas tenían sus pólizas a los seguros contra incendios y huracanes.

Otra importante labor periodística la desarrolló en 1967 al investigar qué ocurrió con las 46 personas fallecidas durante unas revueltas de Detroit producidas ese mismo año. Siguiendo un modelo ya usado previamente por la universidad de California, y apoyándose en un gran equipo que incluyó (entre otros) a una programadora informática y análisis propios de las Ciencias Sociales, consiguió finalizar su investigación tres semanas más tarde. 

En definitiva, fue un gran contribuyente al desarrollo de un primigenio periodismo de datos, por entonces denominado también por él mismo **precision journalism** o periodismo de precisión, como oposición a la tendencia periodística que se había dado en su país de un periodismo más literario, al estilo de Truman Capote. 


- ¿Quién fue Florence Nightingale?

Florence Nightingale fue una enfermera británica del siglo XIX y considerada pionera de la enfermería moderna, por crear el primer modelo conceptual de enfermería. Su labor se considera en otros campos como el periodismo de datos, además, una contribución clara al desarrollo de la disciplina de la **visualización**; pilar estructural del periodismo de datos moderno. 


### PREGUNTA DE DESARROLLO
#### ¿Qué formatos de datos hay?
Hay varios formatos existentes, pero los más habituales y que, además, hemos visto en clase son:
- **JSON**. Son un tipo de ficheros que utilizan la sintaxis JS. Sus siglas responden al nombre de *JavaScript Object Notation*. Sus datos aparecen en forma de cadenas de caracteres y son difíciles de leer, pero son el formato que mejor funciona con aplicaciones web, y permiten llevar a cabo funcionalidades más complejas que otros tipos de formato, como el CSV. 
- ***SV**. Como menciono en una pregunta anterior, son ficheros que contienen valores separados por cualquier valor, como el espacio del Tabulador o por comas, en el caso del formato CSV. Es un formato más sencillo que el JSON que antes comentamos y, probablemente por ello, el formato más utilizado en los catálogos de Datos Abiertos de la mayoría de instituciones, para cumplir con su propósito de transparencia y que estos datos, al estar en este formato, sean manejables para la mayor cantidad de personas posible. Se visualizan como una tabla simple, en la que se distinguen filas y columnas. 
- **XML**. Es el *eXtensible Markup Languaje* o lenguaje de marcas extensible. Es el tipo más completo de los tres presentados, y por eso no hemos tratado con él en esta asignatura. Se utiliza mucho en las administraciones públicas y la industria. Proporciona una plataforma para definir elementos, con formato y lenguaje personalizados y por eso es tan complejo de utilizar. Cada archivo XML se divide en dos partes, que son prolog y body. 
- **XLSX**. Son los archivos generados por Excel; el formato correspondiente a esta aplicación. 

