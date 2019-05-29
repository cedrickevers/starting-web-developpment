# Projet Tim Berners-Lee

## Description du html
La page html se compose de 3 div principals contenus dans un  main.

- La div about contient : 
    - Une image (tim-berner-lee.png)
    - Deux titre (h1,h2)
    - Un paragraphe (p)
    - Un lien (a) conenu dans le paragraphe 
- La div social-network contient : 
    - Une liste non ordonée (ul)
    - Trois liens vers les réseaux sociaux 
- La div fav-movies contient :
    - Un tableau
    - Un th qui contient un h2
    -3 td contenant chacun une img, un h3 et un p


## Description du css

### Partie About

Un display flex à été appliqué  au container ainsi qu'une direction column ainsi qu'un justify-content afin de placr
tous éléments enfants les un en dessous des autres et de les centré.

Concernant l'image de Tim Berners-Lee, j'ai appliqué un border-radius de 40%, afin de lui donner son aspect arrondi.
Le bouton à été réalisé à l'aide d'un border et d'un padding pour en augmenter la dimension.


### Partie social network

Comme pour la partie about un display flex à été appliqué au container, sauf qu cette fois l'orientation par défaut (row à été gardée).

Pour centrer les items au milieu j'ai réduit leur taille via via un calcul flex ```flex: calc(100% -2rem)``` On garde 100% de leur taille initial et on soustrait  2 rem (de chaques côtés). 
Ensuite on applique un goutière en créant égalment un space de 2 rem entre les objets et le bord:``` margin:0 2rem;``` 

###Partie fav movies	

Le choix du tableau s'est fait par défaut car il fallait uniquement avec du html aligner des blocs en display block.


