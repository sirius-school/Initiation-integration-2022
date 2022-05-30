# Conditions

## Exercice 1

Reprenons le code de l'exercice 4 sur les variables et améliorons-le.

1. Supprimez le code JS précédent
2. Recopiez le code suivant
```js
  let person = prompt("Quel es votre nom", "votre nom");
  document.getElementById("exercice").innerHTML = "Hello " + person + "! How are you today?";
```
3. A la suite de votre de votre variable créez une condition `if`
4. Demandez à comparez votre variable `person` et vérifier si elle différente de `null` (retournez voir la théorie sur les operators si besoin)
5. Insérez dans votre condition le code qui insert le résultat dans votre HTML.


<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  let person = prompt("Quel es votre nom", "votre nom");
  if (person != null) {
    document.getElementById("exercice").innerHTML = "Hello " + person + "! How are you today?";
  }
  ```

</details>

## Exercice 2

1. Supprimez le code JS précédent
2. Demandez au visiteur son nom et son âge avec `prompt()`
3. Créez une condition qui vérifiera d'abord si l'utilisateur à 69 ans précisément
4. Insérez dans la `div` exercice, un petit message accueillant cette personne en précisant son nom.
5. Créez ensuite un deuxième condition si la première n'es pas `true` et vérifier que l'utilisateur à 18 ans ou plus
6. De nouveau, accueillez votre visiteur avec son nom.
7. Créez un dernier cas, au cas où aucune des deux conditions n'est vraie pour dire que votre site est réservé à un public adulte.

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  let name = prompt("Quel est vôtre nom?", "Vôtre nom")
  let age = prompt("Quel est vôtre âge?", "Vôtre âge")
  
  if (age == 69) {
    document.getElementById("exercice").innerHTML = "Salut " + name + "! Petit coquin! Bienvenue sur mon site réservé à un public adulte.";
  } else if (age >= 18) {
    document.getElementById("exercice").innerHTML = "Salut " + name + "! Bienvenue sur mon site réservé à un public adulte.";
  } else {
    document.getElementById("exercice").innerHTML = "Salut " + name + "! Désolé mais ce site est réservé à un public adulte.";
  }
  ```

</details>

## Exercice 3

1. Améliorons le code précédent.
2. Ajoutez le code HTML suivant
```html
<img src="https://images.pexels.com/photos/8907688/pexels-photo-8907688.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" id="sexy" alt="">
<img src="https://images.pexels.com/photos/416160/pexels-photo-416160.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" id="cat" alt="">
```
3. Faites en sortes d'afficher l'image avec l'id `sexy` aux utilisateurs qui ont plus de 18 ans
4. Faites en sortes d'afficher l'image avec l'id `cat` aux utilisateurs qui ont moins de 18 ans

<details>
  <summary><strong>Réponse</strong></summary>

  ```js
  
  let name = prompt("Quel est vôtre nom?", "Vôtre nom")
  let age = prompt("Quel est vôtre âge?", "Vôtre âge")
  
  if (age == 69) {
    document.getElementById("exercice").innerHTML = "Salut " + name + "! Petit coquin! Bienvenue sur mon site réservé à un public adulte.";
    document.getElementById("sexy").style.display = "block";
  } else if (age >= 18) {
    document.getElementById("exercice").innerHTML = "Salut " + name + "! Bienvenue sur mon site réservé à un public adulte.";
    document.getElementById("sexy").style.display = "block";
  } else {
    document.getElementById("exercice").innerHTML = "Salut " + name + "! Désolé mais ce site est réservé à un public adulte.";
    document.getElementById("cat").style.display = "block";
  }
  ```

</details>
