# TP1 - Synthèse d'image

Yann Letourneur, INFO4

## Afin d'éxecuter le programme principal

### La première fois
Se placer simplement à la racine du dossier (où est situé ce README.md) puis éxecuter les commandes :
```
mkdir build
cd build
cmake ..
make
./si_info4
```

### Pour changer de forme à afficher

Ne changer que la variable `forme_a_dessiner` au début du main avec une des valeurs suivante :
```
DESSIN_SANS_VAO = 0
TRIANGLE = 1
CARRE = 2
CARRE_EFFICACE = 3
CUBE = 4
POINTS = 5
LINES = 6
LINE_STRIP = 7
LINE_LOOP = 8
TRIANGLE_STRIP = 9
TRIANGLE_FAN = 10
```

Ensuite, à chaque modification du main, l'éxecuter avec :
```
make
./si_info4
```

## Références

Le sujet de TP (d'où provient une partie du code) est disponible dans le dossier `doc`.