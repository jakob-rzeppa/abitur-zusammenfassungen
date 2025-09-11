# Maße

## Häufigkeit

### Absolute Häufigkeit

Die absolute Häufigkeit beschreibt wie häufig ein Ereigniss in absoluten Zahlen eingetreten ist.

> Das Ziel wurde 10-mal getroffen.

Sie wird üblicherweise mit $H$ gekenzeichnet.

### Relative Häufigkeit

Die relative Häufigkeit $h$ beschreibt die absolute Häufigkeit $H$ im Verhältniss zur gesmmt Zahl der Ereignisse $N$.

$$
h_n(A) = \frac{H(A)}{N}
$$

> Das Ziel wurde in 20 Versuchen 10-mal getroffen.

Die Relative Häufigkeit entspricht der Wahrscheinlichkeit eines Ereignisses.

## Erwartungswert

Der Erwartungswert $\mu$ entspricht der Summe aller Ereignisswerte $x_i$ mal ihrer Wahrscheinlichkeit $P(x_i)$.

$$
\mu = \sum_{i = 1}^{n} x_i \cdot P(x_i)
$$

$$
\mu = \frac
{x_1 \cdot H_1 + x_2 \cdot H_2 + \dots + x_n \cdot H_n}
{N}
$$

Der Erwartungswert ist für Glücksspiel relevant, da er bestimmt ob ein Spiel im schnitt profitabel ist. Ist der Erwartungswert höher als der Einsatz, verliert das Haus und die Spieler gewinnen, ist er niedriger verlieren die Spieler und das Haus gewinnt.

## Streuung

Die Streuung eines Zufallsexperimente ist die Abweichung der beobachteten ereignisse vom Erwartungswert.

### Varianz

Die Varianz $\sigma^2$ ist die mittlere quadratische Abweichung vom Erwartungswert $\mu$.

$$
\sigma^2 = \sum_{i=1}^{n} (x_1-\mu)^2 \cdot P(x_i)
$$

- $P(x_i)$ ist die Wahrscheinlichkeit mit der ein Ereigniss eintritt
- $(x_1-\mu)$ ist die Differenz zwischen einem Ereigniss und dem Erwartungswert.
- Geht $\sigma^2$ gegen $0$, konzentriert sich die Verteilung um den Erwartungswert.

### Standartabweichung

Die Standartabweichung $\sigma$ ist die Wurzel der Varianz.

$$
\sigma = \sqrt{
    \sum_{i=1}^{n} (x_i-\mu)^{2} \cdot P(x_i)
}
$$

$$
\sigma = \sqrt{
    (x_1-\mu)^{2} \cdot P(x_1) + (x_2-\mu)^{2} \cdot P(x_2) + \dots + (x_n-\mu)^{2} \cdot P(x_n)
}
$$

Sind alle Ereignisse gleich wahrscheinlich, dann gilt:

$$
\sigma = \sqrt{
    \frac{1}{n}
    \sum_{i=1}^{n} (x_i-\mu)^{2}
}
$$

Die Standartabweichung ist nicht die mittlere absolute Abweichung.
