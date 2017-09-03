# session-1
Initiation à Github et architecture du web

## Plan du cours

- Session 1 : L'architecture du web
- Session 2 : Fondamentaux du HTML (*Modifier une page web*)
- Session 3 : Chemins absolus et relatifs (*Créer une galerie d'images*)
- Session 4 : Styles et mise en forme (*Créer la charte graphique d'un site*)
- Session 5 : Marges et positionnement (*Positionner les éléments d'une page*)
- Session 6 : Frameworks CSS (*Concevoir un design responsif*)
- Session 7 : Javascript et données (*Externaliser les textes, modifier un JSON*)
- Session 8 : Javascript et calculs (*Intégrer la logique d'une application*)
- Session 9 : Sélecteurs javascript et SVG (*Dessiner avec des données*)
- Sessions 10 et 11 : Frameworks réactifs (*Adapter une application web*)
- Session 12 : Révisions :)

## Exposés

2 exposés par séance
**3 minutes maxi par sujet** : Soyez concis et allez à l'essentiel

[Liste des sujets et attribution par séance](https://docs.google.com/spreadsheets/d/1GXkiEZ1TJeetHr60InzMmQV-m5D3NbL6TUdf5gvO-J0/edit?usp=sharing)

## L'architecture du web

Le **serveur** contient du code HTML, CSS ou Javascript, des images, des vidéos, des documents, ou un logiciel capable de générer ce type de fichiers.

Le **client** interroge le serveur via un navigateur web, et télécharge ces fichiers.

![OpenClassrooms](https://user.oc-static.com/files/122001_123000/122572.png)

Le client utilise un **navigateur internet** pour traduire les instructions du code dans un contenu visible à l’écran.

![OpenClassrooms](https://s3-eu-west-1.amazonaws.com/sdz-upload/prod/upload/54d0e588bb668.jpg)

> Sur le web, le code-source d'une page est toujours consultable, et son rendu est même modifiable.

> Pour consulter le code source de [la page d'accueil de Wikipedia](https://www.wikipedia.org/), faites clic-droit, puis *Afficher la source*.

>Pour modifier le rendu de [la page d'accueil du Monde](https://www.lemonde.fr/), faites clic-droit sur un élément, puis *Inspecter l'élement*.


-----


Le **HTML** est le langage qui permet de structurer une page web, en mettant chaque élément dans un bloc.

Le **CSS** est le langage qui permet de définir une mise en forme pour chaque bloc.

Le **Javascript** permet d'interagir avec ces blocs, et de modifier leur contenu ou leur style *dynamiquement*.

Démonstration : [Style switcher](http://etalx.com/jquery-style-switcher/tests/)

## Écrire du code

Avant d'envoyer son propre site sur un serveur, il faut en écrire les fichiers sur son poste **local**.

Pour cela, on peut utiliser un simple éditeur de texte comme le bloc-note, ou opter pour un éditeur avancé comme [**Sublime Text**](https://www.sublimetext.com/).

- Règle 1 : ne pas utiliser d'accents ou d'espaces dans les noms de fichiers
- Règle 2 : nommer la page d'accueil index.html
- Règle 3 : utiliser un seul dossier racine par projet

Pour qu'une page HTML soit valide, il faut qu'elle contienne à minima le code suivant, qui est son squelette : 

````html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Définition de l'encodage des charactères en UTF-8 -->
    <meta charset="utf-8">
    
    <title>Texte de l'onglet de navigateur</title>
  </head>
  <body>
    <!-- Le contenu d'une page s'écrit entre les balises body -->
    <h1>Mon premier titre</h1>
    
    <p>Mon premier paragraphe de texte</p>
  </body>
</html>
````

## Partager du code

Les éditeurs de documents comme Word, Google Docs, ou votre client mail ne "comprennent" pas le code. Pour partager son travail, il faut envoyer tout le dossier contenant son projet, ou utiliser une plateforme collaborative spécialisée, comme **Github**.

Github permet de : 
- stocker ses projets (**repositories**) dans son espace personnel
- travailler à plusieurs sur le même projet (**commits**, **branche** et **pull requests**)
- garder une trace de tous les changements effectués sur chaque fichier
- cloner un projet pour le faire évoluer soi-même (**fork**)
- publier ses projets simples gratuitement

Par exemple, toutes mes modifications sur cette page sont consultables ici : https://github.com/edj-initiation-code/session-1/commits/master/README.md

Pour vous joindre à Github, commencez par : 
- [Créer un compte](https://github.com/join)
- Partagez votre username pour faire partie de l'organisation "Initiation au code"
- Téléchargez ou ouvrez le logiciel [Github Desktop](https://desktop.github.com/) et identifiez-vous
- Clonez ce projet en cherchant Session 1 dans la boite de dialogue "Ajouter un projet"
