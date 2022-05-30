<!-- omit in toc -->
# Data Type JS

Les date type en JS sont les différents types de valeurs qu'une variable peut avoir. Sans eux l'ordinateur ne saurait pas quoi faire avec les valeurs que vous lui donner. C'est donc un concept super important!

On a déjà vu certains de ces types (string, number,...) mais voyons en encore d'autres.

<!-- omit in toc -->
## Table des matières

- [Les types en JS sont dynamique](#les-types-en-js-sont-dynamique)
- [String](#string)
- [Numbers](#numbers)
- [Booleans](#booleans)
- [Arrays](#arrays)
- [Objects](#objects)
- [Typeof](#typeof)
- [Undefined](#undefined)
- [Valeur vide](#valeur-vide)

## Les types en JS sont dynamique

Ceci veut dire qu'une même variable peut contenir différents type.

```js
let x;            // Maintenant x est "undefined"
x = 42;           // Maintenant x est un "Number"
x = "James Bond"; // Maintenant x est un "String"
```

## String

On en a déjà vu pleins d'exemples, c'est une chaîne de caractère. Pour l'indiquer on les place entre simple ou double quotes

```js
let name = "James";
let surname = 'Bond';
```

## Numbers

Rien de nouveau ici non plus, on indique les nombres sans rien.

```js
let x = 42;
let y = 3.14;
```

## Booleans

A voici un nouveau type dont on a pas encore parlé. Le boolean peut avoir 2 valeurs: `true` (vrai) ou `false` (faux).

```js
let x = 5;
let y = 5;
let z = 6;
(x == y)       // Returns true
(x == z)       // Returns false
```

Ceci va nous aider lors du test de condition pour écrire des boucles ou fonctions.

## Arrays

Un array c'est un tableau de donnée. On les écrits avec des crochets ([]) et on sépare les données par une virgule (,).

```js
const games = ["horizon zero dawn" , "league of legends", "counter-strike"]
```

Retenez aussi pour l'instant que le premier élément du tableau est le numéro "0". Ça vous semble pas logique, c'est normal, mais c'est ainsi. Nous verrons plus concernant les arrays plus loin.

## Objects

Un peu comme un tableau mais en plus précis. On va écrire notre objet avec des curly braces (accolades). 

On indique ensuite les propriétés de l'objets en suivant le schéma suivant: `name:value`. Et on sépare les différentes entrées par une virgule (,).

```js
const horizon = {
  name:"Horizon Zero Dawn", 
  character:"Aloy", 
  type:"adventure", 
  price:60
};
```

## Typeof

On peut utiliser l'opérateur `typeof`pour connaître le type d'une variable.

```js
let x = 42;
console.log(typeof x); // Return "Number"
```

## Undefined

Une variable sans valeur retourne la valeur et le type `undefined`. 

```js
let game; // La valeur et le type sont bien "undefined"
game = undefined // On peut volontairement le définir
```

## Valeur vide

:exclamation: Attention à ne pas confondre `undefined` et valeur vide. 

```js
let game = ""; // La valeur est "" et le type est "string"
```

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
