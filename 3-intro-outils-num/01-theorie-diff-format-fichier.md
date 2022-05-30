<!-- omit in toc -->
# Différents types de fichiers

L'informatique est remplit de type de fichiers différents, qu'on parle de fichier texte, image, de tableur, de page internet, d'archives,... chacun à son extension! Voyons ensemble quelques uns des formats que l'on va rencontrer pendant ce cette initiation.

<!-- omit in toc -->
## Table des matières

- [Fichier image](#fichier-image)
  - [Résolution d'une image](#résolution-dune-image)
  - [Image Vectorielle vs Matricielle](#image-vectorielle-vs-matricielle)
  - [Formats fichier image](#formats-fichier-image)
    - [Le cas du WebP](#le-cas-du-webp)
  - [Le SVG](#le-svg)
  - [Sources](#sources)

## Fichier image

### Résolution d'une image

Quand on parle de résolution, on parle du nombre de pixels par pouce (ppp ou dpi). Plus cette résolution est élevé, plus l'image sera de bonne qualité. Les deux résolution dont en parle le plus souvent sont **72dpi** ou **300dpi**. 

Lorsqu'on crée des images pour le web, on utilise le 72dpi, ce qui est la norme pour avoir des images de bonne tailles et qualité sans pour autant avoir des fichiers trop volumineux. 

Si on veut imprimer une affiche géante, on va plutôt utiliser une résolution de 300dpi ou plus.

![résolution](./img/01/resolution.jpeg)

[:arrow_up: Revenir au top](#table-des-matières)

### Image Vectorielle vs Matricielle

-**matricielle**: il s'agit d'une image constitué de pixels. Ce sont des petits carrés qui, une fois mis l'un à côté de l'autre, forment une image. Chaque carrés à sa couleur définit. Plus la résolution est élevé plus leur nombre est important et plus l'image sera de meilleur qualité. Si vous déformez cette image, cela va étirer les pixels et vous aurez une image floue.

-**vectorielle**: une image vectorielle est une suite de segment formé par des points qui sont définis par des formules mathématique. N'ayez crainte, pas besoin de savoir faire des maths pour créer des images vectorielles. L'avantage est que chaque élément à sa place et que si on veut agrandir l'image cela aura pour effet de recalculer la position des segments et ainsi conservé la qualité de l'image original. Le vectoriel est ce qu'on utilise pour réaliser des logos qui seront imprimés sur des affiches de plusieurs mètres par exemple.

![vecteur-vs-pixel](img/01/vectorisation-logo.jpeg)

![vecteur-vs-pixel](img/01/vectorisation-zoom.jpeg)

[:arrow_up: Revenir au top](#table-des-matières)

### Formats fichier image

Une image peut être créer dans différents formats tels que `.jpg`, .`jpeg`, `.gif`, `.png`, `.svg`,.. Chaque format à sa particularité, par exemple le `jpg` ne permet pas la transparence, le `gif` peut-être animé et transparent, le `png` ne peut pas être animé mais propose la gestion de la transparence. Ces formats ont également leurs propre taux de compression, le `jpg` proposera toujours des images moins lourdes mais "de moins bonne qualité" que le `png` Bref, chaque format à son utilisation.

![diff-format-images](img/01/Format-image-difference-jpg-gif-png-svg.jpeg)

[:arrow_up: Revenir au top](#table-des-matières)

#### Le cas du WebP

Le `.webp`est un format moderne proposé par Google qui possède une compression plus importante que les formats cité plus haut et avec une perte en qualité moindre. Il gère également la transparence. Il est supporté nativement dans les navigateurs les plus connus.

Il reste cependant certains logiciel comme Photoshop qui ne savent ni les ouvrir, ni les générer. Il faut donc passer par d'autres outils comme des convertisseurs en ligne pour  les créer.

### Le SVG

`.svg`: C'est un format d'image mais celui-ci est éditable en ligne de code, c'est pour cela qu'on le considère plutôt comme un fichier web, qu'une image. Il est formé de multiples lignes de coordonnées de points qui forment votre image.

### Sources

Les formats vu plus haut sont tous des formats "exploitable" sur le web, c'est à dire que vous pouvez les intégrer à vos pages de votre site, dans un email, sur votre fil d'actualité Facebook ou Instagram. A contrario, il existe des types de fichiers dit "sources" qui sont des fichiers que vous ne pouvez pas afficher dans vos contenus. Ceux-ci sont là pour vous permettre d'éditer de nouveau vos créations pour en changer la taille, la couleur, les formes,...

Chaque logiciel graphique à son propre fichier source, nous allons voir les deux principaux que nous utiliseront lors de cette formation, mais il en existe autant que de logiciels différents.

- `.psd`: PhotoShop Document, il stock toutes les options disponible dans le logiciel. Cela inclut les calques et leurs masques, la transparence, le texte, les couches alpha, les couleurs, les segments, les filtres,... Cela permet d'avoir toujours accès aux modifications apportés à nos contenus en cas de correction nécessaire.
- `.ai`: Adobe Illustrator, un peu comme le psd, ce fichier stock toutes les options du programme dans un fichier pour pouvoir éditer de nouveau l'illustration crée.

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
