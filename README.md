# SYL-LABO-Chenillard
## Question 1
La valeur obtenue à la sortie est: 1000

Chronogramme: 
![Chronograme question 1](chronograme_Q1_1.png)

0) Action du reset

1) Décalage de deux (2) bits vers la droite

3) Décalage de trois bits (3) vers la gauche

4) Action du hold

## Question 2

Chronogramme:
![Chronograme question 2](chronogramme_q2_1.png)
D'après le chronogramme on peut bien voir que le mode HOLD est bioen fonctionnel car il remplit bien son rôle de maintien de la dernière valeur de sortie.


## Question 3
Mauro
## Question 4
| Fréquence visée    | Nombre de cycle | equivalence 28 bits en hexadecimal |value_i en hexadecimal|
| ------- | ---         | ---------- |--------------|
| 10 MHz  |  3          |0x3         | 0x2          |
| 2.0 Hz  | 15 000 000  |0xE4 E1C0   | 0xE4 E1BF    |
| 1.0 Hz  | 30 000 000  |0x1C9 C380  | 0x1C9 C3F7   |
|0.5 Hz   | 60 000 000  |0x393 8700  | 0x393 86FF   |

## Question 5
Mauro
## Question 6
Mauro
## Question 7
Les priorités de fonctionnement du chenillard sont les suivantes en ordre croissant: Load, Hold, Shift left, Shift right 
## Question 8
Table de vérité de mode_i
| Load| En  |Shift|mode_i(1)|mode_i(0)|
| ----| --- | --  |---------|---------|
|  0  |  0  |  0  |   0     |   0     |
|  0  |  0  |  1  |   0     |   0     |
|  0  |  1  |  0  |   1     |   0     |
|  0  |  1  |  1  |   1     |   1     |
|  1  |  0  |  0  |   0     |   1     |
|  1  |  0  |  1  |   0     |   1     |
|  1  |  1  |  0  |   0     |   1     |
|  1  |  1  |  1  |   0     |   1     |
## Question 9
Les équations simplifiées de mode_i(0) et mode_i(1)

Table de karnaugh: mode_i(0)=Load+En+Shift
|  0  |  0  |  1  |   1     |
| ----| --- | --  |---------|
|  0  |  1  |  1  |   1     |

Table de karnaugh: mode_i(1)=/Load.En
|  0  |  1  |  0  |   0     |
| ----| --- | --  |---------|
|  0  |  1  |  0  |   0     |
## Question 10


