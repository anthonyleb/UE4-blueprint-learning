# Apprentissage Unreal engine 

J'ai décidé d'apprendre unreal engine par les blueprints pour me familiariser avec api unreal engine. Je vais mettre des aperçus de comment faire des mouvements du personnage, mouvement de la caméra...

## sommaire

- basics
    -  [mouvement camera](#mouvement_camera)
    -  [mouvement character](#mouvement_character)


## pour débuter

- créer une classe (game mode base)
- créer une classe (character)

# mouvements

## initialiser les touches 

-  edit -> project settings > input

![initialiser les touches](mouvementPersonnageCamera/settings.png)


## cliquer sur notre classe game mode base 


- On arrive sur ce panel on a juste à remplacer notre classe par défaut par notre classe personnage donc ici Player_Character.

![paramètre pour le mode](mouvementPersonnageCamera/settings_mode.png)

## cliquer sur notre classe character <a id="mouvement_character"></a>

- Add component -> Camera 
- puis placer la caméra assez haute

![paramètre pour le mode](mouvementPersonnageCamera/placer_la_camera.png)

## Mouvement de la caméra <a id="mouvement_camera"></a>

![paramètre pour le mode](mouvementPersonnageCamera/mouvement_camera.png)

- compiler -> fermer la fenêtre -> play (jouer)


## Mouvement du character 

![paramètre pour le mode](mouvementPersonnageCamera/mouvement_character.png)

- compiler -> fermer la fenêtre -> play (jouer)