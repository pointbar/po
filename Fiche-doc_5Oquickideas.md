# Synthèse de 50 quick Ideas To get your User Stories Better

## Créer des US

Ce chappitre est dédié à la création de US.

On y décrit comment une US doit ête écrite et quelles questions elle doit soulever.

### Raconter des histoires au lieu de les écrire

On insiste sur l'importance de la discussion vs. le hand-over, c'est à dire la pratique consistant à détailler un cahier des charges.  
on insiste sur l'importance d'avoir réellement une discussion avant de créer une US.  

### Ne pas s'inquiéter trop du format

on insiste sur l'importance d'expérimenter différents types de format d'US et ne pas trop se focaliser sur "As a ... In order to ... I want ... "

### Décrire un changement de comportement

Comment le comportement de l'utilisateur va changer ?

Dans INVEST, les idées qu'une US doit être d'une part Indépendante et avoir de la Valeur et d'autre part Small sont souvent dificiles à réconcilier.

La conséquence est souvent de favoriser la petite taille de la US au détriment de la valeur.

        J'ai besoin de précisions ou d'exemples pour 
        m'aider à capter en quoi il est dificile de 
        concilier "small" et "independent / value"

Pour contourner ce problème, on invite à se concentrer sur la description du changement dans le comportement de l'utilisateur qui est attendus comme résultat de la US.  

Par exemple au lieux de d'écrire "Etre capable d'importer des contacts",  on préfère écrire "Etre capable d'importer plus de contacts plus vite".

Cela permet d'orienter la conversation vers la valeur ajouté et de mieux comprendre la complexité. A quels point souhaitent-on aller plus vite ? Quel est l'ampleur de la différences entre "des contacts" et "plus de contact" ?  
Répondre à ces questions va permettre de proposer la solution la plus simple pour atteindre le changement qui a le plus de valeur.

### Décrire le changement provoqué dans le système

Comment les règles ou le fonctionnement va changer ?

        Y a-t-il une methode de description de la US? 
        Cette description doit-elle faire partie du 
        "titre"? Ou bien doit elle être intégrée d'une
        façon ou d'une autre à la storie? Cette 
        dernière hypothèse ne semble pas coller avec 
        l'idée de "small". Cependant, est-ce que la US
        "Etre capable d'importer plus de contacts 
        plus vite" décrit le changement provoqué dans 
        le système?

#### Bénéfices

Cela provoque une discussion sur ce qui existe déjà et comment on espère le modifier.

Pour que tous le monde comprenne les implications liées à l'embarquement d'une US. Pour comprendre l'ampleur et la complexité du travail.

        Est-ce que les réunions d'affinages sont là
        pour ça? Formuler de la façon la plus idéale 
        possible la storie peut-il être considérer 
        comme un affinage? Si j'ai bien compris les 
        réunions d'affinage sont là pour "découper" les 
        stories, et donc pour justement comprendre 
        l'ampleur et la complexité du travail. Est-ce 
        valable de voir la chose de cette façon?

#### Comment ça marche

En ajoutant à l'US quelquechose comme " Alors qu'aujourd'hui nous ... " ou " Là où nous faisons ...", "A la place de ...".  

Essayer d'utiliser un verbe qui décrit une nouvelles action ou un comportement nouveau.  

        Un peu la même question que plus haut. Ces 
        formules devraient-elles être incorporées au 
        titre de la storie?

### Approcher les US comme des epériences qui se suffisent à elles même

Pour éviter de créer des US trop petites qui n'ont pas assez de valeur.

Pour ne pas impliquer le reste du projet en cas d'échec.

Pour conserver l'implication des parties prenantes

        Avoir un exemple serait cool, mais ça n'est 
        peut être pas dans le livre.

### Eviter le générique

Eviter les US du style "En tant qu'utilisateur, je veux pouvoir me connecter avec un compte utilisateur de n'importe quel réseaux social pour ne pas avoir besoin de me rappeler d'autres identifiant et mot de passe".

"L'utilisateur" est quelque chose qu'on doit éviter à tout prix. Une catégorie aussi générique empèche d'orienter la conversation vers le réel utilisateur.

En essayant d'avancer en rateau vers tout les réseux sociaux, on risque de générer un effort et un coût inutile. Nous avons besoin de cibler.

### Comment ça marche

Il faut identifier les utilisateur à qui s'adresse réellement le produit.

Il faut utiliser les parsonae afin d'identifier les différents segements d'utilisateurs à qui on veux s'adresser.

On peut ajouter confronter ces personae à la check list de Stephen Wendel :

- une expérience anterieur de cette action (US)
- une expérience anterieur d'un produit et ou/canal similaire
- une relation avec l'organisation ou la société
- une motivation existante
- une motivation physique, psychologique ou économique à agir

#### A lire 

Anatomy of a Live Music Fan, BandsInTown
- http://www.slideshare.net/CellfishInc/bandsintown-reveals-what-makes-live-music-fans-tick-14065294

## Evaluer les zones de contrôle et sphères d'influence

Willam Dettmer 

Les trois zones d'un système

Zone de contrôle : inclus toutes les choses dans un système qu'on peut changer directement.

Zone d'influence : les activités qu'on peut impacter mais sur lesquels on a pas le contrôle total.

Environement externe : les éléments sur lesquels on a aucune influence.

Le besoin de l'utilisateur ("Afin de ..." ) doit se situer dans la zone d'influence de l'équipe de dévellopement et le délivrable ("Je veux ...") dans leur zone de contrôle.

Par exmple le besoin utilisateur ne dois pas être le besoin de l'équipe de dévelopement. Sauf à considérer qu'il s'agit d'une micro-US qui fait partie d'une US plus large. Dans ce cas il faudra garder l'attention sur la réussite de la grosse US plutôt que des micro-US.

De la même façon, si le besoin utilisateur est déterminé comme un aspect technique sur lequel l'équipe a directement la main, on peut penser que le besoin réel est dissimulé dans l'US (par exemple : Afin que que le temps d'export soit diminué ... ).

En revanche le délivrable doit être dans la zone de contrôle de l'aquipe. Si ce n'est pas le cas, c'est le signe que la story est tout simplement irréalisable OU qu'il s'agit d'une des story partiellement accionable à commencer rapidement car elle néscessite la colaboration de spécialiste ou tier-partie. 

### Comment ça marche

Se débarrasser des fausses US et des US qui dissimule le vrai besoin ou les remplacer. 

Concaténer les micro-US en une US plus large.

Splitter les US partiellement actionnable entre les parties faisable par l'équipe et celle qui nescessite l'intervantion d'une tier-partie.

#### Donner une date de péremption aux US

Identifier les deadlines.

Ecarter les US non prioritaires.

Imposer une durée de vie minimum aux stories (par exemple : on ne peut pas embraquer de stories qui sont à finir en moins d'un mois)

Ne mettre des DLC que sur les stories avec une échéance fixe et extérieure.  

## Planifier avec les US

### Se fixer des deanlines pour confronter les risques majeurs

Le fait de délivrer fréquement peut pousser les parties prenantes et les équipes de dévellopement à choisir des tâche facile, petite et qui se détourne de la vision à long terme et des risques principaux à confronter. 

Se fixer des dead lines sur ces risques permets de réduire cette tendance à repousser les travaux dificiles et risqués. 

#### Comment ça marche 

Alistaire-Cockburn propose d'alterner entre "paying to learn" et "paying to ad business value" et résume ainsi "dévelope pour ajouter de la valeur ... dès que le risque est abaissé". 

cf Lean

On peut créer des US d'apprentissage avec une dealine pour confronter ces risques.

### Utiliser un backlog priorisé

Ne pas avoit trop de cartes. 

Ne pas diviser les grands blocs en petites tâches avant le moment de réaliser ces tâche ou l'on perd de vue la vision long terme et on investit du temps dans un travail inutile. 

### Regrouper les US en fonctino de leur impact

A lire : 

Impact Mapping, Gojko

### Créer une US map

Lire : User Storry Mapping, Jeff Patton

        Faudrait-il alors préciser le type 
        d'utilisateur? Dire par ecemple "Si ma 
        grand-mêre se connecte à facebook, elle veut 
        pouvoir avoir des nouvelles de ses petits 
        enfants dans son fil d'actualité", plutôt que 
        "En tant qu'utilisateur, je veux que mon fil 
        d'actu se remplisse en fonction de 
        "l'importance" de mes contactes facebook"?

Chappitre suivant
