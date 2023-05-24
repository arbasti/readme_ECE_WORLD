# Projet ECE_World

## Thème :
Pour ce projet, nous avons décidé d'utiliser l'univers de Mario comme thème de notre parc d'attraction. Celle-ci étant variés, ce thème nous permet de pouvoir imaginé de nombreuse façon d'aprehender nos activités comme la course hippique avec des yoshis ou encore du jeu "goombaattack" par exemple

## La Cartes :

Nous avons pris l'initiative de payer un créateur afin d'avoir déjà un tileset potable, et ainsi nous insipirer pour nos tileset suivant

Le créateur du TileSet : https://brysiaa.itch.io/pixel-tileset-grass-island

**Voici notre tileset final :**

<img width="200" alt="my_tileset_2" src="https://github.com/ING1-Paris/ece-world-paris-ing1-2022-2023-equipe-10-td13/assets/90555409/92c40d04-d6fb-4dcf-bc15-5c2b9994df46">


**Voici la map principale :**

<img width="640" alt="my_tileset_2" src="https://github.com/ING1-Paris/ece-world-paris-ing1-2022-2023-equipe-10-td13/assets/90555409/53958167-c611-486e-acb2-34da25b08d55">

## Avancée du Projet :

### 18/04 :
- Idée graphisme
- Achat d'une texture pour la map

### 22/04 :
- Création du Github
- Création README.md
- Ajout des membres
- Création Menu 1/3

### 23/04 :
- Création Menu 2/3
- Création du squelette du projet 1/2

### 24/04 : 
- Brainstorming

### 25/04 :
- Création de la map test Tiled
- Création du squelette du projet 2/2
- Création du Menu 3/3
- Déplacement du joueur 1/2

### 26/04 :
- Erreur : Déplacement de notre GitHub sur celui de l'école
- Déplacement du joueur 2/2
- Mise en place de l'activation d'une attraction lorsque le joueur est sur celle-ci

### 29/04 :
- Création du jeu de la traversé de la rivière 1/2
- Création de la map hub du jeu (1024x1024) et de son calque de collision (Il manque juste le décor)

### 30/04 :
- Création déplacement des bouts de bois pour la traversé de la rivière 2/2

### 02/05 :
- Ajout de la fontionnalité scrolling map pour le hub principal

### 07/05 :
- Mise en place du sprites d'animation de mario dans la traversé de la rivière
- Conception du Tir au koopa 1/x

### 12/05 :
- Développement du jeu Goombattack 1/5
-  Dévelopement du jeu course hyppique 1/4
- Préparation de certain graphisme pour Goombattack

### 13/05 :
- Développement du jeu Goombattack 2/5

### 15/05 : 
- Ajout de la musique et des fonds pour les jeux de la traversé de la rivière et le tir au koopa
- Modification des sprites d'animation pour les koopas 
-  Dévelopement du jeu Course hyppique 2/4

### 17/05 :
- Développement des tuyaux 1/x (Idée Abandonnée)
-  Dévelopement du jeu Course Hyppique 3/4

### 19/05 :
- Développement du jeu Goombattack 3/5
- Video rapide utilisation Tiled
- Modification de la map Goombattack
- Développement du jeu Goombattack 4/5
- Dévelopement du jeu Course Hyppique 4/4

### 20/05 :
- Développement du jeu Goombattack 5/5
- Assemblage des codes 1/2

### 21/05 :
- Assemblage des codes 2/2
- Création des images des menus pour chaque jeux (Gabriel)

## Tiled :

Nous avons utlisé Tiled pour créer la majorité de nos maps de jeu. Nos tuiles font du 16x16.
Et nous utilisons des calques de collision (avec des couleurs rgb simple) caché dans le programme pour gérer les collisions de chaque jeu ainsi que du hub.

Voici un exemple de son utilisation

https://github.com/arbasti/readme_ECE_WORLD/assets/90555409/1bc1b2a7-c539-4941-ae94-570085ae200b

## Goombattack :

### Infos :

#### But du jeu :

- L'objectif du jeu est d'écraser les goombas avec votre personnage, vous êtes dans un duel direct avec le deuxième joueur.

- Vous devez écraser le plus de goomba dans le temps imparti de 60 secondes.

#### Menu Princiapal (Gabriel) :

<img width="640" alt="menu_goombattack" src="https://github.com/ING1-Paris/ece-world-paris-ing1-2022-2023-equipe-10-td13/assets/90555409/780dae27-b066-4703-9d5b-c15da9efa2ec">

#### Les Maps :

1) Première carte de test
2) Calque de collision
3) Map Final Définitive

<img width="320" alt="map_goombattack" src="https://github.com/ING1-Paris/ece-world-paris-ing1-2022-2023-equipe-10-td13/assets/90555409/6c8b3fd2-b942-4f69-a6ef-f2966b38d1a0">
<img width="320" alt="map_goombattack_collision" src="https://github.com/ING1-Paris/ece-world-paris-ing1-2022-2023-equipe-10-td13/assets/90555409/ba219a57-482a-4638-bf9d-3af57c9d1d63">
<img width="320" alt="map_goomba_tap" src="https://github.com/ING1-Paris/ece-world-paris-ing1-2022-2023-equipe-10-td13/assets/90555409/2dca3887-d2f0-48a1-8f33-18e22dca4d6d">

#### Les Personnages :

**Mario 32x32 :**

<img width="80" alt="tileset_mario" src="https://github.com/ING1-Paris/ece-world-paris-ing1-2022-2023-equipe-10-td13/assets/90555409/2c69037d-3a2e-4632-8844-68485d8e5b1d">

**Goomba 48x48 :**

<img width="72" alt="tileset_goomba" src="https://github.com/ING1-Paris/ece-world-paris-ing1-2022-2023-equipe-10-td13/assets/90555409/06afee00-360d-42b8-a89d-60facbb70486">

### Développement 1/5 :

https://github.com/arbasti/readme_ECE_WORLD/assets/90555409/d36a9039-3cb4-4f87-9185-43112aae5709

**Update :**
- Fond (+ calque collision)
- Collisions
- Saut (saute collision + double saut)

### Développement 2/5 :

https://github.com/arbasti/readme_ECE_WORLD/assets/90555409/2327f2a4-852d-438c-b357-0a70b7c8f1ba

**Update :**
- Ennemis (3 niveaux)
- Affichage "points" et "timer"
- Réctification (double saut imprévu)

### Développement 3/5 :

https://github.com/arbasti/readme_ECE_WORLD/assets/90555409/a72f1ff2-697b-4b26-a8ef-739b77950375

**Update :**
- Ajout du personnage
- Animation du personnage (statique, mouvement, saut)
- Réglage d'un problème de collision

### Développement 4/5 :

https://github.com/arbasti/readme_ECE_WORLD/assets/90555409/7e44f331-fff6-44a1-92b4-368af0712eb3

**Update :**
- Modification de la map (plus vivante)
- Ajout des *BITMAP* Goombas
- Animation (statique, ecrasement)
- Réglage d'un problème d'écrasement

### Développement 5/5 :

https://github.com/arbasti/readme_ECE_WORLD/assets/90555409/27e01cdd-4af9-4429-bc56-77c6fac9551f

**Update :**
- Ajout final d'un deuxième joueur
- Ajout *BITMAP* Joueur 2
- Condition de victoire

### Développement 6/5 :

[Video](https://www.youtube.com/watch?v=Tg0Cm3iq3xc&ab_channel=Bastiooo)

**Update :**
- Dernière modification lors de l'assemblage
- Ajout de musique *thème mario desert*
