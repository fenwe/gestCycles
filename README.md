gestCycles
==========

fichier: gestCycles-0.1.js
version:0.1
auteur:pascal TOLEDO
date: 2012.12.02
source: http://legral.fr/intersites/lib/perso/js/
depend de:
  * gestLib (facultatif)
description:
* appelle une fonction par cycle avec le meme ecart temps entre les 2 appels en soustrayant le temps d'execution de la fonction de la consigne
 exemple: votre fcrt doit etre appellé toutes les 100ms mais votre function dure 80ms. Le prochain appelles, se fera donc 20ms apres la fin de l'appel precedent.
vous etes assuréez d'etre au plus pres du temps consigne tant que la duree de votre fonction ne depasse pas votre consigne.

* calcul de la moyenne de la duree de la fonction
 Le nombre de point de la moyenne est parametrable. Plus il y a de point plus la moyenne est fidele mais un trop grand nombre de points augment le temps d'excution de la fonction

bug:
* la pause n'est pas operationnelle
