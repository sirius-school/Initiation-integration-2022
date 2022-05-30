<!-- omit in toc -->
# Statements

Un programme n'est autre qu'une liste "d'instructions" que l'ordinateur doit "exécuter". En langage informatique ces instructions sont appelés des `statements` (déclarations).

<!-- omit in toc -->
## Table des matières

- [Les déclarations en JS](#les-déclarations-en-js)
- [Point-virgule](#point-virgule)
- [Espace vide](#espace-vide)
- [Longueur de ligne](#longueur-de-ligne)
- [Bloc de code](#bloc-de-code)
- [Les mots-clés en JS](#les-mots-clés-en-js)

## Les déclarations en JS

En JS les déclarations sont composés de:

- Values (valeurs)
- Operators (opérateurs)
- Expressions (expressions)
- Keywords (mots-clés)
- Comments (commentaires)

Nous les verrons au fur et à mesures.

[:arrow_up: Revenir au top](#table-des-matières)

## Point-virgule

Le point-virgule est le caractère qui permet de séparer chaque déclarations. Pour une meilleure lisibilité nous les placerons chacune sur une ligne séparée, mais le navigateur lui ne sait pas quand s'arrête la déclaration. Même si de nos jours, pour des opérations simples cela ne devrait pas poser problèmes, il est tout de même préférable de placer un point-virgule à la fin de chacune de nos déclarations. Prenons les bonnes habitudes dès le début.

```js
a = 5; b = 6; c = a + b;
```

[:arrow_up: Revenir au top](#table-des-matières)

## Espace vide

JavaScript ignore les multiples espaces vide. Vous pouvez en ajouter autant que vous voulez.

```js
let person = "James";
let person="James";
```

> Ici le résultat sera le même. JS ne devrait avoir aucun mal.

[:arrow_up: Revenir au top](#table-des-matières)

## Longueur de ligne

Pour une meilleure lisibilité on évite les lignes de codes trop longues (pas plus de 80 caractères). Si vous devez passer à la ligne, vaut mieux le faire après un opérateur.

```js
document.getElementById("demo").innerHTML =
"Hello World!";
```

[:arrow_up: Revenir au top](#table-des-matières)

## Bloc de code

Des déclarations peuvent êtres groupées entres elle à l'aide des curly brackets (accolades). Cela permet d'indiquer que tous ces statements doivent être exécutés ensembles.

Vous retrouverez les blocs de code lorsque vous ferrez des fonctions.

```js
function myFunction() {
  document.getElementById("demo1").innerHTML = "Hello Dolly!";
  document.getElementById("demo2").innerHTML = "How are you?";
}
```

[:arrow_up: Revenir au top](#table-des-matières)

## Les mots-clés en JS

Keyword | Description
--- | ---
var | Déclare une variable
let | Déclare un bloc de variable
const | Déclare un bloc constant
if | Exécute un bloc de déclarations avec une condition
switch | Indique un bloc de déclarations à être exécuté dans différents cas
for | Indique un bloc de déclaration à être exécuté dans une boucle
function | Déclare une fonction
return | Sortir d'une fonction
try | Permet de gérer les erreurs d'un bloc de déclarations

[:arrow_up: Revenir au top](#table-des-matières)
[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)