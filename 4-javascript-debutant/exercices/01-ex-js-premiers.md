# Premiers pas

## Exercice 1

1. Créez une page `index.html` et `script.js`
2. Lier la page JS à votre page HTML
```html
<script src="script.js">
```
3. Insérez la balise suivante
```html
<div id="exercice"></div>
```
4. Insérez la chaine de caractère suivante dans la balise div à l'aide de votre page `script.js`

`Hello, World!`

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  document.getElementById("exercice").innerHTML = "Hello, World!";
  ```

</details>

## Exercice 2

1. Supprimez le code JS précédent
2. Insérez le code nécessaire pour faire une `alert box` avec le texte suivant `Hello, World!`

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  alert("Hello, World!");
  ```

</details>

## Exercice 3

1. Supprimez le code JS précédent
2. Insérer le code nécessaire pour afficher de nouveau `Hello, World!` dans la div de l'exercice 1
3. Changer le style CSS, augmenter la taille de la police en 2em.
4. Changer ensuite la couleur en rouge

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  document.getElementById("exercice").innerHTML = "Hello, World!";
  document.getElementById("exercice").style.fontSize = "2em";
  document.getElementById("exercice").style.color = "red";
  ```

</details>

## Exercice 4

1. Supprimez le code JS précédent
2. Faite un `console log` de la chaîne de caractère `Hello, World!`


<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  console.log("Hello, World!");
  ```

</details>

## Exercice 5

1. Supprimez le code JS précédent
2. Faite un `console log` contenant votre nom et votre âge.
3. Il faut que votre nom soit en chaîne de caractère et votre âge en number.


<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  console.log("Jeremy" + " " + 32 + "ans");
  ```

</details>