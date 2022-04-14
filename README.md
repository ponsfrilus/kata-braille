# Kata braille

> **À propos**
>
> ⓘ Ceci est la donnée d'un [kata], un _exercice de programmation_ qui se
> déroule généralement dans le cadre d'un [coding dojo]. Il est proposé aux
> membres du dojo de l'[EPFL] et fait partie d'une collection de différents
> katas identifiés par le tag **[epfl-dojo-kata]** sur GitHub.  
> Vous êtes plus que bienvenu d'essayer de le réaliser dans le langage de
> programmation de votre choix. Lorsque c'est terminé, ajoutez-vous à la liste
> de ceux qui l'ont fait dans ce document en proposant une [Pull Request]. Vous
> pouvez également **[epfl-dojo-kata]** partager votre intérêt pour ce dépôt en
> le «[stargazant]».  
> Bonne lecture et bon code !

[kata]: https://fr.wikipedia.org/wiki/Coding_dojo#Kata
[coding dojo]: https://fr.wikipedia.org/wiki/Coding_dojo
[EPFL]: https://www.epfl.ch
[epfl-dojo-kata]: https://github.com/topics/epfl-dojo-kata
[Pull Request]: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
[stargazant]: https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars


## Introduction

> Le braille est un système d’écriture tactile à points saillants, à l’usage
> des personnes aveugles ou fortement malvoyantes. Le système porte le nom de
> son inventeur, le Français Louis Braille (1809-1852) qui avait perdu la vue à
> la suite d'un accident.
>
> En braille standard, un caractère est représenté dans une matrice de six
> points sur deux colonnes, chaque caractère étant formé par un à six points en
> relief.
>
> Source : https://fr.wikipedia.org/wiki/Braille


## But

Le but de ce kata est d'écrire un convertisseur de texte vers braille et
invérsément (de braille vers texte).

On utilisera ici le braille standard, sur 6 points. Le système « Antoine sera 
utilisé pour les chiffres. Les lettres diacritées propres au français doivent 
également être gérées, tout comme les majuscules.

Le standard unicode propose tous les caractères nécessaires au braille, de
U+2800 – U+283F (6 points) et jusqu'à U+28FF pour 8 points
(https://www.obliquity.com/computer/html/unicode2800.html).

La correspondance entre un caractère braille et une lettre dépendant de la
langue, on utilisera ici le Français.


## Pour aller plus loin

Voici quelques idées pour faire évoluer le projet :
* Adapter au braille informatique, à 8 points (https://fr.wikipedia.org/wiki/Braille#Braille_informatique) ;
* Réaliser une traduction directe (https://www.lexilogos.com/clavier/braille.htm) ;
* Permettre, en option, de choisir la langue ;
* Imaginer un système permettant de rendre les caractères en Braille tactiles ;
* etc...

Le **[kata-morse](https://github.com/ponsfrilus/kata-morse)** est dans le
même genre, n'hésitez pas à le faire aussi !


## Je l'ai fait 💪

* La version de [@octocat](https://github.com/octocat) a été faite en `langage`
  et est disponible [ici](https://#).
