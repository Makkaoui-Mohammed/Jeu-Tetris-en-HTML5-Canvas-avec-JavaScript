# Jeu-Tetris-en-HTML5-Canvas-avec-JavaScript
Ce code met en place un jeu Tetris en utilisant le langage HTML5 Canvas avec du JavaScript pour la logique du jeu.


Structure HTML (index.html):

La page HTML débute par la déclaration du type de document (<!DOCTYPE html>).
La langue de la page est spécifiée comme anglais (<html lang="en">).
La section <head> contient les métadonnées telles que la définition du jeu de caractères, la vueport, le titre de la page, et une référence à une feuille de style externe.
La balise <body> contient un élément <canvas> avec l'identifiant "tetris" et des dimensions de 240 pixels de large sur 400 pixels de haut.
Le fichier JavaScript "tetris.js" est inclus à la fin du <body>.


Feuille de style CSS (style.css):

La mise en page globale du document est définie avec le modèle de boîte flexible (display: flex).
Les éléments sont centrés horizontalement et verticalement (align-items: center, justify-content: center).
La hauteur de la page est définie à 100% de la hauteur visible (height: 100vh).
Le style de la balise <canvas> inclut une bordure de 1 pixel.


Script JavaScript (tetris.js):

L'instruction "use strict"; indique que le code doit être interprété en mode strict.
Le code crée un objet Canvas et son contexte 2D, et définit une échelle pour les dessins.
Des fonctions sont définies pour créer une matrice, dessiner une matrice, fusionner une matrice avec une pièce, générer une nouvelle pièce, détecter les collisions, faire tourner une pièce, déplacer le joueur, mettre à jour le jeu, etc.
Un tableau pieces contient différentes formes de pièces Tetris.
Un objet player est créé avec une matrice de pièce et une position initiale.
Une fonction gameLoop appelle les fonctions de mise à jour et de dessin à intervalles réguliers, créant ainsi une boucle de jeu.
Les touches du clavier sont écoutées pour déplacer et faire pivoter la pièce.
La boucle de jeu est initiée à la fin du script.

![tetris](https://github.com/Makkaoui-Mohammed/Jeu-Tetris-en-HTML5-Canvas-avec-JavaScript/assets/108239380/64c416c5-5dc7-4df9-9a1b-ad8d5e59d5a1)

