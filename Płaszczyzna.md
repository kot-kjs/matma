
[[Geometria w R3]]

---
- oznaczenie $\pi$

![[Pasted image 20231217201848.png|300]]
![[Pasted image 20231217201800.png|300]]

#### Równania płaszczyzny
##### 1.Ogólne
$\pi: ax + by + cz + d = 0$
gdzie:
	a,b,c - składowe wektora normalnego
	
##### 2.Normalne
$\pi: ax + by + cz + d = 0$
$|\vec{n}| = \sqrt{a^2+b^2+c^2}=1$

##### 3. Odcinkowe *(nie zawsze istnieje)*
$\frac{x}{A} + \frac{y}{B} + \frac{z}{C} = 1$
${a,b,c} \ne 0$


#### Ogólne info
- każde 3 punkty, (jeśli wszystkie nie są współliniowe) określają jedną płaszczyznę (są współpłaszczyznowe)
	![[Pasted image 20231217202617.png|400]]


##### Wzajemne położenie płaszczyzn:
płaszczyzny mogą być:
1) równoległe
   ![[Pasted image 20231217202749.png]]
2) przecinające się
   ![[Pasted image 20231217202853.png]]
3) prostopadłe 
   ![[Pasted image 20231217202916.png]]



#### Jak wyznaczyć równanie płaszczyzny? *(ogólne)*
1) Potrzeba:
- jakikolwiek punkt należący do płaszczyzny
- jakikolwiek wektor do niej prostopadły
2) Napisać równanie płaszczyzny:
	 $\pi: ax + by + cz + d = 0$
	 gdzie:
		$a,b,c$ - składowe wektora prostopadłego
		$x,y,z$ - współrzędne punktu
3) Rozwiązać te równanie z jedną niewiadomą d -> podstawić d i wektor normalny do pierwszego wzoru żeby zyskać całe równanie

##### Ex
Wyznaczyć równanie płaszczyzny mając prostopadły do niej wektor $\vec{n}=[3,5,-1]$ i punkt do niej należący $A(1,-3,-5)$
	$\pi: ax + by + cz + d = 0$
	*podstawienie punktu i wektora*
	$\pi: 3\times 1 +5\times (-3) -1 \times 5 + D = 0$
	*wyliczenie D*
	$3 - 15 + 5 + D = 0$
	$D = 7$
	*napisanie pełnego równania*
	$\pi: 3x + 5y -z + 7 = 0$

##### Ex.2
Znaleźć równanie płaszczyzny przechodzącej przez początek układu współrzędnych o wektorze normalnym $\vec{n} = [-2,-4,4]$
	*podstawienie punktu (0,0,0) i wektora*
	$\pi: -2\times 0 - 4 \times 0 + 4\times 0 + d = 0$
	d = 0
	*napisanie pełnego równania*
	$\pi: -2x -4y + 4z = 0$

##### Ex.3 
Dane są dwa punkty A(2,3,-1) i B(-4,4,0). Znajdź równanie płaszczyzny przechodzącej przez punkt A i $\perp$ do wektora $\vec{AB}$
1) wyznaczyć wektor $\vec{AB}$ 
2) reszta ta sama
   ![[Pasted image 20231218001007.png|400]]

##### Ex.4
Znajdź równanie płaszczyzny przechodzącej przez punkt A(2,3,-7) i $\parallel$ do wektorów $\vec{a}=[3,-3,2]$ i $\vec{b}=[1,5,-1]$
1) zauważyć że a i b można zaczepić w jednym punkcie i wyznaczyć wektor prostopadły do nich (iloczyn wektorowy)
2) mając punkt i wektor normalny wyznaczyć równanie tak jak wcześniej
![[Pasted image 20231218002846.png]] 
