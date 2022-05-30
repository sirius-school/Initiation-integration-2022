# Variables

## Exercice 1

1. Toujours dans les mêmes pages que celles utilisés dans l'exercice 1, créez une variable `hello` et attribuez lui le texte `Hello, World!`
2. Affichez cette variable dans votre console.

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  let hello = "Hello, World!";
  console.log(hello)
  ```

</details>

## Exercice 2

1. Supprimez le code précédent.
2. Déclarez une variable `x`
3. Affichez sa valeur dans la console
4. Assignez lui une valeur numérique au choix.
5. Affichez sa valeur dans la console
6. Assignez une nouvelle valeur à `x`
7. Affichez dans la console sa nouvelle valeur
8. Assignez maintenant une chaîne de caractère
9. Affichez ce texte dans la console

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  let x;
  console.log(x)
  x = 22;
  console.log(x)
  x = 42;
  console.log(x)
  x = "Hello, World!"
  console.log(x)
  ```

</details>

## Exercice 3

1. Créez une première variable qui a pour nom `nom`.
2. Insérez dans cette variable votre nom.
3. Faites de même pour votre prénom, votre âge et votre ville.
4. Créez une nouvelle variable `moi` qui contiendra l'affichage de vos différentes informations. Essayez de mettre la balise `</br>` entre les infos pour allez à la ligne dans votre HTML.
5. Affichez dans la console et dans la `div`le 
6. Voyez la différence entre le console log et l'affichage en HTML

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  let nom = "Scala";
  let prenom = "Jeremy";
  let age = 32;
  let ville = "Hannut";
  let moi = "nom: " + nom + "</br>" + "prénom: " + prenom + "</br>" + "âge: " + age + "</br>" + "ville: " + ville;

  console.log (moi);
  document.getElementById("exercice").innerHTML = moi;
  ```

</details>

## Exercice 4

Dans cet exercice je vais vous apprendre quelque chose qu'on a pas vu. L'utilisation de la méthode `prompt()`

1. Supprimez le code JS précédent
2. Créez une variable `person` 
3. Insérez le code suivant dedans:
```js
prompt("Quel es votre nom", "votre nom");
```
4. Dans les parenthèse on indique une question et ensuite le placeholder du champ dans lequel l'utilisateur va répondre à notre question.
5. Ensuite insérez dans l'HTML un message de bienvenue pour votre utilisateur en utilisant le nom stocké dans la variable `person`

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  let person = prompt("Quel es votre nom", "votre nom");
  document.getElementById("exercice").innerHTML = "Hello " + person + "! How are you today?";
  ```

</details>