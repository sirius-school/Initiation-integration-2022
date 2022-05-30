<!-- omit in toc -->
# Introduction au JavaScript

<!-- omit in toc -->
## Table des matières

- [Introduction](#introduction)
- [Première méthode](#première-méthode)
  - [JavaScript peut changer le contenu HTML](#javascript-peut-changer-le-contenu-html)
  - [JavaScript peut changer la valeur d'un attribut HTML](#javascript-peut-changer-la-valeur-dun-attribut-html)
  - [JavaScript peut changer le style CSS](#javascript-peut-changer-le-style-css)
  - [JavaScript peut afficher/cacher un élément](#javascript-peut-affichercacher-un-élément)
- [Où c'est qu'on place ça ?](#où-cest-quon-place-ça-)
  - [La balise `<script>`](#la-balise-script)
  - [Functions et Events](#functions-et-events)
  - [`<head>` et `<body>`](#head-et-body)
  - [JavaScript externe à la page](#javascript-externe-à-la-page)

## Introduction

JavaScript est le langage de programmation WEB le plus populaire au monde. Il est facile à apprendre.

Pourquoi apprendre le JS ? Car il constitue l'un des 3 langages principaux qu'un développeur se doit de connaître. On  a déjà vu les deux autres: HTML et CSS.

Il est important d'apprendre à son rythme, certains concepts seront plus vite compris par certains, mais ne vous découragez pas.

Comment on se procure JS ? Rien de plus simple, il suffit de ne rien faire! En effet, JS est déjà intégré à votre navigateur internet.

[:arrow_up: Revenir au top](#table-des-matières)

## Première méthode

Une des premières méthodes que l'ont utilisera c'est `getElementById()` pour sélectionner un élément HTML par son ID et non pas sa classe.

### JavaScript peut changer le contenu HTML

 Ensuite on utilisera `innerHTML` pour changer le contenu.

```js
document.getElementById("greeting").innerHTML = "Hello You!";
```

> Dans cet exemple on sélectionnera tous les éléments dont l'ID est "greeting" et on remplacera son contenu par "Hello You!"


### JavaScript peut changer la valeur d'un attribut HTML

```js
document.getElementById('myAvatar').src='avatar2.png'
```

> Dans cet exemple on sélectionne l'élément "myAvatar" qui est une image avec une source que l'ont va changer avec "src=''"

### JavaScript peut changer le style CSS

```js
document.getElementById("monStyle").style.fontSize = "1.5em";
```

> Vous avez compris la logique normalment. Ici on change juste la taille du texte.

### JavaScript peut afficher/cacher un élément

```js
document.getElementById("hide").style.display = "none";
document.getElementById("show").style.display = "block";
```

[:arrow_up: Revenir au top](#table-des-matières)

## Où c'est qu'on place ça ?

Pour exécuter du code JS il y a plusieurs possibilités.

### La balise `<script>`

C'est entre cette balise que vous allez placer votre code JS.

### Functions et Events

Vous allez entendre constamment parler de `functions` (fonctions), ce sont des blocks de code en JS qui sont exécutés quand ils sont "appelés". Une fonction peut être appelés quand un `event` (événement) se produit comme par exemple le click de l'utilisateur sur un bouton.

### `<head>` et `<body>`

C'est dans l'une de ces balises que l'ont peut placer autant de balise `<script>`que l'ont veut.

> :bulb: C'est préférable de placer ses scripts en fin de balise `<body>`, cela amélioré la vitesse de rendu de la page en exécutant le script en dernier.

### JavaScript externe à la page

Il est tout à fait possible d'écrire son code dans un fichier externe. 

```js
/* myScript.js */
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
```

Cette méthode est plus pratique surtout si le code est réutilisé sur plusieurs pages.

Les fichiers JavaScript ont pour extension `.js`

Pour utiliser un fichier externe on ajoute un attribut `src=""` à la balise `<script>`.

L'avantage c'est qu'on sépare le code HTML du JS, c'est ainsi plus facile à lire et à entretenir.

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
