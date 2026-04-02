# Souris
    Le code fourni :
     -construit  des souris ;
     -les fait évoluer au moyen d’une méthode evolue ;
     -affiche les souris avant et après les avoir fait évoluer.
   Le corps de la classe Souris manque et c’est ce qu’il nous est demandé d’écrire.

## Spécifications de la classe Souris
  Une souris est caractérisée par :
     -son poids en grammes (double nommé poids)
     -sa couleur (string nommée couleur)
     -son âge (unsigned int nommé age)
     -son espérance de vie (unsigned int nommé esperance_vie)
     -un indicateur indiquant si elle est clonée (bool nommé clonee)
     
## Méthodes publiques
    1.Constructeurs conformes au main fourni, avec l’ordre des paramètres suivant :poids, couleur, âge, espérance de vie.
        Les deux derniers paramètres ont pour valeurs par défaut : 0 et 36.Ces constructeurs affichent : "Une nouvelle souris !"

    2.Un constructeur de copie qui affiche : "Clonage d’une souris !"
        La souris clonée possède les mêmes caractéristiques sauf son espérance de vie qui est réduite aux 4/5 de celle d’origine

    3.Un destructeur qui affiche: "Fin d’une souris..."
   
    4.Méthode afficher() qui affiche les caractéristiques sous le format :
        "Une souris <couleur> [, clonee,] de <age> mois et pesant <poids> grammes"(la partie , clonee, n’apparaît que si la souris est clonée)

    5.Méthode vieillir: qui augmente l’âge de 1 si la souris est clonée et dépasse la moitié de son espérance de vie, elle devient verte.
        Cette méthode doit être publique.

    6.Méthode evolue: qui fait vieillir la souris jusqu’à atteindre son espérance de vie

Tous les affichages se terminent par un saut de ligne
