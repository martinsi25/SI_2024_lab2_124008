Martin Stojkovski 124008

###  Control Flow Graph

![alt text](https://github.com/martinsi25/SI_2024_lab2_124008/blob/43e377a01886b5c8c53474a1b8b0e258ccc0ecb5/cfg.png)

### Цикломатска комплексност

N=23 E=31
Цикломатската комплексност на овој код е M=E-N+2P=31-23+2=6.

### Тест случаи според критериумот: Every Branch

Paths:
1. 1 2 23 - T
2. 1 3 4 5 6 7 8 23 - F T T F
3. 1 3 4 5 6 7 9 10 11 12 13 23 - F T T T T
4. 1 3 4 5 6 7 9 10 11 12 14 15 17 18 19 20 21 23 - F T T T F T T T
5. 1 3 4 5 6 7 9 10 11 12 14 16 17 19 20 22 23 - F T T T F F F F

