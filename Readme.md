
# le numéro fixe est parametrable par l'URL

La position (dans la grille) du numéro est paramètré par :
- fixed_code_line : la ligne de positionnement (la première ligne est la 0)
- fixed_code_col : la colonne de positionnement (la première colonne est la 0)

le chiffre du numéro est paramètré par :
- fixed_code_number : le numéro a mettre dans la case

# la taille de la grille

La taille de la grille est paramètré par :
- grid_line : le nombre de ligne dans la grille
- grid_col : le nombre de colonnes dans la grille

# Les timers de changement de nombre

Les timers pour le changement des nombres est aléatoire. Pour regler le max et min :
- timer_min : le temps minimum entre deux changement (en ms)
- timer_max : le temps maximum entre deux changement (en ms)


# Exemple de parametrage complet

?grid_line=3&grid_col=3&fixed_code_line=0&fixed_code_col=0&fixed_code_number=3&timer_min=10&timer_max=500
