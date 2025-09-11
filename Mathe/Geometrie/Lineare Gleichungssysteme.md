# Lineare Gleichungssysteme

## Beschreibung

> Ein lineares **Gleichungssystem** (kurz **LGS**) ist in der linearen Algebra eine Menge linearer Gleichungen mit einer oder mehreren Unbekannten, die alle gleichzeitig erfüllt sein sollen.
>
> — Wikipedia

Ein LGS ist also eine Gruppe von Gleichungen, die zeitgleich erfüllt sein sollrn.

Ein LGS mit $n$ Unbekannten und $m$ Gleichungen sieht wie folgt aus:

$$
\begin{matrix}
    a_{1,1} x_1 + a_{1,2} x_2 + &\dots& + a_{1,n} x_n &=& b_1 \\
    a_{2,1} x_1 + a_{2,2} x_2 + &\dots& + a_{2,n} x_n &=& b_2 \\
    &&&\vdots \\
    a_{m,1} x_1 + a_{m,2} x_2 + &\dots& + a_{m,n} x_n &=& b_m
\end{matrix}
$$

Ein LGS kann:

- Exakt eine Lösung haben.
- Unendlich viele Lösungen haben.
- Keine Lösung haben.

## Gauss Algorithmus

Um ein LGS zu lösen kann der Gauss Algorithmus angewand werden. Gegeben ist z.B. ein LGS mit drei Gleichungen und drei Unbekanten ($x_1;x_2;x_3$):

$$
\begin{matrix}
    a_{1,1} x_1& + &a_{1,2} x_2& + &a_{1,3} x_3 &= b_1 \\
    a_{2,1} x_1& + &a_{2,2} x_2& + &a_{2,3} x_3 &= b_2 \\
    a_{3,1} x_1& + &a_{3,2} x_2& + &a_{3,3} x_3 &= b_3
\end{matrix}
$$

Nun wird das LGS zunächst in eine Stufenform gebracht. Dies geschieht, in dem entsprechend gewählte Vielfache der ersten Zeile auf die Zweite und dritte Zeile addiert werden, um hier eine Unbekannte zu Elimineren.

$$
\begin{matrix}
    a_{1,1} x_1& + &a_{1,2} x_2& + &a_{1,3} x_3 &= b_1 \\
    && a_{2,2} x_2& + &a_{2,3} x_3 &= b_2 \\
    && a_{3,2} x_2& + &a_{3,3} x_3 &= b_3
\end{matrix}
$$

Nun wird die zweite auf die dritte Zeile so addiert, dass wieder eine Unbekannte eliminiert wird.

$$
\begin{matrix}
    a_{1,1} x_1& + &a_{1,2} x_2& + &a_{1,3} x_3 &= b_1 \\
    && a_{2,2} x_2& + &a_{2,3} x_3 &= b_2 \\
    &&&&a_{3,3} x_3 &= b_3
\end{matrix}
$$

Nun kann in der dritten Zeile der Wert der Unbekannten abgelesen werden, was es anschließend ermöglicht den wert der nächsten Unbekanten zu erschließen usw.
