<!-- omit in toc -->
# Functions JS

Une fonction c'est un bloc de code créé pour exécuter une tâche particulière qui pourrait avoir lieu plusieurs fois avec des valeurs différentes.

Une fonction s'exécute quand "quelques chose" l'appelle.

<!-- omit in toc -->
## Table des matières

- [Syntaxe](#syntaxe)
  - [Parameters & arguments](#parameters--arguments)
- [Invoquer une fonction](#invoquer-une-fonction)
- [Return](#return)
- [Utiliser une fonction comme valeur](#utiliser-une-fonction-comme-valeur)
- [Variables locales](#variables-locales)

## Syntaxe

On utilise le mot-clé `function` suivi du nom que l'ont veut donner à sa fonction. 

Ensuite suivent des parenthèses. Ces dernières servent à inclure des paramètres à notre fonction, plus de détails là dessus plus tard.

Ensuite on ouvre nos accolades pour y placer à l'intérieur le code à exécuté.

```js
function name(parameter1, parameter2) {
  // code à exécuter
}
```

### Parameters & arguments

Les paramètres ce sont des valeurs que la fonction va recevoir, ces valeurs seront des arguments et serviront de "variables" à l'intérieur de la fonction.

## Invoquer une fonction

Plusieurs "choses" peuvent invoquer/appeller une fonction: 

- Quand un événement se produit (l'utilisateur clique sur un bouton)
- Quand on l'appelle dans le code JS
- Automatiquement (s'invoque elle même)

## Return

Une fonction n'est qu'une liste de déclarations à exécuter l'une après l'autre. Mais si à un moment donné on atteint `return` la fonctionne va s'arrêter là et le navigateur va sortir de la lecture de cette fonction pour continuer son chemin.

```js
let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
```

## Utiliser une fonction comme valeur

Prenons l'exemple suivant:

```js
function addition(x,y) {
  return x + y;
}
console.log(addition)
```

On appelle la fonction sans les parenthèse () et du coup on à la fonction comme retour et non pas le résultat.

```js
function addition(x,y) {
  return x + y;
}
console.log(addition(5, 37))
```

Ici on appelle la fonction avec les parenthèses et en lui donnant des paramètres. Du coup le résultat de la fonction est affiché car elle s'est exécutée.

Et du coup on peut aussi stocker la fonction dans une variables

```js
function addition(x,y) {
  return x + y;
}

let x = "Le résultat est " + addition (5,37);
console.log(x)
```

## Variables locales

Si vous déclarer une variables à l'intérieur d'une function, celle-ci sera uniquement disponible à l'intérieur de cette fonction.

```js
let x = "dispo partout";
function pasDispo() {
  let y = "pas dispo";
  return y;
}
console.log (x)
console.log(pasDispo())
console.log (y)
```

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
