# 2.0 Administration

L'administration du module est accessible depuis le backoffice de Xoops. Il suffit de cliquer sur l'icône du module afin de pouvoir l'administrer. 
Vous noterez que vous pouvez accéder aux différentes parties de l'administration du module par un système d'onglets, ceci afin de vous faciliter l’utilisation du module. 
 
####Articles (Références) 
C’est dans cette partie de l’administration du site que vous allez pouvoir créer vos références (articles). Le module vous présente, tout de suite en dessous des onglets, un bouton vous permettant de rajouter un nouvel article.  

Sous ce bouton, se trouve la liste des références existantes. On trouve, le numéro de la référence, son titre, sa catégorie, son état (en ligne ou pas), une date dite « manuelle » et une colonne vous permettant d’éditer ou de supprimer une référence. 

Lorsque vous ajoutez une référence, l’écran de saisie vous présente les champs suivants 
- Catégorie : C’est la catégorie à laquelle rattacher la référence 
- Titre : Le titre de la référence 
- En ligne: Avec cette option, vous pouvez désactiver des références, cela vous permet de ne pas les afficher tout en les conservant (lorsque l’option est sur Non). 
- Date manuelle : Vos références n’ont pas forcément été réalisées à une date précise. Cette zone vous permettra de rentrer une date comme par exemple Janvier 2009 
- Date de publication de l’article: Cette zone vous demande de renseigner, contrairement à la précédente, une date précise, dans le but de trier vos références entre elles lorsqu’elles font partie d’une même catégorie. 
- Poids : Cette zone vous permet d’ordonner manuellement le tri des références les unes par rapport aux autres 
- URL : Indiquez par exemple l’adresse du site web de votre client (qui concerne la référence en cours) 
- Texte: Rentrez dans cette zone tout texte que vous jugerez nécessaire à la description de votre référence. 
- Mots clés : Cette zone n’est visible que si dans les options du module vous avez décidé d’activer les mots clés. Rentrez les mots clés qui permettront de catégoriser au mieux votre référence. 
- Image courante : Cette zone n’est visible que lorsque vous éditez une référence et que celle-ci contient une image. Cela vous permet de visualiser l’image et de la supprimer. 
- Image  :  Cette zone vous permet de choisir une image depuis votre ordinateur 
- Texte de l’image : cette zone sera affichée sous l’image lorsqu’un visiteur de votre site cliquera dessus. 

Cet ensemble de 3 zones se répète 10 fois, vient ensuite : 
- Fichier attaché : Vous permet de joindre un fichier à votre référence (par exemple un PDF)  

Une fois la référence créée, elle est immédiatement visible sur le site (si vous l’avez activée). 
####Catégories 
Dans cet onglet, sont affichées toutes les catégories auxquelles sont rattachées vos références. 

Comme dans l’onglet précédent, un bouton directement placé sous les onglets vous permet de tout de suite créer une nouvelle catégorie.  

En dessous, se trouve la liste des catégories actuelles (Numéro, Titre, Poids et une colonne vous permettant d’éditer ou de supprimer une catégorie). 

Si vous cliquez sur le bouton intitulé « Ajouter un élément » un écran de saisie se présente pour créer une nouvelle catégorie. Cet écran contient : 
- Le titre de la catégorie 
- Son poids. 
  
  Le poids vous permet d’ordonner les catégories les unes par rapport aux autres. 
Sont d’abord affichées les catégories de poids le plus faible puis les catégories de poids supérieur. 
- La description de la catégorie 
- Les permissions de lecture sur la catégorie 

Note : Lors de la suppression d’une catégorie, c’est à vous qu’il appartient de vérifier que des références ne sont pas rattachées à la catégorie. 
 
####Textes 
Avec cet onglet vous pouvez indiquer au module un message à afficher sur sa page d’index. 
 
####Permissions 
Avec cet onglet, vous pouvez régler les permissions d’accès à chacune des catégories. Il vous suffit de choisir,  pour chacun de vos groupes Xoops, leurs droit de visualisation pour chacune des catégories. 
 
####Maintenir le cache est les tables 
Ce n’est pas un onglet de l’administration mais un lien qui se trouve au dessus des onglets.  

En cliquant sur ce lien, le module va entamer une série de taches de maintenance et de vérifications sur les tables qu’il utilise dans la base de données.  

Le module utilise aussi un système de « cache » (sur les requêtes SQL) afin d’améliorer ses performances, le clic sur ce lien vous permettra de régénérer ce cache. 