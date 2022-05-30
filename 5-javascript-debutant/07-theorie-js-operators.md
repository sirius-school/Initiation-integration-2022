<!-- omit in toc -->
# Operators JS

Voyons un peu plus en détail les différents opérateurs en JS.

<!-- omit in toc -->
## Table des matières

- [Assignment](#assignment)
- [Adding / subtracting](#adding--subtracting)
- [Multiplication / Division](#multiplication--division)
- [String operators](#string-operators)
- [Les opérateurs de comparaisons](#les-opérateurs-de-comparaisons)
- [Incrémenter ou décrémenter](#incrémenter-ou-décrémenter)


## Assignment

On l'a déjà vu plusieurs fois, il s'agit du signe égale (=) qui permet d'assigner une valeur à une variable.

```js
let x = 42;
```

## Adding / subtracting

Le signe d'addition (+) ou de soustraction (-) permettent d'additionner ou soustraire des nombres entres eux.

```js
let x = 40;
let y = 2;
let z = x + y;
```

## Multiplication / Division

Le signe de multiplication (*) ou de division (/) permettent de multiplier ou diviser des nombres entre eux

```js
let x = 40;
let y = 2;
let z = x / y;
```

## String operators

Attention l'addition ne se passe pas de la même façon avec une chaîne de caractère. Les chaînes additionnés vont se coller l'une à l'autre.

```js
let text1 = "James";
let text2 = "Bond";
let text3 = text1 + " " + text2;
```

Il est possible de combiner `string` et `numbers`.

```js
let x = 5 + 5;
let y = "5" + 5;
let z = "Hello" + 5;
```

## Les opérateurs de comparaisons

Il va être utile de comparer des valeurs ensembles.

Operator | Description
--- | ---
== | égale à 
=== | valeur et type égale
!= | n'est pas égale
!== | n'est pas égale en valeur et type
\> | strictement plus grand que
< | strictement plus petit que
\>= | plus grand ou égale que
<= | plus petit ou égale  que

## Incrémenter ou décrémenter

Il est possible d'incrémenter ou décrémenter la valeur d'un nombre facilement. Pour cela on utilise `++` ou `--`.

```js
let x = 5;
x++;
let z = x; // Z sera égale à 6
```

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
