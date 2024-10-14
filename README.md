# Introduction

 L'algorithme transfère le style d'une image d'entrée (l'image de style) sur une autre image d'entrée (l'image de contenu) en utilisant des réseaux de neurones convolutifs (généralement VGG-16/19) et génère une image composite stylisée qui conserve le contenu de l'image de contenu tout en adoptant le style de l'image de style.
C'est le dépôt de NST (Neural Style Transfer) le plus propre et concis que je connaisse, et en plus, il est écrit en PyTorch ! 
La plupart des dépôts de NST étaient écrits en TensorFlow (avant même qu'il ne dispose de l'optimiseur L-BFGS) ou en torch (un framework obsolète qui utilisait Lua) et sont souvent trop compliqués, incluant plusieurs fonctionnalités (vidéo, image statique, transfert de couleurs, etc.) dans un seul dépôt, et exposant une centaine de paramètres en ligne de commande (dont seulement 5 ou 6 sont réellement utilisés régulièrement).

## Exemples : 

Le transfert de style donne des résultats artistiques magnifiques .
![image](https://github.com/user-attachments/assets/fc21b602-a161-4e9a-9a95-30f18d9ecb2c)

Et voici un exepmple de style "vg_starry_night" : 

![image](https://github.com/user-attachments/assets/d5d96c7b-1f32-4c41-b818-9e21029f4497)


## FIN , Mercii ❤️❤️
