---
title: "Crear documentos"
date: 2021-10-10T17:51:59+02:00
draft: false
weight: 20
---

## Creando documentos en hugo.

### ¿Qué pasos hay que seguir?

Para crear documentos dentro de Hugo habrá que tener una carpeta donde alojarlos y dentro de la misma carpeta crear un archivo *_index.html*. De lo contrario se crearán los documentos pero no se visualizarán en la página de Hugo. También hay que tener cuenta la información que aparece en la parte de arriba, tanto del documento como del *_index.html*. En la cabecera de ambos documentos aparece información que nos puede resultar útil. El título, la fecha de creación y si el documento es borrador (draft). Esto último vienen como un booleano. Si el valor que aparece asociado al draft es true, quiere decir que ese documento es un borrador y por lo tanto no aparecerá en la página web. Por lo tanto, para que aparezca como publicado, tendremos que mirar y comprobar que el valor que está asociado al draft, tanto del documento como del _index.html de esa carpeta sea false.

La carpeta se crea al mismo tiempo que se crea el documento con un comando muy sencillo. *hugo new carpeta/nombre_archivo.md* donde *carpeta* es el nombre que tendrá la carpeta, *nombre_archivo* el nombre del archivo que se creará dentro de la carpeta *carpeta* y *.md* la extensión que tendrá dicho archivo. Y con esto ya tenemos los archivos listos para empezar a llenarlos con cosas. En el caso de de este archivo que es el primero que he hecho ha sido así. 

    1.- hugo new tutorial/_index.html
    2.- hugo new tutorial/crear_documentos.md

### Más información sobre las carpetas y archivos de Hugo.

* enlace a desarrolloweb.com[ gestión de contenido.](https://desarrolloweb.com/articulos/generar-contenido-site-hugo)
* enlace a desarrolloweb.com[ markdown.](https://desarrolloweb.com/home/markdown)
* enlace al [docsy de Manuel.](https://malejandror.github.io/staticSite/es/docs/teoria/contenido/) 