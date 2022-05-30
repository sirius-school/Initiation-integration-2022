<!-- omit in toc -->
# Object JS

Les objets en JavaScript permettent de stocker les mêmes valeurs pour des objets. Prenez l'exemple d'un jeu vidéo, celui-ci à un genre, un prix, une plateforme, un héro, un nom,... Tous les jeux vidéo ont ces propriétés là. Du coup, on peut stocker ces propriétés à l'intérieurs d'un objet pour facilement y accéder.

<!-- omit in toc -->
## Table des matières

- [Syntaxe](#syntaxe)
- [Accéder aux propriétés](#accéder-aux-propriétés)
- [Méthodes](#méthodes)

## Syntaxe

On va écrire notre objet avec des curly braces (accolades). 

On indique ensuite les propriétés de l'objets en suivant le schéma suivant: `name:value`. Et on sépare les différentes entrées par une virgule (,).

```js
const horizon = {
  name:"Horizon Zero Dawn", 
  character:"Aloy", 
  type:"adventure", 
  price:60
};
```

## Accéder aux propriétés

Deux méthodes existes pour accéder à une propriété d'un objet.

```js
horizon.name;
// ou
horizon["name"];
```

## Méthodes

Les méthodes sont des actions que l'ont peut stocker dans nos objets pour les exécuter.

```js
const horizon = {
  name:"Horizon Zero Dawn", 
  character:"Aloy", 
  type:"adventure", 
  price:60,
  info: function() {
    return this.name + " est un jeu de type " + this.type + " dont le personnage principale est " + this.character + " et il est vendu à " + this.price + "€";
  }
};
```


[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
