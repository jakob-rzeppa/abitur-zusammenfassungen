# Graden

> Eine **gerade Linie** oder kurz **Gerade** ist ein Objekt der Geometrie. Sie ist eine gerade, unendlich lange, unendlich dünne und in beide Richtungen unbegrenzte Linie. — Wikipedia

Es gibt verschiedene Darstellungsformen einer Graden. Diese sind für unterschiedliche Probleme geeignet.

## Formen

### Parameterform

$$
\overrightarrow{x} =
\overrightarrow{a} +
s \cdot \overrightarrow{u};
$$

- $\overrightarrow{a}$ ist der Stützvektor
- $\overrightarrow{u}$ ist der Richtungsvektor
- $s \in \mathbb{R}; \overrightarrow{u} \neq 0$
- Jeder Wert von $s$ Erzeugt einen Vektor der auf einen Punkt auf der Grade zeigt.

## Lage zu einander

Gegeben sind:

$$
\overrightarrow{g} = \overrightarrow{a} + s \cdot \overrightarrow{v}
$$

$$
\overrightarrow{h} = \overrightarrow{b} + r \cdot \overrightarrow{w}
$$

### Schneident

Ist $\overrightarrow{g} = \overrightarrow{h}$ mit einer Kombination aus $s$- und $r$-Werten Wahr, dann schneiden sich die Graden an diesem Punkt mit Ortsvektor $\overrightarrow{p}$.

$$
\overrightarrow{a} + s_0 \cdot \overrightarrow{v} = \overrightarrow{b} + r_0 \cdot \overrightarrow{w} \implies \overrightarrow{p} = \overrightarrow{a} + s_0 \cdot \overrightarrow{v}
$$

### Parallel

Ist $\overrightarrow{v} = r \cdot \overrightarrow{w}$ mit einem belibigen $r$-Wert Wahr, dann sind die Graden parrallel.

$$
\overrightarrow{a} = r_0 \cdot \overrightarrow{w} \implies \overrightarrow{g} \parallel \overrightarrow{h}
$$

**Echt** parallel bedeutet, dass zwei graden parallel sind und sich explizit nicht schneiden.

### Indentisch

Sind die Graden parallel und schneiden sich, dann sind die Graden identisch.

$$
\overrightarrow{g} \parallel \overrightarrow{h} \wedge
\overrightarrow{a} = \overrightarrow{b} + r_0 \cdot \overrightarrow{w}
\implies \overrightarrow{g} \equiv \overrightarrow{h}
$$

### Windschief

Sind die Graden weder parallel, noch schneident, sind sie windschief.
