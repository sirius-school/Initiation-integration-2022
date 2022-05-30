<!-- omit in toc -->
# Possibilité d'affichage

Il y a différentes façon "d'afficher" des données en JS.

<!-- omit in toc -->
## Table des matières

- [`innerHTML`](#innerhtml)
- [`document.write()`](#documentwrite)
- [`window.alert()`](#windowalert)
- [`console.log()`](#consolelog)

## `innerHTML`

Comme vu dans l'introduction, on peut accéder à un élément avec la méthode `document.getElementById(id)`. 

La propriété `innerHTML` permet de définir le contenu de l'élément HTML sélectionné.

```html
<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = 5 + 6;
</script>
```

## `document.write()`

Cette propriété va ré-écrire le document. Ce qui fait que si vous l'appelé après que votre page soit chargée, vous allez effacer toute la page.

```html
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<button type="button" onclick="document.write(5 + 6)">Try it</button>

</body>
</html>
```

## `window.alert()`

Cette propriété va afficher le résultat demandé dans une alert box. 

```html
<script>
alert(5 + 6);
</script>
```

## `console.log()`

Cette propriété va afficher le résultat demandé dans la console de votre navigateur (F12 ou clic-droit > inspecter)

```html
<script>
console.log(5 + 6);
</script>
```

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)
