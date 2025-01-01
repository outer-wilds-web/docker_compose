# Outer Wilds Web 
## initialisation 
Pour les vaisseaux
```shell
git clone git@github.com:outer-wilds-web/autopilot.git
```

Partie Server/bdd/kafka
```
git clone git@github.com:outer-wilds-web/outer-wilds-front.git
git clone git@github.com:outer-wilds-web/backend.git
git clone git@github.com:outer-wilds-web/docker_compose.git
cd docker_compose
```

## Lancement de l'application de base

Pour run notre projet, il faut effectuer cette commande :

```shell
docker compose up --build
```

Dès que tout les services sont initialisés et l'application lancée, vous pouvez vous rendre sur l'adresse suivante :
localhost:5173

Arrivé sur l'adresse, vous voyez le système solaire en train de tourner et un vaisseau assez proche de vous. Vous pouvez le contrôler en appuyant sur Z, Q, S et D.
Lorsque vous ouvrez un nouvel onglet sur la même adresse, un nouveau vaisseau apparaitra, controllable uniquement depuis cet onglet.


## Apparition de vaisseaux contrôlés automatiquement

Vous pouvez run un "autopilot" en exécutant cette commande :

```shell
cd autopilot
docker compose up --build
```

Pensez à mettre un user et un nom différent à chaque fois.
Cet autopilot permettra de créer un vaisseau contrôlé automatiquement de façon aléatoire. Vous pouvez en ouvrir autant que vous le souhaitez. Ainsi, vous verrez sur l'onglet de votre navigateur à l'adresse par défaut de l'application, des vaisseaux se baladant de façon aléatoire dans le système solaire.

---


## Nos attentes sur le projet 

Comme son nom l'indique, nous souhaitions partir sur le système solaire du jeu Outer Wilds. Nous avons fait beaucoup de tests afin de pouvoir récupérer les planètes et objets composant le système solaire du jeu. Nous avons eu des résultats très concluant vers la fin. Cependant, par manque d'optimisation des textures des planètes qui rendait les modèles 3D trop lourds, nous n'avons pas pu les inclure dans le projet par un manque de temps avec la période des fêtes de fin d'années.
Dans le futur, nous souhaitons pouvoir les inclure et remplacer le système solaire actuellement affiché, par celui du jeu.
 
