<!-- omit in toc -->
# Array JS

Les arrays (tableaux) en JavaScript servent à stocker plusieurs valeurs dans une seule variable. A la différence des objets, ici chaque valeur n'est pas associé à un nom.

<!-- omit in toc -->
## Table des matières

- [Syntaxe](#syntaxe)
- [Accéder à une valeur du tableau](#accéder-à-une-valeur-du-tableau)
- [Changer un élément](#changer-un-élément)
- [La méthode `length`](#la-méthode-length)
- [Accéder à la première valeur](#accéder-à-la-première-valeur)
- [Accéder à la dernière valeur](#accéder-à-la-dernière-valeur)
- [Boucler dans un tableau (avancé)](#boucler-dans-un-tableau-avancé)
- [Ajouter des éléments](#ajouter-des-éléments)

## Syntaxe

On les écrits avec des crochets ([]) et on sépare les données par une virgule (,).

```js
const games = ["horizon zero dawn" , "league of legends", "counter-strike"]
```

## Accéder à une valeur du tableau

Pour accéder à une valeur il faut connaître sa position (index). En lisant de gauche à droite on peut compter chaque élément en **commençant par zéro!!!**

```js
const games = ["horizon zero dawn" , "league of legends", "counter-strike"]

console.log(games[1]) // Affichera League of Legends
```

## Changer un élément

Contrairement aux objets où les valeurs sont fixes et sont là pour être affichées telles qu'elle, les valeurs d'un tableaux sont là pour être modifiées.

```js
const games = ["horizon zero dawn" , "league of legends", "counter-strike"]
games[2] = "apex:legends";

console.log(games[2]) // Affichera apex:legends plutôt que counter-strike
```

## La méthode `length`

Il est possible d'interroger notre tableau pour savoir combien d'élément il possède.

```js
const games = ["horizon zero dawn" , "league of legends", "counter-strike"]

console.log(games.length)
```

## Accéder à la première valeur

Rien de plus simple.

```js
games[0];
```

## Accéder à la dernière valeur

```js
games[games.length - 1];
```

## Boucler dans un tableau (avancé)

```js
const games = ["horizon zero dawn" , "league of legends", "counter-strike"];
let gamesLength = games.length;

let text = "<ul>";

for (let i = 0; i < gamesLength; i++) {
  text += "<li>" + games[i] + "</li>";
}

text += "</ul>";

document.getElementById("demo").innerHTML = text;
```

## Ajouter des éléments

Si l'ont veut créer une fonction qui ajoute des valeurs à notre tableau, il nous faut une méthode pour ajouter ces éléments dynamiquement. C'est là la méthode `push()` intervient.

```js
const games = ["horizon zero dawn" , "league of legends", "counter-strike"]

games.push("apex")
```

Il y a également possibilité d'ajouter un élément avec `length`. Forcément car la valeur de `length` est toujours 1 de plus que la position du dernier élément vu que ces positions commencent à 0.

```js
const games = ["horizon zero dawn" , "league of legends", "counter-strike"]

games[games.length] = "apex";
```

:exclamation: Attention avec cette dernière méthode de ne pas ajouter des éléments à la mauvaise position pour ne pas créer des "trous" dans votre tableau.



[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
