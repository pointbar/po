# GitHub Mode d'emploi

## Pour quoi

Il y a plein d'usages possibles à GitHub mais en gros ça permet :

- de créer un site web super rapidement
- de faire de l'écriture collaborative
- de créer des kanban avec des ressources associées

Et en vrai, à la base, c'est pour écrire du code (informatique) à plusieurs. C'est le principe du Git, on voit facilement toutes les versions qui existent et qui ont pu exister. Du coup, c'est cool pour du code mais ça marche très bien pour du français ou de l'anglais ou n'importe quel langage en fait ...

## Pour qui

Pour tous ceux qui ont besoin de diffuser du contenu ou de le partager surtout si on a envie de bosser à plusieurs dessus.

## Créer un compte GitHub

Se rendre sur <https://www.github.com>

Choisir un blaze.  
Renseigner une adresse mail.  
Choisir un mot de passe.  
Cliquer sur signup.  

## Créer un dépot

Un dépot, c'est comme un disque dur mais "distant". C'est à dire qu'il n'est pas chez toi, "en local".

Cliquer sur le bouton "new repository" depuis la page d'accueil personalisée de GitHub (On la retrouve en cliquant sur le chat).

![new repository](https://github.com/pointbar/po/blob/master/Media_GitHub_Mode_d_emploi/new_repository.png?raw=true)

### Penser à créer un readme.md au moment de l'initialisation du dépot

En cliquant sur la case à cocher.

Ca crée un premier fichier dans notre dépot. Ca permet de beaucoup moins galérer ensuite.

![créer le readme](https://github.com/pointbar/po/blob/master/Media_GitHub_Mode_d_emploi/case_a_cocher.png?raw=true)

## Installer GitHub Desktop

GitHub Desktop est une appli qui permet de cloner le dépot "en local" sur ton ordinateur. En fait, c'est une appli qui lit les .git, les fichiers qui gardent tout l'historique des différentes versions.

Télécharger GitHub Desktop : <https://desktop.github.com/>

On s'identifie dedans avec les mêmes identifiants que sur GitHub.

A partir de là on va retrouver facilement le dépot qu'on a créé sur GitHub.

On va dans "File", "clone repository" et on copie/colle l'URL ou le "nom du propriétaire/nom du dépot".

Maintenant, on a sur notre ordianteur une copie de tous les contenus présents dans le dépot "distant".

## Installer Visual Studio Code

C'est le dernier truc qu'on installe.

Visual Studio Code est un éditeur. C'est à dire qu'il permet (entre autre mille trucs ...) d'écrire sur un document et notamment de prévisualiser la mise en page d'un document en MarkDown, le langage dont on parle plus bas.

Télécharger Visual Studio Code : <https://code.visualstudio.com/>

Dans VSC, on va sur "Fichier","ouvrir" et on choisit le dépot dans le dossier "GitHub".

On va voir apparaitre tous les contenus sur notre gauche.

A partir de maintenant, on a toujours le choix de travailler directement via l'interface de GitHub sur leur site ou en local depuis notre éditeur. On va voir plus bas comment on fusionne les deux fichiers.

## Quelques utilisations de MarkDown

MarkDown est un langage informatique qui va nous servir à mettre en page du texte et des contenus multi-media. C'est un langage basé sur le HTML, le langage des sites web.

En créant notre premier fichier, on en fait un fichier MarkDown en ajoutant .md à la fin. C'est ce qui fait que les ordinateurs vont comprendre qu'on utilise ce langage.

Le mieux est de regarder ces petits conseils sur VSC ou un autre éditeur pour voir à la fois le texte RAW (brut) et la mise en page.

Très simplement, on peut mettre en page :

- des titres en ajoutant un ou plusieurs #. Plus on en met plus on descend dans les niveaux de titre. Par exemple :

        # Titre
        ## Titre
        ### Titre
        #### Titre


# Titre
## Titre
### Titre
#### Titre

- de l'italique en encadrant de * de chaque côté :

        *italique*

*italique*

- du gras en encadrant de deux ** de chaque côté :

        **gras**

**gras**

- des images en utilisant ![le texte qui s'affiche en cas de bug](l'url de l'image) :

        ![image](https://i1.wp.com/www.berejeb.com/wp-content/uploads/2013/12/agile-dilbert-story.gif)

![image](https://i1.wp.com/www.berejeb.com/wp-content/uploads/2013/12/agile-dilbert-story.gif)

## Commit, push and pull

Un commit, c'est un point de sauvegarde, une version du doc sur lequel on travaille. Le mieux, s'est de donner un nom à cette version, à ce commit, en écrivant un petit message qui explicite ce qu'on a fait de nouveau.

Une fois qu'on a tapé du texte dans notre .md :

Soit on est sur l'interface de GitHub, tout en bas de l'éditeur, on trouve un gros bouton vert pour commit.

Soit on est dans l'éditeur de texte (VSC par exemple), on doit d'abord sauver les modifications "en local" en appuyant sur "commande+s" puis on crée le commit en cliquant sur le petit dessin de fourche à gauche.

![fourche](https://github.com/pointbar/po/blob/master/Media_GitHub_Mode_d_emploi/fourche.png?raw=true)

On écrit le nom de notre commit et appuis sur "commande+entrer".

De là, on veut que les modifications "en local" soient copiées sur le dépot "distant". Ca s'appelle un push. Ca va transformer la branche "master", c'est à dire, la version partagée. On en dira un peu plus plus bas sur les notions de branches. Si on voulait au contraire copier la branche "master" sur notre version "local" du dépot, on fait un "pull.

Dans les deux cas, on clique sur le même bouton, en bas à gauche.

![bouton push et pull](https://github.com/pointbar/po/blob/master/Media_GitHub_Mode_d_emploi/bouton_push_et_pull.png?raw=true)

## Visualiser le contenu du dépot grâce à Multibao

Ca y est, votre contenu est en ligne !

On peut le visualiser dès maintenant via multibao en tapant dans le navigateur :

    "https://www.multibao.org/#le nom du propriétaire/le nom du dépot/"

De cette façon, vous ne pouvez pas choisir un autre thème que celui de multibao.

## Ajouter un thème grâce à .yml

Pour choisir le thème, on créé un fichier qu'on appelle config.yml et en tapant simplement sur la première ligne :

    remote_theme: le nom du thème qu'on préfère

par exemple :

    remote_theme: daktary-team/maquillage

## Créer une page GitHub (Visualiser le dépot au travers d'un site web)

Pour avoir un vrai site sans passer par multibao, on peut créer une page GitHub.

On va dans "settings" à doite du menu du dépot sur GitHub.

On descend un peu jusqu'à GitHub Pages et on clique sur "Save" après avoir choisi "Master Branch" comme "source".

![GitHub Pages](https://github.com/pointbar/po/blob/master/Media_GitHub_Mode_d_emploi/github_pages.png?raw=true)

Ca y est, on a un site. L'adresse est indiquée là.

## Inviter des collaborateurs

Les collaborateurs sont les personnes qui peuvent modifier les contenus sans demander d'autorisation. Ca permettra de bosser à plusieurs.

Pour faire ça, il faut être propriétaire du dépot. On trouve l'option dans le menu, tout à droite, dans "Settings". Puis dans "collaborator".

## Fork and merge

Un projet est comme un arbre. A chaque fois qu'on commence une nouvelle version du projet, c'est une nouvelle branche, un "fork". A tout moment, on peut proposer au propriétaire de la branche "master", du tronc, de refusionner les deux branches, de faire un "merge".

C'est comme "push un commit" mais sur un projet dont on est pas propriétaire.

## Revue pull request

L'opération de merger est une "pull request". C'est-à-dire qu'on demande à importer les nouvelles modifications sur la branche "master".

Dans ces cas-là, le propriétaire de la branche va faire une revue pour voir s'il accepte ou refuse les nouvelles modifications.

## Utiliser GitHub pour la gestion de projet

GitHub a une fonction de gestion de projet sous forme de kanban. On trouve cette fonction dans l'onglet "Projects" d'un dépot GitHub.

De là un gros bouton vert permet de créer un projet, de lui donner un nom et de choisir le nombre de colonnes de notre kanban.

## Supprimer un dépot

A ne faire qu'en dernier recours. Bien penser à vérifier que plus personne ne travaille sur une version de ce projet sauf si on veut mettre des gens dans la merde.

Tout en bas de setting, on trouve l'option "Delete this repositoty".
