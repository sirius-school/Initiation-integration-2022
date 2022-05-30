<!-- omit in toc -->
# Loop For JS

Voyons la dernière partie amusante du JS avant d'entamer vos exercices. Les loops (boucles) permettent de répéter un bout de code un certains nombre de fois sans devoir le ré-écrire. Il existe plusieurs type de loop mais nous verrons ici que la loop `for` (pour).

<!-- omit in toc -->
## Table des matières

- [Syntaxe](#syntaxe)

## Syntaxe

```js
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```

### Statement 1

C'est dans ce statement qu'on va initialiser une variable qu'on va utiliser dans notre loop. Mais ce n'est pas toujours obligatoire.

```js
for (let i = 0; statement 2; statement 3) {
  // code block to be executed
}
```

### Statement 2

C'est dans ce statement qu'on va évaluer notre condition pour que la boucle se répète ou non. Si la condition renvoie `true` alors la boucle se répétera. Si elle retourne `false` la boucle prendra fin.

```js
for (let i = 0; i < 5; statement 3) {
  // code block to be executed
}
```

### Statement 3

Et pour finir, on va incrémenter notre variable de 1 puisqu'elle aura été exécuté une fois.

```js
for (let i = 0; i < 5; i++) {
  // code block to be executed
}
```

## Exemple simple de loop

```js
for (let i = 0; i < 5; i++) {
  console.log(i)
}
```

```js

```

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
