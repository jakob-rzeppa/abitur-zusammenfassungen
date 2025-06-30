# Ableitung

## Beschreibung

Die Ableitung einer Funktion ist die Funktion, welche an jeder Stelle der Tangentensteigung ihrer Grundfunktion entspricht.

## Grundfunktionen

### Konstante Funktion

$$
f(x) = c \wedge c \in \mathbb{R} \implies f'(x) = 0
$$

### Potenzfunktion

$$
f(x) = x^r \wedge r \in \mathbb{R} \implies f'(x) = r \cdot x^{r-1}
$$

### Exponentialfunktion

$$
f(x) = b^x \implies f'(x) = ln(b) \cdot b^x
$$

### Logarithmus

$$
f(x) = log_b(x) \implies f'(x) = \frac{1}{x \cdot ln(b)}
$$

### Sinus Kosinus

$$
f(x) = sin(x) \implies f'(x) = cos(x) \implies
f''(x) = -sin(x) \implies f'''(x) = -cos(x) \implies
f''''(x) = sin(x)
$$

## Ableitungsregeln

### Faktorregel

$$
f(x) = a \cdot g(x) \wedge a \in \mathbb{R} \implies f'(x) = a \cdot g'(x)
$$

### Summenregel

$$
f(x) = g(x) + h(x) \implies f'(x) = g'(x) + h'(x)
$$

### Produktregel

$$
f(x) = g(x) \cdot h(x) \implies
f'(x) = g'(x) \cdot h(x) + h'(x) \cdot g(x)
$$

### Kettenregel

$$
f(x) = g(h(x)) \implies f'(x) = g'(h(x)) \cdot h'(x)
$$

## Beispiele

### E-Funktion

Gegeben ist $f(x) = a \cdot e^{x \cdot b}$. Um die Ableitung $f'$ zu finden, teilen wir $f$ zunächst in innere und äußere Funktion, anschließend wenden wir die Kettenregel an.

$$
f(x) = a \cdot e^{x \cdot b} = f_1(f_2(x))
$$

$$
f_1(x) = a \cdot e^x
$$

$$
f_2(x) = x \cdot b
$$

$$
\implies f'(x) = f_1'(f_2(x)) \cdot f_2'(x)
$$

$$
f_1'(x) = ln(e) \cdot a \cdot e^x = a \cdot e^x
$$

$$
f_2'(x) = x^0 \cdot b = b
$$

$$
\implies f'(x) = b \cdot a \cdot e^{x \cdot b}
$$

Die Ableitung von $a \cdot e^{x \cdot b}$ ist also $a \cdot b \cdot e^{x \cdot b}$.
