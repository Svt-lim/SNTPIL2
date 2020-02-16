# SNTPIL2  
# Quelques nuances de gris.  
Pour convertir une image en nuances de gris il y a deux solutions :  
  faire la moyenne des valeurs RGB pour chaque pixels  g=(r+g+b)/3  
  appliquer la formule de la C.I.E (Commission Internationale de l'Éclairage) pour les couleurs non-linéaires (image vue à partir d'un écran vidéo)  
  g= (0.299* r+0.578* v+0.114* b)  
dans tous les cas il faut recalculer chaque pixel.  
préparez le code suivant  :  
![image](https://github.com/Svt-lim/SNTPIL2/blob/master/1.jpg)

# DEFI :  
passez en nuances de gris la photo de la Tour d'Arundel *(Les Sables d'Olonne)*  
Indice0, pour creer une image en nuances de gris il faut utiliser le code L et non RGB avec la fonction Image.new(couleur, (largeur, hauteur))  de l'activité précédente.  
Indice1, il s'agit ici d'adapter le programme de l'activité 1 à vos besoins. 
# Evaluation 1 :  
Faire un filtre pour passer l'image en négatif. Pour afficher l'inverse d'un pixel il faut faire 225-r, 255-v, 255-b  

# Evaluation 2 :  
En vous basant sur la formule pour calculer un niveau de gris, réalisez un filtre "instagram" en passant le rouge et le v à 107% de leur valeur et en diminuant le b à 88% NB : dans la formule des niveau de gris, 107 %  s'écrit 1.07 et 88% s'écrit 0.88 

# lien :  
pour faire les deux évaluations il faut ouvrir le programme suivant et en faire un fork  https://repl.it/@jpeaud/SNTPIL1

