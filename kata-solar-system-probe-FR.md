# Solar system probe

### Instructions
Une sonde à été envoyée par la NASA pour l'exploration du système solaire.

Le but est de développer un programme pour déplacer la sonde à travers le système solaire et en survoler chaque planète.

Dans ce programme, le parcours de la sonde est représenté par une ligne qui croise les orbites des planètes, et la sonde a un state qui contient la distance en unité astronomique (AU) la séparant du soleil.


### Entrée
Le programme prend en entrée un nombre décimal signé :

- le nombre est positif pour déplacer la sonde vers l'extérieur du système solaire, et négatif pour la rapprocher du centre

- la valeur absolue représente la distance à parcourir


### Sortie

La sortie du programme est un message sous forme de chaîne affichant :

- *Hello from [planet's name]* si la sonde est à la même distance du soleil qu'une des planètes

- *I am lost in the universe ...* si la sonde n'est nulle part


### Interface
La classe Sonde doit contenir la distance orbitale de chaque planète en unité astronomique (AU).

- Mercury => 0.387
- Venus => 0.782
- Earth => 1
- Mars => 1.52
- Jupiter => 5.20
- Saturn => 9.58
- Uranus => 19.20
- Pluto => 30.05

On part du principe que la sonde décolle de la Terre, avec comme position initiale 1.

### Exemples à tester :

- l'entrée +0.52 donne en sortie *Hello from Mars*

- l'entrée -0.218 donne en sortie *Hello from Venus*

- l'entrée +2 donne en sortie *I am lost in the universe ...*