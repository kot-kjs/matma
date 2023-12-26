![[Pasted image 20231217194331.png]]
Rozwiązaniem układu n równań liniowych nazywamy każdy $m$-elementowy ciąg liczb, dla których są spełnione równocześnie wszystkie równania tego układu

- Układ równań liniowych może mieć:
	- jedno rozwiązanie - układ oznaczony
	- nieskończenie wiele rozwiązań - układ nieoznaczony ($detA=0$)
	- 0 rozwiązań - układ sprzeczny
	  
- Jeśli równań jest tyle samo co niewiadomych -> twierdzenie Cramera
- Jeśli równań jest mniej niż niewiadomych -> 
	- rozszerzamy macierz do postaci $[A|b]$
	  Macierz ma *postać normalną Gaussa*, kiedy:
	  1) wiersze zerowe (jeśli są) są na dole macierzy
	  2) jeśli wiersz nie składa się wyłącznie z zer, to pierwszym niezerowym elementem jest 1 (element wiodący)
	  3) dla dwóch kolejnych (i niezerowych) wierszy element wiodący w wyższym jest bardziej na lewo niż w niższym
	  4) element wiodący jest jedynym niezerowym elementem w kolumnie (kolumna ma tylko same zera i tą jedną jedynkę)
	- jeśli spełnione są tylko warunki 1-3, to macierz jest *macierzą półnormalną Gaussa*

#### Układy równań o dowolnym wymiarze
![[Pasted image 20231217195403.png]]
gdzie:
	r(A) - rząd macierzy A
- [[Proces Gaussa]] _nie zmienia_ rzędu macierzy
- Rząd macierzy półnormalnej/normalnej Gaussa jest równy liczbie niezerowych wierszy tej macierzy

#### Układ równań jednorodnych
- zawsze ma rozwiązanie -> jeśli ma jedno to jest nudno, ale może też mieć nieskończoność, wtedy każde rozwiązanie jest inne
![[Pasted image 20231217195700.png]]

***Układ liniowy jest układem Cramera gdy:***
- ma tyle samo równań co niewiadomych
- Jego wyznacznik główny jest różny od 0