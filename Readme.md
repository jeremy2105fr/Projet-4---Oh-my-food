Lien vers github : https://github.com/jeremy2105fr/Projet-4---Oh-my-food

- Le dossier asset contient:

  - le dossier css et son fichier css avec style.css (met en style la pages index + restaurants).
    !!! Ne pas modifier directement le fichier css !!!

  - Le dossier Images qui comporte les images et les logos utilisés dans l'ensemble du projet.

- Le dossier restaurants contient :

  - Les pages htmls des restaurants.

- Le dossier sass contient:

  - le fichier main.scss qui permet de modifier par script (package.json) le fichier css style-restaurants.css.

  - le dossier base contient:
    - animation.scss pour les @keyframes du projet.
    - base.scss pours des modifications globales.
    - typography.scss pour changer la police.
  - le dossier components contient:
    - loader.scss" qui contient le loader de l'index.
  - le dossier layouts contient:
    - header-index.scss qui gère la partie header de l'index.
    - header-restaurant.scss qui gère la partie header des restaurants.
    - main-index.scss qui gère la partie main de l'index.
    - main-restaurants qui gère la partie main des restaurants.
    - footer.scss qui gère le footer en commun de l'index et des restaurants.
  - le dossier utils contient:
    - mixins-animations.scss regroupe les @mixins qui gèrent les appels d'animations.
    - mixins.scss qui regroupe les @mixins plus classiques.
    - variables.scss qui regroupe l'ensemble des $variables comme les couleurs ou certaines dimensions.

- La page html de l'index : index.html

- Le script package.json doit être excuter (que si node.js et sass sont installé ) via la cmd:
  " npm run sass "
  via le terminal Git Bash (DANS le dossier: PROJET4 - OH-MY-FOOD)
