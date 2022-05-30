<!-- omit in toc -->
# Variables JS

Voyons un peu plus en détails les variables en JavaScript. Il y a trois solution pour écrire une variables: `var`, `let` et `const`.

<!-- omit in toc -->
## Table des matières

- [Variables](#variables)
- [Déclarer une variable](#déclarer-une-variable)
- [Assigner une valeur](#assigner-une-valeur)
- [Déclarer et assigner](#déclarer-et-assigner)
- [Une déclaration, plusieurs variables](#une-déclaration-plusieurs-variables)
- [Type de données](#type-de-données)
- [Le cas de `const`](#le-cas-de-const)

## Variables

Les variables sont comme des conteneurs pour stocker vos valeurs et pouvoir les réemployer plus tard.

## Déclarer une variable

Qu'il s'agisse de `var`, `let` ou `const`, là méthode pour déclarer une variable est toujours la même. On indique le mot clé suivit de l'identifiant (nom) de notre variable.

```js
var maVariable;
let maVariable2;
const maVariable3;
```

Après avoir déclarer une variable celle-ci n'a pas de valeur (techniquement elle a la valeur `undefined`).

## Assigner une valeur

Pour chaque type de variable on peut lui assigner une valeur à l'aide de l'opérateur d'assignment qu'est le signe égale (=).

```js
maVariable = "James";
maVariable2 = 42;
maVariable3 = "Bond";
```

## Déclarer et assigner

Il est possible de faire les deux en même temps.

```js
let maVariable4 = "Spider-man";
```

## Une déclaration, plusieurs variables

Il est également possible de déclarer plusieurs variables en une seule déclaration (statement).

```js
let game = "Horizon Zero Dawn", character = "Aloy", type = "adventure", price = 60; 
```

## Type de données

En JavaScript vous pouvez stocker différentes choses dans une variable. 

- du texte: on appelle ça une chaine de caractère (text string). Il doit être écrit à l'intérieur de single ou double quotes.
- des nombres.

## Le cas de `const`

La variable `const` porte un peu mal son nom car elle ne peut pas être réassigner.

```js
const age = 18;
age = 16; // Produira une erreur
age = age + 10; // Produira également une erreur
```

Il est également obligatoire d'assigner une valeur à `const` dès qu'elle est déclaré.

```js
// Ceci ne fonctionnera pas
const age;
age = 18;
```

Du coup on utilise `const` pour stocker des valeurs qui ne seront jamais modifiés.

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
