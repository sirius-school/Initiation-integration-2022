<!-- omit in toc -->
# Events JS

Un event en JavaScript c'est tout simplement quand "il se passe quelque chose". Grâce aux events, vous pouvez faire en sorte que JS réagissent à ces événements, comme par exemple exécuter une fonction.

Un event en HTML peut être quelque chose que le navigateur fait ou l'utilisateur. Par exemple:

- La page a fini de se charger.
- Un champ (field) a changé.
- Un bouton à été cliqué.

Quand cela arrive, il y a beaucoup de chances que vous souhaitez effectuer des opérations.

Pour ce faire on peut insérer dans l'html du JS.

```js
<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>
```

Mais cela peut devenir vite long et fastidieux à entretenir comme code, on préférera écrire une fonction à exécuter.

```js
<button onclick="displayDate()">The time is?</button>
```

Voici les principaux "events"

Event | Description
---|---
onchange | Un élément HTML à été changé
onclick	| L'utilisateur à cliquer sur un élément
onmouseover |	L'utilisateur déplace sa souris par dessus un élément HTML
onmouseout |	L'utilisateur passe en dehors d'un élément HTML
onkeydown |	L'utilisateur appuie sur une touche
onload | La navigateur à fini de charger la page

Il en existe évidement bien plus que ça: [:us: JavaScript Reference HTML DOM Events](https://www.w3schools.com/jsref/dom_obj_event.asp)

[:arrow_up: Revenir au top](#table-des-matières)

[:rewind: Retour au sommaire du cours](./README.md#table-des-matières)