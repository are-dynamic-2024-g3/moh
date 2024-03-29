**Compte rendu semaine 4 : **
---

Imports :

    python

    import random
    import time

Nous importons les modules random et time pour générer des nombres aléatoires et gérer les délais dans la simulation, respectivement.

Définition des classes :
        Vehicle (Véhicule) : Cette classe représente un véhicule dans la simulation. Chaque véhicule a un identifiant, une position, une vitesse et une liste de colis qu'il transporte.
        Package (Colis) : Cette classe représente un colis à livrer. Chaque colis a un identifiant, une position de départ (source) et une destination.

Fonctions :
        generate_packages(num_packages, max_position) : Cette fonction génère un nombre donné de colis avec des positions de départ et de destination aléatoires, garantissant que la destination n'est pas la même que la source.
        main(num_vehicles, num_packages, max_position, simulation_time) : Cette fonction est la fonction principale de la simulation. Elle initialise les véhicules et les colis, puis exécute la simulation pendant une certaine durée. À chaque itération, elle déplace les véhicules, livre les colis et charge de nouveaux colis sur les véhicules.

Initialisation de la simulation :
        Nous définissons le nombre de véhicules, de colis, la position maximale sur la route et la durée de la simulation.
        Nous initialisons une liste de véhicules avec des positions et des vitesses aléatoires, ainsi qu'une liste de colis générés aléatoirement.

Boucle de simulation :
        Nous commençons par imprimer un message indiquant le démarrage de la simulation et affichant les paramètres de la simulation.
        Nous enregistrons le temps de début de la simulation.
        Nous exécutons une boucle while jusqu'à ce que le temps écoulé dépasse la durée de la simulation.
        À chaque itération de la boucle :
            Nous affichons le temps écoulé.
            Nous affichons les positions des véhicules.
            Nous affichons les colis chargés sur les véhicules.
            Nous déplaçons les véhicules et livrons les colis.
            Nous chargeons de nouveaux colis sur les véhicules si la position de départ d'un colis correspond à la position actuelle d'un véhicule.
            Nous mettons à jour le temps écoulé et faisons une pause d'une seconde avant la prochaine itération.

Fin de la simulation :
        Une fois la simulation terminée, nous affichons un message de fin.

