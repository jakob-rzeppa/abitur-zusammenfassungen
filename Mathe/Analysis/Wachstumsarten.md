# Wachstumsarten

## Exponentielles Wachstum

Wachstum ist exponentiell, wenn es vom aktuellen Funktionswert abhängt. Es ist proportional zum Funktionswert. Der Graph bildet eine Kurve, die gegen $0$ oder $\infty$ geht.

$$
f'(x) = k \cdot f(x)
$$

$$
f(x) = f(0) \cdot e^{k \cdot x}
$$

### Halbwertszeit / Verdopplungszeit

Die Halbwerts zeit, ist die Zeit (Strecke auf der $x$-Achse) die eine Expotenzielle Abnahme braucht, um ihren Wert zu halbieren. Die Verdopplungszeit ist das Gegenstück für expotentialle Zunahmen, hier ist es die Zeit bis sich der Wert verdppelt hat.

## Begrentztes Wachstum

Begrenztes Wachstum ist proportional zur Differenz des Funktions- und Sättigungswerts. Der Graph bildet eine Kurve, welche sich dem Sättigungswert annähert.

$$
f'(x) = k \cdot (S-f(x))
$$

Funktionen mit begrenztem Wachstum, haben folgende Form:

$$
f(x) = S-(S-f(0))e^{-k \cdot x}
$$

Hier gilt:

- $S$ ist der Sättigungswert
- $f(0)$ ist der Startwert
- $k$ ist die Proportionalitätskonstante zwischen Funktionswert und Steigung

## Logistisches Wachstum

Das logistische Wachstum ist proportional zu sowohl dem Funktionswert als auch der Differenz zum Grenzwert. Der Graph nähert sich bei $x \to -\infty$ $0$ und bei $x \to \infty$ dem Grenzwert.

$$
f'(x) = k \cdot f(x) \cdot (G-f(x))
$$

Funktionen mit logistischem Wachstum, haben folgende Form:

$$
f(x) = G \cdot
\frac{1}{
    1 + e^{ - k \cdot G \cdot x } ( \frac{ G }{ f(0) } - 1)
}
$$

$$
f(x) =
G \cdot
\frac{1}{
    1 + e^{-kGx}\frac{G}{f(0)} - e^{-kGx}
}
$$

Hier gilt:

- $G$ ist der Grenzwert
- $f(0)$ ist der Startwert
- $k$ ist die Proportionalitätskonstante zwischen Funktionswert und Steigung
