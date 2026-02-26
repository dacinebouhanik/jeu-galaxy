#  Galaxy 2D Arcade Game

Galaxy 2D Arcade Game est un jeu d’arcade en 2D avec effet pseudo-3D développé en Python avec le framework Kivy.

Le joueur contrôle un vaisseau spatial et doit éviter les obstacles générés dynamiquement. La difficulté augmente progressivement avec la vitesse du jeu.

---

##  Fonctionnalités

- Déplacement du vaisseau au clavier
- Génération aléatoire du parcours
- Détection de collisions
- Système de score évolutif
- Menu de démarrage et écran Game Over
- Effets sonores et musique d’ambiance
- Interface graphique fluide avec rendu en perspective

---

## Technologies utilisées

- Python 3
- Kivy
- Gestion du rendu graphique avec transformations personnalisées
- Gestion des événements clavier et souris

---

##  Structure du projet
```
audio/ # Effets sonores et musiques
fonts/ # Polices personnalisées
images/ # Images du jeu
main.py # Fichier principal
menu.kv # Interface du menu
galaxy.kv # Interface du jeu
transforms.py # Gestion des transformations graphiques
user_actions.py # Gestion des entrées utilisateur
```