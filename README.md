# package-Javascript
----npm----

node package manager est bun gestionnaire de paquet officiel de node js. il est un des gestionnaire qui s'installe automatiquement lors de l'installation de node Js. il faut noter qu'il permet d'installer les differents modules afin qu'on puisse les utiliser dans le projet.

example d'utilisation de npm pour créer un projet node. la prémière commande est:
    npm init --save
 si je veux installer un module par tel que nodemon pour la mise à jour automatique de mon projet afin de voir des modification 
 automatique, on va taper la commande suite:
 
    npm install --save nodemon

---browser-----

c'est un gestionnaire de paquet pour le web. il permet d'installer les bonnes versions des packages et de leur dependences. il peur gerer les composants contenant du HTML, CSS et Javascript, les polices et mèmes les images. il ne le concarne pas et ni les minimises pas et ne fait rien d'autre.

pour l'utiliser dans un projet , il faut taper la commande suivante pour l'installaer de façon globale:
  npm install -g browser 
  Maintenant si tu veux l'utiliser dans le projet pour installer les packages tels que Jquery:
    
    browser install <nom package>
    
    browser install Jquery
  
  
 --RequireJS--
 
 c'est chargeur de fichiers ou de modules pour JavaScript. il  est installé automatiquement lors de la création de projet Node JS.il permet d'utiliser des modules qui existent dans le projet ou diont nous avons installé.
 Loque nous voulons utiliser un système de fichiers pour travailler dans le projet , nous allons l'appeler grace à require par le code suivant:
  
  const fs = require('fs');
  
  losque nous avons installé le module express et nous voulons l'utuliser par la suite, la commande suivante:
  
  let express = require('express');
  
  
  ---Browserify----
  
  Broswerify est un bandle qui permet d'exiger les modules dans nos navigateurs en regroupant toutes les dependances.
  ce qu'il faut noter est que la methode require n'est pas défini dans les navigateurs.
  
  ---JSLint------
  
  il faut noter que c'est un outil de qui est le plus souvent intégrer aux navigateurs et que qui nous permet de savoir si notre
  code javascript est correcte ou respecte les normes. par exemple losque vous utiliser uin editeur comme atom ou visual Code, il faut aller dans packages et chercher la barre de recherche puis l'installer.
  
  ----Gatsby.js----
  
  c'est un générateur de squelette de site web statique generalement basé sur React.il faut noter qu'il est très rapide dont les developpeurs se servent le plus souvent pour finir leur travaux dans un bref delai.
  Ce qu'il faut noter qu'on peut l'utliser losqu'on a installé node js.
  
  pour installer Gatbst js:
  
       npm install gatsby-cli
    
  pour créer son site web à partir d'une seule commande :
  
       gatsby new [<site-name> [<starter-url>]]
       
   
  
  
  
  
  
