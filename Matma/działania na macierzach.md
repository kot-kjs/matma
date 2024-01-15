##### 1. Dodawanie i odejmowanie - self explanatory
##### 2. Dzielenie - niemożliwe (ale można pomnożyć przez macierz odwrotną)
---
#### 3. Mnożenie:
- nieodwracalne
- używane w równaniach tego typu
	![[Pasted image 20231215185157.png]]
	![[Pasted image 20231215185233.png]]


- Żeby w ogóle macierze pomnożyć, pierwsza musi mieć tyle samo kolumn co druga wierszy:
  ![[Pasted image 20231215164303.png]]

  
######  Ale jak to robić:
- Wyjściowa macierz będzie miała wymiar taki jak wyżej
- każdy wyraz tej macierzy liczy się przez potraktowanie odpowiedniego wiersza pierwszej macierzy i odpowiedniej kolumny drugiej jako wektory i wymnożenie ich skalarnie.

  ![[matrix_multi_1.png]]!
  ![[matrix_multi_2.png]]
- Żeby się nie pomylić które komórki biorą które wiersze etc można użyć tabelki:


  



#### 4. Działania elementarne (przekształcenia Gaussa)
- Lepiej robić to na wierszach bo bardziej użyteczne
	- Po przekształceniach kolumnowych macierze są tylko kolumnowo równoważne (nie nadaje się to do układów równań). -> Jedyne zastosowania to wyznaczniki i rzędy macierzy
- Działania na wierszach można wykorzystać do:
	  - znajdowania wyznaczników
	  - znajdowania macierzy odwrotnych
	  - znajdowania rzędu
	  - układów równań liniowych (eliminacje Gaussa i  Gaussa-Jordana)
- Możliwe przekształcenia wierszy:
	  - zamiana kolejności dwóch wierszy (wtedy wyznacznik mnoży się \*-1 )
	  - mnożenie przez niezerową stałą (wyznacznik też się mnoży)
	  - dodanie wiersza pomnożonego przez stałą do innego wiersza (wyznacznik taki sam)

#### 5. Szukanie wyznacznika - [[Wyznacznik macierzy]]

#### 6. Szukanie macierzy odwrotnej - [[Macierz odwrotna]]

