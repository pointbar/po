# GitHub Mode d'emploi

## Pour quoi

Il y a plein d'usage possibles à GitHub mais en gros ça permets :

- de créer un site web super rapidement
- de faire de l'écriture colaborative
- de créer des kanban avec des ressources associées

Et en vrai, à la base, c'est pour écrire du code (informatique) à plusieur. C'est le principe du Git, on voit facilement toutes les versions qui existe et qui ont pu exister. Du coup, c'est cool pour du code mais ça marche très bien pour du français ou de l'anglais ou n'importe quel langage en fait ...

## Pour qui

Pour tout ceux qui ont besoin de diffuser du contenu ou de le partager surtout si on a envie de bosser à plusieur dessus.

## Créer un compte GitHub

Se rendre sur <https://www.github.com>

Choisir un blaze.  
Renseigner une adresse mail.  
Choisir un mot de passe.  
Cliquer sur signup.  

## Créer un dépot

Un dépot, c'est comme un disque dur mais "distant". C'est à dire qu'il n'est pas chez toi, "en local". 

Cliquer sur le bouton "nem repository" depuis la page d'accueui personalisé de GitHub (On la retrouve ne cliquant sur le chat)

![new repository](https://github.com/pointbar/po/blob/master/Media_GitHub_Mode_d_emploi/new_repository.png?raw=true)

### Penser à créer un readme.md au moment de l'initialisation du dépot

En cliquant sur la case à cocher. 

Ca créé un premier fichier dans notre dépot. Ca permet de beaucoup moins galérer ensuite.

![créer le readme](https://github.com/pointbar/po/blob/master/Media_GitHub_Mode_d_emploi/case_a_cocher.png?raw=true)

## Installer GitHub Desktop

GitHub Desktop est une appli qui permet de cloner le dépot "en local" sur ton ordinateur. En fait, c'est une appli qui lit les .git, les fichiers qui gardent tout l'historique des différentes versions.

Télécharger GitHub Desktop : <https://desktop.github.com/>

On s'identifie dedans avec les même identifiants que sur GitHub.

A partir de là on va retrouver facilement le dépot qu'on a créé sur GitHub.

On va dans "File", "clone repository" et on copie/colle l'URL ou le "nom du propriétaire/nom du dépot".

Maintenant, on a sur notre ordianteur une copie de tous les contenus présents dans le dépot "distant".

## Installer Visual Studio Code

C'est le dernier truc qu'on installe.

Visual Studio Code est un éditeur. C'est à dire qu'il permet (entre autre mille tucs ...) d'écrire sur un document et notament de prévisualiser la mise en page d'un document en MarkDown, le langage dont on parle plus bas.

Télécharger Visual Studio Code : <https://code.visualstudio.com/>

Dans VSC, on va sur "Fichier" ,"ouvrir" et on choisi le dépot dans le dossier "GitHub".

On va voir apparaitre tous les contenus sur notre gauche.

A partir de maintenant, on a toujours le choix de travailler directement via l'interface de GitHub sur leur site ou en local depuis notre éditeur. On va voir plus bas comment on fusionne les deux fichiers.

## Quelques utilisations de MarkDown

MarkDown est un langage informatique qui va nous servir à mettre en page du text et des contenus multi-media. C'est un langage basé sur le HTML, le langage des sites web.

En créant notre premier fichier, on en fait un fichier MarkDown en ajoutant .md à la fin. C'est ce qui fait que les ordinateurs vont comprendre qu'on utilise ce langage.

Le mieux est de regarder ces petits conseils sur VSC ou un autre éditeur pour voir à la fois le text RAW (brut) et la mise en page. 

Très simplement, on peut mettre en page :

- des titres en ajoutant un ou plusieurs #. Plus on en mets plus on descend dans les niveaux de titre. Par exemple :

# Titre
## Titre
### Titre
#### Titre

- de l'italique en encadrant de * de chaque côté :

*italique*

- du gras en encadrant de deux ** de chaque côté :

**gras**

- des images en utilisant ![le text qui s'affiche en cas de bug](l'url de l'image) :

![image](https://i1.wp.com/www.berejeb.com/wp-content/uploads/2013/12/agile-dilbert-story.gif)

## Commit, push and pull

Un commit, c'est un point de sauvegarde, une version du doc sur lequel on travail. Le mieux, s'est de donner un nom a cette version, à ce commit, en écrivant un peit message qui explicite ce qu'on a fait de nouveau.

Une fois qu'on a tapé du text dans notre .md :

Soit on est sur l'interface de GitHub, tout en bas de l'éditeur, on trouve un gros bouton vert pour commit.

Soit on est dans l'éditeur de text (VSC par exemple), on doit d'abord sauver les modifications "en local" en appuyant sur "commande+s" puis on créé le comit en cliquant sur le petit dessin de fourche à gauche.

![fourche](https://github.com/pointbar/po/blob/master/Media_GitHub_Mode_d_emploi/fourche.png?raw=true)

On écrit le nom de notre commit et appuis sur "commande+entrer".

De là, on veut que les modification "en local" soient copiées sur le dépot "distant". Ca s'appel un push. Ca va transformer la branche "master", c'est à dire, la version partagée. On en dira un peu plus plus bas sur les notions de branches. Si on voulait au contraire copier la branche "master" sur notre version "local" du dépot, on fait un "pull. 

Dans les deux cas, on clique sur le même bouton, en bas à gauche.



Ajouter un thème grâce à .yml
===

Créer une page GitHub (Visualiser le dépot au travers d'un site web)
===

## Inviter des collaborateurs

Les collaborateurs sont les personnes qui peuvent modifier les contenus sans demander d'autorisations. Ca permettra de bosser à plusieurs.

Pour faire ça, il faut être propriétaire du dépot. On trouve l'option dans le menu, tout à droite, dans "Settings". Puis dans "collaborator".

Fork and merge
===

Revue pull request
===

Utiliser GitHub pour la gestion de projet
===

Supprimer un dépot
===
