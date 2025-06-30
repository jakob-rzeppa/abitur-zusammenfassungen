# Ganzrationale Funktionen

## Beschreibung

> Eine **ganzrationale Funktion** oder **Polynomfunktion** ist in der Mathematik eine Funktion, die als Summe von Potenzfunktionen mit natürlichen Exponenten beschrieben werden kann.
>
> — Wikipedia

Eine ganzrationale Funktion kann also wie folgt dargestellt werden:

$$
f(x) = a_{n}x^{n} + a_{n-1}x^{n-1} + \dots + a_{2}x^{2} + a–{1}x + a_{0}
$$

Hierbei gilt:

- $n \in \mathbb{N}$ und wird als Grad der Funktion bezeichnet.
- $a_{n \dots 0} \in \mathbb{R}$ und werden als Koeffizienten bezeichnet.
- $a_n \neq 0$ und ist der Leitkoeffizient.

## Grenzverhalten

Wie sich der Graph einer ganzrationalen Funktion verhält, wenn $x$ gegen $\infty$ oder $-\infty$ geht, hängt davon ab, ob $a_n$ größer oder kleiner $0$ ist und ob $n$ grade oder ungrade ist.  
Es besteht folgender Zusammenhang:

|         | $n$ ist grade                             | $n$ ist ungrade                                                                 |
| ------- | ----------------------------------------- | ------------------------------------------------------------------------------- |
| $a_n>0$ | $f(x) \to \infty$ für $x \to \pm \infty$  | $f(x) \to \infty$ für $x \to \infty$ und $f(x) \to -\infty$ für $x \to -\infty$ |
| $a_n<0$ | $f(x) \to -\infty$ für $x \to \pm \infty$ | $f(x) \to -\infty$ für $x \to \infty$ und $f(x) \to \infty$ für $x \to -\infty$ |

## Symmetrie

Der Graph einer ganzrationalen Funktion ist Achsen symetrisch um die $y$-Achse wenn, allle Exponenten grade sind. Er ist um den Nullpunkt punktsymmetrisch, wenn alle Exponenten ungrade sind.

## Nullstellen

Eine Nullstelle ist $x_0$ in der Gleichung $f(x_0)=0$.

Die höchst mögliche Anzahl von Nullstellen, die eine ganzrationale Funktion haben kann, entspricht ihrem Grad. Eine ganzrationale Funktion $n$-ten Grades kann also $n$ Nullstellen haben.

Eine ganzrationale Funktion kann auch als Produkt von Linearfaktoren vorliegen. Das sieht so aus:

$$
f(x) = (x-x_1)^{k_1} \cdot (x-x_2)^{k_2} \cdots (x-x_m)^{k_m} \cdot g(x)
$$

Dabei gilt:

- $x_{1 \dots m}$ sind die Nullstellen.
- $k_{1 \dots m} \in \mathbb{N}$ und sind die Vielfachheit der Nullstellen.
- $g$ ist eine ganzrationale Funktion ohne Nullstelle

Ein Bespiel:

$$
f(x) = (x-3) \cdot (x+1)^2 \cdot (x+4)^3
$$

Die Nullstellen sind hier $3$, $-1$ und $-4$

Ganzrationale Funktionen haben 3 Gruppen von Nullstellen.

1. Eine einfache Nullstelle\
   ![Einfache Nullstelle](../../../images/Mathe/Einfache%20Nullstelle.png)
2. Eine grade Nullstelle\
   ![Grade Nullstelle](../../../images/Mathe/Grade%20Nullstelle.png)
3. Eine ungrade Nullstelle (größer $1$)\
   ![Ungrade Nullstelle](../../../images/Mathe/Ungrade%20Nullstelle.png)
