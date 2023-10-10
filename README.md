Algorithme PointDeControle
    Entrée: phrase (une chaîne de caractères se terminant par un point)
    Sortie: longueur (longueur de la phrase), nbMots (nombre de mots), nbVoyelles (nombre de voyelles)

    // Initialisation des compteurs
    longueur <- 0
    nbMots <- 1  // Le premier mot est compté
    nbVoyelles <- 0

    // Parcourir chaque caractère de la phrase
    Pour chaque caractère dans phrase
        // Incrémenter le compteur de longueur
        longueur <- longueur + 1

        // Vérifier si le caractère est une voyelle (a, e, i, o, u)
        Si caractère est une voyelle Alors
            nbVoyelles <- nbVoyelles + 1

        // Vérifier si le caractère est un espace (délimitation des mots)
        Si caractère est un espace Alors
            nbMots <- nbMots + 1  // Incrémenter le compteur de mots

    // Retourner les résultats
    Retourner longueur, nbMots, nbVoyelles
Fin de l'algorithme
