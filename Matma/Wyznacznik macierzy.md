- Istnieje tylko dla macierzy kwadratowych
- oznacza się przez det(A) albo przez kreski modułu zamiast nawiasów macierzy

#### Liczenie wyznacznika
- 2 x 2 -> odejmowanie iloczynów przekątnych (kolejność taka jak przy rysowaniu znaku ✓)
![[Pasted image 20231215173352.png|300]]
- 3 x 3 -> Metoda Sarrusa (analogiczna do powyższej) albo rozwinięcie Laplace'a i sprowadzenie do 2 x 2
![[Pasted image 20231215173555.png | 600]]
- większe -> Twierdzenie Laplace'a
  ![[Pasted image 20231215173712.png]]
  - generalnie najlepiej robić do dla wiersza / kolumny która ma jak najwięcej zer - wtedy jest mniej liczenia bo się mnoży \*0
  - jeśli macierz ma wiersz albo kolumnę gdzie są same zera to wyznacznik = 0
![[Pasted image 20231215173905.png]]
- macierz trójkątna -> taka która ma powyżej albo poniżej głównej przekątnej same zera

##### Wyznacznik macierzy blokowej
- Macierz można podzielić na bloki (kwadratowe) w taki sposób, że ponad albo poniżej tych bloków (robimy wtedy jakby dziwną przekątną) są same zera. Wtedy, podobnie jak przy macierzach trójkątnych, wyznacznik równa się wyznacznikom poszczególnych bloków.
![[Pasted image 20231215175407.png]]
Ex: 
	![[Pasted image 20231215175625.png]]

##### Własności wyznacznika
- Jeśli macierz ma wiersz lub kolumnę z samych zer to wyznacznik = 0
- Jeśli macierz jest trójkątna to wyznacznik = iloczynowi elementów na przekątnej
- $det(A^T) = det(A)$
- Dla dwóch macierzy $n*n$ : 
	  $det(A\cdot B) = det(A) \cdot det(B)$
- $det(A^n) = (detA)^n$
- Zamiana dwóch wierszy miejscami równa się przemnożeniu wyznacznika \*(-1)
- Mnożenie wiersza przez niezerowy skalar mnoży też wyznacznik przez ten sam skalar
	- Działa w drugą stronę -> można wyłączyć ten mnożnik przed wyznacznik dzieląc wiersz przez skalar
- Dodawanie wiersza pomnożonego przez skalar do innego wiersza nie zmienia wyznacznika
- Wyznacznik jest zerowy gdy:
	  - dwa wiersze lub dwie kolumny są liniowo proporcjonalne (albo takie same)
	  - jeden z wierszy lub kolumn składa się z samych zer

###### Do czego ich używać?
- Można sprowadzić macierz do takiej postaci, gdzie w wierszu lub kolumnie jest jak najwięcej zer
- Sprowadzić macierz do postaci trójkątnej
