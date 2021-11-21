---
title: "Langues"
date: 2021-10-11T15:23:02+02:00
draft: false

---

## Publication en plusieurs langues.

Hugo vous permet d'avoir la page disponible en plusieurs langues. Le contenu de chaque langue est différent et doit être défini, à la fois les langues choisies et ce que chacune contient. Ceci, comme il faut le supposer, signifie que ce n'est pas le site qui effectue les traductions d'une langue à l'autre, mais plutôt que le site est fait par le site. Cette partie est commune à tous les templates hugo.
Pour pouvoir publier en plusieurs langues, la première chose à faire est de modifier le fichier * config.toml * qui se trouve à l'intérieur de la page hugo sur laquelle vous travaillez. Pas dans le sujet. Nous faisons cela pour qu'un menu déroulant apparaisse avec les différentes options de langue disponibles.

### Fonctionnalité ou comment ça marche.

La façon dont cela fonctionne pour l'utilisateur est très simple et intuitive, je fais ici référence au modèle d'apprentissage. Un menu déroulant apparaît dans la barre de gauche avec les langues disponibles.
### Différentes façons de le faire.

Une façon est de versionner le nom du fichier, c'est-à-dire que vous créez un fichier pour chaque langue, l'autre est de traduire le contenu en créant, pour cela nous utilisons
variables.

#### Versionnage du nom de fichier

Dans ce cas, il s'agit d'ajouter le code de la langue que l'on veut mettre entre le nom du fichier et le nom de l'extension entre des points.

     1.- /content/idiomas.es.md
     2.- /content/idiomas.en.md
Le premier fichier est attribué à la langue espagnole et ce sera ce qui sera affiché lorsque nous sélectionnerons cette langue dans le menu des langues. Le second est attribué à l'anglais et sera affiché lors de la sélection de cette langue. Les deux sont liés l'un à l'autre.

### Bibliographie et plus d'informations.

* Notes de cours. [Docsy de Manuel] (https://malejandror.github.io/staticSite/es/docs/teoria/multilenguaje/)
* Manuel de [Hugo] (https://gohugo.io/content-management/multilingual/)