# Vektoren

Vektoren haben eine Länge und eine Richtung. Sie werden haüfig als Pfeil dargestelt.

## Schreibweise

Ein Vektor wird meist mit einem Kleinbuchstaben (häufig $u$, $v$, $w$) unter einem Pfeil bennant und wie Folgt dargestellt:

$$
\overrightarrow{v} =
\begin{pmatrix}
    x_1 \\ x_2 \\ \vdots \\ x_n
\end{pmatrix}
$$

Vektoren zwischen zwei Punkten $A$ & $B$ werden so: $\overrightarrow{AB}$ benannt und heißen Verbindungsvektor. Die Reihenfolge der Buschstaben repräsnetiert hierbei die Richtung des Vektors ($A \to B$).  
Vektoren die vom Nullpunkt auf einen Punkt $A$ zeigen heißen Ortsvektoren und werden entweder so: $\overrightarrow{a}$, so: $\overrightarrow{A}$ oder so: $\overrightarrow{OA}$ benannt.

## Länge

Die Länge oder der Betrag eines Vektors wird wie folgt ermittelt:

$$
|\overrightarrow{v}| =
\begin{vmatrix}
\begin{pmatrix}
    x_1 \\ x_2 \\ \vdots \\ x_n
\end{pmatrix}
\end{vmatrix} =
\sqrt{(x_1)^2+(x_2)^2+\dots+(x_n)^2}
$$

## Rechnen

### Addition / Subtraktion

Vektoren können zu einander addiert und Subtrahiert werden. Dabei werden die einzelnen Dimensionen der Vektoren mit ihrem gegenstück addiert.

$$
\begin{matrix}
\overrightarrow{v} + \overrightarrow{w} =
\begin{pmatrix}
    v_1 \\ v_2 \\ \vdots \\ v_n
\end{pmatrix} +
\begin{pmatrix}
    w_1 \\ w_2 \\ \vdots \\ w_n
\end{pmatrix} =
\begin{pmatrix}
    v_1 + w_1 \\
    v_2 + w_2 \\
    \vdots \\
    v_n + w_n
\end{pmatrix} &&
\overrightarrow{v} - \overrightarrow{w} =
\begin{pmatrix}
    v_1 \\ v_2 \\ \vdots \\ v_n
\end{pmatrix} -
\begin{pmatrix}
    w_1 \\ w_2 \\ \vdots \\ w_n
\end{pmatrix} =
\begin{pmatrix}
    v_1 - w_1 \\
    v_2 - w_2 \\
    \vdots \\
    v_n - w_n
\end{pmatrix}
\end{matrix}
$$

Dies entspricht im Raum die einzelnen Vektorren nach einander auszuführen.  
Vektoren nur mit Vektoren addiert oder subtrahiert werden.

### Skalare Multiplikation

Ein Vektor kann um einen Skalar multipliziert werden. Hierbei werden die Einzelnen Dimensionen des Vektors um den Skalar multipliziert.

$$
s \cdot \overrightarrow{v} =
s \cdot
\begin{pmatrix}
    v_1 \\ v_2 \\ \vdots \\ v_n
\end{pmatrix} =
\begin{pmatrix}
    s \cdot v_1 \\
    s \cdot v_2 \\
    \vdots \\
    s \cdot v_n
\end{pmatrix}
$$

Die Länge des resultierenden Vektors entspricht $|s| \cdot |\overrightarrow{v}|$. Ist der Skalar positiv behält der Vektor seine Richtung, ist er negativ kehrt sich die Richtung um. Ist der Skalar $-1$ wird der resultierende Vektor Gegenvektor genannt.

### Skalarprodukt

Das Skalarprodukt wird durch $\circ$ dargestellt. Mit Hilfe des Sakalarprodukts kann der Winkel zwischen zwei Vektoren errechnet werden.
Das Skalarprodukt zweier Vektoren $\overrightarrow{a}$ & $\overrightarrow{b}$ läst sich wie folgt ermitteln:

$$
\overrightarrow{a} \circ \overrightarrow{b} =
\begin{pmatrix}
    a_1 \\ a_2 \\ \vdots \\ a_n
\end{pmatrix}
\circ
\begin{pmatrix}
    b_1 \\ b_2 \\ \vdots \\ b_n
\end{pmatrix} =
a_1 \cdot b_1 + a_2 \cdot b_2 + \dots + a_n \cdot b_n
$$

Sind die Vektoren orthogonal (im rechten winkel zu einander), ist das Skalarprodukt $0$.

$$
\overrightarrow{a} \bot \overrightarrow{b}
\Leftrightarrow
\overrightarrow{a} \circ \overrightarrow{b} = 0
$$

Um andernfals den Winkel $\varphi$ zwischen den Vektoren zu ermitteln gilt:

$$
\begin{matrix}
cos(\varphi) = \frac
{\overrightarrow{a} \circ \overrightarrow{b}}
{|\overrightarrow{a}| \cdot |\overrightarrow{b}|}
\\
\implies
\varphi = arccos
\begin{pmatrix}
\frac
{\overrightarrow{a} \circ \overrightarrow{b}}
{|\overrightarrow{a}| \cdot |\overrightarrow{b}|}
\end{pmatrix}
\end{matrix}
$$

### Kreuzprodukt

Das Kreuzprodukt wird durch $\times$ dargestellt. Das Kreuzprodukt zweier Vektoren ist ein Vektor der im orthogonal zu beiden Vektoren ist.  
In einem dreidimensionalen Koordinatensystem gilt:

$$
\overrightarrow{a} \times \overrightarrow{b} =
\begin{pmatrix}
    a_1 \\ a_2 \\ a_3
\end{pmatrix}
\times
\begin{pmatrix}
    b_1 \\ b_2 \\ b_3
\end{pmatrix} =
\begin{pmatrix}
    a_2 \cdot b_3 - a_3 \cdot b_2 \\
    a_3 \cdot b_1 - a_1 \cdot b_3 \\
    a_1 \cdot b_2 - a_2 \cdot b_1
\end{pmatrix}
$$

Das Kreuzprodukt ist nütlich um Normalen von Ebenen zu erzeugen.

## Lineare Abhängigkeit

Zwei Vektoren sind linear abhägig von einander, wenn sie als produkt skalarer multiplikation des anderen Vektors dargestellt werden können.

$$
\overrightarrow{a} =
s \cdot \overrightarrow{b}
\Leftrightarrow
\overrightarrow{a} \parallel \overrightarrow{b}
$$

Wobei gilt: $s \in \mathbb{R}$

Umgekehrt sind Vektoren linear unabhängig von einander wenn dies nicht der Fall ist.

$$
\overrightarrow{a} \neq
s \cdot \overrightarrow{b}
\Leftrightarrow
\overrightarrow{a} \nparallel \overrightarrow{b}
$$

Lineare abhägigkeit bedeutet, die Richtung der Vektoren ist identisch.
