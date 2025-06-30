# Tangenten und Normalen

## Beschreibung

Eine **Tangente** ist eine Grade, die einen Graphen an einer Stelle berührt und an dieser der Steigung des Graphen entspricht. Eine Tangente schneidet den Graphen nicht an diesem Punkt, solange es sich nicht um einen Sattelpunkt handelt.

Eine **Normale** ist eine Grade, die einen Graphen an einer Stelle schneidet. Sie steht dabei in einem rechten Winkel zur Tangente des Punktes.

## Differenzierung

Da Steigung $\frac{\Delta y}{\Delta x}$ ist und $\Delta x$ in einem Punkt $0$ ist, kann die Steigung in einem Punkt nicht errechnet werden. Es kann sich ihr jedoch angenähert werden.  
Wenn $\Delta x$ gegen $0$ geht und $\frac{\Delta y}{\Delta x}$ gegen eine Zahl geht, handelt es sich bei dieser um die Steigung im Punkt.

Diese Form der Rechnung nennt sich Infinitesimalrechnung. Um dies zu signalisieren, wird $\Delta$ durch $d$ ersetzt. Die Tangentensteigung in dem Punkt ist also $\frac{dy}{dx}$.

## Funktionen

### Tangenten

Eine Tangente ist eine Grade, die einem Funktionsgraphen an einer Stelle anliegt und seiner Steigung an dieser entspricht.

Die Funktion einer Tangente $g$ an der Stelle $x_0$ der Funktion $f$ lässt sich also wie folgt erschließen:

$$
g(x) = f(x_0) + f'(x_0) (x - x_0)
$$

Der Wert $g(x)$ entspricht somit dem Wert $f(x)$ an der Stelle $x_0$ plus dem Wert der Steigung von $f$ an der Stelle $x_0$ mal der Differenz von $x$ und $x_0$.

Umgestellt ergibt das:

$$
g(x) = f(x_0) - f'(x_0) \cdot x_0 + f'(x_0) \cdot x
$$

Wobei $f(x_0) - x_0 \cdot f'(x_0)$ konstant ist und somit zu einer Zahl wird.

### Normalen

Eine Normale ist eine Grade, die den Graphen an einer Stelle schneidet und in einem rechten Winkel zur Tangente dieses Punktes steht. Dies ist der Fall, wenn:

$$
Steigung_{Tangente} \cdot Steigung_{Normale} = -1
$$

$$
\implies Steigung_{Normale} = \frac{-1}{Steigung_{Tangente}}
$$

Dem entsprechend ist die Funktion der Normale $g$ an der Stelle $x_0$:

$$
g(x) = f(x_0) + \frac{-1}{f'(x_0)} (x - x_0)
$$

Oder:

$$
g(x) = f(x_0) - \frac{-1}{f'(x_0)} x_0 + \frac{-1}{f'(x_0)} x
$$
