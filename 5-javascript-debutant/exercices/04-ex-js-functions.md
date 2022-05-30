# Functions

## Exercice 1

1. Supprimez tout le code JS que vous avez
2. Créez une nouvelle fonction qui aura pour nom `maPremiereFonction`
3. A l'intérieur de cette fonction faites simplement un console log de `Hello, World!`
4. Appelez votre fonction à la suite de votre page `script.js` 

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  function maPremiereFonction() {
    console.log("Hello, World!");
  }

  maPremiereFonction()
  ```

</details>

## Exercice 2

1. Supprimez le code JS de l'exercice précédant.
2. Créez deux variables utilisant un prompt (vu dans les exercices sur les variables) pour demander à l'utilisateur un chiffre et stockez ces deux chiffres dans ces 2 variables (x et y)
3. Créez une fonction `addition` avec pour paramètres `a` et `b`
4. Dans la fonction faites un `return` de `a` + `b`
5. Ensuite créez une nouvelle variable entre vos autres variables et votre fonction. Nommez la `calcul` et assignez lui votre fonction avec comme arguments `x`et `y`
6. Faites un console log de la variable `calcul` et vérifiez que vous avez le bon résultat. 
7. Vous devriez avoir vos deux chiffres qui se sont collés l'un à l'autre ce qui n'est pas l'effet voulu. 
8. On va faire quelque chose de nouveau pour corriger cela. Tout d'abord voyons ce qui ne va pas. Faisons à la suite de nos 2 variables un console log de nos deux variables pour vérifier le type de celles-ci.
```js
console.log(typeof x, typeof y)
```
9.  Relancer votre page et entrer de nouveau 2 chiffres et regardez votre console. Vous devriez voir affichez `string`. C'est normal, la méthode `prompt()` retourne toujours un `string`.
10. Corrigeons cela. Créer deux nouvelles variables `num1` et `num2`
11. Dans `num1` insérez le code suivant : `parseInt(x)` et dans `num2` : `parseInt(y)`. Cela à pour but de transformer la chaîne de caractère en `Integer`, c'est à dire un nombre.
12. Maintenant si on console log `num1` et `num2` on devrait voir que ce sont des `number`.
13. On peut donc modifier notre appel de fonction dans `calcul` et remplacer `x` et `y` par `num1` et `num2` 

Ben ouai tu croyais que c'était si simple JS... Ben non, ce petit exercice m'a permis d'encore glisser un peu de connaissance. Et de vous montrez comme on peut debugger un script qui ne fait pas ce que l'on veut. Mais hey, vous en faites pas ça viendra avec le temps.

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  let x = prompt("Indiquez un premier chiffre", "chiffre n°1");
  let y = prompt("Indiquez un deuxième chiffre", "chiffre n°2");

  console.log(typeof x, typeof y)

  let num1 = parseInt(x);
  let num2 = parseInt(y);

  console.log(typeof num1, typeof num2)

  let calcul = addition(num1, num2);

  function addition(a, b) {
    return a + b;
  }

  console.log(calcul)
  ```

</details>

