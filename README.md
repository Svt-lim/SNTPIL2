# SNTPIL2  
# Quelques nuances de gris.  
Pour convertir une image en nuances de gris il y a deux solutions :  
  faire la moyenne des valeurs RGB pour chaque pixels  g=(r+g+b)/3  
  appliquer par la C.I.E (Commission Internationale de l'Éclairage) pour les couleurs non-linéaires (image vue à partir d'un écran vidéo)  
  g= (0.299r+0.578v+0.114b)  
dans tous les cas il faut recalculer chaque pixel.  
préparez le code suivant  :

# DEFI :  
passez en nuances de gris la photo de la Tour d'Arundel *(Les Sables d'Olonne)*  
Indice0, pour creer une image en nuances de gris il faut utiliser le code L et non RGB avec la fonction Image.new(couleur, (largeur, hauteur))  de l'activité précédente.  
Indice1, il s'agit ici d'adapter le programme de l'activité 1 à vos besoins. 
