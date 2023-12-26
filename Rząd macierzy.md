- Ilość niezależnych od siebie wierszy (takich których nie da się ze sobą wyzerować)
- działania elementarne na wierszach i kolumnach nie zmieniają rzędu macierzy

Def:
	**Rzędem** niezerowej macierzy A nazywamy maksymalny stopień niezerowego [[Minor macierzy|minora tej macierzy]]. // czyli to co poniżej
	Dla macierzy zerowej przyjmujemy, że rząd jest równy zero.

Oznaczenie: rząd macierzy A oznaczamy $r(A)$

##### Liczenie:
- sprowadzanie macierzy do postaci gdzie w którejś z kolumn jest tylko jeden wyraz niezerowy -> wykreślamy ***rząd i kolumnę*** z tym wyrazem *i dodajemy jedynkę*
- jeśli jest kolumna lub rząd wyłącznie z samych zer to wykreślamy go i tyle
![[Pasted image 20231219235509.png]]

- po sprowadzeniu do macierzy 2x2 są pewne zasady:
	1) jeśli det(A) != 0 ---> r(A) = 2
	2) jeśli detA = 0 ---> r(A) = 1
- jeśli zostanie macierz co ma tylko jeden wiersz albo jedną kolumnę to:
	1) jeśli ma conajmniej jeden element różny od zera ---> r(A) = 1
**RZĄD MACIERZY ZEROWEJ = 0**


#### Liniowa niezależność wektorów


