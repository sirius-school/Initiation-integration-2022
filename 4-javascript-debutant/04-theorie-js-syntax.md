<!-- omit in toc -->
# Syntax JS

Voyons un peu comment on écrit du JavaScript.

<!-- omit in toc -->
## Table des matières

- [Valeurs](#valeurs)
  - [Littérales (Literals)](#littérales-literals)
- [Les variables](#les-variables)
- [Les opérateurs](#les-opérateurs)
- [Les expressions](#les-expressions)
- [Les mots-clés](#les-mots-clés)
- [Les commentaires](#les-commentaires)
- [Les identifiants](#les-identifiants)
  - [Sensibilité aux majuscules et minuscules](#sensibilité-aux-majuscules-et-minuscules)
  - [Camel Case](#camel-case)

## Valeurs

Il existe deux types de valeurs en JS:

- Les valeurs fixes (Literals)
- Les valeurs variables (Variables)

### Littérales (Literals)

Les 2 règles les plus important concernant les valeurs fixes sont:

1. Les nombres sont écris avec ou sans décimales (.)

```js
7.50
42
```

2. Les chaînes de caractères (strings) doivent êtres inscrites dans des simples ou doubles quotes.

```js
"Je sappelle Groot"
'What\'s in the box'
```

[:arrow_up: Revenir au top](#table-des-matières)

## Les variables

C'est avec les variables que l'ont va stocker des données.

JS utilise `var`, `let` et `const` pour déclarer une variable. Nous verrons la différences entres eux plus tard.

On utilise le signe égale (=) pour assigner une valeur à la variable.

```js
let x;
x = 42;
```

[:arrow_up: Revenir au top](#table-des-matières)

## Les opérateurs

JS utilise les opérateurs arithmétique (+ - * /) pour calculer des valeurs.

```js
(5 + 6) * 10
```

N'oublions pas que JS utilise le signe égale pour assigner des valeurs aux variables.

[:arrow_up: Revenir au top](#table-des-matières)

## Les expressions

Une expression est la combinaison de valeurs, variables et opérateurs que l'ordinateur va calculer.

```js
5 * 10
x * 10
"James" + " " + "Bond"
```

[:arrow_up: Revenir au top](#table-des-matières)

## Les mots-clés

En JS les mots-clés sont là pour identifié les actions qui doivent êtres effectuées.

```js
let x, y;
x = 5 + 6;
y = x * 10;
```

> Ici le `let` dit au navigateur que l'on définit 2 variables

[:arrow_up: Revenir au top](#table-des-matières)

## Les commentaires

Comme dans tous les langages vus jusqu'à maintenant, il est possible d'ajouter des commentaires à son code. C'est quand on programme qu'on aura le plus besoin de commentaires pour se rappeler ce que fait cette fonctions ou à quoi sert cette variable.

```js
let x = 5; // Ceci est une déclaration qui sera exécuté

// x = 6; Ceci ne sera pas effectué car fait partie d'un commentaire.
```

[:arrow_up: Revenir au top](#table-des-matières)

## Les identifiants

Les identifiants en JS sont des noms qui permettent de nommer nos variables et autres.

La règle est que le premier caractère doit être une lettre, un underscore (_) ou un dollar ($).

Les caractères suivants peuvent être une lettre, un chiffre, un underscore ou un dollar.

> :exclamation: Un chiffre ne peut pas être le premier caractère pour que JS puisse facilement distinguer un identifiant d'un nombre.

[:arrow_up: Revenir au top](#table-des-matières)

### Sensibilité aux majuscules et minuscules

Tous les identifiants en JS sont sensible à la casse.

```js
let lastname, lastName;
lastName = "Doe";
lastname = "Peterson";
```

[:arrow_up: Revenir au top](#table-des-matières)

### Camel Case

Pour séparer plusieurs mots dans vos identifiants il est possible d'utiliser soit des soit des underscores (_), le Upper Camel Case ou le Lower Camel Case.

A vous de choisir ce que vous préférer.

```js
let first_name;
let FirstName;
let firstName;
```

> :exclamation: N'utilisez pas de tirets, ceux-ci sont réservés à la soustraction.

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
