# Affermir le concept de User Story

![image](https://i1.wp.com/www.berejeb.com/wp-content/uploads/2013/12/agile-dilbert-story.gif)

## Une user story c'est quoi

=> Sources: 

*<http://blog.thiga.fr/glossaire/definition-user-story/>

Une user story est une description fonctionnelle d'une fonctionalité à développer. Elle spécifie les utilisateurs concernés, ainsi que la **valeur** qu'elle ajoutera à leur utilisation du produit.
Bien qu'il y ai à priori beaucoup de libertés sur la forme physique et les formules verbales que peut prendre une user story, il sera souvent de bon aloi de la formuler suivant ce model: *En tant que **qui**, je veux **quoi** afin de **pourquoi***. À tout le moins, lorsqu'on débute.

La user story réponds à l'un des principes les plus importants de l'agilité, à savoir, minimiser le travail inutile.  
Pour bien comprendre cette idée, il convient de tenir compte des utilisateurs du produit, et de l'impact que la prochaine partie du travail de développement aura sur l'utilisation de ce produit.

L'imprtance du préciser le **pourquoi** dans l'intitulé de la story s'explique par une réflexion profondément centrée sur la **valeur**. En quoi l'ajout de tel ou tel fonctionalité impactera le comportement de l'utilisateur lors de l'usage du produit.  
Pouvoir mesurer cette valeur ajoutée est primordiale, en raison notemment de la nécésité de **prioriser** les stories dans le **Backlog**.

Il est important également de préciser **qui** est concerné par la story. Premièrement parce qu'il n'est pas toujours nécessairement question d'un utilisateur. Ce peut être: "en tant que *développeur*, je veux *tel ou tel chose*, afin *d'accélerer tel ou tel procéssus*". Deuxièmement parce qu'il est de bon ton de ne pas généraliser le concept d'utilisateur. Il y a en effet plusieurs segments d'utilisateurs. On pourrait même aller plus loin et dire que tous les utilisateurs sont différents.  
En tout cas, préciser le **qui** semble être très important.

## INVEST

=> sources:

*<https://www.berejeb.com/2013/12/bien-definir-en-agile-investir-dans-vos-stories/>

*<http://referentiel.institut-agile.fr/invest.html>

INVEST est une grille de critère, un filtre au travers du quel seul passeront les user stories répondants aux carractéristiques requises. C'est un outil permettant de vérifier point par point les différentes qualités d'une story.

### I pour indépendant

- Les stories doivent être indépendants l’une de l’autre. Ce qui permettra a l’équipe de les réaliser et les livrer sans qu’ils affectent l’ensemble des livrables.

- Elles doivent pouvoir être implémentées avant ou après n'importe quelle autre story.

- une erreur classique étant par exemple d'argumenter que "la Story sur la prise de commande implique d'avoir ouvert un compte, donc il faut réaliser en premier celle concernant l'identification (login) de l'acheteur". C'est un peu comme supposer qu'on ne peut écrire le chapitre 2 d'un roman qu'après avoir achevé le chapitre 1: plus facile, mais avec un peu d'imagination on arrive très bien à inverser cette séquence. Dans notre exemple l'équipe de développement mettra en place les "bouchons" nécessaires pour simuler un utilisateur identifié.

### N pour négociable... et négocié

- Un récit doit être le fruit d’une collaboration entre l’équipe et le client, afin de fournir le maximum de valeur pour ce dernier. Un bon récit ne représente pas un contrat détaillé de fonctionnalités, mais se focalise sur l’essence de la fonctionnalité. La négociation est un élément fondamental pour comprendre l’essence du besoin du client.

- ne formuler dans un premier temps que l'essentiel, à savoir l'objectif fonctionnel recherché; on évitera par exemple de spécifier dans une User Story des éléments techniques, par exemple "En tant qu'acheteur, lorsque j'écris dans le champ texte puis que je clique sur le bouton Recherche, la liste à gauche du champ de recherche est renseignée avec les articles correspondants". Ces détails d'implémentation feront l'objet d'une discussion permettant d'identifier la meilleure solution; initialement, une formulation du type "L'acheteur peut chercher des articles par mot-clé" est suffisante pour l'estimation et la planification.

### V pour valuable

- Ou **veticale** c'est à dire, ayant de la valeur en soit.

- Une story doit avoir de la valeur pour le client. C’est la principale caractéristique d’une story. Généralement, cette caractéristique est perdue lors d’un mauvais découpage de stories. Un bon découpage est un découpage qui livre de la valeur pour le client à chaque story. Imaginez que vous découpez un gâteau à couches par exemple, Personne ne voudra d’un gâteau découpé horizontalement, tout le monde veut plutôt un morceau qui contient l’ensemble des couches. C’est de même pour la story. Ces couches peuvent être assimiles aux couches réseau, persistance, business et interface utilisateur etc. Livrer un ensemble fonctionnel, partie par partie au client a toujours de la valeur.

- représenter un incrément réellement utile pour l'utilisateur final ou du point de vue du client. Par exemple, "réaliser le schéma de la base de données pour la facturation" n'est pas un incrément ayant de la valeur en soi, mais une tâche technique. A contrario, "émettre une facture pour les achats d'articles en France" en laissant pour plus tard une seconde Story dont l'énoncé serait "émettre une facture pour des achats livrés depuis l'étranger" représente un meilleur découpage: chaque incrément permet de réaliser une partie distincte du chiffre d'affaires.

### E pour estimable

- Une story doit être estimable. Sans forcément avoir un estimé exact, nous pouvons en donner assez pour aider le client à prioriser et planifier l’implémentation des stories. C’est le rôle de l’équipe d’estimer, ceci dépendra éventuellement de l’expérience.

- Il arrive souvent que l’équipe n’a pas suffisamment d’informations pour estimer. Dans ce cas, cette dernière doit diviser la story en un “Spike” ayant une durée fixe (time-boxed) et permettant d’avoir assez d’information pour pouvoir estimer le reste de la story.

- être suffisamment comprise, mais également suffisamment précise. Il arrive parfois qu'on formule des User Stories qui représentent presque un projet à part entière, par exemple "Optimiser le calendrier de livraison des achats". Les conditions de satisfaction doivent être suffisamment précises et restreintes pour que l'équipe de développement puisse quantifier l'effort d'implémentation, sinon dans l'absolu du moins en termes de complexité relative. (L'équipe estime par exemple que "Livrer en deux fois lorsque des écarts supérieurs à une semaine séparent les dates de livraison de deux articles du panier" représente deux fois l'effort requis pour "Emettre la facture", cette dernière servant en quelque sorte d'étalon.)

### S pour small

- Une bonne story demande généralement peu de personnes-semaines (ou même peu de personnes-jours) pour être réalisée. Souvent, il viendrait à l’esprit que d’avoir moins de temps et de description mènerait à une mauvaise interprétation, mais l’objectif essentiel derrière ceci est de laisser les détails être élaborées par les conversations directes avec le client.

- La granularité exacte est fonction du nombre de personnes dans l'équipe de développement et de la durée de l'itération, le critère déterminant étant la possibilité de terminer au minimum une, et idéalement cinq ou six au minimum, User Stories dans une seule itération.

### T pour testable

- Ecrire une story implique une promesse cachée : “Je connais suffisamment ce que je veux que je pourrais écrire un test pour”. L’équipe devrait demander au client de l’information sur comment il compte tester sa story. Le plutôt que les tests sont définis, plus vite l’objectif réel est atteint. Généralement, si un client ne sait pas comment il va tester sa story, ceci montre que cette dernière n’est pas assez claire, ou qu’elle n’a pas beaucoup de valeur, ou que ce dernier a plutôt besoin d’aide pour la tester. Dernièrement, les tests non fonctionnels peuvent être considérées comme des requis qui doivent être testées. En déterminant comment réaliser ces tests, l’équipe se rend compte les besoins réels du client.

- être suffisamment bien comprise pour qu'il soit possible de fournir un exemple détaillé: "Lorsque j'achète l'article X au prix Y, sachant que la TVA sur la catégorie Livres est de Z, la facture doit indiquer le montant total suivant:…" La fonctionnalité envisagée doit entraîner de la part du produit des conséquences ou des comportements observables. Ainsi "Améliorer la performance" n'est pas une bonne User Story, il est préférable de préciser: "La page contenant les résultats de recherche doit s'afficher en moins de 2 secondes".

## Comment construire une user story

Voir Strory Mapping  
voir SMART  
Voir Backlog et affinage  
Voir <https://blog.myagilepartner.fr/index.php/2017/08/02/comment-bien-gerer-ses-user-stories/>  
Voir
<http://referentiel.institut-agile.fr/stories.html>