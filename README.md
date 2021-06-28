# Bonjour bonjour !

J'ai commencé la programmation en réalisant quelques prototypes de jeux-vidéo avec la suite de logiciels RPG Maker.
C'est tout naturellement que j'ai rejoint le projet **[RPG Maker Extender](https://rmex.github.io/)** dès ses premières versions et y ai contribué en plus de l'utiliser, notamment pour en faire remonter le moindre bug et suggérer de nombreuses features complémentaires

- Voici quelques exemples de ce que j'ai pu implémenter avec *Ruby, RGSS (le moteur d'RPG Maker, dont les scripts se rédigent en Ruby) et RME* :


### Un Pacman (avec des fantômes intelligents, grâce au pathfinder [Invenio](https://www.youtube.com/watch?v=UDLRea_pmz8))
![Pacman](https://user-images.githubusercontent.com/72009188/122585851-3d5ce980-d05c-11eb-8c26-8c0b372c4999.gif)

### Un système de course-poursuite permettant de créer des ennemis avec plusieurs états/comportements et un champ de vision.
![Pursuit](https://user-images.githubusercontent.com/72009188/122585807-3209be00-d05c-11eb-9818-dc4e2c29d28b.gif)

### Un exemple de Puzzlegame
![PuzzleGame](https://user-images.githubusercontent.com/72009188/122585821-3635db80-d05c-11eb-8512-37091416e1d0.gif)

### Le système de "Voleur" de Link's Awakening
![Thief](https://user-images.githubusercontent.com/72009188/122585834-3930cc00-d05c-11eb-8f40-7a582b42af1d.gif)

### Un système permettant de pousser des objets de façon plus réaliste dans RPG Maker (le joueur reste proche de l'objet qu'il pousse, les z-index sont réajustés)
![Blocks](https://user-images.githubusercontent.com/72009188/122585843-3b932600-d05c-11eb-9f38-f2c5dc7fa36d.gif)

### Des terrains ralentissant ainsi qu'une typologie pour savoir quel personnage est impacté ou non
![Glue](https://user-images.githubusercontent.com/72009188/122585865-40f07080-d05c-11eb-8bdf-6658a93a1436.gif)

### Juste un peu de ripping et d'intégration de ressources graphiques
![LA](https://user-images.githubusercontent.com/72009188/122585875-43eb6100-d05c-11eb-8d21-6b762c7ae987.gif)

## J'étudie actuellement à @Epitech Paris afin de me perfectionner et souhaite faire de mon hobby ma profession 🙂

J'aimerais tout particulièrement reprendre la programmation en **Ruby**, qui est un langage avec lequel je me suis beaucoup amusé.
Je programme également en **C, Go, JS, Python et Javascript**.

## Quelques exempls de projets réalisés à Epitech

### Un prototype de jeu de plateforme (en C et en CSFML, projet réalisé en 1 semaine)
#### - Cliquer sur la miniature pour lancer la vidéo
[![MyRunner - Epitech 2020](https://i9.ytimg.com/vi_webp/haITCqo14J4/mqdefault.webp?sqp=CJzK54YG&rs=AOn4CLB61eoISdiGM8OBNquO3wkU9eTS2A)](https://www.youtube.com/watch?v=haITCqo14J4)
- Gestion de Tileset ingame (il y a juste un tile sur lequel il manque un pixel, je n'ai pas filmé la version la plus à jour dans laquelle ça avait été corrigé... sorry!)
- Fichier de config pour la map (le jeu ne laggue pas, même si la map est immense : elle est mise en cache à l'initialisation du jeu et seules les collisions des éléments à l'écran sont calculées)
- Multi-parallaxes (le mur en image de fond, et les deux tiles du bas de la map, le sol, sur lequel le joueur marche sont des parallaxes et ne sont pas inhérents au fichier map. Pour ce qui est du sol, je souhaitais implémenter un parallax qui défile parfaitement avec l'écran.)
- Fog (parallax en avant-plan)
