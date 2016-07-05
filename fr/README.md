#Documentation Références 
 
##Table des matières  
####Documentation Références 
####Présentation 
- Instant Zero
- Compatibilité Xoops 
- Fonctionnalités
- Environnement serveur
- Traductions
- Licence 
 
####Installation 
####Préférences du module 
- Nombre d'éléments par catégorie, sur la page d'index du module 
- Nombre d'éléments dans l'administration du module
- Editeur à utiliser
- Largeur des vignettes
- Hauteur des vignettes
- Chemin du dossier où stocker les images et vignettes (SANS slash final)
- URL du dossier où sauvegarder les images et vignettes (SANS slash final)
- Chemin du dossier où stocker les fichiers joints aux articles (SANS slash final)
- URL du dossier où sauvegarder les fichiers joints aux articles (SANS slash final)
- Utiliser les flux RSS ?
- Temps de cache du flux RSS (en secondes)
- Types mime autorisés pour les téléchargements
- Taille maximale des fichiers joints et des images
- Utiliser le système de tags ?
- Zone de tri à utiliser sur la page d’index pour trier les références ?
- Ordre de tri
- Config.php

####Administration
- Articles (Références)
- Catégories
- Textes
- Permissions
- Maintenir le cache est les tables

####Blocs 
- Dernières références
- Référence au hasard
- Nuage de mots clés du module
- Top des mots clés du module 

####Côté utilisateur 
- Page d’index
- Page des catégories
- Page d’une référence
- Flux RSS 

####Contenu du répertoire Extra  
- Autres scripts présents dans le répertoire Extra  

####Personnalisation de l’aspect des accordéons 
 
##Présentation 
Références est un module Xoops qui vous permettra de créer un nombre illimité de références clients. 

Il est réalisé en langage Php et utilise la base de données Open Sources Mysql. 
Ce programme a été développé pour s’insérer dans un environnement Xoops .  
 
L’avantage essentiel de ce produit par rapport aux solutions existantes sur le marché, c’est sa facilité de mise en œuvre puisque ce module est opérationnel en moins de 15 minutes (installation et paramétrage) 
 
####Instant Zero 
Ce module a été conçu avec le plus grand soin par la société Instant Zero. 

Instant Zero est une société de services en logiciels libres spécialisée dans le développement de solutions Open Source pour le gestionnaire de contenu Xoops. 

Notre principale activité consiste à développer des solutions Internet à partir de produits éprouvés, sécurisés, faciles d'utilisation et ne nécessitant pas de licences. 

Instant Zero peut vous aider pour la réalisation de votre charte graphique, pour installer et héberger votre site, effectuer des développements spécifiques à vos besoins (comme des modules Xoops), adapter des produits Open Source existants, vous former, mettre en place un certificat de sécurité etc. 

Vous pouvez consulter notre offre sur notre site internet : http://www.instant-zero.com 

Et vous pouvez nous contacter en nous envoyant un email à contact@instant-zero.com 
 
####Compatibilité Xoops 
Références  a été testé et est utilisé avec Xoops >= 2.3.3.  
 
Le module ne fonctionne pas avec la série 2.0.x de Xoops 
 
  
####Fonctionnalités 
 
- Catégorisation des références 

Chaque référence est rattachée à une catégorie afin d’organiser l’information. 
 
- Flux RSS des dernières références 
- Affichage moderne avec effet d’accordéon et « lightview » 
- Choix de l’éditeur de texte à utiliser pour créer ses références 
- Création automatique des vignettes de chaque copie d’écran 
- Possibilité d'utiliser un système de mots clés (TAGS) 
- Possibilité d'activer une notification lors de la création d'une nouvelle référence 
- Intégration à la recherche Xoops 
- Possibilité de cloner le module 
- Gestion de cache afin d’améliorer les performances sur un environnement fortement sollicité 
- Gestion des permissions sur les catégories 

  
####Environnement serveur 
Afin de fonctionner, Références nécessite un environnement web classique. 

Pour fonctionner, le module nécessite Php 5 (une version récente comme la 5.2) et Mysql 4.1 minimum. Il est en outre capable de fonctionner avec Apache 1 & 2 ainsi qu'avec IIS. 
 
####Traductions 
Le module est disponible en français et anglais, toutefois il est possible de le traduire dans d’autres langues sur simple demande auprès d’Instant Zero. 
 
####Licence 
Le module est distribué sous licence GNU/GPL 
 
####Installation 
Après avoir décompacté l'archive du module, il suffit de recopier le contenu de l'archive dans le répertoire modules de votre site via un logiciel FTP. 
 
Ensuite, rendez vous dans le gestionnaire de modules de Xoops afin d’installer le module. 

Après son installation, le module est tout de suite opérationnel ! 

Vous pouvez commencer par le paramétrer. 
  
#Préférences du module 
Vous pouvez changer les préférences du module soit depuis sa page d'accueil dans l'administration en cliquant en haut à gauche sur le lien intitulé "Préférences" soit en sélectionnant le lien adéquate lorsque vous survolez l'icône du module. 

Certaines options n'ont pas forcément besoin  d'être paramétrées alors que d'autres revêtent une certaine importance. 
 
####Nombre d'éléments par catégorie, sur la page d'index du module 
Avec cette option, vous indiquez au module le nombre maximum de références à afficher par catégorie sur la page d’index du module.  
 
####Nombre d'éléments dans l'administration du module 
Cette option vous permet de choisir le nombre maximum d’éléments visibles dans les listes de l’administration du module. 
 
####Editeur à utiliser  
Sélectionnez dans cette liste l’éditeur de texte à utiliser pour créer vos références (ces éditeurs ne sont pas fournis avec le module et doivent être installés par vous-même). 
 
####Largeur des vignettes 
Comme il a été indiqué dans la partie listant les fonctionnalités du module, celui-ci est en mesure de créer les vignettes de chacune des 10 images qu’il est possible de joindre à chaque référence. Avec cette option, vous indiquez la largeur maximale des vignettes. 
 
####Hauteur des vignettes 
Cette option vous permet de spécifier la hauteur maximale des vignettes générées par le module. 
 
####Chemin du dossier où stocker les images et vignettes (SANS slash final) 
Indiquez à quel endroit vous souhaitez que le module enregistre les vignettes des copies d’écran. C’est un chemin complet qui vous est demandé. Par défaut le module utilise le répertoire « uploads » de votre site car celui-ci est ouvert en écriture. 
 
####URL du dossier où sauvegarder les images et vignettes (SANS slash final) 
Spécifiez l’url où seront stockées les vignettes (voir option précédente) 
 
####Chemin du dossier où stocker les fichiers joints aux articles (SANS slash final)  
A chaque référence il est possible de joindre un fichier attaché, avec cette option vous indiquez le chemin où stocker ces fichiers. 
 
####URL du dossier où sauvegarder les fichiers joints aux articles (SANS slash final) 
Spécifiez l’url où seront stockés les fichiers joints aux références (voir option précédente). 
 
####Utiliser les flux RSS ? 
Avec cette option vous avez la possibilité d’activer ou de désactiver la génération du flux RSS du module. 
 
####Temps de cache du flux RSS (en secondes) 
Si vous avez activé la génération du flux RSS du module (voir option précédente), alors cette option vous permet de gérer le temps de cache de ce flux. Par défaut 1 heure. 
 
####Types mime autorisés pour les téléchargements 
Cette option est utilisée pour indiquer les types de fichiers qui peuvent être joints à chaque référence. 
 
####Taille maximale des fichiers joints et des images 
Cette option permet de limiter la taille des fichiers joints aux références ainsi que la taille (en octets) des captures d’écran. Attention, cette option n’écrase pas le paramétrage qui a été fait dans le php.ini de votre site sur la taille maximale des téléchargements. 
 
####Utiliser le système de tags ? 
Cette option vous permet de saisir, pour vos références, des mots clés qui sont ensuite présentés dans la liste des références ou dans 2 blocs du module. Cette option nécessite que le module Xoops TAG soit installé sur votre site (module non livré). 
 
 
####Zone de tri à utiliser sur la page d’index pour trier les références ? 
Cette option vous permet de choisir la zone de tri à utiliser pour afficher les références sur la page d’index (soit la date de création de la référence soit le poids de la référence) 
 
####Ordre de tri 
Cette option est un complément de l’option précédente et vous permet de choisir le sens du tri (par ordre ascendant ou descendant) 
  
####Config.php 
A la racine du module, il existe un fichier qui s’appelle config.php. Ce fichier contient quelques options supplémentaires du module.  

Ces options nécessitent une bonne connaissance de Xoops et des serveurs. C’est pour cela qu’elles ont été placées dans ce fichier et non pas dans les options générales du module. 

Si vous les modifiées, conservez une copie du fichier original car une erreur pourrait entraîner un arrêt du fonctionnement du module. 

Modifiez ce fichier uniquement en connaissance de cause ou contactez-nous. 
Ce fichier contient des « DEFINE » dont il est possible de changer les valeurs pour modifier le comportement du module. Voila la signification de ces « DEFINE » 

 
 
  
#Administration 
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
  
#Blocs 
####Dernières références 
Ce bloc vous permet d’afficher la liste des dernières références rentrées. 

Dans ses paramètres, lorsque vous l’éditez, vous pouvez spécifier le nombre maximum d’articles  à afficher. 
 
####Référence au hasard 
Avec ce bloc, vous affichez un certain nombre de références au hasard. 

Les paramètres du bloc vous permettent de choisir le nombre de références à afficher. 
 
####Nuage de mots clés du module 
Ce bloc affiche, comme son nom l’indique, un nuage des mots clés définis dans les références (ce bloc nécessite le module Xoops TAG). 
 
####Top des mots clés du module 
Ce bloc affiche les mots clés les plus utilisés dans le module (ce bloc nécessite le module Xoops TAG) 
  
#Côté utilisateur 
 
####Page d’index 
La page d’index (index.php) du module affiche la liste des références (en ligne) par catégorie. La page contient aussi, si l’option est activée, un lien vers le flux RSS. 

Note : le titre de la page est tiré du titre de la référence la plus récente. De même, les métas mots clés sont générés à partir de la description de cette dernière référence. 
 
####Page des catégories 
Cette page reprend le même contenu que la page d’index mais limité à une certaine catégorie (en tenant compte des permissions) 
 
####Page d’une référence 
Cette page permet de voir le contenu complet d’une référence (en tenant compte des permissions) 
 
####Flux RSS 
Cette page (rss.php), affiche, si l’option correspondante est activée, un flux RSS qui liste les dernières références du module. 
 
  
#Contenu du répertoire Extra 
Le répertoire Extra contient à sa racine un script Php intitulé clone.php. Celui-ci vous permet de cloner le module.  

Ce script nécessite de connaître Php. 

Si vous souhaitez cloner le module, placez ce script à la racine de votre site et lancez-le. 

Au préalable, prenez soin de l’avoir édité afin d’indiquer le nouveau nom que vous souhaitez donner au module. 
 
####Autres scripts présents dans le répertoire Extra 
Dans le sous répertoire /modules/rss/plugins/, se trouve un script intitulé « rssfit.references.php », ce script vous sera utile si vous utilisez le module RSSFit 

Dans le sous répertoire /modules/sitemap/plugins/, se trouve un script intitulé « references.php », ce script quant à lui vous servira pour le module Sitemap (pour générer un plan de vos catégories) 
 
#Personnalisation de l’aspect des accordéons 
Si vous disposez de quelques connaissances en CSS, vous pouvez personnaliser l’aspect des accordéons en éditant le fichier suivant : /xoops/modules/references/js/css/accordion.css 
