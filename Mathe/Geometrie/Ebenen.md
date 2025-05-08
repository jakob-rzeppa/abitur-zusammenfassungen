# Ebenen

> Die Ebene ist ein Grundbegriff der Geometrie. Allgemein handelt es sich um ein unbegrenzt ausgedehntes flaches zweidimensionales Objekt.
>
> - Hierbei bedeutet unbegrenzt ausgedehnt und flach, dass zu je zwei Punkten auch eine durch diese verlaufende Gerade vollständig in der Ebene liegt.
> - Zweidimensional bedeutet, dass – abgesehen von enthaltenen Geraden – kein echter Teilraum ebenfalls diese Eigenschaft hat.
>
> — Wikipedia

Ebenen im dreidimensionalen Raum können mit verschiedenen Gleichungsformen repräsentiert werden.

## Formen

### Parameterform

Ähnlich zu Parameterform der Graden, jedoch mit einem weiteren, linear vom ersten unabhägien, Richtungsvektor.

$$
\overrightarrow{x} = \overrightarrow{a} + r \cdot \overrightarrow{v} + s \cdot \overrightarrow{w}
$$

- $\overrightarrow{a}$ ist der Stützvektor
- $\overrightarrow{v}$ und $\overrightarrow{w}$ sind die Stützvektoren, Sie müssen linearunabhängig sein
- $r$ und $s$ sind die Skalare, sie können belibige werte $\in \mathbb{R}$ annehmen und so einen Punkt in der Fläche erzeugen.
- $\overrightarrow{v} \neq 0; \overrightarrow{w} \neq 0$

### Normalenform

$$
(\overrightarrow{x} - \overrightarrow{p}) \circ \overrightarrow{n} =
\overrightarrow{x} \circ \overrightarrow{n} - \overrightarrow{p} \circ \overrightarrow{n} = 0
$$

- $\overrightarrow{x}$ ist der Ortsvektor eines Punktes in der Ebene
- $\overrightarrow{p}$ ist der Stützvektor
- $\overrightarrow{n}$ ist ein Normalenvektor, er ist also orthogonal zur Ebene.

Nachdem der Stützvektor vom Ortsvektor abgezogen wurde, ist der Resultieren Vektor parallel zur Fläche wenn der Punkt in der Ebene liegt.  
Das Skalarprodukt diese Vektors und des Normalenvektors ist also Null wenn der Punkt in der Ebene ist.

### Koordinatenform

$$
a \cdot x + b \cdot y + c \cdot z = d
$$

- $x;y;z$ sind die Koordinaten eines Punktes
- Ist die Gleichung wahr, liegt der Punkt in der Ebene.

## Umformung

### Normalenform $\leftrightarrow$ Koordinaten Form

Die Koordiantenform können leicht in einander umgestellt werden.

Die Normalenform:

$$
\overrightarrow{x} \circ \overrightarrow{n} - \overrightarrow{a} \circ \overrightarrow{n} = \overrightarrow{x} \circ \overrightarrow{n} - d = 0
$$

Das Skalarprodukt kann umgeschrieben werden:

$$
n_1 \cdot x_1 + n_2 \cdot x_2 + n_3 \cdot x_3 - d = 0
$$

$$
n_1 \cdot x_1 + n_2 \cdot x_2 + n_3 \cdot x_3 = d
$$

Die Koordinatenform kann umgekehrt auch in die Normalenform umgeformt werden.

$$
n_1 \cdot x_1 + n_2 \cdot x_2 + n_3 \cdot x_3 = d
$$

$$
\to \overrightarrow{a} \circ \overrightarrow{n} = d
$$

Nun muss nuch eine Lösung für $\overrightarrow{p} \circ \overrightarrow{n} = d$ gefunden werden, dann:

$$
\overrightarrow{x} \circ \overrightarrow{n} = \overrightarrow{p} \circ \overrightarrow{n}
$$

$$
\overrightarrow{x} \circ \overrightarrow{n} - \overrightarrow{p} \circ \overrightarrow{n} = 0
$$

### Parameterform $\to$ Normalenform

Um die Parameterform in die Normalenform umzuwandeln wird eine Normal gebraucht. Eine möglichkeit ist über das Kreuzprodukt:

$$
\overrightarrow{v} \times \overrightarrow{w} = \overrightarrow{n}
$$

ein anderer über ein Lineares Gleichungssystem:

$$
\begin{matrix}
    \overrightarrow{v} \circ \overrightarrow{n} =
    v_1 \cdot n_1 + v_2 \cdot n_2 + v_3 \cdot n_3 = 0\\
    \overrightarrow{w} \circ \overrightarrow{n} =
    w_1 \cdot n_1 + w_2 \cdot n_2 + w_3 \cdot n_3 = 0
\end{matrix}
$$

Dieses hat Unendlich viele Lösungen es wird nur eine benötigt. Wobei $n \neq 0$ gilt.

Der Stützvektor kann einfach übernommen werden.

$$
\overrightarrow{x} = \overrightarrow{a} + r \cdot \overrightarrow{v} + s \cdot \overrightarrow{w} \to
(\overrightarrow{x}-\overrightarrow{a}) \circ (\overrightarrow{v} \times \overrightarrow{w}) = 0
$$

### Normalenform $\to$ Parameterform

Der Stützvektor wird Übernommen.

Die Richtungs Vektoren können so gewählt werden, das

$$
\begin{matrix}
    \overrightarrow{v} \circ \overrightarrow{n} =
    v_1 \cdot n_1 + v_2 \cdot n_2 + v_3 \cdot n_3 = 0\\
    \overrightarrow{w} \circ \overrightarrow{n} =
    w_1 \cdot n_1 + w_2 \cdot n_2 + w_3 \cdot n_3 = 0
\end{matrix}
$$

gilt. Es mus lediglich darauf geachtet werden, dass die Vektoren nicht linear abhängig sind.

## Lage

### Lage zu Graden

$$
\overrightarrow{a} + s_g \cdot \overrightarrow{v} = \overrightarrow{b} + s_e \cdot \overrightarrow{w} + r \cdot \overrightarrow{u}
$$

Gibt es hier für

- genau eine Lösung, scheiden sich Grade und Ebene
- keine Lösung, sind Grade und Ebene parallel
- unendlich viele Lösungen, liegt die grade in der Flache.

#### Schnittwinkel Grade

Der Schnittwinkel zwischen einer Grade und einer Ebene, entspricht $90°$/$\frac{1}{2}\pi$ minus dem Winkel zwischen der Normale der Fläche und dem Richtungs Vektors der Grade.

### Lage zu einander

$$
\overrightarrow{a}_1 + s_1 \cdot \overrightarrow{v}_1 + r_1 \cdot \overrightarrow{w}_1 = \overrightarrow{a}_2 + s_2 \cdot \overrightarrow{v}_2 + r_2 \cdot \overrightarrow{w}_2
$$

Hat diese Gleichung

- unendlich viele Lösungen ohne jedoch frei wählbaren Parameter zu haben, schneiden sich die ebenen in eier Schnittgrade.
- keine Lösung, dann sind die Graden Parallel.
- unendlich viele Lösungen mit frei wählbaren Parametern, sind die Flächen identisch.

#### Schnittwinkel Ebene

Der Schnittwinkel zwischen zwei Flächen entspricht dem Winkel zwischen ihren Normalen.
