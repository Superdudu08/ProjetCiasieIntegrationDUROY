## Projet d'intégration, reproduction du design d'un blog - Maxence Duroy

## Lancer le projet 

Pour compiler le SCSS en CSS : `sass scss/style.css css/style.css`

## Note sur le div 'black separator'

Je pense que du point de vue sémantique, c'est mauvais d'utiliser un `<div class="blackSeparator">` plutôt qu'un simple `<hr>`.
Cela dit, en essayant d'utiliser le `<hr>` et en changeant son style, je n'obtenais pas de résultat satisfaisant, avec une barre distordue, probablement à cause de la rotation.
C'est pourquoi j'ai utilisé cette méthode.
