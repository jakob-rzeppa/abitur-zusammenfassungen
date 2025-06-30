# Integral

Die Integration ist die Umkehrung der Ableitung und dient der Berechnung von von Funktionsgraphen eingeschlossenen Flächen.

## Herleitung

Um sich dieser Fläche zu nähern, kann die Funktion $f$ in Abschnitte geteilt werden. Nun kann die Differenz $x$ mit dem Wert von $f$ in der Mitte des Abschnitts multipliziert werden. Um die gewünschte Näherung zu erhalten, müssen noch alle Abschnitte aufsummiert werden. Um die Präzision zu erhöhen, muss lediglich die Anzahl der Abschnitte im Verhältnis zur Größe des Intervalls vergrößert werden.

Für die größt mögliche Genauigkeit muss $\Delta x$ unendlich klein werden. Integralrechnung ist also auch [infinitesimal](Tangenten%20und%20Normalen.md#differenzierung).

## Darstellung

Ein Integral wird wie folgt dargestellt:

$$
\int_{a}^{b} f(x) dx
$$

- $a$ und $b$ beschreiben das Interval in dem der Integral errechnet werden soll. Sie heißen Integrationsgrenzen.
- $f(x)$ ist die Funktion, für die der integral errechnet werden soll. Sie heit Integrand
- $dx$ beschreibt die infinitesimal kleinen diferenzen auf der $x$-Achse, welche Summiert den Integral ergeben.

## Stammfunktionen

Ein relativ einfacher Weg einen Integral zu errechnen ist mittels einer Stammfunktion des Integranten. Eine Stammfunktion einer Funktion ist eine Funktion, deren erste Ableitung die Funktion ist, deren Stammfunktion gesucht wird.

Eine Stammfunktion einer Funktion wird häufig mit dem zur Funktion passenden Großbuchstaben gekennzeichnet. Eine Stammfunktion von $f$ wäre also $F$.

Um an eine Stammfunktion zu gelangen werden die [Ableitungsregeln](Ableitung.md) (sofern möglich) umgekehrt.

$f(x) = c \to f'(x) = 0$ ist nicht umkehrbar, weshalb $c$ nicht bekannt ist. $c$ ist jedoch für das Ausrechnen von Flächen nicht relevant, da es sich in der Berechnung selbst eliminiert.

## Berechnung mittels Stammfunktion

Gegeben ist:

$$
\int_{a}^{b}f(x)dx
$$

Um die Fläche im Interval $[a,b]$ zu errechnen wird zunächst die Stammfunktion $F(x)$ benötigt.  
Es gilt:

$$
\int_{a}^{b}f(x)dx = F(b)-F(a)
$$

### Integral zwischen Funktionen

Ist die Fläche zwischen zwei Funktionsgraphen ($f$ & $g$) gefragt anstelle der Fläche zwischen einem Funktionsgraphen und der $x$-Achse, wird etwas Vorbereitung gebraucht.  
Es gilt:

$$
Integral \ zwischen \ f \ und \ g = Integral_f-Integral_g
$$

Und:

$$
\int_{a}^{b}f(x)dx - \int_{a}^{b}g(x)dx = \int_{a}^{b}(f(x)-g(x))dx
$$

Von hier kann mit der Berechnung wie üblich verfahren werden.

### Beachtung von Nullstellen

Ist in der Aufgabe die zwischen zwei Graphen (oder Achsen) eingeschlossene Fläche gefragt, muss beachtet werden, dass Flächen, welche unter $0$ liegen, von den positiven Flächen abgezogen werden.

Um dies zu vermeiden, kann das Intervall an den Nullstellen der Funktion weiter geteilt werden und anschließend die Beträge der einzelnen Integrale summiert werden.
