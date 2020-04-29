# Méthode Fridrich : accessible à tous

[Grosse image crane]

[Grosse image cube engrenages]

---

## Méthode Fridrich : sommaire

[Grosse image crane]

- Introduction à la méthode

  - Présentation de la méthode
  - Présentation du langage universel
  - Astuces et conseils pour l'apprentissage

- Méthode complète

  - La croix parfaite
  - Les **42** F2L (First Two Layers)
  - Les **57** OLL (Orientation Last Layer)
  - Les **21** PLL (Permutation Last Layer)

---

## Méthode Fridrich : qu'est-ce la méthode CFOP ?

[Grosse image crane]

[Début effet bulle]

La méthode créée par Jessica Fridrich autrement appelé la méthode CFOP (Cross F2L OLL PLL) est une technique de résolution du Rubik's Cube 3x3x3 très rapide et souvent utilisée par les champions lors des compétitions.  
Cette méthode ne nécessite pas la moindre "grande intelligence", les seules qualités requises sont une bonne mémoire et il est préférable d'avoir de bon reflex dans les doigts.

[Fin effet bulle]

Le but est de résoudre le Rubik's Cube en 4 étapes, soit la croix et 6 algorithmes au maximum :

### Étape 1

[Image croix]

La croix (Cross) est résolue logiquement avec une moyenne de 8 mouvements en 2-3 secondes, pour arriver à la résoudre aussi rapidement il est nécessaire de bien connaître les couleurs de son cube et de beaucoup s'entraîner afin de préparer les mouvements à l'avance. Il n'y a pas vraiment d'algorithme à apprendre pour cette étape.

---

[Petite image crane]

[Rappel : Méthode Fridrich : Qu'est-ce que la méthode CFOP ?]

[Petite image cube engrenages]

### Étape 2

[Image F2L]

Les F2L (First Two Layers) sont l'étape la plus longue consistant à résoudre les deux premiers étages. Le but est de regrouper un coin et une arête complémentaires appartenant à la face de référence (dont la couleur est celle de la croix) puis de les placer en même temps.  
Cette étape regroupe 42 cas dont 41 algorithmes (plus le cas résolu) mais elle peut se faire logiquement pour certains. Il est cependant préférable d'apprendre les algorithmes de la méthode pour aller plus vite.

### Étape 3

[Image OLL]

Les OLL (Orientation Last Layer) sont l'étape consistant à orienter tous les cubes de la couleur de la dernière face sur celle-ci (la face opposée à la première face) afin qu'elle soit unicolore et qu'il ne reste plus que la troisième couronne à compléter. Cette étape regroupe 57 algorithmes.

### Étape 4

[Image grand cube fait]

Les PLL (Permutation Last Layer) sont l'étape où l'on va permuter les coins et les arêtes de la troisième couronne afin de refaire le cube. Cette étape regroupe 21 algorithmes.

---

[Grosse image crane]

## Méthode Fridrich : Le langage universel

[Début effet bulle]

Dans le mondu du Rubik's Cube, le langage universel est très utile. Il permet à la fois d'écrire n'importe quel algorithme de façon très courte (une lettre par mouvement) et peut être compris par n'importe qui dans le monde utilisant une méthode avancée, ce qui permet de suivre toute sorte de tutoriel avancé en anglais. De plus ce langage est souvent utilisé dans les logiciels de modélisation tel que Cube Explorer (très utile pour chercher et tester des algorithmes).

[Fin effet bulle]

Pour lire ce langage il faut connaître les choses suivantes :

- Une lettre correspond à une face (Front - Up - Right - Left - Down - Back), je vais également ajouter Milieu qui est un petit peu différent dans ma version du langage

- Une majuscule simple signifie qu'il faut tourner la face dans le sens des aiguilles d'une montre (lorsqu'elle est positionnée face à nous). Une apostrophe correspond au mouvement inverse donc dans le sens inverse des aiguilles d'une montre et le chiffre 2 veut dire qu'il faut tourner deux fois la face (donc le sens n'a aucune importance)

- Une minuscule signifie qu'il faut tourner la face et la tranche du milieu consécutive dans le même sens selon l'apostrophe, le chiffre 2 ou rien (donc la seule face à tourner est celle désignée par la lettre)

[Image petit cube fait]

Si vous êtes perdu pas d'inquiétude, les exemples seront plus clairs !

[Image petit cube fait miroir]

---

[Petite image de crane]

[Rappel : Méthode Fridrich : Le langage universel]

[Petite image cube engrenages]

[Image moyen cube fait]

Afin de vous présenter le langage, nous allons mettre la face bleue face à nous avec la face jaune au dessus

[Images R - R' - R2 - r]  
R - R' - R2 - r

[Images r' - r2 - L - L']  
r' - r2 - L - L'

[Images L2 - l - l' - l2]  
L2 - l - l' - l2

---

[Petite image de crane]

[Rappel : Méthode Fridrich : Le langage universel]

[Petite image cube engrenages]

[Images U - U' - U2 - u]  
U - U' - U2 - u

[Images u' - u2 - D - D']  
u' - u2 - D - D'

[Images D2 - d - d' - d2]  
D2 - d - d' - d2

[Images F - F' - F2 - B]  
F - F' - F2 - B

---

[Petite image de crane]

[Rappel : Méthode Fridrich : Le langage universel]

[Petite image cube engrenages]

[Images B' - B2 - M]  
B' - B2 - M

[Images M' - M2]  
M' - M2

Je tiens à préciser que dans le réel langage universel, M et M' sont inversés et il y a d'autres mouvements qui ne sont pas utilisés dans les algorithmes de la méthode.

Il y a également les changements de points de vue à connaître pour lire les algorithmes, je les représente par une flèche indiquant la face de référence avant et après avoir changé de point de vue.  
Pour généraliser, FaceA → FaceB siginfie que l'on doit déplacer le cube (sans faire de mouvement) de façon à ce que la face "B" soit positionnée à la place de la face "A" qui est placée face à nous.

[Image petit cube fait]

Si vous êtes perdu pas d'inquiétude, les exemples reviennent !

[Image petit cube fait miroir]

---

[Petite image de crane]

[Rappel : Méthode Fridrich : Le langage universel]

[Petite image cube engrenages]

[Image moyen cube fait]

On prend une fois de plus la face bleue comme référence.  
Voici donc tous les cas utilisés dans les algorithmes que je vous présente :

[Image moyen cube fait] → [Image moyen cube fait R->F]  
La face de droite passe à la place de la face de devant. On le note F→F.

[Image moyen cube fait] → [Image moyen cube fait L->F]  
La face de gauche passe à la place de la face de devant. On le note L→F.

[Image moyen cube fait] → [Image moyen cube fait U->F]  
La face du haut passe à la place de la face de devant. On le note U→F.

[Image moyen cube fait] → [Image moyen cube fait D->F]  
La face du bas passe à la place de la face de devant. On le note D→F.

---

[Petite image de crane]

[Rappel : Méthode Fridrich : Le langage universel]

[Petite image cube engrenages]

[Image moyen cube fait] → [Image moyen cube fait F->D]  
La face de devant passe à la place de la face du bas. On le note F→D.

[Image moyen cube fait] → [Image moyen cube fait R->U]  
La face de droite passe à la place de la face du haut. On le note R→U.

[Image moyen cube fait] → [Image moyen cube fait L->U]  
La face de gauche passe à la place de la face du haut. On le note L→U.

Maintenant que vous pouvez lire tous les algorithmes de la méthode, il ne reste plus qu'à les apprendre !  
Si vous avez du mal je vous conseil de regarder mes astuces de mémorisation mais vous n'en avez pas besoin pour comprendre comment utiliser la méthode.

[Image petit cube fait]

[Image petit cube fait miroir]

---

[Grosse image de crane]

## Méthode Fridrich : astuces et conseils pour l'apprentissage

[Début effet bulle]

L'apprentissage des algorithmes demande beaucoup de temps et une pratique régulière afin de ne pas les oublier. Il n'existe pas de technique miracle pour apprendre les formules, si vous avez déjà votre méthode d'apprentissage mes conseils ne devraient pas beaucoup vous aider. Je ne suis pas expert en méthodes d'apprentissage mais je peux vous expliquer celle que j'ai trouvé. L'idée est de repérer les mouvements de base afin de décomposer les algorithmes "complexes" (plus de 4 mouvements) en une suite de quelques mouvements de base (de 2 à 4 mouvements).

[Fin effet bulle]

Pour commencer il faut expliquer ce que j'appelle un mouvement de base. Lorsqu'on regarde des algorithmes, on peut les regrouper en plusieurs suites de mouvements très similaires du type M1 M2 M1' M2' qui permet de faire l'action de l'algorithme, combiné avec des suites de transition comme M1 M2 ou M1 M2 M1' qui permettent de se placer en position d'action ou de refaire le cube.  
Dans presque la totalité des cas, M1 et M2 appartiennent à des faces consécutives par exemple R U, D F, L B... Il est donc très rare d'avoir L R, U D ou F B.

[Image petit cube fait]

Si vous êtes perdu pas d'inquiétude, les exemples reviennent encore !

[Image petit cube fait miroir]

---

[Petite image de crane]

[Rappel : Méthode Fridrich : astuces et conseils pour l'apprentissage]

[Petite image cube engrenages]

Pour vous montrer le fonctionnement de cette technique nous allons utiliser l'algorithme suivant :

**R U R' U'** / *R' F* / *R2 U'* / **R' U' R U** / *R' F'*

Ici le vert (gras) représente les suites de transition et le bleu les suites d'action. Il peut y avoir plusieurs façon de découper l'algorithme, je trouve que celle-ci représente bien son fonctionnement.  
**R U R' U'** est l'une des suites des plus utilisées et on peut voir les formes de transition M1 M2 / M1 M2' avec *R' F* / *R' F'* qui est facilement mémorisable. Une fois qu'on a mémorisé les emplacements des suites d'action, très répétitives, et l'emplacement avec la logique des transitions, on peut facilement se souvenir d'un algorithme.

Cet exemple était assez complexe donc pour illustrer de façon plus simple la logique :

*F* / **R U R' U'** / *F'* - ou encore - *R U* / **U R' U' R** / *U' R'*

Dans ces deux cas on voit beaucoup plus la transition au début et à la fin ainsi que la suite d'action au centre. De plus les transitions sont parfaitement symétriques en étant sous la forme M1 / M1' et M1 M2 / M2' M1'.

[Image petit cube fait]

Vous pouvez maintenant passer à l'apprentissage des algorithmes, bonne chance !

[Image petit cube fait miroir]

---

[Grosse image crane]

## Méthode Fridrich : les 42 F2L (First Two Layers)

### Cubes en position, mal orientés :

1. [F2L-1-bas F2L-1-face] L2 U2 L U L' U L U2 L

2. [F2L-2-bas F2L-2-face] L' U2 L' U' L U' L' U2 L2

3. [F2L-3-bas F2L-3-face] R U' R U B U' B' R2

4. [F2L-4-bas F2L-4-face] L' U L' U' B' U B L2

5. [F2L-5-bas F2L-5-face] R U R' U2 R U2 R' U F' U' F

6. [F2L-6-bas F2L-6-haut F2L-6-face] U' L' U L d R U' R'

---

[Petite image de crane]

[Rappel : Méthode Fridrich : les 42 F2L (First Two Layers)]

### Coin en position, pas l'arête

7. [F2L-7-bas F2L-7-haut F2L-7-face] U R U' R' d' L' U L

8. [F2L-8-bas F2L-8-haut F2L-8-face] L' U L U' L' U L

9. [F2L-9-bas F2L-9-haut F2L-9-face] R U R' U' R U R'

10. [F2L-10-bas F2L-10-haut F2L-10-face] L' U' L U L' U' L

11. [F2L-11-bas F2L-11-haut F2L-11-face] R U' R' U R U' R'

### Arête en position, pas le coin

12. [F2L-12-bas F2L-12-haut F2L-12-face] R2 U R2 U R2 U2 R2

---

[Petite image de crane]

[Rappel : Méthode Fridrich : les 42 F2L (First Two Layers)]

13. [F2L-13-bas F2L-13-haut F2L-13-face] U L' U L U2 L' U L

14. [F2L-14-bas F2L-14-haut F2L-14-face] U' R U' R' U2 R U' R'

15. [F2L-15-bas F2L-15-haut F2L-15-face] U L' U' L U' F U F'

16. [F2L-16-bas F2L-16-haut F2L-16-face] U' R U R' d R' U' R

17. [F2L-17-bas F2L-17-haut F2L-17-face] F' U F R U2 R'

### Cubes à droite, accolés

18. [F2L-18-bas F2L-18-haut F2L-18-face] R U2 R' U' R U R'

19. [F2L-19-bas F2L-19-haut F2L-19-face] U R U' R'

---

[Petite image de crane]

[Rappel : Méthode Fridrich : les 42 F2L (First Two Layers)]

20. [F2L-20-bas F2L-20-haut F2L-20-face] U' R U' R' U R U R'

21. [F2L-21-bas F2L-21-haut F2L-21-face] U2 L2 U2 L U L' U L2

22. [F2L-22-bas F2L-22-haut F2L-22-face] U' R U2 R' U F' U' F

23. [F2L-23-bas F2L-23-haut F2L-23-face] R U' R' U2 F' U' F

24. [F2L-24-bas F2L-24-haut F2L-24-face] U L' U L U' L' U' L

25. [F2L-25-bas F2L-25-haut F2L-25-face] U' L' U L

26. [F2L-26-bas F2L-26-haut F2L-26-face] L' U2 L U L' U' L

27. [F2L-27-bas F2L-27-haut F2L-27-face] L' U L U2 F U F'

---

[Petite image de crane]

[Rappel : Méthode Fridrich : les 42 F2L (First Two Layers)]

28. [F2L-28-bas F2L-28-haut F2L-28-face] U L' U2 L U' F U F'

29. [F2L-29-bas F2L-29-haut F2L-29-face] U2 R2 U2 R' U' R U' R2

### Cubes à droite séparés

30. [F2L-30-bas F2L-30-haut F2L-30-face] U2 L' U' L U' L' U L

31. [F2L-31-bas F2L-31-haut F2L-31-face] U R U2 R' U R U' R'

32. [F2L-32-bas F2L-32-haut F2L-32-face] U' L' U2 L U' L' U L

33. [F2L-33-bas F2L-33-haut F2L-33-face] U2 R U R' U R U' R'

34. [F2L-34-bas F2L-34-haut F2L-34-face] U L' U2 L U2 L' U L

---

[Petite image de crane]

[Rappel : Méthode Fridrich : les 42 F2L (First Two Layers)]

35. [F2L-35-bas F2L-35-haut F2L-35-face] R U R'

36. [F2L-36-bas F2L-36-haut F2L-36-face] U L' U' L U2 L' U L

37. [F2L-37-bas F2L-37-haut F2L-37-face] U L' U L U' F U F'

38. [F2L-38-bas F2L-38-haut F2L-38-face] U' R U' R' U F' U' F

39. [F2L-39-bas F2L-39-haut F2L-39-face] U' R U R' U2 R U' R'

40. [F2L-40-bas F2L-40-haut F2L-40-face] U' R U2 R' U2 R U' R'

41. [F2L-41-bas F2L-41-haut F2L-41-face] L' U' L

[Image petit cube fait]

Vous pouvez maintenant passer à l'apprentissage, bonne chance !

[Image petit cube fait miroir]

---

[Grande image de crane]

## Méthode Fridrich : les 57 OLL (Orientation Last Layer)

### Les carrés

1. [OLL-1] r U2 R' U' R U' r'
2. [OLL-2] l' U2' L U L' U l

### Les "W"

3. [OLL-3] R U R' U R U' R' U' l' U R U'
4. [OLL-4] R' U' R U' R' U R U l U' R' U

### Les "S"

5. [OLL-5] R' F R U R' U' F' U R
6. [OLL-6] L F' L' U' L U F U' L'

### Les "C"

7. [OLL-7] R' U' R' F R F' U R
8. [OLL-8] R U R' U' B' R' F R F' B

### Les "T"

9. [OLL-9] F R U R' U' F'
10. [OLL-10] R U R' U' l' U R U'

---

[Petite image crane]

[Rappel : Méthode Fridrich : les 57 OLL (Orientation Last Layer)]

[Petite image cube engrenages]

### Les éclairs

11. [OLL-11] r U R' U R U2 r'
12. [OLL-12] l' U' L U' L' U2 l
13. [OLL-13] r R2 U' R U' R' U2 R U' M'
14. [OLL-14] r' R2 U R' U R U2 R' U M

### Les flèches

15. [OLL-15] R' F R F' d' L' U L
16. [OLL-16] R' U2 l R U' R' U l' U2 R
17. [OLL-17] R' U' R L→F U→F R U' R' F R U R'
18. [OLL-18] R U R' D→F R→U R' U R B' R' U' R

### Les "P"

19. [OLL-19] F' L F L' U' L' U' L U L' U L
20. [OLL-20] F R' F' R U R U R' U' R U' R'
21. [OLL-21] F U R U' R' F'
22. [OLL-22] F' U' L' U L F

### Les figures étranges

23. [OLL-23] B' R B' R2 U R U R' U' l U2
24. [OLL-24] R2 U R' B' R U' R2 U l U l'

---

[Petite image crane]

[Rappel : Méthode Fridrich : les 57 OLL (Orientation Last Layer)]

[Petite image cube engrenages]

25. [OLL-25] R U2 R' U' R U' R2 R→F L' U' L U F
26. [OLL-26] L' U2 L U L' U L2 L→F R U R' U' F'

### Les lignes

27. [OLL-27] 
28. [OLL-28] 
29. [OLL-29] 
30. [OLL-30] 

### Les "L"

31. [OLL-31] 
32. [OLL-32] 
33. [OLL-33] 
34. [OLL-34] 

### Les coins

35. [OLL-35] 
36. [OLL-36] 
37. [OLL-37] 
38. [OLL-38] 
39. [OLL-39] 
40. [OLL-40] 

---

[Petite image crane]

[Rappel : Méthode Fridrich : les 57 OLL (Orientation Last Layer)]

[Petite image cube engrenages]

### Tous les coins bien orientés

41. [OLL-41] 
42. [OLL-42] 
43. [OLL-43] 

### Aucune arête bien orientée

44. [OLL-44] 
45. [OLL-45] 
46. [OLL-46] 
47. [OLL-47] 
48. [OLL-48] 
49. [OLL-49] 
50. [OLL-50] 

### Toutes les arêtes bien orientées

51. [OLL-51] 
52. [OLL-52] 
53. [OLL-53] 
54. [OLL-54] 

---

[Petite image crane]

[Rappel : Méthode Fridrich : les 57 OLL (Orientation Last Layer)]

[Petite image cube engrenages]

55. [OLL-55] 
56. [OLL-56] 
57. [OLL-57] 

---

## Les 21 PLL (Permutation Last Layer)
