<!-- omit in toc -->
# Conditions JS

Souvent quand on écrit du code on veut déclencher une action à un moment précis. Pour ce faire on peut utiliser les conditions. Il existe plusieurs type de conditions, voyons cela.

- Utiliser `if` pour spécifier un bloc de code à exécuté **si** une condition spécifié est **true** (boolean)
- Utiliser `else` pour spécifier un bloc de code à exécuté **si** la même condition est **false** (boolean)
- Utiliser `else if` pour spécifier une nouvelle condition à tester **si** la première est **false**
- Utiliser `switch` pour spécifier divers blocs de code à exécuté pour divers conditions

<!-- omit in toc -->
## Table des matières

- [If Statement](#if-statement)
- [Else Statement](#else-statement)
- [Else if Statement](#else-if-statement)
- [Switch Statement](#switch-statement)

## If Statement

```js
if (price < 60) {
  console.log("Vous faites une affaire")
}
```

## Else Statement

```js
if (price < 30) {
  console.log("Vous faites une affaire")
} else {
  console.log("C'est trop cher")
}
```

## Else if Statement

```js
if (price < 30) {
  console.log("Vous faites une affaire")
} else if (price == 40) {
  console.log("C'est pas mal comme prix")
} else {
  console.log("C'est trop cher")
}
```

## Switch Statement

Le `switch` permet d'établir des cas pour des valeurs précises.

```js
switch(price) {
  case 30:
    console.log("Vous faites une affaire")
    break;
  case 40:
  console.log("C'est pas mal comme prix")
    break;
  default:
  console.log("C'est trop cher")
}
```

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)