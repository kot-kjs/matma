[[wektory]]
[[Płaszczyzna]]
[[Prosta]]


#### Problemy (teoria):

##### Odległość punktu A od płaszczyzny:
jeśli punkt nie należy do płaszczyzny

1) znaleźć wektor normalny płaszczyzny
2) zrobić prostą przechodzącą przez punkt A, biorąc wektor normalny jako kierunkowy 
3) znaleźć punkt przecięcia prostej i płaszczyzny -> to będzie A'
4) policzyć odległość między punktami A i A'

##### Rzut punktu A na płaszczyznę:
jeśli punkt nie należy do płaszczyzny

1) zrobić prostą przechodzącą przez punkt A i prostopadłą do płaszczyzny
2) znaleźć punkt przecięcia prostej i płaszczyzny -> to będzie A'

##### Rzut punktu A na prostą
jeśli punkt nie należy do prostej

1) zrobić płaszczyznę przechodzącą przez punkt A i prostopadłą do prostej 
	- wektor kierunkowy prostej to wektor normalny płaszczyzny
2) znaleźć punkt przecięcia prostej i płaszczyzny -> to będzie A'

##### Rzut prostej na płaszczyznę
jeśli prosta nie należy do płaszczyzny
![[Pasted image 20231217212701.png|300]]
mając wektor normalny n i wektor kierunkowy v:
1) wyznaczyć wektor $\vec{p} = \vec{v}\times \vec{n}$, który będzie wektorem normalnym płaszczyzny zawierającej prostą i prostopadłej do płaszczyzny $\pi$
3) Rzutem prostej na płaszczyznę będzie przecięcie tych dwóch płaszczyzn


#### Problemy (praktyka):
##### Rzut punktu A na płaszczyznę:
Dane:
	$A = (-4,-5,2)$
	$\pi: 7x+6y+3z+5=0$
![[Pasted image 20231219165542.png|200]]

1) znaleźć prostą zawierającą w sobie wektor normalny i punkt A
$\vec{n} = [7,6,3]$
![[Pasted image 20231219165923.png|100]]![[Pasted image 20231219170046.png|120]]
2) Punkt przecięcia prostej i płaszczyzny:
	- podstawić do równania płaszczyzny x,y,z z równania prostej (rysunek drugi powyżej) i wyliczyć t 
	- podstawić t do równania prostej żeby mieć punkt P
	![[Pasted image 20231219170254.png|300]]
	$P=(-\frac{1}{2}, -2, -\frac{7}{2})$ -> *Rzut punktu na płaszczyznę*
##### Punkt symetryczny do A względem płaszczyzny:
1) znaleźć rzut punktu
2) stworzyć wektor między rzutem a punktem
3) zauważyć że ten sam wektor $*(-1)$ będzie się kończył na A'
4) Aby otrzymać punkt symetryczny A' dodać punkt A do wektora $\vec{AP}$
![[Pasted image 20231219170928.png|400]]

##### Rzut punktu na prostą:
$A=(0,1,2)$
![[Pasted image 20231219172332.png|100]]
![[Pasted image 20231219172326.png]]
1) budowanie płaszczyzny prostopadłej do prostej i zawierającej A i A'
- wektor kierunkowy prostej to wektor normalny płaszczyzny
$\vec{v}=[-1,0,2]$
*Budowanie płaszczyzny mając wektor normalny i punkt*
![[Pasted image 20231219172524.png|200]]

2) punkt przecięcia prostej i płaszczyzny (podstawienie równań prostej do r. płaszczyzny):
![[Pasted image 20231219172631.png]]
