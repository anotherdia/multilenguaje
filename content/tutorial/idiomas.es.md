---
title: "Idiomas"
date: 2021-10-11T11:21:06+02:00
draft: false
weight: 50
---

## Publicando en varios idiomas.

Hugo permite que puedas tener la página disponible en varios idiomas. El contenido de cada idioma es distinto y hay que definilo, tanto los idiomas elegidos como qué contiene cada uno. Esto, como se debería suponer, quiere decir que no es el sito el que realiza las traducciones de un lenguaje a otro sino que lo hace quien realiza la página. Esta parte es común en todas las plantillas de hugo. 
Para poder publicar en varios idiomas lo primero que hay que hacer es modificar el archivo *config.toml* que hay dentro de la página de hugo que estás trabajando. No dentro del tema. Esto lo hacemos para que aparezca un menú desplegable con las diferentes opciones de lenguaje que hay. 

### Funcionalidad o cómo funciona.

La forma de funcionamiento, de cara a la persona ususaria es muy sencilla e intuitiva, aquí me estoy refiriendo a la plantilla de learn. Aparece un menú despleglable en la barra de la izquierda con los idiomas que hay disponibles. 
### Distintas formas de hacerlo.

Una forma es versionando el nombre del fichero, es decir creas un fichero para cada idioma, la otra es traduciendo el contenido creando, para ello usamos 
variables.

#### Versionando el nombre del fichero

En este caso se trata de añadir el código del lenguaje que queremos poner entre el nombre del archivo y el nombre de la extensión entre puntos.

     1.- /content/idiomas.es.md
     2.- /content/idiomas.en.md
El primer archivo está asignado al idioma de español y será lo que se visualice cuando en el menú de idiomas seleccionemos ese idioma. El segundo está asignado al inglés y se mostrará al seleccionar esa lengua. Ambos están linkeados entre sí. 

### Bibliografia y más información.

* Apuntes de clase.[Docsy de Manuel](https://malejandror.github.io/staticSite/es/docs/teoria/multilenguaje/)
* Manual de [Hugo](https://gohugo.io/content-management/multilingual/)
