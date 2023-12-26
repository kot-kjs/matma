- Tylko macierze kwadratowe mogą mieć odwrotność
- Jeśli det(A) = 0 to macierz jest nieodwracalna (osobliwa)



- ---

[[Minor macierzy]]
[[Rząd macierzy]]

#### Sposób I (gorszy bo nie zawsze można) - znajdowanie macierzy odwrotnej przy pomocy macierzy dopełnień algebraicznych

![[Pasted image 20231215190447.png]]
![[Pasted image 20231215190459.png]]
![[Pasted image 20231215190506.png]]
wzór na macierz odwrotną
![[Pasted image 20231215215903.png|200]]
gdzie:
	$A^D$ - [[macierz dopełnień]]

##### Jak to zrobić:
1) Policzyć wyznacznik (jeśli jest 0 to nie ma macierzy odwrotnej)
2) Macierz dopełnień
3) Transpozycja macierzy $A^D$
##### Sprawdzenie:
- pomnożyć $A^{-1}\times A$       -> powinno wyjść $I$

#### Sposób II - metoda Gaussa - Jordana
![[Pasted image 20231215221210.png]]
- Do macierzy A doklejamy macierz jedynkową i przeprowadzamy procesy Gaussa na wierszach tak, żeby po lewej stronie wyszła macierz jedynkowa. Ta doklejona będzie wtedy macierzą odwrotną do A
