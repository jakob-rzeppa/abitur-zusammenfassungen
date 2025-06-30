# Kurvendiskusion

## Monotonie

Monotonie beschreibt die Steigung eines Graphen. Ein Graph oder Abschnitt eines Graphen, der konstant steigt, ist streng monoton steigend. Selbiges gilt für fallende Graphen oder Abschnitte, diese fallen streng monoton.

Dabei ist nicht relevant, wie stark die Steigung oder der Fall ist, sondern nur ob der Graph steigt oder fällt.  
Enthält der Graph auch Stellen mit einer Steigung von $0$, ist er dennoch monoton, solange er keine negative und positive Steigung enthält, er ist dann jedoch nicht mehr streng monoton.

Die Bedingung für Monotonie sind also:

|              | streng      | nicht streng   |
| ------------ | ----------- | -------------- |
| **Steigung** | $f'(x) > 0$ | $f'(x) \geq 0$ |
| **Fall**     | $f'(x) < 0$ | $f'(x) \leq 0$ |

Ein Graph kann in einem Abschnitt monoton Steigen und in einem anderen monoton fallen.

## Extrem- und Sattelstellen

Extrem- und Sattelstellen sind Stellen, an denen ein Graph eine Steigung von $0$ hat.

$$
f'(x) = 0
$$

- Wechselt die Steigung von $-$ zu $+$, handelt es sich um eine Tiefstelle.  
  Die Bedingungen für eine Tiefstelle sind also:

$$
f'(x) = 0 \wedge f''(x) > 0
$$

- Wechselt die Steigung von $+$ zu $-$ handelt sie sich um eine Hochstelle.  
  Die Bedingungen für eine Hochstelle sind also:

$$
f'(x) = 0 \wedge f''(x) < 0
$$

- Wechselt die Steigung nicht das Vorzeichen, handelt es sich um eine Sattelstelle.\
  Die Bedingungen für eine Sattelstelle sind also:

$$
f'(x) = 0 \wedge f''(x) = 0 \wedge f'''(x) \neq 0
$$

## Wendestellen

Wendestellen sind Stellen, an denen der Funktionsgraph seine Krümmung wechselt. Es handelt sich um Extremstellen in der 1. Ableitung. Es gelten also folgende Bedingungen:

$$
f''(x) = 0 \wedge f'''(x) \neq 0
$$

Auch Sattelstellen sind daher Wendestellen.
