Bonjour,
Voici le deuxième code qui nous a été demandé de faire.
C'est une IA jouant au Gomoku (alignement de 5 pions).
C'est la première fois que j'utilise un minimax, la fonction que j'ai utilisé est donc assez basique mais efficace.
L'algorithme devait répondre en moins de dix secondes ce qui m'a laissé un peu de liberté sur la profondeur de recherche.
Vous trouverez dans le pdf "IA-Affrontement_entre_IA" les règles que nous devions suivre (notamment une sur les coups possibles au 1er et 3e tour).
Dans ce code se trouve un dictionnaire qui n'est pas utilisé. Je souhaitais accorder un poids à chaque situation mais l'équilibrage des poids était beaucoup trop long et fastidieux.
J'ai donc décidé de rester sur une une même fonction de calcul pour toutes les combinaisons possibles (sur une même ligne de 5 pions).
Malheureusement il y a un bug (assez rare il apparait lorsque la partie est très longue, environ plus de 35 tours) c'est que les bords de mon plateau n'ont pas été bien définit. C'est à dire que mon programme considère que la partie droite du plateau est aussi à gauche (un tableau infini).
Il est alors possible qu'elle aligne 4 pions sur la partie gauche du plateau et poser le 5e pions à droite du plateau.
Ceci étant dit ce programme a quand même finit 8e sur 135 participants. :)
