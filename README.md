# Modul1TreeAndSort
Dette er vejl. løsning til [programmeringsøvelserne i uge 2. af modul 1](https://datsoftlyngby.github.io/dat2sem2017Fall/Modul1/).

[Big O exercises](https://datsoftlyngby.github.io/dat2sem2017Fall/Modul1/bigOexercises.html) har nogle opgaver. Den vejledende løsning til disse er:

#### 1
Store O for dette program er O(n), hvor n er længden på array der gives som parameter.

#### 2
N \ big O   | O(n)|O(n<sup>2</sup>)|O(n<sup>3</sup>)
---|---|---|---1.000 | 5 | 25 | 1252.000 | 10 | 100 | 1.0003.000 | 15 | 225 | 3.37510.000 | 50 | 2.500 | 125.000

#### 3

opg | løs
---|---
n<sup>2</sup>+ 2n + 1 | n<sup>2n<sup>10</sup> + 9n<sup>9</sup> + 20n<sup>8</sup> + 145n<sup>7</sup> |n<sup>10</sup>n + (0.001)n<sup>3</sup> |n<sup>3</sup>n + *log*(n) | n

#### 4
Det er ikke beskrevet hvilken logaritme der skal bruges. Her er det løst med log<sub>10</sub>. Forskellen mellem log<sub>2</sub> og log<sub>10</sub> er en faktor 3.32 

n | log(n) |n<sup>2</sup> | n*log(n)
---|---|---|---
10 | 1| 100 | 10
100 | 2 | 10.000 | 200
1000 |3 | 1.000.000 | 3000
5.700.000 (number of danes) | 6,76 | 32.490.000.000.000 | 38.532.000
7.400.000.000 (people in the world) | 9,87 |54.760.000.000.000.000.000 | 73.038.000.000

