What day is it ?
---

Créez une app qui permets de connaitre le jour de la semaine en fonction d'une date fournie par l'utilisateur.

Commencez par forker ce repo, puis clonez sur votre machine.
Dans le dossier cloné, faites un `npm init` et répondez aux questions
Les librairies sont  à installer via NPM, n'oubliez pas l'option `--save`
Ex: `npm install jquery --save` 

Les librairies à utiliser sont : 
- [jQuery](http://jquery.com/download/)
- [moment.js](http://momentjs.com/)

## Spec
- le fichier HTML doit s'appeler `index.html`
- Le jour et l'année sont des `<input>` de type `text` ou `number`
- Le mois est un `<select>` avec la liste des mois
- Un `<button>` ayant comme label `Vérifier`
- Votre programme doit vérifier que le jour est compris entre 1 et 31
- L'année doit etre supérieure à 0
- En cas d'erreur, afficher le message correspondant dans une `<div id="message" class="error">`  et changez la bordure du champs correspondant en rouge
- En cas de réussite affichez une `<div class="overlay">` qui occupe tout l'écran et afficher en taille de texte de `100pt` le jour correspondant ainsi qu'un `<button id="restart">` contenant le label `Recommencer`
- Rapprochez vous au maximum du design imposé dans les screenshots

---

Codes hexadécimaux des couleurs utilisées :
- #ff7473
- #fff
- #34314c
- #47b8e0
- #9055A2;
- #D499B9;

La font utilisée est [Open Sans](https://fonts.google.com/specimen/Open+Sans)

Pour centrer verticalement et horizontalement avec flexbox :
[Centering in CSS: A Complete Guide - CSS tricks](https://css-tricks.com/centering-css-complete-guide/)

Créez également un fichier `.gitignore` donc le contenu est :
```
node_modules/
```

N'oubliez pas de nettoyer votre code avant de committer.
Une fois terminé, publiez votre travail sur une Github Page

## Screenshots

![Etat normal](https://raw.githubusercontent.com/SimplonTlse02/what-a-day/master/img/normal.jpeg)
Etat normal

![Hover du bouton](https://raw.githubusercontent.com/SimplonTlse02/what-a-day/master/img/hover.jpeg)
Hover du bouton

![Erreur](https://raw.githubusercontent.com/SimplonTlse02/what-a-day/master/img/error.jpeg)
Erreur

![Résultat](https://raw.githubusercontent.com/SimplonTlse02/what-a-day/master/img/result.jpeg)
Résultat
